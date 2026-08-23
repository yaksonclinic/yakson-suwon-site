---
layout: default
permalink: /faq/
title: "자주 묻는 질문 | 수원 약손한의원"
description: "수원 약손한의원 진료시간, 위치, 초진 준비, 약침·침 치료 등에 관한 자주 묻는 질문입니다."
---
<section class="page-hero"><div class="container"><span class="eyebrow">FAQ</span><h1>자주 묻는 질문</h1><p>방문 전 많이 궁금해하시는 내용을 간단히 정리했습니다.</p></div></section>
<section class="section"><div class="container" style="max-width:880px"><div class="faq-list">
{% for item in site.data.faq %}
<div class="faq-item"><h2>Q. {{ item.question }}</h2><p>{{ item.answer }}</p></div>
{% endfor %}
</div></div></section>
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {% for item in site.data.faq %}
    {
      "@type": "Question",
      "name": {{ item.question | jsonify }},
      "acceptedAnswer": {
        "@type": "Answer",
        "text": {{ item.answer | jsonify }}
      }
    }{% unless forloop.last %},{% endunless %}
    {% endfor %}
  ]
}
</script>
