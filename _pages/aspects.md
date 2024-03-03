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

## Sustainability Aspects

Each of these constituencies has their own needs and abilities to effect change; they also often have different vocabularies for talking about the issues.  Review a few of these groups, and see what commonalities are there if we could only more easily translate the vocabularies.  These span the perspective from the [average computer user](https://fosssustainability.com/aspects/user), to the [entire ecosystem of computing](https://fosssustainability.com/aspects/ecosystem).

<ul>
{% for aspect in site.aspects %}
<li><a href="{{ aspect.url }}">{{ aspect.title }}</a>{% if aspect.excerpt %}<small> - {{ aspect.excerpt }}</small>{% endif %}</li>
{% endfor %}
</ul>

## Relationships Between Aspects

