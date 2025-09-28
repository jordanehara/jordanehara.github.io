---
layout: default
title: Dungeon-Crawl
description: A 3D top-down action role play game about finding your adventuring partner.
images:
  main: Dungeon-Crawl_title.png
---

Dungeon Crawl (Working Title)
============
<!-- Links -->
<a title="{{ _locale_string_follow | replace: '[NAME]', 'itchio' }}" class="social-button itch-io" href="https://{{ site.itchio }}.itch.io/{{page.title}}" itemprop="sameAs" target="_blank">
  <i class="fab fa-itch-io"></i>
  itch.io
</a>
&#160;|&#160;
<a title="{{ _locale_string_follow | replace: '[NAME]', 'github' }}" class="social-button github"
    href="https://github.com/{{site.github}}/{{page.title}}" itemprop="sameAs" target="_blank">
    <i class="fab fa-github"></i>
    GitHub
</a>


Description:
------------
<div class="projectImgGallery">
  <a href="/assets/images/{{ page.title }}_1.png" data-lightbox="{{ page.title }}_1" data-title="Opening cutscene">
    <img src="/assets/images/{{ page.title }}_1.png">
  </a>
</div>
{{page.title}} is a story-driven ARPG about finding your missing adventuring partner. The player traverses a dangerous dungeon fighting and leveling up their abilities to get stronger.

A proof of concept project focused on developing modular systems for combat and quests that are a staple of the RPG genre.


Role:
------------
- Solo Developer
- Writer

Features:
------------
- Player leveling system
  - Skill tree to upgrade abilities and customize playstyle
  - Player stat upgrades
- Quest system
  - Quest-giving NPCs
  - Quest realted enemies
- Ranged and melee attacks for player and enemies