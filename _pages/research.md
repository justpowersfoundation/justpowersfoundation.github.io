---
layout: single
title: "Research"
permalink: /research/
---

# Research Publications

The Just Powers Foundation produces original research on issues of liberty, governance, and public policy. Our publications are available for download and provide in-depth analysis of current policy debates.

## Featured Reports

{% for post in site.research %}
  {% if post.featured %}
<div class="research-item featured">
  <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  <p class="research-date">{{ post.date | date: "%B %d, %Y" }}</p>
  <p class="research-excerpt">{{ post.excerpt }}</p>
  <a href="{{ post.url }}" class="btn btn--small">Read Full Report</a>
</div>
  {% endif %}
{% endfor %}

## All Research Publications

{% for post in site.research %}
<div class="research-item">
  <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  <p class="research-date">{{ post.date | date: "%B %d, %Y" }}</p>
  <p class="research-excerpt">{{ post.excerpt }}</p>
  <a href="{{ post.url }}" class="btn btn--small">Read Report</a>
</div>
{% endfor %}

## Research Areas

- **Constitutional Law**: Analysis of constitutional limits on government power
- **Economic Policy**: Studies on free markets and economic freedom
- **Property Rights**: Examination of property rights in emerging contexts
- **Regulatory Reform**: Proposals for reducing regulatory burdens
- **Fiscal Policy**: Analysis of taxation and government spending

## Subscribe to Updates

Stay informed about our latest research publications by subscribing to our newsletter or following us on social media.

[Subscribe to Newsletter](#newsletter-signup)