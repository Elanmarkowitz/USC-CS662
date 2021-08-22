---
layout: page
title: Staff
description: A listing of all the course staff members.
---

# Staff

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% assign num_instructors = instructors | size %}

{% if num_instructors != 0 %}
{% if num_instructors == 1 %}
## Instructor
{% else %}
## Instructors
{% endif %}


{% for staffer in instructors %}
{{ staffer }}
{% endfor %}
{% endif %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
{% if num_teaching_assistants == 1 %}
## Teaching Assistant
{% else %}
## Teaching Assistants
{% endif %}


{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}
