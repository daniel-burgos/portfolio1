---
layout: post
title: "College Templates"
categories:
  - projects
---
Below you will find a series of images for a couple of the templates I helped createfor several of our education programs.

<div class="canvas-templates">
  {% for file in site.static_files %}
    {% if file.path contains '/assets/img/CanvasTemplates/' %}
      <a href="{{ site.baseurl }}{{ file.path }}" target="_blank">
        <img src="{{ site.baseurl }}{{ file.path }}" alt="Canvas template">
      </a>
    {% endif %}
  {% endfor %}
</div>
