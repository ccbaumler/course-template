---
layout: page
title: Schedule
description: The weekly event schedule.
---

# Google scehdule

- [Lecture, Discussion, and Special Events Calendar](#ldlc)

{: .note }

> If you are having trouble viewing the calendars below and are using Safari, we suggest switching to an alternate browser (like Chrome). Alternatively, you can go to Safari settings and switch "Prevent cross-site tracking" off, or you can see the _Lecture, Discussion, and Special Events Calendar_ [here](https://calendar.google.com/calendar/embed?height=600&wkst=1&ctz=America%2FLos_Angeles&showPrint=0&mode=WEEK&src=Y19hYzMyNWI4ZWJjNjA4OWMxZTY5Y2Q2Yjk1MGI5ZmNlOThiZWYwMThjNTM0NDkxNzMzY2YyZWUyZGY3NjRiYWQ1QGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20&color=%233f51b5).

<a name='ldlc'></a>

## Lecture, Discussion, and Special Events Calendar

This calendar contains times for

- Lectures (in **brown**)
- In-person discussion sections (in **yellow**)
- Remote discussion sections (in **blue**)
<!-- - Exam prep sections and other reviews (in **green**) -->

<!-- **Note: All events on this calendar are virtual.** -->

<!-- To access these events, use the Zoom links posted in <b><a href="">@6 on Piazza</a></b>. -->

<iframe data-a11y-errors="true" title="Google Calendar of Course Events" src="https://calendar.google.com/calendar/embed?height=600&wkst=1&ctz=America%2FLos_Angeles&showPrint=0&mode=WEEK&src=Y19hYzMyNWI4ZWJjNjA4OWMxZTY5Y2Q2Yjk1MGI5ZmNlOThiZWYwMThjNTM0NDkxNzMzY2YyZWUyZGY3NjRiYWQ1QGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20&color=%233f51b5" style="border:solid 1px #777" width="800" height="600" frameborder="0" scrolling="no"></iframe>

# Weekly Schedule

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
