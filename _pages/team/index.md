---
layout: page
title: Team
permalink: /team/
toggle: on
rank: 2
---

<div style="margin-bottom: 50px;">
    <img src="{{ 'team/Alex-party-2022-7.jpg' | prepend: site.images_dir | prepend: site.baseurl }}" />
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
