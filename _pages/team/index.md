---
layout: page
title: Team
permalink: /team/
toggle: on
rank: 2
---

<div style="margin-bottom: 50px; max-width: 65%; margin-left: auto; margin-right: auto;">
    <img src="{{ 'team/Wekiva2023-2.jpg' | prepend: site.images_dir | prepend: site.baseurl }}" />
</div>

<style>
img:hover {
  box-shadow: 0 0 2px 1px rgba(0, 140, 186, 0.5);
}
</style>

<!--
<div>
  <h2>Additional Lab Photos: Click to enlarge</h2>
  <a target="_blank" href="{{ 'team/Alex-party-2022-7.jpg' | prepend: site.images_dir | prepend: site.baseurl }}">
    <img src="{{ 'team/Alex-party-2022-7.jpg' | prepend: site.images_dir | prepend: site.baseurl }}" alt="test" style="border: 1px solid #ddd;border-radius:4px;padding:5px;width:150px" />
  </a>
</div>
//-->

<h2>Additional Lab Photos: click to enlarge</h2>
<div style="border: 1px solid #ddd;border-radius:4px;padding:5px;width:200px">
  <div><a target="_blank" href="{{ 'team/Alex-party-2022-7.jpg' | prepend: site.images_dir | prepend: site.baseurl }}">
    <img src="{{ 'team/Alex-party-2022-7.jpg' | prepend: site.images_dir | prepend: site.baseurl }}" alt="test" />
  </a></div>
  <div><a target="_blank" href="{{ 'team/Lab-Wekiva-crop-July2022.jpg' | prepend: site.images_dir | prepend: site.baseurl }}">
    <img src="{{ 'team/Lab-Wekiva-crop-July2022.jpg' | prepend: site.images_dir | prepend: site.baseurl }}" alt="test" />
  </a></div>
  <div><a target="_blank" href="{{ 'team/lab-dinner2_May22.jpg' | prepend: site.images_dir | prepend: site.baseurl }}">
    <img src="{{ 'team/lab-dinner2_May22.jpg' | prepend: site.images_dir | prepend: site.baseurl }}" alt="test" />
  </a></div>
</div>



<div style="display: flex; flex-wrap: wrap; padding: 20px; margin-left: auto; margin-right: auto;">
    <div style="padding: 20px; max-width: 33%; margin-left: auto; margin-right: auto;">
        <img src="{{ 'team/lab.jpg' | prepend: site.images_dir | prepend: site.baseurl }}" />
        </div>
    <div style="padding: 20px; max-width: 33%; margin-left: auto; margin-right: auto;">
        <img src="{{ 'team/Lab-Wekiva-crop-July2022.jpg' | prepend: site.images_dir | prepend: site.baseurl }}" />
    </div>
      
    <div style="padding: 20px; max-width: 33%; margin-left: auto; margin-right: auto;">
        <img src="{{ 'team/lab-dinner2_May22.jpg' | prepend: site.images_dir | prepend: site.baseurl }}" />
    </div>
    <div style="padding: 20px; max-width: 33%; margin-left: auto; margin-right: auto;">
        <img src="{{ 'team/FIGL_4-14-22_4.jpeg' | prepend: site.images_dir | prepend: site.baseurl }}" />
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
