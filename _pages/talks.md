---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---

### Fall 2023

| Speaker          | Date   |                                                              |
| --------         | ------ | ------------------------------------------------------------ |
| Danielle Wang    | Sep 11   | Description of the item in the list                          |
| Murilo Corato Zanarella    | Sep 18   | Description of the item in the list                          |
| Gefei Dang     | Sep 25   | Description of the item in the list                          |

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}

