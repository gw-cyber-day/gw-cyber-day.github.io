---
layout: 2022_page
title: Participants
---

# 2022 Registered Participants

{% if site.data.2022_participants.leadership %}
## University and School Leadership
<table class="part-table">
{% for part in site.data.2022_participants.leadership %}
{% include bio_row.html %}
{% endfor %}
</table>
{% endif %}


{% if site.data.2022_participants.pis %}
## Faculty, Researcher or Principal Investigator
<table class="part-table">
{% for part in site.data.2022_participants.pis %}
{% include bio_row.html %}
{% endfor %}
</table>
{% endif %}

{% if site.data.2022_participants.staff %}
## Research or Support Staff
<table class="part-table">
{% for part in site.data.2022_participants.staff %}
{% include bio_row.html %}
{% endfor %}
</table>
{% endif %}


To be added to the list of participants, please register.

<div class="reg-link">
<a href="https://docs.google.com/forms/d/e/1FAIpQLScMXPSUulo4vDVfhJA5t7L1RQPIPueJ4weK7bUJSjUZi7yjAQ/viewform?usp=sf_link:">
<button>Register</button>
</a>
</div>
