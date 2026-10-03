---
layout: post
title: "Doctorate of Global Hospitality Leadership (DGHL) Canvas Template"
categories:
  - projects
---
<h3><strong>Overview</strong></h3>
Collaborated with the Communications Department to implement course templates for the Doctorate of Global Hospitality Leadership (DGHL) program, to establish a consistent, professional, and highly accessible learning environment for online doctoral students.
<h3><strong>Challenge</strong></h3>
As the college launched its new online doctoral program, it sought to create a premium learning experience that reflected the unique expectations of working professionals enrolled in graduate-level studies. Consistency, branding, usability, and accessibility were all essential considerations during development.
<h3><strong>Approach</strong></h3>
Working from the visual designs and assets developed by the Communications Department, I translated the designs into functional Canvas course templates using HTML and accessibility best practices. I also supported implementation of the accompanying PowerPoint template and worked with faculty to maintain accessibility standards as course content was added. Accessibility was prioritized from the beginning of development, allowing potential issues to be addressed proactively rather than remediated later.
<h3><strong>Outcome</strong></h3>
The DGHL template was adopted across all courses within the program and contributed to an accessibility rate of approximately 94%, exceeding the college-wide average of 88%. The project demonstrated the value of integrating accessibility planning into the design process and established a consistent digital experience that supports both faculty and students throughout the program.

<div class="canvas-templates">
  {% for file in site.static_files %}
    {% if file.path contains '/assets/img/CanvasTemplates/' %}
      <a href="{{ site.baseurl }}{{ file.path }}" target="_blank">
        <img src="{{ site.baseurl }}{{ file.path }}" alt="Canvas template">
      </a>
    {% endif %}
  {% endfor %}
</div>
