---
layout: page
title: Research
permalink: /research/
toggle: on
rank: 1
---

<div class="lab-wrapper">
    <ul class="lab-list">
    {% for project in site.data.projects %}
    {% if project.name and project.description %}
        <li>
            <h2>{{ project.name }}</h2>
            {% if project.photo %}
                <img class="float-right projects-photo" src="{{ project.photo | prepend: site.images_dir | prepend: site.baseurl }}">
            {% endif %}
            <p>{{ project.description }}</p>
            {% if project.funding %}
                <p><b>Funding: </b>{{ project.funding }}</p>
            {% endif %}
            {% if project.collaborators %}
                <p><b>Collaborators: </b>{{ project.collaborators }}</p>
            {% endif %}
            {% if project.assignees %}
                <p><b>Assignees: </b>{{ project.assignees }}</p>
            {% endif %}
        </li>
    {% endif %}
    {% endfor %}
    </ul>
</div>