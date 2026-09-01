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

  .children-grid{
    display:grid;
    grid-template-columns:repeat(3,minmax(0,1fr));
    gap:18px;
  }
  .children-card{
    padding:26px;
    border:1px solid rgba(0,0,0,.09);
    border-radius:18px;
    background:#fff;
  }
  .children-card h3{margin:0 0 10px;font-size:1.14rem;}
  .children-card p{margin:0;line-height:1.75;}

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
    .children-grid{grid-template-columns:repeat(2,minmax(0,1fr));}
    .treatment-grid{grid-template-columns:repeat(2,minmax(0,1fr));}
    .clinic-cta,.related-box{align-items:flex-start;flex-direction:column;}
  }
  @media (max-width:640px){
    .clinic-page-hero{padding:64px 0 48px;}
    .clinic-section{padding:56px 0;}
    .children-grid,.check-list,.treatment-grid{grid-template-columns:1fr;}
  }
</style>

<section class="clinic-page-hero">
  <div class="container">
    <span class="clinic-kicker">CHILDREN'S CLINIC</span>
    <h1>소아 클리닉</h1>
    <p class="clinic-lead">
      아이의 성장에는 유전뿐 아니라
      <strong>수면, 식사, 운동량, 회복, 반복되는 감기·비염과 전반적인 체력</strong>이 함께 영향을 줄 수 있습니다.
      특히 초등학교 고학년처럼 급성장기를 앞둔 시기나 운동량이 많은 아이,
      또 여자아이에서 또래보다 이른 사춘기 변화가 보이는 경우에는
      최근 성장속도와 생활리듬, 사춘기 진행 시점을 함께 살펴보는 것이 중요합니다.
    </p>
    <div class="clinic-nav" aria-label="소아 클리닉 페이지 바로가기">
      <a href="#symptoms">주요 고민</a>
      <a href="#growth">성장관리</a>
      <a href="#check">진료 시 확인</a>
      <a href="#faq">자주 묻는 질문</a>
    </div>
  </div>
</section>

<section class="clinic-section" id="symptoms">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">CHILDREN'S HEALTH</span>
      <h2>아이에게 이런 고민이 있나요?</h2>
      <p>또래와 단순 비교하기보다 최근 성장속도와 생활리듬, 운동량과 회복 상태를 함께 살펴봅니다.</p>
    </div>

<div class="children-grid">
  <article class="children-card">
    <h3>급성장기를 앞둔 초등 고학년</h3>
    <p>초등학교 고학년처럼 성장 변화가 커지기 전 최근 키와 몸무게의 변화, 수면·식사·활동량을 함께 살펴봅니다.</p>
  </article>

  <article class="children-card">
    <h3>운동하는 아이의 성장·체력관리</h3>
    <p>축구·야구·농구·수영 등 운동량이 많은 아이의 성장속도와 식사량, 수면, 피로와 회복 상태를 함께 확인합니다.</p>
  </article>

  <article class="children-card">
    <h3>성조숙증·빠른 사춘기 변화가 걱정되는 여자아이</h3>
    <p>또래보다 이른 가슴 발달, 성장속도의 갑작스러운 증가 등 사춘기 변화가 빠르게 보일 때 시작 시점과 성장 기록을 확인하고 필요한 소아내분비 평가 여부를 안내합니다.</p>
  </article>

  <article class="children-card">
    <h3>성장 속도가 걱정되는 아이</h3>
    <p>최근 1~2년간 키가 얼마나 자랐는지, 성장속도가 어떻게 달라졌는지와 생활패턴을 함께 살펴봅니다.</p>
  </article>

  <article class="children-card">
    <h3>식욕이 적고 잘 먹지 않는 아이</h3>
    <p>식사량이 적거나 편식이 심한 경우 간식, 소화 상태, 배변과 함께 확인합니다.</p>
  </article>

  <article class="children-card">
    <h3>감기·기침·비염이 자주 반복되는 아이</h3>
    <p>감기나 기침이 자주 반복되고 코막힘이나 입호흡이 수면과 체력에 영향을 주는지 함께 살펴봅니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section soft" id="growth">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">GROWTH CARE</span>
      <h2>성장관리는 키 하나만 보는 것이 아닙니다.</h2>
      <p>성장속도와 함께 수면, 영양, 운동량과 회복 상태를 함께 확인합니다.</p>
    </div>

<div class="children-grid">
  <article class="children-card">
    <h3>최근 성장속도</h3>
    <p>학교 신체검사나 집에서 잰 기록을 바탕으로 최근 1년 동안 얼마나 자랐는지 흐름을 확인합니다.</p>
  </article>

  <article class="children-card">
    <h3>운동량과 회복</h3>
    <p>훈련 횟수와 시간, 경기 일정, 운동 후 피로가 얼마나 오래가는지 살펴봅니다.</p>
  </article>

  <article class="children-card">
    <h3>수면시간과 취침시각</h3>
    <p>늦게 자거나 수면시간이 부족하지 않은지, 코막힘·입호흡으로 수면이 방해받지는 않는지 확인합니다.</p>
  </article>

  <article class="children-card">
    <h3>식사량과 단백질·간식</h3>
    <p>운동량에 비해 식사량이 부족하지 않은지, 편식과 간식으로 식사가 줄지는 않는지 살펴봅니다.</p>
  </article>

  <article class="children-card">
    <h3>부상과 통증</h3>
    <p>운동 중 반복되는 발목·무릎·허리 통증이 활동량과 수면을 방해하는지 함께 확인합니다.</p>
  </article>

  <article class="children-card">
    <h3>성장·성조숙증 관련 검사 여부</h3>
    <p>성장속도가 뚜렷하게 떨어지거나 사춘기 진행이 빠르거나 늦어 보이는 경우에는 골연령·호르몬 검사 등 소아청소년과 성장평가가 도움이 될 수 있습니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section" id="puberty">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">EARLY PUBERTY</span>
      <h2>여자아이의 사춘기 변화가 빠르게 보인다면</h2>
      <p>사춘기 시작 시점은 개인차가 있지만, 또래보다 이른 변화가 보이거나 성장속도가 갑자기 빨라진 경우에는 성장 기록과 사춘기 진행 정도를 함께 확인하는 것이 중요합니다.</p>
    </div>

<div class="children-grid">
  <article class="children-card">
    <h3>가슴 발달이 일찍 시작된 경우</h3>
    <p>여자아이에서 또래보다 이른 가슴 발달이 보이거나 변화 속도가 빠른 경우 시작 시점을 확인합니다.</p>
  </article>

  <article class="children-card">
    <h3>키가 갑자기 빠르게 자라는 경우</h3>
    <p>최근 6개월~1년 사이 성장속도가 갑자기 빨라졌다면 사춘기 진행과 함께 살펴볼 필요가 있습니다.</p>
  </article>

  <article class="children-card">
    <h3>초경 시기가 걱정되는 경우</h3>
    <p>가슴 발달 이후의 변화와 성장 기록을 함께 보고, 필요하면 소아청소년과 또는 소아내분비 평가를 권합니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section soft">
  <div class="container">
    <div class="important-box">
      <h3>성조숙증이 의심되면 소아청소년과·소아내분비 평가가 우선입니다.</h3>
      <p>
        여자아이에서 만 8세 이전에 가슴 발달 등 이차성징이 시작되거나,
        성장속도가 갑자기 빨라지면서 사춘기 변화가 빠르게 진행되는 경우에는
        골연령 검사와 호르몬 평가 등 전문적인 검사가 필요할 수 있습니다.
        약손한의원에서는 이미 받은 검사 결과와 현재 성장속도, 수면·식사·운동량을 함께 확인하며
        생활관리와 성장 컨디션 상담을 진행합니다.
      </p>
    </div>
  </div>
</section>

<section class="clinic-section">
  <div class="container">
    <div class="important-box">
      <h3>운동은 성장에 도움이 되는 생활습관이지만, 운동량이 많을수록 회복도 중요합니다.</h3>
      <p>
        운동하는 아이는 에너지 소비가 크기 때문에 식사량과 수면이 충분한지 함께 살펴봐야 합니다.
        늦은 훈련으로 취침이 늦어지거나 식사를 거르고 운동하는 습관,
        반복되는 통증이나 피로가 있다면 성장관리와 함께 조정할 부분을 확인하는 것이 좋습니다.
      </p>
    </div>
  </div>
</section>

<section class="clinic-section soft" id="check">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">CONSULTATION CHECKPOINT</span>
      <h2>성장상담에서는 이런 내용을 함께 확인합니다.</h2>
      <p>초등 고학년과 운동하는 아이는 키 기록뿐 아니라 운동 일정과 회복상태를 함께 가져오면 도움이 됩니다.</p>
    </div>

<div class="check-list">
  <div class="check-item">
    <strong>최근 1~2년의 키·몸무게</strong>
    <p>학교 신체검사 결과나 정기적으로 측정한 기록으로 최근 성장속도를 확인합니다.</p>
  </div>

  <div class="check-item">
    <strong>부모님의 키와 사춘기 시작 시기</strong>
    <p>가족의 성장 경향과 부모님의 사춘기 시기, 여자아이의 가슴 발달 시작 시점 등을 성장 상담에 참고합니다.</p>
  </div>

  <div class="check-item">
    <strong>운동 종목과 훈련량</strong>
    <p>어떤 운동을 얼마나 자주 하는지, 주당 훈련시간과 경기 일정 등을 확인합니다.</p>
  </div>

  <div class="check-item">
    <strong>식사량·간식·편식 여부</strong>
    <p>운동량에 비해 충분히 먹고 있는지, 간식 때문에 식사량이 줄지는 않는지 살펴봅니다.</p>
  </div>

  <div class="check-item">
    <strong>수면시간·코골이·입호흡</strong>
    <p>몇 시에 자고 일어나는지, 비염·코막힘으로 수면이 방해받지 않는지 확인합니다.</p>
  </div>

  <div class="check-item">
    <strong>성장검사·복용약·영양제</strong>
    <p>성장판 검사나 혈액검사 등 기존 검사 결과와 현재 복용 중인 약·영양제가 있다면 함께 확인합니다.</p>
  </div>
</div>

  </div>
</section>

<section class="clinic-section">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">CARE</span>
      <h2>아이의 연령과 성장 흐름에 맞춰 진료 방향을 상의합니다.</h2>
      <p>특정 치료가 최종 키를 보장할 수는 없으며, 성장에 영향을 줄 수 있는 생활요인을 함께 살펴보는 데 중점을 둡니다.</p>
    </div>

<div class="treatment-grid">
  <article class="treatment-card">
    <h3>성장 흐름 확인</h3>
    <p>최근 키·몸무게 변화와 가족력, 성장 시기를 함께 살펴봅니다.</p>
  </article>

  <article class="treatment-card">
    <h3>운동·회복 점검</h3>
    <p>운동량과 피로, 부상·통증, 휴식일과 수면 상태를 확인합니다.</p>
  </article>

  <article class="treatment-card">
    <h3>한약 상담</h3>
    <p>필요한 경우 연령과 체중, 식욕·소화, 수면, 현재 복용약을 확인한 뒤 한약을 상담합니다.</p>
  </article>

  <article class="treatment-card">
    <h3>생활관리 안내</h3>
    <p>취침시간, 식사와 간식, 운동 후 회복 등 집에서 조절해 볼 부분을 안내합니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section soft">
  <div class="container">
    <div class="safety-box">
      <h3>이런 경우에는 소아청소년과 성장평가 또는 관련 검사가 도움이 될 수 있습니다.</h3>
      <ul>
        <li>최근 성장속도가 이전보다 뚜렷하게 떨어진 경우</li>
        <li>체중이 지속적으로 감소하거나 식사량이 매우 적은 경우</li>
        <li>사춘기 변화가 또래보다 매우 빠르거나 늦어 보이는 경우</li>
        <li>심한 피로, 반복되는 통증, 만성질환 등 성장에 영향을 줄 수 있는 문제가 있는 경우</li>
        <li>보호자가 성장에 대해 지속적으로 걱정되는 경우</li>
      </ul>
    </div>
  </div>
</section>

<section class="clinic-section">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">HOME CARE</span>
      <h2>집에서는 키뿐 아니라 성장 환경을 함께 기록해 보세요.</h2>
    </div>

<div class="check-list">
  <div class="check-item">
    <strong>키·몸무게는 일정한 간격으로</strong>
    <p>매일 재기보다 몇 달 간격으로 같은 조건에서 기록하면 성장 흐름을 보기 좋습니다.</p>
  </div>

  <div class="check-item">
    <strong>운동 후 식사와 수면 확인</strong>
    <p>훈련 후 식사를 충분히 하는지, 늦은 운동으로 취침시간이 계속 밀리지는 않는지 살펴보세요.</p>
  </div>

  <div class="check-item">
    <strong>통증과 피로를 참지 않기</strong>
    <p>운동 후 통증이나 피로가 계속되면 무조건 훈련을 이어가기보다 회복 상태를 점검하는 것이 좋습니다.</p>
  </div>

  <div class="check-item">
    <strong>학교 신체검사 기록 보관하기</strong>
    <p>매년 키와 몸무게 기록을 모아두면 최근 성장속도를 확인하는 데 도움이 됩니다.</p>
  </div>
</div>

  </div>
</section>

<section class="clinic-section soft">
  <div class="container">
    <div class="related-box">
      <div>
        <h3>운동 중 반복되는 통증도 함께 있나요?</h3>
        <p>무릎·발목·허리·어깨 등 운동 중 반복되는 근골격계 불편은 통증 클리닉에서도 자세히 살펴볼 수 있습니다.</p>
      </div>
      <a class="button secondary" href="{{ '/clinic/pain/' | relative_url }}">통증 클리닉 보기</a>
    </div>
  </div>
</section>

<section class="clinic-section" id="faq">
  <div class="container">
    <div class="clinic-heading">
      <span class="eyebrow">FAQ</span>
      <h2>소아 성장 클리닉 자주 묻는 질문</h2>
    </div>

<div class="faq-list">
  <article class="faq-item">
    <h3>초등학교 고학년인데 급성장기 전에 상담받아도 되나요?</h3>
    <p>네. 최근 키와 몸무게 변화, 수면·식사·운동량을 확인해 현재 성장 흐름을 살펴볼 수 있습니다. 필요하면 소아청소년과 성장검사 여부도 함께 안내합니다.</p>
  </article>

  <article class="faq-item">
    <h3>운동을 많이 하는 아이도 성장상담이 필요한가요?</h3>
    <p>운동 자체는 건강한 생활습관이지만 운동량이 많다면 식사와 수면, 회복이 충분한지 함께 확인하는 것이 좋습니다.</p>
  </article>

  <article class="faq-item">
    <h3>축구나 야구를 하는데 키 성장에 운동이 방해될 수 있나요?</h3>
    <p>일반적인 운동 자체가 성장을 방해한다고 단정할 수는 없습니다. 다만 과도한 훈련, 부족한 영양과 수면, 반복되는 부상과 피로가 있다면 회복상태를 함께 살펴보는 것이 중요합니다.</p>
  </article>

  <article class="faq-item">
    <h3>성장한약을 먹으면 키가 많이 크나요?</h3>
    <p>키 성장은 유전, 영양, 수면, 운동, 사춘기 시기 등 여러 요인의 영향을 받습니다. 특정 한약이나 치료가 최종 키를 보장할 수는 없으며, 현재 성장속도와 생활상태를 함께 확인한 뒤 필요한 경우 한약을 상담합니다.</p>
  </article>

  <article class="faq-item">
    <h3>성장상담 전에 무엇을 준비하면 좋나요?</h3>
    <p>최근 1~2년간 키와 몸무게 기록, 학교 신체검사 결과, 운동 종목과 주당 훈련시간을 알고 오시면 도움이 됩니다.</p>
  </article>

  <article class="faq-item">
    <h3>밤늦게까지 운동하는 아이인데 괜찮을까요?</h3>
    <p>운동이 끝난 뒤 취침시간이 계속 늦어지고 전체 수면시간이 부족하다면 성장과 회복을 위해 생활일정을 점검해볼 필요가 있습니다.</p>
  </article>

  <article class="faq-item">
    <h3>성장판 검사를 꼭 해야 하나요?</h3>
    <p>모든 아이에게 반드시 필요한 것은 아닙니다. 성장속도와 사춘기 진행 정도, 보호자의 걱정에 따라 소아청소년과 성장평가가 도움이 될 수 있습니다.</p>
  </article>

  <article class="faq-item">
    <h3>비염이나 잦은 감기도 성장상담에서 같이 보나요?</h3>
    <p>네. 코막힘이나 입호흡으로 수면이 불편하거나 감기·기침이 자주 반복되어 식사와 활동이 자주 끊기는 경우 함께 확인합니다.</p>
  </article>

  <article class="faq-item">
    <h3>여자아이 가슴 발달이 일찍 시작됐는데 성조숙증인가요?</h3>
    <p>가슴 발달만으로 성조숙증을 확정할 수는 없습니다. 특히 만 8세 이전에 이차성징이 시작되거나 진행 속도가 빠르다면 소아청소년과·소아내분비에서 골연령과 호르몬 평가가 필요할 수 있습니다.</p>
  </article>

  <article class="faq-item">
    <h3>성조숙증 검사를 받은 뒤에도 한의원에서 상담할 수 있나요?</h3>
    <p>네. 검사 결과와 현재 성장속도, 수면·식사·운동량, 복용약 등을 함께 확인하며 생활관리와 성장 컨디션을 상담할 수 있습니다.</p>
  </article>

  <article class="faq-item">
    <h3>성조숙증 치료 중인데 한약을 같이 먹어도 되나요?</h3>
    <p>현재 소아내분비 치료 내용과 투약 여부를 먼저 확인해야 합니다. 담당 의료진의 치료를 임의로 중단하거나 변경하지 말고, 복용 중인 약을 알려주신 뒤 개별적으로 상담하는 것이 중요합니다.</p>
  </article>
</div>

  </div>
</section>

<section class="clinic-section" style="padding-top:0">
  <div class="container">
    <div class="clinic-cta">
      <div>
        <h2>급성장기를 앞둔 지금, 최근 성장속도와 생활리듬부터 살펴보겠습니다.</h2>
        <p>최근 키·몸무게 기록과 운동 일정, 기존 성장검사 자료가 있다면 내원 시 함께 알려주세요.</p>
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
      "name": "초등학교 고학년인데 급성장기 전에 상담받아도 되나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "최근 키와 몸무게 변화, 수면·식사·운동량을 확인해 현재 성장 흐름을 살펴볼 수 있습니다. 필요하면 소아청소년과 성장검사 여부도 함께 안내합니다."
      }
    },
    {
      "@type": "Question",
      "name": "운동을 많이 하는 아이도 성장상담이 필요한가요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "운동 자체는 건강한 생활습관이지만 운동량이 많다면 식사와 수면, 회복이 충분한지 함께 확인하는 것이 좋습니다."
      }
    },
    {
      "@type": "Question",
      "name": "성장한약을 먹으면 키가 많이 크나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "키 성장은 유전, 영양, 수면, 운동, 사춘기 시기 등 여러 요인의 영향을 받습니다. 특정 한약이나 치료가 최종 키를 보장할 수는 없으며, 현재 성장속도와 생활상태를 함께 확인한 뒤 필요한 경우 한약을 상담합니다."
      }
    },
    {
      "@type": "Question",
      "name": "성장상담 전에 무엇을 준비하면 좋나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "최근 1~2년간 키와 몸무게 기록, 학교 신체검사 결과, 운동 종목과 주당 훈련시간을 알고 오시면 도움이 됩니다."
      }
    },
    {
      "@type": "Question",
      "name": "성장판 검사를 꼭 해야 하나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "모든 아이에게 반드시 필요한 것은 아닙니다. 성장속도와 사춘기 진행 정도, 보호자의 걱정에 따라 소아청소년과 성장평가가 도움이 될 수 있습니다."
      }
    },
    {
      "@type": "Question",
      "name": "여자아이 가슴 발달이 일찍 시작됐는데 성조숙증인가요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "가슴 발달만으로 성조숙증을 확정할 수는 없습니다. 특히 만 8세 이전에 이차성징이 시작되거나 진행 속도가 빠르다면 소아청소년과·소아내분비에서 골연령과 호르몬 평가가 필요할 수 있습니다."
      }
    },
    {
      "@type": "Question",
      "name": "성조숙증 검사를 받은 뒤에도 한의원에서 상담할 수 있나요?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "검사 결과와 현재 성장속도, 수면·식사·운동량, 복용약 등을 함께 확인하며 생활관리와 성장 컨디션을 상담할 수 있습니다."
      }
    }
  ]
}
</script>
