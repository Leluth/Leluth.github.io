---
layout: page
title: About Me
description: Make it work, make it right, make it fast.
keywords: Shaoshuai Xu
comments: true
menu: About Me
permalink: /about/
---

## Summary

Experienced software engineer with strong programming, analytical and mathematical skills. Has a wide range of software development internships (iFlytek, etc.) and project experience, including mobile application development with Flutter, full-stack web development with Go, React, Spring, Hibernate, 5+years of programming experience for large-scale system development.

## Skill Keywords

{% for skill in site.data.skills %}
### {{ skill.name }}
<div class="btn-inline">
{% for keyword in skill.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}

## Awards

- UNDP Youth Co:lab “National Dialogue”(Second Runner up of the “Start-up” Group, 2018)
- Chinese Undergraduate Computer Design Contest (Third Prize, 2018)
- Alibaba Cloud Campus Geek Competition (Second Prize, 2018)
- “Chuang Qingchun” Hubei College Student Entrepreneurship Competition (Silver award, 2018)
- SK SUNNY Happinnovator Contest (Second Prize, 2018)
- “Seek Truth Cup” HUST Academic and Technology Works Competition (First Prize, 2019)

## Contact Me

<ul>
<li>Email: shaoshuaixu21@gmail.com</li>
{% for website in site.data.social %}
<li>{{website.sitename }}：<a href="{{ website.url }}" target="_blank">@{{ website.name }}</a></li>
{% endfor %}
</ul>