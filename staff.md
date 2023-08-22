---
layout: page
title: Staff
description: A listing of all the course staff members.
nav_order: 10
---

# Staff
### Add 'berkeley.edu' to the end of all emails.

## Instructor

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
<div class="role">
  {% for staffer in instructors %}
  {{ staffer }}
  {% endfor %}
</div>

## Head Teaching Assistant (Head TA)

{% assign HeadTA = site.staffers | where: 'role', 'Head TA' %}
<div class="role">
  {% for staffer in HeadTA %}
  {{ staffer }}
  {% endfor %}
</div>


## Admin Teaching Assistant (Admin TA)

{% assign AdminTA = site.staffers | where: 'role', 'Admin TA' %}
<div class="role">
  {% for staffer in AdminTA %}
  {{ staffer }}
  {% endfor %}
</div>

## Lab Teaching Assistants (Lab TA)

{% assign LabTA = site.staffers | where: 'role', 'Lab TA' %}
<div class="role">
  {% for staffer in LabTA %}
  {{ staffer }}
  {% endfor %}
</div>

## Office Hour Teaching Assistants (OH TA)

{% assign OHTA = site.staffers | where: 'role', 'OH TA' %}
<div class="role">
  {% for staffer in OHTA %}
  {{ staffer }}
  {% endfor %}
</div>


## Academic Interns (AIs)

{% assign ai = site.staffers | where: 'role', 'AI' %}
<div class="role">
  {% for staffer in ai %}
  {{ staffer }}
  {% endfor %}
</div>
