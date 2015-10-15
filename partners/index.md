---
layout: page
title: Partners
permalink: /partners/
---


<div class="row">
{% for p in site.data.partners %}
  <div class="col-xs-4 col-md-2">
    <a href="{{ p.url }}" class="thumbnail">
      <img src="{{ "/img/partners/" | append: p.img | prepend: site.baseurl }}" alt="">
    </a>
  </div>
{% endfor %}
</div>

- - -

# Contacts

Coming soon...
