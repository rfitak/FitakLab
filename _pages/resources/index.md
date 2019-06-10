---
layout: page
title: Resources
permalink: /resources/
toggle: on
rank: 5
---


<div class="link-wrapper">
    <ul class="link-list">
    <!-- Resources -->
    {% for link in site.data.resources %}
       <a href="{{ link.url }}"><h2>{{ link.name }}</h2></a>
       {% if link.photo %}
          <img class="float-left resources-photo" width="100px" src="{{ link.photo | prepend: site.images_dir | prepend: site.baseurl }}">
       {% endif %}
       <p>{{ link.description }}</p>
    {% endfor %}
    </ul>
</div>
