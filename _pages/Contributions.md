---
layout: archive
title: "I pursue a forest"
permalink: /Contributions/
author_profile: true
---

This page is my contribution to the academic community.

I never deny the importance of immersive reading of academic classics, especially in this information age where attention is severely fragmented. However, information—even if it focuses on the most valuable parts—is still infinite. We cannot cover everything, and breadth of academic reading matters.

I am dedicated to distilling multimodal(i.e., data, papers, video etc.) academic knowledge from various sources, including lectures that may lack subtitles or are not publicly available, interdisciplinary papers, and books hidden in the corners of the internet.

Please note that my contribution is not to create new knowledge, but to make existing knowledge **more accessible**. To respect originality, I will cite the source for each piece of information.

I seek not individual trees, but a whole forest.

{% include base_path %}
{% include group-by-array collection=site.posts field="tags" %}

{% for tag in group_names %}
  {% assign posts = group_items[forloop.index0] %}
  <h2 id="{{ tag | slugify }}" class="archive__subtitle">{{ tag }}</h2>
  {% for post in posts %}
    {% include archive-single.html %}
  {% endfor %}
{% endfor %}

Lectures
------



Books
------

Papers
------