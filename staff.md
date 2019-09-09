---
layout: page
title: Staff
nav_order: 5
description: A listing of all the course staff members.
---

# Staff

Jump to [Instructors](#inst), [Teaching Assistants](#tas), or [Readers](#readers)

**Note:** Some office hours may change week-to-week. Consult the [calendar](http://ds100.org/fa19/calendar) for the most up-to-date office hours for each GSI.

<a name = 'inst'></a>

## Instructors

<div class="role">
  {% assign instructors = site.staffers | where: 'role', 'Instructor' %}
  {% for staffer in instructors %}
  {{ staffer }}
  {% endfor %}
</div>

<a name = 'tas'></a>

## Teaching Assistants

<div class="role">
  {% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
  {% for staffer in teaching_assistants %}
  {{ staffer }}
  {% endfor %}
</div>

<a name = 'readers'></a>

## Readers

<div class="role">
  {% assign readers = site.staffers | where: 'role', 'Reader' %}
  {% for staffer in readers %}
  {{ staffer }}
  {% endfor %}
</div>
