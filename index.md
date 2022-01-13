# Posts

[About me](about.md)

## Posts By Date
<ul>
  {% for post in site.posts | sort: "date" | reverse %}
    <li>
      <a href="{{ post.url }}">{{ post.title }} ({{ post.date | date_to_string: "ordinal", "US"}})</a>
    </li>
  {% endfor %}
</ul>
