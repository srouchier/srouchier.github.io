---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Click on the title on a publication below to see an extended description, and a link to the code used in it if relevant.

You can also see the list of my publications on [my ORCID profile](https://orcid.org/0000-0002-8942-1244) or on [Google Scholar](https://scholar.google.fr/citations?user=qa8nWbQAAAAJ&hl=fr&oi=ao).

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
