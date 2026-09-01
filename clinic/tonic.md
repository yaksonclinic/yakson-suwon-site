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

  .tonic-grid{
    display:grid;
    grid-template-columns:repeat(3,minmax(0,1fr));
    gap:18px;
  }
  .tonic-card{
    padding:26px;
    border:1px solid rgba(0,0,0,.09);
    border-radius:18px;
    background:#fff;
  }
  .tonic-card h3{margin:0 0 10px;font-size:1.14rem;}
  .tonic-card p{margin:0;line-height:1.75;}

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
    .tonic-grid{grid-template-columns:repeat(2,minmax(0,1fr));}
    .treatment-grid{grid-template-columns:repeat(2,minmax(0,1fr));}
    .clinic-cta{align-items:flex-start;flex-direction:column;}
  }
  @media (max-width:640px){
    .clinic-page-hero{padding:64px 0 48px;}
    .clinic-section{padding:56px 0;}
    .tonic-grid,.check-list,.treatment-grid{grid-template-columns:1fr;}
  }
</style>

<section class="clinic-page-hero">
  <div class="container">
    <span class="clinic-kicker">TONIC & RECOVERY CARE</span>
    <h1>보약·체력회복 클리닉</h1>
    <p class="clinic-lead">
      충분히 쉬어도 피로가 잘 풀리지 않거나,
      <strong>손·발·어깨·허벅지 등 특정 부위가 유난히 시리거나 반대로 뜨겁게 느껴지는 경우</strong>처럼
      검사 하나로 설명하기 어려운 불편을 호소하는 분들이 있습니다.
      약손한의원에서는 피로의 양상과 수면·식사·소화·활동량, 평소 추위와 더위에 대한 반응을 함께 살펴봅니다.
    </p>
    <div class="clinic-nav" aria-label="보약·체력회복 클리닉 페이지 바로가기">
      <a href="#symptoms">주요 고민</a>
      <a href="#temperature">시림·열감</a>
      <a href="#check">진료 시 확인</a>
      <a href="#treatment">진료 방법</a>
      <a href="#faq">자주 묻는 질문</a>
    </div>
  </div>
</section>

<section class="clinic-section" id="symptoms">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">FATIGUE & RECOVERY</span>
      <h2>이런 피로와 컨디션 저하로 상담합니다.</h2>
      <p>단순히 “기운이 없다”는 말보다 언제 피곤한지, 쉬면 회복되는지, 수면·소화·체온감각은 어떤지를 함께 확인합니다.</p>
    </div>

<div class="tonic-grid">
  <article class="tonic-card">
    <h3>쉽게 지치고 피로가 오래가는 경우</h3>
    <p>아침부터 몸이 무겁거나 일을 조금만 해도 지치고, 자고 나도 개운하지 않은 상태가 반복되는지 살펴봅니다.</p>
  </article>

  <article class="tonic-card">
    <h3>회복이 더딘 경우</h3>
    <p>과로·감기·질병 이후 예전 컨디션으로 돌아오는 데 시간이 오래 걸리거나 활동 후 피로가 며칠씩 이어지는지 확인합니다.</p>
  </article>

  <article class="tonic-card">
    <h3>손발이나 신체 일부가 시린 경우</h3>
    <p>손·발뿐 아니라 어깨·허벅지 등 특정 부위가 차거나 시린 느낌이 반복될 때 어느 상황에서 심해지는지 살펴봅니다.</p>
  </article>

  <article class="tonic-card">
    <h3>신체 일부가 뜨겁고 화끈거리는 경우</h3>
    <p>손발이나 특정 부위가 유난히 뜨겁거나 화끈거리는 느낌이 반복될 때 시간대와 수면·스트레스·활동과의 관계를 확인합니다.</p>
  </article>

  <article class="tonic-card">
    <h3>식욕·소화가 떨어진 경우</h3>
    <p>피로와 함께 입맛이 없고 식사량이 줄거나 더부룩함이 반복되는 경우 식사와 소화 상태를 함께 살펴봅니다.</p>
  </article>

  <article class="tonic-card">
    <h3>수면이 부족하고 아침이 힘든 경우</h3>
    <p>잠은 자지만 깊게 잔 느낌이 없거나 자주 깨고, 아침에 몸이 무겁고 회복되지 않는 느낌이 있는지 확인합니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section soft" id="temperature">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">COLD & HEAT SENSATION</span>
      <h2>같은 사람에게도 시림과 열감이 다르게 나타날 수 있습니다.</h2>
      <p>“몸이 차다” 또는 “열이 많다”는 표현만으로 판단하기보다 실제 어느 부위에서 어떤 느낌이 언제 나타나는지 구체적으로 확인합니다.</p>
    </div>

<div class="tonic-grid">
  <article class="tonic-card">
    <h3>손·발이 시리고 차가운 느낌</h3>
    <p>계절과 관계없이 손발이 시리거나 추위에 유난히 민감한 경우 증상이 시작된 시기와 생활환경을 살펴봅니다.</p>
  </article>

  <article class="tonic-card">
    <h3>어깨·허벅지 등 부분적인 냉감</h3>
    <p>실제 피부 온도와 관계없이 특정 부위가 차갑거나 시리게 느껴질 수 있어 통증·저림·감각 변화가 함께 있는지도 확인합니다.</p>
  </article>

  <article class="tonic-card">
    <h3>손발이 뜨겁고 열나는 느낌</h3>
    <p>특히 밤에 손발이 뜨겁거나 이불 밖으로 내놓고 싶을 정도의 열감이 반복되는지 확인합니다.</p>
  </article>

  <article class="tonic-card">
    <h3>상체는 덥고 하체는 찬 느낌</h3>
    <p>얼굴이나 상체는 쉽게 달아오르지만 손발이나 하체는 차게 느껴지는 등 부위별 차이가 있는지 살펴봅니다.</p>
  </article>

  <article class="tonic-card">
    <h3>피로할수록 심해지는 냉·열감</h3>
    <p>과로, 수면 부족, 스트레스 이후 시림이나 열감이 더 뚜렷해지는지 확인합니다.</p>
  </article>

  <article class="tonic-card">
    <h3>통증·저림과 함께 나타나는 경우</h3>
    <p>냉감이나 열감과 함께 저림, 통증, 감각 둔화가 있다면 신경·혈관 등 다른 원인 가능성도 함께 고려합니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section">
  <div class="container">
    <div class="important-box">
      <h3>‘체질’은 증상을 한 단어로 단정하는 것이 아니라, 반복되는 몸의 경향을 살펴보는 데 활용합니다.</h3>
      <p>
        같은 피로라도 잠이 부족한 분, 소화가 약한 분, 추위에 민감한 분,
        반대로 열감과 답답함을 자주 느끼는 분은 불편의 양상이 서로 다를 수 있습니다.
        진료에서는 평소 몸의 반응과 생활습관을 함께 확인하고,
        현재 증상을 설명하는 데 도움이 되는 체질적 경향을 참고합니다.
      </p>
    </div>
  </div>
</section>

<section class="clinic-section soft" id="check">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">CONSULTATION CHECKPOINT</span>
      <h2>보약 상담에서는 이런 내용을 함께 확인합니다.</h2>
      <p>피로와 시림·열감은 원인이 다양할 수 있어 생활상태와 기존 검사 결과를 함께 살펴보는 것이 중요합니다.</p>
    </div>

<div class="check-list">
  <div class="check-item">
    <strong>피로가 심한 시간과 회복 정도</strong>
    <p>아침부터 피곤한지, 오후에 처지는지, 충분히 쉬었을 때 회복되는지를 확인합니다.</p>
  </div>

  <div class="check-item">
    <strong>시림·열감이 나타나는 부위</strong>
    <p>손·발·어깨·허벅지 등 어느 부위인지, 양쪽인지 한쪽인지, 계절과 시간대에 따라 달라지는지 살펴봅니다.</p>
  </div>

  <div class="check-item">
    <strong>수면시간과 수면의 질</strong>
    <p>잠드는 시간, 자주 깨는지, 아침에 개운한지 등을 확인합니다.</p>
  </div>

  <div class="check-item">
    <strong>식욕·소화·배변</strong>
    <p>피로와 함께 식욕저하, 더부룩함, 변비·묽은 변 등이 있는지 살펴봅니다.</p>
  </div>

  <div class="check-item">
    <strong>과로·운동·업무량</strong>
    <p>최근 업무와 운동량, 휴식일, 활동 후 피로가 얼마나 지속되는지 확인합니다.</p>
  </div>

  <div class="check-item">
    <strong>혈액검사·복용약·기저질환</strong>
    <p>빈혈, 갑상선, 혈당 등 기존 검사 결과와 현재 복용 중인 약이 있다면 함께 확인합니다.</p>
  </div>
</div>

  </div>
</section>

<section class="clinic-section">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">CARE</span>
      <h2>현재 상태에 따라 필요한 회복 방향을 상의합니다.</h2>
      <p>모든 피로에 같은 보약을 권하기보다 생활상태와 증상의 패턴, 기존 검사와 복용약을 먼저 확인합니다.</p>
    </div>

<div class="treatment-grid">
  <article class="treatment-card">
    <h3>체력·생활상태 확인</h3>
    <p>피로의 시작 시점과 활동량, 수면, 식사, 회복 정도를 자세히 살펴봅니다.</p>
  </article>

  <article class="treatment-card">
    <h3>냉·열감 양상 확인</h3>
    <p>신체 어느 부위가 시리거나 뜨거운지, 저림·통증 등 다른 감각 변화가 함께 있는지 확인합니다.</p>
  </article>

  <article class="treatment-card">
    <h3>개인별 한약 상담</h3>
    <p>현재 증상과 체질적 경향, 식욕·소화·수면, 복용약을 확인한 뒤 필요한 경우 한약을 상담합니다.</p>
  </article>

  <article class="treatment-card">
    <h3>회복을 위한 생활관리</h3>
    <p>수면시간, 식사, 운동과 휴식의 균형 등 현재 생활에서 조정해 볼 부분을 함께 안내합니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section soft">
  <div class="container">
    <div class="safety-box">
      <h3>피로와 시림·열감이 있을 때 이런 경우에는 관련 검사가 우선입니다.</h3>
      <ul>
        <li>한쪽 팔이나 다리에 갑자기 심한 냉감·열감과 함께 힘 빠짐이나 감각 이상이 생긴 경우</li>
        <li>손발 색이 창백하거나 파랗게 변하고 심한 통증이 지속되는 경우</li>
        <li>한쪽 다리가 갑자기 붓고 뜨겁거나 통증이 심한 경우</li>
        <li>이유 없는 체중 감소, 지속적인 발열, 심한 식욕저하가 있는 경우</li>
        <li>피로가 심하면서 숨참·흉통·실신, 심한 두근거림 등이 동반되는 경우</li>
      </ul>
    </div>
  </div>
</section>

<section class="clinic-section">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">HOME CARE</span>
      <h2>집에서는 피로와 냉·열감의 패턴을 기록해 보세요.</h2>
    </div>

<div class="check-list">
  <div class="check-item">
    <strong>언제 가장 피곤한지 기록하기</strong>
    <p>기상 직후, 오후, 저녁 중 어느 때 피로가 심한지 기록해 두면 상담에 도움이 됩니다.</p>
  </div>

  <div class="check-item">
    <strong>시리거나 뜨거운 부위 표시하기</strong>
    <p>어느 부위에서 얼마나 오래 지속되는지, 양쪽인지 한쪽인지 간단히 기록해 보세요.</p>
  </div>

  <div class="check-item">
    <strong>수면과 피로의 관계 살펴보기</strong>
    <p>수면시간이 줄었을 때 피로와 냉·열감이 심해지는지 확인해 보세요.</p>
  </div>

  <div class="check-item">
    <strong>기존 검사자료 챙기기</strong>
    <p>최근 건강검진이나 혈액검사, 복용약이 있다면 내원 시 함께 가져오면 도움이 됩니다.</p>
  </div>
</div>

  </div>
</section>

<section class="clinic-section soft" id="faq">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">FAQ</span>
      <h2>보약·체력회복 클리닉 자주 묻는 질문</h2>
    </div>

<div class="faq-list">
  <article class="faq-item">
    <h3>검사에서는 이상이 없는데 계속 피곤해요.</h3>
    <p>검사에서 특별한 이상이 확인되지 않아도 수면 부족, 과로, 식사 불규칙, 스트레스 등 여러 요인이 피로와 함께 나타날 수 있습니다. 기존 검사 결과와 생활패턴을 함께 확인합니다.</p>
  </article>

  <article class="faq-item">
    <h3>손발뿐 아니라 어깨나 허벅지가 시린 느낌도 상담할 수 있나요?</h3>
    <p>네. 어느 부위가 언제 시린지, 한쪽인지 양쪽인지, 통증·저림·감각 변화가 함께 있는지를 확인합니다. 갑작스럽거나 심한 감각 이상이 있다면 신경·혈관 관련 평가가 우선될 수 있습니다.</p>
  </article>

  <article class="faq-item">
    <h3>손발이 차가운 게 아니라 오히려 뜨거운 경우도 있나요?</h3>
    <p>네. 손발이나 특정 부위가 화끈거리거나 뜨겁게 느껴지는 분도 있습니다. 시간대와 수면·스트레스, 다른 감각 증상과의 관계를 함께 살펴봅니다.</p>
  </article>

  <article class="faq-item">
    <h3>체질을 검사해서 보약을 정하나요?</h3>
    <p>체질 하나만으로 처방을 결정하지 않습니다. 현재 피로와 수면, 소화, 냉·열감, 생활상태와 기존 질환·복용약 등을 함께 확인해 상담합니다.</p>
  </article>

  <article class="faq-item">
    <h3>보약은 피곤하면 누구나 먹어도 되나요?</h3>
    <p>피로의 원인이 다양하기 때문에 무조건 보약을 권하지 않습니다. 빈혈, 갑상선 질환, 감염 등 검사가 필요한 경우가 있는지 먼저 확인하는 것이 중요합니다.</p>
  </article>

  <article class="faq-item">
    <h3>건강검진 결과를 가져가도 되나요?</h3>
    <p>네. 최근 혈액검사나 건강검진 결과가 있다면 피로와 현재 상태를 살펴보는 데 도움이 됩니다.</p>
  </article>

  <article class="faq-item">
    <h3>공진단이나 경옥고와 일반 보약은 어떻게 다른가요?</h3>
    <p>현재 상태와 복용 목적에 따라 상담 내용이 달라질 수 있습니다. 공진단·경옥고는 별도 클리닉에서 복용 대상과 복용 방법을 자세히 안내합니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section" style="padding-top:0">
  <div class="container">
    <div class="clinic-cta">
      <div>
        <h2>왜 계속 지치는지, 몸이 어디에서 차거나 뜨겁게 느껴지는지부터 살펴보겠습니다.</h2>
        <p>최근 건강검진이나 혈액검사 결과, 복용약이 있다면 내원 시 함께 알려주세요.</p>
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
      "name": "검사에서는 이상이 없는데 계속 피곤해요.",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "검사에서 특별한 이상이 확인되지 않아도 수면 부족, 과로, 식사 불규칙, 스트레스 등 여러 요인이 피로와 함께 나타날 수 있습니다. 기존 검사 결과와 생활패턴을 함께 확인합니다."
      }
    },
    {
      "@type": "Question",
      "name": "손발뿐 아니라 어깨나 허벅지가 시린 느낌도 상담할 수 있나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "어느 부위가 언제 시린지, 한쪽인지 양쪽인지, 통증·저림·감각 변화가 함께 있는지를 확인합니다. 갑작스럽거나 심한 감각 이상이 있다면 신경·혈관 관련 평가가 우선될 수 있습니다."
      }
    },
    {
      "@type": "Question",
      "name": "손발이 차가운 게 아니라 오히려 뜨거운 경우도 있나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "손발이나 특정 부위가 화끈거리거나 뜨겁게 느껴지는 분도 있습니다. 시간대와 수면·스트레스, 다른 감각 증상과의 관계를 함께 살펴봅니다."
      }
    },
    {
      "@type": "Question",
      "name": "체질을 검사해서 보약을 정하나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "체질 하나만으로 처방을 결정하지 않습니다. 현재 피로와 수면, 소화, 냉·열감, 생활상태와 기존 질환·복용약 등을 함께 확인해 상담합니다."
      }
    },
    {
      "@type": "Question",
      "name": "보약은 피곤하면 누구나 먹어도 되나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "피로의 원인이 다양하기 때문에 무조건 보약을 권하지 않습니다. 빈혈, 갑상선 질환, 감염 등 검사가 필요한 경우가 있는지 먼저 확인하는 것이 중요합니다."
      }
    }
  ]
}
</script>
