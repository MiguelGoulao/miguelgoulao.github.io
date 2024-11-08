---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

[Journal Articles](#journal-articles)\
[Conference Papers](#conference-papers)\
[Book Chapters](#book-chapters)\
[Workshop Papers](#workshop-papers)\
[Technical Reports](#tech-reports)

{% if site.author.googlescholar %}
  <div class="wordwrap">You can find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

## Journal Articles
{% for post in site.publications reversed %}
  {% if post.pubtype == 'journal' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}


## Conference Papers
{% for post in site.publications reversed %}
  {% if post.pubtype == 'conference' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Book Chapters
{% for post in site.publications reversed %}
  {% if post.pubtype == 'chapter' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}


## Workshop Papers
{% for post in site.publications reversed %}
  {% if post.pubtype == 'workshop' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Technical Reports
{% for post in site.publications reversed %}
  {% if post.pubtype == 'report' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Booklets
{% for post in site.publications reversed %}
  {% if post.pubtype == 'booklet' %}
      {% include archive-single.html %}
  {% endif %}
{% endfor %}
