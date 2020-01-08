# WBL Posts

{% for post in site.posts %}
* * *
## {{ post.title }}
{{ post.content }}
##### {{ post.date | date: '%B %d, %Y' }}
{% endfor %}
