---
layout: default
permalink: /articles/
title: "건강칼럼 | 수원 약손한의원"
description: "통증, 소화기 증상, 수면, 자율신경, 두통·어지럼, 여성 건강, 체질 관련 건강정보를 주제별로 정리합니다."
---
<section class="page-hero"><div class="container"><span class="eyebrow">HEALTH LIBRARY</span><h1>약손 건강칼럼</h1><p>진료실에서 자주 설명드리는 건강 주제를 한 편씩 이해하기 쉽게 정리합니다. 새로운 칼럼이 추가될수록 약손한의원의 건강정보가 차곡차곡 쌓입니다..</p></div></section>
<section class="section"><div class="container"><div class="post-grid">
{% for post in site.posts %}<a class="post-card" href="{{ post.url | relative_url }}"><span class="tag">{{ post.category }}</span><h3>{{ post.title }}</h3><p>{{ post.description }}</p><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: '%Y.%m.%d' }}</time></a>{% endfor %}
</div></div></section>
