# WBL Posts

{% for post in site.posts %}
* * *
{{ post.date | date: '%B %d, %Y' }}{{ post.content }}
{% endfor %}
