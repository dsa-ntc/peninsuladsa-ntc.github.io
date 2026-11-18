---
layout: page
title: "News"
permalink: /news/
---
---
### Recommended Sources

Free yourself from corporate-approved content by seeking out progressive and leftist media sources. Peninsula DSA's Steering Committee has many recommendations:

* [Bay Area Current](https://bayareacurrent.com/) - the Bay Area’s brand-new leftist news site covers working-class life and culture
* [California Red](https://www.californiadsa.org/news) - the bimonthly newsletter of [California DSA](https://www.californiadsa.org/) (check out [our ecosocialist article](https://www.californiadsa.org/news/batransit-2025jun))!
* [Democratic Left](https://democraticleft.dsausa.org/) - the official magazine of DSA 🌹
* [Socialist Forum](https://socialistforum.dsausa.org/) - a open and wide-ranging venue for thoughtful discussion and debate among DSA members
* [Other news, podcasts, video essays, and more](/recommended-media/)

---
### Recent statements by Peninsula DSA

{% for post in site.posts %}
### [{{post.date | date: "%b %-d, %Y"}}]({{ post.url }})
#### {{ post.title }}
##### {{ post.short_description }}
{% endfor %}
