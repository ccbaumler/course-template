---
layout: home
title: Stat Adv.
nav_exclude: true
seo:
  type: Course
  name: Stat 101 all the course materials
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

## Welcome to Statistics 101! :bar_chart: 

```
The link to this webpage is [{{site.url}}{{ site.baseurl }}]({{site.url}}{{ site.baseurl }}).
```

Use links at the top right of this page to access the school appropriate learning management system resources (most were mentioned in the [Syllabus]({{site.url}}{{ site.baseurl }}/about/#course-tools)).

This static site is provided as a convenience for quick access and searching of course materials.

{% if site.announcements %}
{{ site.announcements.last }}
[Previous Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}
