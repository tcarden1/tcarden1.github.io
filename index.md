---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

{% for page in site.pages %}
  <h2><a class="post-link" href="{{ page.url | prepend: site.baseurl }}">{{ page.title }}</a></h2>
{% endfor %}
