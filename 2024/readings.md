---
layout: 2024_post
title: Readings
cover: readings.jpg
permalink: /2024/readings
---

## In-Class Readings
There is so much fascinating biology to explore --- far more than we could ever cover in a single quarter of an introductory course.
Instead, we will often point you to excellent readings that serve as opportunities to continue your adventure your own way.
We will list them here as the course progresses.
Interacting with these readings is entirely optional, but highly encouraged.

{% assign readings = site.data.2024.papers %}

{% for week in readings %}

### {{ week[0] }}

{% for p in week[1] %}
{% if p.link != None %}
[{{ p.title }}]({{ p.link }}) by {{ p.author }} *{{ p.journal }}* ({{ p.year }}). {{ p.description }}
{% else %}
{{p.title}} by {{ p.author }} *{{ p.journal }}* ({{ p.year }}). {{ p.description }}
{% endif %}
{% endfor %}
{% endfor %}

## External Resources
Links to external databases and other resources that you may find helpful during the course.

* [The Bionumbers Database](https://bionumbers.hms.harvard.edu/search.aspx). An incredibly handy collection of numbers from the molecular and cell biology literature.

* [The Human Impacts Database](https://anthroponumbers.org/). Useful quantities describing the interactions of humans with Earth's land, oceans, atmosphere, flora and fauna.

* [Street-Fighting Mathematics: The Art of Educated Guessing and Opportunistic Problem Solving](https://sept.mit.edu/sites/default/files/Streetfighting%20Mathematics.pdf). This excellent free book by Sanjoy Mahajan (a Caltech alum!) teaches order-of-magnitude estimation in the same style that we will employ throughout the course. Essential reading for those curious to explore more advanced techniques than those we will cover.