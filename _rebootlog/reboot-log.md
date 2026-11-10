layout: page title: Reboot Log permalink: /reboot-log/
Reboot Log
A collection of short notes, discoveries, links, project updates, and observations.

Think of it as the part of social media I actually enjoyed, except it lives on my own website.

{% assign logs = site.rebootlog | sort: "date" | reverse %}

{% for log in logs %}

{{ log.date | date: "%d %B %Y" }}
{{ log.content }}
{% endfor %}
