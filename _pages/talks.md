---
layout: archive
title: "Talks and Seminars"
permalink: /talks/
author_profile: true
---

### Fall 2023 Learning Seminar
Time: Monday, 10 AM to Noon

Place: 2-361
 
| Speaker          | Date   |           Title/Notes                                          |
| --------         | ------ | ------------------------------------------------------------ |
| Danielle Wang    | Sep 11   |  Twisted GGP conjecture for unramified quadratic extensions     |
| Murilo Corato Zanarella    | Sep 18   |                                |
| Gefei Dang     | Sep 25   |                                       |

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}

