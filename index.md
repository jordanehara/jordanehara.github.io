---
title:
layout: default
permalink: /
published: true
---


<div class="ProjectContainer">
  <div class="gallery">

  {% for project in site.projects %}

  <div class="galleryItem">
    <a href="{{ project.url | prepend: site.baseurl | prepend: site.url }}">
      <span>
        <h2>{{ project.title }}</h2>
      </span>
    </a>
    <a href="{{ project.url | prepend: site.baseurl | prepend: site.url }}">
      <img src="{{ project.images.main | prepend: '/assets/images/' | relative_url }}">
    </a>
    <p>{{ project.description }}</p>
  </div>

  {% endfor %}

  </div>
</div>
