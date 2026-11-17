---
layout: page
title: "Committees"
permalink: "/committees/"
---

<h4>Our committees steer the growth and development of Peninsula DSA and its members - to increase our capacity to lead the working class in the struggle against Capitalism</h4>

---

{% for page in site.pages %}
    {% if page.permalink contains '/committees/' and page.name != 'index.md' and page.name != 'index.html' %}

<a href = "{{ page.permalink }}"><h4>{{ page.emoji }} {{ page.cm }}</h4></a>
<h5>{{ page.tagline }}</h5>
{{page.description}}
*Meets {{page.meetings}}, discussion in **#{{ page.discord }}***

    {% endif %}
{% endfor %}

---