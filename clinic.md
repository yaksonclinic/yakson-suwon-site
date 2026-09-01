<style>
  .clinic-about-hero{
    padding:76px 0 70px;
    background:#f5f1e8;
  }

  .clinic-about-hero-grid{
    display:grid;
    grid-template-columns:1.05fr .95fr;
    gap:58px;
    align-items:center;
  }

  .clinic-about-photo img{
    display:block;
    width:100%;
    aspect-ratio:4 / 3;
    object-fit:cover;
    border-radius:30px;
    box-shadow:0 18px 45px rgba(28,48,41,.10);
  }

  .clinic-about-copy h1{
    margin:8px 0 22px;
    font-size:clamp(2.35rem,5vw,4.35rem);
    line-height:1.12;
    letter-spacing:-.045em;
  }

  .clinic-about-copy .lead{
    margin:0 0 24px;
    color:#5f6b66;
    font-size:1.08rem;
    line-height:1.9;
  }

  .clinic-about-sign{
    padding-top:20px;
    border-top:1px solid rgba(0,0,0,.10);
    color:#315c4d;
    font-size:.95rem;
    font-weight:800;
  }

  .clinic-about-section{
    padding:76px 0;
  }

  .clinic-about-heading{
    max-width:780px;
    margin-bottom:36px;
  }

  .clinic-about-heading h2{
    margin:8px 0 14px;
    font-size:clamp(1.9rem,3.5vw,3rem);
    line-height:1.25;
    letter-spacing:-.035em;
  }

  .clinic-about-heading p{
    margin:0;
    color:#66716c;
    line-height:1.85;
  }

  .clinic-values{
    display:grid;
    grid-template-columns:repeat(3,minmax(0,1fr));
    gap:18px;
  }

  .clinic-value{
    padding:30px;
    border:1px solid rgba(0,0,0,.09);
    border-radius:22px;
    background:#fff;
  }

  .clinic-value .num{
    display:block;
    margin-bottom:28px;
    color:#315c4d;
    font-size:.76rem;
    font-weight:900;
    letter-spacing:.08em;
  }

  .clinic-value h3{
    margin:0 0 12px;
    font-size:1.25rem;
  }

  .clinic-value p{
    margin:0;
    color:#68736e;
    line-height:1.8;
  }

  .clinic-story{
    background:#f7f6f1;
  }

  .clinic-story-grid{
    display:grid;
    grid-template-columns:.8fr 1.2fr;
    gap:56px;
    align-items:start;
  }

  .clinic-story-title{
    position:sticky;
    top:110px;
  }

  .clinic-story-title h2{
    margin:8px 0 0;
    font-size:clamp(2rem,3.5vw,3.1rem);
    line-height:1.25;
  }

  .clinic-story-copy{
    display:grid;
    gap:20px;
  }

  .clinic-story-copy p{
    margin:0;
    font-size:1.03rem;
    line-height:1.95;
    color:#59655f;
  }

  .clinic-info-wrap{
    display:grid;
    grid-template-columns:1.1fr .9fr;
    gap:22px;
  }

  .clinic-info-card{
    padding:32px;
    border-radius:22px;
    border:1px solid rgba(0,0,0,.09);
    background:#fff;
  }

  .clinic-info-card h2{
    margin:0 0 24px;
    font-size:1.45rem;
  }

  .clinic-info-list{
    display:grid;
    gap:0;
  }

  .clinic-info-row{
    display:grid;
    grid-template-columns:110px 1fr;
    gap:18px;
    padding:15px 0;
    border-top:1px solid rgba(0,0,0,.09);
  }

  .clinic-info-row:first-child{
    border-top:0;
    padding-top:0;
  }

  .clinic-info-row strong{
    color:#315c4d;
    font-size:.92rem;
  }

  .clinic-info-row span{
    color:#59655f;
    line-height:1.65;
  }

  .clinic-link-card{
    display:flex;
    flex-direction:column;
    justify-content:space-between;
    padding:32px;
    border-radius:22px;
    background:#223a33;
    color:#fff;
  }

  .clinic-link-card h2{
    margin:8px 0 14px;
    font-size:1.75rem;
    line-height:1.35;
  }

  .clinic-link-card p{
    margin:0 0 26px;
    color:rgba(255,255,255,.78);
    line-height:1.8;
  }

  .clinic-link-actions{
    display:flex;
    gap:10px;
    flex-wrap:wrap;
  }

  .clinic-link-actions .button{
    background:#f2e8d8;
    color:#223a33!important;
  }

  .clinic-link-actions .button.secondary{
    background:transparent;
    border-color:rgba(255,255,255,.55);
    color:#fff!important;
  }

  @media (max-width:900px){
    .clinic-about-hero-grid,
    .clinic-story-grid,
    .clinic-info-wrap{
      grid-template-columns:1fr;
    }

    .clinic-values{
      grid-template-columns:1fr;
    }

    .clinic-story-title{
      position:static;
    }
  }

  @media (max-width:620px){
    .clinic-about-hero{
      padding:56px 0 52px;
    }

    .clinic-about-hero-grid{
      gap:32px;
    }

    .clinic-about-photo img{
      border-radius:22px;
    }

    .clinic-about-section{
      padding:56px 0;
    }

    .clinic-value,
    .clinic-info-card,
    .clinic-link-card{
      padding:24px;
    }

    .clinic-info-row{
      grid-template-columns:90px 1fr;
      gap:12px;
    }
  }
</style>

<section class="clinic-about-hero">
  <div class="container">
    <div class="clinic-about-hero-grid">

  <div class="clinic-about-photo">
    <img
      src="{{ '/assets/img/clinic-interior.jpg' | relative_url }}"
      alt="수원 우만동 약손한의원 내부 모습">
  </div>

  <div class="clinic-about-copy">
    <span class="eyebrow">ABOUT YAKSON</span>
    <h1>오래도록<br>곁에서 살피는 진료.</h1>

    <p class="lead">
    약손한의원은 2017년부터 수원 우만동을 중심으로 지동·연무동·매교동 등 인근 지역 주민들의 건강 고민을 함께 살펴오고 있습니다.
      눈앞의 증상만 보기보다 환자분의 이야기를 충분히 듣고,
      현재의 몸 상태와 생활의 맥락을 함께 이해하려고 합니다.
    </p>

    <div class="clinic-about-sign">
      수원 약손한의원
    </div>
  </div>

</div>

  </div>
</section>

<section class="clinic-about-section">
  <div class="container">

<div class="clinic-about-heading">
  <span class="eyebrow">OUR APPROACH</span>
  <h2>약손한의원이 중요하게 생각하는 세 가지</h2>
  <p>
    거창한 약속보다 진료실에서 지켜야 할 기본을 중요하게 생각합니다.
  </p>
</div>

<div class="clinic-values">

  <article class="clinic-value">
    <span class="num">01</span>
    <h3>충분히 듣습니다.</h3>
    <p>
      언제부터 불편했는지, 어떤 상황에서 달라지는지,
      수면과 식사·스트레스·기존 질환과 복용약까지 필요한 내용을 차분히 확인합니다.
    </p>
  </article>

  <article class="clinic-value">
    <span class="num">02</span>
    <h3>세심하게 살핍니다.</h3>
    <p>
      문진과 진찰 내용을 함께 보며 현재 몸 상태를 살핍니다.
      약손한의원에서는 맥진 역시 중요한 진찰 과정의 하나로 생각합니다.
    </p>
  </article>

  <article class="clinic-value">
    <span class="num">03</span>
    <h3>필요한 것을 설명합니다.</h3>
    <p>
      치료 방향과 생활관리 방법을 이해하기 쉽게 설명하고,
      검사나 다른 의료기관의 평가가 우선인 경우에는 그 부분도 안내합니다.
    </p>
  </article>

</div>

  </div>
</section>

<section class="clinic-about-section clinic-story">
  <div class="container">
    <div class="clinic-story-grid">

  <div class="clinic-story-title">
    <span class="eyebrow">SINCE 2017</span>
    <h2>한 자리에서<br>이어온 시간</h2>
  </div>

  <div class="clinic-story-copy">
    <p>
      소아 시절 진료를 받았던 아이가 성장해 다시 찾아오고,
      한 분의 진료가 배우자와 부모님, 자녀의 방문으로 이어지기도 합니다.
      그런 시간을 통해 한 번의 치료보다 오래도록 건강을 함께 살피는
      동네 한의원의 역할을 중요하게 생각하게 되었습니다.
    </p>

    <p>
      몸의 불편은 한 가지 원인으로만 설명하기 어려운 경우도 있습니다.
      약손한의원은 현재의 증상뿐 아니라 몸의 변화와 생활 상태를 함께 살피고,
      환자분이 자신의 상태를 이해할 수 있도록 설명하는 진료를 지향합니다.
    </p>

    <a class="card-link" href="{{ '/about/' | relative_url }}">
      강민정 원장 진료철학 자세히 보기 →
    </a>
  </div>

</div>

  </div>
</section>

<section class="clinic-about-section">
  <div class="container">

<div class="clinic-info-wrap">

  <div class="clinic-info-card">
    <h2>약손한의원 진료 안내</h2>

     <div class="clinic-info-row">
        <strong>주소</strong>
        <span>경기도 수원시 팔달구 세지로 393, 농협 우만지점 2층</span>
      </div>

      <div class="clinic-info-row">
        <strong>전화</strong>
        <span>031-247-7522</span>
      </div>

      <div class="clinic-info-row">
        <strong>평일</strong>
        <span>09:00–19:00 (접수마감 18:30) 점심시간 13:00–14:00</span>
      </div>

      <div class="clinic-info-row">
        <strong>토요일</strong>
        <span>09:00–14:00 · 점심시간 없음</span>
      </div>

      <div class="clinic-info-row">
        <strong>휴진</strong>
        <span>일요일·공휴일</span>
      </div>
    </div>
  </div>

  <div class="clinic-link-card">
    <div>
      <span class="eyebrow" style="color:#d9cdb9">VISIT YAKSON</span>
      <h2>처음 방문하시는 분도<br>편하게 문의해주세요.</h2>
      <p>
        대체공휴일이나 연휴 전후 일정은 변경될 수 있으므로
        방문 전 진료시간을 확인해주세요.
      </p>
    </div>

    <div class="clinic-link-actions">
      <a class="button" href="{{ site.data.clinic.phone_uri }}">전화 문의</a>
      <a class="button secondary" href="{{ '/location/' | relative_url }}">오시는 길</a>
      <a class="button secondary" href="{{ '/treatment/' | relative_url }}">진료안내</a>
    </div>
  </div>

</div>

  </div>
</section>
