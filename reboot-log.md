---
layout: page
title: Reboot Log
permalink: /reboot-log/
---

{% for log in site.rebootlog reversed %}

## {{ log.date | date: "%d-%b-%Y" }}

{{ log.content }}

---

{% endfor %}
