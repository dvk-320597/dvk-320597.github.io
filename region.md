---
layout: default
permalink: /region/
title: Кандидати в Київську обласну раду
description: Територіальний виборчий округ №9 з виборів депутатів Київської обласної ради
---

{% include navigation.md %}

{% for party in site.data.kyiv_region %}

## {{ party.description }}

| № | Закріплений кандидат | Відомості щодо закріпленого кандидата |
|--- |--- |--- | {% for candidate in party.candidates %}
| {{ candidate.num }} | {{ candidate.name }} | {{ candidate.about }} | {% endfor %}   

{% endfor %}


[За інформацією з офіційного сайту ЦВК](https://www.cvk.gov.ua/pls/vm2020/pvm066pt001f01=695pt00_t001f01=695pid102=884pf7691=884pt004f01=9rej=0.html)

