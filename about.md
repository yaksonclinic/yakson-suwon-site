<style>
  .about-hero{
    padding:84px 0 64px;
    background:linear-gradient(180deg,#f5f1e8 0%,#fff 100%);
  }
  .about-hero-grid{
    display:grid;
    grid-template-columns:.85fr 1.15fr;
    gap:54px;
    align-items:center;
  }
  .about-photo img{
    width:100%;
    border-radius:28px;
    display:block;
  }
  .about-hero h1{
    margin:0 0 20px;
    font-size:clamp(2.3rem,5vw,4.2rem);
    line-height:1.1;
  }
  .about-hero p{
    line-height:1.85;
    font-size:1.06rem;
  }
  .about-section{
    padding:72px 0;
  }
  .about-section.soft{
    background:#f7f6f1;
  }
  .about-heading{
    max-width:820px;
    margin-bottom:34px;
  }
  .about-heading h2{
    margin:8px 0 14px;
    font-size:clamp(1.8rem,3vw,2.8rem);
    line-height:1.25;
  }
  .about-heading p{
    line-height:1.8;
  }
  .philosophy-grid{
    display:grid;
    grid-template-columns:repeat(3,minmax(0,1fr));
    gap:18px;
  }
  .philosophy-card{
    padding:28px;
    background:#fff;
    border:1px solid rgba(0,0,0,.09);
    border-radius:18px;
  }
  .philosophy-card h3{
    margin:0 0 10px;
    font-size:1.18rem;
  }
  .philosophy-card p{
    margin:0;
    line-height:1.8;
  }
  .quote-box{
    padding:34px;
    background:#eee8dc;
    border-radius:20px;
  }
  .quote-box h3{
    margin:0 0 14px;
    font-size:1.5rem;
  }
  .quote-box p{
    margin:0;
    line-height:1.85;
  }
  .career-list{
    display:grid;
    gap:12px;
  }
  .career-item{
    padding:20px 0;
    border-top:1px solid rgba(0,0,0,.12);
  }
  .career-item strong{
    display:block;
    margin-bottom:6px;
  }
  .career-item p{
    margin:0;
    line-height:1.75;
  }
  .about-cta{
    display:flex;
    justify-content:space-between;
    gap:28px;
    align-items:center;
    padding:34px;
    border-radius:20px;
    background:#223a33;
    color:#fff;
  }
  .about-cta h2{margin:0 0 8px;}
  .about-cta p{margin:0;line-height:1.7;}
  .about-cta .actions{
    display:flex;
    gap:10px;
    flex-wrap:wrap;
  }
  .about-cta .button{
    background:#f2e8d8;
    color:#223a33!important;
  }
  .about-cta .button.secondary{
    background:transparent;
    border-color:#f2e8d8;
    color:#fff!important;
  }
  @media (max-width:900px){
    .about-hero-grid{grid-template-columns:1fr;}
    .philosophy-grid{grid-template-columns:1fr;}
    .about-cta{flex-direction:column;align-items:flex-start;}
  }
</style>

<section class="about-hero">
  <div class="container">
    <div class="about-hero-grid">
      <div class="about-photo">
        <img src="{{ '/assets/img/director.jpg' | relative_url }}" alt="수원 약손한의원 강민정 대표원장">
      </div>

  <div>
    <span class="eyebrow">DIRECTOR & PHILOSOPHY</span>
    <h1>질환만 보지 않고,<br>사람을 함께 봅니다.</h1>
    <p>
      안녕하세요. 수원 약손한의원 대표원장 강민정입니다.
      2017년 개원 이후 한 자리에서 지역 주민의 건강을 함께 살피는
      <strong>동네주치의</strong>를 지향하며 진료해왔습니다.
    </p>
    <p>
      소아 시절 보약을 상담했던 아이가 자라 다시 찾아오고,
      한 가족의 부모님과 자녀가 함께 내원하는 모습을 보며
      한 번의 치료보다 오랜 시간 건강을 함께 살피는 진료의 의미를 중요하게 생각하게 되었습니다.
    </p>
  </div>
</div>

  </div>
</section>

<section class="about-section">
  <div class="container">
    <div class="about-heading">
      <span class="eyebrow">PHILOSOPHY</span>
      <h2>증상 하나보다, 그 증상이 생긴 사람의 생활을 함께 봅니다.</h2>
      <p>
        같은 증상을 호소하더라도 불편이 시작된 이유와 생활환경은 사람마다 다를 수 있습니다.
        그래서 현재 증상뿐 아니라 식사, 수면, 소화, 스트레스와 생활습관을 함께 확인합니다.
      </p>
    </div>

<div class="philosophy-grid">
  <article class="philosophy-card">
    <h3>질환만 보지 않습니다.</h3>
    <p>현재의 증상과 함께 과거의 생활습관, 식사와 수면, 스트레스가 어떤 영향을 주었는지 살펴봅니다.</p>
  </article>

  <article class="philosophy-card">
    <h3>개인의 상태를 함께 봅니다.</h3>
    <p>같은 병명이라도 불편의 양상은 다를 수 있어 평소 몸의 반응과 체질적 경향을 함께 참고합니다.</p>
  </article>

  <article class="philosophy-card">
    <h3>설명하는 진료를 중요하게 생각합니다.</h3>
    <p>환자분이 자신의 상태를 이해하고 생활 속에서 관리할 수 있도록 필요한 내용을 충분히 설명하려고 합니다.</p>
  </article>
</div>

  </div>
</section>

<section class="about-section soft">
  <div class="container">
    <div class="quote-box">
      <h3>“치료는 짧고, 생활은 길다.”</h3>
      <p>
        진료실에서의 치료만큼 중요한 것은 다시 같은 불편이 반복되지 않도록
        일상에서 조절할 수 있는 부분을 찾는 것이라고 생각합니다.
        필요한 치료 방향을 설명하고, 다른 의료기관의 검사나 진료가 우선인 경우에는
        그 부분도 분명하게 안내하려고 합니다.
      </p>
    </div>
  </div>
</section>

<section class="about-section">
  <div class="container">
    <div class="about-heading">
      <span class="eyebrow">STUDY & INTEREST</span>
      <h2>불면과 불안, 스트레스 관련 증상에도 꾸준히 관심을 가져왔습니다.</h2>
      <p>
        현대인의 건강에서는 몸의 증상뿐 아니라 수면과 스트레스, 정서적 긴장을 함께 살펴보는 것이 중요하다고 생각합니다.
      </p>
    </div>

<div class="career-list">
  <div class="career-item">
    <strong>한방신경정신과 분야 관심 및 연구</strong>
    <p>불면, 불안, 두근거림, 화병 등 스트레스와 관련된 증상을 진료와 연구의 중요한 영역으로 보고 있습니다.</p>
  </div>

  <div class="career-item">
    <strong>2011년</strong>
    <p>동의신경정신과학회지에 꿈에 관한 문헌연구 발표</p>
  </div>

  <div class="career-item">
    <strong>2012년</strong>
    <p>동의신경정신과학회지에 불안장애 치료에 관한 최근 임상연구 동향 발표</p>
  </div>

  <div class="career-item">
    <strong>2017년</strong>
    <p>수원 약손한의원 개원</p>
  </div>
</div>

  </div>
</section>

<section class="about-section soft">
  <div class="container">
    <div class="about-heading">
      <span class="eyebrow">YAKSON</span>
      <h2>따뜻한 약손이 되겠습니다.</h2>
      <p>
        ‘약손한의원’이라는 이름에는 아픈 분들에게 따뜻한 약손이 되어드리고 싶다는 마음이 담겨 있습니다.
        한결같이 같은 자리에서 환자분의 이야기에 귀 기울이고,
        현재의 불편뿐 아니라 앞으로의 건강한 생활까지 함께 고민하는 한의원이 되겠습니다.
      </p>
    </div>
  </div>
</section>

<section class="about-section" style="padding-top:0">
  <div class="container">
    <div class="about-cta">
      <div>
        <h2>현재의 불편이 언제부터 시작됐는지부터 함께 살펴보겠습니다.</h2>
        <p>기존 검사 결과와 복용약이 있다면 진료 시 함께 알려주세요.</p>
      </div>
      <div class="actions">
        <a class="button" href="{{ site.data.clinic.phone_uri }}">전화 문의</a>
        <a class="button secondary" href="{{ '/clinic/' | relative_url }}">진료 안내</a>
        <a class="button secondary" href="{{ '/location/' | relative_url }}">오시는 길</a>
      </div>
    </div>
  </div>
</section>
