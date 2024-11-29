---
layout: page
title: Announcements
nav_exclude: false
nav_order: 3
description: A feed containing all of the class announcements.
---

# Announcements

_This page lists all of the announcements._

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}
