---
layout: home
title: /arsip
permalink: /arsip/
---

# Log web
<ul>
    {%- for post in site.posts -%}
    <li>
      {%- assign date_format = "%d-%m-%Y" -%}
      [ {{ post.date | date: date_format }} ] <a href="{{ post.url | relative_url }}">{{ post.title | escape }}</a>
    </li>
    {%- endfor -%}
  </ul>
