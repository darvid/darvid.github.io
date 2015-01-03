When I'm not writing software, I'm learning how to write software better. That,
or playing video games. Primary interests include *Python*, *web applications
and frameworks*, *Linux*, and *information security*.

- - -
<div class="posts">
  <h2>Posts</h2>
  <ul>
    {% for post in site.posts %}
      <li><a href="{{ post.url }}">{{ post.date | date: "%B %-d, %Y" }} {{ post.title }}</a></li>
    {% endfor %}
  </ul>
</div>
- - -
