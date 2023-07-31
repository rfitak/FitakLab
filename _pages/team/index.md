---
layout: page
title: Team
permalink: /team/
itoggle: on
rank: 2
---

<div style="margin-bottom: 50px; max-width: 65%; margin-left: auto; margin-right: auto;">
    <img src="{{ 'team/Wekiva2023-2.jpg' | prepend: site.images_dir | prepend: site.baseurl }}" alt="Wekiva Springs 2023: Alien birthing" />
</div>

<style>
img:hover {
  box-shadow: 0 0 4px 2px rgba(0, 140, 186, 0.5);
}
</style>

<h2>Additional Lab Photos: click to enlarge</h2>
<div style="display: flex; flex-wrap: wrap; padding: 20px; margin-left: auto; margin-right: auto">
    <div style="padding: 5px; width: 200px; margin-left: auto; margin-right: auto; border-radius: 4px">
      <a target="_blank" href="{{ 'team/AK-2022_1.jpg' | prepend: site.images_dir | prepend: site.baseurl }}">
        <img src="{{ 'team/AK-2022_1.jpg' | prepend: site.images_dir | prepend: site.baseurl }}" alt="Animal Kingdom Trip 2022" /></a>
    </div>
    <div style="padding: 5px; width: 200px; margin-left: auto; margin-right: auto; border-radius: 4px">
      <a target="_blank" href="{{ 'team/Alex-party-2022-7.jpg' | prepend: site.images_dir | prepend: site.baseurl }}">
        <img src="{{ 'team/Alex-party-2022-7.jpg' | prepend: site.images_dir | prepend: site.baseurl }}" alt="Alex's Farewell Party 2022" /></a>
    </div>
    <div style="padding: 5px; width: 200px; margin-left: auto; margin-right: auto; border-radius: 4px">
      <a target="_blank" href="{{ 'team/Lab-Wekiva-crop-July2022' | prepend: site.images_dir | prepend: site.baseurl }}">
        <img src="{{ 'team/Lab-Wekiva-crop-July2022.jpg' | prepend: site.images_dir | prepend: site.baseurl }}" alt="Wekiva Springs 2022" /></a>
    </div>
    <div style="padding: 5px; width: 200px; margin-left: auto; margin-right: auto; border-radius: 4px">
      <a target="_blank" href="{{ 'team/lab-dinner2_May22.jpg' | prepend: site.images_dir | prepend: site.baseurl }}">
        <img src="{{ 'team/lab-dinner2_May22.jpg' | prepend: site.images_dir | prepend: site.baseurl }}" alt="Lab Dinner May 2022" /></a>
    </div>
    <div style="padding: 5px; width: 200px; margin-left: auto; margin-right: auto; border-radius: 4px">
      <a target="_blank" href="{{ 'team/FIGL_4-14-22_4.jpg' | prepend: site.images_dir | prepend: site.baseurl }}">
        <img src="{{ 'team/FIGL_4-14-22_4.jpg' | prepend: site.images_dir | prepend: site.baseurl }}" alt="GBC Open House April 2022" /></a>
    </div>
    <div style="padding: 5px; width: 300px; margin-left: auto; margin-right: auto; border-radius: 4px">
      <a target="_blank" href="{{ 'team/lab.jpg' | prepend: site.images_dir | prepend: site.baseurl }}">
        <img src="{{ 'team/lab.jpg' | prepend: site.images_dir | prepend: site.baseurl }}" alt="First Lab Photo: Zoom 2020" /></a>
    </div>
</div>

<div>
<font size="4">Equality and inclusion of people from diverse backgrounds are fundamental to scientific inquiry.  Similar to how major scientific steps forward have been made through the integration of multiple disciplines, the integration and collaboration of diverse people has generated new ideas, techniques, and paradigms critical for scientific advancement. Not only are we committed to fostering a diverse and inclusive atmosphere, whether it be gender, race, disability, sexual preference, etc., but recognize that it is essential to the scientific and personal development of all of us. For more information regarding what the Fitak Lab has been doing to promote diversity in our group, the UCF Biology Department, and in STEM, visit the <a href="http://fitaklab.com/resources/">Resources</a> page.</font>
</div>
<br>
<hr style="height:4px;border-width:0;color:gray;background-color:gray">
<br>
<div class="lab-wrapper">
    <ul class="lab-list">
    <!-- Current PI -->
    {% for member in site.data.team %}
        {% if member.is_current and member.is_pi %}
            {% if member.name and member.bio %}
                {% include member.html %}
            {% endif %}
        {% endif %}
    {% endfor %}
    <!-- Current Members -->
    <br><br><h1 class="post-title">Current Lab Members</h1><hr style="height:4px;border-width:0;color:gray;background-color:gray"><br>
    {% for member in site.data.team %}
        {% if member.is_current and member.is_pi == false %}
            {% if member.name and member.bio %}
                {% include member.html %}
            {% endif %}
        {% endif %}
    {% endfor %}
    <!-- Non-current (alumni) -->
    {% assign alumni_size = site.data.team | size %}
    {% if alumni_size > 0 %}
        <br><h1 class="post-title">Alumni</h1><hr style="height:4px;border-width:0;color:gray;background-color:gray"><br>
        {% for member in site.data.team %}
            {% if member.is_current == false %}
                {% if member.name and member.bio %}
                    {% include member.html %}
                {% endif %}
            {% endif %}
        {% endfor %}
    {% endif %}
    </ul>
</div>
