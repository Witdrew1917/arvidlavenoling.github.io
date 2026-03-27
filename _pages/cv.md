---
layout: single
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

## Education

* **Ph.D** in ... , Chalmers University of Technology / Zenseact (ongoing)
* **M.Sc.** in ..., *University*, year
* **B.Sc.** in ..., *University*, year

## Work Experience

* **Industrial PhD Student**, Zenseact AB — *year–present*
  * Research on autonomous driving: prediction and planning

*(Replace the above with your actual education and work history)*

## Skills

* Skill 1
* Skill 2
* Skill 3

## Publications

<ul>
{% for post in site.publications reversed %}
  <li><a href="{{ post.url }}">{{ post.title }}</a> — {{ post.venue }}, {{ post.date | date: "%Y" }}</li>
{% endfor %}
</ul>

## Teaching

<ul>
{% for post in site.teaching reversed %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
