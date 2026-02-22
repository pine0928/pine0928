---
layout: home
title: ホーム
---

# 数学独学ノート

<p style="font-size: 1.1em;">
工学部生による数学の学習記録と理論ノートです。
</p>

<br>

## 📚 分野別

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 15px; max-width: 500px; margin: 0 auto;">

<a href="{{ site.baseurl }}/categories/analysis/">解析学</a>

<a href="{{ site.baseurl }}/categories/linear-algebra/">線形代数</a>

<a href="{{ site.baseurl }}/categories/discrete-math/">離散数学</a>

<a href="{{ site.baseurl }}/categories/algorithm/">アルゴリズム理論</a>

</div>

<br><br>

## 📝 最新記事

<ul style="max-width: 600px; margin: 0 auto; text-align: left;">
{% for post in site.posts limit:5 %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    <span style="color: gray; font-size: 0.9em;">
      ({{ post.date | date: "%Y.%m.%d" }})
    </span>
  </li>
{% endfor %}
</ul>
