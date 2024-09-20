# Christian Alleyne's Blog

## About Me

My name is Christian Alleyne I am 17 and im a part of the Brooklyn steam center. This is going to be My developer blog for a project I'm working on.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
