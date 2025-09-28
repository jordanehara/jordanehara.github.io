---
title:
layout: default
permalink: /
published: true
---


<div class="ProjectContainer">

  <div class="gallery">


  {% for project in site.projects %}

  {% if project.redirect %}
  <div class="projectTile">
          <a href="{{ project.redirect }}" target="_blank">
          <span>
              <h2><img src="{{ project.image | prepend: '/assets/images/' | relative_url }}"></h2>
              <p>{{ project.title }}</p>
          </span>
          </a>
  </div>

  {% else %}

  <div class="projectTile">
          <a href="{{ project.url | prepend: site.baseurl | prepend: site.url }}">
          <span>
              <h2><img src="{{ project.image | prepend: '/assets/images/' | relative_url }}"></h2>
              <p>{{ project.title }}</p>
          </span>
          </a>
  </div>

  {% endif %}

  {% endfor %}

  </div>

</div>
