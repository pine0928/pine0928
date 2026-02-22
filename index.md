---
layout: home
title: ホーム
---

# 数学独学ノート

このサイトは、工学部生の筆者の勉強記録です。

---

## 📚 分野別

-[解析学]({{ site.baseurl }}/categories/analysis/)
-[線形代数]({{ site.baseurl }}/categories/linear-algebra/)
-[離散数学]({{ site.baseurl }}/categories/discrete-math/)
-[アルゴリズム理論]({{ site.baseurl }}/categories/algorithm/)
---

## 📝 最新記事

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
