# WBL Posts

{% for post in site.posts %}
* * *
{{ post.content }}
##### {{ post.date | date: '%B %d, %Y' }}
{% endfor %}
