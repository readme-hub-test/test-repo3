# Organization READMEs

{% for repo in site.pages %}
  {% if repo.layout == "readme" %}
  - [{{ repo.title }}]({{ repo.url }})
  {% endif %}
{% endfor %}
