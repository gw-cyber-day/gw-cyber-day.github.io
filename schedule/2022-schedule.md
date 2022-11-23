---
layout: 2022_page
title: Schedule
---

## Schedule

* **830-900 : Arrival/Breakfast**

* **900-915: Opening Remarks**
  * Pamela M. Norris -- Vice Provost
  * John Lach -- Dean of the School of Engeering

* **915-930: Introductions from the Audience**
 

* **930-1050: Rapid Research Talks (7 minutes with 3 minutes of questions)**
{% if site.data.2022_participants.pis %}
{% for part in site.data.2022_participants.pis %}
{% if part.talk %}
  * {{ part.name }} -- {{part.title}}
    * *{{part.talk}}*
{% endif %}
{% endfor %}
{% endif%}


* **1050-1115: Break/Coffee**

* **1115-1215: Panel on cybersecurity educational offerings at GW**
  * Moderators: Costis Toregas and Scott J. White
  
* **1215-200: Lunch and Research Poster Session**

* **200-330: Breakout Groups**

* **330-400: Break/Coffee**

* **400-500: Town hall on future of support elements and cybersecurity@GW long term efforts**

* **500-530: Out-brief discussion and next steps**


