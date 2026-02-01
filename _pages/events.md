---
layout: archive
title: "Organized Events"
permalink: /events/
author_profile: true
---

Below is a list of events (schools, conferences, minisymposia/dedicated sessions at larger events, etc.), that I have participated in organizing over the years.

{% for post in site.events reversed %}
  {% include archive-single.html %}
{% endfor %}