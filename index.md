layout: default
私の日記
これまでの日記一覧です。
{% for post in site.posts %}
 [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) - {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}
