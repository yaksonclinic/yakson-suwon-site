<style>
  .treatment-hero{
    padding:82px 0 54px;
    background:linear-gradient(180deg,#f5f1e8 0%,#fff 100%);
  }
  .treatment-hero h1{
    margin:8px 0 18px;
    font-size:clamp(2.3rem,5vw,4rem);
    line-height:1.12;
  }
  .treatment-hero p{
    max-width:760px;
    margin:0;
    color:#65706b;
    font-size:1.05rem;
    line-height:1.85;
  }

  .treatment-section{
    padding:68px 0;
  }
  .treatment-section.soft{
    background:#f7f6f1;
  }
  .treatment-heading{
    max-width:760px;
    margin-bottom:34px;
  }
  .treatment-heading h2{
    margin:8px 0 14px;
    font-size:clamp(1.8rem,3vw,2.8rem);
    line-height:1.25;
  }
  .treatment-heading p{
    margin:0;
    color:#65706b;
    line-height:1.8;
  }

  .treatment-grid{
    display:grid;
    grid-template-columns:repeat(3,minmax(0,1fr));
    gap:18px;
  }
  .treatment-card{
    min-height:230px;
    padding:28px;
    border:1px solid rgba(0,0,0,.09);
    border-radius:20px;
    background:#fff;
  }
  .treatment-card .num{
    display:block;
    margin-bottom:24px;
    color:#315c4d;
    font-size:.78rem;
    font-weight:900;
    letter-spacing:.08em;
  }
  .treatment-card h3{
    margin:0 0 12px;
    font-size:1.23rem;
  }
  .treatment-card p{
    margin:0;
    color:#68736e;
    font-size:.96rem;
    line-height:1.78;
  }

  .treatment-philosophy{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:24px;
    align-items:stretch;
  }
  .treatment-quote,
  .treatment-note{
    padding:32px;
    border-radius:20px;
  }
  .treatment-quote{
    background:#223a33;
    color:#fff;
  }
  .treatment-quote span{
    display:block;
    margin-bottom:12px;
    font-size:.76rem;
    font-weight:900;
    letter-spacing:.08em;
    opacity:.78;
  }
  .treatment-quote h2{
    margin:0 0 14px;
    font-size:clamp(1.65rem,3vw,2.35rem);
    line-height:1.35;
  }
  .treatment-quote p{
    margin:0;
    line-height:1.8;
    opacity:.9;
  }
  .treatment-note{
    background:#eee8dc;
  }
  .treatment-note h3{
    margin:0 0 12px;
  }
  .treatment-note p{
    margin:0 0 12px;
    line-height:1.8;
  }
  .treatment-note p:last-child{
    margin-bottom:0;
  }

  .treatment-cta{
    display:flex;
    justify-content:space-between;
    align-items:center;
    gap:24px;
    padding:32px;
    background:#f5f1e8;
    border-radius:20px;
  }
  .treatment-cta h2{
    margin:0 0 8px;
    font-size:1.55rem;
  }
  .treatment-cta p{
    margin:0;
    color:#68736e;
    line-height:1.7;
  }
  .treatment-cta .actions{
    display:flex;
    gap:10px;
    flex-wrap:wrap;
  }

  @media (max-width:900px){
    .treatment-grid{
      grid-template-columns:repeat(2,minmax(0,1fr));
    }
    .treatment-philosophy{
      grid-template-columns:1fr;
    }
    .treatment-cta{
      flex-direction:column;
      align-items:flex-start;
    }
  }

  @media (max-width:620px){
    .treatment-hero{
      padding:62px 0 40px;
    }
    .treatment-section{
      padding:52px 0;
    }
    .treatment-grid{
      grid-template-columns:1fr;
      gap:12px;
    }
    .treatment-card{
      min-height:0;
      padding:23px;
    }
  }
</style>

<section class="treatment-hero">
  <div class="container">
    <span class="eyebrow">TREATMENT GUIDE</span>
    <h1>약손한의원의<br>진료안내</h1>
    <p>
      질환명 하나만 보고 치료를 정하기보다 현재 증상과 기존 진단,
      복용약, 생활습관과 진찰 소견을 함께 확인합니다.
      환자분의 이야기를 충분히 듣고 현재 몸 상태에 필요한 진료 방향을 상담합니다.
    </p>
  </div>
</section>

<section class="treatment-section">
  <div class="container">
    <div class="treatment-heading">
      <span class="eyebrow">HOW WE CARE</span>
      <h2>진료는 이렇게 진행합니다.</h2>
      <p>
        한 가지 증상만 보기보다 불편이 시작된 시기와 생활 상태를 함께 살펴보고,
        필요한 진찰과 치료 방법을 순서대로 안내합니다.
      </p>
    </div>

<div class="treatment-grid">
  <article class="treatment-card">
    <span class="num">01</span>
    <h3>충분한 문진</h3>
    <p>
      현재 가장 불편한 증상과 시작 시기, 심해지는 상황을 확인합니다.
      식사·소화·수면·배변·피로·스트레스, 기존 질환과 복용약도 필요한 범위에서 함께 살펴봅니다.
    </p>
  </article>

  <article class="treatment-card">
    <span class="num">02</span>
    <h3>맥진</h3>
    <p>
      약손한의원에서는 맥진을 중요한 진찰 과정으로 생각합니다.
      맥의 깊이, 빠르기, 힘과 긴장도 등 여러 특징을 살피고 문진과 다른 진찰 내용을 함께 종합합니다.
    </p>
  </article>

  <article class="treatment-card">
    <span class="num">03</span>
    <h3>침·약침 치료</h3>
    <p>
      증상과 진찰 소견에 따라 경혈과 자극 방법을 달리할 수 있습니다.
      약침 적용 여부 역시 현재 상태와 과거력, 복용약 등을 확인한 뒤 결정합니다.
    </p>
  </article>

  <article class="treatment-card">
    <span class="num">04</span>
    <h3>추나·부항·한방물리요법</h3>
    <p>
      근골격계 상태와 움직임의 불편, 치료 필요성을 살핀 뒤
      상태에 따라 보조적인 치료 방법으로 선택할 수 있습니다.
    </p>
  </article>

  <article class="treatment-card">
    <span class="num">05</span>
    <h3>한약 상담</h3>
    <p>
      현재 증상과 생활 상태, 기존 질환과 복용약 등을 함께 확인하고
      한약 처방이 필요한지 개인의 상태에 맞춰 상담합니다.
    </p>
  </article>

  <article class="treatment-card">
    <span class="num">06</span>
    <h3>생활관리·필요 시 검사 안내</h3>
    <p>
      수면, 식사, 활동량과 스트레스처럼 증상에 영향을 줄 수 있는 생활 요소를 함께 확인합니다.
      추가 검사나 다른 의료기관의 평가가 우선인 경우에는 그 부분을 안내합니다.
    </p>
  </article>
</div>

  </div>
</section>

<section class="treatment-section soft">
  <div class="container">
    <div class="treatment-philosophy">
      <div class="treatment-quote">
        <span>YAKSON PHILOSOPHY</span>
        <h2>“치료는 짧고,<br>생활은 길다.”</h2>
        <p>
          진료실에서의 치료뿐 아니라 일상에서 조절할 수 있는 부분을 함께 설명하고,
          환자분이 자신의 몸 상태를 이해할 수 있도록 안내하는 진료를 중요하게 생각합니다.
        </p>
      </div>

  <div class="treatment-note">
    <h3>필요한 진료가 우선입니다.</h3>
    <p>
      모든 증상을 한의원 치료만으로 판단하지 않습니다.
      갑자기 발생한 심한 증상이나 정밀검사가 필요한 상황,
      다른 의료기관의 진료가 우선인 경우에는 적절한 평가를 안내합니다.
    </p>
    <p>
      구체적인 진료 가능 여부와 치료 방법은 환자분의 상태를 확인한 뒤 결정됩니다.
    </p>
  </div>
</div>

  </div>
</section>

<section class="treatment-section">
  <div class="container">
    <div class="treatment-cta">
      <div>
        <h2>진료 전 궁금한 점이 있으신가요?</h2>
        <p>현재 증상과 기존 검사 결과, 복용약이 있다면 진료 시 함께 알려주세요.</p>
      </div>
      <div class="actions">
        <a class="button" href="{{ site.data.clinic.phone_uri }}">전화 문의</a>
        <a class="button secondary" href="{{ '/about/' | relative_url }}">원장 진료철학 보기</a>
      </div>
    </div>
  </div>
</section>
