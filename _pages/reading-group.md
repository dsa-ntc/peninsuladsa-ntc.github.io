---
layout: tagline
title: "Reading Group"
permalink: /reading-group/
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


###### For the winter months, we'll have a series of shorter readings:


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
        {% if session.location and session.location != blank %}
##### [{{ book.title }}]({{ book.url }}) by {{ book.author }} --- **{{ session.date }} at {{ session.location }}**
        {% else %}

##### [{{ book.title }}]({{ book.url }}) by {{ book.author }} --- **{{ session.date }}**
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


<h3>2024</h3>
* [Ideas for the Struggle](https://www.oldandnewproject.net/Essays/Harnecker_Ideas.html) (2004, revised 2016) by Marta Harnecker.
* [San Francisco Reds: Communists in the Bay Area, 1919-1958](https://www.press.uillinois.edu/books/?id=p087936) (2024) by Robert W. Cherny.
* [Palo Alto: A History of California, Capitalism, and the World](https://www.hachettebookgroup.com/titles/malcolm-harris/palo-alto/9780316592031/?lens=little-brown) (2023) by Malcolm Harris.

<h3>2023</h3>
* [The Wretched of the Earth](https://groveatlantic.com/book/the-wretched-of-the-earth/) (1961) by Frantz Fanon.

<h3>2022</h3>
* [_How to Read Marx's_ Capital](https://monthlyreview.org/product/how-to-read-marxs-capital/) (2021) by Michael Heinrich, in tandem with [_Capital: A Critique of Political Economy_](https://www.marxists.org/archive/marx/works/1867-c1/) by Karl Marx
* [How to Blow Up a Pipeline](https://www.versobooks.com/books/3665-how-to-blow-up-a-pipeline) (2021) by Andreas Malm ([Ecosocialism WG](https://peninsuladsa.org/ecosocialism/) crossover!)
* [The Jakarta Method: Washington's Anticommunist Crusade and the Mass Murder Program that Shaped Our World](https://www.publicaffairsbooks.com/titles/vincent-bevins/the-jakarta-method/9781541724013/) (2020) by Vincent Bevins
* [Why Marx Was Right](https://yalebooks.yale.edu/book/9780300231069/why-marx-was-right/) (2011) by Terry Eagleton

<h3>2021</h3>
* "Capitalism and Class Struggle" (2020) by Vivek Chibber, from [_The ABCs of Capitalism_](https://bit.ly/abcsofcapitalism) series from [Jacobin](https://jacobin.com/) and [Catalyst Journal](https://catalyst-journal.com/)
* "Capitalism and the State" (2020) by Vivek Chibber, from [_The ABCs of Capitalism_](https://bit.ly/abcsofcapitalism) series from [Jacobin](https://jacobin.com/) and [Catalyst Journal](https://catalyst-journal.com/)
* "Understanding Capitalism" (2020) by Vivek Chibber, from [_The ABCs of Capitalism_](https://bit.ly/abcsofcapitalism) series from [Jacobin](https://jacobin.com/) and [Catalyst Journal](https://catalyst-journal.com/)

<h3>2020</h3>
* ['Disband, Disempower, and Disarm': Amplifying the Theory and Practice of Police](https://link.springer.com/article/10.1007/s10612-018-9400-4) (2018) by Meghan G. McDowell and Luis A. Fernandez
* [Mistaken Identity: Mass Movements and Racial Identity](https://www.versobooks.com/products/708-mistaken-identity) (2018) by Asad Haider
* [No Shortcuts: Organizing for Power in the New Gilded Age](https://janemcalevey.com/book/no-shortcuts-organizing-for-power-in-the-new-gilded-age/) by Jane McAlevey
* [On Contradiction](https://www.marxists.org/reference/archive/mao/selected-works/volume-1/mswv1_17.htm) (1937) by Mao Zedong
* [On Practice](https://www.marxists.org/reference/archive/mao/selected-works/volume-1/mswv1_16.htm) (1937) by Mao Zedong
* [Production for Use](https://www.marxists.org/archive/lawrence/1983/production_use.htm) (1983) by Pieter Lawrence
* [Stalinism and Bolshevism: In Defense of October](https://marxist.com/stalinism-bolshevism-trotsky.htm) by Leon Trotsky
* [War is a Racket](https://archive.org/details/WarIsARacket) (1935) by Major General Smedley Butler

<h3>2019</h3>
* [Are Prisons Obsolete?](https://decolonisesociology.com/wp-content/uploads/2019/03/angela-davis-are_prisons_obsolete.pdf) (2003) by Angela Y. Davis
* [Capitalist Realism: Is There No Alternative?](https://files.libcom.org/files/Capitalist%20Realism_%20Is%20There%20No%20Alternat%20-%20Mark%20Fisher.pdf) (2009) by Mark Fisher
* [Civil Disobedience](https://blogs.law.columbia.edu/uprising1313/files/2017/10/Civil-Disobedience-by-Henry-David-Thoreau.pdf) (1849) by Henry David Thoreau
* The Color of Law: A Forgotten History of How Our Government Segregated America (2017) by Richard Rothstein
* [The Communist Manifesto](https://www.marxists.org/archive/marx/works/1848/communist-manifesto/index.htm) (1848) by Friedrich Engels and Karl Marx
* [In Defense of Housing: The Politics of Crisis](https://www.versobooks.com/products/191-in-defense-of-housing?) (2016) by David J. Madden and Peter Marcuse
* [Pedagogy of the Oppressed](https://envs.ucsc.edu/internships/internship-readings/freire-pedagogy-of-the-oppressed.pdf) (1968) by Paolo Friere
* ["The Strategy of International Class Struggle and the Political Fight Against Capitalist Reaction in 2019"](https://www.wsws.org/en/articles/2019/01/03/pers-j03.html) (January 3, 2010) by James Cogan, Joseph Kishore, and David North
* ["Toward Transformative Justice: A Liberatory Approach to Child Sexual Abuse and Other Forms of Intimate and Community Violence"](https://transformharm.org/tj_resource/toward-transformative-justice-a-liberatory-approach-to-child-sexual-abuse-and-other-forms-of-intimate-and-community-violence/) (2007) by generation FIVE

<h3>2018</h3>
* [How Nonviolent Struggle Works](https://static1.squarespace.com/static/62b0eb7da51f3717911bb4e1/t/642f35733af6ca7e837ffe53/1680815475818/HNVSW-updated-Jan-2015.pdf) by Gene Sharp
* ["The Lesser Evil? The Left, the Democrats and 1984"](https://www.versobooks.com/blogs/news/4109-the-lesser-evil-the-left-the-democrats-and-1984) by Mike Davis
