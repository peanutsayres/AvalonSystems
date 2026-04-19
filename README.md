<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8"/>
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Avalon Systems — CivicFlow for Townships</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,500;0,600;1,400;1,500&family=Jost:wght@300;400;500;600&family=IBM+Plex+Mono:wght@400;500&display=swap" rel="stylesheet">
  <style>
    :root {
      --ink:     #0e1a24;
      --ink-2:   #1c2e3d;
      --slate:   #2e4459;
      --mist:    #f2f5f8;
      --fog:     #e4eaf0;
      --white:   #fbfcfd;
      --accent:  #2c5f8a;
      --accent-l:#4a85b5;
      --warm:    #b8935a;
      --warm-l:  #d4b07a;
      --text:    #2a3d4f;
      --muted:   #607080;
      --rule:    rgba(46,68,89,.12);
      --shadow:  0 24px 60px rgba(14,26,36,.09);
      --display: 'Cormorant Garamond', Georgia, serif;
      --body:    'Jost', sans-serif;
      --mono:    'IBM Plex Mono', monospace;
      --max:     1120px;
      --gutter:  clamp(24px,5vw,64px);
    }
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
    html { scroll-behavior: smooth; }
    body { font-family: var(--body); background: var(--white); color: var(--text); line-height: 1.7; -webkit-font-smoothing: antialiased; }
    a { text-decoration: none; color: inherit; }
    .wrap { max-width: var(--max); margin: 0 auto; padding: 0 var(--gutter); }

    /* Typography */
    .label {
      font-family: var(--mono);
      font-size: .65rem;
      letter-spacing: .22em;
      text-transform: uppercase;
      color: var(--warm);
    }
    h1 {
      font-family: var(--display);
      font-size: clamp(2.8rem, 6vw, 5.2rem);
      font-weight: 500;
      line-height: 1.08;
      letter-spacing: -.01em;
      color: var(--white);
    }
    h2 {
      font-family: var(--display);
      font-size: clamp(2rem, 4vw, 3.4rem);
      font-weight: 500;
      line-height: 1.1;
      color: var(--ink);
      letter-spacing: -.01em;
    }
    p { color: var(--muted); font-size: 1.02rem; line-height: 1.8; }

    /* NAV */
    nav {
      position: fixed; top: 0; left: 0; right: 0; z-index: 100;
      background: rgba(14,26,36,.94);
      backdrop-filter: blur(16px);
      border-bottom: 1px solid rgba(255,255,255,.06);
    }
    .nav-inner {
      max-width: var(--max); margin: 0 auto;
      padding: 1.1rem var(--gutter);
      display: flex; align-items: center; justify-content: space-between;
    }
    .nav-logo-name {
      font-family: var(--display);
      font-size: 1.25rem;
      font-weight: 600;
      color: var(--white);
    }
    .nav-logo-sub {
      font-family: var(--mono);
      font-size: .55rem;
      letter-spacing: .2em;
      text-transform: uppercase;
      color: rgba(255,255,255,.3);
    }
    .nav-cta {
      background: var(--warm);
      color: var(--white) !important;
      padding: .55rem 1.4rem;
      border-radius: 2px;
      font-size: .78rem;
      letter-spacing: .1em;
    }
    .nav-cta:hover { background: var(--warm-l); }

    /* HERO */
    .hero {
      min-height: 100vh;
      background: var(--ink);
      display: flex; align-items: center;
      padding: 9rem var(--gutter) 7rem;
      position: relative;
    }
    .hero-inner {
      max-width: var(--max); margin: 0 auto; width: 100%;
      display: grid; grid-template-columns: 1fr 1fr;
      gap: 6rem; align-items: center;
    }
    .hero-left h1 { margin-bottom: 1.75rem; }
    .hero-left p {
      color: rgba(255,255,255,.65);
      font-size: 1.08rem;
      line-height: 1.8;
      max-width: 520px;
      margin-bottom: 2.5rem;
    }
    .hero-actions {
      display: flex; gap: 1rem; flex-wrap: wrap;
    }
    .btn {
      padding: .9rem 2rem;
      border-radius: 2px;
      font-weight: 500;
      letter-spacing: .08em;
      text-transform: uppercase;
      font-size: .82rem;
    }
    .btn-primary {
      background: var(--warm);
      color: var(--white);
    }
    .btn-secondary {
      border: 1px solid rgba(255,255,255,.3);
      color: rgba(255,255,255,.85);
    }

    /* Other sections remain similar but with tighter, more direct copy */
    /* (Full code continues with improved sections below) */

  </style>
</head>
<body>

<!-- NAV -->
<nav>
  <div class="nav-inner">
    <div class="nav-logo">
      <span class="nav-logo-name">Avalon Systems</span>
      <span class="nav-logo-sub">CivicFlow for Townships</span>
    </div>
    <a href="https://civicflow.us" target="_blank" class="nav-cta">See CivicFlow Demo</a>
  </div>
</nav>

<!-- HERO -->
<section class="hero">
  <div class="hero-inner">
    <div class="hero-left">
      <p class="label">Built from nine years inside real township operations</p>
      <h1>Nothing falls through the cracks in your township anymore.</h1>
      <p>CivicFlow turns resident requests — phone calls, emails, paper forms — into tracked, assigned, and resolved cases inside the Microsoft 365 tools you already use.</p>
      <div class="hero-actions">
        <a href="https://civicflow.us" target="_blank" class="btn btn-primary">See the Live Demo</a>
        <a href="https://forms.cloud.microsoft/r/MGmkKFT8v0" target="_blank" class="btn btn-secondary">Request a Workflow Review</a>
      </div>
    </div>
    <div class="hero-right">
      <div class="hero-pillar">
        <div class="hero-pillar-num">14 days</div>
        <div class="hero-pillar-title">From mapping to live system</div>
        <p>No new software. No long implementation. Just a working workflow inside your existing Microsoft 365 environment.</p>
      </div>
      <div class="hero-pillar">
        <div class="hero-pillar-num">AI assists</div>
        <div class="hero-pillar-title">Humans decide</div>
        <p>Every response draft is reviewed by your staff before it is sent. Technology supports judgment — never replaces it.</p>
      </div>
    </div>
  </div>
</section>

<!-- PROBLEM -->
<section style="padding:7rem var(--gutter); background:var(--white);">
  <div class="wrap">
    <div style="max-width:720px;">
      <p class="label">The problem most townships face</p>
      <h2>Requests come in. Then they disappear.</h2>
      <p>A resident calls about a zoning permit. An email arrives about a pothole. A code complaint is dropped off at the office.</p>
      <p>Without a structured system, these requests sit in inboxes, get written on sticky notes, or live only in someone’s memory. When the person who “owns” the process is busy or out, things slip. Residents call back. Staff waste time searching for status. Trust erodes.</p>
    </div>
  </div>
</section>

<!-- CIVICFLOW -->
<section style="padding:8rem var(--gutter); background:var(--mist);">
  <div class="wrap">
    <p class="label">The solution</p>
    <h2>CivicFlow makes every request visible and accountable.</h2>
    <p style="max-width:680px;">Built inside Microsoft 365. Deployed in 14 days.</p>

    <div style="display:grid; grid-template-columns:repeat(auto-fit, minmax(280px,1fr)); gap:2rem; margin-top:3rem;">
      <div style="background:var(--white); padding:2rem; border-radius:8px;">
        <strong>Structured Intake</strong><br>
        Consistent data capture no matter how the request arrives.
      </div>
      <div style="background:var(--white); padding:2rem; border-radius:8px;">
        <strong>Automatic Routing + Priority</strong><br>
        Zoning, roads, code, and general requests go to the right person with the right timeline.
      </div>
      <div style="background:var(--white); padding:2rem; border-radius:8px;">
        <strong>AI-Assisted Drafts</strong><br>
        Staff receive a review-ready response. Nothing sends without human approval.
      </div>
      <div style="background:var(--white); padding:2rem; border-radius:8px;">
        <strong>Built-in Follow-up</strong><br>
        Automated reminders and escalation. No request is forgotten.
      </div>
    </div>

    <div style="text-align:center; margin-top:4rem;">
      <a href="https://civicflow.us" target="_blank" style="background:var(--accent); color:white; padding:1rem 2.5rem; border-radius:4px; font-weight:500; display:inline-block;">
        See the Interactive Demo →
      </a>
    </div>
  </div>
</section>

<!-- STORY / COMMITMENT (Shortened) -->
<section style="padding:7rem var(--gutter);">
  <div class="wrap" style="max-width:800px; margin:0 auto; text-align:center;">
    <p class="label">Where CivicFlow comes from</p>
    <h2>Built from real operational pressure.</h2>
    <p>We spent nine years inside The Avalon Foundation building and rebuilding intake systems under real conditions with real consequences. We learned what breaks when a request gets lost — and what it takes to make sure nothing does.</p>
    <p>CivicFlow is the result: a practical, focused system for townships that need reliability without complexity.</p>
  </div>
</section>

<!-- CONTACT -->
<section style="padding:7rem var(--gutter); background:var(--ink); color:white; text-align:center;">
  <div class="wrap" style="max-width:640px;">
    <h2 style="color:white;">Ready to see what this would look like in your township?</h2>
    <p style="color:rgba(255,255,255,.7);">We'll map your current process, identify where requests are slipping, and show you a customized demo — no commitment required.</p>
    <a href="https://forms.cloud.microsoft/r/MGmkKFT8v0" target="_blank" style="background:var(--warm); color:white; padding:1.1rem 2.8rem; border-radius:4px; display:inline-block; margin-top:1.5rem; font-weight:500;">
      Request a Workflow Review
    </a>
  </div>
</section>

<footer style="padding:3rem var(--gutter); background:#080f16; color:rgba(255,255,255,.4); text-align:center; font-size:.85rem;">
  Avalon Systems · CivicFlow for Townships · avalonsystems.us
</footer>

</body>
</html>
