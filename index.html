<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Máy Tính Giấc Ngủ</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,700;1,400&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet"/>
  <style>
    :root {
      --navy: #0b0f2e;
      --deep: #070b20;
      --indigo: #1a1f4e;
      --lavender: #7b7fd4;
      --soft-blue: #a8b4f8;
      --gold: #e8c97e;
      --cream: #f5f0e8;
      --muted: #8890b8;
      --card-bg: rgba(255,255,255,0.04);
      --border: rgba(168,180,248,0.15);
    }

    * { margin: 0; padding: 0; box-sizing: border-box; }

    body {
      background-color: var(--deep);
      color: var(--cream);
      font-family: 'DM Sans', sans-serif;
      min-height: 100vh;
      overflow-x: hidden;
      position: relative;
    }

    /* Starfield */
    body::before {
      content: '';
      position: fixed;
      inset: 0;
      background-image:
        radial-gradient(1px 1px at 10% 20%, rgba(255,255,255,0.6) 0%, transparent 100%),
        radial-gradient(1px 1px at 30% 60%, rgba(255,255,255,0.4) 0%, transparent 100%),
        radial-gradient(1.5px 1.5px at 50% 10%, rgba(255,255,255,0.7) 0%, transparent 100%),
        radial-gradient(1px 1px at 70% 40%, rgba(255,255,255,0.3) 0%, transparent 100%),
        radial-gradient(1px 1px at 85% 75%, rgba(255,255,255,0.5) 0%, transparent 100%),
        radial-gradient(1px 1px at 15% 80%, rgba(255,255,255,0.4) 0%, transparent 100%),
        radial-gradient(1.5px 1.5px at 60% 90%, rgba(255,255,255,0.6) 0%, transparent 100%),
        radial-gradient(1px 1px at 92% 15%, rgba(255,255,255,0.5) 0%, transparent 100%),
        radial-gradient(1px 1px at 42% 50%, rgba(255,255,255,0.3) 0%, transparent 100%),
        radial-gradient(1px 1px at 78% 88%, rgba(255,255,255,0.4) 0%, transparent 100%),
        radial-gradient(1px 1px at 5% 45%, rgba(255,255,255,0.3) 0%, transparent 100%),
        radial-gradient(1.5px 1.5px at 25% 35%, rgba(255,255,255,0.5) 0%, transparent 100%);
      pointer-events: none;
      z-index: 0;
    }

    /* Moon glow */
    body::after {
      content: '';
      position: fixed;
      top: -120px;
      right: -80px;
      width: 400px;
      height: 400px;
      background: radial-gradient(circle, rgba(123,127,212,0.18) 0%, rgba(123,127,212,0.06) 50%, transparent 70%);
      pointer-events: none;
      z-index: 0;
    }

    .container {
      position: relative;
      z-index: 1;
      max-width: 680px;
      margin: 0 auto;
      padding: 60px 24px 80px;
    }

    /* Header */
    .header {
      text-align: center;
      margin-bottom: 56px;
      animation: fadeDown 0.8s ease both;
    }

    .moon-icon {
      font-size: 48px;
      display: block;
      margin-bottom: 16px;
      animation: float 6s ease-in-out infinite;
    }

    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
    }

    h1 {
      font-family: 'Playfair Display', serif;
      font-size: clamp(2rem, 5vw, 3rem);
      font-weight: 700;
      color: var(--cream);
      line-height: 1.1;
      margin-bottom: 12px;
    }

    h1 span {
      color: var(--gold);
      font-style: italic;
    }

    .subtitle {
      color: var(--muted);
      font-size: 0.95rem;
      font-weight: 300;
      line-height: 1.6;
      max-width: 420px;
      margin: 0 auto;
    }

    /* Card */
    .card {
      background: var(--card-bg);
      border: 1px solid var(--border);
      border-radius: 24px;
      padding: 40px 36px;
      backdrop-filter: blur(10px);
      margin-bottom: 24px;
      animation: fadeUp 0.8s ease 0.2s both;
    }

    /* Toggle */
    .toggle-wrap {
      display: flex;
      background: rgba(255,255,255,0.05);
      border-radius: 12px;
      padding: 4px;
      margin-bottom: 32px;
      gap: 4px;
    }

    .toggle-btn {
      flex: 1;
      padding: 10px;
      border: none;
      border-radius: 9px;
      background: transparent;
      color: var(--muted);
      font-family: 'DM Sans', sans-serif;
      font-size: 0.9rem;
      cursor: pointer;
      transition: all 0.25s;
    }

    .toggle-btn.active {
      background: var(--indigo);
      color: var(--soft-blue);
      box-shadow: 0 2px 12px rgba(123,127,212,0.3);
    }

    /* Label */
    label {
      display: block;
      font-size: 0.8rem;
      font-weight: 500;
      text-transform: uppercase;
      letter-spacing: 0.12em;
      color: var(--muted);
      margin-bottom: 10px;
    }

    /* Time input */
    .time-input-wrap {
      position: relative;
      margin-bottom: 28px;
    }

    input[type="time"] {
      width: 100%;
      padding: 18px 20px;
      background: rgba(255,255,255,0.06);
      border: 1px solid var(--border);
      border-radius: 14px;
      color: var(--cream);
      font-family: 'Playfair Display', serif;
      font-size: 2rem;
      text-align: center;
      outline: none;
      cursor: pointer;
      transition: border-color 0.2s, background 0.2s;
      appearance: none;
      -webkit-appearance: none;
    }

    input[type="time"]::-webkit-calendar-picker-indicator {
      filter: invert(0.7);
      cursor: pointer;
    }

    input[type="time"]:focus {
      border-color: var(--lavender);
      background: rgba(123,127,212,0.1);
    }

    /* Info box */
    .info-box {
      background: rgba(123,127,212,0.08);
      border: 1px solid rgba(123,127,212,0.2);
      border-radius: 12px;
      padding: 14px 18px;
      display: flex;
      align-items: flex-start;
      gap: 10px;
      margin-bottom: 28px;
      font-size: 0.85rem;
      color: var(--muted);
      line-height: 1.5;
    }

    .info-box .icon { font-size: 16px; flex-shrink: 0; margin-top: 1px; }

    /* Button */
    .btn {
      width: 100%;
      padding: 18px;
      background: linear-gradient(135deg, #4a4fbe, #7b7fd4);
      border: none;
      border-radius: 14px;
      color: white;
      font-family: 'DM Sans', sans-serif;
      font-size: 1rem;
      font-weight: 500;
      cursor: pointer;
      transition: transform 0.2s, box-shadow 0.2s;
      letter-spacing: 0.02em;
    }

    .btn:hover {
      transform: translateY(-2px);
      box-shadow: 0 8px 30px rgba(123,127,212,0.4);
    }

    .btn:active { transform: translateY(0); }

    /* Results */
    .results {
      animation: fadeUp 0.5s ease both;
      display: none;
    }

    .results.show { display: block; }

    .results-header {
      text-align: center;
      margin-bottom: 24px;
    }

    .results-header p {
      color: var(--muted);
      font-size: 0.9rem;
      margin-top: 6px;
    }

    .results-title {
      font-family: 'Playfair Display', serif;
      font-size: 1.4rem;
      color: var(--cream);
    }

    .cycles-grid {
      display: grid;
      gap: 12px;
    }

    .cycle-item {
      display: flex;
      align-items: center;
      justify-content: space-between;
      background: var(--card-bg);
      border: 1px solid var(--border);
      border-radius: 16px;
      padding: 18px 22px;
      transition: all 0.25s;
      cursor: default;
      animation: fadeUp 0.4s ease both;
    }

    .cycle-item:hover {
      border-color: rgba(123,127,212,0.4);
      background: rgba(123,127,212,0.08);
      transform: translateX(4px);
    }

    .cycle-item.best {
      border-color: rgba(232,201,126,0.4);
      background: rgba(232,201,126,0.06);
    }

    .cycle-item.best:hover {
      border-color: rgba(232,201,126,0.6);
      background: rgba(232,201,126,0.1);
    }

    .cycle-left { display: flex; align-items: center; gap: 14px; }

    .cycle-icon { font-size: 22px; }

    .cycle-time {
      font-family: 'Playfair Display', serif;
      font-size: 1.6rem;
      color: var(--cream);
      line-height: 1;
    }

    .cycle-label {
      font-size: 0.78rem;
      color: var(--muted);
      margin-top: 3px;
      font-weight: 300;
    }

    .cycle-badge {
      font-size: 0.72rem;
      padding: 4px 10px;
      border-radius: 20px;
      font-weight: 500;
      letter-spacing: 0.05em;
    }

    .badge-best {
      background: rgba(232,201,126,0.2);
      color: var(--gold);
      border: 1px solid rgba(232,201,126,0.3);
    }

    .badge-good {
      background: rgba(168,180,248,0.15);
      color: var(--soft-blue);
      border: 1px solid rgba(168,180,248,0.2);
    }

    .badge-warn {
      background: rgba(255,140,100,0.15);
      color: #ffaa7a;
      border: 1px solid rgba(255,140,100,0.25);
    }

    /* Sleep stages legend */
    .legend {
      margin-top: 28px;
      background: var(--card-bg);
      border: 1px solid var(--border);
      border-radius: 16px;
      padding: 22px;
    }

    .legend-title {
      font-size: 0.78rem;
      text-transform: uppercase;
      letter-spacing: 0.1em;
      color: var(--muted);
      margin-bottom: 16px;
    }

    .legend-items {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 12px;
    }

    .legend-item {
      display: flex;
      align-items: center;
      gap: 10px;
      font-size: 0.82rem;
      color: var(--muted);
    }

    .legend-dot {
      width: 8px;
      height: 8px;
      border-radius: 50%;
      flex-shrink: 0;
    }

    /* Animations */
    @keyframes fadeDown {
      from { opacity: 0; transform: translateY(-20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    /* Now button */
    .now-btn {
      display: inline-block;
      margin-top: 8px;
      font-size: 0.8rem;
      color: var(--lavender);
      cursor: pointer;
      border: none;
      background: none;
      font-family: 'DM Sans', sans-serif;
      text-decoration: underline;
      text-underline-offset: 3px;
    }

    .now-btn:hover { color: var(--soft-blue); }

    @media (max-width: 480px) {
      .card { padding: 28px 20px; }
      .legend-items { grid-template-columns: 1fr; }
      input[type="time"] { font-size: 1.5rem; }
    }
  </style>
</head>
<body>
<div class="container">

  <!-- Header -->
  <div class="header">
    <span class="moon-icon">🌙</span>
    <h1>Máy tính <span>giấc ngủ</span></h1>
    <p class="subtitle">Dựa trên chu kỳ giấc ngủ 90 phút, tính toán thời điểm thức dậy tốt nhất để bạn cảm thấy tươi tỉnh.</p>
  </div>

  <!-- Input Card -->
  <div class="card">
    <div class="toggle-wrap">
      <button class="toggle-btn active" id="btn-sleep" onclick="setMode('sleep')">⏰ Tôi ngủ lúc...</button>
      <button class="toggle-btn" id="btn-wake" onclick="setMode('wake')">☀️ Tôi muốn thức lúc...</button>
    </div>

    <div id="section-sleep">
      <label>Giờ đi ngủ</label>
      <div class="time-input-wrap">
        <input type="time" id="sleep-time" value="23:00"/>
      </div>
      <button class="now-btn" onclick="setNow('sleep')">Dùng giờ hiện tại</button>

      <div class="info-box" style="margin-top:16px;">
        <span class="icon">💡</span>
        <span>Mất trung bình <strong style="color:var(--soft-blue)">14 phút</strong> để đi vào giấc ngủ. Chúng tôi đã tính sẵn điều này cho bạn.</span>
      </div>
    </div>

    <div id="section-wake" style="display:none;">
      <label>Giờ muốn thức dậy</label>
      <div class="time-input-wrap">
        <input type="time" id="wake-time" value="06:30"/>
      </div>
      <button class="now-btn" onclick="setNow('wake')">Dùng giờ hiện tại</button>

      <div class="info-box" style="margin-top:16px;">
        <span class="icon">💡</span>
        <span>Chúng tôi sẽ tính <strong style="color:var(--soft-blue)">giờ nên đi ngủ</strong> để bạn dậy đúng giữa chu kỳ.</span>
      </div>
    </div>

    <div style="margin-top:28px;">
      <button class="btn" onclick="calculate()">✨ Tính giờ tốt nhất</button>
    </div>
  </div>

  <!-- Results -->
  <div class="results" id="results">
    <div class="card" style="padding-bottom:32px;">
      <div class="results-header">
        <div class="results-title" id="results-title">Nên thức dậy lúc...</div>
        <p id="results-sub"></p>
      </div>
      <div class="cycles-grid" id="cycles-grid"></div>
    </div>

    <div class="legend">
      <div class="legend-title">Chu kỳ giấc ngủ gồm 4 giai đoạn (≈ 90 phút/chu kỳ)</div>
      <div class="legend-items">
        <div class="legend-item">
          <div class="legend-dot" style="background:#a8b4f8"></div>
          <span>N1 – Ngủ nông (5–10 phút)</span>
        </div>
        <div class="legend-item">
          <div class="legend-dot" style="background:#7b7fd4"></div>
          <span>N2 – Ngủ nhẹ (~20 phút)</span>
        </div>
        <div class="legend-item">
          <div class="legend-dot" style="background:#4a4fbe"></div>
          <span>N3 – Ngủ sâu (~40 phút)</span>
        </div>
        <div class="legend-item">
          <div class="legend-dot" style="background:#e8c97e"></div>
          <span>REM – Giấc mơ (~20 phút)</span>
        </div>
      </div>
    </div>
  </div>

</div>

<script>
  let mode = 'sleep';

  function setMode(m) {
    mode = m;
    document.getElementById('section-sleep').style.display = m === 'sleep' ? 'block' : 'none';
    document.getElementById('section-wake').style.display = m === 'wake' ? 'block' : 'none';
    document.getElementById('btn-sleep').classList.toggle('active', m === 'sleep');
    document.getElementById('btn-wake').classList.toggle('active', m === 'wake');
    document.getElementById('results').classList.remove('show');
  }

  function setNow(type) {
    const now = new Date();
    const hh = String(now.getHours()).padStart(2, '0');
    const mm = String(now.getMinutes()).padStart(2, '0');
    document.getElementById(type === 'sleep' ? 'sleep-time' : 'wake-time').value = `${hh}:${mm}`;
  }

  function addMinutes(timeStr, mins) {
    const [h, m] = timeStr.split(':').map(Number);
    const total = h * 60 + m + mins;
    const nh = Math.floor(((total % 1440) + 1440) % 1440 / 60);
    const nm = ((total % 1440) + 1440) % 1440 % 60;
    return `${String(nh).padStart(2,'0')}:${String(nm).padStart(2,'0')}`;
  }

  function subtractMinutes(timeStr, mins) {
    return addMinutes(timeStr, -mins);
  }

  function formatTime(timeStr) {
    const [h, m] = timeStr.split(':').map(Number);
    const period = h >= 12 ? 'CH' : 'SA';
    const h12 = h % 12 || 12;
    return `${h12}:${String(m).padStart(2,'0')} ${period}`;
  }

  function calculate() {
    const FALL_ASLEEP = 14;
    const CYCLE = 90;

    const resultsEl = document.getElementById('results');
    const gridEl = document.getElementById('cycles-grid');
    const titleEl = document.getElementById('results-title');
    const subEl = document.getElementById('results-sub');

    gridEl.innerHTML = '';

    const icons = ['😴','💤','🌛','⭐','✨','🌟'];
    const badges = [
      { text: 'Quá ít', cls: 'badge-warn', best: false },
      { text: 'Quá ít', cls: 'badge-warn', best: false },
      { text: 'Chấp nhận', cls: 'badge-good', best: false },
      { text: 'Chấp nhận', cls: 'badge-good', best: false },
      { text: 'Tốt nhất', cls: 'badge-best', best: true },
      { text: 'Tốt nhất', cls: 'badge-best', best: true },
    ];

    if (mode === 'sleep') {
      const sleepTime = document.getElementById('sleep-time').value;
      if (!sleepTime) return alert('Vui lòng nhập giờ đi ngủ!');

      titleEl.textContent = 'Nên thức dậy lúc...';
      subEl.textContent = `Bắt đầu từ sau khi bạn ngủ lúc ${formatTime(sleepTime)}`;

      const asleepAt = addMinutes(sleepTime, FALL_ASLEEP);

      for (let i = 1; i <= 6; i++) {
        const wakeTime = addMinutes(asleepAt, i * CYCLE);
        const hours = Math.floor(i * CYCLE / 60);
        const mins = (i * CYCLE) % 60;
        const label = hours > 0 ? `${hours}g${mins > 0 ? ` ${mins}p` : ''} ngủ · ${i} chu kỳ` : `${mins}p ngủ · ${i} chu kỳ`;

        addCycleItem(gridEl, icons[i-1], formatTime(wakeTime), label, badges[i-1], i);
      }

    } else {
      const wakeTime = document.getElementById('wake-time').value;
      if (!wakeTime) return alert('Vui lòng nhập giờ muốn thức!');

      titleEl.textContent = 'Nên đi ngủ lúc...';
      subEl.textContent = `Để thức dậy tươi tỉnh vào ${formatTime(wakeTime)}`;

      for (let i = 6; i >= 1; i--) {
        const sleepTime = subtractMinutes(wakeTime, i * CYCLE + FALL_ASLEEP);
        const hours = Math.floor(i * CYCLE / 60);
        const mins = (i * CYCLE) % 60;
        const label = hours > 0 ? `${hours}g${mins > 0 ? ` ${mins}p` : ''} ngủ · ${i} chu kỳ` : `${mins}p ngủ · ${i} chu kỳ`;

        const idx = 6 - i;
        addCycleItem(gridEl, icons[idx], formatTime(sleepTime), label, badges[idx], idx + 1);
      }
    }

    resultsEl.classList.add('show');
    resultsEl.scrollIntoView({ behavior: 'smooth', block: 'start' });
  }

  function addCycleItem(grid, icon, time, label, badge, idx) {
    const item = document.createElement('div');
    item.className = `cycle-item${badge.best ? ' best' : ''}`;
    item.style.animationDelay = `${idx * 0.07}s`;
    item.innerHTML = `
      <div class="cycle-left">
        <span class="cycle-icon">${icon}</span>
        <div>
          <div class="cycle-time">${time}</div>
          <div class="cycle-label">${label}</div>
        </div>
      </div>
      <span class="cycle-badge ${badge.cls}">${badge.text}</span>
    `;
    grid.appendChild(item);
  }
</script>
</body>
</html>
