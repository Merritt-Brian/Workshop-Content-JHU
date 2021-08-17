---
layout: post
title:  "Theory Modules"
categories: jekyll update
permalink: /training/theory

---

---
<br>

[NAME] partners have developed a combination of complete training courses and individual modules. Individual courses have been categorized into four main categories: theory, laboratory, bioinformatics, and phylogenetics. Most of the individual modules are included as part of [complete training courses]({{site.baseurl}}{% link pages/training/courses.md %}), but they may also be viewed on their own to gain expertise on individual topics.

Below you will find the **theory** modules. These are modules that cover background data on genomic epidemiology and the history of pathogen genome sequencing.

---

<br>

#### Available Modules

Introduction to Pathogen Sequencing\
<font size="2">
	&emsp;**Materials:** None\
	&emsp;**Parent course:** [Genomic Epidemiology of SARS-CoV-2 (Command Line)]({{site.baseurl}}{% link pages/training/courses/sarscov2_commandline.md %})\
	&emsp;**Suggested prerequisites:** None\
	&emsp;**Suggested partner modules:** None\
	&emsp;**Language:** English (with French subtitles). **Runtime:** 14 minutes
</font> 

Introduction to Genomic Epidemiology\
<font size="2">
	&emsp;**Materials:** None\
	&emsp;**Parent course:** [Genomic Epidemiology of SARS-CoV-2 (Command Line)]({{site.baseurl}}{% link pages/training/courses/sarscov2_commandline.md %})\
	&emsp;**Suggested prerequisites:** None\
	&emsp;**Suggested partner modules:** None\
	&emsp;**Language:** English (with French subtitles). **Runtime:** 10 minutes
</font> 


{% assign link = site.data.navigation[1].sublinks[0] %}
{% for sublink in link.sublinks %}
[{{sublink.title}}]( {% link pages{{ sublink.url }}.md  %} )
{% endfor %}


