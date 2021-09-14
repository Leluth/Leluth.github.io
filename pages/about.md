---
layout: page
title: About Me
description: Make it work, make it right, make it fast.
keywords: Shaoshuai Xu
comments: true
menu: About Me
permalink: /about/
---

Hi there

## Contact Me

<ul>
<li>Email: shaoshuaixu21@gmail.com</li>
{% for website in site.data.social %}
<li>{{website.sitename }}：<a href="{{ website.url }}" target="_blank">@{{ website.name }}</a></li>
{% endfor %}
</ul>


## Skill Keywords

{% for skill in site.data.skills %}
### {{ skill.name }}
<div class="btn-inline">
{% for keyword in skill.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
