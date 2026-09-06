---
layout: default
---

Команда «Проект-А» приветствует вас! Мы работаем на гребне высоких технологий.

## 📝 Записи на полях

{% for post in site.posts limit: 10 %}
* [{{ post.title }}]( {{ post.url | relative_url }}) — <small>{{ post.date | date: "%d.%m.%Y" }}</small>
{% endfor %}
