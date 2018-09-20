---
layout: home
---
<ul id="post-list">
    {% for post in paginator.post %}
        {% include item.html %}
    {% endfor %}
</ul>
{% include pagination.html %}


