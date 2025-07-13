---
layout: page
title: 🏠 Home
description: Listing of course modules and topics.
nav_order: 1
permalink: /
---

# **Data 8: Foundations of Data Science**

{: .mb-2 }
UC Berkeley, Summer 2025
{: .mb-2 .fs-6}

[Ed](https://edstem.org/us/courses/79204/discussion){: .btn .btn-ed}
[Gradescope](https://www.gradescope.com/courses/1042415){: .btn .btn-gradescope}
<!-- [Lecture Recordings](https://bcourses.berkeley.edu/courses/1542000/external_tools/90481){: .btn .btn-bcourses} -->
[Lecture Recordings](https://bcourses.berkeley.edu/courses/1544818/external_tools/90481){: .btn .btn-bcourses}
[Office Hours Queue](https://oh.data8.org/){: .btn .btn-officehours}
<!-- [Extensions](https://docs.google.com/forms/d/e/1FAIpQLSebp86RhH3cWG1_4v6dR5f_WyJ_icj3cmXoUy9p4C30typmOw/viewform){: .btn .btn-extensions} -->
[Jump to Current Week](https://www.data8.org/su25/#week-4){: .btn .btn-currweek}
{% include announcements-navigation.html %}

{% assign mods = site.modules | where: 'class', 'Berkeley' %}
{% assign active-mods = '' | split: '' %}

{% for mod in mods %}
{% if mod.status == 'Active' %}
{% assign active-mods = active-mods | push: mod %}
{% endif %}
{% endfor %}

{% for module in active-mods %}
{{ module }}
{% endfor %}

<script src="{{ '/assets/scripts/announcement-navigation.js' | relative_url }}"></script>
