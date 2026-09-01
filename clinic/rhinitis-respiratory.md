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
    max-width:800px;
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

  .resp-grid{
    display:grid;
    grid-template-columns:repeat(3,minmax(0,1fr));
    gap:18px;
  }
  .resp-card{
    padding:26px;
    border:1px solid rgba(0,0,0,.09);
    border-radius:18px;
    background:#fff;
  }
  .resp-card h3{margin:0 0 10px;font-size:1.14rem;}
  .resp-card p{margin:0;line-height:1.75;}

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
    .resp-grid{grid-template-columns:repeat(2,minmax(0,1fr));}
    .treatment-grid{grid-template-columns:repeat(2,minmax(0,1fr));}
    .clinic-cta{align-items:flex-start;flex-direction:column;}
  }
  @media (max-width:640px){
    .clinic-page-hero{padding:64px 0 48px;}
    .clinic-section{padding:56px 0;}
    .resp-grid,.check-list,.treatment-grid{grid-template-columns:1fr;}
  }
</style>

<section class="clinic-page-hero">
  <div class="container">
    <span class="clinic-kicker">RESPIRATORY CLINIC</span>
    <h1>비염·호흡기 클리닉</h1>
    <p class="clinic-lead">
      감기는 지나간 것 같은데 기침만 오래 남거나,
      <strong>몇 주째 낫지 않는 감기처럼 느껴지는 증상, 목 이물감·후비루·코막힘</strong>이 반복되는 경우가 있습니다.
      약손한의원에서는 증상이 얼마나 지속됐는지, 밤과 새벽에 심해지는지, 코·목 증상이 함께 있는지,
      기존 검사와 복용약은 무엇인지 함께 확인합니다.
    </p>
    <div class="clinic-nav" aria-label="비염·호흡기 클리닉 페이지 바로가기">
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
      <span class="eyebrow">RESPIRATORY CONCERNS</span>
      <h2>이런 호흡기 불편으로 상담합니다.</h2>
      <p>“감기가 안 낫는다”는 느낌 안에도 기침의 지속 기간, 코·목 증상, 수면과 생활환경에 따라 여러 양상이 있을 수 있습니다.</p>
    </div>

<div class="resp-grid">
  <article class="resp-card">
    <h3>만성기침·오래가는 기침</h3>
    <p>기침이 몇 주 이상 이어지거나 좋아지는 듯하다 다시 반복되는 경우, 시작 시점과 시간대·동반 증상을 함께 살펴봅니다.</p>
  </article>

  <article class="resp-card">
    <h3>감기 후 남은 잔기침</h3>
    <p>열과 콧물은 좋아졌는데 마른기침이나 목 간질거림이 오래 남는 경우 기침의 양상과 회복 과정을 확인합니다.</p>
  </article>

  <article class="resp-card">
    <h3>낫지 않는 감기처럼 느껴지는 증상</h3>
    <p>콧물·코막힘·목 불편·기침이 반복되면서 감기가 계속되는 것처럼 느껴질 때 실제 증상 패턴과 기존 진료 내용을 함께 확인합니다.</p>
  </article>

  <article class="resp-card">
    <h3>후비루·목 이물감</h3>
    <p>콧물이 목 뒤로 넘어가는 느낌, 목에 무엇이 걸린 듯한 불편, 잦은 헛기침이 있는지 살펴봅니다.</p>
  </article>

  <article class="resp-card">
    <h3>비염·코막힘</h3>
    <p>맑은 콧물, 재채기, 코막힘이 반복되고 환절기나 실내환경에 따라 심해지는지 확인합니다.</p>
  </article>

  <article class="resp-card">
    <h3>야간기침·수면 불편</h3>
    <p>누우면 기침이 심해지거나 새벽에 기침 때문에 깨고, 입호흡이나 코막힘으로 잠이 불편한 경우 수면 상태까지 함께 살펴봅니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section soft" id="check">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">CONSULTATION CHECKPOINT</span>
      <h2>기침이 얼마나 오래됐는지부터 확인합니다.</h2>
      <p>기침은 감기 이후에도 남을 수 있지만, 지속 기간과 동반 증상에 따라 다른 원인을 확인해야 할 수도 있습니다.</p>
    </div>

<div class="check-list">
  <div class="check-item">
    <strong>기침이 시작된 시점과 기간</strong>
    <p>감기 뒤 시작됐는지, 몇 주째 지속되는지, 좋아졌다 반복되는지 확인합니다.</p>
  </div>

  <div class="check-item">
    <strong>마른기침인지 가래기침인지</strong>
    <p>마른기침인지, 가래가 있는지, 가래의 양과 색에 변화가 있는지 살펴봅니다.</p>
  </div>

  <div class="check-item">
    <strong>밤·새벽·누울 때 심해지는지</strong>
    <p>특정 시간대나 자세에서 기침이 심해지는지 확인합니다.</p>
  </div>

  <div class="check-item">
    <strong>코막힘·후비루·목 불편</strong>
    <p>비염이나 후비루처럼 기침과 함께 나타나는 코·목 증상이 있는지 살펴봅니다.</p>
  </div>

  <div class="check-item">
    <strong>흉부검사·호흡기 진료 이력</strong>
    <p>흉부 X-ray, 폐기능검사, 이비인후과·호흡기내과 진료 결과가 있다면 함께 참고합니다.</p>
  </div>

  <div class="check-item">
    <strong>현재 복용 중인 약</strong>
    <p>기침약, 항히스타민제, 흡입제, 비강 스프레이 등 현재 사용 중인 약을 확인합니다.</p>
  </div>
</div>

  </div>
</section>

<section class="clinic-section">
  <div class="container">
    <div class="important-box">
      <h3>“감기가 오래간다”는 느낌이 모두 같은 원인인 것은 아닙니다.</h3>
      <p>
        감기 후 기침이 남는 경우도 있지만, 후비루·비염, 천식성 기침, 역류와 관련된 기침 등
        여러 원인이 비슷하게 느껴질 수 있습니다.
        따라서 오랫동안 지속되는 기침은 단순히 감기가 덜 나았다고 생각하기보다
        증상의 기간과 양상을 확인하고 필요한 경우 관련 검사를 받는 것이 중요합니다.
      </p>
    </div>
  </div>
</section>

<section class="clinic-section soft">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">PATTERN & APPROACH</span>
      <h2>기침의 양상에 따라 함께 살펴볼 부분이 달라집니다.</h2>
    </div>

<div class="resp-grid">
  <article class="resp-card">
    <h3>감기 후 잔기침형</h3>
    <p>감기의 다른 증상은 좋아졌지만 마른기침과 목 간질거림이 오래 이어지는 경우입니다.</p>
  </article>

  <article class="resp-card">
    <h3>후비루·비염 동반형</h3>
    <p>코막힘과 콧물, 목 뒤로 넘어가는 느낌이 있으면서 헛기침이나 기침이 반복되는 경우입니다.</p>
  </article>

  <article class="resp-card">
    <h3>야간·새벽 기침형</h3>
    <p>밤에 눕거나 새벽에 기침이 심해지고 수면을 방해하는 경우에는 호흡기 상태와 수면환경을 함께 확인합니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section" id="treatment">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">CARE</span>
      <h2>현재 증상과 기존 진료 내용을 확인한 뒤 진료 방향을 상의합니다.</h2>
      <p>기침의 기간과 원인이 다양할 수 있어 모든 분에게 같은 진료를 적용하지 않습니다.</p>
    </div>

<div class="treatment-grid">
  <article class="treatment-card">
    <h3>증상 경과 확인</h3>
    <p>감기 시작부터 현재까지 어떤 증상이 좋아지고 무엇이 남았는지 시간의 흐름을 살펴봅니다.</p>
  </article>

  <article class="treatment-card">
    <h3>침 치료 상담</h3>
    <p>현재 코·목·호흡기 불편과 전반적인 상태에 따라 필요한 경우 침 치료를 진료 방법 가운데 하나로 고려할 수 있습니다.</p>
  </article>

  <article class="treatment-card">
    <h3>한약 상담</h3>
    <p>기침의 양상과 수면, 식사, 피로, 기존 복용약을 확인한 뒤 필요한 경우 한약을 상담합니다.</p>
  </article>

  <article class="treatment-card">
    <h3>생활환경 안내</h3>
    <p>실내 건조함, 먼지, 수면환경, 목을 자극하는 습관 등 일상에서 조절해 볼 부분을 안내합니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section soft">
  <div class="container">
    <div class="safety-box">
      <h3>이런 경우에는 호흡기내과·이비인후과 또는 응급 진료가 우선입니다.</h3>
      <ul>
        <li>호흡곤란이나 쌕쌕거림이 심한 경우</li>
        <li>흉통이나 객혈이 있는 경우</li>
        <li>고열이 지속되거나 전신 상태가 빠르게 나빠지는 경우</li>
        <li>기침이 오래 지속되면서 이유 없는 체중 감소가 있는 경우</li>
        <li>입술이 파래지거나 의식이 흐려지는 등 응급 증상이 있는 경우</li>
      </ul>
    </div>
  </div>
</section>

<section class="clinic-section">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">HOME CARE</span>
      <h2>집에서는 기침의 패턴을 기록해 보세요.</h2>
    </div>

<div class="check-list">
  <div class="check-item">
    <strong>기침이 심한 시간 기록하기</strong>
    <p>아침, 낮, 밤, 새벽 중 언제 심한지 기록하면 기침의 양상을 이해하는 데 도움이 됩니다.</p>
  </div>

  <div class="check-item">
    <strong>코·목 증상 같이 기록하기</strong>
    <p>코막힘, 콧물, 후비루, 목 이물감이 기침과 함께 나타나는지 살펴보세요.</p>
  </div>

  <div class="check-item">
    <strong>실내 건조함과 자극 줄이기</strong>
    <p>지나치게 건조한 환경과 담배연기·향·먼지 등 기침을 자극하는 요인을 줄이는 것이 좋습니다.</p>
  </div>

  <div class="check-item">
    <strong>검사자료와 복용약 챙기기</strong>
    <p>흉부 X-ray나 다른 검사 결과, 현재 복용 중인 기침약과 흡입제 등이 있다면 내원 시 알려주세요.</p>
  </div>
</div>

  </div>
</section>

<section class="clinic-section soft" id="faq">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">FAQ</span>
      <h2>비염·호흡기 클리닉 자주 묻는 질문</h2>
    </div>

<div class="faq-list">
  <article class="faq-item">
    <h3>감기는 다 나은 것 같은데 기침만 계속돼요.</h3>
    <p>감기 후 기침이 한동안 남는 경우가 있습니다. 다만 기침이 오래 지속되거나 밤에 심하고 호흡곤란 등 다른 증상이 있다면 관련 검사가 필요할 수 있어 지속 기간과 동반 증상을 확인합니다.</p>
  </article>

  <article class="faq-item">
    <h3>몇 주째 감기가 안 낫는 것 같은데 상담할 수 있나요?</h3>
    <p>네. 실제로 감기가 계속되는 것인지, 비염·후비루·기침 등 일부 증상이 반복되는 것인지 구분하기 위해 증상의 시작과 변화 과정을 함께 살펴봅니다.</p>
  </article>

  <article class="faq-item">
    <h3>기침이 3주 이상 계속되면 검사를 받아야 하나요?</h3>
    <p>기침의 지속 기간과 동반 증상에 따라 흉부 X-ray나 폐기능검사 등 관련 검사가 도움이 될 수 있습니다. 특히 흉통, 객혈, 호흡곤란, 체중 감소 등이 있다면 의료기관 평가가 우선입니다.</p>
  </article>

  <article class="faq-item">
    <h3>후비루 때문에 기침이 날 수도 있나요?</h3>
    <p>목 뒤로 분비물이 넘어가는 느낌이 기침이나 헛기침과 함께 나타나는 경우가 있습니다. 코막힘과 비염 증상도 함께 확인합니다.</p>
  </article>

  <article class="faq-item">
    <h3>밤에만 기침이 심한 이유는 뭔가요?</h3>
    <p>누운 자세, 후비루, 호흡기 과민, 역류 등 여러 원인이 관련될 수 있어 다른 증상과 함께 살펴보는 것이 중요합니다.</p>
  </article>

  <article class="faq-item">
    <h3>기침약을 먹고 있어도 상담할 수 있나요?</h3>
    <p>가능합니다. 현재 복용 중인 약과 흡입제, 비강 스프레이 등이 있다면 알려주세요. 처방받은 약은 임의로 중단하지 않는 것이 중요합니다.</p>
  </article>

  <article class="faq-item">
    <h3>아이도 감기와 기침이 자주 반복되는데 상담 가능한가요?</h3>
    <p>가능합니다. 연령과 증상 기간, 수면, 식사, 생활환경을 함께 확인합니다. 소아에서 호흡이 가쁘거나 처짐, 고열이 지속되는 경우에는 소아청소년과 평가가 우선입니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section" style="padding-top:0">
  <div class="container">
    <div class="clinic-cta">
      <div>
        <h2>기침이 언제 시작됐고 무엇이 아직 남아 있는지부터 살펴보겠습니다.</h2>
        <p>현재 복용약과 흉부검사 등 기존 자료가 있다면 내원 시 함께 알려주세요.</p>
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
      "name": "감기는 다 나은 것 같은데 기침만 계속돼요.",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "감기 후 기침이 한동안 남는 경우가 있습니다. 다만 기침이 오래 지속되거나 밤에 심하고 호흡곤란 등 다른 증상이 있다면 관련 검사가 필요할 수 있어 지속 기간과 동반 증상을 확인합니다."
      }
    },
    {
      "@type": "Question",
      "name": "몇 주째 감기가 안 낫는 것 같은데 상담할 수 있나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "실제로 감기가 계속되는 것인지, 비염·후비루·기침 등 일부 증상이 반복되는 것인지 구분하기 위해 증상의 시작과 변화 과정을 함께 살펴봅니다."
      }
    },
    {
      "@type": "Question",
      "name": "기침이 3주 이상 계속되면 검사를 받아야 하나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "기침의 지속 기간과 동반 증상에 따라 흉부 X-ray나 폐기능검사 등 관련 검사가 도움이 될 수 있습니다. 특히 흉통, 객혈, 호흡곤란, 체중 감소 등이 있다면 의료기관 평가가 우선입니다."
      }
    },
    {
      "@type": "Question",
      "name": "후비루 때문에 기침이 날 수도 있나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "목 뒤로 분비물이 넘어가는 느낌이 기침이나 헛기침과 함께 나타나는 경우가 있습니다. 코막힘과 비염 증상도 함께 확인합니다."
      }
    },
    {
      "@type": "Question",
      "name": "밤에만 기침이 심한 이유는 뭔가요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "누운 자세, 후비루, 호흡기 과민, 역류 등 여러 원인이 관련될 수 있어 다른 증상과 함께 살펴보는 것이 중요합니다."
      }
    }
  ]
}
</script>
