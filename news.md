---
layout: post
title: News
---

{% for post in site.posts %}
# <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>

{{ post.excerpt }}

<section class="special">
<ul class="actions">
<li><a href="{{ site.baseurl }}{{ post.url }}" class="button {% cycle '', 'alt'%}">Read More</a></li>
</ul>
</section>
{% endfor %}
