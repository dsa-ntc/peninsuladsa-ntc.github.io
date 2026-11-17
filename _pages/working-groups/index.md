---
layout: group
title: "Working Groups"
permalink: "/working-groups/"
tagline: Our working groups organize socialist campaigns and/or join coalitions around issues that empower the working class
---
---
<h3>Currently Active</h3>

{% for page in site.pages %}
    {% if page.permalink contains '/working-groups/' and page.name != 'index.md' and page.name != 'index.html' and page.current == true %}

<a href = "{{ page.permalink }}"><h4>{{ page.emoji }} {{ page.wg }} {{ page.emoji-1 }}</h4></a>
<h5><i>{{ page.tagline }}</i></h5>

> {{page.description}}

* _Meets {{page.meetings}}, discussion in **#{{ page.discord }}**_

    {% endif %}
{% endfor %}

---
<h3>Past Work</h3>

<h5> Some of our working groups are not currently meeting. However, if you are interested in fighting for the working class in these areas,  you should help us get them active again and build upon our past efforts.</h5>

{% for page in site.pages %}
    {% if page.permalink contains '/working-groups/' and page.name != 'index.md' and page.name != 'index.html' and page.current != true %}
    {% if page.current == 'show' %}

<a href = "{{ page.permalink }}"><h4>{{ page.emoji }} {{ page.wg }}</h4></a>

    {% else %}

<h4>{{ page.emoji }} {{ page.wg }}</h4>

    {% endif %}

<h5><i>{{ page.tagline }}</i></h5>

> {{ page.description}}
    
    {% endif %}
{% endfor %}

<!-- <h4>:fist: Labor</h4>
Our [Labor](../labor/) working group continues to show solidarity with local unions--especially [AFSCME Local 829](https://www.afscme57.org/afscme-local-829), [AFT 1493](https://aft1493.org/), and [Teamsters Local 2785](https://www.teamsters2785.org/)—-on the picket line, at board meetings, and anywhere we're needed.

* _Read more [here](../labor/) and join your labor-minded comrades on the **PDSA Discord: #labor**_

<h4>:station: Public Transit</h4>
With a mandate from our 2024 convention, Peninsula DSA developed our own Transit 4 All campaign in coalition with our friends at [Transbay Coalition](https://www.transbaycoalition.org/). Recently we were focused on saving BART and Caltrain with a regional funding measure (SB 63), but our ultimate goal is pushing for (1) free fares for SamTrans and (2) making the countywide El Camino Real corridor safe for people of all ages to walk, bike, and ride transit!

* _Read more [here](../public-transit/) and join your public transit-loving comrades on the **PDSA Discord: #transit**_


<h4>:city_sunrise: Housing</h4>
Our [Housing](../working-groups/housing/) working group seeks to fight corporate greed and guarantee dignified housing for all. Peninsula DSA is organizing with [Faith in Action Bay Area](https://faithinactionba.org/san-mateo-county/)'s coalition to win rent control and tenant protections in Redwood City through a 2026 citizens' ballot measure campaign. 

* _Read more [here](../working-groups/housing/) or on the **PDSA Discord: #housing** and **#affordable-rwc**_

<h4>:children_crossing: Universal Preschool</h4>
Our [Universal Preschool](../preschool-for-all/) working group, which spearheaded the [Yes on Measure DD](https://www.facebook.com/yesonddssf/) / [Preschool for All South San Francisco](https://www.instagram.com/yesonddssf/) ballot measure campaign (2022) organized for universal preschool in San Mateo County. 

* _Read more [here](../preschool-for-all/) or on the **PDSA Discord: #universal-preschool**_

<h4>:earth_africa: Ecosocialism</h4>
Our [Ecosocialism](../ecosocialism/) working group organized for building energy justice and holding PG&E accountable for its dirty, dangerous, and unreliable fossil-fuel energy. We have run workshops on making DIY air purifiers to protect against wildfire smoke and airborne pathogens, and have distributed money-saving energy efficiency tips to renters.

* _Read more [here](../ecosocialism/) or on the **PDSA Discord: #ecosocialism**_

<h4>:hospital: Healthcare Justice</h4>
Our [Healthcare Justice](../healthcare-justice/) working group organized for Medicare for All. We endorsed and supported the California Nurses Association's (CNA) statewide universal healthcare campaign, [CalCare](https://www.nationalnursesunited.org/calcare).  Though AB 1690 and then AB 2200 didn't make it to the floor of the California legislature, Guaranteed Healthcare for All bill will be back again—and we'll be there to fight for it.

* _Read more [here](../healthcare-justice/) or on the **PDSA Discord: #healthcare**_ -->