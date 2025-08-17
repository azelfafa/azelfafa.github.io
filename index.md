---
title: /beranda
layout: home
permalink: /
---

# Azelfafage ♪(´▽｀)
Seorang manusia biasa yang gemar berselancar ria di internet. Suka Jejepangan (anime, manga, dll.) dan sesuatu yang berbau teknologi. Sukarelawan di Wikipedia dan berbagai proyek Wikimedia lainnya. Hobi menulis dan menggambar.

# Log
<ul>
    {%- for post in site.posts -%}
    <li>
      {%- assign date_format = "%d-%m-%Y" -%}
      [ {{ post.date | date: date_format }} ] <a href="{{ post.url | relative_url }}">{{ post.title | escape }}</a>
    </li>
    {%- endfor -%}
  </ul>