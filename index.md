---
layout: home
title: ホーム
---

# 数学独学ノート

<p class="subtitle">
工学部生による数学の学習記録と理論ノート
</p>

<br>

## 📚 分野別

<div class="card-grid">

  <a class="card" href="{{ site.baseurl }}/categories/analysis/">
    <h3>解析学</h3>
    <p>微分・積分・級数・極限</p>
  </a>

  <a class="card" href="{{ site.baseurl }}/categories/linear-algebra/">
    <h3>線形代数</h3>
    <p>行列・固有値・ベクトル空間</p>
  </a>

  <a class="card" href="{{ site.baseurl }}/categories/discrete-math/">
    <h3>離散数学</h3>
    <p>グラフ理論・組合せ</p>
  </a>

  <a class="card" href="{{ site.baseurl }}/categories/algorithm/">
    <h3>アルゴリズム理論</h3>
    <p>DP・最大フロー・計算量</p>
  </a>

</div>

<br><br>

## 📝 最新記事

<ul class="latest-posts">
{% for post in site.posts limit:5 %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    <span class="post-date">
      {{ post.date | date: "%Y.%m.%d" }}
    </span>
  </li>
{% endfor %}
</ul>
