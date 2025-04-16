---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on [my Google Scholar profile](https://scholar.google.com/citations?user=UwWnVeAAAAAJ&hl=en).

<form action="https://www.jung.ms/citations.txt">
  <input type="id" value="UwWnVeAAAAAJ">
  <input type="lang" value = "en">
</form>


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
