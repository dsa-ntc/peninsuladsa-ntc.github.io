---
# config
layout: tagline
permalink: /reading-group/
redirect_from:
    - /political-reading/
# display
title: "Reading Group"
tagline: Engaging in ongoing political education in socialist history and thought
---
<head>
<style>
    .map-display{
        display: grid;
        grid-template-columns: 30% 70%;
    }
    .content-pic-display{
        display: grid;
        grid-template-columns: 70% 30%; 
    }
    .pic-column{
        align: right;
        width: 200px;
        height: auto;
    }
</style>
</head>

---
<h2>Upcoming Book Schedule</h2>


> For the winter months, we'll have a series of shorter readings:


{% for book in site.data.books.upcoming %}
    {% if book.sessions.size > 1 %}
##### [{{ book.title }}]({{ book.url }}) by {{ book.author }}
        {% for session in book.sessions %}
            {% if session.location %}
* ##### --- **{{ session.date }} at {{ session.location }}:** Chapters {{ session.chapters }}
            {% else %}
* ##### --- **{{ session.date }}:** Chapters {{ session.chapters }}
            {% endif %}
        {% endfor %}
    {% else %}
        {% assign session = book.sessions[0] %}
        {% if book.printout == true %}
            {% if session.location and session.location != blank %}
##### [{{ book.title }}]({{ book.url }}) by {{ book.author }} --- **{{ session.date }} at {{ session.location }}** (_Free Printouts Available_)
            {% else %}
##### [{{ book.title }}]({{ book.url }}) by {{ book.author }} --- **{{ session.date }}** (_Free Printouts Available_)
            {% endif %}
        {% else %}
            {% if session.location and session.location != blank %}
##### [{{ book.title }}]({{ book.url }}) by {{ book.author }} --- **{{ session.date }} at {{ session.location }}**
            {% else %}
##### [{{ book.title }}]({{ book.url }}) by {{ book.author }} --- **{{ session.date }}**
            {% endif %}
        {% endif %}
    {% endif %}
{% endfor %}


## Meeting Info

<iframe align="right" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1392.297448639672!2d-122.2333827283639!3d37.48656626196101!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x808fa300197b0149%3A0x628d496358370b41!2sFireside%20Books%20%26%20More!5e1!3m2!1sen!2sus!4v1794939919067!5m2!1sen!2sus" width="auto" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="strict-origin-when-cross-origin"></iframe>

#### Date & Time: **Every other Tuesday, 6:15-7:45pm**
#### Place: **Fireside Books & More (2421 Broadway, Redwood City)**

>**Note:** During the Winter, meetings sometimes held at Gourmet Haus Stadt (2615 Broadway, Redwood City; on the other side of the station).

#### [Join virtually on Google Meet](https://meet.google.com/yqs-mvtd-ahn)

#### Bring Your Own Book (Usually)

* Please consider ordering your copy of our reads from our friendly hosts- Andrew and Taylor at [Fireside Books & More](https://firesiderwc.com/):

* *For short readings, printed copies will be handed out at the beginning of meetings or can be found at Fireside Books for free.*

>[Visit their Bookshop.org storefront](https://bookshop.org/shop/FiresideRWC) or email [orders@firesiderwc.com](mailto:orders@firesiderwc.com)


<h4>What To Expect</h4>

* Peninsula DSA's reading group sessions kick off with icebreakers to get to know your fellow comrades, followed by a guided discussion

* Light refreshments and KN94 respirators provided

* If you have it, wearing DSA gear is encouraged! :rose:

* After 7:45, we almost always go to a restaurant nearby to grab dinner and socialize ([typically Gourmet Haus Stadt](https://gourmethausstaudt.com/))


## Past Reads

{% for year in site.data.books.past %}
### {{year.year}}
    {% for book in year.books %}
        {% if book.author and book.author != blank %}
##### [{{ book.title }}]({{ book.url }}) by {{ book.author }}
            {% if book.details and book.details != blank %}
###### --- {{book.details}}
            {% endif %}
        {% else %}
##### [{{ book.title }}]({{ book.url }})
        {% endif %}
    {% endfor %}
    {% if year.pics and year.pics != blank %}
<div style="display: flex; overflow-x: auto; gap: 10px">
        {% for pic in year.pics %}
<img src="/assets/images/pages/reading-group/{{ pic.file }}" alt="{{ pic.alt }}" style="scroll-snap-align: start; height: 300px; flex-shrink: 0;">
        {% endfor %}
</div>
    {% endif %}
{% endfor %}
