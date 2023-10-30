---
permalink: /
title: "Intelligent Unmanned Systems Laboratory at Westlake University"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome to our project page on GitHub. This page shows our recent research work.

Our lab, the Intelligent Unmanned Systems Laboratory at Westlake University, focuses on novel theories and applications of robotic systems, especially multi-robot systems. We are interested in next-generation robotic systems that are interesting, meaningful, and challenging to study.

For more information, please visit our [group website](https://shiyuzhao.westlake.edu.cn/) and [Professor Shiyu Zhao’s homepage](https://www.shiyuzhao.net/).

### Recent research work

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}