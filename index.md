<ul>
  {% for post in site.posts %}
    <li>
      <h1 href="{{ post.url }}">{{ post.title }}</h1>
      <small>{{ post.date | date: "%-d %B %Y" }}</small>
    </li>
  {% endfor %}
</ul>
