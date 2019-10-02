---
layout: archive
title: "Courses Taken"
permalink: /courses/
author_profile: true
---

{% include base_path %}

Relevant Courses Taken
=======
*Software Construction and User Interface
*Advanced Programming Techniques
*Software Architecture and Design
*Design and Analysis of Algorithms
*Software Testing
*Fundamental Concepts in Computer Networking

{% for post in site.courses reversed %}
  {% include archive-single.html %}
{% endfor %}
