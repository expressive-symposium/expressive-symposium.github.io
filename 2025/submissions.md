---
layout: submission
title: ACM/EG Expressive 2025 — Call for Submissions
excerpt: "Submit your work to Expressive 2019"
image:
  card: 2025/expressiveCard.jpg
year: 2025
---

The _Expressive_ symposium explores the capacity of computer graphics, animation, and computational media to be used in artistic, aesthetic, and creative ways. The field can be seen as encompassing problems in expressive __understanding__, expressive __communication__, and expressive __interaction__:

* Expressive __understanding__ integrates aspects of computer science, philosophy, psychology, and the fine, applied, and performing arts, investigating theoretical approaches that further our understanding of aesthetic evaluation, perception and meaning.

* Expressive __communication__ focuses on imagery and motion which is expressive rather than photorealistic, although it may incorporate realistic elements.

* Expressive __interaction__ explores models, algorithms, and technologies for sketch-based and XR interfaces, particularly classifying and recognizing hand-drawn shapes as a way to create or edit digital models, text, mathematics, or 3D shapes.

[Expressive 2025](http://expressive.graphics/2025/) will take place in London, UK, on May 12th 2025 - co-located with [Eurographics 2025](https://eg25.cs.ucl.ac.uk/main/home.html). The symposium will also include an arts program, posters, and demos.

{::options parse_block_html="true" /}
<a href="#call-for-papers--expressive" class="bold"> > Call for Papers - Expressive</a><br>
<a href="/2025/wiced/#call-for-papers--wiced-2025" class="bold"> > Call for Papers – WICED 2025</a><br>
<a href="#call-for-posters-and-demos" class="bold"> > Call for Posters and Demos</a><br>
<!-- <a href="#call-for-artworks--generative-chronicles" class="bold"> > Call for Artworks</a><br> -->
<!-- <a href="#call-for-journal-presentations" class="bold"> > Call for Journal Presentations</a> -->
{::options parse_block_html="false" /}

---

## Call for Papers – EXPRESSIVE
{: .top2}

<!-- [<span class="glyphicon glyphicon-file"></span> Call for Papers (PDF)](/docs/expressive-2019-call-for-papers-v04.pdf) -->

{::options parse_block_html="true" /}

<div class="panel panel-warning">
#### Important dates
{: .panel-heading}
<div class="panel-body">

{% capture nowtime %}{{'now' | date: '%s'}}{% endcapture %}{% capture nowtime %}{{'now' | date: '%s'}}{% endcapture %}
{% capture abstractduetime %}{{site.symposium[page.year].abstract | date: '%s'}}{% endcapture %}
{% capture paperduetime %}{{site.symposium[page.year].paper | date: '%s'}}{% endcapture %}
{% capture extensionduetime %}{{site.symposium[page.year].extension | date: '%s'}}{% endcapture %}
{% capture acceptanceduetime %}{{site.symposium[page.year].acceptance | date: '%s'}}{% endcapture %}
{% capture firstreviewnotificationduetime %}{{site.symposium[page.year].first-review-notification | date: '%s'}}{% endcapture %}
{% capture revisedsubmissionduetime %}{{site.symposium[page.year].revised-submission | date: '%s'}}{% endcapture %}
{% capture secondreviewnotificationduetime %}{{site.symposium[page.year].second-review-notification | date: '%s'}}{% endcapture %}
{% capture camerareadyduetime %}{{site.symposium[page.year].camera-ready | date: '%s'}}{% endcapture %}

{% if site.symposium[page.year] contains 'abstract' %}| __Abstract due:__ {% if abstractduetime < nowtime %}~~{% endif %}{{ site.symposium[page.year].abstract }}{% if abstractduetime < nowtime %}~~{% endif %} |{% endif %}
| __Paper submission deadline:__ {% if paperduetime < nowtime %}~~{% endif %}{{ site.symposium[page.year].paper }}{% if paperduetime < nowtime %}~~{% endif %} |
{% if site.symposium[page.year] contains 'extension' %}| __Extended full paper deadline:__ {% if extensionduetime < nowtime %}~~{% endif %}**{{ site.symposium[page.year].extension }}**{% if extensionduetime < nowtime %}~~{% endif %} |{% endif %}
{% if site.symposium[page.year] contains 'extention-poster-demo' %}| __Extended posters and demos deadline:__ {% if extentionposterdemoduetime < nowtime %}~~{% endif %}**{{ site.symposium[page.year].extention-poster-demo }}**{% if xtentionposterdemoduetime < nowtime %}~~{% endif %} |{% endif %}
| __First review notification (Possible outcomes: Conditionally accepted as a journal paper, Accepted as a conference paper, Reject):__ {% if firstreviewnotificationduetime < nowtime %}~~{% endif %}{{ site.symposium[page.year].first-review-notification }}{% if firstreviewnotificationduetime < nowtime %}~~{% endif %} |
| __Revised paper submission deadline (for Conditionally accepted journal papers):__ {% if revisedsubmissionduetime < nowtime %}~~{% endif %}{{ site.symposium[page.year].revised-submission }}{% if revisedsubmissionduetime < nowtime %}~~{% endif %} |
| __Second review notification:__ {% if secondreviewnotificationduetime < nowtime %}~~{% endif %}{{ site.symposium[page.year].second-review-notification }}{% if secondreviewnotificationduetime < nowtime %}~~{% endif %} |
{% if site.symposium[page.year] contains 'camera-ready' %}| __Camera-ready submission:__ {% if camerareadyduetime < nowtime %}~~{% endif %}{{ site.symposium[page.year].camera-ready }}{% if camerareadyduetime < nowtime %}~~{% endif %} |{% endif %}
| |
| All deadlines are at 23:59:59 UTC/GMT |

</div>
</div>

### Submission Types
{: .top1}

Paper submissions are invited across the broad range of areas covered by Expressive. We welcome papers in several categories:

* __Research:__ New algorithms, scientific studies, analysis, or data (i.e., traditional academic papers). Research papers must contain novel results that substantially contribute to the field.
* __Production:__ Candid discussion of the process of creating a work (e.g., film, image, game) or developing a tool (e.g., paint or CAD program, software library). We are equally interested in papers on the use of existing techniques combined in novel ways, or their application in a new or unusual context.
* __Creative:__ Descriptions of original creative projects or analyses of expressive techniques used in artworks, performances, or computational design projects. Creative papers should highlight artistic innovation, and we encourage artists submitting to the Expressive 2025 Art Exhibition to also submit a creative paper describing their project.

* __Meta:__ Statements about research that do not contain new results, e.g.: grand challenges, position papers, evaluation standards, surveys, and primers on art / aesthetics / psychophysics for a computer science audience. We welcome papers that discuss the challenges of bridging computational expression across disciplines.

Submissions can also overlap more than one of these categories. 

At Expressive 2025, the Technical Papers program will have two integrated paper tracks: Journal (Elsevier Computers & Graphics) and Conference. 



<!--Eurographics will publish the accepted papers as a single conference proceedings and make them available online via  [Eurographics Digital Library](https://diglib.eg.org/). They will also be archived in the [ACM Digital Library](http://dl.acm.org/). 

**Authors of selected papers will be invited to submit extended versions of their manuscripts to be considered for publication in a special section of [Computers & Graphics](https://www.journals.elsevier.com/computers-and-graphics/) journal (Elsevier) via a fast-track review process.** !-->

### Submission Topics
{: .top1}

Topics include, but are not limited to:

* Analysis and modelling of creative behaviour (AI, A-life)
* Simulation of natural media, traditional styles, and novel artistic styles
* Analysis of image style and saliency (paintings, photographs, others)
* Visualisation techniques, Simplification and Aabstraction techniques (e.g., sketching, indication) 
* Empirically-based metrics of aesthetic attributes
* Applied visual perception
* Interaction techniques (e.g. sketch, gestural, multi-touch, multi-modal, XR)
* Sketch-parsing, classification and recognition
* Novel interfaces for art creation, modelling, control, sketch input
* Study designs and methodologies for evaluating and validating sketch-based systems, aesthetic metrics, visual communication systems
* Advanced rendering techniques (e.g. volumetric, GPU, mobile, multi-modal)
* Applications in special domains, e.g.,  Medicine, Geology, Biology, Sociology, Cultural Heritage
* Sketch-based information retrieval
* Stylistic or aesthetic aspects of character animation and simulated physics
* Accounts of real productions (e.g., animated films, digital art) or applications in software products (e.g., modelling, visualisation, presentation software)
* Visual composition design, rendering, and evaluation of layouts for text and presentation graphics
* Example-based style transfer
* Deep learning and neural networks for expressive rendering (e.g. neural style transfer)
* Temporal and spatial coherence
* Aesthetic evaluation and stylistic rendering of visual effects such as motion blur, depth of field, and lighting
* Non-traditional camera models
* Generative Adversarial Networks (GANs)
* AI-assisted modeling, animation, and generation of 2D/3D content
* AI-enhanced visual effects and generative art


### Submission Information
{: .top1}
The papers can be submitted through:

* [Elsevier Computers and Graphics submission portal](https://www.editorialmanager.com/cag/default.aspx) (Note: please select VSI: Expressive Media 2025.)

    After reviews, the best papers will be retained for publication in the C&G journal, while other high-quality papers that do not reach the C&G bar will be redirected to the conference paper track. The submitted papers must be anonymous and formatted according to either the C&G guidelines or the EG guidelines (see below). There is no strict page limit, but the length should justify the contribution. 
* [SRM submission system](https://srmv2.eg.org/COMFy/Conference/Expressive_WICED_2025) 

    The papers submitted through SRM will only be considered for the conference track. The conference proceedings will be made available online via  Eurographics Digital Library. They will also be archived in the  ACM Digital Library. The submitted papers must be anonymous and formatted in the template given [here](https://srmv2.eg.org/COMFy/Conference/Expressive_WICED_2025/GetConferenceFile?fileID=17039).

If you have any questions, please feel welcome to contact the Program chairs, Chiara Eva Catalano and Amal Dev Parakkat, at [{{site.symposium[page.year].contact}}](mailto:{{site.symposium[page.year].contact}})

<!--Submissions will be made electronically through the Eurographics Submission and Review Management [SRM]({{site.symposium[2025].submission}}) system. Submitted papers must be anonymous and formatted according to the Eurographics [Author’s guidelines](http://expressive.graphics/2025/instructions/). There is no strict page limit, but the length should justify the contribution. If you have any questions, please feel welcome to contact the Program chairs Chiara Eva Catalano and Amal Dev Parakkat at general@expressive.graphics . !-->

---

## Call for Posters and Demos
{: .top2}

<!-- [<span class="glyphicon glyphicon-file"></span> Call for Posters and Demos (PDF)](/docs/expressive-2019-call-for-posters-demos-v02.pdf) -->

{::options parse_block_html="true" /}

<div class="panel panel-warning">
#### Important dates
{: .panel-heading}
<div class="panel-body">

{% capture nowtime %}{{'now' | date: '%s'}}{% endcapture %}{% capture nowtime %}{{'now' | date: '%s'}}{% endcapture %}
{% capture generalposterdemosubmissionduetime %}{{site.symposium[page.year].general-poster-demo-submission | date: '%s'}}{% endcapture %}

| __Poster/Demos submission deadline:__ Rolling notification, closes {% if generalposterdemosubmissionduetime < nowtime %}~~{% endif %}{{ site.symposium[page.year].general-poster-demo-submission }}{% if generalposterdemosubmissionduetime < nowtime %}~~{% endif %} |
{% if site.symposium[page.year] contains 'extention-poster-demo' %}| __Extended posters and demos deadline:__ {% if extentionposterdemoduetime < nowtime %}~~{% endif %}**{{ site.symposium[page.year].extention-poster-demo }}**{% if xtentionposterdemoduetime < nowtime %}~~{% endif %} |{% endif %}
| |
| All deadlines are at 23:59:59 UTC/GMT |

</div>
</div>

{::options parse_block_html="false" /}

Expressive 2025 will host an exhibition for artworks, posters, and demonstration projects, where artistic pieces, computational demonstrations, and posters will be featured side-by-side. This category focuses on recent research and creative activities at the intersection of arts and sciences. We are open to any work and research related to the Expressive 2025 conference topics. The authors of accepted works will be invited to present their work (as posters or interactive demo sessions) through a panel discussion at the main Expressive 2025 conference. Accepted works will be archived through the [Eurographics Digital Library](https://diglib.eg.org/)and will be made available in the [ACM Digital Library](http://dl.acm.org/).

### Topics

We seek submissions for posters and demos. We are interested in a wide variety of works that bridge arts and sciences. We are particularly interested in techniques for visually communicating ideas and information and for sketch based interaction and modeling integration through integration of computer science, mathematics, philosophy, psychology, and the fine, applied & performing arts.

Expressive solicits extended abstracts for posters and demos. Accepted works will be demonstrated and displayed during the conference. We expect these works will pose new questions and motivate further research in the main areas of Expressive: understanding, communication, and interaction.

Accepted submissions for Posters and Demos will be published together with the accepted papers as a single conference proceedings by the ACM and will be available online via the [ACM Digital Library](http://dl.acm.org/). Accepted submissions will also be archived in the [Eurographics Digital Library](https://diglib.eg.org/).

### Guidelines

All submissions should be between 2 and 4 pages, written in English, including a title page with an abstract, keywords, and a [bibliography](https://srmv2.eg.org/COMFy/Conference/EG_2025/Instruction). The required LaTeX template is available from the SRM system. Submissions should provide a clear description of the work and the process. Posters and demos will be demonstrated and/or displayed at the conference venue. Authors of accepted works in all areas of submitted work are encouraged to demonstrate their work; creating a separate submission for a poster and a demo is unnecessary if they refer to the same project.
<!-- All submissions should be 4 pages, written in English, including a title page with an abstract, keywords, and a [bibliography](https://srmv2.eg.org/COMFy/Conference/EG_2025/Instruction). Submissions should provide a clear description of the work and the process. Posters and demos will be demonstrated and/or displayed at the conference venue. Authors of accepted works in all areas of submitted work are encouraged to demonstrate their work; creating a separate submission for a poster and a demo is unnecessary if they refer to the same project. -->

### Submission

All submissions must be made through the Eurographics [SRM conference submission site](https://srmv2.eg.org/COMFy/Conference/Expressive_WICED_2025). If you have any questions, please feel welcome to contact the Posters and Demos chairs Daniel Berio and Alexandre Bruckert at [{{site.symposium[page.year].contact-poster-demo}}](mailto:{{site.symposium[page.year].contact-poster-demo}}) .

For detailed instructions to submit posters, demos and other materials, please view the [submission instructions](http://expressive.graphics/2025/instructions/).

<!-- --- -->

<!-- ## Call for Artworks — _Generative Chronicles_
{: .top2}

[<span class="glyphicon glyphicon-file"></span> Call for Artworks (PDF)](/docs/expressive-2019-call-for-artworks-v04.pdf)

{::options parse_block_html="true" /}

<div class="panel panel-warning">
#### Important dates
{: .panel-heading}
<div class="panel-body">

{% capture nowtime %}{{'now' | date: '%s'}}{% endcapture %}{% capture nowtime %}{{'now' | date: '%s'}}{% endcapture %}
{% capture generalartworksubmissionduetime %}{{site.symposium[page.year].general-artwork-submission | date: '%s'}}{% endcapture %}

| __Artwork submission deadline:__ Rolling notification, closes {% if generalartworksubmissionduetime < nowtime %}~~{% endif %}{{ site.symposium[page.year].general-artwork-submission }}{% if generalartworksubmissionduetime < nowtime %}~~{% endif %} |
| |
| All deadlines are at 23:59:59 UTC/GMT |

</div>
</div>

{::options parse_block_html="false" /}

### Theme: _Generative Chronicles_

What are the possible transformations and processes underlying the genesis of a visual form? For the Expressive 2019 Arts Program, we invite artwork submissions that explore, visualize, challenge, or reflect upon the process embedded in the artwork itself. This includes, but is not limited to:

* Simulations and visualizations of biologically inspired growth/decay processes;
* Procedurally-generated graphics and expressive animations that highlight the steps required for their generation;
* Digital elaborations upon the cognitive and motor processes underlying the act of human art making (e.g. painting/drawing/sculpting);
* Rule-based design systems that generate a myriad of visual outcomes;
* Multimodal visualizations exploring the art-making process;
* Projects that utilize glitches or explore serendipity.

Projects may take the form of computer animations and interactive installations, 
but we also welcome prints, digitally fabricated objects, as well as handmade drawings or design notes. 

For each submission, we require an extended abstract of 2 to 4 pages. The extended abstract should describe, illustrate, and discuss how the work relates to the theme of **Generative Chronicles** or to the Expressive Symposium's focus on expressive understanding, expressive communication, and expressive interaction. We suggest the inclusion of at least one representative image in the extended abstract.

Submissions can also optionally include supplementary materials, such as additional images, links to a video or website, and technical and installation requirements. Extended abstracts will be published in the ACM/EG Expressive 2019 conference proceedings, and archived through the [ACM Digital Library](http://dl.acm.org/) and [Eurographics Digital Library](https://diglib.eg.org/). **We also encourage dual submissions to the Arts Program and the main Expressive papers track**. The authors of accepted works will be invited to present their work through a panel discussion or short oral presentation within the main Expressive 2019 conference. All submissions must be made through the Eurographics SRM conference submission site.

**Authors of selected papers will be invited to submit extended versions of their manuscripts to be considered for publication in a special section of [Computers & Graphics](https://www.journals.elsevier.com/computers-and-graphics/) journal (Elsevier) via a fast-track review process.**

Please feel welcome to contact the Arts Program chairs Pedro Cruz and Daniel Berio at [{{site.symposium[page.year].contact-arts}}](mailto:{{site.symposium[page.year].contact-arts}}) if you have any questions.

For detailed instructions to submit artworks and other materials, please view the [submission instructions](http://expressive.graphics/2019/instructions/).

--- -->

<!-- ## Call for Journal Presentations
{: .top2}

[<span class="glyphicon glyphicon-file"></span> Call for Journal Presentations (PDF)](/docs/expressive-2019-call-for-journal-presentations-v03.pdf)

{::options parse_block_html="true" /}

<div class="panel panel-warning">
#### Important dates
{: .panel-heading}
<div class="panel-body">

{% capture nowtime %}{{'now' | date: '%s'}}{% endcapture %}{% capture nowtime %}{{'now' | date: '%s'}}{% endcapture %}
{% capture journalsubmissionduetime %}{{site.symposium[page.year].journal-submission | date: '%s'}}{% endcapture %}

| __Presentation of work previously published in a journal:__ Rolling notification, closes {% if journalsubmissionduetime < nowtime %}~~{% endif %}{{ site.symposium[page.year].journal-submission }}{% if journalsubmissionduetime < nowtime %}~~{% endif %} |
| |
| All deadlines are at 23:59:59 UTC/GMT |

</div>
</div>

{::options parse_block_html="false" /}

As at previous events, we will include a submission category for the presentation of work previously published in a journal (e.g. TVCG, C&G, CGF, TOG). The intent of this category is to allow authors of journal papers the opportunity to present their research at Expressive. These papers will not appear in the Expressive proceedings.

### Guidelines

The work should be published in the July 2018 -- July 2019 time-frame, and not have been previously presented at a conference or symposium. A copy of the paper abstract and a link to the published paper or preprint should be submitted via email to the program chairs. Submissions will be reviewed by the program committee. Note that accepted presentations are subject to the same rules as regular papers, namely that at least one author must register for the conference.
 -->
---

<!-- ### Contact

Conference chairs can be contacted via the following emails:

* General chairs: [{{site.symposium[page.year].contact}}](mailto:{{site.symposium[page.year].contact}})
* Program/Paper chairs: [{{site.symposium[page.year].contact-papers}}](mailto:{{site.symposium[page.year].contact-papers}})
* Poster + Demo chair: [{{site.symposium[page.year].contact-poster-demo}}](mailto:{{site.symposium[page.year].contact-poster-demo}}) -->

{::options parse_block_html="true" /}

<div class="panel panel-default">

#### Conference Chairs
{: .panel-heading .top2}
<div class="panel-body">

| __General Co-chairs:__ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|| {{ site.chairs2025.general }}, _{{ site.chairs2025.generalAff }}_
|                        || {{ site.chairs2025.general2 }}, _{{ site.chairs2025.general2Aff }}_
| __Program Co-chairs:__ || {{ site.chairs2025.program }}, _{{ site.chairs2025.programAff }}_
|                            || {{ site.chairs2025.program2 }}, _{{ site.chairs2025.program2Aff }}_
| __Posters and Demo Chair:__ || {{ site.chairs2025.postersdemo }}, _{{ site.chairs2025.postersdemoAff }}_
|                             || {{ site.chairs2025.postersdemo2 }}, _{{ site.chairs2025.postersdemo2Aff }}_
| __Publicity Chair:__      || {{ site.chairs2025.publicity }}, _{{ site.chairs2025.publicityAff }}_

</div>
</div>

{::options parse_block_html="false" /}
