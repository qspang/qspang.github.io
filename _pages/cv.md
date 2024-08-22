---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. South China University of Technology , 2021 (expected)

Work experience
======
* Summer 2015: Research Assistant
  * Dingjia
  * Duties included: C++Y R&D

  
Skills
======
* Skill 1 ：C++ Python Java
* Skill 2 ：DL ML


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
# Talks
======
  <ul>
    {% for post in site.talks reversed %}
      <!-- 对每个演讲项目进行循环，并在每次迭代中包含 archive-single-talk-cv.html 模板 -->
      {% include archive-single-talk-cv.html  %}
    {% endfor %}
  </ul>

# Teaching
======
  <ul>
    {% for post in site.teaching reversed %}
      <!-- 对每个教学项目进行循环，并在每次迭代中包含 archive-single-cv.html 模板 -->
      {% include archive-single-cv.html %}
    {% endfor %}
  </ul>

# Service and leadership
======
  <!-- 列出服务和领导力部分的一些信息，这里只有一个项目：当前加入的 Slack 团队数量 -->
  * Currently signed in to 43 different slack teams
