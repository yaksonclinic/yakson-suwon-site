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
    max-width:760px;
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
    max-width:760px;
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
  .pain-grid{
    display:grid;
    grid-template-columns:repeat(3,minmax(0,1fr));
    gap:18px;
  }
  .pain-card{
    padding:26px;
    border:1px solid rgba(0,0,0,.09);
    border-radius:18px;
    background:#fff;
  }
  .pain-card h3{
    margin:0 0 10px;
    font-size:1.14rem;
  }
  .pain-card p{
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
  .safety-box{
    padding:28px;
    border-radius:18px;
    background:#223a33;
    color:#fff;
  }
  .safety-box h3{
    margin-top:0;
  }
  .safety-box p{
    margin-bottom:0;
    line-height:1.8;
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
    .pain-grid{grid-template-columns:repeat(2,minmax(0,1fr));}
    .treatment-grid{grid-template-columns:repeat(2,minmax(0,1fr));}
    .clinic-cta{align-items:flex-start;flex-direction:column;}
  }
  @media (max-width:640px){
    .clinic-page-hero{padding:64px 0 48px;}
    .clinic-section{padding:56px 0;}
    .pain-grid,.check-list,.treatment-grid{grid-template-columns:1fr;}
  }
</style>

<section class="clinic-page-hero">
  <div class="container">
    <span class="clinic-kicker">PAIN CLINIC</span>
    <h1>통증 클리닉</h1>
    <p class="clinic-lead">
      목·어깨·허리·무릎처럼 자주 아픈 부위만 보는 것이 아니라,
      <strong>언제 시작됐는지, 어떤 동작에서 심해지는지, 생활 속에서 무엇이 반복되는지</strong>를 함께 살펴봅니다.
      같은 부위의 통증도 시작 시점과 양상에 따라 확인해야 할 내용이 달라질 수 있습니다.
    </p>
    <div class="clinic-nav" aria-label="통증 클리닉 페이지 바로가기">
      <a href="#symptoms">주요 통증</a>
      <a href="#check">진료 시 확인</a>
      <a href="#treatment">진료 방법</a>
      <a href="#faq">자주 묻는 질문</a>
    </div>
  </div>
</section>

<section class="clinic-section" id="symptoms">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">COMMON PAIN</span>
      <h2>이런 통증으로 상담합니다.</h2>
      <p>통증 부위와 함께 움직임, 반복되는 상황, 저림이나 당김 같은 동반 증상도 확인합니다.</p>
    </div>

<div class="pain-grid">
  <article class="pain-card">
    <h3>목·어깨 통증</h3>
    <p>목이 뻣뻣하거나 잘 돌아가지 않는 경우, 어깨와 승모근 주변이 반복적으로 뭉치고 불편한 경우를 살펴봅니다.</p>
  </article>

  <article class="pain-card">
    <h3>허리 통증</h3>
    <p>허리를 굽히거나 펴기 어렵거나 오래 앉아 있은 뒤 허리 주변이 아프고 뻐근한 경우를 확인합니다.</p>
  </article>

  <article class="pain-card">
    <h3>무릎·고관절 통증</h3>
    <p>걷기, 계단 오르내리기, 앉았다 일어날 때 무릎이나 고관절 주변이 불편한 경우를 살펴봅니다.</p>
  </article>

  <article class="pain-card">
    <h3>팔꿈치·손목 통증</h3>
    <p>컴퓨터 작업, 육아, 운동처럼 같은 동작을 반복한 뒤 팔꿈치나 손목의 통증이 지속되는 경우를 확인합니다.</p>
  </article>

  <article class="pain-card">
    <h3>발목·발 통증</h3>
    <p>발목을 삐끗한 뒤 불편이 남아 있거나 걸을 때 발목·발 주변의 통증이 반복되는 경우를 살펴봅니다.</p>
  </article>

  <article class="pain-card">
    <h3>저림·당김을 동반한 통증</h3>
    <p>목이나 허리 통증과 함께 팔·다리가 저리거나 당기는 느낌이 있을 때 동반 증상과 진행 양상을 함께 확인합니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section soft" id="check">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">CHECK POINTS</span>
      <h2>진료할 때 이런 부분을 함께 확인합니다.</h2>
      <p>질환명을 먼저 단정하기보다 현재 증상과 생활에서 반복되는 요소를 차분히 확인하는 것이 중요합니다.</p>
    </div>

<div class="check-list">
  <div class="check-item">
    <strong>언제부터 아팠는지</strong>
    <p>갑자기 시작되었는지, 서서히 생겼는지, 좋아졌다 다시 반복되는지를 확인합니다.</p>
  </div>

  <div class="check-item">
    <strong>어떤 자세에서 심해지는지</strong>
    <p>오래 앉아 있을 때, 걸을 때, 몸을 숙일 때, 특정 동작을 반복할 때 등 통증이 나타나는 상황을 살펴봅니다.</p>
  </div>

  <div class="check-item">
    <strong>다른 증상이 함께 있는지</strong>
    <p>저림, 당김, 움직임 제한, 힘이 빠지는 느낌 등 통증과 함께 나타나는 불편을 확인합니다.</p>
  </div>

  <div class="check-item">
    <strong>평소 생활환경은 어떤지</strong>
    <p>업무 자세, 스마트폰 사용, 운전, 운동, 수면 습관처럼 통증과 관련될 수 있는 생활 요소를 함께 살펴봅니다.</p>
  </div>

  <div class="check-item">
    <strong>기존 검사와 치료 경험</strong>
    <p>MRI·CT·X-ray 등 기존 검사자료나 과거 치료 경험이 있다면 현재 증상과 함께 참고합니다.</p>
  </div>

  <div class="check-item">
    <strong>통증이 반복되는 패턴</strong>
    <p>특정 활동 뒤 심해지는지, 쉬면 줄어드는지 등 통증의 반복 패턴을 확인해 생활관리 방향도 함께 안내합니다.</p>
  </div>
</div>

  </div>
</section>

<section class="clinic-section">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">PAIN PATTERN</span>
      <h2>통증의 양상에 따라 살펴볼 부분도 달라집니다.</h2>
    </div>

<div class="pain-grid">
  <article class="pain-card">
    <h3>갑자기 생긴 통증</h3>
    <p>무거운 물건을 들거나 운동, 잘못된 동작 이후 갑자기 생긴 통증은 현재의 통증 정도와 움직임 제한을 먼저 살펴봅니다.</p>
  </article>

  <article class="pain-card">
    <h3>오래 지속되는 통증</h3>
    <p>수개월 이상 반복되는 통증은 통증 부위뿐 아니라 업무환경, 자세, 운동습관처럼 일상에서 반복되는 요소도 함께 확인합니다.</p>
  </article>

  <article class="pain-card">
    <h3>좋아졌다 다시 아픈 통증</h3>
    <p>한동안 괜찮았다가 다시 불편해지는 경우에는 어떤 활동이나 생활패턴 뒤에 재발하는지를 살펴보는 것이 중요합니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section soft" id="treatment">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">TREATMENT</span>
      <h2>현재 상태를 확인한 뒤 진료 방법을 고려합니다.</h2>
      <p>모든 환자에게 같은 치료를 적용하기보다 증상과 상태를 확인한 뒤 필요한 방법을 선택합니다.</p>
    </div>

<div class="treatment-grid">
  <article class="treatment-card">
    <h3>침 치료</h3>
    <p>통증 부위와 주변 근육의 긴장, 움직임 상태 등을 살펴 침 치료를 진행할 수 있습니다.</p>
  </article>

  <article class="treatment-card">
    <h3>약침 치료</h3>
    <p>현재 증상과 상태에 따라 필요한 경우 약침을 치료 방법 가운데 하나로 고려할 수 있습니다.</p>
  </article>

  <article class="treatment-card">
    <h3>부항 치료</h3>
    <p>근육의 긴장이나 뻐근함이 있는 부위를 살펴 상태에 따라 부항 치료를 함께 시행할 수 있습니다.</p>
  </article>

  <article class="treatment-card">
    <h3>생활관리 안내</h3>
    <p>치료와 함께 평소 통증을 반복시키는 자세나 활동을 확인하고 일상에서 조절할 부분을 안내합니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section">
  <div class="container">
    <div class="safety-box">
      <h3>이런 경우에는 다른 검사가 먼저 필요할 수 있습니다.</h3>
      <p>
        심한 외상 이후 통증이 매우 심하거나, 팔다리에 갑자기 힘이 빠지거나,
        감각이 뚜렷하게 떨어지는 등 평소와 다른 증상이 나타난 경우에는
        영상검사나 관련 의료기관의 평가가 우선 필요할 수 있습니다.
        기존 MRI·CT·X-ray 자료가 있다면 내원 시 함께 가져오시면 진료에 참고가 됩니다.
      </p>
    </div>
  </div>
</section>

<section class="clinic-section soft">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">DAILY CARE</span>
      <h2>집에서는 이렇게 관리해 보세요.</h2>
    </div>

<div class="check-list">
  <div class="check-item">
    <strong>통증이 심할 때 무리하지 않기</strong>
    <p>갑자기 통증이 심해진 상태에서는 억지로 운동하기보다 현재 상태에 맞춰 활동량을 조절하는 것이 좋습니다.</p>
  </div>

  <div class="check-item">
    <strong>같은 자세를 오래 유지하지 않기</strong>
    <p>컴퓨터나 스마트폰을 사용할 때 한 자세를 너무 오래 유지하지 않고, 통증이 심하지 않은 범위에서 가볍게 몸을 움직여 주세요.</p>
  </div>

  <div class="check-item">
    <strong>통증이 심해지는 상황 기록하기</strong>
    <p>언제 아픈지, 어떤 동작 뒤에 심해지는지를 기억하거나 간단히 기록해 두면 진료할 때 도움이 됩니다.</p>
  </div>

  <div class="check-item">
    <strong>기존 검사자료 챙기기</strong>
    <p>이미 촬영한 MRI·CT·X-ray 또는 복용 중인 약이 있다면 내원 시 알려주세요.</p>
  </div>
</div>

  </div>
</section>

<section class="clinic-section" id="faq">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">FAQ</span>
      <h2>통증 클리닉 자주 묻는 질문</h2>
    </div>

<div class="faq-list">
  <article class="faq-item">
    <h3>허리디스크나 목디스크 진단을 받았는데 한의원 진료를 받아도 되나요?</h3>
    <p>기존 진단이 있더라도 현재 나타나는 증상과 검사 결과를 함께 확인해 진료 방향을 상담할 수 있습니다. MRI나 CT 자료가 있다면 가져오시는 것이 좋습니다.</p>
  </article>

  <article class="faq-item">
    <h3>갑자기 허리를 삐끗했는데 바로 진료받아도 되나요?</h3>
    <p>현재 통증의 정도와 움직임 상태를 확인한 뒤 진료 여부를 판단할 수 있습니다. 다만 심한 외상이나 골절 가능성이 의심되는 경우에는 관련 검사가 먼저 필요할 수 있습니다.</p>
  </article>

  <article class="faq-item">
    <h3>약침은 통증 환자에게 모두 하나요?</h3>
    <p>모든 경우에 동일하게 시행하기보다 현재 증상과 상태를 확인한 뒤 필요한 경우 치료 방법 가운데 하나로 고려합니다.</p>
  </article>

  <article class="faq-item">
    <h3>통증이 좋아졌다가 계속 다시 생기는 이유는 무엇인가요?</h3>
    <p>자세, 반복되는 동작, 업무환경, 운동습관 등 여러 요소와 연관될 수 있어 언제 어떤 상황에서 통증이 반복되는지를 함께 살펴보는 것이 중요합니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section" style="padding-top:0">
  <div class="container">
    <div class="clinic-cta">
      <div>
        <h2>현재 통증이 어떻게 시작됐는지부터 살펴보겠습니다.</h2>
        <p>기존 검사자료나 복용 중인 약이 있다면 내원 시 함께 알려주세요.</p>
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
      "name": "허리디스크나 목디스크 진단을 받았는데 한의원 진료를 받아도 되나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "기존 진단이 있더라도 현재 나타나는 증상과 검사 결과를 함께 확인해 진료 방향을 상담할 수 있습니다. MRI나 CT 자료가 있다면 가져오시는 것이 좋습니다."
      }
    },
    {
      "@type": "Question",
      "name": "갑자기 허리를 삐끗했는데 바로 진료받아도 되나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "현재 통증의 정도와 움직임 상태를 확인한 뒤 진료 여부를 판단할 수 있습니다. 다만 심한 외상이나 골절 가능성이 의심되는 경우에는 관련 검사가 먼저 필요할 수 있습니다."
      }
    },
    {
      "@type": "Question",
      "name": "약침은 통증 환자에게 모두 하나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "모든 경우에 동일하게 시행하기보다 현재 증상과 상태를 확인한 뒤 필요한 경우 치료 방법 가운데 하나로 고려합니다."
      }
    },
    {
      "@type": "Question",
      "name": "통증이 좋아졌다가 계속 다시 생기는 이유는 무엇인가요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "자세, 반복되는 동작, 업무환경, 운동습관 등 여러 요소와 연관될 수 있어 언제 어떤 상황에서 통증이 반복되는지를 함께 살펴보는 것이 중요합니다."
      }
    }
  ]
}
</script>
