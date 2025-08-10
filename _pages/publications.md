---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="https://scholar.google.com/citations?user=TqMFlMYAAAAJ&hl=en">my Google Scholar profile</a> and <a href="https://ieeexplore.ieee.org/author/949288735174528">my IEEE Xplore author page</a>.</div>
{% endif %}


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
