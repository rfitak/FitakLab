---
layout: page
title: Research
permalink: /research/
toggle: on
rank: 1
---
Over the past decade, technological advancements in next-generation sequencing and genomics have revolutionized the field of biology.  Unfortunately, the unprecedented pace and volume of data being generated often exceeds the infrastructure and bioinformatic capabilities of many researchers.  As a result, many disciplines have developed a divide between those actively involved in experimental research and data collection at the organismal level and those with the computational and bioinformatic skills to process these data. As a quantitative organismal biologist, my research continuously bridges this divide by integrating skills and training in computational genomics with experimental research in organismal biology while fostering collaborations with scientists on both sides.  In particular, my research program utilizes these quantitative approaches to investigate the ___measurement___, ___maintenance___, and ___restoration___ of biodiversity (Fig. 1, below).
<br>
<img class="float-right" width="70%" style="margin: 25px 0px" src="{{ 'research.png' | prepend: site.images_dir | prepend: site.baseurl }}" />
<br>
In one way or another, my lab's various projects and interests intersect the chart in Fig. 1 (right), whether it be through the importance of understanding levels of genetic diversity, basic biology (e.g., physiology and behavior), or in directly translational results (e.g., population reintroductions).  Furthermore, this paradigm is not limited to wild species, as many of the same concepts are directly applicable to domestic or otherwise agriculturally and economically important species.  Below you will find specific examples of ongoing research projects in the lab.

---

<br>

<h1><b><ins>Projects</ins></b></h1>

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
