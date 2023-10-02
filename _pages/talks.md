---
layout: archive
title: "Talks and Seminars"
permalink: /talks/
author_profile: true
---

### Fall 2023 Learning Seminar
Time: Monday, 10 AM to Noon

Place: 2-361

[Syllabus](https://weixiao-lu.github.io/files/Fall_2023_seminar.pdf)
 
| Speaker          | Date   |           Title/Notes                                          |
| --------         | ------ | ------------------------------------------------------------ |
| Danielle Wang    | Sep. 11   |  Twisted GGP conjecture for unramified quadratic extensions     |
| Murilo Corato Zanarella    | Sep. 18   |     Explicit models of relative spherical functions and a conjecture of Hironaka           |
| Gefei Dang     | Sep. 25   |  Local newforms for generic representations of unitary groups                                     |
|                | Oct. 16         |  Orthogonal Shimura varieties and moduli of K3 surfaces         |
|                | Oct. 23      | Tate conjecture for hyperkahler varieties over number fieds  |
|          | Oct. 30 | Integral models of orthogonal Shimura varieties |
|          | Nov. 6  | Tate conjeuture of K3 surfaces over finite fields |
|         | Nov. 13 | Jump of Picard rank I |
|         | Nov. 20 | Jump of Picard rank II|
|         | Nov. 27 | Average Colmez conjecture I|
|         | Dec. 4  | Average Colmez conjecture II|

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}

