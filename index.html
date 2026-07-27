<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="theme-color" content="#0b0a0f" />
  <title>BIRTH ARCANA | 나의 탄생 타로</title>

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Gowun+Batang:wght@400;700&family=Noto+Sans+KR:wght@300;400;500;600;700&display=swap" rel="stylesheet">

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    :root {
      --bg: #09090d;
      --bg2: #121019;
      --cream: #f4ecdc;
      --gold: #d7b978;
      --gold2: #9d7a3d;
      --muted: #aaa3a0;
      --card: rgba(255,255,255,.055);
      --line: rgba(215,185,120,.22);
    }

    body {
      min-height: 100vh;
      background:
        radial-gradient(circle at 50% 0%, #241d30 0%, transparent 35%),
        radial-gradient(circle at 80% 80%, #17121e 0%, transparent 30%),
        var(--bg);
      color: var(--cream);
      font-family: "Noto Sans KR", sans-serif;
      overflow-x: hidden;
    }

    body::before {
      content: "";
      position: fixed;
      inset: 0;
      pointer-events: none;
      opacity: .35;
      background-image:
        radial-gradient(circle, rgba(255,255,255,.7) 1px, transparent 1px),
        radial-gradient(circle, rgba(215,185,120,.7) 1px, transparent 1px);
      background-size: 80px 80px, 130px 130px;
      background-position: 10px 10px, 35px 60px;
      mask-image: linear-gradient(to bottom, black, transparent 80%);
    }

    .page {
      width: min(100%, 720px);
      margin: 0 auto;
      padding: 24px 20px 70px;
      position: relative;
      z-index: 2;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 60px;
    }

    .logo {
      font-family: "Gowun Batang", serif;
      letter-spacing: 4px;
      font-size: 14px;
      color: var(--gold);
    }

    .moon {
      color: var(--gold);
      font-size: 22px;
    }

    .hero {
      text-align: center;
      padding: 15px 0 45px;
    }

    .eyebrow {
      color: var(--gold);
      letter-spacing: 4px;
      font-size: 11px;
      margin-bottom: 20px;
    }

    h1 {
      font-family: "Gowun Batang", serif;
      font-size: clamp(35px, 8vw, 57px);
      line-height: 1.22;
      font-weight: 400;
      margin-bottom: 20px;
    }

    .hero p {
      color: var(--muted);
      font-size: 14px;
      line-height: 1.9;
    }

    .sparkle {
      display: block;
      color: var(--gold);
      margin: 25px 0 5px;
      font-size: 18px;
      letter-spacing: 8px;
    }

    .input-card {
      padding: 28px 24px;
      border: 1px solid var(--line);
      background: var(--card);
      backdrop-filter: blur(12px);
      border-radius: 24px;
      box-shadow: 0 30px 80px rgba(0,0,0,.25);
    }

    label {
      display: block;
      font-size: 12px;
      color: var(--gold);
      margin-bottom: 10px;
      letter-spacing: 1px;
    }

    input {
      width: 100%;
      border: 1px solid rgba(255,255,255,.12);
      border-radius: 13px;
      background: rgba(0,0,0,.25);
      padding: 16px;
      color: white;
      font-family: inherit;
      font-size: 16px;
      outline: none;
      margin-bottom: 20px;
    }

    input:focus {
      border-color: var(--gold2);
    }

    input[type="date"] {
      color-scheme: dark;
    }

    button {
      width: 100%;
      border: 0;
      border-radius: 14px;
      padding: 17px;
      background: linear-gradient(135deg, #e2c98e, #aa8244);
      color: #17120b;
      font-family: inherit;
      font-weight: 700;
      font-size: 14px;
      cursor: pointer;
      transition: .25s ease;
    }

    button:hover {
      transform: translateY(-2px);
      box-shadow: 0 12px 30px rgba(215,185,120,.18);
    }

    .notice {
      margin-top: 16px;
      color: #777178;
      font-size: 10px;
      text-align: center;
      line-height: 1.7;
    }

    #loading {
      display: none;
      text-align: center;
      padding: 80px 0;
    }

    .deck {
      width: 120px;
      height: 190px;
      margin: 0 auto 35px;
      position: relative;
    }

    .mini-card {
      position: absolute;
      inset: 0;
      border: 1px solid var(--gold2);
      border-radius: 12px;
      background:
        radial-gradient(circle, #d7b978 1px, transparent 2px),
        linear-gradient(145deg, #19131f, #0e0b12);
      background-size: 20px 20px, auto;
      transition: .3s;
    }

    .mini-card:nth-child(1) {
      transform: rotate(-8deg);
      animation: shuffle1 .8s infinite alternate;
    }

    .mini-card:nth-child(2) {
      transform: rotate(7deg);
      animation: shuffle2 .8s infinite alternate;
    }

    .mini-card:nth-child(3) {
      transform: rotate(0);
    }

    @keyframes shuffle1 {
      to { transform: translateX(-30px) rotate(-15deg); }
    }

    @keyframes shuffle2 {
      to { transform: translateX(30px) rotate(15deg); }
    }

    #loading p {
      color: var(--muted);
      letter-spacing: 2px;
      font-size: 13px;
    }

    #result {
      display: none;
      animation: reveal .8s ease;
    }

    @keyframes reveal {
      from { opacity: 0; transform: translateY(25px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .result-head {
      text-align: center;
      margin-bottom: 35px;
    }

    .result-head .small {
      font-size: 11px;
      color: var(--gold);
      letter-spacing: 3px;
    }

    .tarot-card {
      width: 230px;
      height: 380px;
      margin: 30px auto;
      perspective: 1000px;
    }

    .tarot-inner {
      width: 100%;
      height: 100%;
      position: relative;
      transform-style: preserve-3d;
      animation: flip 1.5s ease forwards;
    }

    @keyframes flip {
      0% { transform: rotateY(180deg) scale(.85); }
      70% { transform: rotateY(-8deg) scale(1.03); }
      100% { transform: rotateY(0) scale(1); }
    }

    .tarot-face {
      position: absolute;
      inset: 0;
      border-radius: 16px;
      border: 1px solid #c29b55;
      background:
        radial-gradient(circle at 50% 40%, rgba(215,185,120,.16), transparent 35%),
        linear-gradient(145deg, #1d1723, #0b090e);
      box-shadow: 0 25px 70px rgba(0,0,0,.55);
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      padding: 20px;
    }

    .roman {
      position: absolute;
      top: 17px;
      color: var(--gold);
      font-family: "Gowun Batang", serif;
      font-size: 16px;
    }

    .card-symbol {
      font-size: 75px;
      margin-bottom: 24px;
      filter: drop-shadow(0 8px 15px rgba(0,0,0,.4));
    }

    .card-en {
      font-family: "Gowun Batang", serif;
      font-size: 21px;
      color: var(--cream);
      letter-spacing: 2px;
    }

    .card-ko {
      color: var(--gold);
      font-size: 13px;
      margin-top: 8px;
    }

    .birth-number {
      color: var(--muted);
      font-size: 13px;
      margin-bottom: 8px;
    }

    .result-title {
      font-family: "Gowun Batang", serif;
      font-size: 29px;
      margin-bottom: 12px;
    }

    .keywords {
      color: var(--gold);
      font-size: 13px;
      line-height: 1.8;
    }

    .sections {
      display: grid;
      gap: 14px;
      margin-top: 35px;
    }

    .section {
      padding: 22px;
      border: 1px solid rgba(255,255,255,.08);
      background: rgba(255,255,255,.035);
      border-radius: 17px;
    }

    .section h3 {
      color: var(--gold);
      font-family: "Gowun Batang", serif;
      font-size: 17px;
      margin-bottom: 11px;
    }

    .section p {
      color: #c5bec1;
      font-size: 13px;
      line-height: 1.9;
    }

    .question {
      text-align: center;
      border-color: var(--line);
      margin-top: 12px;
    }

    .question p {
      font-family: "Gowun Batang", serif;
      color: var(--cream);
      font-size: 17px;
    }

    .retry {
      background: transparent;
      color: var(--gold);
      border: 1px solid var(--line);
      margin-top: 25px;
    }

    footer {
      text-align: center;
      color: #575159;
      font-size: 10px;
      margin-top: 60px;
      line-height: 1.8;
    }

    @media(max-width: 500px) {
      header { margin-bottom: 35px; }
      .hero { padding-top: 5px; }
      .input-card { padding: 24px 18px; }
      .tarot-card { width: 205px; height: 340px; }
    }
  </style>
</head>

<body>

<div class="page">

  <header>
    <div class="logo">BIRTH ARCANA</div>
    <div class="moon">☾</div>
  </header>

  <main id="start">

    <section class="hero">
      <div class="eyebrow">YOUR BIRTH · YOUR ARCANA</div>

      <h1>
        생일에 숨겨진<br>
        나의 타로 카드
      </h1>

      <p>
        우리가 태어난 날짜에는 하나의 숫자가 숨어 있습니다.<br>
        당신의 생일을 따라가며<br>
        당신을 닮은 한 장의 카드를 만나보세요.
      </p>

      <span class="sparkle">✦ · ✦</span>
    </section>

    <div class="input-card">

      <label for="name">NAME</label>
      <input
        type="text"
        id="name"
        maxlength="12"
        placeholder="이름 또는 닉네임"
      >

      <label for="birthday">DATE OF BIRTH</label>
      <input type="date" id="birthday">

      <button onclick="startReading()">
        나의 탄생 카드 만나기
      </button>

      <div class="notice">
        본 콘텐츠는 타로 상징을 활용한 자기이해·성찰용 콘텐츠입니다.<br>
        미래를 확정적으로 예측하는 운세가 아닙니다.
      </div>

    </div>
  </main>


  <section id="loading">

    <div class="deck">
      <div class="mini-card"></div>
      <div class="mini-card"></div>
      <div class="mini-card"></div>
    </div>

    <p>당신의 생일에서 카드를 찾고 있습니다...</p>

  </section>


  <section id="result">

    <div class="result-head">

      <div class="small">YOUR BIRTH ARCANA</div>

      <div class="tarot-card">
        <div class="tarot-inner">
          <div class="tarot-face">
            <div class="roman" id="roman"></div>
            <div class="card-symbol" id="symbol"></div>
            <div class="card-en" id="cardEn"></div>
            <div class="card-ko" id="cardKo"></div>
          </div>
        </div>
      </div>

      <div class="birth-number" id="birthNumber"></div>

      <h2 class="result-title" id="resultTitle"></h2>

      <div class="keywords" id="keywords"></div>

    </div>


    <div class="sections">

      <div class="section">
        <h3>01 · 나의 기본 성향</h3>
        <p id="personality"></p>
      </div>

      <div class="section">
        <h3>02 · 타고난 강점</h3>
        <p id="strength"></p>
      </div>

      <div class="section">
        <h3>03 · 그림자와 성장 포인트</h3>
        <p id="shadow"></p>
      </div>

      <div class="section">
        <h3>04 · 관계 속의 나</h3>
        <p id="relationship"></p>
      </div>

      <div class="section">
        <h3>05 · 일과 진로</h3>
        <p id="career"></p>
      </div>

      <div class="section question">
        <h3>오늘 카드가 당신에게 묻습니다</h3>
        <p id="question"></p>
      </div>

    </div>

    <button class="retry" onclick="resetReading()">
      다른 생일로 다시 보기
    </button>

  </section>

  <footer>
    BIRTH ARCANA<br>
    Tarot symbols for self-reflection.
  </footer>

</div>


<script>

const cards = [
  null,

  {
    number:1,
    roman:"I",
    en:"THE MAGICIAN",
    ko:"마법사",
    symbol:"✦",
    keywords:"시작 · 의지 · 창조 · 실행",
    personality:"당신은 생각을 현실로 옮기고 싶어 하는 사람입니다. 새로운 아이디어가 생겼을 때 직접 시도해 보며 가능성을 확인하는 편입니다. 스스로 선택하고 움직일 때 에너지가 살아납니다.",
    strength:"빠른 실행력과 표현력이 강점입니다. 가지고 있는 자원과 능력을 연결해 새로운 결과를 만들어내는 힘이 있습니다.",
    shadow:"모든 것을 혼자 해결하려 하거나 결과를 빨리 만들어야 한다는 압박을 느낄 수 있습니다. 시작하는 힘만큼 꾸준히 완성하는 힘을 기르는 것이 중요합니다.",
    relationship:"관계에서도 주도적인 모습을 보이는 경우가 많습니다. 상대를 이끌기보다 서로의 의견이 함께 움직일 공간을 만들어줄 때 관계가 더 편안해집니다.",
    career:"기획, 창업, 마케팅, 콘텐츠, 영업처럼 아이디어를 직접 실행하고 결과를 만들어내는 일이 잘 맞을 수 있습니다.",
    question:"지금 내가 가진 것만으로 시작할 수 있는 일은 무엇인가요?"
  },

  {
    number:2,
    roman:"II",
    en:"THE HIGH PRIESTESS",
    ko:"여사제",
    symbol:"☾",
    keywords:"직관 · 관찰 · 내면 · 통찰",
    personality:"당신은 겉으로 드러난 말보다 그 안의 분위기와 의미를 읽는 데 익숙한 사람입니다. 충분히 관찰하고 생각한 뒤 움직이는 편이며 혼자 생각을 정리하는 시간이 중요합니다.",
    strength:"섬세한 관찰력과 직관이 강점입니다. 다른 사람이 놓치는 감정이나 상황의 미묘한 변화를 알아차릴 수 있습니다.",
    shadow:"생각이 너무 깊어지면 행동을 미루거나 자신의 마음을 표현하지 못할 수 있습니다. 모든 답을 확신한 뒤 움직이려 하지 않아도 됩니다.",
    relationship:"넓은 관계보다 깊이 신뢰할 수 있는 관계를 선호할 가능성이 큽니다. 마음을 알아주기를 기다리기보다 직접 표현하는 연습이 도움이 됩니다.",
    career:"상담, 연구, 분석, 교육, 기획처럼 깊이 관찰하고 의미를 발견하는 분야에서 강점을 보일 수 있습니다.",
    question:"나는 지금 무엇을 알고 있으면서도 외면하고 있나요?"
  },

  {
    number:3,
    roman:"III",
    en:"THE EMPRESS",
    ko:"여황제",
    symbol:"❀",
    keywords:"풍요 · 감각 · 돌봄 · 창조",
    personality:"당신은 사람과 공간에 따뜻함을 더하는 능력이 있습니다. 아름다움과 감각적인 경험을 중요하게 여기며 무언가를 키우고 발전시키는 과정에서 만족감을 느낄 수 있습니다.",
    strength:"사람을 편안하게 만드는 힘과 창조적인 감각이 있습니다. 아이디어를 풍성하게 발전시키는 능력도 강점입니다.",
    shadow:"다른 사람을 돌보느라 자신의 필요를 뒤로 미루거나 편안함에 오래 머물 수 있습니다.",
    relationship:"애정 표현이 풍부하고 가까운 사람을 잘 챙기는 편입니다. 다만 상대의 문제까지 모두 책임지려고 하지 않는 것이 중요합니다.",
    career:"디자인, 예술, 뷰티, 교육, 서비스, 콘텐츠처럼 사람에게 경험과 가치를 제공하는 일이 잘 맞을 수 있습니다.",
    question:"나는 무엇을 더 아름답게 성장시키고 싶은가요?"
  },

  {
    number:4,
    roman:"IV",
    en:"THE EMPEROR",
    ko:"황제",
    symbol:"♜",
    keywords:"질서 · 책임 · 안정 · 리더십",
    personality:"당신은 기준과 방향이 분명할 때 안정감을 느끼는 사람입니다. 맡은 일에 책임감을 가지고 끝까지 해내려는 경향이 있습니다.",
    strength:"조직력과 책임감, 현실적인 판단력이 강점입니다. 혼란스러운 상황에서 구조를 만들고 방향을 잡는 능력이 있습니다.",
    shadow:"계획대로 되지 않을 때 스트레스를 크게 느끼거나 자신과 타인에게 지나치게 엄격해질 수 있습니다.",
    relationship:"신뢰와 약속을 중요하게 생각합니다. 감정보다 해결책을 먼저 제시하기보다 상대의 마음을 들어주는 것이 도움이 됩니다.",
    career:"관리, 행정, 경영, 프로젝트 운영, 조직 리더십처럼 체계와 책임이 필요한 분야와 잘 맞습니다.",
    question:"내가 지키려는 기준은 지금의 나에게도 필요한가요?"
  },

  {
    number:5,
    roman:"V",
    en:"THE HIEROPHANT",
    ko:"교황",
    symbol:"♢",
    keywords:"가치 · 배움 · 전통 · 가르침",
    personality:"당신은 삶에서 의미와 기준을 중요하게 생각하는 사람입니다. 배우고 이해한 것을 다른 사람과 나누는 과정에서 보람을 느낄 수 있습니다.",
    strength:"지식을 정리하고 전달하는 능력이 있습니다. 사람들에게 방향이나 기준을 제시하는 역할에서도 강점을 보입니다.",
    shadow:"익숙한 기준이 정답이라고 생각하면 새로운 가능성을 놓칠 수 있습니다.",
    relationship:"가치관이 맞는 사람과 깊은 관계를 만드는 편입니다. 서로 다른 생각도 존중할 수 있을 때 관계의 폭이 넓어집니다.",
    career:"교육, 코칭, 상담, 연구, 인사, 조직문화처럼 지식과 가치관을 전달하는 분야와 잘 맞습니다.",
    question:"내가 믿고 있는 기준은 어디에서 시작되었나요?"
  },

  {
    number:6,
    roman:"VI",
    en:"THE LOVERS",
    ko:"연인",
    symbol:"♡",
    keywords:"선택 · 관계 · 조화 · 가치",
    personality:"당신에게 관계와 선택은 중요한 주제입니다. 사람과의 연결 속에서 자신을 발견하고 마음이 움직이는 방향을 중요하게 생각합니다.",
    strength:"공감 능력과 관계를 연결하는 힘이 있습니다. 서로 다른 사람 사이에서 공통점을 발견하는 능력도 뛰어납니다.",
    shadow:"다른 사람의 기대를 지나치게 의식하면 자신의 선택을 미룰 수 있습니다.",
    relationship:"관계를 중요하게 여기지만 상대에게 맞추기만 하기보다 자신의 가치와 욕구를 함께 표현하는 것이 중요합니다.",
    career:"협업, 상담, 커뮤니케이션, 브랜딩, 인사 등 사람과 사람을 연결하는 분야에서 강점을 보일 수 있습니다.",
    question:"다른 사람의 기대가 없다면 나는 무엇을 선택할까요?"
  },

  {
    number:7,
    roman:"VII",
    en:"THE CHARIOT",
    ko:"전차",
    symbol:"➶",
    keywords:"도전 · 추진 · 집중 · 승리",
    personality:"당신은 목표가 생겼을 때 강한 추진력을 발휘하는 사람입니다. 경쟁과 도전이 오히려 에너지가 되기도 합니다.",
    strength:"집중력과 실행력이 뛰어납니다. 어려운 상황에서도 목표를 향해 계속 움직이는 힘이 있습니다.",
    shadow:"앞으로 나아가는 데 집중하다 보면 자신의 감정이나 주변 사람의 속도를 놓칠 수 있습니다.",
    relationship:"관계에서도 명확하고 적극적인 편입니다. 함께 가는 관계에서는 속도보다 방향을 맞추는 것이 중요합니다.",
    career:"영업, 스포츠, 프로젝트, 창업, 목표 중심의 조직처럼 성과와 도전이 있는 환경과 잘 맞습니다.",
    question:"나는 지금 어디를 향해 이렇게 빠르게 달리고 있나요?"
  },

  {
    number:8,
    roman:"VIII",
    en:"STRENGTH",
    ko:"힘",
    symbol:"∞",
    keywords:"용기 · 인내 · 자제 · 내면의 힘",
    personality:"당신은 겉으로 강하게 밀어붙이기보다 상황을 견디고 조절하면서 해결하는 힘을 가진 사람입니다.",
    strength:"인내심과 회복력이 강점입니다. 어려움 속에서도 감정을 조절하며 다시 중심을 잡을 수 있습니다.",
    shadow:"강해야 한다는 생각 때문에 힘든 감정을 혼자 견디려 할 수 있습니다.",
    relationship:"상대를 이해하고 기다려주는 편이지만 자신의 한계를 명확하게 표현하는 것도 필요합니다.",
    career:"코칭, 교육, 상담, 리더십, 장기 프로젝트처럼 꾸준함과 사람에 대한 이해가 필요한 분야와 잘 맞습니다.",
    question:"나는 무엇을 억누르고 있는 대신 부드럽게 다룰 수 있을까요?"
  },

  {
    number:9,
    roman:"IX",
    en:"THE HERMIT",
    ko:"은둔자",
    symbol:"✧",
    keywords:"탐구 · 독립 · 지혜 · 성찰",
    personality:"당신은 스스로 생각하고 답을 찾아가는 과정이 중요한 사람입니다. 혼자 있는 시간이 오히려 생각을 선명하게 만들어 줍니다.",
    strength:"깊이 파고드는 집중력과 분석력이 뛰어납니다.",
    shadow:"혼자 해결하려는 습관이 강해지면 사람들과 거리를 두게 될 수 있습니다.",
    relationship:"많은 사람보다 깊이 연결되는 몇 사람을 중요하게 생각합니다.",
    career:"연구, 전문직, 개발, 분석, 글쓰기처럼 깊은 전문성을 쌓는 분야와 잘 맞습니다.",
    question:"지금의 나에게 정말 필요한 답은 무엇인가요?"
  },

  {
    number:10,
    roman:"X",
    en:"WHEEL OF FORTUNE",
    ko:"운명의 수레바퀴",
    symbol:"◎",
    keywords:"변화 · 흐름 · 기회 · 전환",
    personality:"당신의 삶에서는 변화와 새로운 흐름이 중요한 주제가 될 수 있습니다. 환경 변화에 적응하면서 새로운 가능성을 발견하는 능력이 있습니다.",
    strength:"변화를 빠르게 읽고 기회를 발견하는 감각이 있습니다.",
    shadow:"상황이 바뀌기를 기다리기만 하면 자신의 선택권을 놓칠 수 있습니다.",
    relationship:"새로운 사람과 경험에 열린 편입니다. 관계가 변화하는 과정도 자연스럽게 받아들이는 연습이 중요합니다.",
    career:"변화가 빠른 산업, 프로젝트형 업무, 콘텐츠, 마케팅 등 새로운 흐름을 읽는 일이 잘 맞을 수 있습니다.",
    question:"지금 내 앞에 열리고 있는 새로운 흐름은 무엇인가요?"
  },

  {
    number:11,
    roman:"XI",
    en:"JUSTICE",
    ko:"정의",
    symbol:"⚖",
    keywords:"균형 · 판단 · 원칙 · 책임",
    personality:"당신은 무엇이 공정하고 합리적인지 중요하게 생각합니다. 감정과 현실을 함께 비교하며 판단하려는 편입니다.",
    strength:"객관적인 판단력과 책임감이 강점입니다.",
    shadow:"정답을 찾으려는 마음이 강해지면 자신과 타인을 지나치게 평가할 수 있습니다.",
    relationship:"상호 존중과 균형을 중요하게 생각합니다.",
    career:"법률, 행정, 기획, 데이터, 평가처럼 객관적인 판단이 필요한 분야와 잘 맞습니다.",
    question:"나는 지금 누구의 기준으로 옳고 그름을 판단하고 있나요?"
  },

  {
    number:12,
    roman:"XII",
    en:"THE HANGED MAN",
    ko:"매달린 사람",
    symbol:"◇",
    keywords:"관점 · 기다림 · 전환 · 내려놓음",
    personality:"당신은 다른 사람들이 쉽게 지나치는 부분을 새로운 관점에서 바라보는 힘이 있습니다.",
    strength:"고정관념에서 벗어나 문제를 다르게 보는 능력이 뛰어납니다.",
    shadow:"생각만 계속하다 행동할 타이밍을 놓칠 수 있습니다.",
    relationship:"상대의 입장을 이해하려는 능력이 크지만 지나친 희생은 피하는 것이 좋습니다.",
    career:"창작, 상담, 연구, 전략 등 새로운 시각이 필요한 분야와 잘 맞습니다.",
    question:"이 상황을 완전히 반대로 바라본다면 무엇이 보일까요?"
  },

  {
    number:13,
    roman:"XIII",
    en:"DEATH",
    ko:"죽음",
    symbol:"✦",
    keywords:"끝 · 변화 · 정리 · 재탄생",
    personality:"당신에게 변화는 중요한 성장의 방식입니다. 오래된 것을 정리하고 새로운 단계로 넘어가는 힘을 가지고 있습니다.",
    strength:"과감하게 변화하고 다시 시작할 수 있는 힘이 있습니다.",
    shadow:"변화를 두려워해 이미 끝난 것에 오래 머물거나 반대로 너무 빨리 관계와 상황을 정리할 수 있습니다.",
    relationship:"관계를 통해 큰 변화를 경험하는 경우가 있습니다. 끝과 시작을 자연스러운 과정으로 받아들이는 것이 중요합니다.",
    career:"혁신, 리브랜딩, 변화관리, 창업 등 기존의 것을 새롭게 만드는 분야와 잘 맞습니다.",
    question:"지금의 내가 놓아주어야 할 것은 무엇인가요?"
  },

  {
    number:14,
    roman:"XIV",
    en:"TEMPERANCE",
    ko:"절제",
    symbol:"△",
    keywords:"조화 · 균형 · 연결 · 치유",
    personality:"당신은 서로 다른 것을 자연스럽게 연결하고 균형을 만들어내는 능력이 있습니다.",
    strength:"조율과 중재 능력이 뛰어납니다.",
    shadow:"갈등을 피하기 위해 자신의 의견을 지나치게 줄일 수 있습니다.",
    relationship:"편안하고 안정적인 관계를 만드는 능력이 있습니다.",
    career:"조정, 상담, 서비스, 기획, 협업 중심 업무에서 강점을 보일 수 있습니다.",
    question:"내 삶에서 지금 균형을 되찾아야 하는 부분은 어디인가요?"
  },

  {
    number:15,
    roman:"XV",
    en:"THE DEVIL",
    ko:"악마",
    symbol:"♠",
    keywords:"욕망 · 매력 · 집착 · 본능",
    personality:"당신은 자신이 원하는 것에 강하게 몰입할 수 있는 에너지를 가지고 있습니다. 사람을 끌어당기는 매력과 현실적인 욕구도 중요한 동력이 됩니다.",
    strength:"강한 집중력과 영향력을 발휘할 수 있습니다.",
    shadow:"욕망이 집착으로 변하거나 익숙한 습관에서 벗어나기 어려울 수 있습니다.",
    relationship:"강렬한 관계를 경험하기 쉽지만 서로의 자유와 경계를 존중하는 것이 중요합니다.",
    career:"비즈니스, 마케팅, 엔터테인먼트, 영업처럼 욕구와 사람의 심리를 읽는 분야에서 강점을 보일 수 있습니다.",
    question:"나는 무엇을 원하고 있으며, 그것이 나를 자유롭게 하고 있나요?"
  },

  {
    number:16,
    roman:"XVI",
    en:"THE TOWER",
    ko:"탑",
    symbol:"ϟ",
    keywords:"각성 · 변화 · 해체 · 진실",
    personality:"당신은 기존의 틀을 깨고 새로운 기준을 만드는 경험을 통해 크게 성장하는 사람입니다.",
    strength:"위기 속에서도 핵심을 발견하고 다시 시작하는 힘이 있습니다.",
    shadow:"갑작스러운 변화에 대한 두려움 때문에 안정된 것에 지나치게 집착할 수 있습니다.",
    relationship:"솔직함을 중요하게 생각합니다. 감정을 한꺼번에 터뜨리기보다 조금씩 표현하는 것이 도움이 됩니다.",
    career:"혁신, 문제 해결, 스타트업, 위기관리 등 변화를 만들어야 하는 환경과 잘 맞습니다.",
    question:"무너져야 비로소 새롭게 세울 수 있는 것은 무엇인가요?"
  },

  {
    number:17,
    roman:"XVII",
    en:"THE STAR",
    ko:"별",
    symbol:"☆",
    keywords:"희망 · 영감 · 가능성 · 진정성",
    personality:"당신은 미래의 가능성을 바라보는 힘이 있습니다. 자신의 생각과 감정을 솔직하게 표현할 때 사람들에게 영감을 줄 수 있습니다.",
    strength:"긍정적인 비전과 창의성이 강점입니다.",
    shadow:"이상적인 미래만 바라보다 현실적인 실행을 놓칠 수 있습니다.",
    relationship:"진솔한 연결을 중요하게 생각하며 서로의 꿈을 응원하는 관계를 선호합니다.",
    career:"예술, 콘텐츠, 브랜딩, 교육, 크리에이터처럼 영감과 메시지를 전달하는 분야와 잘 맞습니다.",
    question:"내가 아직 포기하지 않은 꿈은 무엇인가요?"
  },

  {
    number:18,
    roman:"XVIII",
    en:"THE MOON",
    ko:"달",
    symbol:"☽",
    keywords:"감수성 · 상상 · 무의식 · 직관",
    personality:"당신은 감정과 분위기를 섬세하게 느끼는 사람입니다. 풍부한 상상력과 감수성을 가지고 있습니다.",
    strength:"창의적인 상상력과 공감 능력이 뛰어납니다.",
    shadow:"불확실한 상황에서 걱정과 상상이 커질 수 있습니다.",
    relationship:"상대의 감정에 민감하게 반응하는 편입니다. 추측보다 직접 확인하는 것이 관계에 도움이 됩니다.",
    career:"예술, 디자인, 심리, 영상, 음악처럼 감정과 이미지를 다루는 분야와 잘 맞습니다.",
    question:"지금 내가 두려워하는 것은 사실인가요, 아니면 나의 상상인가요?"
  },

  {
    number:19,
    roman:"XIX",
    en:"THE SUN",
    ko:"태양",
    symbol:"☀",
    keywords:"활력 · 자신감 · 표현 · 기쁨",
    personality:"당신은 자신의 에너지를 밖으로 표현할 때 더욱 빛나는 사람입니다. 밝은 분위기와 솔직한 표현이 사람들에게 영향을 줄 수 있습니다.",
    strength:"긍정적인 에너지와 표현력이 강점입니다.",
    shadow:"항상 밝아야 한다는 부담을 느끼거나 인정에 지나치게 민감해질 수 있습니다.",
    relationship:"솔직하고 따뜻한 관계를 선호합니다.",
    career:"교육, 방송, 리더십, 콘텐츠, 행사 등 사람들 앞에서 에너지를 전달하는 분야와 잘 맞습니다.",
    question:"나는 언제 가장 나답게 빛나고 있나요?"
  },

  {
    number:20,
    roman:"XX",
    en:"JUDGEMENT",
    ko:"심판",
    symbol:"♬",
    keywords:"각성 · 소명 · 결단 · 새로운 단계",
    personality:"당신은 삶의 중요한 순간마다 자신에게 의미 있는 방향을 찾으려는 사람입니다.",
    strength:"경험을 돌아보고 그 안에서 의미를 발견하는 능력이 있습니다.",
    shadow:"과거의 선택을 계속 평가하거나 후회하는 데 머물 수 있습니다.",
    relationship:"서로의 성장을 돕는 관계에서 큰 의미를 느낍니다.",
    career:"교육, 코칭, 사회적 프로젝트, 리더십처럼 사람에게 변화와 방향을 제시하는 분야와 잘 맞습니다.",
    question:"지금의 나를 다음 단계로 부르고 있는 것은 무엇인가요?"
  },

  {
    number:21,
    roman:"XXI",
    en:"THE WORLD",
    ko:"세계",
    symbol:"◯",
    keywords:"완성 · 확장 · 통합 · 성취",
    personality:"당신은 다양한 경험을 연결해 하나의 큰 그림을 만드는 능력이 있습니다.",
    strength:"넓은 시야와 통합적인 사고가 강점입니다.",
    shadow:"완벽하게 준비된 뒤 움직이려 하면 새로운 시작이 늦어질 수 있습니다.",
    relationship:"서로 독립적이면서 함께 성장할 수 있는 관계를 선호합니다.",
    career:"글로벌 업무, 기획, 프로젝트 총괄, 콘텐츠처럼 여러 요소를 연결하는 분야와 잘 맞습니다.",
    question:"지금까지의 경험들이 나를 어디로 데려가고 있나요?"
  },

  {
    number:22,
    roman:"0 · XXII",
    en:"THE FOOL",
    ko:"바보",
    symbol:"☁",
    keywords:"자유 · 모험 · 가능성 · 새로운 시작",
    personality:"당신은 새로운 경험과 가능성에 마음이 움직이는 사람입니다. 정해진 길보다 직접 경험하며 자신만의 길을 발견하는 편입니다.",
    strength:"새로운 환경에 뛰어들 수 있는 용기와 유연성이 있습니다.",
    shadow:"흥미가 빠르게 바뀌거나 계획 없이 움직이면 시작한 일을 마무리하기 어려울 수 있습니다.",
    relationship:"자유롭고 편안한 관계를 좋아합니다. 자유와 책임의 균형을 만드는 것이 중요합니다.",
    career:"창작, 여행, 스타트업, 프리랜서 등 새로운 경험이 계속 생기는 환경과 잘 맞을 수 있습니다.",
    question:"실패할 걱정이 없다면 나는 무엇을 시작하고 싶나요?"
  }
];


function calculateBirthNumber(dateString) {

  const digits = dateString.replace(/\D/g, "");

  let total = [...digits]
    .map(Number)
    .reduce((a,b) => a+b, 0);

  while (total > 22) {
    total = [...String(total)]
      .map(Number)
      .reduce((a,b) => a+b, 0);
  }

  return total;
}


function startReading() {

  const name =
    document.getElementById("name").value.trim() || "당신";

  const birthday =
    document.getElementById("birthday").value;

  if (!birthday) {
    alert("생년월일을 입력해주세요.");
    return;
  }

  const number = calculateBirthNumber(birthday);
  const card = cards[number];

  document.getElementById("start").style.display = "none";
  document.getElementById("loading").style.display = "block";

  window.scrollTo({
    top: 0,
    behavior: "smooth"
  });

  setTimeout(() => {

    document.getElementById("loading").style.display = "none";
    document.getElementById("result").style.display = "block";

    document.getElementById("roman").textContent = card.roman;
    document.getElementById("symbol").textContent = card.symbol;
    document.getElementById("cardEn").textContent = card.en;
    document.getElementById("cardKo").textContent = card.ko;

    document.getElementById("birthNumber").textContent =
      "TAROT BIRTH NUMBER · " + number;

    document.getElementById("resultTitle").textContent =
      name + "님의 탄생 카드는 " + card.ko;

    document.getElementById("keywords").textContent =
      card.keywords;

    document.getElementById("personality").textContent =
      card.personality;

    document.getElementById("strength").textContent =
      card.strength;

    document.getElementById("shadow").textContent =
      card.shadow;

    document.getElementById("relationship").textContent =
      card.relationship;

    document.getElementById("career").textContent =
      card.career;

    document.getElementById("question").textContent =
      "“" + card.question + "”";

    window.scrollTo({
      top: 0,
      behavior: "smooth"
    });

  }, 2100);
}


function resetReading() {

  document.getElementById("result").style.display = "none";
  document.getElementById("start").style.display = "block";

  window.scrollTo({
    top: 0,
    behavior: "smooth"
  });
}

</script>

</body>
</html>
