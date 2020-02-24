---
layout: page
title: Publications
permalink: /publications/
toggle: on
rank: 3
---

<p>Members of the Fitak Lab indicated in <b>boldface</b>
   <br>
   *Authors contributed equally
   <br>
</p>

<div align="center"><h2><b>2020</b></h2></div>
<div class="lab-wrapper">
    <ul class="lab-list">
    {% for pub in site.data.publications %}
    {% if pub.year == 2020 %}
     <li><p><a href="{{ pub.doi }}"><b>{{ pub.title }}</b></a>
      <br>
      {{ pub.authors }}
      <br>
      <i>{{ pub.journal }}</i> {{ pub.year }}, {{ pub.vol }}:{{ pub.pages }}
      {% if pub.pdf %}
         <a href="{{ pub.pdf | prepend: site.pub_dir | prepend: site.baseurl }}" style="-moz-box-shadow:inset 0px 1px 3px 0px #91b8b3; -webkit-box-shadow:inset 0px 1px 3px 0px #91b8b3; box-shadow:inset 0px 1px 3px 0px #91b8b3; background:-webkit-gradient(linear, left top, left bottom, color-stop(0.05, #768d87), color-stop(1, #6c7c7c)); background:-moz-linear-gradient(top, #768d87 5%, #6c7c7c 100%); background:-webkit-linear-gradient(top, #768d87 5%, #6c7c7c 100%); background:-o-linear-gradient(top, #768d87 5%, #6c7c7c 100%); background:-ms-linear-gradient(top, #768d87 5%, #6c7c7c 100%); background:linear-gradient(to bottom, #768d87 5%, #6c7c7c 100%); filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#768d87', endColorstr='#6c7c7c',GradientType=0); background-color:#768d87; -moz-border-radius:5px; -webkit-border-radius:5px; border-radius:5px; border:1px solid #566963; display:inline-block; cursor:pointer; color:#ffffff; font-family:Arial; font-size:15px; font-weight:bold; padding:2px 5px; text-decoration:none; text-shadow:0px -1px 0px #2b665e;" download>Download</a>
      {% endif %}
      </p></li>
    {% endif %}
    {% endfor %}
    </ul>
</div>

<div align="center"><h2><b>2019</b></h2></div>
<div class="lab-wrapper">
    <ul class="lab-list">
    {% for pub in site.data.publications %}
    {% if pub.year == 2019 %}
     <li><p><a href="{{ pub.doi }}"><b>{{ pub.title }}</b></a>
      <br>
      {{ pub.authors }}
      <br>
      <i>{{ pub.journal }}</i> {{ pub.year }}, {{ pub.vol }}:{{ pub.pages }}   
      {% if pub.pdf %}
         <a href="{{ pub.pdf | prepend: site.pub_dir | prepend: site.baseurl }}" style="-moz-box-shadow:inset 0px 1px 3px 0px #91b8b3; -webkit-box-shadow:inset 0px 1px 3px 0px #91b8b3; box-shadow:inset 0px 1px 3px 0px #91b8b3; background:-webkit-gradient(linear, left top, left bottom, color-stop(0.05, #768d87), color-stop(1, #6c7c7c)); background:-moz-linear-gradient(top, #768d87 5%, #6c7c7c 100%); background:-webkit-linear-gradient(top, #768d87 5%, #6c7c7c 100%); background:-o-linear-gradient(top, #768d87 5%, #6c7c7c 100%); background:-ms-linear-gradient(top, #768d87 5%, #6c7c7c 100%); background:linear-gradient(to bottom, #768d87 5%, #6c7c7c 100%); filter:progid:DXImageTransform.Microsoft.gradient(startColorstr='#768d87', endColorstr='#6c7c7c',GradientType=0); background-color:#768d87; -moz-border-radius:5px; -webkit-border-radius:5px; border-radius:5px; border:1px solid #566963; display:inline-block; cursor:pointer; color:#ffffff; font-family:Arial; font-size:15px; font-weight:bold; padding:2px 5px; text-decoration:none; text-shadow:0px -1px 0px #2b665e;" download>Download</a>
      {% endif %}
      </p></li>
    {% endif %}
    {% endfor %}
    </ul>
</div>
