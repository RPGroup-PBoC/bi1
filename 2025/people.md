---
layout: 2025_post
title: People
cover: phage.jpg
permalink: /2025/people
---

All emails are given as `<name>@caltech.edu` unless otherwise specified. 

The course ombuds this quarter are **tbd**.

## Instructor

{% for author in site.data.2025.members %}
{% if author.role == 'Professor' %}
<div id="im">
<figure>
<b> <a href="{{ author.link }}">{{ author.name }}</a></b><br/>
<img width='200' height='200' src="{{ site.baseurl }}/2025/assets/images/people/{{ author.image }}"><br/>
<figcaption>
{{ author.major }}<br/>
({{ author.pronouns }})<br/>
<code>{{ author.email }}</code>
</figcaption>
</figure>
</div>
{% endif %}
{% endfor %}


## Head Teaching Assistants

{% for author in site.data.2025.members %}
{% if author.role == 'HTA' %}
<div id="im">
<figure>
<b> {{ author.name }} </b><br/>
<img src="{{ site.baseurl }}/2025/assets/images/people/{{ author.image }}" width="200" height="200"><br/>
<figcaption>
{{ author.year }}, {{ author.major }}<br/>
({{ author.pronouns }})<br/>
<code>{{ author.email }}</code>
</figcaption>
</figure>
</div>
{% endif %}
{% endfor %}

## Teaching Assistants

{% for author in site.data.2025.members %}
{% if author.role == 'TA' %}
<div id="im">
<figure>
<b> {{ author.name }} </b><br/>
<img src="{{ site.baseurl }}/2025/assets/images/people/{{ author.image }}" width="200" height="200"><br/>
<figcaption>
{{ author.year }}, {{ author.major }}<br/>
({{ author.pronouns }})<br/>
<code>{{ author.email }}</code>
</figcaption>
</figure>
</div>
{% endif %}
{% endfor %}
