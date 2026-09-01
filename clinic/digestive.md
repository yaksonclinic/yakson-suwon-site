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
  .clinic-section{padding:72px 0;}
  .clinic-section.soft{background:#f7f6f1;}
  .clinic-heading{max-width:780px;margin-bottom:34px;}
  .clinic-heading h2{
    margin:8px 0 14px;
    font-size:clamp(1.8rem,3vw,2.8rem);
    line-height:1.2;
  }
  .clinic-heading p{line-height:1.8;}
  .digestive-grid{
    display:grid;
    grid-template-columns:repeat(3,minmax(0,1fr));
    gap:18px;
  }
  .digestive-card{
    padding:26px;
    border:1px solid rgba(0,0,0,.09);
    border-radius:18px;
    background:#fff;
  }
  .digestive-card h3{margin:0 0 10px;font-size:1.14rem;}
  .digestive-card p{margin:0;line-height:1.75;}
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
  .damjeok-box{
    padding:32px;
    border-radius:20px;
    background:#fff;
    border:1px solid rgba(0,0,0,.10);
  }
  .damjeok-box h3{
    margin:0 0 14px;
    font-size:1.45rem;
  }
  .damjeok-box p{
    line-height:1.85;
  }
  .damjeok-points{
    display:grid;
    grid-template-columns:repeat(2,minmax(0,1fr));
    gap:14px;
    margin-top:24px;
  }
  .damjeok-point{
    padding:20px;
    background:#f7f6f1;
    border-radius:14px;
  }
  .damjeok-point strong{
    display:block;
    margin-bottom:6px;
  }
  .damjeok-point p{
    margin:0;
    line-height:1.7;
  }
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
    .digestive-grid{grid-template-columns:repeat(2,minmax(0,1fr));}
    .treatment-grid{grid-template-columns:repeat(2,minmax(0,1fr));}
    .clinic-cta{align-items:flex-start;flex-direction:column;}
  }
  @media (max-width:640px){
    .clinic-page-hero{padding:64px 0 48px;}
    .clinic-section{padding:56px 0;}
    .digestive-grid,.check-list,.treatment-grid,.damjeok-points{grid-template-columns:1fr;}
  }
</style>

<section class="clinic-page-hero">
  <div class="container">
    <span class="clinic-kicker">DIGESTIVE CLINIC</span>
    <h1>소화기 클리닉</h1>
    <p class="clinic-lead">
      소화불편은 단순히 무엇을 먹었는지만으로 설명되지 않는 경우가 있습니다.
      <strong>식사시간과 식사속도, 야식, 배변, 수면, 스트레스</strong>처럼
      매일 반복되는 생활리듬과 증상이 언제 심해지는지를 함께 살펴봅니다.
    </p>
    <div class="clinic-nav" aria-label="소화기 클리닉 페이지 바로가기">
      <a href="#symptoms">주요 증상</a>
      <a href="#damjeok">담적 관련 상담</a>
      <a href="#check">진료 시 확인</a>
      <a href="#treatment">진료 방법</a>
      <a href="#faq">자주 묻는 질문</a>
    </div>
  </div>
</section>

<section class="clinic-section" id="symptoms">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">DIGESTIVE CONCERNS</span>
      <h2>이런 소화기 불편으로 상담합니다.</h2>
      <p>증상 자체뿐 아니라 공복·식후·야간 중 언제 심한지, 배변과 어떤 관계가 있는지 함께 확인합니다.</p>
    </div>

<div class="digestive-grid">
  <article class="digestive-card">
    <h3>식후 더부룩함·체기</h3>
    <p>많이 먹지 않았는데도 속이 오래 더부룩하거나 식사 후 답답하고 체한 느낌이 반복되는 경우를 살펴봅니다.</p>
  </article>

  <article class="digestive-card">
    <h3>명치 답답함</h3>
    <p>명치 주변이 꽉 막힌 듯 답답하거나 식후 불편감이 반복될 때 증상이 나타나는 시점과 식사패턴을 확인합니다.</p>
  </article>

  <article class="digestive-card">
    <h3>속쓰림·역류감</h3>
    <p>속이 쓰리거나 신물이 올라오는 느낌, 누웠을 때 불편이 심해지는 경우 식사시간과 야식 여부를 함께 살펴봅니다.</p>
  </article>

  <article class="digestive-card">
    <h3>가스·복부팽만</h3>
    <p>배에 가스가 차고 빵빵한 느낌이 자주 들거나 특정 음식과 함께 심해지는지 확인합니다.</p>
  </article>

  <article class="digestive-card">
    <h3>식욕저하·조기포만감</h3>
    <p>식욕이 떨어지거나 조금만 먹어도 금방 배가 부르고 식사를 이어가기 어려운 경우를 살펴봅니다.</p>
  </article>

  <article class="digestive-card">
    <h3>변비·묽은 변의 반복</h3>
    <p>변비와 묽은 변이 반복되거나 배변 전후로 복부 불편이 달라지는 경우 식사와 배변패턴을 함께 확인합니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section soft" id="damjeok">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">DAMJEOK</span>
      <h2>한의학에서 말하는 ‘담적’ 관련 소화불편</h2>
      <p>‘담적’은 현대의학의 공식 진단명과 동일한 개념은 아니며, 한의학 진료에서 반복되는 소화불편의 양상을 설명할 때 사용하는 표현 가운데 하나입니다.</p>
    </div>

<div class="damjeok-box">
  <h3>더부룩함과 명치 답답함이 오래 반복된다면</h3>
  <p>
    한의학에서는 식후 더부룩함, 잦은 체기, 명치가 단단하거나 막힌 듯한 느낌,
    트림·가스·복부팽만, 식욕저하처럼 소화기 불편이 반복될 때
    환자의 전체 증상과 생활상태를 살펴 ‘담적’이라는 관점에서 설명하기도 합니다.
  </p>
  <p>
    다만 이런 증상은 위염, 역류성 식도염, 기능성 소화불량 등 여러 원인과도 관련될 수 있으므로
    ‘담적병’이라는 이름만으로 원인을 단정하기보다 기존 검사 결과와 현재 증상을 함께 확인하는 것이 중요합니다.
  </p>

  <div class="damjeok-points">
    <div class="damjeok-point">
      <strong>식후 오래 남는 더부룩함</strong>
      <p>식사량이 많지 않아도 속이 꽉 찬 느낌이 오래 지속되는지 확인합니다.</p>
    </div>

    <div class="damjeok-point">
      <strong>명치의 답답함·압박감</strong>
      <p>명치 부위가 막힌 듯하거나 누르면 불편한 느낌이 반복되는지 살펴봅니다.</p>
    </div>

    <div class="damjeok-point">
      <strong>잦은 트림·가스·복부팽만</strong>
      <p>식사 후 트림이나 가스가 많고 배가 쉽게 불러오는지 확인합니다.</p>
    </div>

    <div class="damjeok-point">
      <strong>소화불편과 함께 나타나는 컨디션 변화</strong>
      <p>피로, 두통, 수면불편 등이 소화 증상과 함께 반복되는지도 함께 살펴봅니다.</p>
    </div>
  </div>
</div>

  </div>
</section>

<section class="clinic-section" id="check">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">CONSULTATION CHECKPOINT</span>
      <h2>소화기 진료에서는 이런 내용을 함께 확인합니다.</h2>
      <p>언제, 무엇을 먹고, 어떤 생활을 할 때 증상이 달라지는지 구체적으로 살펴봅니다.</p>
    </div>

<div class="check-list">
  <div class="check-item">
    <strong>증상이 나타나는 시간</strong>
    <p>공복, 식사 직후, 식후 몇 시간 뒤, 야간 중 어느 때 가장 불편한지 확인합니다.</p>
  </div>

  <div class="check-item">
    <strong>식사시간과 식사속도</strong>
    <p>식사가 불규칙한지, 급하게 먹는 편인지, 늦은 시간에 식사나 간식을 자주 하는지 살펴봅니다.</p>
  </div>

  <div class="check-item">
    <strong>자주 먹는 음식과 음료</strong>
    <p>커피, 술, 맵거나 기름진 음식 등 특정 음식 이후 불편이 심해지는지 확인합니다.</p>
  </div>

  <div class="check-item">
    <strong>배변의 빈도와 형태</strong>
    <p>며칠에 한 번 배변하는지, 변의 형태와 복통·복부팽만이 어떤 관계가 있는지 살펴봅니다.</p>
  </div>

  <div class="check-item">
    <strong>수면과 스트레스</strong>
    <p>수면 부족이나 긴장, 스트레스가 심해질 때 소화불편도 함께 심해지는지 확인합니다.</p>
  </div>

  <div class="check-item">
    <strong>기존 검사와 복용약</strong>
    <p>위·대장내시경, 혈액검사 등 기존 검사 결과와 현재 복용 중인 소화기 약을 함께 확인합니다.</p>
  </div>
</div>

  </div>
</section>

<section class="clinic-section soft">
  <div class="container">
    <div class="important-box">
      <h3>검사에서 큰 이상이 없더라도 불편은 계속될 수 있습니다.</h3>
      <p>
        내시경이나 다른 검사에서 뚜렷한 구조적 이상이 확인되지 않았더라도
        식사 습관이나 위장 기능, 배변 패턴, 스트레스와 연결된 소화불편이 이어질 수 있습니다.
        따라서 검사 결과와 함께 실제 생활에서 반복되는 증상의 패턴을 구체적으로 확인하는 것이 중요합니다.
      </p>
    </div>
  </div>
</section>

<section class="clinic-section">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">PATTERN & APPROACH</span>
      <h2>소화불편은 이런 양상으로 나눠 살펴볼 수 있습니다.</h2>
    </div>

<div class="digestive-grid">
  <article class="digestive-card">
    <h3>식후 더부룩형</h3>
    <p>많이 먹지 않았는데도 식사 후 속이 더부룩하고 명치 주변의 답답함이 오래 남는 경우입니다.</p>
  </article>

  <article class="digestive-card">
    <h3>속쓰림·역류형</h3>
    <p>속쓰림이나 신물이 올라오는 느낌이 있고 늦은 식사나 누운 자세에서 불편이 심해지는 경우입니다.</p>
  </article>

  <article class="digestive-card">
    <h3>배변 연관형</h3>
    <p>변비나 설사, 복부팽만과 복통이 서로 연결되어 반복되는 경우 배변패턴까지 함께 확인합니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section soft" id="treatment">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">CARE</span>
      <h2>현재 상태에 따라 진료 방법을 함께 상의합니다.</h2>
      <p>모든 분에게 같은 방법을 적용하기보다 증상의 패턴과 기존 진료, 생활불편의 정도를 확인한 뒤 필요한 방향을 설명합니다.</p>
    </div>

<div class="treatment-grid">
  <article class="treatment-card">
    <h3>생활 문진</h3>
    <p>식사시간과 식사속도, 음식, 배변, 수면과 스트레스 등 증상에 영향을 줄 수 있는 생활패턴을 자세히 확인합니다.</p>
  </article>

  <article class="treatment-card">
    <h3>침 치료 상담</h3>
    <p>더부룩함이나 명치 답답함 등 현재 증상과 상태에 따라 필요한 경우 침 치료를 진료 방법 가운데 하나로 고려할 수 있습니다.</p>
  </article>

  <article class="treatment-card">
    <h3>한약 상담</h3>
    <p>증상과 전반적인 몸 상태, 기존 복용약을 확인한 뒤 필요한 경우 한약 복용을 상담합니다.</p>
  </article>

  <article class="treatment-card">
    <h3>생활관리 안내</h3>
    <p>식사속도, 야식, 증상을 유발하는 음식, 배변 습관처럼 일상에서 조절해 볼 부분을 함께 안내합니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section">
  <div class="container">
    <div class="safety-box">
      <h3>이런 경우에는 소화기내과 검사나 관련 의료기관의 평가가 우선입니다.</h3>
      <ul>
        <li>특별한 이유 없이 체중이 계속 감소하는 경우</li>
        <li>검은색 변이나 혈변이 확인되는 경우</li>
        <li>구토가 반복되거나 음식과 수분 섭취가 어려운 경우</li>
        <li>음식을 삼키기 어렵거나 걸리는 느낌이 지속되는 경우</li>
        <li>심한 복통이나 탈수 증상이 있는 경우</li>
      </ul>
    </div>
  </div>
</section>

<section class="clinic-section soft">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">HOME CARE</span>
      <h2>집에서는 식사와 증상의 관계를 살펴보세요.</h2>
    </div>

<div class="check-list">
  <div class="check-item">
    <strong>천천히 식사하기</strong>
    <p>짧은 시간에 급하게 먹기보다 천천히 씹으며 식사하고, 한 번에 과식하는 습관을 줄여보세요.</p>
  </div>

  <div class="check-item">
    <strong>늦은 야식 줄이기</strong>
    <p>취침 직전의 식사와 간식은 속쓰림이나 역류감, 수면 불편과 연결될 수 있어 식사시간을 살펴보는 것이 좋습니다.</p>
  </div>

  <div class="check-item">
    <strong>증상을 유발하는 음식 기록하기</strong>
    <p>커피, 술, 맵거나 기름진 음식 등 특정 음식 이후 증상이 반복되는지 간단히 기록해 보세요.</p>
  </div>

  <div class="check-item">
    <strong>배변 패턴 함께 기록하기</strong>
    <p>배변 횟수와 변의 형태, 복통과 복부팽만이 어떻게 달라지는지를 함께 기록하면 상담에 도움이 됩니다.</p>
  </div>
</div>

  </div>
</section>

<section class="clinic-section" id="faq">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">FAQ</span>
      <h2>소화기 클리닉 자주 묻는 질문</h2>
    </div>

<div class="faq-list">
  <article class="faq-item">
    <h3>담적병인지 어떻게 알 수 있나요?</h3>
    <p>‘담적병’은 현대의학의 공식 진단명과 동일한 개념은 아닙니다. 한의학 진료에서는 식후 더부룩함, 명치 답답함, 잦은 체기, 가스와 복부팽만 등 반복되는 증상과 생활상태를 함께 살펴 담적의 관점에서 설명하기도 합니다. 필요한 경우 위내시경 등 기존 검사 결과도 함께 확인합니다.</p>
  </article>

  <article class="faq-item">
    <h3>내시경은 정상인데 계속 더부룩할 수 있나요?</h3>
    <p>네. 검사에서 구조적인 이상이 확인되지 않더라도 식사습관, 위장 기능, 스트레스 등과 관련된 불편이 지속될 수 있어 증상 패턴을 함께 살펴봅니다.</p>
  </article>

  <article class="faq-item">
    <h3>역류성 식도염 진단을 받았는데 상담할 수 있나요?</h3>
    <p>가능합니다. 현재 복용 중인 약과 검사 결과, 식사시간과 수면패턴 등을 함께 확인합니다. 처방받은 약은 임의로 중단하지 마세요.</p>
  </article>

  <article class="faq-item">
    <h3>변비와 설사가 번갈아 나타나도 상담하나요?</h3>
    <p>네. 배변 빈도와 형태, 복부팽만과 복통, 식사와 스트레스의 관계를 함께 살펴봅니다.</p>
  </article>

  <article class="faq-item">
    <h3>메스꺼움도 소화기 클리닉에서 볼 수 있나요?</h3>
    <p>상담할 수 있습니다. 다만 임신 가능성, 복용약, 어지럼 등 다른 원인도 있을 수 있어 함께 확인해야 합니다.</p>
  </article>

  <article class="faq-item">
    <h3>소화기 약을 복용 중인데 한의원 진료가 가능한가요?</h3>
    <p>가능합니다. 복용 중인 약의 이름이나 처방 내용을 알려주시고 임의로 중단하지 않는 것이 중요합니다.</p>
  </article>

  <article class="faq-item">
    <h3>한약은 꼭 먹어야 하나요?</h3>
    <p>아닙니다. 현재 증상과 생활패턴을 먼저 확인하고 필요한 경우에 한해 한약 상담을 진행합니다.</p>
  </article>

  <article class="faq-item">
    <h3>진료 전에 준비하면 좋은 것이 있나요?</h3>
    <p>최근 내시경이나 검사 결과, 복용 중인 약, 어떤 음식과 상황에서 증상이 심해지는지에 대한 간단한 메모가 있으면 도움이 됩니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section" style="padding-top:0">
  <div class="container">
    <div class="clinic-cta">
      <div>
        <h2>언제 먹고, 언제 불편한지부터 살펴보겠습니다.</h2>
        <p>최근 검사자료와 복용약, 음식과 증상의 관계를 기록한 내용이 있다면 내원 시 함께 알려주세요.</p>
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
      "name": "담적병인지 어떻게 알 수 있나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "담적병은 현대의학의 공식 진단명과 동일한 개념은 아닙니다. 한의학 진료에서는 식후 더부룩함, 명치 답답함, 잦은 체기, 가스와 복부팽만 등 반복되는 증상과 생활상태를 함께 살펴 담적의 관점에서 설명하기도 합니다."
      }
    },
    {
      "@type": "Question",
      "name": "내시경은 정상인데 계속 더부룩할 수 있나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "검사에서 구조적인 이상이 확인되지 않더라도 식사습관, 위장 기능, 스트레스 등과 관련된 불편이 지속될 수 있어 증상 패턴을 함께 살펴봅니다."
      }
    },
    {
      "@type": "Question",
      "name": "역류성 식도염 진단을 받았는데 상담할 수 있나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "현재 복용 중인 약과 검사 결과, 식사시간과 수면패턴 등을 함께 확인합니다. 처방받은 약은 임의로 중단하지 않는 것이 중요합니다."
      }
    },
    {
      "@type": "Question",
      "name": "한약은 꼭 먹어야 하나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "현재 증상과 생활패턴을 먼저 확인하고 필요한 경우에 한해 한약 상담을 진행합니다."
      }
    }
  ]
}
</script>
