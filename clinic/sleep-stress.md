<style>
  .clinic-page-hero{
    padding:84px 0 64px;
    background:linear-gradient(180deg,#f5f1e8 0%,#fff 100%);
  }
  .clinic-page-hero .clinic-kicker{
    display:inline-block;
    margin-bottom:14px;
    font-size:.82rem;
    letter-spacing:.14em;
    font-weight:700;
  }
  .clinic-page-hero h1{
    margin:0 0 20px;
    font-size:clamp(2.3rem,5vw,4.4rem);
    line-height:1.08;
  }
  .clinic-page-hero .clinic-lead{
    max-width:820px;
    font-size:1.08rem;
    line-height:1.85;
  }
  .clinic-nav{
    display:flex;
    flex-wrap:wrap;
    gap:10px;
    margin-top:28px;
  }
  .clinic-nav a{
    display:inline-block;
    padding:10px 15px;
    border:1px solid rgba(0,0,0,.14);
    border-radius:999px;
    text-decoration:none;
  }

  .clinic-section{padding:72px 0;}
  .clinic-section.soft{background:#f7f6f1;}
  .clinic-heading{max-width:800px;margin-bottom:34px;}
  .clinic-heading h2{
    margin:8px 0 14px;
    font-size:clamp(1.8rem,3vw,2.8rem);
    line-height:1.2;
  }
  .clinic-heading p{line-height:1.8;}

  .stress-grid{
    display:grid;
    grid-template-columns:repeat(3,minmax(0,1fr));
    gap:18px;
  }
  .stress-card{
    padding:26px;
    border:1px solid rgba(0,0,0,.09);
    border-radius:18px;
    background:#fff;
  }
  .stress-card h3{margin:0 0 10px;font-size:1.14rem;}
  .stress-card p{margin:0;line-height:1.75;}

  .check-list{
    display:grid;
    grid-template-columns:repeat(2,minmax(0,1fr));
    gap:16px;
  }
  .check-item{
    padding:24px;
    border-top:1px solid rgba(0,0,0,.14);
  }
  .check-item strong{
    display:block;
    margin-bottom:8px;
    font-size:1.05rem;
  }
  .check-item p{margin:0;line-height:1.75;}

  .treatment-grid{
    display:grid;
    grid-template-columns:repeat(4,minmax(0,1fr));
    gap:16px;
  }
  .treatment-card{
    padding:24px;
    border-radius:16px;
    background:#fff;
    border:1px solid rgba(0,0,0,.08);
  }
  .treatment-card h3{margin:0 0 10px;}
  .treatment-card p{margin:0;line-height:1.75;}

  .important-box{
    padding:30px;
    border-radius:18px;
    background:#eee8dc;
  }
  .important-box h3{margin-top:0;font-size:1.35rem;}
  .important-box p{margin-bottom:0;line-height:1.8;}

  .safety-box{
    padding:28px;
    border-radius:18px;
    background:#223a33;
    color:#fff;
  }
  .safety-box h3{margin-top:0;}
  .safety-box ul{
    margin:14px 0 0;
    padding-left:20px;
    line-height:1.9;
  }

  .faq-list{border-top:1px solid rgba(0,0,0,.12);}
  .faq-item{
    padding:24px 0;
    border-bottom:1px solid rgba(0,0,0,.12);
  }
  .faq-item h3{margin:0 0 10px;font-size:1.08rem;}
  .faq-item p{margin:0;line-height:1.8;}

  .clinic-cta{
    display:flex;
    justify-content:space-between;
    gap:28px;
    align-items:center;
    padding:34px;
    border-radius:20px;
    background:#eee8dc;
  }
  .clinic-cta h2{margin:0 0 8px;}
  .clinic-cta p{margin:0;line-height:1.7;}
  .clinic-cta .actions{
    display:flex;
    flex-wrap:wrap;
    gap:10px;
    flex-shrink:0;
  }

  @media (max-width:900px){
    .stress-grid{grid-template-columns:repeat(2,minmax(0,1fr));}
    .treatment-grid{grid-template-columns:repeat(2,minmax(0,1fr));}
    .clinic-cta{align-items:flex-start;flex-direction:column;}
  }
  @media (max-width:640px){
    .clinic-page-hero{padding:64px 0 48px;}
    .clinic-section{padding:56px 0;}
    .stress-grid,.check-list,.treatment-grid{grid-template-columns:1fr;}
  }
</style>

<section class="clinic-page-hero">
  <div class="container">
    <span class="clinic-kicker">SLEEP & STRESS CARE</span>
    <h1>수면·스트레스 관리 클리닉</h1>
    <p class="clinic-lead">
      잠을 잘 자지 못하거나 스트레스가 오래 이어지면
      <strong>두근거림, 가슴 답답함, 긴장감, 목 이물감, 소화불편과 피로</strong>처럼
      몸의 여러 불편이 함께 나타날 수 있습니다.
      약손한의원에서는 수면의 양상과 스트레스 상황, 생활리듬과 기존 진료 내용을 함께 살펴봅니다.
    </p>
    <div class="clinic-nav" aria-label="수면·스트레스 관리 클리닉 페이지 바로가기">
      <a href="#symptoms">주요 증상</a>
      <a href="#check">진료 시 확인</a>
      <a href="#treatment">진료 방법</a>
      <a href="#faq">자주 묻는 질문</a>
    </div>
  </div>
</section>

<section class="clinic-section" id="symptoms">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">SLEEP & STRESS CONCERNS</span>
      <h2>이런 불편으로 상담합니다.</h2>
      <p>한 가지 증상만 보기보다 잠과 스트레스, 신체 증상이 어떻게 연결되어 반복되는지를 함께 확인합니다.</p>
    </div>

<div class="stress-grid">
  <article class="stress-card">
    <h3>잠들기 어려운 불면</h3>
    <p>누워도 생각이 많아 잠들기 어렵거나 잠드는 데 오랜 시간이 걸리는 경우 취침 전 생활과 긴장 상태를 함께 살펴봅니다.</p>
  </article>

  <article class="stress-card">
    <h3>자주 깨는 잠·새벽각성</h3>
    <p>밤중에 여러 번 깨거나 새벽에 일찍 깬 뒤 다시 잠들기 어려운 경우 수면시간과 각성 패턴을 확인합니다.</p>
  </article>

  <article class="stress-card">
    <h3>두근거림·심장이 뛰는 느낌</h3>
    <p>긴장하거나 스트레스를 받을 때 심장이 빨리 뛰는 느낌이 반복되는지, 카페인·수면 부족과의 관계를 함께 살펴봅니다.</p>
  </article>

  <article class="stress-card">
    <h3>가슴 답답함·숨이 차는 느낌</h3>
    <p>검사에서 특별한 이상이 없는데도 답답함이 반복되거나 긴장 상황에서 심해지는 경우 발생 상황과 지속 시간을 확인합니다.</p>
  </article>

  <article class="stress-card">
    <h3>불안·긴장·예민함</h3>
    <p>마음이 쉽게 긴장되고 작은 일에도 예민해지며 잠이나 소화, 두근거림이 함께 불편한지 살펴봅니다.</p>
  </article>

  <article class="stress-card">
    <h3>스트레스성 신체 불편</h3>
    <p>목에 무엇이 걸린 듯한 느낌, 두통·어지럼, 소화불편, 피로처럼 스트레스와 함께 반복되는 신체 증상을 확인합니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section soft" id="check">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">CONSULTATION CHECKPOINT</span>
      <h2>잠과 스트레스의 흐름을 함께 확인합니다.</h2>
      <p>수면 문제와 두근거림은 원인이 다양할 수 있어 발생 시점과 기존 검사를 함께 확인하는 것이 중요합니다.</p>
    </div>

<div class="check-list">
  <div class="check-item">
    <strong>잠드는 시간과 실제 수면시간</strong>
    <p>몇 시에 눕고 실제로 잠드는 데 얼마나 걸리는지, 총 수면시간은 어느 정도인지 확인합니다.</p>
  </div>

  <div class="check-item">
    <strong>밤중 각성과 새벽각성</strong>
    <p>몇 번 정도 깨는지, 깬 뒤 다시 잠들기 어려운지, 특정 시간에 반복되는지 살펴봅니다.</p>
  </div>

  <div class="check-item">
    <strong>스트레스와 증상의 관계</strong>
    <p>업무, 학업, 가족관계 등 특정 상황에서 불면·두근거림·가슴 답답함이 심해지는지 확인합니다.</p>
  </div>

  <div class="check-item">
    <strong>카페인·음주·야간 생활</strong>
    <p>커피와 에너지음료, 늦은 음주·야식, 스마트폰 사용 등이 수면과 연관되는지 살펴봅니다.</p>
  </div>

  <div class="check-item">
    <strong>소화·피로·두통 등 동반 증상</strong>
    <p>스트레스가 심할 때 명치 답답함, 설사·변비, 두통, 어지럼, 피로가 함께 나타나는지 확인합니다.</p>
  </div>

  <div class="check-item">
    <strong>기존 검사와 복용약</strong>
    <p>심전도·혈액검사 등 기존 검사 결과와 수면제, 항불안제, 심장약 등 현재 복용 중인 약이 있다면 함께 확인합니다.</p>
  </div>
</div>

  </div>
</section>

<section class="clinic-section">
  <div class="container">
    <div class="important-box">
      <h3>두근거림이나 가슴 답답함을 모두 스트레스 때문이라고 단정하지 않습니다.</h3>
      <p>
        두근거림과 가슴 불편은 스트레스와 함께 나타날 수도 있지만,
        부정맥·갑상선 질환·빈혈 등 다른 원인과 관련될 수도 있습니다.
        증상이 처음 생겼거나 빈도가 늘었거나 강도가 심해졌다면 필요한 검사를 먼저 받는 것이 중요합니다.
        기존 검사 결과가 있다면 진료 시 함께 확인합니다.
      </p>
    </div>
  </div>
</section>

<section class="clinic-section soft">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">PATTERN & APPROACH</span>
      <h2>불편이 나타나는 양상에 따라 함께 살펴볼 부분이 달라집니다.</h2>
    </div>

<div class="stress-grid">
  <article class="stress-card">
    <h3>생각이 많아 잠들기 어려운 유형</h3>
    <p>잠자리에 누우면 생각이 많아지고 긴장감이 올라와 잠들기 어려운 경우입니다.</p>
  </article>

  <article class="stress-card">
    <h3>자다가 자주 깨는 유형</h3>
    <p>잠은 들지만 깊게 이어지지 않고 자주 깨거나 새벽에 일찍 깨는 경우입니다.</p>
  </article>

  <article class="stress-card">
    <h3>두근거림·신체불편 동반형</h3>
    <p>스트레스 상황에서 두근거림, 가슴 답답함, 목 이물감이나 소화불편이 함께 반복되는 경우입니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section" id="treatment">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">CARE</span>
      <h2>현재 상태와 생활패턴에 따라 진료 방향을 상의합니다.</h2>
      <p>수면 문제의 기간과 정도, 동반 증상, 기존 진료와 복용약을 확인한 뒤 필요한 방향을 안내합니다.</p>
    </div>

<div class="treatment-grid">
  <article class="treatment-card">
    <h3>수면·생활 문진</h3>
    <p>취침·기상 시간과 수면시간, 카페인, 야간 생활, 스트레스 상황을 자세히 확인합니다.</p>
  </article>

  <article class="treatment-card">
    <h3>침 치료 상담</h3>
    <p>현재 수면과 긴장 상태, 동반되는 신체 불편에 따라 필요한 경우 침 치료를 진료 방법 가운데 하나로 고려할 수 있습니다.</p>
  </article>

  <article class="treatment-card">
    <h3>한약 상담</h3>
    <p>불면의 양상과 두근거림·소화·피로, 기존 복용약 등을 확인한 뒤 필요한 경우 한약을 상담합니다.</p>
  </article>

  <article class="treatment-card">
    <h3>수면·스트레스 관리</h3>
    <p>취침시간, 카페인, 낮잠, 야간 화면 노출 등 현재 생활에서 조절할 수 있는 부분을 함께 안내합니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section soft">
  <div class="container">
    <div class="safety-box">
      <h3>이런 경우에는 관련 의료기관 또는 응급 진료가 우선입니다.</h3>
      <ul>
        <li>갑작스럽고 심한 흉통이나 호흡곤란이 있는 경우</li>
        <li>두근거림과 함께 실신하거나 의식을 잃을 것 같은 증상이 있는 경우</li>
        <li>맥박이 매우 빠르거나 불규칙한 상태가 지속되는 경우</li>
        <li>극심한 불안이나 혼란으로 일상생활이 어렵거나 안전이 우려되는 경우</li>
        <li>수면 문제와 함께 심한 우울감이나 자해·자살 생각이 있는 경우</li>
      </ul>
    </div>
  </div>
</section>

<section class="clinic-section">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">HOME CARE</span>
      <h2>집에서는 잠과 증상의 패턴을 기록해 보세요.</h2>
    </div>

<div class="check-list">
  <div class="check-item">
    <strong>기상시간을 일정하게</strong>
    <p>잠을 설쳤더라도 기상시간이 계속 크게 달라지지 않도록 일정한 생활리듬을 유지하는 데 신경 써 보세요.</p>
  </div>

  <div class="check-item">
    <strong>늦은 카페인 줄이기</strong>
    <p>오후 늦게 마시는 커피, 차, 에너지음료가 잠드는 시간과 두근거림에 영향을 주는지 살펴보세요.</p>
  </div>

  <div class="check-item">
    <strong>잠이 안 올 때 시간 확인 반복 줄이기</strong>
    <p>몇 시인지 계속 확인하며 초조해지는 습관이 있다면 수면에 대한 긴장을 높일 수 있어 줄여보는 것이 좋습니다.</p>
  </div>

  <div class="check-item">
    <strong>두근거림이 생긴 상황 기록하기</strong>
    <p>발생 시간과 지속 시간, 운동·카페인·스트레스와의 관계를 기록해 두면 상담에 도움이 됩니다.</p>
  </div>
</div>

  </div>
</section>

<section class="clinic-section soft" id="faq">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">FAQ</span>
      <h2>수면·스트레스 관리 클리닉 자주 묻는 질문</h2>
    </div>

<div class="faq-list">
  <article class="faq-item">
    <h3>잠들기까지 한두 시간이 걸리는데 상담할 수 있나요?</h3>
    <p>네. 잠드는 데 걸리는 시간과 취침·기상 시간, 낮잠, 카페인, 스트레스 상태를 함께 확인합니다.</p>
  </article>

  <article class="faq-item">
    <h3>자다가 새벽에 자꾸 깨요.</h3>
    <p>밤중에 깨는 횟수와 시간, 다시 잠드는 데 걸리는 시간, 코골이·야간뇨·통증 등 잠을 깨우는 요인이 있는지 함께 살펴봅니다.</p>
  </article>

  <article class="faq-item">
    <h3>스트레스를 받으면 심장이 두근거리는데 괜찮을까요?</h3>
    <p>스트레스와 함께 두근거림이 나타날 수 있지만 심장질환, 갑상선, 빈혈 등 다른 원인도 있을 수 있습니다. 처음 생긴 증상이거나 심해지는 경우에는 관련 검사를 먼저 받는 것이 좋습니다.</p>
  </article>

  <article class="faq-item">
    <h3>가슴 답답함도 스트레스와 관련될 수 있나요?</h3>
    <p>긴장과 스트레스 상황에서 가슴 불편이 나타나는 경우가 있지만 원인을 스트레스로 단정해서는 안 됩니다. 흉통, 호흡곤란, 실신 등이 동반되면 의료기관 평가가 우선입니다.</p>
  </article>

  <article class="faq-item">
    <h3>수면제를 먹고 있어도 한의원에서 상담할 수 있나요?</h3>
    <p>가능합니다. 현재 복용 중인 약과 복용 기간을 알려주세요. 처방받은 수면제나 정신건강의학과 약은 임의로 줄이거나 중단하지 않는 것이 중요합니다.</p>
  </article>

  <article class="faq-item">
    <h3>목에 뭔가 걸린 느낌이 스트레스 받을 때 심해져요.</h3>
    <p>긴장이나 스트레스와 함께 목 이물감이 심해지는 경우가 있습니다. 다만 삼키기 어렵거나 통증, 체중 감소 등이 있다면 이비인후과나 관련 검사가 우선될 수 있습니다.</p>
  </article>

  <article class="faq-item">
    <h3>한약은 꼭 먹어야 하나요?</h3>
    <p>아닙니다. 현재 수면과 증상, 생활패턴, 기존 치료를 먼저 확인하고 필요한 경우에 한해 한약 상담을 진행합니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section" style="padding-top:0">
  <div class="container">
    <div class="clinic-cta">
      <div>
        <h2>잠이 언제부터 달라졌고, 어떤 상황에서 몸이 긴장하는지부터 살펴보겠습니다.</h2>
        <p>현재 복용약과 기존 검사 결과, 수면시간이나 두근거림을 기록한 내용이 있다면 내원 시 함께 알려주세요.</p>
      </div>
      <div class="actions">
        <a class="button" href="{{ site.data.clinic.phone_uri }}">전화 문의</a>
        <a class="button secondary" href="{{ '/clinic/' | relative_url }}">진료시간 보기</a>
        <a class="button secondary" href="{{ '/location/' | relative_url }}">오시는 길</a>
      </div>
    </div>
  </div>
</section>

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "잠들기까지 한두 시간이 걸리는데 상담할 수 있나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "잠드는 데 걸리는 시간과 취침·기상 시간, 낮잠, 카페인, 스트레스 상태를 함께 확인합니다."
      }
    },
    {
      "@type": "Question",
      "name": "자다가 새벽에 자꾸 깨요.",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "밤중에 깨는 횟수와 시간, 다시 잠드는 데 걸리는 시간, 코골이·야간뇨·통증 등 잠을 깨우는 요인이 있는지 함께 살펴봅니다."
      }
    },
    {
      "@type": "Question",
      "name": "스트레스를 받으면 심장이 두근거리는데 괜찮을까요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "스트레스와 함께 두근거림이 나타날 수 있지만 심장질환, 갑상선, 빈혈 등 다른 원인도 있을 수 있습니다. 처음 생긴 증상이거나 심해지는 경우에는 관련 검사를 먼저 받는 것이 좋습니다."
      }
    },
    {
      "@type": "Question",
      "name": "수면제를 먹고 있어도 한의원에서 상담할 수 있나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "현재 복용 중인 약과 복용 기간을 알려주세요. 처방받은 수면제나 정신건강의학과 약은 임의로 줄이거나 중단하지 않는 것이 중요합니다."
      }
    },
    {
      "@type": "Question",
      "name": "한약은 꼭 먹어야 하나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "현재 수면과 증상, 생활패턴, 기존 치료를 먼저 확인하고 필요한 경우에 한해 한약 상담을 진행합니다."
      }
    }
  ]
}
</script>
