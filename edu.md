---
layout: home
---
<ul id="post-list">
    {% for edu in paginator.edu %}
        {% include item.html %}
    {% endfor %}
</ul>
{% include pagination.html %}


