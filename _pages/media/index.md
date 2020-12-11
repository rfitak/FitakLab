---
layout: page
title: Media
permalink: /media/
toggle: on
rank: 6
---


<div class="link-wrapper">
    <ul class="link-list">
    <!-- Media -->
    {% for link in site.data.media %}
       <li><h3>{{ link.year }} by {{ link.author }}: <a href="{{ link.url }}">{{ link.title }}</a></h3></li>
    {% endfor %}
    </ul>
</div>
