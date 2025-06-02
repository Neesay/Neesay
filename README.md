## Hi there 👋

<!--
**Neesay/Neesay** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


<?xml version="1.0" encoding="UTF-8"?>
<svg  xmlns="http://www.w3.org/2000/svg"
      width="460" height="200" viewBox="0 0 460 200" role="img"
      aria-labelledby="title desc">
  <title id="title">Animated README card – Yaseen Mehraf Alam</title>
  <desc id="desc">
    Animated profile card showing name, role and cycling achievements pulled
    from CV – built for GitHub README use (no JS, SMIL or external assets).
  </desc>

  <!-- ----------  Styling & keyframes  ---------- -->
  <style>
    @keyframes slideFade {
      0%   { opacity:0; transform:translateY(10px); }
      10%  { opacity:1; transform:translateY(0);    }
      30%  { opacity:1; transform:translateY(0);    }
      40%  { opacity:0; transform:translateY(-10px);}
      100% { opacity:0; }
    }
    .achieve text {
      font: 600 13px/1.3 "Segoe UI", Ubuntu, sans-serif;
      fill:#f7f7f7;
      animation: slideFade 20s ease-in-out infinite;
    }
    text, tspan{ font-family:"Segoe UI", Ubuntu, sans-serif; }
  </style>

  <!-- ----------  Card background  ---------- -->
  <rect x="2" y="2" width="456" height="196" rx="16"
        fill="#0A192F" stroke="#64ffda" stroke-width="2"/>

  <!-- ----------  Static header section  ---------- -->
  <!-- Name -->
  <text x="30" y="60" font-size="28" font-weight="700" fill="#64ffda">
      Yaseen&nbsp;Mehraf&nbsp;Alam
  </text>

  <!-- Tagline -->
  <text x="32" y="90" font-size="15" fill="#8892B0">
    AI&nbsp;BSc&nbsp;@&nbsp;KCL&nbsp;·&nbsp;ML&nbsp;&amp;&nbsp;Software&nbsp;Engineer
  </text>

  <!-- Skills row -->
  <text x="30" y="120" font-size="13" fill="#CCD6F6">
    ⚙️&nbsp;Python&nbsp;&nbsp;|&nbsp;&nbsp;Java&nbsp;&nbsp;|&nbsp;&nbsp;TensorFlow&nbsp;&nbsp;|&nbsp;&nbsp;Docker&nbsp;&nbsp;|&nbsp;&nbsp;AWS
  </text>

  <!-- ----------  Cycling achievements  ---------- -->
  <!-- Each <g class="achieve"> holds one message;
       stagger animation-delay so they appear one after another -->
  <g class="achieve" style="animation-delay:0s"><text x="30" y="155">
    • Marshall Wace Scholar – £9.9 k merit award:contentReference[oaicite:0]{index=0}
  </text></g>

  <g class="achieve" style="animation-delay:5s"><text x="30" y="155">
    • Hyperloop Braking System Award ’24 (Global top prize):contentReference[oaicite:1]{index=1}
  </text></g>

  <g class="achieve" style="animation-delay:10s"><text x="30" y="155">
    • Rank 1st (60 peers) Goldman Sachs trading sim, £ PnL top 3:contentReference[oaicite:2]{index=2}
  </text></g>

  <g class="achieve" style="animation-delay:15s"><text x="30" y="155">
    • Built “Accessify” to boost web accessibility – React&nbsp;+&nbsp;FastAPI:contentReference[oaicite:3]{index=3}
  </text></g>

</svg>
