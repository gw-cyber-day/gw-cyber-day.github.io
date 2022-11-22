---
layout: 2022_page
title: Participants
---

# 2022 Registered Participants

* [University and School Leadership](#leadership)
* [Faculty, Researchers or Principal Investigators](#faculty)
* [Research and Support Staff](#staff)
* [Research Students](#rstudents)
* [Students](#ostudents)

{% if site.data.2022_participants.leadership %}
<a id="leadership"></a>
## University and School Leadership
<table class="part-table">
{% for part in site.data.2022_participants.leadership %}
{% include bio_row.html %}
{% endfor %}
</table>
{% endif %}


{% if site.data.2022_participants.pis %}
<a id="faculty"></a>
## Faculty, Researchers or Principal Investigators
<table class="part-table">
{% for part in site.data.2022_participants.pis %}
{% include bio_row.html %}
{% endfor %}
</table>
{% endif %}

{% if site.data.2022_participants.staff %}
<a id="staff"></a>
## Research or Support Staff
<table class="part-table">
{% for part in site.data.2022_participants.staff %}
{% include bio_row.html %}
{% endfor %}
</table>
{% endif %}

{% if site.data.2022_participants.rstudent %}
<a id="rstudents"></a>
## Research Graduate Students
<table class="part-table">
{% for part in site.data.2022_participants.rstudent %}
{% include bio_row.html %}
{% endfor %}
</table>
{% endif %}

{% if site.data.2022_participants.ostudent %}
<a id="ostudents"></a>
## Students
<ul>
{% for part in site.data.2022_participants.ostudent %}
<li> {{ part.name }} </li>
{% endfor %}
</ul>
{% endif %}



To be added to the list of participants, please register.

<div class="reg-link">
<a href="https://docs.google.com/forms/d/e/1FAIpQLScMXPSUulo4vDVfhJA5t7L1RQPIPueJ4weK7bUJSjUZi7yjAQ/viewform?usp=sf_link:">
<button>Register</button>
</a>
</div>
