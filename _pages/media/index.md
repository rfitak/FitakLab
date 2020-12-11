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
       <h3>{{ link.year }} by {{ link.author }}: <li><a href="{{ link.url }}">{{ link.title }}</h3></a></li>
    {% endfor %}
    </ul>
</div>
