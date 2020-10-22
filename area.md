---
layout: default
permalink: /area/
title: Кандидати в районну раду
description: Територіальний виборчий округ №5 з виборів депутатів Фастівської районної ради
---

{% include navigation.md %}

{% for party in site.data.fastiv_area %}

## {{ party.description }}

| № | Закріплений кандидат | Відомості щодо закріпленого кандидата |
|--- |--- |--- | {% for candidate in party.candidates %}
| {{ candidate.num }} | {{ candidate.name }} | {{ candidate.about }} | {% endfor %}   

{% endfor %}


[За інформацією з офіційного сайту ЦВК](https://www.cvk.gov.ua/pls/vm2020/pvm066pt001f01=695pt00_t001f01=695pid102=63591pf7691=63591pt004f01=5rej=0.html)
