---
layout: submission
title: ACM/EG Expressive 2025 — Call for Submissions
excerpt: "Submit your work to Expressive 2019"
image:
  card: 2025/expressiveCard.jpg
year: 2025
---

Virtual cameras, mise-en-scene, lighting and editing (montage) are regularly used in 3D synthetic environments for visual media such as film, games, and virtual reality. While often invisible to the public eye, their use increases the effectiveness of the content in engaging their audiences, creating more impactful and emotional experiences. At the same time, recent advances in computer vision-based object, actor, and event recognition, face tracking, and camera motion estimation make it possible to new kinds of automation in film, television and other videographic media, such as re-cinematography (re-lighting, re-framing) and automatic editing of videos. 

The WICED workshop series is intended to bridge the gap between these topics of research and confront challenges in these domains. This workshop aims to bring together researchers and industrial experts working in all aspects of digital cinematography and film editing in their respective fields, including 3D graphics, artificial intelligence, computer vision, visualization, interactive narrative, cognitive and perceptual psychology, computational linguistics, computational aesthetics and visual effects.

We invite submissions in the form of regular papers and invited papers (1 page abstract of relevant work already published in other venues).

WICED 2025 is organized as a joint event with Expressive 2025, and co-located with Eurographics 2025.

{::options parse_block_html="true" /}
<a href="#call-for-papers" class="bold"> > Call for Papers</a><br>
<a href="#call-for-papers--wiced-2025" class="bold"> > Call for Papers – WICED 2025</a><br>
<a href="#call-for-posters-and-demos" class="bold"> > Call for Posters and Demos</a><br>
<!-- <a href="#call-for-artworks--generative-chronicles" class="bold"> > Call for Artworks</a><br> -->
<!-- <a href="#call-for-journal-presentations" class="bold"> > Call for Journal Presentations</a> -->
{::options parse_block_html="false" /}

---

## Call for Papers – WICED 2025
{: .top2}

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

Researchers should submit one of:

* __Regular paper__ (max 8 pages) reporting original research or proposing perspectives for future directions.

* __Invited paper__ (1 page abstract) reporting relevant work __already published in other venues__.

Submissions will be made electronically through the Eurographics Submission and Review Management [SRM]({{site.symposium[2025].submission}}) system. For the regular papers, submissions must be anonymous and formatted according to the Eurographics Author’s guidelines (LateX template is available from the SRM system).


### Topics of Interest

{: .top1}

* Camera path planning and visibility
* Interactive and automatic camera control
* Automatic video editing
* Movie pre-visualization
* Game cinematics, cinematic replays, and machinima
* Virtual reality and augmented reality movie making
* Immersive and interactive cinema
* Natural user interfaces for cinematography and video editing
* Expressive performance of virtual characters
* Cognitive models of film perception
* Automatic video analysis of movies
* Re-cinematography, re-lighting and re-framing of live-action video
* Computer-assisted multi-camera production
* Evaluation methodologies and user experience
* Analysis of film style

### Submission Information
{: .top1}
The papers can be submitted through:

* [Elsevier Computers and Graphics submission portal](https://www.editorialmanager.com/cag/default.aspx) (Note: please select VSI: Expressive Media 2025.)

    After reviews, the best papers will be retained for publication in the C&G journal, while other high-quality papers that do not reach the C&G bar will be redirected to the conference paper track. The submitted papers must be anonymous and formatted according to either the C&G guidelines or the EG guidelines (see below). There is no strict page limit, but the length should justify the contribution. 
* [SRM submission system](https://srmv2.eg.org/COMFy/Conference/Expressive_WICED_2025) 

    The papers submitted through SRM will only be considered for the conference track. The conference proceedings will be made available online via  Eurographics Digital Library. They will also be archived in the  ACM Digital Library. The submitted papers must be anonymous and formatted in the template given [here](https://srmv2.eg.org/COMFy/Conference/Expressive_WICED_2025/GetConferenceFile?fileID=17039).

If you have any questions, please feel welcome to contact the Program chairs, Chiara Eva Catalano and Amal Dev Parakkat, at [{{site.symposium[page.year].contact}}](mailto:{{site.symposium[page.year].contact}})
