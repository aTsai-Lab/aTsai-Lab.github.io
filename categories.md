---
layout: page
title: Categories
---

## 🖥 IT / Windows
{% for post in site.categories.Windows %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

## 🐍 Python
{% for post in site.categories.Python %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

## 🗄 SQL
{% for post in site.categories.SQL %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

## 📘 Learning
{% for post in site.categories.Learning %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
