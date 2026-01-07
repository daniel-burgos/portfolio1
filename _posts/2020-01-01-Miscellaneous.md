---
layout: post
title: "Miscellaneous"
categories:
  - projects
---

Here are other items I have worked on.   

<div class="Canvas-Templates">
  {% assign images = site.static_files | where_exp: "file", "file.path contains 'assets/img/CanvasTemplates/'" %}
  {% for image in images %}
    <a href="{{ image.path }}" target="_blank">
      <img src="{{ image.path }}" alt="Gallery image">
    </a>
  {% endfor %}
</div>

.Canvas-Templates {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(160px, 1fr));
  gap: 1rem;
  margin-top: 2rem;
}

.Canvas-Templates {
  width: 100%;
  height: 160px;
  object-fit: cover;
  border-radius: 10px;
  transition: transform .2s ease, box-shadow .2s ease;
}

.Canvas-Templates:hover {
  transform: scale(1.04);
  box-shadow: 0 6px 18px rgba(0,0,0,.25);
}

<iframe
  src="https://drive.google.com/file/d/1K9UyKRUdRsYoHPkYKL3QJsJjNXGYoq_5/preview"
  width="100%"
  height="480p"
  frameborder="0"
  allowfullscreen>
</iframe>

