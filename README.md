<div align="center">

<!-- WELCOME BANNER -->
<svg viewBox="0 0 900 320" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:900px;">
  <defs>
    <filter id="glowR"><feGaussianBlur stdDeviation="3"/><feMerge><feMergeNode/><feMergeNode in="SourceGraphic"/></feMerge></filter>
    <filter id="glowI"><feGaussianBlur stdDeviation="6"/><feMerge><feMergeNode/><feMergeNode in="SourceGraphic"/></feMerge></filter>
    <filter id="glowS"><feGaussianBlur stdDeviation="2"/><feMerge><feMergeNode/><feMergeNode in="SourceGraphic"/></feMerge></filter>
    <radialGradient id="dotG" cx="50%" cy="50%" r="50%"><stop offset="0%" stop-color="#ff003c" stop-opacity="0.9"/><stop offset="60%" stop-color="#ff003c" stop-opacity="0.3"/><stop offset="100%" stop-color="#ff003c" stop-opacity="0"/></radialGradient>
    <radialGradient id="coreG" cx="50%" cy="50%" r="50%"><stop offset="0%" stop-color="#ff003c" stop-opacity="1"/><stop offset="40%" stop-color="#ff1744" stop-opacity="0.6"/><stop offset="100%" stop-color="#ff003c" stop-opacity="0"/></radialGradient>
  </defs>
  <style>
    @keyframes pn{0%,100%{r:2.5;opacity:0.6}50%{r:5;opacity:1}}
    @keyframes pc{0%,100%{r:15;opacity:0.8}50%{r:22;opacity:1}}
    @keyframes pr{0%,100%{r:25;opacity:0.4;stroke-width:1}50%{r:45;opacity:0.08;stroke-width:0.3}}
    @keyframes fp{0%{transform:translateY(0);opacity:0}20%{opacity:0.7}80%{opacity:0.7}100%{transform:translateY(-50px);opacity:0}}
    @keyframes fp2{0%{transform:translateY(0)translateX(0);opacity:0}25%{opacity:0.5}75%{opacity:0.5}100%{transform:translateY(-35px)translateX(12px);opacity:0}}
    @keyframes dm{to{stroke-dashoffset:-200}}
    @keyframes dm2{to{stroke-dashoffset:200}}
    @keyframes rs{from{transform:rotate(0deg)}to{transform:rotate(360deg)}}
    @keyframes rr{from{transform:rotate(360deg)}to{transform:rotate(0deg)}}
    @keyframes fk{0%,100%{opacity:1}50%{opacity:0.3}53%{opacity:1}56%{opacity:0.2}60%{opacity:1}}
    @keyframes sl{0%{transform:translateY(-100px)}100%{transform:translateY(380px)}}
    .p{animation:pn 2s ease-in-out infinite}.pc{animation:pc 2.5s ease-in-out infinite}.pr{animation:pr 3s ease-in-out infinite}.fp{animation:fp 4s ease-in-out infinite}.fp2{animation:fp2 5s ease-in-out infinite}.d{animation:dm 3s linear infinite}.d2{animation:dm2 4s linear infinite}.rt{animation:rs 8s linear infinite;transform-origin:450px 150px}.rr{animation:rr 12s linear infinite;transform-origin:450px 150px}.fk{animation:fk 5s ease-in-out infinite}.sl{animation:sl 4s linear infinite}
  </style>
  <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse"><circle cx="20" cy="20" r="0.8" fill="#ff003c" opacity="0.08"/></pattern>
  <rect width="900" height="320" fill="url(#grid)"/>
  <rect x="0" y="0" width="900" height="2" fill="#ff003c" opacity="0.3" class="sl" filter="url(#glowR)"/>
  
  <!-- CONNECTING LINES -->
  <line x1="450" y1="150" x2="340" y2="80" stroke="#ff003c" stroke-width="0.8" opacity="0.35" class="d" stroke-dasharray="4 6"/>
  <line x1="450" y1="150" x2="560" y2="80" stroke="#ff003c" stroke-width="0.8" opacity="0.35" class="d2" stroke-dasharray="5 5"/>
  <line x1="450" y1="150" x2="340" y2="220" stroke="#ff003c" stroke-width="0.8" opacity="0.3" class="d2" stroke-dasharray="3 7"/>
  <line x1="450" y1="150" x2="560" y2="220" stroke="#ff003c" stroke-width="0.8" opacity="0.3" class="d" stroke-dasharray="6 4"/>
  <line x1="450" y1="150" x2="280" y2="150" stroke="#ff003c" stroke-width="0.6" opacity="0.25" class="d2" stroke-dasharray="3 8"/>
  <line x1="450" y1="150" x2="620" y2="150" stroke="#ff003c" stroke-width="0.6" opacity="0.25" class="d" stroke-dasharray="4 7"/>
  
  <line x1="340" y1="80" x2="240" y2="50" stroke="#ff003c" stroke-width="0.5" opacity="0.18">
    <animate attributeName="stroke-dashoffset" from="0" to="-100" dur="3s" repeatCount="indefinite" stroke-dasharray="3 6"/>
  </line>
  <line x1="560" y1="80" x2="660" y2="50" stroke="#ff003c" stroke-width="0.5" opacity="0.18">
    <animate attributeName="stroke-dashoffset" from="0" to="100" dur="3.5s" repeatCount="indefinite" stroke-dasharray="3 6"/>
  </line>
  <line x1="340" y1="220" x2="240" y2="250" stroke="#ff003c" stroke-width="0.5" opacity="0.18">
    <animate attributeName="stroke-dashoffset" from="0" to="100" dur="3.2s" repeatCount="indefinite" stroke-dasharray="3 6"/>
  </line>
  <line x1="560" y1="220" x2="660" y2="250" stroke="#ff003c" stroke-width="0.5" opacity="0.18">
    <animate attributeName="stroke-dashoffset" from="0" to="-100" dur="3.7s" repeatCount="indefinite" stroke-dasharray="3 6"/>
  </line>
  
  <line x1="240" y1="50" x2="170" y2="35" stroke="#ff003c" stroke-width="0.4" opacity="0.1">
    <animate attributeName="stroke-dashoffset" from="0" to="-100" dur="5s" repeatCount="indefinite" stroke-dasharray="2 8"/>
  </line>
  <line x1="660" y1="50" x2="730" y2="35" stroke="#ff003c" stroke-width="0.4" opacity="0.1">
    <animate attributeName="stroke-dashoffset" from="0" to="100" dur="5s" repeatCount="indefinite" stroke-dasharray="2 8"/>
  </line>
  
  <!-- ROTATING ORBITS -->
  <g class="rt"><ellipse cx="450" cy="150" rx="90" ry="30" fill="none" stroke="#ff003c" stroke-width="0.6" opacity="0.15" filter="url(#glowS)"/></g>
  <g class="rr"><ellipse cx="450" cy="150" rx="120" ry="38" fill="none" stroke="#ff003c" stroke-width="0.4" opacity="0.1" filter="url(#glowS)"/></g>
  
  <!-- CORE -->
  <circle cx="450" cy="150" r="30" fill="url(#coreG)" filter="url(#glowI)"/>
  <circle cx="450" cy="150" r="7" fill="#ff003c" filter="url(#glowI)" class="pc"/>
  <circle cx="450" cy="150" r="12" fill="none" stroke="#ff003c" stroke-width="1.5" opacity="0.5" class="pr" filter="url(#glowR)"/>
  <circle cx="450" cy="150" r="40" fill="none" stroke="#ff003c" stroke-width="0.5" opacity="0.15" class="pr" filter="url(#glowR)"/>
  
  <!-- NODES -->
  <circle cx="340" cy="80" r="6" fill="url(#dotG)" filter="url(#glowR)"/><circle cx="340" cy="80" r="2.5" fill="#fff" class="p"/>
  <circle cx="560" cy="80" r="6" fill="url(#dotG)" filter="url(#glowR)"/><circle cx="560" cy="80" r="2.5" fill="#fff" class="p" style="animation-delay:0.5s"/>
  <circle cx="340" cy="220" r="6" fill="url(#dotG)" filter="url(#glowR)"/><circle cx="340" cy="220" r="2.5" fill="#fff" class="p" style="animation-delay:1s"/>
  <circle cx="560" cy="220" r="6" fill="url(#dotG)" filter="url(#glowR)"/><circle cx="560" cy="220" r="2.5" fill="#fff" class="p" style="animation-delay:1.5s"/>
  <circle cx="280" cy="150" r="5" fill="url(#dotG)" filter="url(#glowR)"/><circle cx="280" cy="150" r="2" fill="#fff" class="p" style="animation-delay:0.3s"/>
  <circle cx="620" cy="150" r="5" fill="url(#dotG)" filter="url(#glowR)"/><circle cx="620" cy="150" r="2" fill="#fff" class="p" style="animation-delay:0.8s"/>
  <circle cx="240" cy="50" r="4" fill="url(#dotG)" filter="url(#glowS)"/><circle cx="240" cy="50" r="1.5" fill="#fff" class="p" style="animation-delay:0.2s"/>
  <circle cx="660" cy="50" r="4" fill="url(#dotG)" filter="url(#glowS)"/><circle cx="660" cy="50" r="1.5" fill="#fff" class="p" style="animation-delay:0.7s"/>
  <circle cx="170" cy="35" r="3" fill="url(#dotG)" filter="url(#glowS)"/><circle cx="170" cy="35" r="1" fill="#fff"/>
  <circle cx="730" cy="35" r="3" fill="url(#dotG)" filter="url(#glowS)"/><circle cx="730" cy="35" r="1" fill="#fff"/>
  
  <!-- FLOATING PARTICLES -->
  <circle cx="140" cy="210" r="1.5" fill="#ff003c" opacity="0.6" class="fp" filter="url(#glowS)"/>
  <circle cx="300" cy="280" r="1" fill="#ff003c" opacity="0.4" class="fp2" style="animation-delay:0.5s"/>
  <circle cx="510" cy="290" r="1.5" fill="#ff003c" opacity="0.5" class="fp" style="animation-delay:1s"/>
  <circle cx="680" cy="260" r="1" fill="#ff003c" opacity="0.4" class="fp2" style="animation-delay:1.5s"/>
  <circle cx="780" cy="230" r="1.5" fill="#ff003c" opacity="0.3" class="fp" style="animation-delay:2s"/>
  <circle cx="200" cy="130" r="1" fill="#ff003c" opacity="0.5" class="fp2" style="animation-delay:0.8s"/>
  <circle cx="720" cy="190" r="1" fill="#ff003c" opacity="0.4" class="fp" style="animation-delay:1.3s"/>
  
  <!-- CORNER DECORATIONS -->
  <path d="M 20 10 L 20 35" fill="none" stroke="#ff003c" stroke-width="2" opacity="0.4" filter="url(#glowS)">
    <animate attributeName="opacity" values="0.4;0.15;0.4" dur="2s" repeatCount="indefinite"/>
  </path>
  <path d="M 880 10 L 880 35" fill="none" stroke="#ff003c" stroke-width="2" opacity="0.4" filter="url(#glowS)">
    <animate attributeName="opacity" values="0.4;0.15;0.4" dur="2.3s" repeatCount="indefinite"/>
  </path>
  <path d="M 20 310 L 20 285" fill="none" stroke="#ff003c" stroke-width="2" opacity="0.4" filter="url(#glowS)">
    <animate attributeName="opacity" values="0.4;0.15;0.4" dur="1.8s" repeatCount="indefinite"/>
  </path>
  <path d="M 880 310 L 880 285" fill="none" stroke="#ff003c" stroke-width="2" opacity="0.4" filter="url(#glowS)">
    <animate attributeName="opacity" values="0.4;0.15;0.4" dur="2.7s" repeatCount="indefinite"/>
  </path>
  
  <!-- CORNER DOTS -->
  <circle cx="20" cy="35" r="2" fill="#ff003c" opacity="0.6" filter="url(#glowS)" class="fk"/>
  <circle cx="880" cy="35" r="2" fill="#ff003c" opacity="0.6" filter="url(#glowS)" class="fk" style="animation-delay:0.7s"/>
  <circle cx="20" cy="285" r="2" fill="#ff003c" opacity="0.6" filter="url(#glowS)" class="fk" style="animation-delay:0.4s"/>
  <circle cx="880" cy="285" r="2" fill="#ff003c" opacity="0.6" filter="url(#glowS)" class="fk" style="animation-delay:1s"/>
</svg>

<br/>

<!-- WELCOME TEXT -->
<svg viewBox="0 0 860 80" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:860px;">
  <defs>
    <linearGradient id="welcomeG" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#ff003c" stop-opacity="0"/><stop offset="15%" stop-color="#ff003c" stop-opacity="0.3"/>
      <stop offset="50%" stop-color="#ff003c" stop-opacity="0.8"/><stop offset="85%" stop-color="#ff003c" stop-opacity="0.3"/>
      <stop offset="100%" stop-color="#ff003c" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <line x1="0" y1="40" x2="860" y2="40" stroke="url(#welcomeG)" stroke-width="0.8"/>
  <text x="430" y="46" text-anchor="middle" fill="#ffffff" font-family="monospace" font-size="28" font-weight="bold" opacity="0.95" letter-spacing="4">WELCOME</text>
</svg>

</div>

<br/>

<div align="center">

<!-- STATUS CARD -->
<svg viewBox="0 0 700 100" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:700px;">
  <rect x="2" y="2" width="696" height="96" rx="12" fill="#050505" stroke="#ff003c" stroke-width="0.8" stroke-opacity="0.12"/>
  <line x1="20" y1="2" x2="680" y2="2" stroke="#ff003c" stroke-width="1.5" opacity="0.3"/>
  
  <text x="350" y="38" text-anchor="middle" fill="#bbbbbb" font-family="monospace" font-size="13" opacity="0.6">Started GitHub journey at 8th grade</text>
  <text x="350" y="62" text-anchor="middle" fill="#ff003c" font-family="monospace" font-size="15" opacity="0.9">vibe coder · building the future</text>
  
  <circle cx="22" cy="50" r="2" fill="#ff003c" opacity="0.8" filter="url(#glowR)">
    <animate attributeName="opacity" values="0.8;0.2;0.8" dur="1s" repeatCount="indefinite"/>
  </circle>
</svg>

</div>

<br/>

<div align="center">

<!-- STACK SECTION LABEL -->
<svg viewBox="0 0 860 40" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:860px;">
  <defs>
    <linearGradient id="secG" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#ff003c" stop-opacity="0"/><stop offset="15%" stop-color="#ff003c" stop-opacity="0.4"/>
      <stop offset="50%" stop-color="#ff003c" stop-opacity="0.8"/><stop offset="85%" stop-color="#ff003c" stop-opacity="0.4"/>
      <stop offset="100%" stop-color="#ff003c" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <line x1="0" y1="20" x2="860" y2="20" stroke="url(#secG)" stroke-width="0.8"/>
  <text x="430" y="24" text-anchor="middle" fill="#ff003c" font-family="monospace" font-size="10" opacity="0.6" letter-spacing="5">STACK</text>
</svg>

<br/>

<a href="#"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/></a>
<a href="#"><img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go"/></a>
<a href="#"><img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++"/></a>
<a href="#"><img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" alt="Rust"/></a>
<a href="#"><img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/></a>
<a href="#"><img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite"/></a>

</div>

<br/>

<div align="center">

<!-- STATS LABEL -->
<svg viewBox="0 0 860 40" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:860px;">
  <defs>
    <linearGradient id="secG2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#ff003c" stop-opacity="0"/><stop offset="15%" stop-color="#ff003c" stop-opacity="0.4"/>
      <stop offset="50%" stop-color="#ff003c" stop-opacity="0.8"/><stop offset="85%" stop-color="#ff003c" stop-opacity="0.4"/>
      <stop offset="100%" stop-color="#ff003c" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <line x1="0" y1="20" x2="860" y2="20" stroke="url(#secG2)" stroke-width="0.8"/>
  <text x="430" y="24" text-anchor="middle" fill="#ff003c" font-family="monospace" font-size="10" opacity="0.6" letter-spacing="5">STATS</text>
</svg>

<br/>

<table>
  <tr>
    <td align="center" width="50%">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=Solveran601&show_icons=true&theme=dark&hide_border=true&count_private=true&bg_color=0d1117&title_color=ff003c&icon_color=ff003c&text_color=ffffff&border_color=1a1a1a&ring_color=ff003c&rank_icon=default&card_width=400"/>
        <img src="https://github-readme-stats.vercel.app/api?username=Solveran601&show_icons=true&theme=dark&hide_border=true&count_private=true&bg_color=0d1117&title_color=ff003c&icon_color=ff003c&text_color=ffffff&border_color=1a1a1a&ring_color=ff003c&rank_icon=default&card_width=400" width="95%"/>
      </picture>
    </td>
    <td align="center" width="50%">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Solveran601&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=ff003c&text_color=ffffff&border_color=1a1a1a&card_width=400"/>
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Solveran601&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=ff003c&text_color=ffffff&border_color=1a1a1a&card_width=400" width="95%"/>
      </picture>
    </td>
  </tr>
</table>

</div>

<br/>

<div align="center">

<!-- FOOTER -->
<svg viewBox="0 0 860 60" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:860px;">
  <defs>
    <filter id="glassF"><feGaussianBlur in="SourceAlpha" stdDeviation="3"/><feOffset dx="0" dy="0"/><feFlood flood-color="#ff003c" flood-opacity="0.05"/><feComposite in2="offsetBlur" operator="in"/><feMerge><feMergeNode/><feMergeNode in="SourceGraphic"/></feMerge></filter>
  </defs>
  <rect x="2" y="2" width="856" height="56" rx="12" fill="#050505" stroke="#ff003c" stroke-width="0.8" stroke-opacity="0.1" filter="url(#glassF)"/>
  <line x1="20" y1="2" x2="840" y2="2" stroke="#ff003c" stroke-width="1" opacity="0.25"/>
  
  <image href="https://api.visitorbadge.io/api/visitors?path=Solveran601%2FSolveran601&countColor=%23ff003c&style=flat&label=&labelColor=%23000000" x="700" y="15" width="130" height="35"/>
  <text x="430" y="50" text-anchor="middle" fill="#333333" font-family="monospace" font-size="8" opacity="0.4">SOLVERAN // ALL SYSTEMS OPERATIONAL</text>
</svg>

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:ff003c,40:111111,70:0a0a0a,100:000000&height=150&section=footer&animation=fadeIn" width="100%"/>

</div>