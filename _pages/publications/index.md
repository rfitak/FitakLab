---
layout: page
title: Publications
permalink: /Publications/
toggle: on
rank: 3
---

Members of the Fitak Laboratory indicated in **boldface**

\*Authors contributed equally<br>

<div align="center"><h2><b>2019</b></h2></div>
<div class="lab-wrapper">
    <ul class="lab-list">
    {% for pub in site.data.publications %}
    {% if pub.year == 2019 %}
       <p><a href="{{ pub.doi }}">{{ pub.title }}</a><br>{{ pub.authors }}<br>{{ pub.journal }} {{ pub.year }}, {{ pub.vol }}:{{ pub.pages }}</p>
    {% endif %}
    {% endfor %}
    </ul>
</div>
