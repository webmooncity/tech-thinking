---
layout: default
title: 개발에 대한 사유
---

# Tech Thinking

테크와 개발에 대한 사유

[About Me]({{ site.baseurl }}/about/)

---

## Posts

<ul>
    {% for post in site.posts %}
        <li>
            <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
            <small>{{ post.date | date: "%Y-%m-%d" }}</small>
        </li>
    {% endfor %}
</ul>

<p>posts count: {{ site.posts | size }}</p>g