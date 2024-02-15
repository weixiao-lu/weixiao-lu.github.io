---
layout: archive
title: "Talks and Seminars"
permalink: /talks/
author_profile: true
---

### Spring 2024 Learning Seminar
Time: Thursday, 1:30 PM to 3:30 PM

Place: 2-255, unless otherwise noted


### Fall 2023 Learning Seminar
Time: Monday, 10 AM to Noon

Place: 2-361

[Syllabus](https://weixiao-lu.github.io/files/Fall_2023_Seminar.pdf)
 
| Speaker          | Date   |           Title/Notes                                          |
| --------         | ------ | ------------------------------------------------------------ |
| Danielle Wang    | Sep. 11   |  Twisted GGP conjecture for unramified quadratic extensions     |
| Murilo Corato Zanarella    | Sep. 18   |     Explicit models of relative spherical functions and a conjecture of Hironaka           |
| Gefei Dang     | Sep. 25   |  Local newforms for generic representations of unitary groups                                     |
|  Kenta Suzuki     | Oct. 16         |  [Orthogonal Shimura varieties and moduli of K3 surfaces](https://weixiao-lu.github.io/files/k3_surface_talk.pdf)         |
|   Hao Peng         | Oct. 23      | Tate conjecture for hyperkähler varieties over number fields  |
|   Ryan Chen    | Oct. 30 | [Integral models of orthogonal Shimura varieties](https://weixiao-lu.github.io/files/Integral_models_I.pdf)|
|   Ryan Chen/ Vijay Srinivasan    | Nov. 13  | [Integral modles II](https://weixiao-lu.github.io/files/Integral_models_II.pdf)  Tate conjecture for K3 surfaces of positive characteristic |
|  Vijay Srinivasan       | Nov. 20 |  Tate conjecture for K3 surfaces of positive characteristic II|
|  Weixiao Lu        | Nov. 27 | Tate conjecture for K3 surfaces of positive characteristic III|
|   Andreas Mihatsch      | Dec. 4  | Average Colmez conjecture|
|   Hao Peng                  | Dec. 11 |    [Local Langlands for GL(n) over p-adic fields](https://weixiao-lu.github.io/files/LLC_for_GL(n).pdf)                |




{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}

