---
layout: 2024_post
title: People
cover: phage.jpg
permalink: /2024/people
---

All emails are given as `<name>@caltech.edu` unless otherwise specified. 


## Instructor

{% for author in site.data.2024.members %}
{% if author.role == 'Professor' %}
<div id="im">
<figure>
<b> <a href="{{ author.link }}">{{ author.name }}</a></b><br/>
<img width='200' height='200' src="{{ site.baseurl }}/2024/assets/images/people/{{ author.image }}"><br/>
({{ author.pronouns }})<br/>
<figcaption>
<code>{{ author.email }}</code>
</figcaption>

</figure>
</div>
{% endif %}
{% endfor %}



## Teaching Assistants

{% for author in site.data.2024.members %}
{% if author.role != 'Professor' %}
<div id="im">
<figure>
<b> {{ author.name }} </b><br/>
<img src="{{ site.baseurl }}/2024/assets/images/people/{{ author.image }}" width="200" height="200"><br/>
<figcaption>
<i> {{ author.year }} - {{ author.major }}</i><br/>
({{ author.pronouns }})<br/>
<code>{{ author.email }}</code>
</figcaption>
</figure>
</div>
{% endif %}
{% endfor %}
