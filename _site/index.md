# Home


{% for post in site.posts %}
  <div class="post">
    <h2>{{ post.title }}</h2>
    <p>{{ post.date | date_to_string }}</p>
    <div class="post-content">
      {{ post.content }}
    </div>
  </div>
{% endfor %}



{% for post in site.posts %}
## {{ post.Word2Vec }}

<div class="post-content">
    {{ post.content }}
</div>
{% endfor %}

## Home
- [Home](/Test2/index.html)

### Posts
- [Aliquam](/2023site/2016/08/25/aliquam.html)
- [Tempus](/2023site/2016/08/24/tempus.html)
- [Magna](/2023site/2016/08/23/magna.html)
- [Ipsum](/2023site/2016/08/22/ipsum.html)
- [Consequat](/2023site/2016/08/21/consequat.html)

