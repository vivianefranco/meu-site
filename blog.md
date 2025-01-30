# 📖 Blog  

Aqui você encontra artigos sobre **Inteligência Articial e o futuro da Educação**.  

{% for post in site.posts %}
- 📅 **{{ post.date | date: "%d/%m/%Y" }}** - [{{ post.title }}]({{ post.url }})
{% endfor %}
