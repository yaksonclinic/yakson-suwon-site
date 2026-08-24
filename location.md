---
layout: default
permalink: /location/
title: "오시는 길 | 수원 약손한의원"
description: "경기 수원시 팔달구 세지로 393, 농협 우만지점 2층 약손한의원의 위치, 전화번호, 진료시간을 안내합니다."
---
<section class="page-hero"><div class="container"><span class="eyebrow">LOCATION</span><h1>오시는 길</h1><p>{{ site.data.clinic.address }}</p></div></section>
<section class="section"><div class="container facts-band">
<div class="fact-panel light"><h3>주소·전화</h3><div class="fact-list"><div class="fact-row"><span>주소</span><strong>{{ site.data.clinic.address }}</strong></div><div class="fact-row"><span>전화</span><strong><a href="{{ site.data.clinic.phone_uri }}">{{ site.data.clinic.phone }}</a></strong></div><div class="fact-row"><span>지도</span><strong><a href="{{ site.data.clinic.naver_map }}" target="_blank" rel="noopener">네이버 지도에서 위치보기 →</a></strong></div></div></div>
<div class="fact-panel"><h3>진료시간</h3><div class="fact-list"><div class="fact-row"><span>평일</span><strong>{{ site.data.clinic.hours.weekday }}<br>접수마감 {{ site.data.clinic.hours.reception_close }}</strong></div><div class="fact-row"><span>점심</span><strong>{{ site.data.clinic.hours.lunch }}</strong></div><div class="fact-row"><span>토요일</span><strong>{{ site.data.clinic.hours.saturday }}<br>{{ site.data.clinic.hours.saturday_lunch }}</strong></div><div class="fact-row"><span>일요일·공휴일</span><strong>{{ site.data.clinic.hours.sunday }}</strong></div></div></div>
</div><div class="container" style="margin-top:28px"><p class="notice">일요일 및 공휴일은 휴진입니다. 임시 휴진이나 연휴 전후 일정은 변경될 수 있으니 실제 방문 전 전화로 확인해 주세요.</p></div></section>
