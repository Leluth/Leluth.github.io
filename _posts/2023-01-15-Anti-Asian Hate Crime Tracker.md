---
layout: post
topmost: false
title: Anti-Asian Hate Crime Tracker
categories: Python Scrapy Docker Nginx
description: Anti-Asian Hate Crime Tracker
keywords: FullStackWebsite
---

Time: Jan.2022 - Jan.2023 &emsp; Location: Seattle, USA

![register&login](/images/posts/python/Anti-Asian-Hate-Crime-Tracker.png)

Volunteered to work with a team of 4 engineers to develop a crawler that feeds hate incident data to the backend of [Anti-Asian Hate Crime Tracker](https://hatecrimetracker.1thing.org), a website designed to increase awareness of Anti-Asian hate.

Built distributed web crawlers with Scrapy. Created Docker files to run crawlers and proxy service in a portable multi-container application. Protected crawler services by setting up Nginx server authentication.

Developed integrated Scrapy item pipelines to support message push service in multiple platforms including Slack APP, Google Drive and Algolia.

Implemented distributed crawling, URL/URI deduplication and established the data access layer by applying Scrapy-Redis. It effectively filtered duplicate contents and improved the crawler efficiency by 42%.

