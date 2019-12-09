---
layout: default
speakers:
  - name: Rafael Irizarry
    inst: Harvard University
    url: https://rafalab.github.io
    blurb: "Rafael Irizarry is Professor and Chair of the Department of Data Sciences at the Dana-Farber Cancer Institute and a Professor of Biostatistics at Harvard School of Public Health, and one of the original founders of the Bioconductor Project. Professor Irizarry’s work has focused on problems related to microarray, next-generation sequencing, and genomic data. Currently, he is interested in leveraging his knowledge in translational work, e.g. developing diagnostic tools and discovering biomarkers. During his career, he as co-authored papers on a variety of topics including musical sound signals, infectious diseases, circadian patterns in health, fetal health monitoring, and estimating the effects of Hurricane María in Puerto Rico."
  - name: Caroline Uhler
    inst: ETH Zurich, Switzerland
    url: https://www.carolineuhler.com
    blurb: "Caroline Uhler, formerly Associate Professor at MIT in Cambridge, USA, recently joined the ETH Zurich, Switzerland, as Professor of Machine Learning, Statistics and Genomics. Her research focuses on statistics, machine learning and computational biology. In particular, graphical models, causal inference, algebraic statistics and applications to genomics, for example linking the spatial organization of the DNA with gene regulation."
  - name: Kylie Ariel Bemis
    inst: Northeastern University
    url: https://kuwisdelu.github.io
    blurb: "Kylie Bemis is a faculty in the Khoury College of Computer Sciences at Northeastern University where she teaches data science and develops curriculum for the MS in Data Science program. Her research interests include machine learning and large-scale statistical computing for bioinformatics. She is active in outreach to the Native American and LGBTQ communities, an enrolled member of the Zuni tribe, and a writer of fiction and poetry."
---

{% include header.md %}

BioC2020 highlights current developments within and beyond
the [Bioconductor](https://www.bioconductor.org) project. 


## Key dates

- Jan 9: Registration Opens
- Jan 15: Call for abstracts/applications for talks, early posters, scholarships, workshops
- March 3: Deadline for proposals for talks, workshops, early posters, and travel scholarships
- March 24: Notification of decision
- July 1: Deadline for late posters and for __Birds of a Feather__ meetings
- July 10: Notification of decision for late posters
- July 10: Last day of early registration
- July 29-31: Bioc2020 Meeting, Boston
  - [Community-Developer Day](./schedule-developer-day) July 29:
    provides developers and would-be developers with insights into
    Bioconductor project direction and software development best
    practices.
  - [Main Conference](./schedule-day-two) July 30-31 :
    morning scientific talks and afternoon workshops provide insights
    and tools required for the analysis and comprehension of
    high-throughput genomic data.
  

## Confirmed Speakers

{% for s in page.speakers %}
{% assign imgpath = "images/speakers/" | append: s.name | remove: ' ' | append: '.jpg' %}
<img src="{{ imgpath }}" style="float:right; width:120px; height:150px; object-fit: cover">
### [{{ s.name }}]({{ s.url }}), {{ s.inst }}

> {{ s.blurb }}

{% endfor %}

More information: [workshop@bioconductor.org][contact]

<a href="https://twitter.com/intent/tweet?button_hashtag=bioc2020&ref_src=twsrc%5Etfw"
    class="twitter-hashtag-button"
    data-show-count="false">Tweet #bioc2020</a>

<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

[contact]: mailto:workshop@bioconductor.org?subject=BioC2020%20question
[survey]: https://forms.gle/eRWv3tdXLvxYT2CYA