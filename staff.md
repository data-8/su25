---
layout: page
title: 🧑‍🏫 Staff
description: A listing of all the course staff members.
nav_order: 4
---

# **Staff**

**Email [data8@berkeley.edu](mailto:data8@berkeley.edu) for all logistical and student support questions!**

<!-- Staff information is stored in the `_staffers` directory and rendered according to the layout file, `_layouts/staffer.html`. -->


<!-- <p style="font-size:30px">Note: This page is under construction.</p> -->


<!-- <p style="font-size:30px">Please check back soon for an updated staff roster!</p> -->

## Instructors

<div class="role flex">
{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}
</div>

## UCS2

{% assign ucs2 = site.staffers | where: 'role', 'UCS2' %}
{% assign num_ucs2 = ucs2 | size %}
{% if num_ucs2 != 0 %}

<div class="role flex">
{% for staffer in ucs2 %}
{{ staffer }}
{% endfor %}
{% endif %}
</div>

## UCS1

{% assign ucs1 = site.staffers | where: 'role', 'UCS1' %}
{% assign num_ucs1 = ucs1 | size %}
{% if num_ucs1 != 0 %}


<div class="role flex">
{% for staffer in ucs1 %}
{{ staffer }}
{% endfor %}
{% endif %}
</div>
