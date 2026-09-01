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
  .skin-grid{
    display:grid;
    grid-template-columns:repeat(3,minmax(0,1fr));
    gap:18px;
  }
  .skin-card{
    padding:26px;
    border:1px solid rgba(0,0,0,.09);
    border-radius:18px;
    background:#fff;
  }
  .skin-card h3{margin:0 0 10px;font-size:1.14rem;}
  .skin-card p{margin:0;line-height:1.75;}
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
    .skin-grid{grid-template-columns:repeat(2,minmax(0,1fr));}
    .treatment-grid{grid-template-columns:repeat(2,minmax(0,1fr));}
    .clinic-cta{align-items:flex-start;flex-direction:column;}
  }
  @media (max-width:640px){
    .clinic-page-hero{padding:64px 0 48px;}
    .clinic-section{padding:56px 0;}
    .skin-grid,.check-list,.treatment-grid{grid-template-columns:1fr;}
  }
</style>

<section class="clinic-page-hero">
  <div class="container">
    <span class="clinic-kicker">SKIN CLINIC</span>
    <h1>피부 클리닉</h1>
    <p class="clinic-lead">
      피부의 불편은 겉으로 보이는 증상뿐 아니라
      <strong>언제 심해지는지, 수면·식사·스트레스와 어떤 연관이 있는지</strong>를 함께 살펴보는 것이 중요합니다.
      반복되는 피부 트러블과 가려움, 건조함 등 현재 피부 상태와 생활패턴을 함께 확인합니다.
    </p>
    <div class="clinic-nav" aria-label="피부 클리닉 페이지 바로가기">
      <a href="#symptoms">주요 피부 고민</a>
      <a href="#check">진료 시 확인</a>
      <a href="#treatment">진료 방법</a>
      <a href="#faq">자주 묻는 질문</a>
    </div>
  </div>
</section>

<section class="clinic-section" id="symptoms">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">SKIN CONCERNS</span>
      <h2>이런 피부 불편으로 상담합니다.</h2>
      <p>피부 증상의 위치와 양상, 반복되는 시기와 악화 요인을 함께 살펴봅니다.</p>
    </div>

<div class="skin-grid">
  <article class="skin-card">
  <h3>두드러기·가려움</h3>
  <p>갑자기 올라왔다 사라지거나 반복되는 두드러기와 가려움이 있을 때 발생 시점과 지속 시간, 음식·약물·스트레스·생활환경 등을 함께 살펴봅니다.</p>
</article>

  <article class="skin-card">
  <h3>여드름·반복되는 피부 트러블</h3>
  <p>얼굴이나 몸에 여드름과 붉은 트러블이 반복되거나 특정 시기에 심해지는 경우 발생 패턴과 생활습관을 함께 확인합니다.</p>
</article>

   <article class="skin-card">
    <h3>습진·민감성 피부</h3>
<p>붉어짐, 건조함, 가려움이 반복되는 피부 상태를 현재 사용 중인 제품과 생활환경을 함께 확인하며 살펴봅니다.</p>
</article>

  <article class="skin-card">
    <h3>건조함·각질</h3>
    <p>피부가 쉽게 당기고 건조해지거나 각질이 반복되는 경우 계절과 세안·보습 습관 등을 함께 살펴봅니다.</p>
  </article>

  <article class="skin-card">
    <h3>붉어짐·열감</h3>
    <p>얼굴이나 특정 부위가 쉽게 붉어지거나 열감이 반복될 때 나타나는 상황과 지속 시간을 확인합니다.</p>
  </article>

  <article class="skin-card">
    <h3>스트레스와 함께 심해지는 피부 불편</h3>
    <p>수면 부족이나 과로, 스트레스 이후 피부 증상이 반복적으로 심해지는지 함께 살펴봅니다.</p>
  </article>

  <article class="skin-card">
    <h3>피부 컨디션 한약 상담</h3>
    <p>현재 피부 증상과 소화, 수면, 피로, 복용약 등을 확인한 뒤 필요한 경우 한약 상담을 진행합니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section soft" id="check">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">CONSULTATION CHECKPOINT</span>
      <h2>피부 증상이 언제, 어떻게 변하는지 확인합니다.</h2>
      <p>같은 피부 불편도 악화되는 시기와 생활환경이 다를 수 있어 변화의 흐름을 살펴봅니다.</p>
    </div>

<div class="check-list">
  <div class="check-item">
    <strong>언제부터 시작됐는지</strong>
    <p>최근 갑자기 생겼는지, 오래 반복됐는지, 특정 계절이나 시기에 심해지는지 확인합니다.</p>
  </div>

  <div class="check-item">
    <strong>어느 부위에 나타나는지</strong>
    <p>얼굴, 목, 팔, 다리 등 증상이 나타나는 위치와 퍼지는 양상을 살펴봅니다.</p>
  </div>

  <div class="check-item">
    <strong>가려움·열감·통증 여부</strong>
    <p>가려움이나 화끈거림, 통증, 진물 등 동반되는 불편이 있는지 확인합니다.</p>
  </div>

  <div class="check-item">
    <strong>수면·스트레스 상태</strong>
    <p>수면 부족이나 과로, 스트레스가 심해진 시기와 피부 변화가 겹치는지 살펴봅니다.</p>
  </div>

  <div class="check-item">
    <strong>식사·소화 상태</strong>
    <p>식사 패턴, 소화 불편, 특정 음식 이후 피부 증상 변화가 있었는지 함께 확인합니다.</p>
  </div>

  <div class="check-item">
    <strong>기존 피부과 진료와 복용약</strong>
    <p>피부과 진단, 사용 중인 연고나 복용약이 있다면 현재 상태와 함께 참고합니다.</p>
  </div>
</div>

  </div>
</section>

<section class="clinic-section">
  <div class="container">
    <div class="important-box">
      <h3>피부는 생활환경에 따라 하루하루 다르게 보일 수 있습니다.</h3>
      <p>
        언제 심해지는지, 무엇을 사용했을 때 달라지는지, 수면과 식사 상태는 어땠는지
        간단히 기록해 두면 변화의 흐름을 이해하는 데 도움이 됩니다.
        기존에 피부과 치료를 받고 있다면 임의로 중단하지 말고 현재 치료 내용도 함께 알려주세요.
      </p>
    </div>
  </div>
</section>

<section class="clinic-section soft" id="treatment">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">CARE</span>
      <h2>현재 피부 상태와 전반적인 컨디션을 함께 살펴봅니다.</h2>
      <p>피부 증상과 생활패턴을 확인한 뒤 필요한 한의학적 진료 방향을 안내합니다.</p>
    </div>

<div class="treatment-grid">
  <article class="treatment-card">
    <h3>피부 상태 확인</h3>
    <p>증상의 위치와 양상, 시작 시점과 악화 요인을 먼저 확인합니다.</p>
  </article>

  <article class="treatment-card">
    <h3>침 치료 상담</h3>
    <p>현재 증상과 전반적인 상태에 따라 필요한 경우 침 치료를 진료 방법 가운데 하나로 고려할 수 있습니다.</p>
  </article>

  <article class="treatment-card">
    <h3>한약 상담</h3>
    <p>피부 증상뿐 아니라 수면, 피로, 소화와 복용약 등을 확인한 뒤 필요한 경우 한약 상담을 진행합니다.</p>
  </article>

  <article class="treatment-card">
    <h3>생활관리 안내</h3>
    <p>세안과 보습, 수면, 과로, 자극적인 피부관리 등 현재 상태에서 조절할 부분을 함께 안내합니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section">
  <div class="container">
    <div class="safety-box">
      <h3>이런 경우에는 피부과 또는 응급 진료가 우선입니다.</h3>
      <ul>
        <li>갑자기 전신에 심한 발진이 퍼지면서 호흡곤란이나 입술·목의 붓기가 있는 경우</li>
        <li>고열과 함께 피부 통증이나 물집이 빠르게 번지는 경우</li>
        <li>상처 부위가 심하게 붓고 뜨겁거나 고름이 생기는 등 감염이 의심되는 경우</li>
        <li>갑자기 생긴 점이나 피부 병변의 모양·색·크기가 빠르게 변하는 경우</li>
        <li>눈 주변에 심한 붓기나 통증, 시야 이상이 동반되는 경우</li>
      </ul>
    </div>
  </div>
</section>

<section class="clinic-section soft">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">HOME CARE</span>
      <h2>집에서는 자극을 줄이고 변화를 기록해 보세요.</h2>
    </div>

<div class="check-list">
  <div class="check-item">
    <strong>과도한 세안 피하기</strong>
    <p>피부가 예민한 시기에는 잦은 세안이나 강한 스크럽처럼 자극이 큰 관리는 줄이는 것이 좋습니다.</p>
  </div>

  <div class="check-item">
    <strong>보습을 꾸준히 하기</strong>
    <p>건조함이 심한 경우 자극이 적은 보습제를 활용해 피부 장벽 관리에 신경 써 주세요.</p>
  </div>

  <div class="check-item">
    <strong>피부 변화를 사진으로 남기기</strong>
    <p>증상이 심한 날의 모습을 사진으로 기록하면 내원 시 변화 양상을 설명하는 데 도움이 됩니다.</p>
  </div>

  <div class="check-item">
    <strong>사용 중인 제품과 약 확인하기</strong>
    <p>화장품, 연고, 복용약을 새로 시작한 시점과 피부 변화가 겹치는지도 함께 살펴보세요.</p>
  </div>
</div>

  </div>
</section>

<section class="clinic-section" id="faq">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">FAQ</span>
      <h2>피부 클리닉 자주 묻는 질문</h2>
    </div>

<div class="faq-list">
  <article class="faq-item">
    <h3>피부과 치료를 받고 있어도 한의원에서 상담할 수 있나요?</h3>
    <p>네. 현재 받고 있는 피부과 진료와 사용하는 연고·복용약을 확인한 뒤 상담할 수 있습니다. 처방받은 약은 임의로 중단하지 않는 것이 중요합니다.</p>
  </article>

  <article class="faq-item">
    <h3>여드름이나 반복되는 피부 트러블도 상담하나요?</h3>
    <p>반복되는 피부 트러블의 시기와 위치, 수면·스트레스·식사 상태 등을 함께 확인할 수 있습니다.</p>
  </article>

  <article class="faq-item">
    <h3>가려움이 심한데 원인을 알 수 있나요?</h3>
    <p>가려움은 다양한 원인과 관련될 수 있어 시작 시점과 피부 상태, 복용약, 생활환경을 함께 확인합니다. 필요한 경우 피부과 검사가 우선될 수 있습니다.</p>
  </article>

  <article class="faq-item">
    <h3>피부 때문에 한약 상담도 가능한가요?</h3>
    <p>가능합니다. 현재 피부 증상과 수면, 소화, 피로 상태, 기존 치료 내용을 확인한 뒤 필요한 경우 상담합니다.</p>
  </article>

  <article class="faq-item">
    <h3>피부가 갑자기 붉어지고 붓는데 한의원에 가도 되나요?</h3>
    <p>호흡곤란이나 입술·목의 붓기, 전신에 빠르게 퍼지는 발진이 동반된다면 응급진료가 우선입니다.</p>
  </article>

  <article class="faq-item">
    <h3>피부 상태를 사진으로 찍어 가도 도움이 되나요?</h3>
    <p>네. 증상이 심한 날과 비교적 괜찮은 날의 사진이 있으면 변화의 양상을 확인하는 데 도움이 됩니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section" style="padding-top:0">
  <div class="container">
    <div class="clinic-cta">
      <div>
        <h2>피부가 언제부터, 어떤 상황에서 달라졌는지부터 살펴보겠습니다.</h2>
        <p>사용 중인 연고나 복용약, 최근 피부 사진이 있다면 내원 시 함께 알려주세요.</p>
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
      "name": "피부과 치료를 받고 있어도 한의원에서 상담할 수 있나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "현재 받고 있는 피부과 진료와 사용하는 연고·복용약을 확인한 뒤 상담할 수 있습니다. 처방받은 약은 임의로 중단하지 않는 것이 중요합니다."
      }
    },
    {
      "@type": "Question",
      "name": "여드름이나 반복되는 피부 트러블도 상담하나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "반복되는 피부 트러블의 시기와 위치, 수면·스트레스·식사 상태 등을 함께 확인할 수 있습니다."
      }
    },
    {
      "@type": "Question",
      "name": "가려움이 심한데 원인을 알 수 있나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "가려움은 다양한 원인과 관련될 수 있어 시작 시점과 피부 상태, 복용약, 생활환경을 함께 확인합니다. 필요한 경우 피부과 검사가 우선될 수 있습니다."
      }
    },
    {
      "@type": "Question",
      "name": "피부 때문에 한약 상담도 가능한가요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "현재 피부 증상과 수면, 소화, 피로 상태, 기존 치료 내용을 확인한 뒤 필요한 경우 상담합니다."
      }
    }
  ]
}
</script>
