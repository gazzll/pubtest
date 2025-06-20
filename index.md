---
layout: default
---
# The Pub Test
Honest chats about Australian life, for everyone

{% for post in site.posts %}
<div class="post">
    <h2>{{ post.title }}</h2>
    <div class="post-meta">Posted on {{ post.date | date: "%B %d, %Y" }} by The Pub Test Team</div>
    <p>{{ post.excerpt }}</p>
    <p><a href="{{ post.url }}" class="read-more">Dive in and read more...</a></p>
</div>
{% endfor %}
