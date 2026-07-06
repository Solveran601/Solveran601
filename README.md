<!-- 
пїЅ==============================================================================пїЅ
пїЅ  SOLVERAN // PROFILE v2.0                                                  пїЅ
пїЅ  ---------------------------------------------                               пїЅ
пїЅ  NEURAL INTERFACE // CYBERPUNK EDITION                                     пїЅ
L==============================================================================-
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&amp;color=0:000000,30:0a0a0a,60:111111,100:ff003c&amp;height=280&amp;section=header&amp;text=SOLVERAN&amp;fontSize=70&amp;fontColor=ff003c&amp;fontAlignY=30&amp;desc=%3E+neural+interface+initialized&amp;descSize=16&amp;descAlignY=52&amp;descColor=bbbbbb&amp;animation=fadeIn" width="100%"/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;weight=600&amp;size=22&amp;duration=2500&amp;pause=800&amp;color=FF003C&amp;center=true&amp;vCenter=true&amp;multiline=true&amp;repeat=true&amp;width=700&amp;height=100&amp;lines=%3E+system+online+v2.0;%3E+neural+core+active;%3E+status:+creating;%3E+mission:+build+the+future" width="100%"/>

</div>
<svg viewBox="0 0 900 300" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:900px;display:block;margin:0 auto;">
  <defs>
    <filter id="glowRed">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="glowIntense">
      <feGaussianBlur stdDeviation="6" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="glowSoft">
      <feGaussianBlur stdDeviation="2" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <radialGradient id="nodeGlow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#ff003c" stop-opacity="0.9"/>
      <stop offset="60%" stop-color="#ff003c" stop-opacity="0.3"/>
      <stop offset="100%" stop-color="#ff003c" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="coreGlow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#ff003c" stop-opacity="1"/>
      <stop offset="40%" stop-color="#ff1744" stop-opacity="0.6"/>
      <stop offset="100%" stop-color="#ff003c" stop-opacity="0"/>
    </radialGradient>
  </defs>
  <style>
    @keyframes pulseNode { 0%,100%{r:3;opacity:0.7} 50%{r:6;opacity:1} }
    @keyframes pulseCore { 0%,100%{r:18;opacity:0.8} 50%{r:25;opacity:1} }
    @keyframes pulseRing { 0%,100%{r:30;opacity:0.4;stroke-width:1} 50%{r:50;opacity:0.1;stroke-width:0.5} }
    @keyframes floatParticle {
      0%{transform:translateY(0);opacity:0} 20%{opacity:0.8} 80%{opacity:0.8} 100%{transform:translateY(-60px);opacity:0}
    }
    @keyframes floatParticle2 {
      0%{transform:translateY(0)translateX(0);opacity:0} 25%{opacity:0.6} 75%{opacity:0.6} 100%{transform:translateY(-40px)translateX(15px);opacity:0}
    }
    @keyframes dashMove { to{stroke-dashoffset:-200} }
    @keyframes dashMove2 { to{stroke-dashoffset:200} }
    @keyframes rotateSlow { from{transform:rotate(0deg)} to{transform:rotate(360deg)} }
    @keyframes rotateReverse { from{transform:rotate(360deg)} to{transform:rotate(0deg)} }
    @keyframes flicker { 0%,100%{opacity:1} 50%{opacity:0.3} 53%{opacity:1} 56%{opacity:0.2} 60%{opacity:1} }
    @keyframes scanLine { 0%{transform:translateY(-100px)} 100%{transform:translateY(400px)} }
    .particle{animation:floatParticle 4s ease-in-out infinite}
    .particle2{animation:floatParticle2 5s ease-in-out infinite}
    .pulse{animation:pulseNode 2s ease-in-out infinite}
    .pulse-core{animation:pulseCore 2.5s ease-in-out infinite}
    .pulse-ring{animation:pulseRing 3s ease-in-out infinite}
    .dash{animation:dashMove 3s linear infinite}
    .dash2{animation:dashMove2 4s linear infinite}
    .rotate{animation:rotateSlow 8s linear infinite;transform-origin:450px 150px}
    .rotate-rev{animation:rotateReverse 12s linear infinite;transform-origin:450px 150px}
    .flicker{animation:flicker 5s ease-in-out infinite}
    .scan{animation:scanLine 4s linear infinite}
  </style>
  <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
    <circle cx="20" cy="20" r="0.8" fill="#ff003c" opacity="0.08"/>
  </pattern>
  <rect width="900" height="300" fill="url(#grid)"/>
  <rect x="0" y="0" width="900" height="2" fill="#ff003c" opacity="0.3" class="scan" filter="url(#glowRed)"/>
  <line x1="450" y1="150" x2="350" y2="90" stroke="#ff003c" stroke-width="0.8" opacity="0.4" class="dash" stroke-dasharray="4 6"/>
  <line x1="450" y1="150" x2="550" y2="90" stroke="#ff003c" stroke-width="0.8" opacity="0.4" class="dash2" stroke-dasharray="5 5"/>
  <line x1="450" y1="150" x2="350" y2="210" stroke="#ff003c" stroke-width="0.8" opacity="0.3" class="dash2" stroke-dasharray="3 7"/>
  <line x1="450" y1="150" x2="550" y2="210" stroke="#ff003c" stroke-width="0.8" opacity="0.3" class="dash" stroke-dasharray="6 4"/>
  <line x1="450" y1="150" x2="300" y2="150" stroke="#ff003c" stroke-width="0.6" opacity="0.25" class="dash2" stroke-dasharray="3 8"/>
  <line x1="450" y1="150" x2="600" y2="150" stroke="#ff003c" stroke-width="0.6" opacity="0.25" class="dash" stroke-dasharray="4 7"/>
  <line x1="350" y1="90" x2="250" y2="60" stroke="#ff003c" stroke-width="0.5" opacity="0.2" stroke-dasharray="3 6">
    <animate attributeName="stroke-dashoffset" from="0" to="-100" dur="3s" repeatCount="indefinite"/>
  </line>
  <line x1="550" y1="90" x2="650" y2="60" stroke="#ff003c" stroke-width="0.5" opacity="0.2" stroke-dasharray="3 6">
    <animate attributeName="stroke-dashoffset" from="0" to="100" dur="3.5s" repeatCount="indefinite"/>
  </line>
  <line x1="350" y1="90" x2="300" y2="150" stroke="#ff003c" stroke-width="0.5" opacity="0.15" stroke-dasharray="4 8">
    <animate attributeName="stroke-dashoffset" from="0" to="100" dur="4s" repeatCount="indefinite"/>
  </line>
  <line x1="550" y1="90" x2="600" y2="150" stroke="#ff003c" stroke-width="0.5" opacity="0.15" stroke-dasharray="4 8">
    <animate attributeName="stroke-dashoffset" from="0" to="-100" dur="4s" repeatCount="indefinite"/>
  </line>
  <line x1="350" y1="210" x2="250" y2="240" stroke="#ff003c" stroke-width="0.5" opacity="0.2" stroke-dasharray="3 6">
    <animate attributeName="stroke-dashoffset" from="0" to="100" dur="3.2s" repeatCount="indefinite"/>
  </line>
  <line x1="550" y1="210" x2="650" y2="240" stroke="#ff003c" stroke-width="0.5" opacity="0.2" stroke-dasharray="3 6">
    <animate attributeName="stroke-dashoffset" from="0" to="-100" dur="3.7s" repeatCount="indefinite"/>
  </line>
  <line x1="350" y1="210" x2="300" y2="150" stroke="#ff003c" stroke-width="0.5" opacity="0.15" stroke-dasharray="4 8">
    <animate attributeName="stroke-dashoffset" from="0" to="-100" dur="4.2s" repeatCount="indefinite"/>
  </line>
  <line x1="550" y1="210" x2="600" y2="150" stroke="#ff003c" stroke-width="0.5" opacity="0.15" stroke-dasharray="4 8">
    <animate attributeName="stroke-dashoffset" from="0" to="100" dur="3.8s" repeatCount="indefinite"/>
  </line>
  <line x1="250" y1="60" x2="180" y2="40" stroke="#ff003c" stroke-width="0.4" opacity="0.12" stroke-dasharray="2 8">
    <animate attributeName="stroke-dashoffset" from="0" to="-100" dur="5s" repeatCount="indefinite"/>
  </line>
  <line x1="650" y1="60" x2="720" y2="40" stroke="#ff003c" stroke-width="0.4" opacity="0.12" stroke-dasharray="2 8">
    <animate attributeName="stroke-dashoffset" from="0" to="100" dur="5s" repeatCount="indefinite"/>
  </line>
  <line x1="250" y1="240" x2="180" y2="260" stroke="#ff003c" stroke-width="0.4" opacity="0.12" stroke-dasharray="2 8">
    <animate attributeName="stroke-dashoffset" from="0" to="100" dur="5.5s" repeatCount="indefinite"/>
  </line>
  <line x1="650" y1="240" x2="720" y2="260" stroke="#ff003c" stroke-width="0.4" opacity="0.12" stroke-dasharray="2 8">
    <animate attributeName="stroke-dashoffset" from="0" to="-100" dur="5.5s" repeatCount="indefinite"/>
  </line>
  <g class="rotate">
    <ellipse cx="450" cy="150" rx="90" ry="30" fill="none" stroke="#ff003c" stroke-width="0.6" opacity="0.2" filter="url(#glowSoft)"/>
  </g>
  <g class="rotate-rev">
    <ellipse cx="450" cy="150" rx="110" ry="35" fill="none" stroke="#ff003c" stroke-width="0.4" opacity="0.15" filter="url(#glowSoft)"/>
  </g>
  <circle cx="450" cy="150" r="30" fill="url(#coreGlow)" filter="url(#glowIntense)"/>
  <circle cx="450" cy="150" r="8" fill="#ff003c" filter="url(#glowIntense)" class="pulse-core"/>
  <circle cx="450" cy="150" r="12" fill="none" stroke="#ff003c" stroke-width="1" opacity="0.6" class="pulse-ring" filter="url(#glowRed)"/>
  <circle cx="450" cy="150" r="40" fill="none" stroke="#ff003c" stroke-width="0.5" opacity="0.2" class="pulse-ring" filter="url(#glowRed)"/>
  <circle cx="350" cy="90" r="6" fill="url(#nodeGlow)" filter="url(#glowRed)"/>
  <circle cx="350" cy="90" r="2.5" fill="#ffffff" class="pulse"/>
  <circle cx="550" cy="90" r="6" fill="url(#nodeGlow)" filter="url(#glowRed)"/>
  <circle cx="550" cy="90" r="2.5" fill="#ffffff" class="pulse" style="animation-delay: 0.5s;"/>
  <circle cx="350" cy="210" r="6" fill="url(#nodeGlow)" filter="url(#glowRed)"/>
  <circle cx="350" cy="210" r="2.5" fill="#ffffff" class="pulse" style="animation-delay: 1s;"/>
  <circle cx="550" cy="210" r="6" fill="url(#nodeGlow)" filter="url(#glowRed)"/>
  <circle cx="550" cy="210" r="2.5" fill="#ffffff" class="pulse" style="animation-delay: 1.5s;"/>
  <circle cx="300" cy="150" r="5" fill="url(#nodeGlow)" filter="url(#glowRed)"/>
  <circle cx="300" cy="150" r="2" fill="#ffffff" class="pulse" style="animation-delay: 0.3s;"/>
  <circle cx="600" cy="150" r="5" fill="url(#nodeGlow)" filter="url(#glowRed)"/>
  <circle cx="600" cy="150" r="2" fill="#ffffff" class="pulse" style="animation-delay: 0.8s;"/>
  <circle cx="250" cy="60" r="4" fill="url(#nodeGlow)" filter="url(#glowSoft)"/>
  <circle cx="250" cy="60" r="1.5" fill="#ffffff" class="pulse" style="animation-delay: 0.2s;"/>
  <circle cx="650" cy="60" r="4" fill="url(#nodeGlow)" filter="url(#glowSoft)"/>
  <circle cx="650" cy="60" r="1.5" fill="#ffffff" class="pulse" style="animation-delay: 0.7s;"/>
  <circle cx="250" cy="240" r="4" fill="url(#nodeGlow)" filter="url(#glowSoft)"/>
  <circle cx="250" cy="240" r="1.5" fill="#ffffff" class="pulse" style="animation-delay: 1.2s;"/>
  <circle cx="650" cy="240" r="4" fill="url(#nodeGlow)" filter="url(#glowSoft)"/>
  <circle cx="650" cy="240" r="1.5" fill="#ffffff" class="pulse" style="animation-delay: 1.7s;"/>
  <circle cx="180" cy="40" r="3" fill="url(#nodeGlow)" filter="url(#glowSoft)"/>
  <circle cx="180" cy="40" r="1" fill="#ffffff"/>
  <circle cx="720" cy="40" r="3" fill="url(#nodeGlow)" filter="url(#glowSoft)"/>
  <circle cx="720" cy="40" r="1" fill="#ffffff"/>
  <circle cx="180" cy="260" r="3" fill="url(#nodeGlow)" filter="url(#glowSoft)"/>
  <circle cx="180" cy="260" r="1" fill="#ffffff"/>
  <circle cx="720" cy="260" r="3" fill="url(#nodeGlow)" filter="url(#glowSoft)"/>
  <circle cx="720" cy="260" r="1" fill="#ffffff"/>
  <circle cx="150" cy="200" r="1.5" fill="#ff003c" opacity="0.6" class="particle" filter="url(#glowSoft)"/>
  <circle cx="300" cy="260" r="1" fill="#ff003c" opacity="0.4" class="particle2" style="animation-delay: 0.5s;"/>
  <circle cx="500" cy="280" r="1.5" fill="#ff003c" opacity="0.5" class="particle" style="animation-delay: 1s;"/>
  <circle cx="650" cy="250" r="1" fill="#ff003c" opacity="0.4" class="particle2" style="animation-delay: 1.5s;"/>
  <circle cx="750" cy="220" r="1.5" fill="#ff003c" opacity="0.3" class="particle" style="animation-delay: 2s;"/>
  <circle cx="200" cy="140" r="1" fill="#ff003c" opacity="0.5" class="particle2" style="animation-delay: 0.8s;"/>
  <circle cx="700" cy="180" r="1" fill="#ff003c" opacity="0.4" class="particle" style="animation-delay: 1.3s;"/>
  <circle cx="400" cy="270" r="1.2" fill="#ff003c" opacity="0.5" class="particle2" style="animation-delay: 2.2s;"/>
  <circle cx="80" cy="220" r="1" fill="#ff003c" opacity="0.3" class="particle" style="animation-delay: 3s;"/>
  <circle cx="820" cy="150" r="1" fill="#ff003c" opacity="0.3" class="particle2" style="animation-delay: 3.5s;"/>
  <circle cx="450" cy="260" r="1.5" fill="#ff003c" opacity="0.4" class="particle" style="animation-delay: 0.3s;"/>
  <text x="450" y="158" text-anchor="middle" fill="#ffffff" font-family="monospace" font-size="10" font-weight="bold" opacity="0.9" filter="url(#glowSoft)">AI</text>
  <path d="M 20 0 L 20 30 L 0 30" fill="none" stroke="#ff003c" stroke-width="2" opacity="0.3" filter="url(#glowSoft)"/>
  <path d="M 20 0 L 20 30" fill="none" stroke="#ff003c" stroke-width="2" opacity="0.5" filter="url(#glowRed)">
    <animate attributeName="opacity" values="0.5;0.2;0.5" dur="2s" repeatCount="indefinite"/>
  </path>
  <path d="M 880 0 L 880 30 L 900 30" fill="none" stroke="#ff003c" stroke-width="2" opacity="0.3" filter="url(#glowSoft)"/>
  <path d="M 880 0 L 880 30" fill="none" stroke="#ff003c" stroke-width="2" opacity="0.5" filter="url(#glowRed)">
    <animate attributeName="opacity" values="0.5;0.2;0.5" dur="2.3s" repeatCount="indefinite"/>
  </path>
  <path d="M 20 300 L 20 270 L 0 270" fill="none" stroke="#ff003c" stroke-width="2" opacity="0.3" filter="url(#glowSoft)"/>
  <path d="M 20 300 L 20 270" fill="none" stroke="#ff003c" stroke-width="2" opacity="0.5" filter="url(#glowRed)">
    <animate attributeName="opacity" values="0.5;0.2;0.5" dur="1.8s" repeatCount="indefinite"/>
  </path>
  <path d="M 880 300 L 880 270 L 900 270" fill="none" stroke="#ff003c" stroke-width="2" opacity="0.3" filter="url(#glowSoft)"/>
  <path d="M 880 300 L 880 270" fill="none" stroke="#ff003c" stroke-width="2" opacity="0.5" filter="url(#glowRed)">
    <animate attributeName="opacity" values="0.5;0.2;0.5" dur="2.7s" repeatCount="indefinite"/>
  </path>
  <text x="35" y="290" fill="#ff003c" font-family="monospace" font-size="9" opacity="0.4">SYS::ACTIVE</text>
  <text x="800" y="290" fill="#ff003c" font-family="monospace" font-size="9" opacity="0.4">NODE::v2.0</text>
  <text x="35" y="18" fill="#ff003c" font-family="monospace" font-size="9" opacity="0.3">NEURAL_NET::ONLINE</text>
  <circle cx="22" cy="286" r="2" fill="#ff003c" opacity="0.6" filter="url(#glowSoft)" class="flicker"/>
  <circle cx="790" cy="286" r="2" fill="#ff003c" opacity="0.6" filter="url(#glowSoft)" class="flicker" style="animation-delay: 0.7s;"/>
</svg>

<br/>
<div align="center">


<svg viewBox="0 0 860 110" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:860px;">
  <defs>
    <filter id="glowRed">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="glowIntense">
      <feGaussianBlur stdDeviation="6" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="glowSoft">
      <feGaussianBlur stdDeviation="2" result="coloredBlur"/>
      <feMerge><feMergeNode in="coloredBlur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="glassCard">
      <feGaussianBlur in="SourceAlpha" stdDeviation="3" result="blur"/>
      <feOffset dx="0" dy="0" result="offsetBlur"/>
      <feFlood flood-color="#ff003c" flood-opacity="0.05" result="color"/>
      <feComposite in="color" in2="offsetBlur" operator="in" result="shadow"/>
      <feMerge><feMergeNode in="shadow"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>
  <filter id="glassCard">
    <feGaussianBlur in="SourceAlpha" stdDeviation="3" result="blur"/>
    <feOffset dx="0" dy="0" result="offsetBlur"/>
    <feFlood flood-color="#ff003c" flood-opacity="0.05" result="color"/>
    <feComposite in="color" in2="offsetBlur" operator="in" result="shadow"/>
    <feMerge><feMergeNode in="shadow"/><feMergeNode in="SourceGraphic"/></feMerge>
  </filter>
  <rect x="2" y="2" width="856" height="106" rx="16" fill="#050505" stroke="#ff003c" stroke-width="1" stroke-opacity="0.15" filter="url(#glassCard)"/>
  <line x1="20" y1="2" x2="840" y2="2" stroke="#ff003c" stroke-width="1.5" opacity="0.4" filter="url(#glowRed)">
    <animate attributeName="opacity" values="0.4;0.15;0.4" dur="3s" repeatCount="indefinite"/>
  </line>
  <circle cx="40" cy="55" r="5" fill="#ff003c" filter="url(#glowIntense)">
    <animate attributeName="r" values="5;7;5" dur="1.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="1;0.6;1" dur="1.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="40" cy="55" r="10" fill="none" stroke="#ff003c" stroke-width="1" opacity="0.3">
    <animate attributeName="r" values="10;16;10" dur="1.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0.05;0.3" dur="1.5s" repeatCount="indefinite"/>
  </circle>
  <text x="60" y="44" fill="#ffffff" font-family="monospace" font-size="14" font-weight="bold" opacity="0.95">AI Engineer</text>
  <text x="60" y="62" fill="#bbbbbb" font-family="monospace" font-size="11" opacity="0.7">Building tools &middot; Learning every day</text>
  <line x1="330" y1="20" x2="330" y2="90" stroke="#ff003c" stroke-width="0.5" opacity="0.2"/>
  <text x="360" y="42" fill="#bbbbbb" font-family="monospace" font-size="10" opacity="0.5">STATUS</text>
  <text x="360" y="60" fill="#ff003c" font-family="monospace" font-size="12" opacity="0.9">active</text>
  <circle cx="355" cy="56" r="2" fill="#ff003c" opacity="0.8" filter="url(#glowRed)">
    <animate attributeName="opacity" values="0.8;0.2;0.8" dur="1s" repeatCount="indefinite"/>
  </circle>
  <text x="460" y="42" fill="#bbbbbb" font-family="monospace" font-size="10" opacity="0.5">FOCUS</text>
  <text x="460" y="60" fill="#ff003c" font-family="monospace" font-size="12" opacity="0.9">full-stack</text>
  <text x="560" y="42" fill="#bbbbbb" font-family="monospace" font-size="10" opacity="0.5">MODE</text>
  <text x="560" y="60" fill="#ff003c" font-family="monospace" font-size="12" opacity="0.9">creation</text>
  <line x1="660" y1="20" x2="660" y2="90" stroke="#ff003c" stroke-width="0.5" opacity="0.2"/>
  <text x="690" y="55" fill="#ff003c" font-family="monospace" font-size="20" opacity="0.8" filter="url(#glowSoft)">&#9889;</text>
  <text x="730" y="55" fill="#ff003c" font-family="monospace" font-size="20" opacity="0.6" filter="url(#glowSoft)">&#128013;</text>
  <text x="775" y="55" fill="#ff003c" font-family="monospace" font-size="20" opacity="0.7" filter="url(#glowSoft)">&#x2388;</text>
</svg>

<br/><br/>

</div>
<div align="center">

<svg viewBox="0 0 860 50" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:860px;">
  <defs>
    <linearGradient id="labelLine" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#ff003c" stop-opacity="0"/>
      <stop offset="15%" stop-color="#ff003c" stop-opacity="0.4"/>
      <stop offset="50%" stop-color="#ff003c" stop-opacity="0.8"/>
      <stop offset="85%" stop-color="#ff003c" stop-opacity="0.4"/>
      <stop offset="100%" stop-color="#ff003c" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <line x1="0" y1="25" x2="860" y2="25" stroke="url(#labelLine)" stroke-width="0.8"/>
  <text x="430" y="29" text-anchor="middle" fill="#ff003c" font-family="monospace" font-size="11" opacity="0.7" letter-spacing="6">TECH STACK</text>
</svg>

<br/>

<table>
  <tr>
    <td width="25%" align="center" valign="top">
      <svg viewBox="0 0 195 160" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:195px;">
        <rect x="2" y="2" width="191" height="156" rx="12" fill="#050505" stroke="#ff003c" stroke-width="0.8" stroke-opacity="0.15"/>
        <line x1="10" y1="2" x2="185" y2="2" stroke="#ff003c" stroke-width="1.5" opacity="0.3"/>
        <text x="98" y="30" text-anchor="middle" fill="#ffffff" font-family="monospace" font-size="11" font-weight="bold" opacity="0.8">LANGUAGES</text>
        <line x1="40" y1="38" x2="155" y2="38" stroke="#ff003c" stroke-width="0.3" opacity="0.15"/>
        <image href="https://skillicons.dev/icons?i=python&amp;theme=dark" x="35" y="50" width="40" height="40"/>
        <image href="https://skillicons.dev/icons?i=javascript&amp;theme=dark" x="80" y="50" width="40" height="40"/>
        <image href="https://skillicons.dev/icons?i=typescript&amp;theme=dark" x="125" y="50" width="40" height="40"/>
        <image href="https://skillicons.dev/icons?i=html&amp;theme=dark" x="35" y="95" width="40" height="40"/>
        <image href="https://skillicons.dev/icons?i=css&amp;theme=dark" x="80" y="95" width="40" height="40"/>
        <image href="https://skillicons.dev/icons?i=md&amp;theme=dark" x="125" y="95" width="40" height="40"/>
      </svg>
    </td>
    <td width="25%" align="center" valign="top">
      <svg viewBox="0 0 195 160" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:195px;">
        <rect x="2" y="2" width="191" height="156" rx="12" fill="#050505" stroke="#ff003c" stroke-width="0.8" stroke-opacity="0.15"/>
        <line x1="10" y1="2" x2="185" y2="2" stroke="#ff003c" stroke-width="1.5" opacity="0.3"/>
        <text x="98" y="30" text-anchor="middle" fill="#ffffff" font-family="monospace" font-size="11" font-weight="bold" opacity="0.8">FRAMEWORKS</text>
        <line x1="30" y1="38" x2="165" y2="38" stroke="#ff003c" stroke-width="0.3" opacity="0.15"/>
        <image href="https://skillicons.dev/icons?i=react&amp;theme=dark" x="35" y="50" width="40" height="40"/>
        <image href="https://skillicons.dev/icons?i=nodejs&amp;theme=dark" x="80" y="50" width="40" height="40"/>
        <image href="https://skillicons.dev/icons?i=nextjs&amp;theme=dark" x="125" y="50" width="40" height="40"/>
        <image href="https://skillicons.dev/icons?i=tailwind&amp;theme=dark" x="35" y="95" width="40" height="40"/>
        <image href="https://skillicons.dev/icons?i=fastapi&amp;theme=dark" x="80" y="95" width="40" height="40"/>
        <image href="https://skillicons.dev/icons?i=flask&amp;theme=dark" x="125" y="95" width="40" height="40"/>
      </svg>
    </td>
    <td width="25%" align="center" valign="top">
      <svg viewBox="0 0 195 160" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:195px;">
        <rect x="2" y="2" width="191" height="156" rx="12" fill="#050505" stroke="#ff003c" stroke-width="0.8" stroke-opacity="0.15"/>
        <line x1="10" y1="2" x2="185" y2="2" stroke="#ff003c" stroke-width="1.5" opacity="0.3"/>
        <text x="98" y="30" text-anchor="middle" fill="#ffffff" font-family="monospace" font-size="11" font-weight="bold" opacity="0.8">TOOLS</text>
        <line x1="45" y1="38" x2="150" y2="38" stroke="#ff003c" stroke-width="0.3" opacity="0.15"/>
        <image href="https://skillicons.dev/icons?i=git&amp;theme=dark" x="35" y="50" width="40" height="40"/>
        <image href="https://skillicons.dev/icons?i=github&amp;theme=dark" x="80" y="50" width="40" height="40"/>
        <image href="https://skillicons.dev/icons?i=vscode&amp;theme=dark" x="125" y="50" width="40" height="40"/>
        <image href="https://skillicons.dev/icons?i=bash&amp;theme=dark" x="35" y="95" width="40" height="40"/>
        <image href="https://skillicons.dev/icons?i=docker&amp;theme=dark" x="80" y="95" width="40" height="40"/>
        <image href="https://skillicons.dev/icons?i=postman&amp;theme=dark" x="125" y="95" width="40" height="40"/>
      </svg>
    </td>
    <td width="25%" align="center" valign="top">
      <svg viewBox="0 0 195 160" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:195px;">
        <rect x="2" y="2" width="191" height="156" rx="12" fill="#050505" stroke="#ff003c" stroke-width="0.8" stroke-opacity="0.15"/>
        <line x1="10" y1="2" x2="185" y2="2" stroke="#ff003c" stroke-width="1.5" opacity="0.3"/>
        <text x="98" y="30" text-anchor="middle" fill="#ffffff" font-family="monospace" font-size="11" font-weight="bold" opacity="0.8">AI &amp; DEVOPS</text>
        <line x1="30" y1="38" x2="165" y2="38" stroke="#ff003c" stroke-width="0.3" opacity="0.15"/>
        <image href="https://skillicons.dev/icons?i=tensorflow&amp;theme=dark" x="35" y="50" width="40" height="40"/>
        <image href="https://skillicons.dev/icons?i=pytorch&amp;theme=dark" x="80" y="50" width="40" height="40"/>
        <image href="https://skillicons.dev/icons?i=opencv&amp;theme=dark" x="125" y="50" width="40" height="40"/>
        <image href="https://skillicons.dev/icons?i=linux&amp;theme=dark" x="35" y="95" width="40" height="40"/>
        <image href="https://skillicons.dev/icons?i=nginx&amp;theme=dark" x="80" y="95" width="40" height="40"/>
        <image href="https://skillicons.dev/icons?i=heroku&amp;theme=dark" x="125" y="95" width="40" height="40"/>
      </svg>
    </td>
  </tr>
</table>

</div>

<br/>
<div align="center">

<svg viewBox="0 0 860 50" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:860px;">
  <defs>
    <linearGradient id="labelLine2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#ff003c" stop-opacity="0"/>
      <stop offset="15%" stop-color="#ff003c" stop-opacity="0.4"/>
      <stop offset="50%" stop-color="#ff003c" stop-opacity="0.8"/>
      <stop offset="85%" stop-color="#ff003c" stop-opacity="0.4"/>
      <stop offset="100%" stop-color="#ff003c" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <line x1="0" y1="25" x2="860" y2="25" stroke="url(#labelLine2)" stroke-width="0.8"/>
  <text x="430" y="29" text-anchor="middle" fill="#ff003c" font-family="monospace" font-size="11" opacity="0.7" letter-spacing="6">GITHUB ANALYTICS</text>
</svg>

<br/>

<table>
  <tr>
    <td align="center" width="50%">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=Solveran601&amp;show_icons=true&amp;theme=dark&amp;hide_border=true&amp;count_private=true&amp;bg_color=0d1117&amp;title_color=ff003c&amp;icon_color=ff003c&amp;text_color=ffffff&amp;border_color=1a1a1a&amp;ring_color=ff003c&amp;rank_icon=default&amp;card_width=400"/>
        <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=Solveran601&amp;show_icons=true&amp;theme=light&amp;hide_border=true&amp;count_private=true&amp;bg_color=ffffff&amp;title_color=ff003c&amp;icon_color=ff003c&amp;text_color=333333&amp;border_color=e0e0e0&amp;ring_color=ff003c&amp;rank_icon=default&amp;card_width=400"/>
        <img src="https://github-readme-stats.vercel.app/api?username=Solveran601&amp;show_icons=true&amp;theme=dark&amp;hide_border=true&amp;count_private=true&amp;bg_color=0d1117&amp;title_color=ff003c&amp;icon_color=ff003c&amp;text_color=ffffff&amp;border_color=1a1a1a&amp;ring_color=ff003c&amp;rank_icon=default&amp;card_width=400" width="95%"/>
      </picture>
    </td>
    <td align="center" width="50%">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Solveran601&amp;layout=compact&amp;theme=dark&amp;hide_border=true&amp;bg_color=0d1117&amp;title_color=ff003c&amp;text_color=ffffff&amp;border_color=1a1a1a&amp;card_width=400"/>
        <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Solveran601&amp;layout=compact&amp;theme=light&amp;hide_border=true&amp;bg_color=ffffff&amp;title_color=ff003c&amp;text_color=333333&amp;border_color=e0e0e0&amp;card_width=400"/>
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Solveran601&amp;layout=compact&amp;theme=dark&amp;hide_border=true&amp;bg_color=0d1117&amp;title_color=ff003c&amp;text_color=ffffff&amp;border_color=1a1a1a&amp;card_width=400" width="95%"/>
      </picture>
    </td>
  </tr>
</table>

<br/>

<table>
  <tr>
    <td align="center" width="50%">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=Solveran601&amp;theme=dark&amp;background=0d1117&amp;ring=ff003c&amp;fire=ff003c&amp;currStreakLabel=ff003c&amp;sideLabels=ff003c&amp;currStreakNum=ffffff&amp;sideNums=ffffff&amp;dates=666666&amp;border=1a1a1a"/>
        <img src="https://streak-stats.demolab.com?user=Solveran601&amp;theme=dark&amp;background=0d1117&amp;ring=ff003c&amp;fire=ff003c&amp;currStreakLabel=ff003c&amp;sideLabels=ff003c&amp;currStreakNum=ffffff&amp;sideNums=ffffff&amp;dates=666666&amp;border=1a1a1a" width="95%"/>
      </picture>
    </td>
    <td align="center" width="50%">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=Solveran601&amp;bg_color=0d1117&amp;color=ff003c&amp;line=ff003c&amp;point=ffffff&amp;area=true&amp;area_color=ff003c20&amp;hide_border=true&amp;radius=12&amp;height=200"/>
        <img src="https://github-readme-activity-graph.vercel.app/graph?username=Solveran601&amp;bg_color=0d1117&amp;color=ff003c&amp;line=ff003c&amp;point=ffffff&amp;area=true&amp;area_color=ff003c20&amp;hide_border=true&amp;radius=12&amp;height=200" width="95%"/>
      </picture>
    </td>
  </tr>
</table>

<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-trophy.vercel.app/?username=Solveran601&amp;theme=dark&amp;no-frame=true&amp;no-bg=true&amp;column=7&amp;margin-w=15&amp;margin-h=15&amp;title_color=ff003c"/>
  <img src="https://github-profile-trophy.vercel.app/?username=Solveran601&amp;theme=dark&amp;no-frame=true&amp;no-bg=true&amp;column=7&amp;margin-w=15&amp;margin-h=15&amp;title_color=ff003c" width="100%"/>
</picture>

</div>

<br/>
<div align="center">

<svg viewBox="0 0 860 50" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:860px;">
  <defs>
    <linearGradient id="labelLine3" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#ff003c" stop-opacity="0"/>
      <stop offset="15%" stop-color="#ff003c" stop-opacity="0.4"/>
      <stop offset="50%" stop-color="#ff003c" stop-opacity="0.8"/>
      <stop offset="85%" stop-color="#ff003c" stop-opacity="0.4"/>
      <stop offset="100%" stop-color="#ff003c" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <line x1="0" y1="25" x2="860" y2="25" stroke="url(#labelLine3)" stroke-width="0.8"/>
  <text x="430" y="29" text-anchor="middle" fill="#ff003c" font-family="monospace" font-size="11" opacity="0.7" letter-spacing="6">CONTRIBUTIONS</text>
</svg>

<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake.svg"/>
  <img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" width="100%"/>
</picture>

</div>

<br/>
<div align="center">

<svg viewBox="0 0 860 70" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:860px;">
  <defs>
    <filter id="glassFooter">
      <feGaussianBlur in="SourceAlpha" stdDeviation="3" result="blur"/>
      <feOffset dx="0" dy="0" result="offsetBlur"/>
      <feFlood flood-color="#ff003c" flood-opacity="0.05" result="color"/>
      <feComposite in="color" in2="offsetBlur" operator="in" result="shadow"/>
      <feMerge><feMergeNode in="shadow"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>
  <rect x="2" y="2" width="856" height="66" rx="12" fill="#050505" stroke="#ff003c" stroke-width="0.8" stroke-opacity="0.12" filter="url(#glassFooter)"/>
  <line x1="20" y1="2" x2="840" y2="2" stroke="#ff003c" stroke-width="1" opacity="0.3"/>
  <text x="60" y="40" fill="#ffffff" font-family="monospace" font-size="13" font-weight="bold" opacity="0.7">VISITORS</text>
  <text x="60" y="55" fill="#666666" font-family="monospace" font-size="9" opacity="0.5">PROFILE TRACKER</text>
  <image href="https://api.visitorbadge.io/api/visitors?path=Solveran601%2FSolveran601&amp;countColor=%23ff003c&amp;style=flat&amp;label=&amp;labelColor=%23000000" x="720" y="18" width="130" height="35"/>
</svg>

<br/><br/>

<svg viewBox="0 0 860 60" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:860px;">
  <rect x="2" y="2" width="856" height="56" rx="12" fill="#050505" stroke="#ff003c" stroke-width="0.8" stroke-opacity="0.1"/>
  <text x="430" y="22" text-anchor="middle" fill="#666666" font-family="monospace" font-size="9" opacity="0.5" letter-spacing="4">CONNECT</text>
  <a href="https://github.com/Solveran601" target="_blank">
    <rect x="290" y="28" width="120" height="22" rx="4" fill="none" stroke="#ff003c" stroke-width="0.5" stroke-opacity="0.3"/>
    <text x="350" y="43" text-anchor="middle" fill="#ffffff" font-family="monospace" font-size="10" opacity="0.7">github.com/Solveran601</text>
  </a>
  <text x="430" y="52" text-anchor="middle" fill="#333333" font-family="monospace" font-size="8" opacity="0.4">NEURAL INTERFACE v2.0 // ALL SYSTEMS OPERATIONAL</text>
</svg>

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&amp;color=0:ff003c,40:111111,70:0a0a0a,100:000000&amp;height=200&amp;section=footer&amp;text=%3E+thanks+for+connecting&amp;fontSize=22&amp;fontColor=ffffff&amp;fontAlignY=60&amp;desc=SOLVERAN+||+BUILDING+THE+FUTURE&amp;descSize=12&amp;descAlignY=80&amp;descColor=bbbbbb&amp;animation=fadeIn" width="100%"/>

</div>

<!-- 
пїЅ==============================================================================пїЅ
пїЅ  END OF PROFILE                                                            пїЅ
пїЅ  --------------------------------                                          пїЅ
пїЅ  Design System: Cyberpunk Neural Interface                                 пїЅ
пїЅ  Palette: #000000, #0d1117, #ff003c, #ffffff, #bbbbbb                     пїЅ
пїЅ  Signature: NORD // SOLVERAN                                               пїЅ
L==============================================================================-
-->
