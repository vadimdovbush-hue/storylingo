<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>StoryLingo — Learn English Through Stories</title>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,600;0,700;1,400&family=Inter:wght@300;400;500;600&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet" />
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    :root {
      --bg: #08090c;
      --bg1: #0e1018;
      --bg2: #141720;
      --bg3: #1c2030;
      --border: rgba(255,255,255,0.06);
      --border2: rgba(255,255,255,0.10);
      --border3: rgba(255,255,255,0.16);
      --text: #e8eaf0;
      --text2: #8b90a0;
      --text3: #4a5068;
      --gold: #c9a84c;
      --gold2: #e8c878;
      --gold3: rgba(201,168,76,0.12);
      --red: #b22234;
      --red2: #dc143c;
      --blue: #3c3b6e;
      --blue2: #4a4896;
      --teal: #4ab8c8;
      --green: #34c97a;
      --radius: 12px;
      --radius2: 8px;
    }

    html { scroll-behavior: smooth; }
    body {
      font-family: 'Inter', -apple-system, sans-serif;
      background: var(--bg);
      color: var(--text);
      min-height: 100vh;
      overflow-x: hidden;
    }

    /* ── SCREENS ── */
    .screen { display: none; animation: fadeIn 0.4s ease; }
    .screen.active { display: block; }
    @keyframes fadeIn { from { opacity: 0; transform: translateY(8px); } to { opacity: 1; transform: translateY(0); } }

    /* ══════════════════════════════════════
       GENERATOR SCREEN
    ══════════════════════════════════════ */
    .gen-page { min-height: 100vh; }

    /* Hero */
    .gen-hero {
      position: relative;
      padding: 80px 32px 64px;
      text-align: center;
      overflow: hidden;
    }
    .hero-flag {
      position: absolute;
      inset: 0;
      opacity: 0.03;
      background:
        repeating-linear-gradient(
          transparent, transparent 40px,
          #b22234 40px, #b22234 80px
        );
      pointer-events: none;
    }
    .hero-flag::after {
      content: '🇺🇸';
      position: absolute;
      font-size: 180px;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -55%);
      opacity: 0.4;
      filter: grayscale(0.3);
    }
    .hero-eyebrow {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      border: 1px solid var(--border2);
      border-radius: 20px;
      padding: 5px 14px;
      font-size: 11px;
      letter-spacing: 2px;
      text-transform: uppercase;
      color: var(--gold);
      margin-bottom: 24px;
      position: relative;
      background: rgba(201,168,76,0.06);
    }
    .hero-eyebrow span { color: var(--text3); }
    .gen-hero h1 {
      font-family: 'Playfair Display', serif;
      font-size: clamp(40px, 6vw, 68px);
      font-weight: 700;
      color: var(--text);
      letter-spacing: -1px;
      line-height: 1.1;
      margin-bottom: 16px;
      position: relative;
    }
    .gen-hero h1 em { color: var(--gold); font-style: italic; }
    .gen-hero .sub {
      font-size: 16px;
      color: var(--text2);
      max-width: 440px;
      margin: 0 auto;
      line-height: 1.6;
      position: relative;
    }

    /* Form */
    .gen-form {
      max-width: 660px;
      margin: 0 auto;
      padding: 0 24px 80px;
    }

    .form-block {
      background: var(--bg1);
      border: 1px solid var(--border);
      border-radius: var(--radius);
      padding: 24px;
      margin-bottom: 16px;
    }
    .block-label {
      font-size: 10px;
      letter-spacing: 2px;
      text-transform: uppercase;
      color: var(--text3);
      font-weight: 600;
      margin-bottom: 16px;
      display: flex;
      align-items: center;
      gap: 10px;
    }
    .block-label::after { content: ''; flex: 1; height: 1px; background: var(--border); }

    textarea.words-input {
      width: 100%;
      background: var(--bg);
      border: 1px solid var(--border);
      border-radius: var(--radius2);
      padding: 14px 16px;
      color: var(--text);
      font-family: 'Inter', sans-serif;
      font-size: 15px;
      line-height: 1.7;
      resize: none;
      outline: none;
      min-height: 96px;
      transition: border-color 0.2s;
    }
    textarea.words-input:focus { border-color: var(--border3); }
    textarea.words-input::placeholder { color: var(--text3); }
    .words-hint { font-size: 12px; color: var(--text3); margin-top: 8px; }

    .settings-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 14px;
    }
    @media(max-width:520px){ .settings-grid { grid-template-columns: 1fr; } }

    .setting-item label {
      font-size: 10px;
      letter-spacing: 1.5px;
      text-transform: uppercase;
      color: var(--text3);
      font-weight: 600;
      display: block;
      margin-bottom: 8px;
    }
    .setting-item select {
      width: 100%;
      background: var(--bg);
      border: 1px solid var(--border);
      border-radius: var(--radius2);
      color: var(--text);
      font-family: 'Inter', sans-serif;
      font-size: 13px;
      padding: 10px 32px 10px 12px;
      outline: none;
      cursor: pointer;
      appearance: none;
      background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='10' height='10' viewBox='0 0 24 24' fill='none' stroke='%234a5068' stroke-width='2'%3E%3Cpath d='M6 9l6 6 6-6'/%3E%3C/svg%3E");
      background-repeat: no-repeat;
      background-position: right 10px center;
      transition: border-color 0.2s;
    }
    .setting-item select:focus { border-color: var(--border3); }
    .setting-item select option { background: #1c2030; }

    /* Generate button */
    .gen-btn {
      width: 100%;
      background: var(--gold);
      border: none;
      border-radius: var(--radius2);
      color: #08090c;
      font-family: 'Inter', sans-serif;
      font-size: 14px;
      font-weight: 600;
      letter-spacing: 1px;
      padding: 16px;
      cursor: pointer;
      transition: all 0.25s;
      text-transform: uppercase;
      margin-top: 4px;
    }
    .gen-btn:hover:not(:disabled) { background: var(--gold2); transform: translateY(-1px); box-shadow: 0 8px 32px rgba(201,168,76,0.2); }
    .gen-btn:active:not(:disabled) { transform: translateY(0); }
    .gen-btn:disabled { opacity: 0.4; cursor: not-allowed; }

    /* Status */
    .gen-status {
      margin-top: 16px;
      text-align: center;
      font-size: 13px;
      color: var(--text2);
      min-height: 20px;
      font-style: italic;
    }
    .gen-status.err { color: #ff6b6b; font-style: normal; }

    /* ── LOADER ── */
    .loader-overlay {
      display: none;
      position: fixed;
      inset: 0;
      background: rgba(8,9,12,0.92);
      z-index: 1000;
      align-items: center;
      justify-content: center;
      flex-direction: column;
      gap: 32px;
      backdrop-filter: blur(8px);
    }
    .loader-overlay.show { display: flex; }
    .loader-ring {
      width: 64px;
      height: 64px;
      border: 2px solid var(--border2);
      border-top-color: var(--gold);
      border-radius: 50%;
      animation: spin 0.9s linear infinite;
    }
    @keyframes spin { to { transform: rotate(360deg); } }
    .loader-text {
      font-family: 'Playfair Display', serif;
      font-size: 18px;
      color: var(--text2);
      font-style: italic;
      text-align: center;
    }
    .loader-sub { font-size: 12px; color: var(--text3); letter-spacing: 1px; text-transform: uppercase; }

    /* ══════════════════════════════════════
       READER SCREEN
    ══════════════════════════════════════ */
    .reader-page { min-height: 100vh; }

    /* Topbar */
    .reader-bar {
      position: sticky;
      top: 0;
      z-index: 200;
      background: rgba(8,9,12,0.9);
      backdrop-filter: blur(16px);
      -webkit-backdrop-filter: blur(16px);
      border-bottom: 1px solid var(--border);
      padding: 0 24px;
      height: 56px;
      display: flex;
      align-items: center;
      gap: 16px;
    }
    .bar-btn {
      height: 32px;
      padding: 0 14px;
      background: none;
      border: 1px solid var(--border2);
      border-radius: 6px;
      color: var(--text2);
      font-size: 12px;
      font-family: 'Inter', sans-serif;
      cursor: pointer;
      transition: all 0.2s;
      white-space: nowrap;
      display: flex;
      align-items: center;
      gap: 6px;
    }
    .bar-btn:hover { color: var(--text); border-color: var(--border3); }
    .bar-btn.active { color: var(--gold); border-color: var(--gold3); background: var(--gold3); }
    .bar-divider { width: 1px; height: 20px; background: var(--border); }
    .bar-spacer { flex: 1; }
    .bar-vocab-count {
      font-size: 12px;
      color: var(--text3);
      font-family: 'JetBrains Mono', monospace;
      white-space: nowrap;
    }
    .bar-vocab-count span { color: var(--gold); }
    .bar-timer {
      font-family: 'JetBrains Mono', monospace;
      font-size: 12px;
      color: var(--text3);
    }
    .progress-track {
      position: absolute;
      bottom: 0;
      left: 0;
      right: 0;
      height: 2px;
      background: var(--border);
    }
    .progress-fill {
      height: 100%;
      background: linear-gradient(90deg, var(--gold), var(--teal));
      width: 0%;
      transition: width 0.15s;
    }

    /* Story content */
    .reader-wrap {
      max-width: 740px;
      margin: 0 auto;
      padding: 56px 32px 80px;
    }
    @media(max-width:600px){ .reader-wrap { padding: 32px 20px 60px; } }

    .story-title {
      font-family: 'Playfair Display', serif;
      font-size: clamp(26px, 4vw, 38px);
      font-weight: 700;
      color: var(--text);
      line-height: 1.2;
      margin-bottom: 8px;
      letter-spacing: -0.5px;
    }
    .story-byline {
      font-size: 13px;
      color: var(--text3);
      margin-bottom: 48px;
      display: flex;
      align-items: center;
      gap: 12px;
    }
    .story-byline::after { content: ''; flex: 1; height: 1px; background: var(--border); }

    .story-body { font-size: 18px; line-height: 1.95; color: #c8cad4; font-weight: 300; }
    .story-body p { margin-bottom: 1.5em; }
    .story-body h2 {
      font-family: 'Playfair Display', serif;
      font-size: 22px;
      color: var(--text);
      margin: 2em 0 0.8em;
      font-weight: 600;
      border-left: 2px solid var(--gold);
      padding-left: 16px;
    }

    /* Vocab words */
    .vw {
      color: var(--gold);
      border-bottom: 1px solid rgba(201,168,76,0.3);
      cursor: pointer;
      transition: all 0.15s;
    }
    .vw:hover { color: var(--gold2); border-bottom-color: var(--gold); }
    .vw.seen { color: var(--teal); border-bottom-color: rgba(74,184,200,0.3); }

    /* Focus mode */
    body.focus-mode .reader-bar .bar-btn:not(.focus-btn):not(.back-btn) { opacity: 0; pointer-events: none; }
    body.focus-mode .story-byline { opacity: 0.4; }

    /* ── POPUP ── */
    .word-popup {
      position: fixed;
      z-index: 9000;
      display: none;
      pointer-events: none;
    }
    .word-popup.visible { display: block; }
    .popup-inner {
      background: var(--bg2);
      border: 1px solid var(--border2);
      border-radius: var(--radius);
      padding: 18px 20px;
      box-shadow: 0 24px 64px rgba(0,0,0,0.8), 0 0 0 1px rgba(255,255,255,0.03);
      min-width: 200px;
      max-width: 280px;
    }
    .popup-word { font-family: 'Playfair Display', serif; font-size: 22px; color: var(--gold); font-weight: 600; line-height: 1; margin-bottom: 6px; }
    .popup-transcr { font-family: 'JetBrains Mono', monospace; font-size: 12px; color: var(--teal); margin-bottom: 10px; opacity: 0.8; }
    .popup-divider { height: 1px; background: var(--border); margin-bottom: 10px; }
    .popup-trans { font-size: 15px; color: var(--text); line-height: 1.4; }
    .popup-trans.loading { color: var(--text3); font-style: italic; font-size: 13px; }
    .popup-phrase { font-size: 13px; color: var(--text2); margin-top: 8px; padding-top: 8px; border-top: 1px solid var(--border); line-height: 1.4; font-style: italic; }

    /* ── VOCAB TABLE SECTION ── */
    .vocab-section {
      max-width: 740px;
      margin: 0 auto;
      padding: 0 32px 80px;
    }
    .section-head {
      display: flex;
      align-items: center;
      justify-content: space-between;
      margin-bottom: 20px;
    }
    .section-head h2 { font-family: 'Playfair Display', serif; font-size: 22px; color: var(--text); }
    .section-head .seen-badge {
      font-size: 12px;
      color: var(--text3);
      font-family: 'JetBrains Mono', monospace;
    }
    .section-head .seen-badge b { color: var(--gold); }

    .vocab-table { width: 100%; border-collapse: collapse; }
    .vocab-table th {
      text-align: left;
      font-size: 10px;
      letter-spacing: 1.5px;
      text-transform: uppercase;
      color: var(--text3);
      padding: 8px 12px;
      border-bottom: 1px solid var(--border);
      font-weight: 600;
    }
    .vocab-table td { padding: 12px; border-bottom: 1px solid var(--border); font-size: 14px; vertical-align: middle; }
    .vocab-table tr:hover td { background: var(--bg1); }
    .vocab-table tr:last-child td { border-bottom: none; }
    .vt-word { font-family: 'Playfair Display', serif; color: var(--gold); font-size: 17px; }
    .vt-tr { font-family: 'JetBrains Mono', monospace; color: var(--teal); font-size: 11px; opacity: 0.7; }
    .vt-uk { color: var(--text); }
    .vt-uk.loading { color: var(--text3); font-style: italic; }
    .vt-star { text-align: center; cursor: pointer; font-size: 16px; opacity: 0.3; transition: all 0.2s; user-select: none; }
    .vt-star:hover { opacity: 1; transform: scale(1.2); }
    .vt-star.active { opacity: 1; }
    .vt-seen-dot { text-align: center; }
    .dot { display: inline-block; width: 7px; height: 7px; border-radius: 50%; background: var(--border2); transition: all 0.3s; }
    .dot.on { background: var(--teal); box-shadow: 0 0 6px rgba(74,184,200,0.5); }

    /* ── QUIZ ── */
    .quiz-section {
      max-width: 740px;
      margin: 0 auto;
      padding: 0 32px 80px;
    }
    .quiz-card {
      background: var(--bg1);
      border: 1px solid var(--border);
      border-radius: var(--radius);
      padding: 32px;
    }
    .quiz-header { display: flex; align-items: center; justify-content: space-between; margin-bottom: 8px; }
    .quiz-header h2 { font-family: 'Playfair Display', serif; font-size: 22px; color: var(--text); }
    .quiz-counter { font-family: 'JetBrains Mono', monospace; font-size: 12px; color: var(--text3); }
    .quiz-progress-bar { height: 2px; background: var(--border); border-radius: 2px; margin-bottom: 32px; }
    .quiz-progress-fill { height: 100%; background: var(--gold); border-radius: 2px; transition: width 0.3s; }
    .quiz-question { font-size: 17px; color: var(--text2); margin-bottom: 24px; line-height: 1.5; }
    .quiz-question strong { color: var(--text); font-weight: 600; }
    .quiz-options { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; }
    .quiz-opt {
      background: var(--bg);
      border: 1px solid var(--border2);
      border-radius: var(--radius2);
      padding: 14px 16px;
      font-size: 14px;
      color: var(--text);
      cursor: pointer;
      transition: all 0.2s;
      text-align: left;
      font-family: 'Inter', sans-serif;
    }
    .quiz-opt:hover { border-color: var(--border3); background: var(--bg2); }
    .quiz-opt.correct { border-color: var(--green); color: var(--green); background: rgba(52,201,122,0.08); }
    .quiz-opt.wrong { border-color: #ff6b6b; color: #ff6b6b; background: rgba(255,107,107,0.08); }
    .quiz-result { text-align: center; padding: 24px 0 0; }
    .quiz-score { font-family: 'Playfair Display', serif; font-size: 48px; color: var(--gold); font-weight: 700; }
    .quiz-score-label { font-size: 14px; color: var(--text2); margin-bottom: 24px; }
    .quiz-restart {
      background: none;
      border: 1px solid var(--border2);
      border-radius: var(--radius2);
      color: var(--text2);
      font-size: 13px;
      padding: 10px 20px;
      cursor: pointer;
      font-family: 'Inter', sans-serif;
      transition: all 0.2s;
    }
    .quiz-restart:hover { border-color: var(--border3); color: var(--text); }

    /* Divider */
    .section-divider {
      max-width: 740px;
      margin: 0 auto 48px;
      border: none;
      border-top: 1px solid var(--border);
    }

    /* PDF / regen bar */
    .action-bar {
      max-width: 740px;
      margin: 0 auto;
      padding: 0 32px 32px;
      display: flex;
      gap: 10px;
    }
    .action-btn {
      flex: 1;
      background: var(--bg1);
      border: 1px solid var(--border);
      border-radius: var(--radius2);
      color: var(--text2);
      font-size: 13px;
      padding: 12px;
      cursor: pointer;
      font-family: 'Inter', sans-serif;
      transition: all 0.2s;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 8px;
    }
    .action-btn:hover { border-color: var(--border3); color: var(--text); background: var(--bg2); }
    .action-btn.gold { border-color: rgba(201,168,76,0.3); color: var(--gold); }
    .action-btn.gold:hover { background: var(--gold3); }

    /* Scrollbar */
    ::-webkit-scrollbar { width: 4px; }
    ::-webkit-scrollbar-track { background: var(--bg); }
    ::-webkit-scrollbar-thumb { background: var(--bg3); border-radius: 4px; }

    /* Flag stripe accent */
    .flag-stripe {
      height: 3px;
      background: linear-gradient(90deg, var(--blue2) 0%, var(--blue2) 33%, #fff 33%, #fff 34%, var(--red) 34%, var(--red) 67%, #fff 67%, #fff 68%, var(--blue2) 68%);
      opacity: 0.4;
    }
  </style>
</head>
<body>

<!-- Loader -->
<div class="loader-overlay" id="loader">
  <div class="loader-ring"></div>
  <div>
    <div class="loader-text" id="loader-text">Crafting your story…</div>
    <div class="loader-sub" style="margin-top:8px;text-align:center" id="loader-sub">Powered by Claude AI</div>
  </div>
</div>

<!-- Word popup -->
<div class="word-popup" id="word-popup">
  <div class="popup-inner">
    <div class="popup-word" id="popup-word"></div>
    <div class="popup-transcr" id="popup-transcr"></div>
    <div class="popup-divider"></div>
    <div class="popup-trans loading" id="popup-trans">translating…</div>
  </div>
</div>

<!-- ══ GENERATOR ══ -->
<div class="screen active" id="screen-gen">
  <div class="gen-page">
    <div class="flag-stripe"></div>
    <div class="gen-hero">
      <div class="hero-flag"></div>
      <div class="hero-eyebrow">🇺🇸 <span>American English</span> · AI-Powered</div>
      <h1>Story<em>Lingo</em></h1>
      <p class="sub">Enter words you want to master — get a personalized story that uses them naturally, again and again.</p>
    </div>

    <div class="gen-form">
      <div class="form-block">
        <div class="block-label">Vocabulary words</div>
        <textarea class="words-input" id="words-input" placeholder="exhausted, determined, bliss, wanderer, solitude&#10;&#10;Separate words with commas or new lines…" rows="4"></textarea>
        <div class="words-hint">Up to 20 words · each will appear multiple times in context</div>
      </div>

      <div class="form-block">
        <div class="block-label">Story settings</div>
        <div class="settings-grid">
          <div class="setting-item">
            <label>Topic</label>
            <select id="sel-topic">
              <option value="travel and adventure in Southeast Asia">✈ Travel & Adventure</option>
              <option value="a romantic story about connection and love">❤ Romance</option>
              <option value="business startups and career ambitions">💼 Business</option>
              <option value="a psychological mystery or thriller">🔍 Mystery / Thriller</option>
              <option value="survival in nature and self-discovery">🌿 Nature & Survival</option>
              <option value="personal growth friendship and life lessons">🌟 Personal Growth</option>
            </select>
          </div>
          <div class="setting-item">
            <label>Length</label>
            <select id="sel-length">
              <option value="300">300 words — quick</option>
              <option value="500" selected>500 words — short</option>
              <option value="1000">1 000 words — medium</option>
              <option value="2000">2 000 words — long</option>
            </select>
          </div>
          <div class="setting-item">
            <label>Level</label>
            <select id="sel-level">
              <option value="A1">A1 — Beginner</option>
              <option value="A2" selected>A2 — Elementary</option>
              <option value="B1">B1 — Intermediate</option>
              <option value="B2">B2 — Upper-Intermediate</option>
            </select>
          </div>
          <div class="setting-item">
            <label>Repetitions</label>
            <select id="sel-reps">
              <option value="3" selected>3× each word</option>
              <option value="5">5× each word</option>
              <option value="8">8× each word</option>
            </select>
          </div>
        </div>
      </div>

      <button class="gen-btn" id="gen-btn" onclick="generateStory()">Generate Story</button>
      <div class="gen-status" id="gen-status"></div>
    </div>
  </div>
</div>

<!-- ══ READER ══ -->
<div class="screen" id="screen-reader">
  <div class="reader-page">
    <div class="flag-stripe"></div>

    <!-- Top bar -->
    <div class="reader-bar">
      <button class="bar-btn back-btn" onclick="showGen()">← Back</button>
      <div class="bar-divider"></div>
      <button class="bar-btn focus-btn" onclick="toggleFocus(this)" title="Focus mode">Focus</button>
      <button class="bar-btn" onclick="speakStory()" id="speak-btn" title="Read aloud">▶ Listen</button>
      <div class="bar-spacer"></div>
      <div class="bar-vocab-count"><span id="seen-count">0</span>/<span id="total-count">0</span> words</div>
      <div class="bar-divider"></div>
      <div class="bar-timer" id="timer">0:00</div>
      <div class="progress-track"><div class="progress-fill" id="progress-fill"></div></div>
    </div>

    <!-- Story -->
    <div class="reader-wrap">
      <div class="story-title" id="story-title"></div>
      <div class="story-byline" id="story-byline">AI-generated · StoryLingo</div>
      <div class="story-body" id="story-body"></div>
    </div>

    <!-- Action bar -->
    <div class="action-bar">
      <button class="action-btn gold" onclick="regenStory()">↺ Regenerate</button>
      <button class="action-btn" onclick="savePDF()">↓ Save PDF</button>
      <button class="action-btn" onclick="scrollToQuiz()">Quiz →</button>
    </div>

    <hr class="section-divider" />

    <!-- Vocab table -->
    <div class="vocab-section">
      <div class="section-head">
        <h2>Vocabulary</h2>
        <div class="seen-badge">Seen: <b id="seen-count2">0</b>/<b id="total-count2">0</b></div>
      </div>
      <table class="vocab-table">
        <thead>
          <tr>
            <th>Word</th>
            <th>Transcription</th>
            <th>Ukrainian</th>
            <th style="text-align:center">⭐</th>
            <th style="text-align:center">✓</th>
          </tr>
        </thead>
        <tbody id="vocab-tbody"></tbody>
      </table>
    </div>

    <hr class="section-divider" />

    <!-- Quiz -->
    <div class="quiz-section" id="quiz-section">
      <div class="quiz-card">
        <div class="quiz-header">
          <h2>Quick Quiz</h2>
          <div class="quiz-counter" id="quiz-counter">1 / 5</div>
        </div>
        <div class="quiz-progress-bar"><div class="quiz-progress-fill" id="quiz-progress-fill" style="width:0%"></div></div>
        <div id="quiz-body"></div>
      </div>
    </div>

  </div>
</div>

<script>
// ── Transcriptions ──────────────────────────────────────────────────────────
const TRANSCR = {
  exhausted:'ɪɡˈzɔːstɪd',determined:'dɪˈtɜːrmɪnd',bliss:'blɪs',wanderer:'ˈwɒndərər',
  solitude:'ˈsɒlɪtjuːd',effort:'ˈefərt',imperfectly:'ɪmˈpɜːrfɪktli',empty:'ˈempti',
  stood:'stʊd',uncertain:'ʌnˈsɜːrtn',journey:'ˈdʒɜːrni',adventure:'ədˈventʃər',
  beautiful:'ˈbjuːtɪfl',wonderful:'ˈwʌndərfl',amazing:'əˈmeɪzɪŋ',discover:'dɪˈskʌvər',
  freedom:'ˈfriːdəm',courage:'ˈkʌrɪdʒ',hope:'həʊp',dream:'driːm',believe:'bɪˈliːv',
  achieve:'əˈtʃiːv',success:'səkˈses',failure:'ˈfeɪljər',opportunity:'ˌɒpəˈtjuːnɪti',
  challenge:'ˈtʃælɪndʒ',grateful:'ˈɡreɪtfl',peaceful:'ˈpiːsfl',passionate:'ˈpæʃənət',
  confident:'ˈkɒnfɪdənt',inspired:'ɪnˈspaɪərd',anxious:'ˈæŋkʃəs',brave:'breɪv',
  calm:'kɑːm',curious:'ˈkjʊəriəs',elegant:'ˈelɪɡənt',fierce:'fɪərs',gentle:'ˈdʒentl',
  humble:'ˈhʌmbl',joyful:'ˈdʒɔɪfl',lonely:'ˈləʊnli',mysterious:'mɪˈstɪəriəs',
  noble:'ˈnəʊbl',patient:'ˈpeɪʃənt',quiet:'ˈkwaɪət',restless:'ˈrestləs',
  sincere:'sɪnˈsɪər',tender:'ˈtendər',unique:'juːˈniːk',vivid:'ˈvɪvɪd',
  weary:'ˈwɪəri',yearning:'ˈjɜːrnɪŋ',flourish:'ˈflʌrɪʃ',perish:'ˈperɪʃ',
  whisper:'ˈwɪspər',shadow:'ˈʃædəʊ',silence:'ˈsaɪləns',linger:'ˈlɪŋɡər',
  tremble:'ˈtrembl',wander:'ˈwɒndər',stumble:'ˈstʌmbl',gather:'ˈɡæðər',
  breathe:'briːð',awaken:'əˈweɪkən',survive:'səˈvaɪv',escape:'ɪˈskeɪp',
  embrace:'ɪmˈbreɪs',glimmer:'ˈɡlɪmər',shimmer:'ˈʃɪmər',hunger:'ˈhʌŋɡər',
  shiver:'ˈʃɪvər',roam:'rəʊm',scatter:'ˈskætər',inhale:'ɪnˈheɪl',exhale:'eksˈheɪl'
};

// ── State ───────────────────────────────────────────────────────────────────
let vocabWords = [];
let seenWords  = new Set();
let favorites  = new Set();
let transCache = {};
let currentPrompt = '';
let timerInterval = null;
let timerSeconds  = 0;
let isSpeaking    = false;
let currentMeta   = {};
let quizState     = { questions:[], idx:0, score:0, done:false };

// ── Audio click ─────────────────────────────────────────────────────────────
function playClick() {
  try {
    const ctx = new (window.AudioContext || window.webkitAudioContext)();
    const o = ctx.createOscillator();
    const g = ctx.createGain();
    o.connect(g); g.connect(ctx.destination);
    o.frequency.value = 880; o.type = 'sine';
    g.gain.setValueAtTime(0.08, ctx.currentTime);
    g.gain.exponentialRampToValueAtTime(0.001, ctx.currentTime + 0.08);
    o.start(); o.stop(ctx.currentTime + 0.08);
  } catch(e){}
}

// ── Speak word ──────────────────────────────────────────────────────────────
function speakWord(word) {
  if (!window.speechSynthesis) return;
  window.speechSynthesis.cancel();
  const u = new SpeechSynthesisUtterance(word);
  u.lang = 'en-US'; u.rate = 0.85;
  window.speechSynthesis.speak(u);
}

// ── Speak story ─────────────────────────────────────────────────────────────
function speakStory() {
  const btn = document.getElementById('speak-btn');
  if (isSpeaking) {
    window.speechSynthesis.cancel();
    isSpeaking = false; btn.textContent = '▶ Listen'; return;
  }
  const text = document.getElementById('story-body').innerText;
  const u = new SpeechSynthesisUtterance(text);
  u.lang = 'en-US'; u.rate = 0.9;
  u.onend = () => { isSpeaking = false; btn.textContent = '▶ Listen'; };
  window.speechSynthesis.speak(u);
  isSpeaking = true; btn.textContent = '⏹ Stop';
}

// ── Timer ───────────────────────────────────────────────────────────────────
function startTimer() {
  timerSeconds = 0;
  clearInterval(timerInterval);
  timerInterval = setInterval(() => {
    timerSeconds++;
    const m = Math.floor(timerSeconds/60);
    const s = timerSeconds % 60;
    document.getElementById('timer').textContent = m + ':' + String(s).padStart(2,'0');
  }, 1000);
}
function stopTimer() { clearInterval(timerInterval); }

// ── Parse words ─────────────────────────────────────────────────────────────
function parseWords(raw) {
  return [...new Set(
    raw.split(/[\n,]+/).map(w=>w.trim().toLowerCase()).filter(w=>w.length>1&&/^[a-z]/i.test(w))
  )].slice(0,20);
}

// ── Highlight vocab ──────────────────────────────────────────────────────────
function highlight(text, words) {
  const sorted = [...words].sort((a,b)=>b.length-a.length);
  const rx = new RegExp(`\\b(${sorted.map(w=>w.replace(/[.*+?^${}()|[\]\\]/g,'\\$&')).join('|')})\\b`,'gi');
  return text.replace(rx, m => {
    const lw = m.toLowerCase();
    return `<span class="vw" data-word="${lw}" onclick="onVwClick(event,this,'${lw}')">${m}</span>`;
  });
}

// ── API call ─────────────────────────────────────────────────────────────────
async function callClaude(prompt) {
  const res = await fetch('/.netlify/functions/generate', {
    method:'POST',
    headers:{'Content-Type':'application/json'},
    body: JSON.stringify({ messages:[{role:'user',content:prompt}] })
  });
  const data = await res.json();
  if (!res.ok) throw new Error(data.error||`HTTP ${res.status}`);
  return data.content[0].text;
}

// ── Translate ────────────────────────────────────────────────────────────────
async function translate(word) {
  if (transCache[word]) return transCache[word];
  try {
    const r = await fetch(`https://api.mymemory.translated.net/get?q=${encodeURIComponent(word)}&langpair=en|uk`);
    const d = await r.json();
    const t = d.responseData?.translatedText || word;
    transCache[word] = t; return t;
  } catch { return word; }
}

async function translatePhrase(phrase) {
  try {
    const r = await fetch(`https://api.mymemory.translated.net/get?q=${encodeURIComponent(phrase)}&langpair=en|uk`);
    const d = await r.json();
    return d.responseData?.translatedText || '';
  } catch { return ''; }
}

// ── Generate story ────────────────────────────────────────────────────────────
async function generateStory(regen) {
  const rawWords = document.getElementById('words-input').value;
  const words = parseWords(rawWords);
  if (!words.length) { setStatus('Please enter at least one word','err'); return; }

  const topic  = document.getElementById('sel-topic').value;
  const length = document.getElementById('sel-length').value;
  const level  = document.getElementById('sel-level').value;
  const reps   = document.getElementById('sel-reps').value;

  currentMeta = {topic,length,level,reps,words};

  const levelDesc = {
    A1:'Very simple short sentences. Only present and past tense. Basic vocabulary only.',
    A2:'Simple sentences. Common vocabulary. Basic grammar.',
    B1:'Moderate complexity. Varied vocabulary. Some idioms are fine.',
    B2:'Rich vocabulary. Complex sentences. Natural idiomatic English.'
  }[level];

  const prompt = `You are a creative writer and language teacher. Write a compelling ${length}-word story in English at ${level} level about: ${topic}.

Structure:
- Start with a creative TITLE on the first line (just the title, no "Title:" prefix)
- Then write the story in paragraphs
- Use 2-3 chapter/section headings (format: ## Heading Name) to break up the story
- Write vivid, engaging prose — not educational-sounding

Vocabulary requirement — each of these words must appear exactly ${reps} times:
${words.join(', ')}

Level ${level}: ${levelDesc}
Length: approximately ${length} words

Return ONLY the story with title. No preamble, no commentary.`;

  currentPrompt = prompt;

  showLoader(true);
  document.getElementById('gen-btn').disabled = true;

  try {
    const raw = await callClaude(prompt);
    showReader(raw, words, {topic,length,level});
  } catch(err) {
    showLoader(false);
    setStatus('Error: '+err.message,'err');
  } finally {
    document.getElementById('gen-btn').disabled = false;
  }
}

async function regenStory() {
  showLoader(true);
  try {
    const raw = await callClaude(currentPrompt);
    showReader(raw, currentMeta.words, currentMeta);
  } catch(err) {
    showLoader(false);
    alert('Error: '+err.message);
  }
}

// ── Loader ────────────────────────────────────────────────────────────────────
const loaderTexts = [
  'Crafting your story…','Weaving the narrative…','Placing your words…','Almost ready…'
];
let loaderTimer;
function showLoader(show) {
  const el = document.getElementById('loader');
  if (show) {
    el.classList.add('show');
    let i = 0;
    document.getElementById('loader-text').textContent = loaderTexts[0];
    loaderTimer = setInterval(()=>{ i=(i+1)%loaderTexts.length; document.getElementById('loader-text').textContent=loaderTexts[i]; },1800);
  } else {
    el.classList.remove('show');
    clearInterval(loaderTimer);
  }
}

// ── Show reader ───────────────────────────────────────────────────────────────
function showReader(raw, words, meta) {
  showLoader(false);
  vocabWords = words;
  seenWords  = new Set();
  favorites  = new Set();

  // Parse title
  const lines = raw.trim().split('\n');
  let title = lines[0].replace(/^#+\s*/,'').trim();
  let body  = lines.slice(1).join('\n').trim();

  // Render body: handle ## headings
  const paras = body.split(/\n\n+/);
  const html = paras.map(p=>{
    p = p.trim();
    if (p.startsWith('##')) return `<h2>${p.replace(/^##\s*/,'')}</h2>`;
    return `<p>${highlight(p, words)}</p>`;
  }).join('');

  document.getElementById('story-title').textContent = title;
  const levelLabels = {A1:'A1 Beginner',A2:'A2 Elementary',B1:'B1 Intermediate',B2:'B2 Upper-Intermediate'};
  document.getElementById('story-byline').textContent = `${levelLabels[meta.level]} · ${meta.length} words · ${words.length} vocab words`;
  document.getElementById('story-body').innerHTML = html;

  buildVocabTable(words);
  buildQuiz(words);
  updateCounts();

  document.getElementById('screen-gen').classList.remove('active');
  document.getElementById('screen-reader').classList.add('active');
  window.scrollTo(0,0);
  startTimer();

  window.addEventListener('scroll', onScroll, {passive:true});
  document.addEventListener('mouseup', onSelectionEnd);

  // Pre-fetch translations
  words.forEach(w => translate(w).then(t=>{ transCache[w]=t; updateTableCell(w,t); }));
}

// ── Word click (vocab highlight) ─────────────────────────────────────────────
async function onVwClick(e, el, word) {
  e.stopPropagation();
  playClick();
  speakWord(word);
  markSeen(word);
  await showPopup(e.clientX, e.clientY, word, null);
}

function markSeen(word) {
  seenWords.add(word);
  document.querySelectorAll(`.vw[data-word="${word}"]`).forEach(n=>n.classList.add('seen'));
  const dot = document.getElementById(`dot-${word}`);
  if (dot) dot.classList.add('on');
  updateCounts();
}

// ── Selection popup (any word) ────────────────────────────────────────────────
async function onSelectionEnd(e) {
  const sel = window.getSelection();
  if (!sel || sel.isCollapsed) return;
  const text = sel.toString().trim();
  if (!text || text.length > 120) return;

  // Single word
  if (/^\w+$/.test(text)) {
    playClick();
    speakWord(text);
    await showPopup(e.clientX, e.clientY, text.toLowerCase(), null);
  } else {
    // Phrase — just translate
    await showPopupPhrase(e.clientX, e.clientY, text);
  }
}

async function showPopup(x, y, word, phrase) {
  const popup = document.getElementById('word-popup');
  document.getElementById('popup-word').textContent = word;
  document.getElementById('popup-transcr').textContent = TRANSCR[word] ? `/${TRANSCR[word]}/` : '';
  const transEl = document.getElementById('popup-trans');
  transEl.textContent = 'translating…';
  transEl.className = 'popup-trans loading';

  positionPopup(popup, x, y);
  popup.classList.add('visible');

  const t = await translate(word);
  transEl.textContent = t;
  transEl.className = 'popup-trans';
  updateTableCell(word, t);
}

async function showPopupPhrase(x, y, phrase) {
  const popup = document.getElementById('word-popup');
  document.getElementById('popup-word').textContent = phrase.length>30 ? phrase.slice(0,30)+'…' : phrase;
  document.getElementById('popup-transcr').textContent = '';
  const transEl = document.getElementById('popup-trans');
  transEl.textContent = 'translating…';
  transEl.className = 'popup-trans loading';

  positionPopup(popup, x, y);
  popup.classList.add('visible');

  const t = await translatePhrase(phrase);
  transEl.textContent = t;
  transEl.className = 'popup-trans';
}

function positionPopup(popup, x, y) {
  popup.style.display = 'block';
  const pw = 280, ph = 140;
  let left = x + 12, top = y + 12;
  if (left + pw > window.innerWidth)  left = x - pw - 12;
  if (top  + ph > window.innerHeight) top  = y - ph - 12;
  popup.style.left = left + 'px';
  popup.style.top  = top  + 'px';
}

document.addEventListener('click', e=>{
  if (!e.target.classList.contains('vw') && !e.target.closest('.word-popup')) {
    document.getElementById('word-popup').classList.remove('visible');
    window.getSelection()?.removeAllRanges();
  }
});

// ── Vocab table ───────────────────────────────────────────────────────────────
function buildVocabTable(words) {
  const tbody = document.getElementById('vocab-tbody');
  tbody.innerHTML = '';
  words.forEach(w=>{
    const tr = document.createElement('tr');
    tr.innerHTML = `
      <td class="vt-word">${w}</td>
      <td class="vt-tr">${TRANSCR[w]?`/${TRANSCR[w]}/`:'—'}</td>
      <td class="vt-uk loading" id="cell-${w}">…</td>
      <td class="vt-star" id="star-${w}" onclick="toggleFav('${w}')">⭐</td>
      <td class="vt-seen-dot"><span class="dot" id="dot-${w}"></span></td>
    `;
    tbody.appendChild(tr);
  });
}

function updateTableCell(word, trans) {
  const c = document.getElementById(`cell-${word}`);
  if (c) { c.textContent = trans; c.className = 'vt-uk'; }
}

function toggleFav(word) {
  const el = document.getElementById(`star-${word}`);
  if (favorites.has(word)) { favorites.delete(word); el.classList.remove('active'); }
  else { favorites.add(word); el.classList.add('active'); playClick(); }
}

// ── Counts ────────────────────────────────────────────────────────────────────
function updateCounts() {
  const s = seenWords.size, t = vocabWords.length;
  document.getElementById('seen-count').textContent  = s;
  document.getElementById('total-count').textContent = t;
  document.getElementById('seen-count2').textContent  = s;
  document.getElementById('total-count2').textContent = t;
}

// ── Progress / scroll ─────────────────────────────────────────────────────────
function onScroll() {
  const pct = Math.round((window.scrollY/(document.documentElement.scrollHeight-window.innerHeight))*100);
  document.getElementById('progress-fill').style.width = Math.min(pct,100)+'%';
}

// ── Focus mode ────────────────────────────────────────────────────────────────
function toggleFocus(btn) {
  document.body.classList.toggle('focus-mode');
  btn.classList.toggle('active');
}

// ── Quiz ──────────────────────────────────────────────────────────────────────
function buildQuiz(words) {
  if (words.length < 2) { document.getElementById('quiz-section').style.display='none'; return; }
  document.getElementById('quiz-section').style.display='';
  const pool = [...words].sort(()=>Math.random()-0.5).slice(0,Math.min(5,words.length));
  quizState = { questions: pool.map(w=>({word:w, trans: transCache[w]||null})), idx:0, score:0, done:false };
  renderQuiz();
}

async function renderQuiz() {
  const qs = quizState.questions;
  const idx = quizState.idx;
  if (quizState.done || idx >= qs.length) { showQuizResult(); return; }

  const q = qs[idx];
  if (!q.trans) q.trans = await translate(q.word);

  // Build wrong options
  const allWords = vocabWords.filter(w=>w!==q.word);
  const wrongs = allWords.sort(()=>Math.random()-0.5).slice(0,3);
  const opts = [q.trans, ...await Promise.all(wrongs.map(w=>translate(w)))].sort(()=>Math.random()-0.5);

  document.getElementById('quiz-counter').textContent = `${idx+1} / ${qs.length}`;
  document.getElementById('quiz-progress-fill').style.width = (idx/qs.length*100)+'%';

  document.getElementById('quiz-body').innerHTML = `
    <div class="quiz-question">What is the Ukrainian translation of <strong>"${q.word}"</strong>?</div>
    <div class="quiz-options">
      ${opts.map(o=>`<button class="quiz-opt" onclick="answerQuiz(this,'${o.replace(/'/g,"\\'")}','${q.trans.replace(/'/g,"\\'")}')">
        ${o}
      </button>`).join('')}
    </div>
  `;
}

function answerQuiz(btn, chosen, correct) {
  document.querySelectorAll('.quiz-opt').forEach(b=>b.onclick=null);
  if (chosen === correct) { btn.classList.add('correct'); quizState.score++; }
  else {
    btn.classList.add('wrong');
    document.querySelectorAll('.quiz-opt').forEach(b=>{ if(b.textContent.trim()===correct) b.classList.add('correct'); });
  }
  setTimeout(()=>{ quizState.idx++; renderQuiz(); }, 900);
}

function showQuizResult() {
  const s = quizState.score, t = quizState.questions.length;
  document.getElementById('quiz-counter').textContent = 'Done!';
  document.getElementById('quiz-progress-fill').style.width = '100%';
  document.getElementById('quiz-body').innerHTML = `
    <div class="quiz-result">
      <div class="quiz-score">${s}/${t}</div>
      <div class="quiz-score-label">${s===t?'Perfect! 🎉':s>=t/2?'Good job! Keep practicing':'Keep learning!'}</div>
      <button class="quiz-restart" onclick="buildQuiz(vocabWords)">Retake Quiz</button>
    </div>
  `;
}

function scrollToQuiz() {
  document.getElementById('quiz-section').scrollIntoView({behavior:'smooth'});
}

// ── PDF ───────────────────────────────────────────────────────────────────────
function savePDF() {
  window.print();
}

// ── Status ────────────────────────────────────────────────────────────────────
function setStatus(msg, type='') {
  const el = document.getElementById('gen-status');
  el.textContent = msg;
  el.className = 'gen-status' + (type?' '+type:'');
}

// ── Nav ───────────────────────────────────────────────────────────────────────
function showGen() {
  stopTimer();
  window.speechSynthesis?.cancel();
  window.removeEventListener('scroll', onScroll);
  document.removeEventListener('mouseup', onSelectionEnd);
  document.getElementById('screen-reader').classList.remove('active');
  document.getElementById('screen-gen').classList.add('active');
  window.scrollTo(0,0);
  setStatus('');
}
</script>
</body>
</html>
