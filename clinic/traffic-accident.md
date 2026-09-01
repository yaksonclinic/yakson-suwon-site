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
  .traffic-grid{
    display:grid;
    grid-template-columns:repeat(3,minmax(0,1fr));
    gap:18px;
  }
  .traffic-card{
    padding:26px;
    border:1px solid rgba(0,0,0,.09);
    border-radius:18px;
    background:#fff;
  }
  .traffic-card h3{
    margin:0 0 10px;
    font-size:1.14rem;
  }
  .traffic-card p{
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
    .traffic-grid{grid-template-columns:repeat(2,minmax(0,1fr));}
    .treatment-grid{grid-template-columns:repeat(2,minmax(0,1fr));}
    .clinic-cta{align-items:flex-start;flex-direction:column;}
  }
  @media (max-width:640px){
    .clinic-page-hero{padding:64px 0 48px;}
    .clinic-section{padding:56px 0;}
    .traffic-grid,.check-list,.treatment-grid{grid-template-columns:1fr;}
  }
</style>

<section class="clinic-page-hero">
  <div class="container">
    <span class="clinic-kicker">TRAFFIC ACCIDENT CLINIC</span>
    <h1>교통사고 클리닉</h1>
    <p class="clinic-lead">
      교통사고 직후에는 긴장 때문에 괜찮게 느껴지다가
      <strong>시간이 지나면서 목·허리 통증, 어깨 뻐근함, 두통이나 어지럼, 피로와 수면 변화</strong>가
      두드러지는 경우가 있습니다. 사고 당시 상황과 사고 전후 몸의 변화를 함께 확인합니다.
    </p>
    <div class="clinic-nav" aria-label="교통사고 클리닉 페이지 바로가기">
      <a href="#symptoms">사고 후 증상</a>
      <a href="#check">진료 시 확인</a>
      <a href="#treatment">진료 방법</a>
      <a href="#faq">자주 묻는 질문</a>
    </div>
  </div>
</section>

<section class="clinic-section" id="symptoms">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">AFTER ACCIDENT</span>
      <h2>교통사고 후 이런 불편이 있나요?</h2>
      <p>통증뿐 아니라 사고 이전에는 없었던 몸의 변화가 생겼는지도 함께 살펴보는 것이 중요합니다.</p>
    </div>

<div class="traffic-grid">
  <article class="traffic-card">
    <h3>목·허리 통증</h3>
    <p>사고 이후 목이나 허리가 뻣뻣하고 움직일 때 아프거나, 앉아 있을 때 통증이 심해지는 경우를 살펴봅니다.</p>
  </article>

  <article class="traffic-card">
    <h3>어깨·등의 긴장</h3>
    <p>충돌 이후 어깨와 등에 힘이 들어간 느낌이 지속되거나 근육이 뭉치고 뻐근한 경우를 확인합니다.</p>
  </article>

  <article class="traffic-card">
    <h3>두통·어지럼</h3>
    <p>사고 이후 두통이나 어지럼, 멍한 느낌이 새롭게 생겼거나 이전보다 심해졌는지 확인합니다.</p>
  </article>

  <article class="traffic-card">
    <h3>며칠 뒤 심해진 통증</h3>
    <p>사고 당일에는 괜찮았지만 다음 날이나 며칠 뒤 통증과 뻐근함이 두드러지는 경우도 있습니다.</p>
  </article>

  <article class="traffic-card">
    <h3>검사 후에도 남은 불편</h3>
    <p>검사에서 큰 이상이 확인되지 않았더라도 움직임의 불편이나 통증이 이어진다면 현재 증상을 다시 살펴볼 수 있습니다.</p>
  </article>

  <article class="traffic-card">
    <h3>피로·수면 변화</h3>
    <p>사고 이후 쉽게 피곤하거나 잠들기 어렵고 자주 깨는 등 평소와 다른 컨디션 변화가 있는지 확인합니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section soft" id="check">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">CONSULTATION CHECKPOINT</span>
      <h2>사고 당시 상황과 이후의 변화를 함께 확인합니다.</h2>
      <p>교통사고는 충돌 방향과 당시 자세, 기존 증상 여부에 따라 불편의 양상이 다르게 나타날 수 있습니다.</p>
    </div>

<div class="check-list">
  <div class="check-item">
    <strong>충돌 방향과 사고 당시 자세</strong>
    <p>앞·뒤·옆 어느 방향에서 충격이 있었는지, 사고 당시 몸과 목의 자세는 어땠는지 확인합니다.</p>
  </div>

  <div class="check-item">
    <strong>안전벨트와 충격 부위</strong>
    <p>안전벨트 착용 여부와 머리, 어깨, 무릎 등 직접 부딪힌 부위가 있었는지 살펴봅니다.</p>
  </div>

  <div class="check-item">
    <strong>사고 전후 통증의 차이</strong>
    <p>사고 이전에도 있던 통증인지, 사고 이후 새롭게 시작됐거나 뚜렷하게 심해졌는지를 확인합니다.</p>
  </div>

  <div class="check-item">
    <strong>동반되는 증상</strong>
    <p>두통, 어지럼, 메스꺼움, 수면 변화, 피로, 저림처럼 통증 이외의 변화가 있는지도 함께 확인합니다.</p>
  </div>

  <div class="check-item">
    <strong>기존 검사와 치료</strong>
    <p>응급실·정형외과 등에서 시행한 X-ray, CT, MRI 결과와 처방받은 약, 치료 내용을 참고합니다.</p>
  </div>

  <div class="check-item">
    <strong>자동차보험 접수 상황</strong>
    <p>자동차보험으로 진료를 원하시는 경우 사고 접수 여부와 접수번호 등 필요한 정보를 확인해 안내드립니다.</p>
  </div>
</div>

  </div>
</section>

<section class="clinic-section">
  <div class="container">
    <div class="important-box">
      <h3>검사에서 “큰 이상이 없다”는 말을 들었는데도 계속 불편할 수 있나요?</h3>
      <p>
        영상검사에서 응급한 이상이 확인되지 않았더라도 목·허리의 뻐근함,
        움직임 제한, 두통이나 수면 변화처럼 일상생활을 불편하게 만드는 증상이 이어질 수 있습니다.
        기존 검사 결과와 현재 느끼는 증상을 함께 확인하는 것이 중요합니다.
      </p>
    </div>
  </div>
</section>

<section class="clinic-section soft">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">PATTERN & APPROACH</span>
      <h2>사고 이후 나타나는 불편의 양상을 살펴봅니다.</h2>
    </div>

<div class="traffic-grid">
  <article class="traffic-card">
    <h3>근골격계 통증형</h3>
    <p>목·허리·어깨의 통증과 뻣뻣함, 움직임 제한이 중심으로 나타나는 경우입니다.</p>
  </article>

  <article class="traffic-card">
    <h3>두통·어지럼 동반형</h3>
    <p>사고 이후 목 주변의 불편과 함께 두통이나 어지럼, 멍한 느낌 등이 동반되는 경우를 살펴봅니다.</p>
  </article>

  <article class="traffic-card">
    <h3>수면·피로 변화형</h3>
    <p>사고 이후 잠이 잘 오지 않거나 자주 깨고, 평소보다 쉽게 지치는 등 컨디션 변화가 이어지는 경우입니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section" id="treatment">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">CARE</span>
      <h2>현재 상태에 따라 진료 방법을 고려합니다.</h2>
      <p>모든 치료를 일률적으로 적용하지 않고 사고 후 증상과 현재 몸 상태를 확인해 필요한 진료 방향을 안내합니다.</p>
    </div>

<div class="treatment-grid">
  <article class="treatment-card">
    <h3>침 치료</h3>
    <p>목·허리·어깨 등 불편한 부위와 주변 근육의 긴장, 움직임 상태를 살펴 침 치료를 진행할 수 있습니다.</p>
  </article>

  <article class="treatment-card">
    <h3>부항 치료</h3>
    <p>근육의 긴장이나 뻐근함이 있는 부위를 확인한 뒤 상태에 따라 부항 치료를 함께 고려할 수 있습니다.</p>
  </article>

  <article class="treatment-card">
    <h3>약침 상담</h3>
    <p>현재 증상과 상태에 따라 필요한 경우 약침을 치료 방법 가운데 하나로 설명드릴 수 있습니다.</p>
  </article>

  <article class="treatment-card">
    <h3>경과 확인</h3>
    <p>사고 직후와 며칠 뒤의 증상이 달라질 수 있으므로 통증과 생활 불편의 변화 양상을 계속 확인합니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section soft">
  <div class="container">
    <div class="safety-box">
      <h3>이런 경우에는 응급평가나 병원 검사가 우선입니다.</h3>
      <ul>
        <li>의식이 흐려지거나 심한 두통과 반복되는 구토가 있는 경우</li>
        <li>골절이 의심될 정도의 심한 외상이나 변형이 있는 경우</li>
        <li>걷기 어렵거나 팔·다리에 갑자기 심한 힘 빠짐이 있는 경우</li>
        <li>감각 저하나 마비 등 신경학적 증상이 점점 심해지는 경우</li>
        <li>흉통, 호흡곤란 등 응급 증상이 있는 경우</li>
      </ul>
    </div>
  </div>
</section>

<section class="clinic-section">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">HOME CARE</span>
      <h2>사고 후 일상에서는 이렇게 살펴보세요.</h2>
    </div>

<div class="check-list">
  <div class="check-item">
    <strong>초기에 무리한 운동은 미루기</strong>
    <p>사고 직후에는 몸의 반응을 살펴보며 활동량을 조절하고, 통증을 참고 무리하게 운동하지 않는 것이 좋습니다.</p>
  </div>

  <div class="check-item">
    <strong>증상 변화를 기록하기</strong>
    <p>통증이 언제 심해지는지, 두통이나 어지럼은 어떤지, 수면 상태는 달라졌는지 기록하면 경과 확인에 도움이 됩니다.</p>
  </div>

  <div class="check-item">
    <strong>강한 자극을 반복하지 않기</strong>
    <p>통증이 심한 초기에는 강한 마사지나 과도한 스트레칭을 스스로 반복하기보다 현재 상태를 먼저 확인하는 것이 좋습니다.</p>
  </div>

  <div class="check-item">
    <strong>기존 검사자료 보관하기</strong>
    <p>응급실이나 다른 의료기관 방문 기록, 검사자료, 처방 내역이 있다면 진료 시 함께 알려주세요.</p>
  </div>
</div>

  </div>
</section>

<section class="clinic-section soft" id="faq">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">FAQ</span>
      <h2>교통사고 클리닉 자주 묻는 질문</h2>
    </div>

<div class="faq-list">
  <article class="faq-item">
    <h3>자동차보험으로 진료가 가능한가요?</h3>
    <p>사고 접수 여부와 보험 적용 상황을 확인한 뒤 안내드립니다. 방문 전에 보험사에서 받은 사고 접수번호가 있다면 준비해 주세요.</p>
  </article>

  <article class="faq-item">
    <h3>사고 당일 바로 진료받아도 되나요?</h3>
    <p>현재 상태를 확인해 진료할 수 있습니다. 다만 심한 두통·구토, 의식 변화, 심한 외상 등 응급평가가 필요한 증상이 있다면 응급실이나 관련 검사를 먼저 받는 것이 중요합니다.</p>
  </article>

  <article class="faq-item">
    <h3>사고 후 며칠 지나서 아프기 시작했는데 관련이 있을 수 있나요?</h3>
    <p>사고 직후보다 시간이 지난 뒤 통증이나 뻐근함이 두드러지는 경우가 있습니다. 사고 전후의 증상 변화를 함께 확인합니다.</p>
  </article>

  <article class="faq-item">
    <h3>다른 병원에서 검사받은 자료를 가져가야 하나요?</h3>
    <p>가능하면 가져오시는 것이 좋습니다. X-ray·CT·MRI 검사 결과와 처방 내역은 현재 증상을 살펴보는 데 도움이 됩니다.</p>
  </article>

  <article class="faq-item">
    <h3>두통이나 어지럼도 함께 상담할 수 있나요?</h3>
    <p>사고 이후 새롭게 나타난 두통이나 어지럼도 함께 확인합니다. 다만 머리 외상이나 신경학적 이상이 의심되는 경우에는 필요한 검사가 우선입니다.</p>
  </article>

  <article class="faq-item">
    <h3>약침도 받을 수 있나요?</h3>
    <p>모든 경우에 시행하는 것은 아니며, 현재 증상과 상태를 확인한 뒤 필요한 경우 치료 방법 가운데 하나로 고려합니다.</p>
  </article>

  <article class="faq-item">
    <h3>얼마나 자주 진료받아야 하나요?</h3>
    <p>사고의 정도와 증상, 경과에 따라 다르므로 초진에서 현재 상태를 확인한 뒤 진료 간격과 경과 확인 방법을 안내드립니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section" style="padding-top:0">
  <div class="container">
    <div class="clinic-cta">
      <div>
        <h2>사고 당시 상황과 지금 가장 불편한 증상부터 살펴보겠습니다.</h2>
        <p>사고 접수번호와 기존 검사자료, 복용 중인 약이 있다면 내원 시 함께 알려주세요.</p>
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
      "name": "자동차보험으로 진료가 가능한가요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "사고 접수 여부와 보험 적용 상황을 확인한 뒤 안내드립니다. 방문 전에 보험사에서 받은 사고 접수번호가 있다면 준비해 주세요."
      }
    },
    {
      "@type": "Question",
      "name": "사고 당일 바로 진료받아도 되나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "현재 상태를 확인해 진료할 수 있습니다. 다만 심한 두통·구토, 의식 변화, 심한 외상 등 응급평가가 필요한 증상이 있다면 응급실이나 관련 검사를 먼저 받는 것이 중요합니다."
      }
    },
    {
      "@type": "Question",
      "name": "사고 후 며칠 지나서 아프기 시작했는데 관련이 있을 수 있나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "사고 직후보다 시간이 지난 뒤 통증이나 뻐근함이 두드러지는 경우가 있습니다. 사고 전후의 증상 변화를 함께 확인합니다."
      }
    },
    {
      "@type": "Question",
      "name": "다른 병원에서 검사받은 자료를 가져가야 하나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "가능하면 가져오시는 것이 좋습니다. X-ray·CT·MRI 검사 결과와 처방 내역은 현재 증상을 살펴보는 데 도움이 됩니다."
      }
    },
    {
      "@type": "Question",
      "name": "두통이나 어지럼도 함께 상담할 수 있나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "사고 이후 새롭게 나타난 두통이나 어지럼도 함께 확인합니다. 다만 머리 외상이나 신경학적 이상이 의심되는 경우에는 필요한 검사가 우선입니다."
      }
    }
  ]
}
</script>
