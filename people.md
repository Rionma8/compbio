---
layout: page
title: People
subtitle: More about us…
---

## Permanent staff

{% for post in site.peoples %}
    {% if post.position == "Permanent researcher" %}
        {% include archive-people.html %}
    {% endif %}
{% endfor %}

## Postdoctoral researcher

{% for post in site.peoples %}
    {% if post.position == "postdoc" %}
        {% include archive-people.html %}
    {% endif %}
{% endfor %}


## PhD students

{% for post in site.peoples %}
    {% if post.position == "phd_student" %}
        {% include archive-people.html %}
    {% endif %}
{% endfor %}


## Interns

**Benoit Sauret** (M2, intern, supervised by Nelle Varoquaux)


## Alumni


Duc-Anh Do (2022, intern)   
Flora Gaudillière (2021, intern)  
Renato Augusto Antoniassi Battistin (2021, intern)  
Vu-Lam Dang (2021, intern)  
William Schmitt (2021, PhD student)  
Qiqi He (2020, intern)  
Safa Berraies (2019, intern)  
Morgane Roger-Margueritat (2019&2022, intern)  
Clothilde Chenal (2018, intern)  
Brian Villette (2018, intern)  
Judith Boldt (2016, intern)  
Loic Duquennoy (2016, intern)  
Thibaut Lepage (2015-2017, postdoc)
