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

  .diet-grid{
    display:grid;
    grid-template-columns:repeat(3,minmax(0,1fr));
    gap:18px;
  }
  .diet-card{
    padding:26px;
    border:1px solid rgba(0,0,0,.09);
    border-radius:18px;
    background:#fff;
  }
  .diet-card h3{margin:0 0 10px;font-size:1.14rem;}
  .diet-card p{margin:0;line-height:1.75;}

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

  .care-grid{
    display:grid;
    grid-template-columns:repeat(4,minmax(0,1fr));
    gap:16px;
  }
  .care-card{
    padding:24px;
    border-radius:16px;
    background:#fff;
    border:1px solid rgba(0,0,0,.08);
  }
  .care-card h3{margin:0 0 10px;}
  .care-card p{margin:0;line-height:1.75;}

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
    .diet-grid{grid-template-columns:repeat(2,minmax(0,1fr));}
    .care-grid{grid-template-columns:repeat(2,minmax(0,1fr));}
    .clinic-cta{align-items:flex-start;flex-direction:column;}
  }
  @media (max-width:640px){
    .clinic-page-hero{padding:64px 0 48px;}
    .clinic-section{padding:56px 0;}
    .diet-grid,.check-list,.care-grid{grid-template-columns:1fr;}
  }
</style>

<section class="clinic-page-hero">
  <div class="container">
    <span class="clinic-kicker">WEIGHT MANAGEMENT CLINIC</span>
    <h1>다이어트 클리닉</h1>
    <p class="clinic-lead">
      체중관리는 단순히 적게 먹는 것만으로 해결되지 않는 경우가 많습니다.
      <strong>식사량과 야식·간식, 수면, 스트레스, 소화, 활동량과 최근 체중 변화</strong>를 함께 살펴보고
      무리하지 않으면서 지속할 수 있는 체중관리 방향을 상담합니다.
    </p>

<div class="clinic-nav" aria-label="다이어트 클리닉 페이지 바로가기">
  <a href="#concerns">주요 고민</a>
  <a href="#check">진료 시 확인</a>
  <a href="#care">관리 방향</a>
  <a href="#faq">자주 묻는 질문</a>
</div>

  </div>
</section>

<section class="clinic-section" id="concerns">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">WEIGHT CONCERNS</span>
      <h2>이런 체중관리 고민으로 상담합니다.</h2>
      <p>체중 숫자 하나보다 왜 체중이 늘었는지, 어떤 생활패턴이 반복되는지를 함께 살펴봅니다.</p>
    </div>

<div class="diet-grid">
  <article class="diet-card">
    <h3>최근 체중이 계속 늘어난 경우</h3>
    <p>최근 몇 개월 사이 체중이 늘었거나 이전과 같은 생활을 해도 체중이 쉽게 증가하는 경우 변화 시점과 생활환경을 확인합니다.</p>
  </article>

  <article class="diet-card">
    <h3>야식·간식이 반복되는 경우</h3>
    <p>낮에는 적게 먹다가 저녁이나 밤에 식사량이 늘거나 간식과 배달음식이 반복되는 패턴을 살펴봅니다.</p>
  </article>

  <article class="diet-card">
    <h3>스트레스 받을 때 많이 먹는 경우</h3>
    <p>배가 고프지 않아도 긴장이나 스트레스 후 음식이 당기거나 먹는 양을 조절하기 어려운지 확인합니다.</p>
  </article>

  <article class="diet-card">
    <h3>식후 더부룩함이 있으면서 체중도 고민인 경우</h3>
    <p>소화불편 때문에 식사패턴이 불규칙하거나 배가 더부룩하고 붓는 느낌이 함께 있는지 살펴봅니다.</p>
  </article>

  <article class="diet-card">
    <h3>수면 부족과 함께 체중이 늘어난 경우</h3>
    <p>늦게 자고 수면시간이 부족하면서 야식이나 식욕 변화가 함께 나타나는지 확인합니다.</p>
  </article>

  <article class="diet-card">
    <h3>여러 번 감량했다가 다시 늘어난 경우</h3>
    <p>짧은 기간에 무리하게 감량한 뒤 다시 체중이 늘기를 반복했다면 이전 다이어트 방식과 생활패턴을 함께 살펴봅니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section soft" id="check">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">CONSULTATION CHECKPOINT</span>
      <h2>다이어트 상담에서는 이런 부분을 확인합니다.</h2>
      <p>무조건 식사량을 줄이기보다 현재 체중과 식습관, 수면과 건강상태를 먼저 확인합니다.</p>
    </div>

<div class="check-list">
  <div class="check-item">
    <strong>최근 체중 변화</strong>
    <p>최근 6개월~1년 동안 체중이 어떻게 변했는지, 언제부터 증가했는지 살펴봅니다.</p>
  </div>

  <div class="check-item">
    <strong>식사시간과 식사량</strong>
    <p>아침을 거르는지, 점심·저녁의 식사량이 어떤지, 한 끼에 과식하는 경향이 있는지 확인합니다.</p>
  </div>

  <div class="check-item">
    <strong>야식·간식·음료</strong>
    <p>늦은 야식과 간식, 단 음료나 커피 등에 들어가는 열량 섭취가 반복되는지 살펴봅니다.</p>
  </div>

  <div class="check-item">
    <strong>수면과 스트레스</strong>
    <p>잠이 부족하거나 스트레스가 심할 때 식욕과 식사량이 달라지는지 확인합니다.</p>
  </div>

  <div class="check-item">
    <strong>소화·배변 상태</strong>
    <p>더부룩함, 변비·묽은 변, 식후 불편처럼 식사와 관련된 증상이 있는지 살펴봅니다.</p>
  </div>

  <div class="check-item">
    <strong>기존 질환과 복용약</strong>
    <p>갑상선 질환, 당뇨, 고혈압 등 기존 질환과 현재 복용 중인 약이 있다면 함께 확인합니다.</p>
  </div>
</div>

  </div>
</section>

<section class="clinic-section">
  <div class="container">
    <div class="important-box">
      <h3>빠르게 빼는 것보다 다시 돌아가지 않는 생활을 만드는 것이 중요합니다.</h3>
      <p>
        지나친 절식이나 한 가지 음식만 먹는 방식은 오래 유지하기 어렵고,
        피로·어지럼·근손실·과식의 반복으로 이어질 수 있습니다.
        체중 감량 속도와 목표는 현재 체중, 건강상태와 생활환경에 따라 달라질 수 있으므로
        현실적으로 지속할 수 있는 방향을 함께 정하는 것이 좋습니다.
      </p>
    </div>
  </div>
</section>

<section class="clinic-section soft">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">PATTERN & APPROACH</span>
      <h2>체중이 늘어나는 흐름도 사람마다 다릅니다.</h2>
    </div>

<div class="diet-grid">
  <article class="diet-card">
    <h3>야식·과식형</h3>
    <p>낮에는 식사를 거르거나 적게 먹고 저녁과 밤에 식사량이 크게 늘어나는 경우입니다.</p>
  </article>

  <article class="diet-card">
    <h3>스트레스·수면부족형</h3>
    <p>스트레스와 수면 부족이 반복되면서 음식이 당기고 식사 조절이 어려워지는 경우입니다.</p>
  </article>

  <article class="diet-card">
    <h3>활동량 저하형</h3>
    <p>운동량이나 일상 활동이 줄었는데 식사량은 비슷하게 유지되면서 체중이 늘어난 경우입니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section" id="care">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">CARE</span>
      <h2>현재 상태에 맞춰 체중관리 방향을 상의합니다.</h2>
      <p>모든 분에게 같은 목표와 방법을 적용하지 않고 식사와 생활패턴, 건강상태를 확인한 뒤 필요한 방향을 설명합니다.</p>
    </div>

<div class="care-grid">
  <article class="care-card">
    <h3>식사패턴 확인</h3>
    <p>끼니와 간식, 야식, 과식이 반복되는 시간대를 확인하고 조절할 부분을 함께 찾습니다.</p>
  </article>

  <article class="care-card">
    <h3>한약 상담</h3>
    <p>현재 건강상태와 식욕, 수면·소화, 기존 복용약을 확인한 뒤 필요한 경우 체중관리를 위한 한약 상담을 진행합니다.</p>
  </article>

  <article class="care-card">
    <h3>활동량·운동 확인</h3>
    <p>현재 운동 여부와 일상 활동량을 확인하고 무리 없이 지속할 수 있는 방향을 함께 살펴봅니다.</p>
  </article>

  <article class="care-card">
    <h3>생활관리 안내</h3>
    <p>수면시간, 외식·야식, 음료, 주말 식사처럼 체중 변화에 영향을 주는 생활습관을 점검합니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section soft">
  <div class="container">
    <div class="safety-box">
      <h3>이런 경우에는 체중감량보다 관련 진료나 평가가 우선입니다.</h3>
      <ul>
        <li>임신·수유 중이거나 임신을 준비 중인 경우</li>
        <li>청소년 등 성장기에 체중감량을 고려하는 경우</li>
        <li>갑작스럽고 이유 없는 체중 증가 또는 체중 감소가 있는 경우</li>
        <li>폭식 후 구토, 극단적인 절식 등 섭식문제가 의심되는 경우</li>
        <li>심한 어지럼·실신·두근거림 등 전신 증상이 있는 경우</li>
      </ul>
    </div>
  </div>
</section>

<section class="clinic-section">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">HOME CARE</span>
      <h2>집에서는 체중보다 생활패턴부터 기록해 보세요.</h2>
    </div>

<div class="check-list">
  <div class="check-item">
    <strong>식사시간 기록하기</strong>
    <p>무엇을 먹었는지만 적기보다 언제 먹었는지, 야식과 간식이 언제 반복되는지 확인해 보세요.</p>
  </div>

  <div class="check-item">
    <strong>공복이 너무 길어지지 않게</strong>
    <p>오랫동안 굶은 뒤 한 번에 많이 먹는 패턴이 반복된다면 식사 간격을 살펴보는 것이 좋습니다.</p>
  </div>

  <div class="check-item">
    <strong>수면시간 함께 기록하기</strong>
    <p>잠이 부족한 날 식욕이나 야식이 어떻게 달라지는지 함께 살펴보세요.</p>
  </div>

  <div class="check-item">
    <strong>매일의 숫자에만 매달리지 않기</strong>
    <p>체중은 수분과 식사, 배변 등에 따라 변할 수 있어 생활습관의 변화를 함께 보는 것이 중요합니다.</p>
  </div>
</div>

  </div>
</section>

<section class="clinic-section soft" id="faq">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">FAQ</span>
      <h2>다이어트 클리닉 자주 묻는 질문</h2>
    </div>

<div class="faq-list">
  <article class="faq-item">
    <h3>한약만 먹으면 살이 빠지나요?</h3>
    <p>한약만으로 체중감량이 보장되는 것은 아닙니다. 식사와 활동량, 수면, 스트레스 등 생활요인을 함께 조절하는 것이 중요하며 필요한 경우 한약을 상담합니다.</p>
  </article>

  <article class="faq-item">
    <h3>얼마나 빨리 빼는 게 좋나요?</h3>
    <p>적절한 감량 속도는 현재 체중과 건강상태에 따라 다릅니다. 무리하게 빠른 감량을 목표로 하기보다 지속할 수 있는 범위를 정하는 것이 중요합니다.</p>
  </article>

  <article class="faq-item">
    <h3>야식을 끊기 너무 어려워요.</h3>
    <p>낮 동안 식사량이 너무 적지는 않은지, 수면과 스트레스가 야식과 연결되는지 먼저 살펴봅니다.</p>
  </article>

  <article class="faq-item">
    <h3>소화가 약한데 다이어트 한약을 먹어도 되나요?</h3>
    <p>더부룩함이나 속쓰림 등 소화불편이 있다면 현재 상태를 먼저 확인해야 합니다. 소화 상태와 기존 복용약을 고려해 개별적으로 상담합니다.</p>
  </article>

  <article class="faq-item">
    <h3>혈압약이나 당뇨약을 먹고 있어도 상담 가능한가요?</h3>
    <p>가능하지만 현재 복용약과 검사 결과를 반드시 알려주세요. 처방받은 약은 임의로 중단하거나 변경하지 않는 것이 중요합니다.</p>
  </article>

  <article class="faq-item">
    <h3>출산 후 체중이 안 빠져요.</h3>
    <p>출산 후에는 회복과 수유 여부, 수면 부족, 식사패턴을 함께 고려해야 합니다. 특히 수유 중이라면 체중감량보다 회복과 영양 상태를 우선 확인합니다.</p>
  </article>

  <article class="faq-item">
    <h3>중학생이나 고등학생도 다이어트 상담을 하나요?</h3>
    <p>성장기에는 체중 숫자만을 목표로 감량하는 접근을 권하지 않습니다. 성장과 영양상태, 필요 시 소아청소년과 평가를 우선 고려합니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section" style="padding-top:0">
  <div class="container">
    <div class="clinic-cta">
      <div>
        <h2>무엇을 덜 먹을지보다, 왜 체중이 늘었는지부터 살펴보겠습니다.</h2>
        <p>최근 체중 변화와 복용약, 건강검진 결과가 있다면 내원 시 함께 알려주세요.</p>
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
      "name": "한약만 먹으면 살이 빠지나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "한약만으로 체중감량이 보장되는 것은 아닙니다. 식사와 활동량, 수면, 스트레스 등 생활요인을 함께 조절하는 것이 중요하며 필요한 경우 한약을 상담합니다."
      }
    },
    {
      "@type": "Question",
      "name": "얼마나 빨리 빼는 게 좋나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "적절한 감량 속도는 현재 체중과 건강상태에 따라 다릅니다. 무리하게 빠른 감량을 목표로 하기보다 지속할 수 있는 범위를 정하는 것이 중요합니다."
      }
    },
    {
      "@type": "Question",
      "name": "야식을 끊기 너무 어려워요.",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "낮 동안 식사량이 너무 적지는 않은지, 수면과 스트레스가 야식과 연결되는지 먼저 살펴봅니다."
      }
    },
    {
      "@type": "Question",
      "name": "출산 후 체중이 안 빠져요.",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "출산 후에는 회복과 수유 여부, 수면 부족, 식사패턴을 함께 고려해야 합니다. 특히 수유 중이라면 체중감량보다 회복과 영양 상태를 우선 확인합니다."
      }
    },
    {
      "@type": "Question",
      "name": "중학생이나 고등학생도 다이어트 상담을 하나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "성장기에는 체중 숫자만을 목표로 감량하는 접근을 권하지 않습니다. 성장과 영양상태, 필요 시 소아청소년과 평가를 우선 고려합니다."
      }
    }
  ]
}
</script>
