---
layout: default
title: 개발에 대한 사유
---

# Tech Thinking

테크와 개발에 대한 사유

[About]({{ site.baseurl }}/about/)

---

## Posts

<ul>
    {% for post in site.posts %}
        <li>
            <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
            <small>{{ post.date | date: "%Y-%m-%d" }}</small>
        </li>
    {% endfor %}
</ul>