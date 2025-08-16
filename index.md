---
title: /beranda
layout: home
permalink: /
---

<img src="/media/IMG_20250129_213324.jpg">

<b>Selamat datang!</b> Ini adalah situs blog yang ditulis dan dikelola oleh diri saya, Rinai Natsumi. Saya di sini biasa menulis artikel resensi (pendapat, ulasan) mengenai buku novel, <i>manga</i> atau serial <i>anime</i> yang saya tonton. Saya juga akan menulis hal-hal yang menurut saya penting.

Terima kasih bagi yang sudah berkenan membaca isi blog ini! Saya harap blog ini dapat bermanfaat bagi Anda. >_<

<a href="/tentang">Tentang Saya</a> • <a href="/lain">Serba-serbi</a> • <a href="/archive">Arsip</a>
<link href="https://github.com/rinanatsu" rel="me">

# Log
<ul>
    {%- for post in site.posts -%}
    <li>
      {%- assign date_format = "%d-%m-%Y" -%}
      [ {{ post.date | date: date_format }} ] <a href="{{ post.url | relative_url }}">{{ post.title | escape }}</a>
    </li>
    {%- endfor -%}
  </ul>