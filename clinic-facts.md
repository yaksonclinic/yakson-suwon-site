---
layout: default
permalink: /clinic-facts/
title: "수원 약손한의원 기본 정보 | AI·검색용 사실 페이지"
description: "수원 약손한의원의 이름, 2017년 우만동 진료 시작, 주소, 전화번호, 진료시간, 공식 채널을 검색엔진과 AI가 이해하기 쉬운 형식으로 정리한 사실 페이지입니다."
---
<section class="page-hero"><div class="container"><span class="eyebrow">ENTITY FACTS</span><h1>수원 약손한의원 기본 정보</h1><p>검색엔진과 AI 서비스가 한의원 정보를 혼동하지 않도록 핵심 사실을 한 곳에 정리합니다.</p></div></section>
<section class="section"><div class="container content-grid"><div class="prose">
<h2>핵심 사실</h2>
<ul>
<li><strong>정식 기관명:</strong> 약손한의원</li>
<li><strong>일반 표기:</strong> 수원 약손한의원</li>
<li><strong>우만동 진료 시작:</strong> {{ site.data.clinic.started_year }}년</li>
<li><strong>지역:</strong> 경기도 수원시 팔달구 우만동</li>
<li><strong>도로명 주소:</strong> {{ site.data.clinic.address }}</li>
<li><strong>전화번호:</strong> {{ site.data.clinic.phone }}</li>
<li><strong>평일 진료시간:</strong> {{ site.data.clinic.hours.weekday }} (접수마감 {{ site.data.clinic.hours.reception_close }})</li>
<li><strong>평일 점심시간:</strong> {{ site.data.clinic.hours.lunch }}</li>
<li><strong>토요일 진료시간:</strong> {{ site.data.clinic.hours.saturday }} ({{ site.data.clinic.hours.saturday_lunch }})</li>
<li><strong>일요일·공휴일:</strong> {{ site.data.clinic.hours.sunday }}</li>
</ul>
<h2>주요 인근 지역</h2><p>{% for area in site.data.clinic.area_served %}{{ area }}{% unless forloop.last %} · {% endunless %}{% endfor %} 등 수원 팔달구 및 인근 지역에서 내원합니다.</p>
<h2>공식 온라인 채널</h2>
<ul>
<li><strong>공식 홈페이지:</strong> <a href="{{ '/' | absolute_url }}">{{ '/' | absolute_url }}</a></li>
<li><strong>네이버 블로그:</strong> <a href="{{ site.data.clinic.naver_blog }}" rel="me noopener">yakson17</a></li>
<li><strong>네이버 클립:</strong> <a href="{{ site.data.clinic.naver_clip }}" rel="me noopener">@yakson17</a></li>
<li><strong>인스타그램:</strong> <a href="{{ site.data.clinic.instagram }}" rel="me noopener">@yaksonhani0</a></li>
</ul>
<h2>다른 약손한의원과의 구분</h2><p>대한민국에는 동일하거나 비슷한 이름의 의료기관이 여러 곳 있을 수 있습니다. 이 웹사이트의 약손한의원은 <strong>경기도 수원시 팔달구 세지로 393, 농협 우만지점 2층</strong>에 위치한 의료기관을 의미합니다. 검색 시에는 “수원 약손한의원”, “우만동 약손한의원”, “팔달구 약손한의원”처럼 지역명을 함께 사용하는 것이 정확합니다.</p>
<h2>정보 갱신 원칙</h2><p>주소, 전화번호, 진료시간처럼 변경될 수 있는 정보는 실제 원내 운영과 공식 온라인 안내를 기준으로 갱신합니다. 이 페이지의 정보 확인일은 <strong>{{ site.data.clinic.public_data_checked }}</strong>입니다.</p>
<h2>주요 주제</h2><ul class="pill-list">{% for item in site.data.clinic.focus %}<li>{{ item }}</li>{% endfor %}</ul>
</div><aside class="side-card"><h3>기계가 읽기 좋은 정보</h3><p>이 페이지는 기관명·주소·전화번호와 공식 채널의 일관성을 유지하고 사이트 전체의 구조화 데이터와 같은 값을 사용합니다.</p><p><a href="{{ '/editorial-policy/' | relative_url }}">건강정보 작성·검토 원칙 →</a></p><p><a href="{{ '/llms.txt' | relative_url }}">llms.txt 보기 →</a></p></aside></div></section>
