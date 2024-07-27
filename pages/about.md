---
layout: page
title: About
description: On My Way
keywords:
comments: true
menu: About
permalink: /about/
---

<ul>
{% for website in site.data.social %}
<li>{{website.sitename }}：<a href="{{ website.url }}" target="_blank">@{{ website.name }}</a></li>
{% endfor %}
{% if site.url contains 'clairechn.github.io' %}
{% endif %}
</ul>

<!-- ## Skill Keywords

{% for skill in site.data.skills %} -->

<!-- ### {{ skill.name }}

<div class="btn-inline">
{% for keyword in skill.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %} -->
