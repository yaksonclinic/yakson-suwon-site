---
layout: default
permalink: /articles/
title: "건강정보 | 수원 약손한의원"
description: "통증, 소화기 증상, 수면, 자율신경, 두통·어지럼, 여성 건강, 체질 관련 건강정보를 주제별로 정리합니다."
---
<section class="page-hero"><div class="container"><span class="eyebrow">HEALTH LIBRARY</span><h1>약손 건강정보</h1><p>검색할 때 궁금했던 질문을 한 페이지에 한 주제씩 정리합니다. 새로운 글이 추가될수록 사이트의 정보 구조가 자연스럽게 확장됩니다.</p></div></section>
<section class="section"><div class="container"><div class="post-grid">
{% for post in site.posts %}<a class="post-card" href="{{ post.url | relative_url }}"><span class="tag">{{ post.category }}</span><h3>{{ post.title }}</h3><p>{{ post.description }}</p><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: '%Y.%m.%d' }}</time></a>{% endfor %}
</div></div></section>
