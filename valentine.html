<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Valentine?</title>
  <style>
    :root {
      --bg1: #ffdde1;
      --bg2: #ee9ca7;
      --card: rgba(255, 255, 255, 0.85);
      --text: #2b2b2b;
    }

    * { box-sizing: border-box; }
    body {
      margin: 0;
      font-family: system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
      min-height: 100vh;
      display: grid;
      place-items: center;
      background: radial-gradient(circle at top, var(--bg1), var(--bg2));
      overflow: hidden;
    }

    .card {
      width: min(720px, 92vw);
      background: var(--card);
      border-radius: 24px;
      padding: 28px 22px 24px;
      box-shadow: 0 18px 60px rgba(0,0,0,0.18);
      position: relative;
      text-align: center;
      backdrop-filter: blur(6px);
    }

    h1 {
      margin: 0 0 8px;
      font-size: clamp(24px, 3vw, 34px);
      color: var(--text);
    }

    p {
      margin: 0 0 18px;
      color: #444;
      font-size: 16px;
    }

    /* This is the "play area" so the No button can move around safely */
    .arena {
      margin: 18px auto 0;
      width: min(620px, 86vw);
      height: 300px;
      border-radius: 20px;
      background: rgba(255,255,255,0.55);
      border: 2px dashed rgba(0,0,0,0.12);
      position: relative;
      overflow: hidden;
    }

    .btn {
      border: 0;
      padding: 14px 18px;
      border-radius: 14px;
      font-weight: 700;
      cursor: pointer;
      font-size: 16px;
      transition: transform 0.12s ease;
      user-select: none;
    }

    .btn:active { transform: scale(0.98); }

    #yesBtn {
      background: #ff3b7f;
      color: white;
      box-shadow: 0 10px 20px rgba(255, 59, 127, 0.35);
      margin-right: 10px;
    }

    #noBtn {
      background: #222;
      color: white;
      position: absolute;
      left: 60%;
      top: 55%;
      box-shadow: 0 10px 20px rgba(0,0,0,0.25);
    }

    .topButtons {
      display: inline-flex;
      gap: 10px;
      flex-wrap: wrap;
      justify-content: center;
      margin-top: 6px;
    }

    .status {
      margin-top: 12px;
      font-weight: 700;
      color: #1f1f1f;
      min-height: 24px;
    }

    .hearts {
      position: absolute;
      inset: 0;
      pointer-events: none;
      opacity: 0.35;
    }

    .heart {
      position: absolute;
      font-size: 18px;
      animation: floatUp 6s linear infinite;
    }

    @keyframes floatUp {
      0%   { transform: translateY(40px); opacity: 0; }
      10%  { opacity: 1; }
      100% { transform: translateY(-360px); opacity: 0; }
    }
  </style>
</head>
<body>
  <div class="card">
    <div class="hearts" id="hearts"></div>

    <h1>Will you go to Valentine’s with me? 💘</h1>
    <p>Be honest… but also… try clicking “No” 😈</p>

    <div class="topButtons">
      <button class="btn" id="yesBtn">Yes 💖</button>
    </div>

    <div class="arena" id="arena">
      <button class="btn" id="noBtn">No 🙃</button>
    </div>

    <div class="status" id="status"></div>
  </div>

  <script>
    const arena = document.getElementById("arena");
    const noBtn = document.getElementById("noBtn");
    const yesBtn = document.getElementById("yesBtn");
    const status = document.getElementById("status");
    const hearts = document.getElementById("hearts");

    // Put the No button somewhere random inside the arena
    function moveNoButton() {
      const arenaRect = arena.getBoundingClientRect();
      const btnRect = noBtn.getBoundingClientRect();

      const padding = 10;
      const maxX = arenaRect.width - btnRect.width - padding;
      const maxY = arenaRect.height - btnRect.height - padding;

      const x = Math.max(padding, Math.floor(Math.random() * maxX));
      const y = Math.max(padding, Math.floor(Math.random() * maxY));

      noBtn.style.left = x + "px";
      noBtn.style.top = y + "px";

      const msgs = [
        "Nice try 😭",
        "Nope 😼",
        "You can’t catch me 🏃‍♂️💨",
        "Pick Yes already 😇",
        "Try again 😏"
      ];
      status.textContent = msgs[Math.floor(Math.random() * msgs.length)];
    }

    // Move on hover (desktop) and on click/tap attempts
    noBtn.addEventListener("mouseenter", moveNoButton);
    noBtn.addEventListener("mousedown", (e) => { e.preventDefault(); moveNoButton(); });
    noBtn.addEventListener("touchstart", (e) => { e.preventDefault(); moveNoButton(); }, { passive: false });

    // In case screen resizes, keep it inside
    window.addEventListener("resize", moveNoButton);

    yesBtn.addEventListener("click", () => {
      status.textContent = "YAYYY! 💖 See you on Valentine’s! 🌹";
      launchHearts();
      // Optional: disable the No button so it stops running away
      noBtn.disabled = true;
      noBtn.style.opacity = "0.5";
      noBtn.style.cursor = "not-allowed";
    });

    // Cute floating hearts effect
    function launchHearts() {
      hearts.innerHTML = "";
      const emojis = ["💖","💘","💝","💗","💕","🌹"];
      for (let i = 0; i < 22; i++) {
        const span = document.createElement("div");
        span.className = "heart";
        span.textContent = emojis[Math.floor(Math.random() * emojis.length)];
        span.style.left = Math.random() * 100 + "%";
        span.style.animationDelay = (Math.random() * 1.5) + "s";
        span.style.fontSize = (14 + Math.random() * 16) + "px";
        hearts.appendChild(span);
      }
    }

    // Place the No button randomly at start
    moveNoButton();
  </script>
</body>
</html>
