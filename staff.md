---
layout: page
title: Staff
description: A listing of all the course staff members.
---

# People

Staff information is stored in the `_staffers` directory and rendered according to the layout file, `_layouts/staffer.html`.

## Instructor

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign participants = site.staffers | where: 'role', 'Participant' %}
{% assign num_participants = participants | size %}
{% if participants != 0 %}

## Participants

{% for staffer in participants %}
{{ staffer }}
{% endfor %}
{% endif %}

