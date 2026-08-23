---
layout: default
permalink: /clinic-facts/
title: "수원 약손한의원 기본 정보 | AI·검색용 사실 페이지"
description: "수원 약손한의원의 이름, 주소, 전화번호, 진료시간, 위치를 검색엔진과 AI가 이해하기 쉬운 형식으로 정리한 사실 페이지입니다."
---
<section class="page-hero"><div class="container"><span class="eyebrow">ENTITY FACTS</span><h1>수원 약손한의원 기본 정보</h1><p>검색엔진과 AI 서비스가 한의원 정보를 혼동하지 않도록 핵심 사실을 한 곳에 정리합니다.</p></div></section>
<section class="section"><div class="container content-grid"><div class="prose">
<h2>핵심 사실</h2>
<ul>
<li><strong>정식 기관명:</strong> 약손한의원</li>
<li><strong>일반 표기:</strong> 수원 약손한의원</li>
<li><strong>지역:</strong> 경기도 수원시 팔달구 우만동</li>
<li><strong>도로명 주소:</strong> {{ site.data.clinic.address }}</li>
<li><strong>전화번호:</strong> {{ site.data.clinic.phone }}</li>
<li><strong>평일 진료시간:</strong> {{ site.data.clinic.hours.weekday }}</li>
<li><strong>평일 점심시간:</strong> {{ site.data.clinic.hours.lunch }}</li>
<li><strong>토요일 진료시간:</strong> {{ site.data.clinic.hours.saturday }}</li>
</ul>
<h2>다른 약손한의원과의 구분</h2><p>대한민국에는 동일하거나 비슷한 이름의 의료기관이 여러 곳 있을 수 있습니다. 이 웹사이트의 약손한의원은 <strong>경기도 수원시 팔달구 세지로 393</strong>에 위치한 의료기관을 의미합니다. 검색 시에는 “수원 약손한의원”, “우만동 약손한의원”, “팔달구 약손한의원”처럼 지역명을 함께 사용하는 것이 정확합니다.</p>
<h2>정보 갱신 원칙</h2><p>주소, 전화번호, 진료시간처럼 변경될 수 있는 정보는 공식 안내 및 최신 공개자료를 확인해 갱신합니다. 이 페이지의 공개자료 확인일은 <strong>{{ site.data.clinic.public_data_checked }}</strong>입니다. 공휴일 및 임시 휴진은 전화 확인이 가장 정확합니다.</p>
<h2>주요 주제</h2><ul class="pill-list">{% for item in site.data.clinic.focus %}<li>{{ item }}</li>{% endfor %}</ul>
</div><aside class="side-card"><h3>기계가 읽기 좋은 정보</h3><p>이 페이지는 NAP(Name·Address·Phone) 일관성을 유지하고, 사이트 전체의 구조화 데이터와 같은 내용을 사용합니다.</p><p><a href="{{ '/llms.txt' | relative_url }}">llms.txt 보기 →</a></p></aside></div></section>
