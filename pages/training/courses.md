---
layout: post
title:  "Complete Courses"
categories: jekyll update
permalink: /training/courses

---

[NAME] partners have developed a combination of complete training courses and individual modules. Read the descriptions of full training courses below to select the course that best fits your needs. Click on the name of a course for a full description of training modules and content.

<br>

#### [Genomic Epidemiology of SARS-CoV-2 (Command Line)]({{site.baseurl}}{% link pages/training/courses/sarscov2_commandline.md %})

**Sequencing methodologies:** Amplicon sequencing

**Sequencing technologies:** Oxford Nanopore

**Specific pathogens:** SARS-CoV-2

**Video language:** English (with French subtitles)

**Written materials language:** English

**Recommended for:** Building capacity for SARS-CoV-2 sequencing, developing broadly applicable bioinformatics skills (e.g., the Linux Command Line)

<br>

#### [Genomic Epidemiology of SARS-CoV-2 (BaseStack)]({{site.baseurl}}{% link pages/training/courses/sarscov2_basestack.md %})

**Sequencing methodologies:** Amplicon sequencing

**Sequencing technologies:** Oxford Nanopore

**Specific pathogens:** SARS-CoV-2

**Video language:** English

**Written materials language:** English

**Recommended for:** Building capacity for SARS-CoV-2 sequencing, learning how to use BaseStack software for bioinformatics and phylogenetic analysis


{% assign link = site.data.navigation[1].sublinks[0] %}
{% for sublink in link.sublinks %}
[{{sublink.title}}]( {% link pages{{ sublink.url }}.md  %} )
{% endfor %}