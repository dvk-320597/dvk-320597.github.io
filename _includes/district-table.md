| ПІБ | Дата та місце народження | Висування | Відомості |
|--- |--- |--- |--- |--- | {% for candidate in page.candidates %}
| {{ candidate.name }} | {{ candidate.birth }} | {{ candidate.party }}, зареєстрований {{ candidate.date }} | {{ candidate.about }} | {% endfor %}   
