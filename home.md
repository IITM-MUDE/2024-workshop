---
layout: home
title: Home Page
description: Home Page
nav_order: 1
nav_exclude: false
permalink: /:path/
seo:
  type: Course
  name: Home
---

# Welcome to the MUDE in Madras
{:.no_toc}

_Workshop participants should view this page as a_ **Student**{: .label .label-green }

*This page shows the most recent announcement. Frequently used pages are found via the links at the top right.*

Demonstration edit. Something.

*See [Course Info page]({{ site.baseurl }}/info) for additional information.*

### Most recent announcement

*A record of previous announcements can be found on the [All Announcements page]({{ site.baseurl }}/announcements).*

{% if site.announcements %}
{{ site.announcements.last }}
[Previous Announcements](announcements){: .btn .btn-outline .fs-3 }
{% endif %}

