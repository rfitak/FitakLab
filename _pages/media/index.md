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
       <li><h4><b>{{ link.year }}</b> by {{ link.author }}: <a href="{{ link.url }}">{{ link.title }}</a></h4></li>
    {% endfor %}
    </ul>
</div>
