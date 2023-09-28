---
title: "Aspects of Sustainability"
excerpt: "Various groups, people, policies, tools, etc. that affect sustainability."
layout: aspects
permalink: /aspects/
tags:
  - Aspects
--- 

Discussing *open source sustainability* with any four people will quickly bring up a dozen different conversations, based on how each person is related to open source.  To keep conversations productive, it helps to define what *aspects* of sustainability you're considering.

Even if we confine sustainability to just "common open source projects", the important points may be **very** different for someone working in a software company, versus lone maintainers, versus academics, or anyone else.  This site offers context to discussions with a framework of major aspects to consider.

Some key aspects - or different ways to think about sustainability - are:

<ul>
{% for aspect in site.aspects %}
<li><a href="{{ aspect.url }}">{{ aspect.title }}</a>{% if aspect.excerpt %}<small> - {{ aspect.excerpt }}</small>{% endif %}</li>
{% endfor %}
</ul>
