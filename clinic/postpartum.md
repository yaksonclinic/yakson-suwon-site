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
    max-width:780px;
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
  .clinic-section{
    padding:72px 0;
  }
  .clinic-section.soft{
    background:#f7f6f1;
  }
  .clinic-heading{
    max-width:780px;
    margin-bottom:34px;
  }
  .clinic-heading h2{
    margin:8px 0 14px;
    font-size:clamp(1.8rem,3vw,2.8rem);
    line-height:1.2;
  }
  .clinic-heading p{
    line-height:1.8;
  }
  .postpartum-grid{
    display:grid;
    grid-template-columns:repeat(3,minmax(0,1fr));
    gap:18px;
  }
  .postpartum-card{
    padding:26px;
    border:1px solid rgba(0,0,0,.09);
    border-radius:18px;
    background:#fff;
  }
  .postpartum-card h3{
    margin:0 0 10px;
    font-size:1.14rem;
  }
  .postpartum-card p{
    margin:0;
    line-height:1.75;
  }
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
  .check-item p{
    margin:0;
    line-height:1.75;
  }
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
  .treatment-card h3{
    margin:0 0 10px;
  }
  .treatment-card p{
    margin:0;
    line-height:1.75;
  }
  .important-box{
    padding:30px;
    border-radius:18px;
    background:#eee8dc;
  }
  .important-box h3{
    margin-top:0;
    font-size:1.35rem;
  }
  .important-box p{
    margin-bottom:0;
    line-height:1.8;
  }
  .safety-box{
    padding:28px;
    border-radius:18px;
    background:#223a33;
    color:#fff;
  }
  .safety-box h3{
    margin-top:0;
  }
  .safety-box ul{
    margin:14px 0 0;
    padding-left:20px;
    line-height:1.9;
  }
  .faq-list{
    border-top:1px solid rgba(0,0,0,.12);
  }
  .faq-item{
    padding:24px 0;
    border-bottom:1px solid rgba(0,0,0,.12);
  }
  .faq-item h3{
    margin:0 0 10px;
    font-size:1.08rem;
  }
  .faq-item p{
    margin:0;
    line-height:1.8;
  }
  .clinic-cta{
    display:flex;
    justify-content:space-between;
    gap:28px;
    align-items:center;
    padding:34px;
    border-radius:20px;
    background:#eee8dc;
  }
  .clinic-cta h2{
    margin:0 0 8px;
  }
  .clinic-cta p{
    margin:0;
    line-height:1.7;
  }
  .clinic-cta .actions{
    display:flex;
    flex-wrap:wrap;
    gap:10px;
    flex-shrink:0;
  }
  @media (max-width:900px){
    .postpartum-grid{grid-template-columns:repeat(2,minmax(0,1fr));}
    .treatment-grid{grid-template-columns:repeat(2,minmax(0,1fr));}
    .clinic-cta{align-items:flex-start;flex-direction:column;}
  }
  @media (max-width:640px){
    .clinic-page-hero{padding:64px 0 48px;}
    .clinic-section{padding:56px 0;}
    .postpartum-grid,.check-list,.treatment-grid{grid-template-columns:1fr;}
  }
</style>

<section class="clinic-page-hero">
  <div class="container">
    <span class="clinic-kicker">POSTPARTUM CLINIC</span>
    <h1>산후 클리닉</h1>
    <p class="clinic-lead">
      출산 후에는 몸의 회복과 육아가 동시에 시작됩니다.
      <strong>피로, 허리·골반·손목·관절의 불편, 수면 부족과 컨디션 변화</strong>가
      함께 나타날 수 있어 출산 방식과 수유 여부, 현재 생활환경까지 함께 살펴봅니다.
    </p>
    <div class="clinic-nav" aria-label="산후 클리닉 페이지 바로가기">
      <a href="#symptoms">산후 불편</a>
      <a href="#check">진료 시 확인</a>
      <a href="#treatment">진료 방법</a>
      <a href="#faq">자주 묻는 질문</a>
    </div>
  </div>
</section>

<section class="clinic-section" id="symptoms">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">POSTPARTUM RECOVERY</span>
      <h2>출산 후 이런 불편으로 상담합니다.</h2>
      <p>한 가지 증상만 보기보다 출산 후 회복 상태와 수면, 수유, 육아 환경을 함께 확인합니다.</p>
    </div>

<div class="postpartum-grid">
  <article class="postpartum-card">
    <h3>산후 피로·체력 저하</h3>
    <p>출산 후 쉽게 지치고 기운이 없거나, 충분히 쉬어도 회복이 더디게 느껴지는 경우를 살펴봅니다.</p>
  </article>

  <article class="postpartum-card">
    <h3>허리·골반 불편</h3>
    <p>출산 후 허리나 골반 주변의 뻐근함, 움직일 때 불편한 느낌이 지속되는지 확인합니다.</p>
  </article>

  <article class="postpartum-card">
    <h3>손목·어깨·관절 통증</h3>
    <p>수유, 아기 안기, 반복되는 육아 자세 이후 손목과 어깨, 여러 관절이 아프거나 뻐근한 경우를 살펴봅니다.</p>
  </article>

  <article class="postpartum-card">
    <h3>수면 부족과 컨디션 변화</h3>
    <p>수유와 육아로 잠이 자주 끊기면서 피로, 두통, 집중력 저하 등 컨디션 변화가 함께 있는지 확인합니다.</p>
  </article>

  <article class="postpartum-card">
    <h3>식욕·소화의 변화</h3>
    <p>출산 후 식욕이 떨어지거나 더부룩함, 소화 불편 등이 반복되는 경우 현재 식사와 생활패턴을 함께 살펴봅니다.</p>
  </article>

  <article class="postpartum-card">
    <h3>산후 한약 상담</h3>
    <p>출산 방식과 회복 상태, 수유 여부, 현재 불편을 확인한 뒤 한약 상담이 필요한지 함께 상의합니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section soft" id="check">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">CONSULTATION CHECKPOINT</span>
      <h2>산후에는 현재 시기와 회복 흐름을 함께 확인합니다.</h2>
      <p>같은 산후 피로와 통증이라도 출산 후 얼마나 지났는지, 출산 방식과 수유 여부에 따라 확인할 내용이 달라질 수 있습니다.</p>
    </div>

<div class="check-list">
  <div class="check-item">
    <strong>출산 후 얼마나 지났는지</strong>
    <p>출산 직후인지, 몇 주 또는 몇 달이 지났는지와 그동안 몸 상태가 어떻게 변했는지 확인합니다.</p>
  </div>

  <div class="check-item">
    <strong>자연분만·제왕절개 여부</strong>
    <p>출산 방식과 출산 과정에서 특이사항이 있었는지, 수술 후 회복 상태는 어떤지 살펴봅니다.</p>
  </div>

  <div class="check-item">
    <strong>수유 여부</strong>
    <p>모유수유·혼합수유·분유수유 여부를 확인하고 한약이나 진료 상담 시 함께 고려합니다.</p>
  </div>

  <div class="check-item">
    <strong>출혈과 산후 회복 상태</strong>
    <p>산후 출혈의 변화와 복통, 발열 등 평소와 다른 증상이 있는지 확인합니다.</p>
  </div>

  <div class="check-item">
    <strong>수면·식사·육아 환경</strong>
    <p>밤중 수유로 인한 수면 부족, 식사 패턴, 아기를 안는 자세처럼 회복에 영향을 줄 수 있는 생활환경을 살펴봅니다.</p>
  </div>

  <div class="check-item">
    <strong>기존 산부인과 진료와 복용약</strong>
    <p>산부인과 검사 결과와 현재 복용 중인 약, 영양제 등이 있다면 함께 확인합니다.</p>
  </div>
</div>

  </div>
</section>

<section class="clinic-section">
  <div class="container">
    <div class="important-box">
      <h3>산후 회복은 “얼마나 빨리 예전으로 돌아가느냐”보다 현재 몸 상태를 살피는 과정이 중요합니다.</h3>
      <p>
        출산 후에는 수면이 부족하고 육아로 활동량이 늘어 충분히 쉬기 어려운 경우가 많습니다.
        따라서 피로와 통증을 단순히 참기보다 어떤 상황에서 심해지는지,
        현재 회복을 방해하는 요소는 무엇인지 함께 살펴보는 것이 좋습니다.
      </p>
    </div>
  </div>
</section>

<section class="clinic-section soft">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">PATTERN & APPROACH</span>
      <h2>산후 불편은 이런 흐름으로 나눠 살펴볼 수 있습니다.</h2>
    </div>

<div class="postpartum-grid">
  <article class="postpartum-card">
    <h3>피로·회복 저하형</h3>
    <p>출산 후 쉽게 지치고 기운이 없으며 수면 부족과 식사 불규칙이 함께 있는 경우입니다.</p>
  </article>

  <article class="postpartum-card">
    <h3>근골격계 통증형</h3>
    <p>허리·골반·손목·어깨처럼 출산과 육아 과정에서 자주 사용하는 부위의 통증이 중심인 경우입니다.</p>
  </article>

  <article class="postpartum-card">
    <h3>수면·컨디션 변화형</h3>
    <p>잠이 자주 끊기고 쉽게 피곤해지며 두통이나 전반적인 컨디션 저하가 함께 있는 경우입니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section" id="treatment">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">CARE</span>
      <h2>현재 회복 상태에 따라 진료 방법을 상의합니다.</h2>
      <p>출산 후 시기와 수유 여부, 현재 증상을 확인한 뒤 필요한 진료 방법을 선택합니다.</p>
    </div>

<div class="treatment-grid">
  <article class="treatment-card">
    <h3>상태 확인</h3>
    <p>출산 후 경과, 수유 여부, 수면과 식사, 통증 부위 등 현재 회복 상태를 먼저 확인합니다.</p>
  </article>

  <article class="treatment-card">
    <h3>침 치료</h3>
    <p>허리·골반·손목·어깨 등 근골격계 불편이 있는 경우 현재 상태를 살펴 침 치료를 고려할 수 있습니다.</p>
  </article>

  <article class="treatment-card">
    <h3>한약 상담</h3>
    <p>피로와 회복 상태, 소화, 수유 여부 등을 확인한 뒤 필요한 경우 한약 복용을 상담합니다.</p>
  </article>

  <article class="treatment-card">
    <h3>생활관리 안내</h3>
    <p>수면과 휴식, 아기를 안는 자세, 반복되는 손목 사용 등 일상에서 조절할 부분을 함께 안내합니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section soft">
  <div class="container">
    <div class="safety-box">
      <h3>이런 경우에는 산부인과 또는 응급평가가 우선입니다.</h3>
      <ul>
        <li>출혈량이 갑자기 많아지거나 큰 혈괴가 반복되는 경우</li>
        <li>고열과 함께 심한 하복부 통증이 있는 경우</li>
        <li>심한 어지럼이나 실신, 호흡곤란 또는 흉통이 있는 경우</li>
        <li>제왕절개나 회음부 상처 부위에 심한 통증·붓기·분비물이 있는 경우</li>
        <li>기분 저하나 불안이 매우 심하거나 본인 또는 아기의 안전이 걱정되는 경우</li>
      </ul>
    </div>
  </div>
</section>

<section class="clinic-section">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">HOME CARE</span>
      <h2>집에서는 회복할 시간을 확보해 주세요.</h2>
    </div>

<div class="check-list">
  <div class="check-item">
    <strong>가능한 범위에서 자주 쉬기</strong>
    <p>긴 시간을 한 번에 쉬기 어렵다면 짧게라도 자주 누워 쉬고, 무리한 집안일은 가능한 범위에서 줄여주세요.</p>
  </div>

  <div class="check-item">
    <strong>아기를 안는 자세 바꾸기</strong>
    <p>한쪽 손목과 어깨만 반복적으로 사용하지 않도록 수유 자세와 아기를 안는 자세를 점검해 보세요.</p>
  </div>

  <div class="check-item">
    <strong>출혈·통증·체온 변화 살피기</strong>
    <p>평소와 다른 출혈이나 통증, 발열이 있다면 기록하고 필요한 경우 산부인과에 확인하는 것이 좋습니다.</p>
  </div>

  <div class="check-item">
    <strong>복용 중인 약과 수유 여부 알리기</strong>
    <p>한약이나 다른 치료를 상담할 때 현재 복용약과 영양제, 수유 여부를 꼭 알려주세요.</p>
  </div>
</div>

  </div>
</section>

<section class="clinic-section soft" id="faq">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">FAQ</span>
      <h2>산후 클리닉 자주 묻는 질문</h2>
    </div>

<div class="faq-list">
  <article class="faq-item">
    <h3>산후 보약은 언제부터 상담할 수 있나요?</h3>
    <p>출산 방식과 현재 회복 상태, 출혈 양상, 수유 여부 등을 확인한 뒤 상담합니다. 모든 산모에게 같은 시기와 처방이 적용되는 것은 아닙니다.</p>
  </article>

  <article class="faq-item">
    <h3>모유수유 중에도 한약 상담이 가능한가요?</h3>
    <p>가능합니다. 다만 수유 여부와 아기의 상태, 현재 복용 중인 약이나 영양제를 반드시 알려주시고 진료 후 복용 여부를 결정하는 것이 좋습니다.</p>
  </article>

  <article class="faq-item">
    <h3>출산 후 손목과 허리가 계속 아파요.</h3>
    <p>수유와 아기 돌봄 과정에서 같은 자세와 동작이 반복되면서 손목·어깨·허리의 불편이 나타날 수 있습니다. 통증 부위와 움직임, 육아 자세를 함께 확인합니다.</p>
  </article>

  <article class="faq-item">
    <h3>제왕절개 후에도 상담할 수 있나요?</h3>
    <p>현재 수술 부위의 회복 상태와 산부인과 진료 내용을 먼저 확인한 뒤 상담할 수 있습니다. 상처 부위의 심한 통증이나 발열, 분비물이 있다면 산부인과 평가가 우선입니다.</p>
  </article>

  <article class="faq-item">
    <h3>산후에 너무 피곤한 것도 상담 대상인가요?</h3>
    <p>네. 수면, 식사, 수유, 출혈, 통증 등 현재 회복에 영향을 줄 수 있는 요소를 함께 확인합니다. 피로가 매우 심하거나 어지럼 등이 동반된다면 필요한 검사 여부도 확인하는 것이 좋습니다.</p>
  </article>

  <article class="faq-item">
    <h3>산후에는 운동을 언제부터 시작해야 하나요?</h3>
    <p>출산 방식과 회복 상태에 따라 다릅니다. 무리해서 시작하기보다 산부인과의 회복 확인과 현재 통증 상태를 고려해 활동량을 서서히 늘리는 것이 좋습니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section" style="padding-top:0">
  <div class="container">
    <div class="clinic-cta">
      <div>
        <h2>출산 후 지금 가장 힘든 부분부터 살펴보겠습니다.</h2>
        <p>출산 방식과 수유 여부, 산부인과 진료 내용과 복용 중인 약이 있다면 함께 알려주세요.</p>
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
      "name": "산후 보약은 언제부터 상담할 수 있나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "출산 방식과 현재 회복 상태, 출혈 양상, 수유 여부 등을 확인한 뒤 상담합니다. 모든 산모에게 같은 시기와 처방이 적용되는 것은 아닙니다."
      }
    },
    {
      "@type": "Question",
      "name": "모유수유 중에도 한약 상담이 가능한가요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "가능합니다. 다만 수유 여부와 아기의 상태, 현재 복용 중인 약이나 영양제를 반드시 알려주시고 진료 후 복용 여부를 결정하는 것이 좋습니다."
      }
    },
    {
      "@type": "Question",
      "name": "출산 후 손목과 허리가 계속 아파요.",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "수유와 아기 돌봄 과정에서 같은 자세와 동작이 반복되면서 손목·어깨·허리의 불편이 나타날 수 있습니다. 통증 부위와 움직임, 육아 자세를 함께 확인합니다."
      }
    },
    {
      "@type": "Question",
      "name": "제왕절개 후에도 상담할 수 있나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "현재 수술 부위의 회복 상태와 산부인과 진료 내용을 먼저 확인한 뒤 상담할 수 있습니다. 상처 부위의 심한 통증이나 발열, 분비물이 있다면 산부인과 평가가 우선입니다."
      }
    },
    {
      "@type": "Question",
      "name": "산후에 너무 피곤한 것도 상담 대상인가요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "수면, 식사, 수유, 출혈, 통증 등 현재 회복에 영향을 줄 수 있는 요소를 함께 확인합니다. 피로가 매우 심하거나 어지럼 등이 동반된다면 필요한 검사 여부도 확인하는 것이 좋습니다."
      }
    }
  ]
}
</script>
