{% include adsense.html %}
## 每日一题

学习算法是一种信仰，每天都需要坚持.

{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }}) {{repository.description}}
{% endfor %}
