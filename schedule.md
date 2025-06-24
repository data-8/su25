---
layout: page
title: 🏢 Weekly OH
description: The weekly event schedule.
nav_order: 2
---

# **Weekly Office Hours**

We use an [online sign-up system](https://oh.data8.org/) to help keep track of everyone.

All office hours take place in [Warren 101B](https://www.google.com/maps/place/Warren+Hall/@37.8744309,-122.2694008,712m/data=!3m2!1e3!4b1!4m6!3m5!1s0x80857e9fc96d7f9b:0x1f3694d1fb1a1f03!8m2!3d37.8744309!4d-122.2668205!16s%2Fg%2F11bwgfg2jf?entry=ttu&g_ep=EgoyMDI1MDYxNy4wIKXMDSoASAFQAw%3D%3D).

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}


