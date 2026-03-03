---
permalink: /problem-map/
---

<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />

  <!-- EDIT 1: page title -->
  <title>WFGY · Redirecting</title>

  <!-- EDIT 2: target url -->
  <meta http-equiv="refresh" content="0; url=https://github.com/onestardao/WFGY/blob/main/ProblemMap/README.md" />

  <style>
    :root {
      color-scheme: dark;
      --bg: #0b0f0d;
      --fg: #d7f9d7;
      --muted: rgba(215, 249, 215, 0.65);
      --line: rgba(215, 249, 215, 0.16);
      --accent: #9cff9c;
    }
    html, body {
      height: 100%;
      margin: 0;
      background: radial-gradient(1200px 600px at 50% 10%, rgba(156, 255, 156, 0.08), transparent 60%),
                  var(--bg);
      color: var(--fg);
      font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;
    }
    .wrap {
      min-height: 100%;
      display: grid;
      place-items: center;
      padding: 24px;
    }
    .card {
      width: min(920px, 100%);
      border: 1px solid var(--line);
      border-radius: 12px;
      padding: 22px 18px;
      background: rgba(0,0,0,0.35);
      box-shadow: 0 0 0 1px rgba(0,0,0,0.4) inset;
    }
    .top {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 12px;
      margin-bottom: 14px;
    }
    .brand {
      display: flex;
      align-items: baseline;
      gap: 10px;
      flex-wrap: wrap;
    }
    .brand b { color: var(--accent); }
    .tag { color: var(--muted); font-size: 12px; }
    .pill {
      border: 1px solid var(--line);
      padding: 6px 10px;
      border-radius: 999px;
      color: var(--muted);
      font-size: 12px;
    }
    .title {
      font-size: 16px;
      margin: 10px 0 6px;
    }
    .hint {
      margin: 0 0 14px;
      color: var(--muted);
      font-size: 13px;
      line-height: 1.5;
    }
    .bar {
      height: 10px;
      border-radius: 999px;
      border: 1px solid var(--line);
      overflow: hidden;
      background: rgba(255,255,255,0.03);
    }
    .bar > div {
      height: 100%;
      width: 40%;
      background: linear-gradient(90deg, transparent, rgba(156,255,156,0.55), transparent);
      animation: scan 900ms linear infinite;
    }
    @keyframes scan {
      0% { transform: translateX(-80%); }
      100% { transform: translateX(280%); }
    }
    .links {
      margin-top: 14px;
      display: flex;
      gap: 12px;
      flex-wrap: wrap;
      align-items: center;
    }
    a {
      color: var(--fg);
      text-decoration: none;
      border-bottom: 1px dotted var(--line);
    }
    a:hover {
      border-bottom-color: var(--accent);
      color: var(--accent);
    }
    .small {
      color: var(--muted);
      font-size: 12px;
    }
    .mono {
      color: var(--muted);
      font-size: 12px;
      word-break: break-all;
      border-top: 1px dashed var(--line);
      margin-top: 14px;
      padding-top: 12px;
    }
  </style>

  <script>
    // EDIT 2: target url (same as meta refresh)
    const target = "https://github.com/onestardao/WFGY/blob/main/ProblemMap/README.md";
    try {
      window.location.replace(target);
    } catch (e) {
      window.location.href = target;
    }
  </script>
</head>

<body>
  <div class="wrap">
    <div class="card">
      <div class="top">
        <div class="brand">
          <b>WFGY</b>
          <span class="tag">verification-first reasoning ecosystem</span>
        </div>
        <div class="pill">redirect</div>
      </div>

      <!-- EDIT 1: destination label -->
      <div class="title">Opening: RAG 16 Problem Map</div>
      <p class="hint">
        Routing you to the canonical page. If your browser blocks automatic redirects, use the manual link below.
      </p>

      <div class="bar"><div></div></div>

      <div class="links">
        <a href="https://github.com/onestardao/WFGY/blob/main/ProblemMap/README.md">Open manually</a>
        <span class="small">·</span>
        <a href="https://onestardao.github.io/">Back to home</a>
      </div>

      <div class="mono">
        target: https://github.com/onestardao/WFGY/blob/main/ProblemMap/README.md
      </div>
    </div>
  </div>
</body>
</html>
