---
layout: default
---
# The Pub Test
Honest chats about Australian life, for everyone

{% assign latest_post = site.posts | first %}
<div class="post">
    <h2>{{ latest_post.title }}</h2>
    <div class="post-meta">Posted on {{ latest_post.date | date: "%B %d, %Y" }} by The Pub Test Team</div>
    <p>{{ latest_post.excerpt }}</p>
    <p><a href="{{ latest_post.url }}" class="read-more">Dive in and read more...</a></p>
</div>
<p>Explore our <a href="{{ site.baseurl }}/archive">archive</a> or <a href="{{ site.baseurl }}/special-reports">special reports</a>.</p>
