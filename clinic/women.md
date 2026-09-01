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
  .women-grid{
    display:grid;
    grid-template-columns:repeat(3,minmax(0,1fr));
    gap:18px;
  }
  .women-card{
    padding:26px;
    border:1px solid rgba(0,0,0,.09);
    border-radius:18px;
    background:#fff;
  }
  .women-card h3{
    margin:0 0 10px;
    font-size:1.14rem;
  }
  .women-card p{
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
  .related-box{
    display:flex;
    justify-content:space-between;
    gap:24px;
    align-items:center;
    padding:28px;
    border:1px solid rgba(0,0,0,.09);
    border-radius:18px;
    background:#fff;
  }
  .related-box h3{
    margin:0 0 8px;
  }
  .related-box p{
    margin:0;
    line-height:1.7;
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
    .women-grid{grid-template-columns:repeat(2,minmax(0,1fr));}
    .treatment-grid{grid-template-columns:repeat(2,minmax(0,1fr));}
    .clinic-cta,.related-box{align-items:flex-start;flex-direction:column;}
  }
  @media (max-width:640px){
    .clinic-page-hero{padding:64px 0 48px;}
    .clinic-section{padding:56px 0;}
    .women-grid,.check-list,.treatment-grid{grid-template-columns:1fr;}
  }
</style>

<section class="clinic-page-hero">
  <div class="container">
    <span class="clinic-kicker">WOMEN'S CLINIC</span>
    <h1>여성 클리닉</h1>
    <p class="clinic-lead">
      여성의 몸은 생리 주기, 임신 준비, 출산 이후, 갱년기처럼
      <strong>생애주기에 따라 몸의 변화와 불편의 양상이 달라질 수 있습니다.</strong>
      현재 가장 불편한 증상과 함께 수면, 피로, 식사, 기존 산부인과 진료와 복용약을 함께 확인합니다.
    </p>
    <div class="clinic-nav" aria-label="여성 클리닉 페이지 바로가기">
      <a href="#symptoms">주요 고민</a>
      <a href="#check">진료 시 확인</a>
      <a href="#treatment">진료 방법</a>
      <a href="#faq">자주 묻는 질문</a>
    </div>
  </div>
</section>

<section class="clinic-section" id="symptoms">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">WOMEN'S HEALTH</span>
      <h2>이런 여성 건강 고민으로 상담합니다.</h2>
      <p>증상 하나만 보기보다 현재 어느 시기에 있는지와 반복되는 생활 불편을 함께 살펴봅니다.</p>
    </div>

<div class="women-grid">
  <article class="women-card">
    <h3>생리통</h3>
    <p>생리 전후 복통이나 허리통증이 반복되거나 일상생활에 불편을 주는 경우 통증 시점과 양상을 확인합니다.</p>
  </article>

  <article class="women-card">
    <h3>생리주기 변화</h3>
    <p>평소와 달리 주기가 불규칙해졌거나 주기와 함께 컨디션 변화가 반복되는 경우 현재 상태를 살펴봅니다.</p>
  </article>

  <article class="women-card">
    <h3>생리 전 컨디션 변화</h3>
    <p>생리 전 피로, 부종감, 두통, 예민함 등 반복되는 불편이 있는지 수면과 스트레스 상태와 함께 확인합니다.</p>
  </article>

  <article class="women-card">
    <h3>임신 준비 중 컨디션 관리</h3>
    <p>임신을 준비하면서 피로, 수면, 소화 등 전반적인 컨디션 관리가 필요한 경우 기존 산부인과 진료와 함께 살펴봅니다.</p>
  </article>

  <article class="women-card">
    <h3>갱년기 전후 불편</h3>
    <p>열감, 식은땀, 수면 불편, 피로 등 갱년기 전후에 나타나는 생활 불편을 현재 변화와 함께 확인합니다.</p>
  </article>

  <article class="women-card">
    <h3>여성 건강 한약 상담</h3>
    <p>현재 시기와 증상, 기존 진료와 복용약을 확인한 뒤 필요한 경우 한약 상담을 진행합니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section soft" id="check">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">CONSULTATION CHECKPOINT</span>
      <h2>여성 클리닉에서는 이런 내용을 함께 확인합니다.</h2>
      <p>현재 시기와 증상 변화, 기존 산부인과 진료 내용을 함께 보는 것이 중요합니다.</p>
    </div>

<div class="check-list">
  <div class="check-item">
    <strong>생리통의 시점과 출혈량 변화</strong>
    <p>통증이 생리 전·초기·후반 중 언제 심한지, 평소와 달라진 출혈 양상이 있는지 확인합니다.</p>
  </div>

  <div class="check-item">
    <strong>생리주기의 변화</strong>
    <p>평소 주기와 최근 주기가 어떻게 달라졌는지, 변화가 언제부터 시작됐는지 살펴봅니다.</p>
  </div>

  <div class="check-item">
    <strong>수면·피로·소화 상태</strong>
    <p>잠드는 시간과 수면의 질, 피로도, 식욕과 소화 상태 등 전반적인 컨디션을 함께 확인합니다.</p>
  </div>

  <div class="check-item">
    <strong>임신·출산·수유 여부</strong>
    <p>임신 가능성이나 임신 준비 여부, 최근 출산과 수유 여부가 있다면 진료 시 꼭 확인합니다.</p>
  </div>

  <div class="check-item">
    <strong>열감·식은땀·기분 변화</strong>
    <p>갱년기 전후라면 열감과 식은땀, 수면 불편, 기분 변화가 어느 정도인지 살펴봅니다.</p>
  </div>

  <div class="check-item">
    <strong>산부인과 검사와 복용약</strong>
    <p>최근 검사 결과와 현재 복용 중인 약, 건강기능식품이 있다면 함께 확인합니다.</p>
  </div>
</div>

  </div>
</section>

<section class="clinic-section">
  <div class="container">
    <div class="important-box">
      <h3>여성 건강은 “증상 하나”보다 “현재 시기와 변화의 흐름”을 함께 보는 것이 중요합니다.</h3>
      <p>
        같은 복통이나 피로라도 생리 전후인지, 임신을 준비하는 시기인지,
        갱년기 전후인지에 따라 확인해야 할 부분이 달라질 수 있습니다.
        현재 가장 힘든 증상과 언제부터 어떻게 달라졌는지를 구체적으로 살펴봅니다.
      </p>
    </div>
  </div>
</section>

<section class="clinic-section soft">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">PATTERN & APPROACH</span>
      <h2>대표적으로 이런 흐름으로 나눠 살펴볼 수 있습니다.</h2>
    </div>

<div class="women-grid">
  <article class="women-card">
    <h3>생리 관련 고민</h3>
    <p>생리통, 주기 변화, 생리 전후의 컨디션 저하가 반복되는 경우입니다.</p>
  </article>

  <article class="women-card">
    <h3>임신 준비 중 컨디션 고민</h3>
    <p>기존 산부인과 진료를 확인하면서 수면, 피로, 소화 등 전반적인 생활 컨디션을 함께 살펴보는 경우입니다.</p>
  </article>

  <article class="women-card">
    <h3>갱년기 전후 고민</h3>
    <p>열감, 식은땀, 수면 불편, 피로 등 여러 변화가 함께 이어지는 경우입니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section" id="treatment">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">CARE</span>
      <h2>현재 상태에 따라 진료 방법을 함께 상의합니다.</h2>
      <p>모든 분에게 같은 진료를 일률적으로 적용하지 않고 현재 시기와 증상, 기존 치료 내용을 확인한 뒤 필요한 방향을 설명합니다.</p>
    </div>

<div class="treatment-grid">
  <article class="treatment-card">
    <h3>현재 시기 확인</h3>
    <p>생리주기, 임신 준비 여부, 출산·수유 여부, 갱년기 전후인지 등을 먼저 확인합니다.</p>
  </article>

  <article class="treatment-card">
    <h3>침 치료 상담</h3>
    <p>현재 증상과 몸 상태에 따라 필요한 경우 침 치료를 진료 방법 가운데 하나로 고려할 수 있습니다.</p>
  </article>

  <article class="treatment-card">
    <h3>한약 상담</h3>
    <p>현재 증상과 복용약, 임신·수유 여부 등을 확인한 뒤 필요한 경우 한약 복용을 상담합니다.</p>
  </article>

  <article class="treatment-card">
    <h3>생활관리 안내</h3>
    <p>수면, 식사, 과로, 운동, 증상 기록 등 현재 상태를 이해하는 데 도움이 되는 생활관리 방법을 안내합니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section soft">
  <div class="container">
    <div class="safety-box">
      <h3>이런 경우에는 산부인과 또는 필요한 의료기관의 평가가 우선입니다.</h3>
      <ul>
        <li>임신 중 출혈이나 심한 복통이 있는 경우</li>
        <li>평소와 다르게 출혈량이 매우 많거나 출혈이 지속되는 경우</li>
        <li>고열과 심한 하복부 통증이 함께 있는 경우</li>
        <li>갑작스러운 심한 어지럼이나 실신이 있는 경우</li>
        <li>기분 저하나 불안이 매우 심하거나 본인의 안전이 걱정되는 경우</li>
      </ul>
    </div>
  </div>
</section>

<section class="clinic-section">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">HOME CARE</span>
      <h2>평소에는 몸의 변화를 간단히 기록해 보세요.</h2>
    </div>

<div class="check-list">
  <div class="check-item">
    <strong>생리주기와 통증 기록하기</strong>
    <p>생리 시작일과 기간, 통증이 심한 시점, 출혈량 변화를 간단히 기록하면 상담에 도움이 됩니다.</p>
  </div>

  <div class="check-item">
    <strong>수면과 컨디션 함께 보기</strong>
    <p>잠을 얼마나 잤는지뿐 아니라 자고 일어난 뒤 피로감과 낮 시간의 컨디션도 함께 살펴보세요.</p>
  </div>

  <div class="check-item">
    <strong>무리한 활동 줄이기</strong>
    <p>컨디션이 크게 떨어지는 시기에는 과도한 운동이나 무리한 일정을 줄이고 충분한 휴식을 확보하는 것이 좋습니다.</p>
  </div>

  <div class="check-item">
    <strong>기존 검사결과 챙기기</strong>
    <p>산부인과 검사 결과와 현재 복용약을 준비하면 현재 상태를 이해하는 데 도움이 됩니다.</p>
  </div>
</div>

  </div>
</section>

<section class="clinic-section soft">
  <div class="container">
    <div class="related-box">
      <div>
        <h3>출산 후 회복이 주된 고민인가요?</h3>
        <p>출산 후 피로, 허리·골반·손목 불편과 수유 중 컨디션은 산후 클리닉에서 조금 더 자세히 안내합니다.</p>
      </div>
      <a class="button secondary" href="{{ '/clinic/postpartum/' | relative_url }}">산후 클리닉 보기</a>
    </div>
  </div>
</section>

<section class="clinic-section" id="faq">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">FAQ</span>
      <h2>여성 클리닉 자주 묻는 질문</h2>
    </div>

<div class="faq-list">
  <article class="faq-item">
    <h3>생리통도 한의원에서 상담할 수 있나요?</h3>
    <p>네. 통증이 언제 시작되는지, 생리주기와 출혈량에 변화가 있는지 등을 함께 확인합니다.</p>
  </article>

  <article class="faq-item">
    <h3>생리주기가 불규칙해졌는데 상담해도 되나요?</h3>
    <p>최근 주기의 변화와 체중, 스트레스, 수면 상태 등을 함께 살펴볼 수 있습니다. 갑작스러운 변화가 크거나 임신 가능성이 있다면 필요한 산부인과 평가도 함께 고려합니다.</p>
  </article>

  <article class="faq-item">
    <h3>임신 준비 중에도 진료받을 수 있나요?</h3>
    <p>현재 받고 있는 산부인과 진료와 복용약, 건강기능식품을 확인한 뒤 상담합니다.</p>
  </article>

  <article class="faq-item">
    <h3>갱년기 열감과 수면 불편도 함께 볼 수 있나요?</h3>
    <p>네. 열감과 식은땀의 양상, 수면과 피로 상태, 생리주기의 변화 등을 함께 확인합니다.</p>
  </article>

  <article class="faq-item">
    <h3>산부인과 약을 먹고 있어도 상담 가능한가요?</h3>
    <p>가능합니다. 현재 복용 중인 약을 반드시 알려주시고, 처방받은 약은 임의로 중단하지 않는 것이 중요합니다.</p>
  </article>

  <article class="faq-item">
    <h3>여성 클리닉에서는 한약만 하나요?</h3>
    <p>아닙니다. 현재 상태를 먼저 확인하고 생활관리와 필요한 진료 방법을 함께 설명합니다. 한약은 필요에 따라 상담합니다.</p>
  </article>

  <article class="faq-item">
    <h3>출산 후 피로와 손목 통증은 여성 클리닉에서 보나요?</h3>
    <p>상담할 수 있습니다. 약손한의원 홈페이지에서는 출산 후 회복과 육아로 인한 근골격계 불편을 산후 클리닉에서 더 자세히 안내하고 있습니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section" style="padding-top:0">
  <div class="container">
    <div class="clinic-cta">
      <div>
        <h2>현재 어느 시기에 있고 무엇이 가장 불편한지부터 살펴보겠습니다.</h2>
        <p>최근 생리주기와 산부인과 검사 결과, 복용 중인 약이 있다면 내원 시 함께 알려주세요.</p>
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
      "name": "생리통도 한의원에서 상담할 수 있나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "통증이 언제 시작되는지, 생리주기와 출혈량에 변화가 있는지 등을 함께 확인합니다."
      }
    },
    {
      "@type": "Question",
      "name": "생리주기가 불규칙해졌는데 상담해도 되나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "최근 주기의 변화와 체중, 스트레스, 수면 상태 등을 함께 살펴볼 수 있습니다. 갑작스러운 변화가 크거나 임신 가능성이 있다면 필요한 산부인과 평가도 함께 고려합니다."
      }
    },
    {
      "@type": "Question",
      "name": "임신 준비 중에도 진료받을 수 있나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "현재 받고 있는 산부인과 진료와 복용약, 건강기능식품을 확인한 뒤 상담합니다."
      }
    },
    {
      "@type": "Question",
      "name": "갱년기 열감과 수면 불편도 함께 볼 수 있나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "열감과 식은땀의 양상, 수면과 피로 상태, 생리주기의 변화 등을 함께 확인합니다."
      }
    },
    {
      "@type": "Question",
      "name": "산부인과 약을 먹고 있어도 상담 가능한가요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "가능합니다. 현재 복용 중인 약을 반드시 알려주시고, 처방받은 약은 임의로 중단하지 않는 것이 중요합니다."
      }
    }
  ]
}
</script
