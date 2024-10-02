---
layout: archive
title: "List of publications"
permalink: /publications/
author_profile: true
---

![](/images/vials1.jpg){:height="100px"} ![](/images/petri.jpg){:height="100px"}

For a up-to-date publication list, please check my [Google Scholar profile](https://scholar.google.fr/citations?user=1rPv6m4AAAAJ&hl=fr)  

___

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
