---
layout: default
title: "수원 약손한의원 | 우만동 한의원 진료·건강정보"
description: "수원 팔달구 우만동 약손한의원의 진료시간, 위치, 진료 안내와 통증·소화·수면·체질 등 한의학 건강정보를 확인하세요."
---

<style>
  .clinic-cards{
    grid-template-columns:repeat(3,minmax(0,1fr));
  }
  .clinic-cards .card{
    position:relative;
    min-height:250px;
    display:flex;
    flex-direction:column;
  }
  .clinic-cards .card-link{
    margin-top:auto;
  }
  .clinic-cards .featured-clinic{
    grid-column:span 2;
  }
  @media (max-width:900px){
    .clinic-cards{
      grid-template-columns:repeat(2,minmax(0,1fr));
    }
    .clinic-cards .featured-clinic{
      grid-column:span 1;
    }
  }
  @media (max-width:640px){
    .clinic-cards{
      grid-template-columns:1fr;
    }
  }
</style>

<section class="hero">
  <div class="container hero-inner">
    <div>
      <span class="eyebrow">SUWON · UMAN-DONG</span>
      <h1>몸의 불편을<br><em>차분히 살피는</em><br>수원 약손한의원</h1>
      <p class="lead">수원 우만동에서 진료를 이어오고 있습니다. 진료 정보는 명확하게, 실제 진료실에서 자주 설명하는 건강정보는 한 주제씩 차곡차곡 기록합니다.</p>
      <div class="hero-actions">
        <a class="button" href="{{ site.data.clinic.phone_uri }}">031-247-7522 전화 문의</a>
        <a class="button secondary" href="{{ '/treatment/' | relative_url }}">진료 안내 보기</a>
      </div>
    </div>
    <div class="hero-card" aria-label="약손한의원 핵심 안내">
      <span class="seal">藥手</span>
      <p>수원 팔달구 우만동</p>
      <strong>통증부터 일상의 불편까지<br>증상과 상태를 살펴 진료합니다.</strong>
      <p>침 · 약침 · 부항 · 한약 등 한의학적 진료</p>
    </div>
  </div>
</section>

<div class="quick-strip">
  <div class="container quick-grid">
    <a href="{{ site.data.clinic.phone_uri }}"><small>전화 문의</small><strong>{{ site.data.clinic.phone }}</strong></a>
    <a href="{{ '/location/' | relative_url }}"><small>주소</small><strong>수원 팔달구 세지로 393</strong></a>
    <a href="{{ '/clinic/' | relative_url }}"><small>평일 진료</small><strong>{{ site.data.clinic.hours.weekday }}</strong></a>
    <a href="{{ '/articles/' | relative_url }}"><small>건강정보</small><strong>증상별 글 모아보기</strong></a>
  </div>
</div>

<section class="section clinic-guide">
  <div class="container">
    <div class="section-head">
      <div>
        <span class="eyebrow">CLINIC</span>
        <h2>약손한의원<br>주요 진료분야</h2>
      </div>
      <p>현재의 증상과 생활 상태를 함께 살펴보고, 필요한 한의학적 진료 방향을 안내합니다.</p>
    </div>

    <div class="cards clinic-cards">
      <article class="card">
        <span class="num">01</span>
        <h3>통증 클리닉</h3>
        <p>목·어깨·허리·무릎 등 일상에서 반복되는 근골격계 통증과 불편을 상담합니다.</p>
        <a class="card-link" href="{{ '/clinic/pain/' | relative_url }}">자세히 보기 →</a>
      </article>

      <article class="card">
        <span class="num">02</span>
        <h3>교통사고 클리닉</h3>
        <p>사고 이후 나타나는 목·허리 통증, 뻐근함과 여러 불편을 살펴봅니다.</p>
        <a class="card-link" href="{{ '/clinic/traffic-accident/' | relative_url }}">자세히 보기 →</a>
      </article>

      <article class="card">
        <span class="num">03</span>
        <h3>여성 클리닉</h3>
        <p>생리 주기와 컨디션 변화, 갱년기 등 여성 건강과 관련된 불편을 상담합니다.</p>
        <a class="card-link" href="{{ '/clinic/women/' | relative_url }}">자세히 보기 →</a>
      </article>

      <article class="card">
        <span class="num">04</span>
        <h3>산후 클리닉</h3>
        <p>출산 후 회복 과정에서 나타나는 피로감과 컨디션 변화를 함께 살펴봅니다.</p>
       <a class="card-link" href="{{ '/clinic/postpartum/' | relative_url }}">자세히 보기 →</a>
      </article>

      <article class="card">
        <span class="num">05</span>
        <h3>소화기 클리닉</h3>
        <p>더부룩함, 명치 답답함, 복부 불편 등 반복되는 소화기 증상을 살펴봅니다.</p>
       <a class="card-link" href="{{ '/clinic/digestive/' | relative_url }}">자세히 보기 →</a>
      </article>

      <article class="card">
        <span class="num">06</span>
        <h3>비염·호흡기 클리닉</h3>
        <p>만성기침, 감기 후 잔기침, 후비루·비염처럼 오래 반복되는 호흡기 불편을 살펴봅니다.</p>
        <a class="card-link" href="{{ '/clinic/rhinitis-respiratory/' | relative_url }}">자세히 보기 →</a>
      </article>

      <article class="card">
        <span class="num">07</span>
         <h3>소아·성장 클리닉</h3>
  <p>급성장기를 앞둔 초등 고학년, 운동하는 아이의 성장·체력과 여자아이의 빠른 사춘기 변화를 함께 살펴봅니다.</p>
  <a class="card-link" href="{{ '/clinic/children/' | relative_url }}">자세히 보기 →</a>
      </article>

      <article class="card">
  <span class="num">08</span>
  <h3>보약·체력회복 클리닉</h3>
  <p>쉽게 지치는 피로감과 회복 저하, 손발이나 신체 일부의 시림·열감 등을 생활상태와 함께 살펴봅니다.</p>
  <a class="card-link" href="{{ '/clinic/tonic/' | relative_url }}">자세히 보기 →</a>
</article>

      <article class="card">
  <span class="num">09</span>
  <h3>수면·스트레스 관리 클리닉</h3>
  <p>불면, 두근거림, 가슴 답답함, 긴장과 스트레스로 반복되는 불편을 수면과 생활상태와 함께 살펴봅니다.</p>
  <a class="card-link" href="{{ '/clinic/sleep-stress/' | relative_url }}">자세히 보기 →</a>
</article>

      <article class="card">
  <span class="num">10</span>
  <h3>공진단·경옥고 클리닉</h3>
  <p>과로와 체력 소모가 큰 시기, 회복이 더딘 피로와 중요한 일정 전 컨디션 관리 등을 복용 목적과 건강상태에 맞춰 상담합니다.</p>
  <a class="card-link" href="{{ '/clinic/gongjindan-gyeongokgo/' | relative_url }}">자세히 보기 →</a>
</article>

      <article class="card">
        <span class="num">11</span>
        <h3>다이어트 클리닉</h3>
        <p>체질과 생활습관, 식사 패턴을 함께 살펴 개인별 한방 체중관리 방향을 상담합니다.</p>
        <a class="card-link" href="{{ '/treatment/' | relative_url }}">자세히 보기 →</a>
      </article>

<article class="card">
  <span class="num">12</span>
  <h3>피부 클리닉</h3>
  <p>두드러기,가려움, 여드름, 반복되는 피부 트러블, 건조함과 피부 컨디션 변화를 생활습관과 수면,소화,스트레스 상태와 함께 살펴봅니다.</p>
  <a class="card-link" href="{{ '/clinic/skin/' | relative_url }}">자세히 보기 →</a>
</article>
      
    </div>
  </div>
</section>

<section class="section soft">
  <div class="container facts-band">
    <div class="fact-panel">
      <span class="eyebrow" style="color:#d6e3dd">CLINIC INFO</span>
      <h3>진료시간</h3>
      <div class="fact-list">
        <div class="fact-row"><span>월–금</span><strong>{{ site.data.clinic.hours.weekday }}<br>접수마감 {{ site.data.clinic.hours.reception_close }}</strong></div>
        <div class="fact-row"><span>점심시간</span><strong>{{ site.data.clinic.hours.lunch }}</strong></div>
        <div class="fact-row"><span>토요일</span><strong>{{ site.data.clinic.hours.saturday }}<br>{{ site.data.clinic.hours.saturday_lunch }}</strong></div>
        <div class="fact-row"><span>일요일·공휴일</span><strong>휴진</strong></div>
      </div>
    </div>
    <div class="fact-panel light">
      <span class="eyebrow">LOCATION</span>
      <h3>수원 팔달구 우만동</h3>
      <div class="fact-list">
        <div class="fact-row"><span>주소</span><strong>세지로 393<br>농협 우만지점 2층</strong></div>
        <div class="fact-row"><span>전화</span><strong>{{ site.data.clinic.phone }}</strong></div>
        <div class="fact-row"><span>오시는 길</span><strong><a href="{{ '/location/' | relative_url }}">상세 안내 →</a></strong></div>
      </div>
    </div>
  </div>
</section>

<section class="section">
  <div class="container">
    <div class="section-head">
  <div>
    <span class="eyebrow">HEALTH COLUMN</span>
    <h2>약손한의원<br>건강칼럼</h2>
  </div>
  <p>진료실에서 자주 설명드리는 건강 주제를 이해하기 쉽게 한 편씩 정리합니다.</p>
</div>
    <div class="post-grid">
      {% for post in site.posts limit:6 %}
      <a class="post-card" href="{{ post.url | relative_url }}">
        <span class="tag">{{ post.category }}</span>
        <h3>{{ post.title }}</h3>
        <p>{{ post.description }}</p>
        <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: '%Y.%m.%d' }}</time>
      </a>
      {% endfor %}
    </div>
  </div>
</section>

<section class="section soft">
  <div class="container">
    <div class="section-head">
      <div><span class="eyebrow">OFFICIAL CHANNELS</span><h2>약손한의원 공식 채널</h2></div>
      <p>홈페이지의 공식 정보와 함께 네이버 블로그·클립·인스타그램에서도 건강정보와 소식을 확인할 수 있습니다.</p>
    </div>
    <div class="channel-grid">
      <a class="channel-card" href="{{ site.data.clinic.naver_blog }}" rel="me noopener"><small>NAVER BLOG</small><strong>약손한의원 네이버 블로그</strong><span>자세한 건강정보와 기존 콘텐츠 보기 →</span></a>
      <a class="channel-card" href="{{ site.data.clinic.naver_clip }}" rel="me noopener"><small>NAVER CLIP</small><strong>약손한의원 네이버 클립</strong><span>짧은 영상으로 건강정보 보기 →</span></a>
      <a class="channel-card" href="{{ site.data.clinic.instagram }}" rel="me noopener"><small>INSTAGRAM</small><strong>@yaksonhani0</strong><span>인스타그램 콘텐츠 보기 →</span></a>
    </div>
  </div>
</section>

<section class="section" style="padding-top:0">
  <div class="container cta-band">
    <div><h2>내원 전 진료시간을<br>전화로 확인해 주세요.</h2><p>일요일·공휴일은 휴진이며, 임시 휴진이나 일정 변경은 전화로 확인해 주세요.</p></div>
    <a class="button" href="{{ site.data.clinic.phone_uri }}">{{ site.data.clinic.phone }}</a>
  </div>
</section>
