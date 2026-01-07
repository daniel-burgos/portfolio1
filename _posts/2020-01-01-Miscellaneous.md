---
layout: post
title: "Miscellaneous"
categories:
  - projects
---

Here are other items I have worked on.   

<div class="canvas-templates">
  {% for file in site.static_files %}
    {% if file.path contains '/assets/img/CanvasTemplates/' %}
      <a href="{{ site.baseurl }}{{ file.path }}" target="_blank">
        <img src="{{ site.baseurl }}{{ file.path }}" alt="Canvas template">
      </a>
    {% endif %}
  {% endfor %}
</div>



<iframe
  src="https://drive.google.com/file/d/1K9UyKRUdRsYoHPkYKL3QJsJjNXGYoq_5/preview"
  width="100%"
  height="480p"
  frameborder="0"
  allowfullscreen>
</iframe>

