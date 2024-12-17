---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
(\* denotes equal contribution, up-to-date list [here](https://scholar.google.com/citations?hl=en&user=a3AbXGcAAAAJ&view_op=list_works))

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


