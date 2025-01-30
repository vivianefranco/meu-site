<div class="blog-container">
    <h1>📖 Blog</h1>
    <p class="blog-description">
        Aqui você encontra artigos sobre <strong>Inteligência Artificial na Educação, Revisão de Texto e Inovação</strong>.
    </p>

    <div class="blog-posts">
        {% for post in site.posts %}
        <div class="post">
            {% if post.image %}
                <img src="{{ post.image }}" alt="{{ post.title }}" class="post-thumbnail">
            {% endif %}
            <div class="post-content">
                <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
                <p class="post-meta">📅 {{ post.date | date: "%d/%m/%Y" }}</p>
                <p class="post-excerpt">{{ post.excerpt }}</p>
            </div>
        </div>
        {% endfor %}
    </div>
</div>

