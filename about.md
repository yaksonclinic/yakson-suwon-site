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
    line-height:1.85;
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
  .pulse-visual-grid{
    display:grid;
    grid-template-columns:repeat(2,minmax(0,1fr));
    gap:20px;
    margin:34px 0;
  }
  .pulse-visual{
    margin:0;
    padding:14px;
    background:#fff;
    border:1px solid rgba(0,0,0,.09);
    border-radius:20px;
  }
  .pulse-visual img{
    display:block;
    width:100%;
    height:auto;
    border-radius:14px;
  }
  .pulse-visual figcaption{
    padding:12px 4px 2px;
    color:#68736e;
    font-size:14px;
    line-height:1.6;
  }
  .pulse-note{
    margin-top:28px;
    padding:26px;
    border-left:4px solid #315c4d;
    background:#fff;
    border-radius:0 16px 16px 0;
  }
  .pulse-note strong{
    display:block;
    margin-bottom:8px;
    font-size:1.08rem;
  }
  .pulse-note p{
    margin:0;
    line-height:1.8;
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
    .pulse-visual-grid{grid-template-columns:1fr;}
    .about-cta{flex-direction:column;align-items:flex-start;}
  }
</style>

<section class="about-hero">
  <div class="container">
    <div class="about-hero-grid">
      <div class="about-photo">
        <img
  src="{{ '/assets/img/clinic/clinic-interior.jpg' | relative_url }}"
  alt="수원 약손한의원 내부 모습">
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
      저는 환자분의 이야기를 충분히 듣고,
      현재의 증상뿐 아니라 식사와 수면, 생활습관과 스트레스를 함께 살피며
      <strong>진료 과정에서 맥진을 중요하게 생각합니다.</strong>
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
    <p>같은 병명이라도 불편의 양상은 다를 수 있어 평소 몸의 반응과 생활 상태를 함께 참고합니다.</p>
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
    <div class="about-heading">
      <span class="eyebrow">PULSE DIAGNOSIS</span>
      <h2>문진을 충분히 하고,<br>맥을 세심하게 살펴봅니다.</h2>

  <p>
    두통, 어지럼증, 만성통증, 소화불량, 불면처럼
    한 가지 증상만으로 설명하기 어려운 여러 불편을 함께 호소하는 분들이 있습니다.
    검사에서 큰 이상이 확인되지 않았더라도 몸의 불편이 반복된다고 이야기하는 경우도 있습니다.
  </p>

  <p>
    저는 이런 경우 현재 증상만 확인하기보다
    식사와 수면, 소화, 스트레스, 피로도와 생활 상태를 충분히 듣고
    <strong>맥진을 중요한 진찰 과정의 하나로 활용합니다.</strong>
  </p>
</div>

<div class="pulse-visual-grid">
  <figure class="pulse-visual">
    <img
      src="{{ '/assets/img/pulse/pulse-location.jpg' | relative_url }}"
      alt="촌 관 척 위치를 설명하는 맥진 안내 이미지">
    <figcaption>손목의 촌(寸)·관(關)·척(尺)을 나누어 맥의 특징을 살펴봅니다.</figcaption>
  </figure>

  <figure class="pulse-visual">
    <img
      src="{{ '/assets/img/pulse/pulse-pattern.jpg' | relative_url }}"
      alt="맥의 깊이와 속도 힘 긴장도를 설명하는 맥진 안내 이미지">
    <figcaption>맥의 빠르기뿐 아니라 깊이, 힘, 긴장도 등 여러 특징을 함께 관찰합니다.</figcaption>
  </figure>
</div>

<div class="about-heading">
  <p>
    한의학의 맥진에서는 손목의 촌(寸)·관(關)·척(尺)을 나누어 살피고,
    맥의 깊이와 빠르기, 힘과 긴장도 등 여러 특징을 함께 관찰합니다.
    이러한 맥의 특징을 다른 진찰 내용과 종합하여
    현재 몸 상태를 이해하는 데 참고합니다.
  </p>

  <p>
    맥을 짚는 것에서 끝나지 않고
    <strong>왜 이런 맥의 특징이 관찰되는지 환자분이 이해할 수 있도록 설명하는 것</strong>도
    중요하게 생각합니다.
  </p>

  <p>
    필요할 때에는 이전 진료 때의 맥과 현재의 맥을 비교해
    몸 상태의 변화를 살펴보기도 합니다.
  </p>
</div>

<div class="pulse-note">
  <strong>맥진만으로 모든 상태를 판단하지 않습니다.</strong>
  <p>
    환자분이 말씀해주시는 증상과 생활 변화, 다른 진찰 내용,
    필요한 경우 기존 검사 결과와 복용약 등을 함께 확인하여 종합적으로 살펴봅니다.
    새로운 증상이 심하거나 검사가 필요한 상황에서는 해당 의료기관의 평가를 우선 안내합니다.
  </p>
</div>

  </div>
</section>

<section class="about-section">
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

<section class="about-section soft">
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

<section class="about-section">
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
