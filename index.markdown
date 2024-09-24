---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<h1> Lessons </h1>

{% for lessoncontent in site.lessoncontent %}
  <h2>
    <a href="{{ site.url }}{{ lessoncontent.url }}">
      {{ lessoncontent.title }} 
    </a>
  </h2>
{% endfor %}

