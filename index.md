<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <h1>{{ page.title }}</h1>
      <small>{{ page.date | date: "%-d %B %Y" }}</small>
    </li>
  {% endfor %}
</ul>
