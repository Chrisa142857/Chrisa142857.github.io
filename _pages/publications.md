---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

# Highlighted publications

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

# All publications

<script src="https://bibbase.org/show?bib=https%3A%2F%2Fbibbase.org%2Fnetwork%2Ffiles%2FcebNHWyS7v2h35hbv&noBootstrap=1&jsonp=1"></script>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<br/>
