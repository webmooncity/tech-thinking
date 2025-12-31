---
layout: withnav
title: 개발에 대한 사유
---

기술,
개발,
미래에 대해
생각하고 기록합니다. 

[About Me]({{ "/about/" | relative_url }})

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

<p>posts count: {{ site.posts | size }}</p>