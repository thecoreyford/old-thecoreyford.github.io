---
layout: page
title: teaching
permalink: /teaching/
description: Over the last 3+ years I've worked as a lecturer/tutor in a variety of settings. Mostly, I have focused on teaching audio principles and technologies, as well as computer programming. Furthermore, I have taught a variety of ages and expertise - from young children all the way up to masters level students. My experience is listed below...
nav: true
display_categories: [2021, 2020, 2019]
horizontal: false
---

<h4 class="font-weight-bolder">Associate Lecturing / Demonstrating</h4>

<div class="projects">
  {% if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
    {% for category in page.display_categories %}
      <h2 class="category">{{ category }}</h2>
      {% assign categorized_projects = site.projects | where: "category", category %}
      {% assign sorted_projects = categorized_projects | sort: "importance" %}
      <!-- Generate cards for each project -->
        <div class="grid">
          {% for project in sorted_projects %}
            {% include projects.html %}
          {% endfor %}
        </div>
    {% endfor %}
  {% endif %}


<br>
<br>
<h4 class="font-weight-bolder">Support Roles</h4>

I have supported teaching at the following workshops, for conferences or during outreach events. <br>

* July 2020 | <b>Crowd Driven Music with Manhattan</b> | @ NIME 2020 <br>
* Feb 2020 | <b>Codetta Workshop</b> |	 MA Creative Music Practice @ University of Gloucestershire <br>
* Jan 2020 | <b>BBC Digital Cities</b> | @ Engine Shed (Bristol) <br>
* Summer 2019 | <b>STEM Outreach Event (for sixth-formers)</b> | @ UWE Bristol <br>
<br>

Similarly, I have been a tutor in the following positions...<br>
* 2018-2020 | <b>Espresso Programming</b> | Computer Science and Creative Tech @ UWE Bristol <br>
* 2017-2018 | <b>PAL Leader</b> | BSc Creative Music Technology @ UWE Bristol <br>
* Summer 2019 & 2018 | <b>Tech Tutor</b> | @ FunTech <br>



</div>