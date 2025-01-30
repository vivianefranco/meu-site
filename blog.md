<div class="container">

# 📖 Blog  

Aqui você encontra artigos sobre **Inteligência Artificial na Educação, Revisão de Texto e Inovação**.  

{% for post in site.posts %}
<div class="post">
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p><small>📅 {{ post.date | date: "%d/%m/%Y" }}</small></p>
    <p>{{ post.excerpt }}</p>
</div>
<hr>
{% endfor %}

</div>
