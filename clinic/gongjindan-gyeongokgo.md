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

  .product-grid{
    display:grid;
    grid-template-columns:repeat(2,minmax(0,1fr));
    gap:18px;
  }
  .product-card{
    padding:30px;
    border:1px solid rgba(0,0,0,.09);
    border-radius:18px;
    background:#fff;
  }
  .product-card h3{
    margin:0 0 12px;
    font-size:1.35rem;
  }
  .product-card p{margin:0;line-height:1.8;}

  .reason-grid{
    display:grid;
    grid-template-columns:repeat(3,minmax(0,1fr));
    gap:18px;
  }
  .reason-card{
    padding:26px;
    border:1px solid rgba(0,0,0,.09);
    border-radius:18px;
    background:#fff;
  }
  .reason-card h3{margin:0 0 10px;font-size:1.14rem;}
  .reason-card p{margin:0;line-height:1.75;}

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
  .related-box h3{margin:0 0 8px;}
  .related-box p{margin:0;line-height:1.7;}

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
    .reason-grid{grid-template-columns:repeat(2,minmax(0,1fr));}
    .care-grid{grid-template-columns:repeat(2,minmax(0,1fr));}
    .clinic-cta,.related-box{align-items:flex-start;flex-direction:column;}
  }
  @media (max-width:640px){
    .clinic-page-hero{padding:64px 0 48px;}
    .clinic-section{padding:56px 0;}
    .product-grid,.reason-grid,.check-list,.care-grid{grid-template-columns:1fr;}
  }
</style>

<section class="clinic-page-hero">
  <div class="container">
    <span class="clinic-kicker">GONGJINDAN & GYEONGOKGO</span>
    <h1>공진단·경옥고 클리닉</h1>
    <p class="clinic-lead">
      공진단과 경옥고는 이름이나 선물용 이미지로만 선택하기보다
      <strong>누가, 어떤 목적으로 복용하려는지와 현재의 건강상태</strong>를 먼저 확인하는 것이 중요합니다.
      약손한의원에서는 피로와 수면·식사·소화 상태, 기존 질환과 복용약을 함께 살펴본 뒤
      현재 상태에 적합한지 상담합니다.
    </p>

<div class="clinic-nav" aria-label="공진단·경옥고 클리닉 페이지 바로가기">
  <a href="#choice">공진단·경옥고</a>
  <a href="#reasons">상담하는 경우</a>
  <a href="#check">복용 전 확인</a>
  <a href="#care">상담 과정</a>
  <a href="#faq">자주 묻는 질문</a>
</div>

  </div>
</section>

<section class="clinic-section" id="choice">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">GONGJINDAN & GYEONGOKGO</span>
      <h2>무엇이 더 유명한가보다 나에게 맞는지가 중요합니다.</h2>
      <p>공진단과 경옥고는 제형과 처방 구성이 다르며 복용 목적과 현재 몸 상태에 따라 상담 방향도 달라질 수 있습니다.</p>
    </div>

<div class="product-grid">
  <article class="product-card">
    <h3>공진단 상담</h3>
    <p>
      과로와 일정이 이어져 체력 소모가 크거나 중요한 일정 전 컨디션 관리,
      부모님 건강선물 등으로 공진단을 찾는 경우가 있습니다.
      현재 피로와 수면·소화 상태, 기존 질환과 복용약을 먼저 확인한 뒤 복용 적합성을 상담합니다.
    </p>
  </article>

  <article class="product-card">
    <h3>경옥고 상담</h3>
    <p>
      평소 체력과 컨디션 관리, 회복이 더딘 느낌 등으로 경옥고를 찾는 경우가 있습니다.
      연령과 식사·소화 상태, 평소 건강상태와 복용 목적을 확인하고
      현재 복용 중인 약과 함께 고려해야 할 부분을 상담합니다.
    </p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section soft" id="reasons">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">CONSULTATION REASONS</span>
      <h2>이런 이유로 공진단·경옥고를 문의합니다.</h2>
      <p>같은 제품을 찾더라도 복용하는 이유가 다르기 때문에 목적부터 확인합니다.</p>
    </div>

<div class="reason-grid">
  <article class="reason-card">
    <h3>과로 뒤 회복이 더딘 경우</h3>
    <p>일이나 운동, 일정이 이어진 뒤 충분히 쉬어도 컨디션이 쉽게 돌아오지 않는 경우입니다.</p>
  </article>

  <article class="reason-card">
    <h3>체력 소모가 큰 시기</h3>
    <p>업무와 출장, 훈련 등 활동량이 많아 평소보다 체력 소모가 크게 느껴지는 시기에 상담합니다.</p>
  </article>

  <article class="reason-card">
    <h3>중요한 시험·일정을 앞둔 경우</h3>
    <p>시험이나 중요한 일정 전 컨디션 관리 목적으로 찾을 때 현재 수면과 피로 상태를 함께 확인합니다.</p>
  </article>

  <article class="reason-card">
    <h3>부모님 건강선물 상담</h3>
    <p>선물용이라도 복용할 분의 연령과 건강상태, 만성질환과 복용약을 확인하는 것이 중요합니다.</p>
  </article>

  <article class="reason-card">
    <h3>평소 체력 관리가 필요한 경우</h3>
    <p>특별히 아픈 곳은 없지만 쉽게 지치거나 일상적인 컨디션 관리에 대해 상담하고 싶은 경우입니다.</p>
  </article>

  <article class="reason-card">
    <h3>보약과 무엇이 다른지 궁금한 경우</h3>
    <p>일반적인 개인별 한약 상담과 공진단·경옥고의 차이가 궁금할 때 현재 목적에 맞춰 설명합니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section">
  <div class="container">
    <div class="important-box">
      <h3>“몸에 좋다더라”보다 복용하는 분의 현재 상태가 먼저입니다.</h3>
      <p>
        공진단이나 경옥고도 모든 사람에게 같은 방식으로 권할 수 있는 것은 아닙니다.
        특히 만성질환으로 치료 중이거나 여러 약을 복용하고 있다면
        복용자의 건강상태와 기존 치료 내용을 먼저 확인하는 것이 중요합니다.
        선물용인 경우에도 가능하면 실제 복용할 분의 건강정보를 확인한 뒤 상담하는 것을 권합니다.
      </p>
    </div>
  </div>
</section>

<section class="clinic-section soft" id="check">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">BEFORE TAKING</span>
      <h2>공진단·경옥고 상담 전에 이런 점을 확인합니다.</h2>
      <p>복용 목적뿐 아니라 현재 건강상태와 기존 치료를 함께 고려합니다.</p>
    </div>

<div class="check-list">
  <div class="check-item">
    <strong>복용하려는 이유</strong>
    <p>피로와 회복, 평소 체력관리, 중요한 일정, 선물 등 무엇을 기대하고 찾는지 확인합니다.</p>
  </div>

  <div class="check-item">
    <strong>현재 피로와 수면 상태</strong>
    <p>얼마나 피곤한지, 충분히 쉬면 회복되는지, 잠들기와 수면 유지에 불편은 없는지 살펴봅니다.</p>
  </div>

  <div class="check-item">
    <strong>식욕·소화 상태</strong>
    <p>식사량과 소화불편, 더부룩함 등 평소 위장 상태를 함께 확인합니다.</p>
  </div>

  <div class="check-item">
    <strong>고혈압·당뇨 등 기존 질환</strong>
    <p>현재 진단받아 치료 중인 질환이 있다면 반드시 알려주세요.</p>
  </div>

  <div class="check-item">
    <strong>처방약·건강기능식품</strong>
    <p>현재 복용 중인 약과 영양제, 건강기능식품 등을 확인합니다.</p>
  </div>

  <div class="check-item">
    <strong>과거 보약 복용 경험</strong>
    <p>공진단·경옥고나 다른 한약을 복용했을 때 불편이나 알레르기 반응이 있었는지 확인합니다.</p>
  </div>
</div>

  </div>
</section>

<section class="clinic-section" id="care">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">CARE</span>
      <h2>이런 순서로 상담합니다.</h2>
      <p>제품부터 정하기보다 복용 목적과 몸 상태를 먼저 확인합니다.</p>
    </div>

<div class="care-grid">
  <article class="care-card">
    <h3>01 복용 목적 확인</h3>
    <p>누가 복용할지, 왜 공진단 또는 경옥고를 찾는지 먼저 확인합니다.</p>
  </article>

  <article class="care-card">
    <h3>02 현재 상태 확인</h3>
    <p>피로와 수면, 식욕·소화, 활동량과 기존 건강상태를 살펴봅니다.</p>
  </article>

  <article class="care-card">
    <h3>03 적합성 상담</h3>
    <p>기존 질환과 복용약을 고려해 현재 상태에 적합한지 상담합니다.</p>
  </article>

  <article class="care-card">
    <h3>04 복용 안내</h3>
    <p>선택한 처방에 따라 복용 방법과 기간, 보관 시 확인할 점을 안내합니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section soft">
  <div class="container">
    <div class="safety-box">
      <h3>상담 전에 반드시 알려주세요.</h3>
      <ul>
        <li>임신 또는 수유 중이거나 임신을 준비 중인 경우</li>
        <li>고혈압·당뇨·심혈관질환 등 만성질환으로 치료 중인 경우</li>
        <li>항응고제 등 처방약을 포함해 여러 약을 복용하고 있는 경우</li>
        <li>과거 한약이나 특정 약재 복용 후 알레르기 또는 이상반응이 있었던 경우</li>
        <li>선물용이지만 실제 복용할 분의 건강상태와 복용약을 정확히 모르는 경우</li>
      </ul>
    </div>
  </div>
</section>

<section class="clinic-section">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">BEFORE VISIT</span>
      <h2>상담 전에 준비하면 좋은 내용입니다.</h2>
    </div>

<div class="check-list">
  <div class="check-item">
    <strong>복용 목적 정리하기</strong>
    <p>피로·회복 관리인지, 평소 컨디션 관리인지, 중요한 일정이나 선물 때문인지 알려주세요.</p>
  </div>

  <div class="check-item">
    <strong>현재 복용약 확인하기</strong>
    <p>처방약과 건강기능식품을 메모하거나 약 봉투·처방전을 가져오면 도움이 됩니다.</p>
  </div>

  <div class="check-item">
    <strong>최근 건강검진 확인하기</strong>
    <p>최근 혈액검사나 건강검진 결과가 있다면 현재 상태를 살펴보는 데 참고할 수 있습니다.</p>
  </div>

  <div class="check-item">
    <strong>선물이라면 복용자 정보 확인하기</strong>
    <p>연령과 현재 치료 중인 질환, 복용약을 미리 알아두면 상담에 도움이 됩니다.</p>
  </div>
</div>

  </div>
</section>

<section class="clinic-section soft">
  <div class="container">
    <div class="related-box">
      <div>
        <h3>피로와 시림·열감 등 현재 몸 상태를 더 자세히 상담하고 싶으신가요?</h3>
        <p>쉽게 지치는 피로, 회복 저하, 손발이나 신체 일부의 시림·열감은 보약·체력회복 클리닉에서 개인별 상태를 더 자세히 살펴봅니다.</p>
      </div>
      <a class="button secondary" href="{{ '/clinic/tonic/' | relative_url }}">보약·체력회복 클리닉 보기</a>
    </div>
  </div>
</section>

<section class="clinic-section" id="faq">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">FAQ</span>
      <h2>공진단·경옥고 클리닉 자주 묻는 질문</h2>
    </div>

<div class="faq-list">
  <article class="faq-item">
    <h3>공진단과 경옥고 중 어떤 것이 더 좋은가요?</h3>
    <p>어느 하나가 누구에게나 더 좋다고 말하기는 어렵습니다. 복용 목적과 현재 건강상태, 식사·소화, 기존 질환과 복용약 등을 확인한 뒤 상담하는 것이 좋습니다.</p>
  </article>

  <article class="faq-item">
    <h3>공진단은 누구나 먹어도 되나요?</h3>
    <p>누구에게나 일률적으로 권하지 않습니다. 현재 건강상태와 복용약, 알레르기 경험 등을 확인한 뒤 적합성을 상담합니다.</p>
  </article>

  <article class="faq-item">
    <h3>경옥고는 오래 먹어도 되나요?</h3>
    <p>복용 목적과 처방 형태, 현재 건강상태에 따라 복용 방법과 기간이 달라질 수 있어 상담 후 안내받는 것이 좋습니다.</p>
  </article>

  <article class="faq-item">
    <h3>혈압약이나 당뇨약을 먹고 있어도 괜찮나요?</h3>
    <p>복용 중인 약의 종류와 현재 상태를 먼저 확인해야 합니다. 처방받은 약은 임의로 중단하지 말고 상담 시 반드시 알려주세요.</p>
  </article>

  <article class="faq-item">
    <h3>부모님 선물로 바로 준비할 수 있나요?</h3>
    <p>선물용이라도 실제 복용자의 연령과 질환, 복용약에 따라 확인할 점이 달라질 수 있어 가능하면 건강상태를 알고 상담하는 것이 좋습니다.</p>
  </article>

  <article class="faq-item">
    <h3>시험을 앞둔 학생도 상담할 수 있나요?</h3>
    <p>가능합니다. 수면 부족과 식사, 피로 정도, 현재 복용 중인 약이나 건강기능식품 등을 함께 확인합니다.</p>
  </article>

  <article class="faq-item">
    <h3>공진단·경옥고와 일반 보약은 어떻게 다른가요?</h3>
    <p>공진단과 경옥고는 정해진 처방 형태를 바탕으로 복용 적합성을 상담하는 반면, 일반적인 보약 상담은 현재 증상과 상태에 따라 개인별 한약 처방을 고려할 수 있다는 점에서 상담 방향이 다를 수 있습니다.</p>
  </article>

  <article class="faq-item">
    <h3>건강검진 결과를 가져가도 되나요?</h3>
    <p>네. 최근 건강검진이나 혈액검사 결과와 현재 복용약 정보가 있으면 상담에 도움이 됩니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section" style="padding-top:0">
  <div class="container">
    <div class="clinic-cta">
      <div>
        <h2>누가, 어떤 목적으로 복용하는지부터 확인하겠습니다.</h2>
        <p>현재 복용약과 기존 질환, 최근 건강검진 결과가 있다면 상담 시 함께 알려주세요.</p>
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
      "name": "공진단과 경옥고 중 어떤 것이 더 좋은가요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "어느 하나가 누구에게나 더 좋다고 말하기는 어렵습니다. 복용 목적과 현재 건강상태, 식사·소화, 기존 질환과 복용약 등을 확인한 뒤 상담하는 것이 좋습니다."
      }
    },
    {
      "@type": "Question",
      "name": "공진단은 누구나 먹어도 되나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "누구에게나 일률적으로 권하지 않습니다. 현재 건강상태와 복용약, 알레르기 경험 등을 확인한 뒤 적합성을 상담합니다."
      }
    },
    {
      "@type": "Question",
      "name": "경옥고는 오래 먹어도 되나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "복용 목적과 처방 형태, 현재 건강상태에 따라 복용 방법과 기간이 달라질 수 있어 상담 후 안내받는 것이 좋습니다."
      }
    },
    {
      "@type": "Question",
      "name": "혈압약이나 당뇨약을 먹고 있어도 괜찮나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "복용 중인 약의 종류와 현재 상태를 먼저 확인해야 합니다. 처방받은 약은 임의로 중단하지 말고 상담 시 반드시 알려주세요."
      }
    },
    {
      "@type": "Question",
      "name": "부모님 선물로 바로 준비할 수 있나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "선물용이라도 실제 복용자의 연령과 질환, 복용약에 따라 확인할 점이 달라질 수 있어 가능하면 건강상태를 알고 상담하는 것이 좋습니다."
      }
    },
    {
      "@type": "Question",
      "name": "공진단·경옥고와 일반 보약은 어떻게 다른가요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "공진단과 경옥고는 정해진 처방 형태를 바탕으로 복용 적합성을 상담하는 반면, 일반적인 보약 상담은 현재 증상과 상태에 따라 개인별 한약 처방을 고려할 수 있다는 점에서 상담 방향이 다를 수 있습니다."
      }
    }
  ]
}
</script>
