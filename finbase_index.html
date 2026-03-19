<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>FINBASE – Your Base for Finance</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&family=Noto+Sans+KR:wght@300;400;500;700;900&display=swap" rel="stylesheet" />
  <style>
    /* ── Reset & Root ───────────────────────────────────────── */
    *, *::before, *::after { margin: 0; padding: 0; box-sizing: border-box; }
    :root {
      --navy:      #0b1628;
      --navy-2:    #0f1e35;
      --navy-card: #132040;
      --navy-light:#1c2d4a;
      --gold:      #f5b800;
      --gold-dark: #d49f00;
      --gold-dim:  rgba(245,184,0,.12);
      --red:       #e63946;
      --white:     #ffffff;
      --grey:      #a0aec0;
      --border:    rgba(245,184,0,.22);
    }
    html { scroll-behavior: smooth; }
    body {
      background: var(--navy);
      color: var(--white);
      font-family: 'Inter', 'Noto Sans KR', sans-serif;
      line-height: 1.6;
      overflow-x: hidden;
    }
    a { text-decoration: none; color: inherit; }
    ul { list-style: none; }

    /* ── HEADER ─────────────────────────────────────────────── */
    header {
      position: fixed; top: 0; left: 0; right: 0; z-index: 1000;
      background: rgba(11,22,40,.92);
      backdrop-filter: blur(14px);
      border-bottom: 1px solid var(--border);
    }
    .header-inner {
      max-width: 1200px; margin: 0 auto;
      display: flex; align-items: center;
      padding: 0 24px; height: 68px; gap: 40px;
    }
    /* Logo */
    .logo { display: flex; align-items: center; gap: 10px; flex-shrink: 0; }
    .logo svg { width: 36px; height: 36px; }
    .logo-text { font-size: 1.35rem; font-weight: 800; color: var(--gold); letter-spacing: .06em; }

    /* Nav */
    nav { display: flex; align-items: center; gap: 4px; flex: 1; }
    .nav-item {
      position: relative;
      padding: 8px 14px;
      font-size: .88rem; font-weight: 500;
      color: #c8d4e8; cursor: pointer; border-radius: 6px;
      transition: color .2s, background .2s;
      white-space: nowrap;
    }
    .nav-item:hover { color: var(--gold); background: var(--gold-dim); }
    .nav-item .chevron { font-size: .7rem; margin-left: 4px; transition: transform .2s; }
    .nav-item:hover .chevron { transform: rotate(180deg); }

    /* Dropdown */
    .dropdown {
      position: absolute; top: calc(100% + 6px); left: 0;
      background: var(--navy-2); border: 1px solid var(--border);
      border-radius: 10px; min-width: 150px;
      padding: 8px 0; opacity: 0; pointer-events: none;
      transform: translateY(-6px); transition: opacity .2s, transform .2s;
    }
    .nav-item:hover .dropdown { opacity: 1; pointer-events: auto; transform: translateY(0); }
    .dropdown a {
      display: block; padding: 9px 18px;
      font-size: .85rem; color: #c8d4e8;
      transition: color .15s, background .15s;
    }
    .dropdown a:hover { color: var(--gold); background: var(--gold-dim); }

    /* Right side */
    .header-right { display: flex; align-items: center; gap: 14px; margin-left: auto; }
    .lang-switch { font-size: .82rem; color: var(--grey); }
    .lang-switch span { cursor: pointer; transition: color .2s; }
    .lang-switch span.active { color: var(--gold); font-weight: 600; }
    .lang-switch span:hover { color: var(--white); }
    .btn-apply {
      background: var(--red); color: var(--white);
      padding: 9px 20px; border-radius: 7px;
      font-size: .85rem; font-weight: 700;
      border: none; cursor: pointer;
      transition: background .2s, transform .15s;
      white-space: nowrap;
    }
    .btn-apply:hover { background: #c62f3a; transform: translateY(-1px); }

    /* Hamburger */
    .hamburger {
      display: none; flex-direction: column; gap: 5px;
      cursor: pointer; padding: 4px; margin-left: auto;
    }
    .hamburger span {
      display: block; width: 24px; height: 2px;
      background: var(--white); border-radius: 2px;
      transition: transform .3s, opacity .3s;
    }

    /* ── MOBILE MENU ─────────────────────────────────────────── */
    .mobile-menu {
      display: none; position: fixed;
      inset: 0; z-index: 999;
      background: var(--navy-2);
      flex-direction: column; overflow-y: auto;
      padding: 80px 28px 100px;
    }
    .mobile-menu.open { display: flex; }
    .mobile-close {
      position: absolute; top: 18px; right: 22px;
      font-size: 1.8rem; cursor: pointer; color: var(--white);
      background: none; border: none; line-height: 1;
    }
    .mobile-section-title {
      font-size: 1.05rem; font-weight: 700; color: var(--white);
      margin: 24px 0 8px; border-bottom: 1px solid var(--border); padding-bottom: 8px;
    }
    .mobile-menu a {
      display: block; padding: 11px 10px;
      color: #b0c4de; font-size: .95rem;
      border-bottom: 1px solid rgba(255,255,255,.05);
      transition: color .15s;
    }
    .mobile-menu a:hover { color: var(--gold); }
    .mobile-apply {
      position: fixed; bottom: 0; left: 0; right: 0;
      background: var(--red); color: var(--white);
      text-align: center; padding: 18px;
      font-size: 1rem; font-weight: 700; cursor: pointer;
      border: none;
    }

    /* ── TICKER ──────────────────────────────────────────────── */
    .ticker-wrapper {
      background: var(--navy-light);
      border-bottom: 1px solid var(--border);
      overflow: hidden; white-space: nowrap;
      padding: 10px 0; margin-top: 68px;
    }
    .ticker-inner {
      display: inline-block;
      animation: ticker-scroll 30s linear infinite;
    }
    .ticker-item {
      display: inline-block; margin-right: 60px;
      font-size: .8rem; color: var(--grey);
    }
    .ticker-item::before {
      content: '●'; color: var(--gold);
      margin-right: 8px; font-size: .65rem;
    }
    @keyframes ticker-scroll {
      0%   { transform: translateX(0); }
      100% { transform: translateX(-50%); }
    }

    /* ── HERO ────────────────────────────────────────────────── */
    .hero {
      min-height: 100vh; display: flex; align-items: center;
      justify-content: center; text-align: center;
      position: relative; overflow: hidden;
      padding: 80px 24px 60px;
      background:
        radial-gradient(ellipse 70% 60% at 50% 40%, rgba(245,184,0,.06) 0%, transparent 70%),
        var(--navy);
    }
    /* subtle grid */
    .hero::before {
      content: ''; position: absolute; inset: 0;
      background-image:
        linear-gradient(rgba(245,184,0,.04) 1px, transparent 1px),
        linear-gradient(90deg, rgba(245,184,0,.04) 1px, transparent 1px);
      background-size: 60px 60px;
      pointer-events: none;
    }
    .hero-content { position: relative; max-width: 820px; }
    .hero-badge {
      display: inline-block;
      border: 1px solid var(--gold); border-radius: 50px;
      padding: 6px 20px; font-size: .78rem; font-weight: 600;
      color: var(--gold); letter-spacing: .12em;
      margin-bottom: 28px; text-transform: uppercase;
    }
    .hero-title {
      font-size: clamp(2.2rem, 5.5vw, 4rem);
      font-weight: 900; line-height: 1.15;
      letter-spacing: -.01em; margin-bottom: 24px;
    }
    .hero-title .highlight { color: var(--gold); }
    .hero-desc {
      font-size: clamp(.9rem, 2vw, 1.05rem);
      color: #a8bcd4; max-width: 600px; margin: 0 auto 40px;
      font-family: 'Noto Sans KR', sans-serif;
      word-break: keep-all; line-height: 1.9;
    }
    .hero-buttons { display: flex; gap: 16px; justify-content: center; flex-wrap: wrap; }
    .btn-primary {
      background: var(--gold); color: var(--navy);
      padding: 14px 34px; border-radius: 8px;
      font-size: .95rem; font-weight: 800;
      border: none; cursor: pointer;
      transition: background .2s, transform .2s;
    }
    .btn-primary:hover { background: var(--gold-dark); transform: translateY(-2px); }
    .btn-outline {
      background: transparent; color: var(--white);
      padding: 14px 34px; border-radius: 8px;
      font-size: .95rem; font-weight: 600;
      border: 1.5px solid rgba(255,255,255,.3); cursor: pointer;
      transition: border-color .2s, color .2s, transform .2s;
    }
    .btn-outline:hover { border-color: var(--gold); color: var(--gold); transform: translateY(-2px); }

    /* scroll indicator */
    .scroll-hint {
      position: absolute; bottom: 32px; left: 50%; transform: translateX(-50%);
      display: flex; flex-direction: column; align-items: center; gap: 6px;
      color: var(--grey); font-size: .72rem; letter-spacing: .1em; text-transform: uppercase;
      animation: bounce 2s infinite;
    }
    .scroll-hint svg { width: 20px; height: 20px; opacity: .7; }
    @keyframes bounce { 0%,100%{transform:translateX(-50%) translateY(0)} 50%{transform:translateX(-50%) translateY(6px)} }

    /* ── SECTION COMMONS ─────────────────────────────────────── */
    section { padding: 90px 24px; }
    .section-inner { max-width: 1200px; margin: 0 auto; }
    .section-header { text-align: center; margin-bottom: 56px; }
    .section-eyebrow {
      font-size: .78rem; font-weight: 700; letter-spacing: .15em;
      color: var(--gold); text-transform: uppercase; margin-bottom: 12px;
    }
    .section-title {
      font-size: clamp(1.7rem, 3.5vw, 2.6rem);
      font-weight: 900; line-height: 1.2;
    }
    .section-title .gold { color: var(--gold); }
    .section-divider {
      width: 56px; height: 3px; background: var(--gold);
      margin: 18px auto 0; border-radius: 2px;
    }
    .section-sub {
      margin-top: 16px; color: var(--grey);
      font-size: .95rem; font-family: 'Noto Sans KR', sans-serif;
    }

    /* ── STATS ───────────────────────────────────────────────── */
    .stats-section { background: var(--navy-2); border-top: 1px solid var(--border); border-bottom: 1px solid var(--border); padding: 48px 24px; }
    .stats-grid {
      max-width: 900px; margin: 0 auto;
      display: grid; grid-template-columns: repeat(4, 1fr); gap: 0;
    }
    .stat-item {
      text-align: center; padding: 16px 20px;
      border-right: 1px solid var(--border);
    }
    .stat-item:last-child { border-right: none; }
    .stat-num {
      font-size: 2.4rem; font-weight: 900; color: var(--gold);
      line-height: 1; margin-bottom: 6px;
    }
    .stat-label { font-size: .8rem; color: var(--grey); font-weight: 500; letter-spacing: .05em; }

    /* ── DEPARTMENTS ─────────────────────────────────────────── */
    .dept-section { background: var(--navy); }
    .dept-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 24px;
    }
    .dept-card {
      background: var(--navy-card);
      border: 1px solid var(--border);
      border-radius: 14px; padding: 36px 28px;
      transition: transform .3s, border-color .3s, box-shadow .3s;
      position: relative; overflow: hidden;
    }
    .dept-card::after {
      content: ''; position: absolute;
      bottom: 0; left: 0; right: 0; height: 3px;
      background: var(--gold); transform: scaleX(0);
      transform-origin: left; transition: transform .3s;
    }
    .dept-card:hover { transform: translateY(-6px); border-color: var(--gold); box-shadow: 0 16px 40px rgba(0,0,0,.4); }
    .dept-card:hover::after { transform: scaleX(1); }
    .dept-icon {
      width: 52px; height: 52px; background: var(--gold-dim);
      border: 1px solid var(--border); border-radius: 12px;
      display: flex; align-items: center; justify-content: center;
      font-size: 1.4rem; margin-bottom: 20px;
    }
    .dept-tag {
      font-size: .72rem; font-weight: 700; color: var(--gold);
      letter-spacing: .1em; text-transform: uppercase; margin-bottom: 8px;
    }
    .dept-name {
      font-size: 1.05rem; font-weight: 800;
      line-height: 1.3; margin-bottom: 14px;
    }
    .dept-desc {
      font-size: .84rem; color: var(--grey);
      font-family: 'Noto Sans KR', sans-serif;
      line-height: 1.85; word-break: keep-all;
    }

    /* ── WHY FINBASE ─────────────────────────────────────────── */
    .why-section { background: var(--navy-2); }
    .why-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 28px;
    }
    .why-card {
      background: var(--navy-card);
      border: 1px solid var(--border);
      border-radius: 14px; padding: 32px;
      display: flex; gap: 20px; align-items: flex-start;
      transition: border-color .3s, transform .3s;
    }
    .why-card:hover { border-color: var(--gold); transform: translateY(-4px); }
    .why-icon {
      width: 48px; height: 48px; flex-shrink: 0;
      background: var(--gold-dim); border-radius: 10px;
      display: flex; align-items: center; justify-content: center;
      font-size: 1.3rem;
    }
    .why-text h4 { font-size: .97rem; font-weight: 700; margin-bottom: 8px; }
    .why-text p { font-size: .84rem; color: var(--grey); font-family: 'Noto Sans KR',sans-serif; line-height: 1.8; word-break: keep-all; }

    /* ── CHALLENGE ───────────────────────────────────────────── */
    .challenge-section { background: var(--navy); }
    .challenge-box {
      max-width: 720px; margin: 0 auto;
      background: var(--navy-card);
      border: 1px solid var(--border);
      border-radius: 20px; padding: 52px 48px;
      text-align: center;
    }
    .challenge-title {
      font-size: 1.8rem; font-weight: 900; margin-bottom: 8px;
    }
    .challenge-title .gold { color: var(--gold); }
    .challenge-sub {
      font-size: .88rem; color: var(--grey);
      font-family: 'Noto Sans KR',sans-serif; margin-bottom: 36px;
    }
    .challenge-question {
      font-size: 1.05rem; font-weight: 700;
      font-family: 'Noto Sans KR',sans-serif;
      margin-bottom: 28px; line-height: 1.6;
    }
    .challenge-options {
      display: grid; grid-template-columns: 1fr 1fr;
      gap: 14px; text-align: left;
    }
    .option-btn {
      background: var(--navy-light);
      border: 1.5px solid var(--border);
      border-radius: 10px; padding: 14px 18px;
      font-size: .88rem; color: var(--white);
      font-family: 'Noto Sans KR',sans-serif;
      cursor: pointer; transition: border-color .2s, background .2s, color .2s;
      word-break: keep-all; line-height: 1.6;
    }
    .option-btn .opt-label { color: var(--gold); font-weight: 700; margin-right: 6px; }
    .option-btn:hover { border-color: var(--gold); background: var(--gold-dim); }
    .option-btn.correct { border-color: #22c55e; background: rgba(34,197,94,.1); color: #86efac; }
    .option-btn.wrong   { border-color: var(--red); background: rgba(230,57,70,.1); color: #fca5a5; }
    .challenge-result { margin-top: 20px; font-size: .95rem; font-weight: 600; min-height: 28px; }
    .challenge-result.correct { color: #22c55e; }
    .challenge-result.wrong   { color: var(--red); }

    /* ── APPLY ───────────────────────────────────────────────── */
    .apply-section {
      background:
        radial-gradient(ellipse 60% 70% at 50% 50%, rgba(245,184,0,.07) 0%, transparent 70%),
        var(--navy-2);
      text-align: center;
    }
    .apply-inner { max-width: 540px; margin: 0 auto; }
    .apply-inner h2 { font-size: clamp(1.5rem, 3vw, 2.2rem); font-weight: 900; margin-bottom: 12px; }
    .apply-inner h2 .gold { color: var(--gold); }
    .apply-inner p { font-size: .93rem; color: var(--grey); font-family: 'Noto Sans KR',sans-serif; margin-bottom: 36px; }
    .qr-box {
      width: 180px; height: 180px;
      background: #fff; border-radius: 14px;
      margin: 0 auto 28px;
      display: flex; align-items: center; justify-content: center;
      border: 3px solid var(--gold); padding: 10px;
    }
    .qr-placeholder {
      width: 100%; height: 100%;
      border: 2px dashed #bbb;
      border-radius: 8px;
      display: flex; align-items: center; justify-content: center;
      font-size: .72rem; color: #888; letter-spacing: .05em;
    }
    .btn-google-form {
      background: var(--gold); color: var(--navy);
      padding: 14px 36px; border-radius: 9px;
      font-size: .95rem; font-weight: 800; border: none; cursor: pointer;
      transition: background .2s, transform .2s; display: inline-block;
    }
    .btn-google-form:hover { background: var(--gold-dark); transform: translateY(-2px); }

    /* ── FOOTER ──────────────────────────────────────────────── */
    footer {
      background: var(--navy-2);
      border-top: 1px solid var(--border);
      padding: 36px 24px 28px;
    }
    .footer-inner {
      max-width: 1200px; margin: 0 auto;
      display: flex; align-items: center; justify-content: space-between;
      flex-wrap: wrap; gap: 16px;
    }
    .footer-logo { display: flex; align-items: center; gap: 8px; }
    .footer-logo svg { width: 26px; height: 26px; }
    .footer-logo span { font-size: 1rem; font-weight: 800; color: var(--gold); letter-spacing: .06em; }
    .footer-copy { font-size: .78rem; color: var(--grey); }
    .footer-links { display: flex; gap: 22px; }
    .footer-links a {
      font-size: .78rem; color: var(--grey); font-weight: 600;
      letter-spacing: .05em; text-transform: uppercase;
      transition: color .2s;
    }
    .footer-links a:hover { color: var(--gold); }

    /* ── RESPONSIVE ──────────────────────────────────────────── */
    @media (max-width: 768px) {
      nav, .header-right .lang-switch, .header-right .btn-apply { display: none; }
      .hamburger { display: flex; }
      .stats-grid { grid-template-columns: repeat(2, 1fr); }
      .stat-item:nth-child(2) { border-right: none; }
      .stat-item:nth-child(3) { border-right: 1px solid var(--border); }
      .challenge-box { padding: 36px 24px; }
      .challenge-options { grid-template-columns: 1fr; }
      .footer-inner { flex-direction: column; align-items: flex-start; }
    }
    @media (max-width: 480px) {
      .stats-grid { grid-template-columns: 1fr 1fr; }
      .hero-buttons { flex-direction: column; align-items: center; }
    }

    /* ── SCROLL ANIMATIONS ───────────────────────────────────── */
    .fade-up {
      opacity: 0; transform: translateY(32px);
      transition: opacity .65s ease, transform .65s ease;
    }
    .fade-up.visible { opacity: 1; transform: translateY(0); }
    .fade-up-delay-1 { transition-delay: .1s; }
    .fade-up-delay-2 { transition-delay: .2s; }
    .fade-up-delay-3 { transition-delay: .3s; }
    .fade-up-delay-4 { transition-delay: .4s; }
  </style>
</head>
<body>

<!-- ── HEADER ──────────────────────────────────────────────── -->
<header>
  <div class="header-inner">
    <!-- Logo -->
    <a href="#" class="logo">
      <svg viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg">
        <polygon points="18,2 34,18 18,34 2,18" stroke="#f5b800" stroke-width="2" fill="none"/>
        <polygon points="18,6 30,18 18,30 6,18" fill="#f5b800" opacity=".15"/>
        <line x1="9" y1="18" x2="27" y2="18" stroke="#f5b800" stroke-width="1.5"/>
        <line x1="18" y1="7" x2="18" y2="20" stroke="#f5b800" stroke-width="1.5"/>
        <line x1="10" y1="22" x2="18" y2="20" stroke="#f5b800" stroke-width="1.5"/>
        <line x1="26" y1="22" x2="18" y2="20" stroke="#f5b800" stroke-width="1.5"/>
        <line x1="10" y1="22" x2="18" y2="30" stroke="#f5b800" stroke-width="1.5"/>
        <line x1="26" y1="22" x2="18" y2="30" stroke="#f5b800" stroke-width="1.5"/>
      </svg>
      <span class="logo-text">FINBASE</span>
    </a>

    <!-- Nav -->
    <nav>
      <div class="nav-item">동아리 소개 <span class="chevron">▾</span>
        <div class="dropdown">
          <a href="#">소개</a>
          <a href="#">조직도</a>
          <a href="#">CI</a>
          <a href="#">Contact</a>
        </div>
      </div>
      <div class="nav-item">리서치 <span class="chevron">▾</span>
        <div class="dropdown">
          <a href="#">부동산 PF</a>
          <a href="#">IPO &amp; M&A</a>
        </div>
      </div>
      <div class="nav-item">뉴스 <span class="chevron">▾</span>
        <div class="dropdown">
          <a href="#">금융 뉴스 터미널</a>
        </div>
      </div>
      <div class="nav-item">커뮤니티 <span class="chevron">▾</span>
        <div class="dropdown">
          <a href="#">활동 기록</a>
          <a href="#">자료실</a>
        </div>
      </div>
    </nav>

    <!-- Right -->
    <div class="header-right">
      <div class="lang-switch">
        <span class="active">KR</span>
        &nbsp;|&nbsp;
        <span>EN</span>
      </div>
      <button class="btn-apply">지원 안내</button>
    </div>

    <!-- Hamburger -->
    <div class="hamburger" id="hamburger" onclick="toggleMenu()">
      <span></span><span></span><span></span>
    </div>
  </div>
</header>

<!-- ── MOBILE MENU ──────────────────────────────────────────── -->
<div class="mobile-menu" id="mobileMenu">
  <button class="mobile-close" onclick="toggleMenu()">✕</button>
  <div class="mobile-section-title">동아리 소개</div>
  <a href="#">소개</a>
  <a href="#">조직도</a>
  <a href="#">CI</a>
  <a href="#">Contact</a>
  <div class="mobile-section-title">리서치</div>
  <a href="#">부동산 PF</a>
  <a href="#">IPO &amp; M&A</a>
  <div class="mobile-section-title">뉴스</div>
  <a href="#">금융 뉴스 터미널</a>
  <div class="mobile-section-title">커뮤니티</div>
  <a href="#">활동 기록</a>
  <a href="#">자료실</a>
  <button class="mobile-apply">지원 안내</button>
</div>

<!-- ── NEWS TICKER ──────────────────────────────────────────── -->
<div class="ticker-wrapper">
  <div class="ticker-inner">
    <span class="ticker-item">B테크, 코스닥 상장 예비심사 등과</span>
    <span class="ticker-item">C자산운용, 500억 규모 메자닌 펀드 조성</span>
    <span class="ticker-item">D은행, 혁신금융서비스 지정… 플랫폼 출시 박차</span>
    <span class="ticker-item">E바이오, 1000억 프리IPO 투자 유치 성공</span>
    <span class="ticker-item">F증권, 2026 하반기 IB부문 채용 공고 발표</span>
    <span class="ticker-item">G캐피탈, 부동산 PF 구조조정 본격 착수</span>
    <span class="ticker-item">B테크, 코스닥 상장 예비심사 등과</span>
    <span class="ticker-item">C자산운용, 500억 규모 메자닌 펀드 조성</span>
    <span class="ticker-item">D은행, 혁신금융서비스 지정… 플랫폼 출시 박차</span>
    <span class="ticker-item">E바이오, 1000억 프리IPO 투자 유치 성공</span>
    <span class="ticker-item">F증권, 2026 하반기 IB부문 채용 공고 발표</span>
    <span class="ticker-item">G캐피탈, 부동산 PF 구조조정 본격 착수</span>
  </div>
</div>

<!-- ── HERO ─────────────────────────────────────────────────── -->
<section class="hero" id="hero">
  <div class="hero-content">
    <div class="hero-badge">Your Base for Finance</div>
    <h1 class="hero-title">
      EXPLORE THE WORLD OF<br>
      <span class="highlight">FINANCE &amp; INVESTMENT</span><br>
      BANKING
    </h1>
    <p class="hero-desc">
      여의도 및 월스트리트 실무진과 협력하여 실제 딜을 다룹니다.<br>
      M&amp;A, IPO, Real Estate PF 등 실물 금융을 심도 있게 연구하고<br>
      학술적 인사이트를 배양하세요.
    </p>
    <div class="hero-buttons">
      <button class="btn-primary" onclick="document.getElementById('apply').scrollIntoView({behavior:'smooth'})">지원하기 →</button>
      <button class="btn-outline" onclick="document.getElementById('departments').scrollIntoView({behavior:'smooth'})">더 알아보기</button>
    </div>
  </div>
  <div class="scroll-hint">
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M12 5v14M5 12l7 7 7-7"/></svg>
    SCROLL
  </div>
</section>

<!-- ── STATS ─────────────────────────────────────────────────── -->
<div class="stats-section">
  <div class="stats-grid">
    <div class="stat-item fade-up">
      <div class="stat-num">50<span style="font-size:1.4rem">+</span></div>
      <div class="stat-label">Active Members</div>
    </div>
    <div class="stat-item fade-up fade-up-delay-1">
      <div class="stat-num">4</div>
      <div class="stat-label">Departments</div>
    </div>
    <div class="stat-item fade-up fade-up-delay-2">
      <div class="stat-num">20<span style="font-size:1.4rem">+</span></div>
      <div class="stat-label">Research Reports</div>
    </div>
    <div class="stat-item fade-up fade-up-delay-3">
      <div class="stat-num">3<span style="font-size:1.4rem">기</span></div>
      <div class="stat-label">운영 기수</div>
    </div>
  </div>
</div>

<!-- ── DEPARTMENTS ───────────────────────────────────────────── -->
<section class="dept-section" id="departments">
  <div class="section-inner">
    <div class="section-header">
      <div class="section-eyebrow">Our Departments</div>
      <h2 class="section-title">RESEARCH &amp; <span class="gold">DEPARTMENTS</span></h2>
      <div class="section-divider"></div>
    </div>
    <div class="dept-grid">
      <div class="dept-card fade-up">
        <div class="dept-icon">🏢</div>
        <div class="dept-tag">리서치 1팀</div>
        <div class="dept-name">CAPITAL MARKETS &amp;<br>REAL ESTATE PF</div>
        <div class="dept-desc">부동산 PF, 대체투자, 자본시장 전반에 대한 깊이 있는 분석과 실제 딜케이스 스터디를 진행합니다.</div>
      </div>
      <div class="dept-card fade-up fade-up-delay-1">
        <div class="dept-icon">📈</div>
        <div class="dept-tag">리서치 2팀</div>
        <div class="dept-name">CORPORATE M&amp;A &amp; IPO</div>
        <div class="dept-desc">기업가치평가(Valuation), 재무 모델링, 공모주 시장 분석 및 실제 M&amp;A 사례를 연구합니다.</div>
      </div>
      <div class="dept-card fade-up fade-up-delay-2">
        <div class="dept-icon">🌐</div>
        <div class="dept-tag">콘텐츠 / 홍보팀</div>
        <div class="dept-name">INSIGHT PUBLISHING</div>
        <div class="dept-desc">동아리 공식 웹사이트 및 SNS 플랫폼을 운영하고, 금융 트렌드를 반영한 양질의 콘텐츠를 기획 발행합니다.</div>
      </div>
      <div class="dept-card fade-up fade-up-delay-3">
        <div class="dept-icon">🤝</div>
        <div class="dept-tag">이벤트 기획팀</div>
        <div class="dept-name">NETWORKING &amp; EVENTS</div>
        <div class="dept-desc">현업 선배(여의도/금융권) 초청 세미나, 타 학회와의 교류 등 다양한 네트워킹 및 학습 행사를 기획하고 총괄합니다.</div>
      </div>
    </div>
  </div>
</section>

<!-- ── WHY FINBASE ───────────────────────────────────────────── -->
<section class="why-section">
  <div class="section-inner">
    <div class="section-header">
      <div class="section-eyebrow">Why Join Us</div>
      <h2 class="section-title">FINBASE를 <span class="gold">선택해야 하는 이유</span></h2>
      <div class="section-divider"></div>
      <p class="section-sub">금융 현장과 가장 가까운 학회, FINBASE에서 커리어를 시작하세요.</p>
    </div>
    <div class="why-grid">
      <div class="why-card fade-up">
        <div class="why-icon">💼</div>
        <div class="why-text">
          <h4>Real-World Deal Study</h4>
          <p>실제 거래 케이스를 바탕으로 한 딜 스터디로 현장 감각을 키웁니다. 단순 이론이 아닌 실전 적용 능력을 배웁니다.</p>
        </div>
      </div>
      <div class="why-card fade-up fade-up-delay-1">
        <div class="why-icon">🧠</div>
        <div class="why-text">
          <h4>Expert Mentorship</h4>
          <p>여의도 IB, 자산운용, 컨설팅 현직자와 직접 연결되는 멘토링 프로그램으로 인사이트를 나눕니다.</p>
        </div>
      </div>
      <div class="why-card fade-up fade-up-delay-2">
        <div class="why-icon">📊</div>
        <div class="why-text">
          <h4>Research Publication</h4>
          <p>직접 작성한 리서치 레포트를 공식 플랫폼에 발행하고, 포트폴리오로 활용할 수 있습니다.</p>
        </div>
      </div>
      <div class="why-card fade-up fade-up-delay-3">
        <div class="why-icon">🌏</div>
        <div class="why-text">
          <h4>Finance Network</h4>
          <p>금융권 취업을 희망하는 동료들과 함께 성장하며 강력한 네트워크를 구축할 수 있습니다.</p>
        </div>
      </div>
      <div class="why-card fade-up fade-up-delay-1">
        <div class="why-icon">🏆</div>
        <div class="why-text">
          <h4>Competition &amp; Awards</h4>
          <p>금융 공모전, 케이스 컴피티션 등 다양한 대외 활동 지원과 팀 구성을 도와드립니다.</p>
        </div>
      </div>
      <div class="why-card fade-up fade-up-delay-2">
        <div class="why-icon">📰</div>
        <div class="why-text">
          <h4>Finance News Terminal</h4>
          <p>매일 업데이트되는 금융 뉴스 터미널을 통해 시장 흐름을 놓치지 않고 트래킹합니다.</p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ── CHALLENGE ─────────────────────────────────────────────── -->
<section class="challenge-section" id="challenge">
  <div class="section-inner">
    <div class="challenge-box fade-up">
      <h2 class="challenge-title">FINBASE <span class="gold">CHALLENGE</span></h2>
      <p class="challenge-sub">간단한 금융 상식 퀴즈를 풀고 FINBASE에 도전해보세요!</p>
      <p class="challenge-question" id="quiz-question">Q. 경영학에서 'IPO'의 약자는 무엇을 의미할까요?</p>
      <div class="challenge-options" id="quiz-options">
        <button class="option-btn" onclick="checkAnswer(this, false)"><span class="opt-label">A.</span>초기 사모 투자 (Initial Private Offering)</button>
        <button class="option-btn" onclick="checkAnswer(this, true)"><span class="opt-label">B.</span>기업 공개 (Initial Public Offering)</button>
        <button class="option-btn" onclick="checkAnswer(this, false)"><span class="opt-label">C.</span>국제 조달 사무소 (International Procurement Office)</button>
        <button class="option-btn" onclick="checkAnswer(this, false)"><span class="opt-label">D.</span>내부 프로젝트 기획 (Internal Project Outline)</button>
      </div>
      <div class="challenge-result" id="quiz-result"></div>
    </div>
  </div>
</section>

<!-- ── APPLY ─────────────────────────────────────────────────── -->
<section class="apply-section" id="apply">
  <div class="apply-inner">
    <div class="section-eyebrow fade-up">Join FINBASE</div>
    <h2 class="fade-up" style="font-size:clamp(1.5rem,3vw,2.1rem);font-weight:900;margin-bottom:10px;">
      지금 바로 <span class="gold">지원하기</span>
    </h2>
    <p class="fade-up" style="color:var(--grey);font-family:'Noto Sans KR',sans-serif;font-size:.93rem;margin-bottom:36px;">
      구글 폼을 통해 지원서를 제출하거나 QR코드를 스캔하세요.
    </p>
    <div class="qr-box fade-up">
      <div class="qr-placeholder">[QR CODE PLACEHOLDER]</div>
    </div>
    <button class="btn-google-form fade-up">구글 폼 열기</button>
  </div>
</section>

<!-- ── FOOTER ────────────────────────────────────────────────── -->
<footer>
  <div class="footer-inner">
    <div class="footer-logo">
      <svg viewBox="0 0 36 36" fill="none" xmlns="http://www.w3.org/2000/svg">
        <polygon points="18,2 34,18 18,34 2,18" stroke="#f5b800" stroke-width="2" fill="none"/>
        <line x1="9" y1="18" x2="27" y2="18" stroke="#f5b800" stroke-width="1.5"/>
        <line x1="18" y1="7" x2="18" y2="20" stroke="#f5b800" stroke-width="1.5"/>
        <line x1="10" y1="22" x2="18" y2="30" stroke="#f5b800" stroke-width="1.5"/>
        <line x1="26" y1="22" x2="18" y2="30" stroke="#f5b800" stroke-width="1.5"/>
      </svg>
      <span>FINBASE</span>
    </div>
    <div class="footer-copy">© 2026 FINBASE Academic Club. All rights reserved.</div>
    <div class="footer-links">
      <a href="#">INSTAGRAM</a>
      <a href="#">LINKEDIN</a>
      <a href="#">CONTACT</a>
    </div>
  </div>
</footer>

<!-- ── SCRIPTS ───────────────────────────────────────────────── -->
<script>
  /* ── Mobile Menu ── */
  function toggleMenu() {
    const m = document.getElementById('mobileMenu');
    m.classList.toggle('open');
    document.body.style.overflow = m.classList.contains('open') ? 'hidden' : '';
  }

  /* ── Quiz ── */
  function checkAnswer(btn, isCorrect) {
    const opts = document.querySelectorAll('.option-btn');
    const result = document.getElementById('quiz-result');
    opts.forEach(o => o.disabled = true);
    if (isCorrect) {
      btn.classList.add('correct');
      result.textContent = '✅ 정답입니다! IPO = Initial Public Offering (기업공개)';
      result.className = 'challenge-result correct';
    } else {
      btn.classList.add('wrong');
      opts[1].classList.add('correct'); // B is correct
      result.textContent = '❌ 아쉽네요! 정답은 B. 기업 공개 (Initial Public Offering)입니다.';
      result.className = 'challenge-result wrong';
    }
  }

  /* ── Scroll Fade-Up ── */
  const observer = new IntersectionObserver((entries) => {
    entries.forEach(e => {
      if (e.isIntersecting) { e.target.classList.add('visible'); }
    });
  }, { threshold: 0.12 });
  document.querySelectorAll('.fade-up').forEach(el => observer.observe(el));

  /* ── Smooth header hide on scroll ── */
  let lastY = 0;
  const header = document.querySelector('header');
  window.addEventListener('scroll', () => {
    const y = window.scrollY;
    if (y > lastY && y > 80) header.style.transform = 'translateY(-100%)';
    else header.style.transform = 'translateY(0)';
    lastY = y;
    header.style.transition = 'transform .3s ease';
  });
</script>
</body>
</html>
