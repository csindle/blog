---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<div class="row">

  <div class="column">
    {% for article in site.a %}
    <p>
      <a class="post-link" href="{{ article.url | prepend: site.baseurl }}">
      {{ article.title }}
      </a>
    </p>
    {% endfor %}
  </div>
  
</div> 

