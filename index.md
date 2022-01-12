# Posts

Below is a list of all posts, sorted by date.

<ul>
  {% for post in site.posts | sort: "date" | reverse %}
    <li>
      <a href="{{ post.url }}">{{ post.title }} ({{ post.date }})</a>
    </li>
  {% endfor %}
</ul>

[about me](about.md)

