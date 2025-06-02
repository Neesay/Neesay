<?xml version="1.0" encoding="UTF-8"?>
<svg  xmlns="http://www.w3.org/2000/svg"
      width="460" height="200" viewBox="0 0 460 200" role="img"
      aria-labelledby="title desc">
  <title id="title">Animated README card – Yaseen Mehraf Alam</title>
  <desc id="desc">
    Animated profile card cycling through achievements – built for GitHub README use.
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
  <text x="30"  y="60"  font-size="28" font-weight="700" fill="#64ffda">
      Yaseen&nbsp;Mehraf&nbsp;Alam
  </text>

  <text x="32"  y="90"  font-size="15" fill="#8892B0">
    AI&nbsp;BSc&nbsp;@&nbsp;KCL&nbsp;·&nbsp;ML&nbsp;&amp;&nbsp;Software&nbsp;Engineer
  </text>

  <text x="30"  y="120" font-size="13" fill="#CCD6F6">
    ⚙️&nbsp;Python&nbsp;&nbsp;|&nbsp;&nbsp;Java&nbsp;&nbsp;|&nbsp;&nbsp;TensorFlow&nbsp;&nbsp;|&nbsp;&nbsp;Docker&nbsp;&nbsp;|&nbsp;&nbsp;AWS
  </text>

  <!-- ----------  Cycling achievements  ---------- -->
  <g class="achieve" style="animation-delay:0s"><text x="30" y="155">
    • Marshall Wace Scholar – £9.9 k merit award
  </text></g>

  <g class="achieve" style="animation-delay:5s"><text x="30" y="155">
    • Hyperloop Braking System Award ’24 – Global top prize
  </text></g>

  <g class="achieve" style="animation-delay:10s"><text x="30" y="155">
    • Rank 1/60 – Goldman Sachs trading sim (PnL top 3)
  </text></g>

  <g class="achieve" style="animation-delay:15s"><text x="30" y="155">
    • Built “Accessify” – React + FastAPI accessibility tool
  </text></g>

</svg>
