<div align="center">

<!-- SYSTEM BOOT SEQUENCE -->
<svg viewBox="0 0 900 340" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:900px;display:block;margin:0 auto;">
<defs>
<filter id="gRed"><feGaussianBlur stdDeviation="3" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
<filter id="gInt"><feGaussianBlur stdDeviation="6" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
<filter id="gSft"><feGaussianBlur stdDeviation="2" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
<radialGradient id="cGlow" cx="50%" cy="50%" r="50%">
<stop offset="0%" stop-color="#ff003c" stop-opacity="1"/>
<stop offset="40%" stop-color="#ff1744" stop-opacity="0.6"/>
<stop offset="100%" stop-color="#ff003c" stop-opacity="0"/>
</radialGradient>
<pattern id="dotGrid" width="30" height="30" patternUnits="userSpaceOnUse">
<circle cx="15" cy="15" r="0.6" fill="#ff003c" opacity="0.06"/>
</pattern>
</defs>
<style>
@keyframes bootText{0%,10%{opacity:0}12%,100%{opacity:1}}
@keyframes bootText2{0%,25%{opacity:0}27%,100%{opacity:1}}
@keyframes bootText3{0%,45%{opacity:0}47%,100%{opacity:1}}
@keyframes bootText4{0%,65%{opacity:0}67%,100%{opacity:1}}
@keyframes bootText5{0%,82%{opacity:0}84%,100%{opacity:1}}
@keyframes progressFill{0%{width:0}30%{width:15}60%{width:38}80%{width:62}90%{width:84}100%{width:100}}
@keyframes barGlow{0%,100%{opacity:0.3}50%{opacity:0.8}}
@keyframes blink{0%,100%{opacity:1}50%{opacity:0}}
@keyframes spinCog{from{transform:rotate(0deg)}to{transform:rotate(360deg)}}
@keyframes spinCog2{from{transform:rotate(360deg)}to{transform:rotate(0deg)}}
@keyframes flicker{0%,100%{opacity:1}50%{opacity:0.3}53%{opacity:1}56%{opacity:0.2}60%{opacity:1}}
@keyframes scanDown{0%{transform:translateY(-340px)}100%{transform:translateY(680px)}}
@keyframes readyFlash{0%,100%{opacity:0}95%{opacity:0}96%,98%{opacity:1}99%{opacity:0}}
@keyframes dropChar{0%{transform:translateY(-30px);opacity:0}20%{opacity:0.8}80%{opacity:0.3}100%{transform:translateY(30px);opacity:0}}
.flick{animation:flicker 4s ease-in-out infinite}
.scan{animation:scanDown 5s linear infinite}
.cog{animation:spinCog 6s linear infinite;transform-origin:60px 60px}
.cog2{animation:spinCog2 8s linear infinite;transform-origin:145px 75px}
.cog3{animation:spinCog 10s linear infinite;transform-origin:105px 130px}
</style>

<rect width="900" height="340" fill="url(#dotGrid)"/>
<rect x="0" y="0" width="900" height="2" fill="#ff003c" opacity="0.15" class="scan" filter="url(#gRed)"/>

<!-- Matrix Rain -->
<g opacity="0.08">
<text x="50" y="0" fill="#ff003c" font-family="monospace" font-size="8" class="flick">
<animate attributeName="y" from="-20" to="360" dur="7s" repeatCount="indefinite"/>
<animate attributeName="opacity" values="0;0.3;0.5;0.2;0" dur="7s" repeatCount="indefinite"/>
11010</text>
<text x="120" y="0" fill="#ff003c" font-family="monospace" font-size="7">
<animate attributeName="y" from="-40" to="360" dur="9s" repeatCount="indefinite" begin="2s"/>
<animate attributeName="opacity" values="0;0.2;0.4;0.1;0" dur="9s" repeatCount="indefinite" begin="2s"/>
01101</text>
<text x="200" y="0" fill="#ff003c" font-family="monospace" font-size="9">
<animate attributeName="y" from="-60" to="360" dur="11s" repeatCount="indefinite" begin="1s"/>
<animate attributeName="opacity" values="0;0.15;0.3;0.1;0" dur="11s" repeatCount="indefinite" begin="1s"/>
10110</text>
<text x="320" y="0" fill="#ff003c" font-family="monospace" font-size="8">
<animate attributeName="y" from="-30" to="360" dur="8s" repeatCount="indefinite" begin="3s"/>
<animate attributeName="opacity" values="0;0.2;0.35;0.1;0" dur="8s" repeatCount="indefinite" begin="3s"/>
01011</text>
<text x="450" y="0" fill="#ff003c" font-family="monospace" font-size="7">
<animate attributeName="y" from="-50" to="360" dur="12s" repeatCount="indefinite" begin="0.5s"/>
<animate attributeName="opacity" values="0;0.15;0.25;0.1;0" dur="12s" repeatCount="indefinite" begin="0.5s"/>
00110</text>
<text x="580" y="0" fill="#ff003c" font-family="monospace" font-size="9">
<animate attributeName="y" from="-20" to="360" dur="6s" repeatCount="indefinite" begin="1.5s"/>
<animate attributeName="opacity" values="0;0.2;0.4;0.1;0" dur="6s" repeatCount="indefinite" begin="1.5s"/>
11010</text>
<text x="700" y="0" fill="#ff003c" font-family="monospace" font-size="8">
<animate attributeName="y" from="-70" to="360" dur="10s" repeatCount="indefinite" begin="2.5s"/>
<animate attributeName="opacity" values="0;0.15;0.3;0.1;0" dur="10s" repeatCount="indefinite" begin="2.5s"/>
01101</text>
<text x="820" y="0" fill="#ff003c" font-family="monospace" font-size="7">
<animate attributeName="y" from="-40" to="360" dur="8.5s" repeatCount="indefinite" begin="4s"/>
<animate attributeName="opacity" values="0;0.2;0.35;0.1;0" dur="8.5s" repeatCount="indefinite" begin="4s"/>
10101</text>
</g>

<!-- Corner Frame -->
<path d="M 25 20 L 25 50 L 15 50" fill="none" stroke="#ff003c" stroke-width="2" opacity="0.35" filter="url(#gRed)"/>
<path d="M 875 20 L 875 50 L 885 50" fill="none" stroke="#ff003c" stroke-width="2" opacity="0.35" filter="url(#gRed)"/>
<path d="M 25 320 L 25 290 L 15 290" fill="none" stroke="#ff003c" stroke-width="2" opacity="0.35" filter="url(#gRed)"/>
<path d="M 875 320 L 875 290 L 885 290" fill="none" stroke="#ff003c" stroke-width="2" opacity="0.35" filter="url(#gRed)"/>

<!-- Gears Section -->
<g transform="translate(60,55)">
<g class="cog">
<circle cx="0" cy="0" r="18" fill="none" stroke="#ff003c" stroke-width="2" opacity="0.35"/>
<circle cx="0" cy="0" r="12" fill="none" stroke="#ff003c" stroke-width="1" opacity="0.2"/>
<circle cx="0" cy="0" r="4" fill="#ff003c" opacity="0.3" filter="url(#gRed)"/>
<line x1="0" y1="-20" x2="0" y2="-14" stroke="#ff003c" stroke-width="2.5" opacity="0.3"/>
<line x1="0" y1="14" x2="0" y2="20" stroke="#ff003c" stroke-width="2.5" opacity="0.3"/>
<line x1="-20" y1="0" x2="-14" y2="0" stroke="#ff003c" stroke-width="2.5" opacity="0.3"/>
<line x1="14" y1="0" x2="20" y2="0" stroke="#ff003c" stroke-width="2.5" opacity="0.3"/>
<line x1="-14" y1="-14" x2="-10" y2="-10" stroke="#ff003c" stroke-width="2" opacity="0.25"/>
<line x1="10" y1="10" x2="14" y2="14" stroke="#ff003c" stroke-width="2" opacity="0.25"/>
<line x1="-14" y1="14" x2="-10" y2="10" stroke="#ff003c" stroke-width="2" opacity="0.25"/>
<line x1="10" y1="-10" x2="14" y2="-14" stroke="#ff003c" stroke-width="2" opacity="0.25"/>
</g>
</g>

<g transform="translate(145,70)">
<g class="cog2">
<circle cx="0" cy="0" r="14" fill="none" stroke="#ff003c" stroke-width="1.5" opacity="0.3"/>
<circle cx="0" cy="0" r="9" fill="none" stroke="#ff003c" stroke-width="0.8" opacity="0.15"/>
<circle cx="0" cy="0" r="3" fill="#ff003c" opacity="0.25"/>
<line x1="0" y1="-16" x2="0" y2="-11" stroke="#ff003c" stroke-width="2" opacity="0.25"/>
<line x1="0" y1="11" x2="0" y2="16" stroke="#ff003c" stroke-width="2" opacity="0.25"/>
<line x1="-16" y1="0" x2="-11" y2="0" stroke="#ff003c" stroke-width="2" opacity="0.25"/>
<line x1="11" y1="0" x2="16" y2="0" stroke="#ff003c" stroke-width="2" opacity="0.25"/>
</g>
</g>

<g transform="translate(105,130)">
<g class="cog3">
<circle cx="0" cy="0" r="20" fill="none" stroke="#ff003c" stroke-width="1.5" opacity="0.2"/>
<circle cx="0" cy="0" r="14" fill="none" stroke="#ff003c" stroke-width="0.8" opacity="0.12"/>
<circle cx="0" cy="0" r="4" fill="#ff003c" opacity="0.2" filter="url(#gSft)"/>
<line x1="0" y1="-22" x2="0" y2="-16" stroke="#ff003c" stroke-width="2" opacity="0.2"/>
<line x1="0" y1="16" x2="0" y2="22" stroke="#ff003c" stroke-width="2" opacity="0.2"/>
<line x1="-22" y1="0" x2="-16" y2="0" stroke="#ff003c" stroke-width="2" opacity="0.2"/>
<line x1="16" y1="0" x2="22" y2="0" stroke="#ff003c" stroke-width="2" opacity="0.2"/>
</g>
</g>

<!-- Boot Sequence Text -->
<g font-family="monospace" font-size="13" fill="#bbbbbb">
<text x="200" y="70" fill="#ff003c" font-weight="bold" font-size="15" opacity="0.9" filter="url(#gRed)">SYSTEM v2.0</text>
<text x="200" y="95" class="bootText" opacity="0.6">> initializing kernel...</text>
<text x="200" y="118" class="bootText2" opacity="0.6">> loading neural core modules</text>
<text x="200" y="141" class="bootText3" opacity="0.6">> establishing secure channel</text>
<text x="200" y="164" class="bootText4" opacity="0.6">> calibrating system interfaces</text>
<text x="200" y="187" class="bootText5" opacity="0.6">> finalizing startup sequence</text>
</g>

<!-- Progress Bar -->
<rect x="200" y="210" width="500" height="8" rx="4" fill="#0a0a0a" stroke="#ff003c" stroke-width="0.5" opacity="0.3"/>
<rect x="200" y="210" width="0" height="8" rx="4" fill="#ff003c" opacity="0.7" filter="url(#gRed)">
<animate attributeName="width" from="0" to="500" dur="5s" repeatCount="indefinite"/>
</rect>
<rect x="200" y="210" width="500" height="8" rx="4" fill="none" stroke="#ff003c" stroke-width="1" opacity="0.15"/>

<!-- Percentage -->
<text x="715" y="218" fill="#ff003c" font-family="monospace" font-size="10" opacity="0">100%
<animate attributeName="opacity" values="0;0;0;0;0;0.6" dur="5s" repeatCount="indefinite"/></text>

<!-- Loading -->
<text x="200" y="245" fill="#666666" font-family="monospace" font-size="10" opacity="0.4">status .............</text>

<!-- Ready Flash -->
<rect x="0" y="0" width="900" height="340" fill="#ff003c" opacity="0" class="readyFlash" filter="url(#gInt)">
<animate attributeName="opacity" values="0;0;0.15;0;0" dur="5s" repeatCount="indefinite" begin="4.5s"/>
</rect>

<!-- System Ready Text -->
<text x="450" y="300" text-anchor="middle" fill="#ff003c" font-family="monospace" font-size="22" font-weight="bold" opacity="0" filter="url(#gRed)">
<animate attributeName="opacity" values="0;0;0.95" dur="5.5s" repeatCount="indefinite"/>
SYSTEM READY</text>

<text x="450" y="325" text-anchor="middle" fill="#666666" font-family="monospace" font-size="10" opacity="0">
<animate attributeName="opacity" values="0;0;0.4" dur="5.5s" repeatCount="indefinite"/>
node :: active &gt; all systems operational</text>

<!-- Blinking cursor after ready -->
<text x="565" y="300" fill="#ff003c" font-family="monospace" font-size="22" opacity="0" filter="url(#gRed)">
<animate attributeName="opacity" values="0;0;0;1;0;1;0;1" dur="5.5s" repeatCount="indefinite"/>
_</text>

<!-- Boot time -->
<text x="780" y="325" fill="#333333" font-family="monospace" font-size="8" opacity="0.3">boot: 4.7s</text>
</svg>

</div>

<br/>
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&amp;color=0:000000,30:050505,60:0a0a0a,100:ff003c&amp;height=250&amp;section=header&amp;text=SOLVERAN&amp;fontSize=65&amp;fontColor=ff003c&amp;fontAlignY=30&amp;desc=%3E+system+v2.0+online&amp;descSize=15&amp;descAlignY=52&amp;descColor=aaaaaa&amp;animation=fadeIn" width="100%"/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&amp;weight=600&amp;size=20&amp;duration=2200&amp;pause=900&amp;color=FF003C&amp;center=true&amp;vCenter=true&amp;multiline=true&amp;repeat=true&amp;width=700&amp;height=90&amp;lines=%3E+neural+core+loaded;%3E+system+ready;%3E+deploy+mission;%3E+build+the+future" width="100%"/>

</div>

<!-- WELCOME BANNER -->
<div align="center">
<svg viewBox="0 0 900 140" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:900px;">
<defs>
<filter id="gw"><feGaussianBlur stdDeviation="4" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
<filter id="gw2"><feGaussianBlur stdDeviation="8" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
<filter id="gwc"><feGaussianBlur in="SourceAlpha" stdDeviation="3" result="b"/><feOffset dx="0" dy="0" result="o"/><feFlood flood-color="#ff003c" flood-opacity="0.06" result="c"/><feComposite in="c" in2="o" operator="in" result="s"/><feMerge><feMergeNode in="s"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
<linearGradient id="ww" x1="0%" y1="0%" x2="100%" y2="0%">
<stop offset="0%" stop-color="#ff003c" stop-opacity="0"/>
<stop offset="50%" stop-color="#ff003c" stop-opacity="0.8"/>
<stop offset="100%" stop-color="#ff003c" stop-opacity="0"/>
</linearGradient>
<radialGradient id="wg" cx="50%" cy="50%" r="50%">
<stop offset="0%" stop-color="#ff003c" stop-opacity="0.12"/>
<stop offset="100%" stop-color="#ff003c" stop-opacity="0"/>
</radialGradient>
</defs>
<rect x="2" y="2" width="896" height="136" rx="18" fill="#050505" stroke="#ff003c" stroke-width="0.8" stroke-opacity="0.1" filter="url(#gwc)"/>
<rect x="300" y="10" width="300" height="120" rx="60" fill="url(#wg)" filter="url(#gw2)"/>
<line x1="20" y1="2" x2="880" y2="2" stroke="#ff003c" stroke-width="1.5" opacity="0.3" filter="url(#gw)"/>
<text x="450" y="52" text-anchor="middle" fill="#777777" font-family="monospace" font-size="11" opacity="0.5" letter-spacing="4">Р”РћР‘Р Рћ РџРћР–РђР›РћР’РђРўР¬ Р’ РџР РћР¤РР›Р¬</text>
<text x="450" y="100" text-anchor="middle" fill="#ff003c" font-family="monospace" font-size="42" font-weight="bold" opacity="0.95" filter="url(#gw)" letter-spacing="3">
SOLVERAN
<animate attributeName="opacity" values="0.95;0.7;0.95" dur="3s" repeatCount="indefinite"/>
</text>
<line x1="300" y1="112" x2="600" y2="112" stroke="url(#ww)" stroke-width="1.5" filter="url(#gw)">
<animate attributeName="opacity" values="0.8;0.3;0.8" dur="2.5s" repeatCount="indefinite"/>
</line>
<circle cx="280" cy="98" r="2" fill="#ff003c" opacity="0.4">
<animate attributeName="opacity" values="0.4;0.1;0.4" dur="2s" repeatCount="indefinite"/>
</circle>
<circle cx="620" cy="98" r="2" fill="#ff003c" opacity="0.4">
<animate attributeName="opacity" values="0.4;0.1;0.4" dur="2s" repeatCount="indefinite" begin="1s"/>
</circle>
<path d="M 15 20 L 15 50 L 25 50" fill="none" stroke="#ff003c" stroke-width="1.2" opacity="0.2" filter="url(#gw)"/>
<path d="M 885 20 L 885 50 L 875 50" fill="none" stroke="#ff003c" stroke-width="1.2" opacity="0.2" filter="url(#gw)"/>
<path d="M 15 120 L 15 90 L 25 90" fill="none" stroke="#ff003c" stroke-width="1.2" opacity="0.2" filter="url(#gw)"/>
<path d="M 885 120 L 885 90 L 875 90" fill="none" stroke="#ff003c" stroke-width="1.2" opacity="0.2" filter="url(#gw)"/>
</svg>
</div>

<br/>
<!-- NEURAL CORE SCENE -->
<svg viewBox="0 0 900 280" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:900px;display:block;margin:0 auto;">
<defs>
<filter id="gr"><feGaussianBlur stdDeviation="3" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
<filter id="gi"><feGaussianBlur stdDeviation="6" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
<filter id="gs"><feGaussianBlur stdDeviation="2" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
<radialGradient id="ng" cx="50%" cy="50%" r="50%">
<stop offset="0%" stop-color="#ff003c" stop-opacity="0.8"/>
<stop offset="60%" stop-color="#ff003c" stop-opacity="0.2"/>
<stop offset="100%" stop-color="#ff003c" stop-opacity="0"/>
</radialGradient>
<radialGradient id="cg" cx="50%" cy="50%" r="50%">
<stop offset="0%" stop-color="#ff003c" stop-opacity="1"/>
<stop offset="30%" stop-color="#ff1744" stop-opacity="0.7"/>
<stop offset="100%" stop-color="#ff003c" stop-opacity="0"/>
</radialGradient>
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
.p{animation:pn 2s ease-in-out infinite}
.pc{animation:pc 2.5s ease-in-out infinite}
.pr{animation:pr 3s ease-in-out infinite}
.fp{animation:fp 4s ease-in-out infinite}
.fp2{animation:fp2 5s ease-in-out infinite}
.d{animation:dm 3s linear infinite}
.d2{animation:dm2 4s linear infinite}
.rt{animation:rs 8s linear infinite;transform-origin:450px 140px}
.rr{animation:rr 12s linear infinite;transform-origin:450px 140px}
.fk{animation:fk 5s ease-in-out infinite}
.sl{animation:sl 4s linear infinite}
</style>
<pattern id="grd" width="35" height="35" patternUnits="userSpaceOnUse">
<circle cx="17.5" cy="17.5" r="0.7" fill="#ff003c" opacity="0.07"/>
</pattern>
<rect width="900" height="280" fill="url(#grd)"/>
<rect x="0" y="0" width="900" height="2" fill="#ff003c" opacity="0.2" class="sl" filter="url(#gr)"/>

<!-- Corner brackets -->
<path d="M 30 15 L 30 45 L 20 45" fill="none" stroke="#ff003c" stroke-width="1.5" opacity="0.25" filter="url(#gs)"/>
<path d="M 870 15 L 870 45 L 880 45" fill="none" stroke="#ff003c" stroke-width="1.5" opacity="0.25" filter="url(#gs)"/>
<path d="M 30 265 L 30 235 L 20 235" fill="none" stroke="#ff003c" stroke-width="1.5" opacity="0.25" filter="url(#gs)"/>
<path d="M 870 265 L 870 235 L 880 235" fill="none" stroke="#ff003c" stroke-width="1.5" opacity="0.25" filter="url(#gs)"/>
<line x1="40" y1="15" x2="100" y2="15" stroke="#ff003c" stroke-width="0.3" opacity="0.1"/>
<line x1="800" y1="15" x2="860" y2="15" stroke="#ff003c" stroke-width="0.3" opacity="0.1"/>
<line x1="40" y1="265" x2="100" y2="265" stroke="#ff003c" stroke-width="0.3" opacity="0.1"/>
<line x1="800" y1="265" x2="860" y2="265" stroke="#ff003c" stroke-width="0.3" opacity="0.1"/>
<text x="35" y="255" fill="#ff003c" font-family="monospace" font-size="8" opacity="0.3"></text>
<text x="790" y="255" fill="#ff003c" font-family="monospace" font-size="8" opacity="0.3"></text>
<circle cx="25" cy="252" r="1.5" fill="#ff003c" opacity="0.5" filter="url(#gs)" class="fk"/>
<circle cx="783" cy="252" r="1.5" fill="#ff003c" opacity="0.5" filter="url(#gs)" class="fk" style="animation-delay:0.7s"/>
<!-- Connections -->
<line x1="450" y1="140" x2="340" y2="80" stroke="#ff003c" stroke-width="0.7" opacity="0.35" class="d" stroke-dasharray="3 7"/>
<line x1="450" y1="140" x2="560" y2="80" stroke="#ff003c" stroke-width="0.7" opacity="0.35" class="d2" stroke-dasharray="4 6"/>
<line x1="450" y1="140" x2="340" y2="200" stroke="#ff003c" stroke-width="0.7" opacity="0.25" class="d2" stroke-dasharray="3 8"/>
<line x1="450" y1="140" x2="560" y2="200" stroke="#ff003c" stroke-width="0.7" opacity="0.25" class="d" stroke-dasharray="5 5"/>
<line x1="450" y1="140" x2="290" y2="140" stroke="#ff003c" stroke-width="0.5" opacity="0.2" class="d2" stroke-dasharray="2 9"/>
<line x1="450" y1="140" x2="610" y2="140" stroke="#ff003c" stroke-width="0.5" opacity="0.2" class="d" stroke-dasharray="3 8"/>
<line x1="450" y1="140" x2="450" y2="50" stroke="#ff003c" stroke-width="0.5" opacity="0.18" stroke-dasharray="4 7">
<animate attributeName="stroke-dashoffset" from="0" to="-100" dur="3.5s" repeatCount="indefinite"/>
</line>
<line x1="450" y1="140" x2="450" y2="230" stroke="#ff003c" stroke-width="0.5" opacity="0.18" stroke-dasharray="4 7">
<animate attributeName="stroke-dashoffset" from="0" to="100" dur="3.5s" repeatCount="indefinite"/>
</line>

<!-- Outer connections -->
<line x1="340" y1="80" x2="240" y2="50" stroke="#ff003c" stroke-width="0.4" opacity="0.15" stroke-dasharray="2 8">
<animate attributeName="stroke-dashoffset" from="0" to="-80" dur="3s" repeatCount="indefinite"/>
</line>
<line x1="560" y1="80" x2="660" y2="50" stroke="#ff003c" stroke-width="0.4" opacity="0.15" stroke-dasharray="2 8">
<animate attributeName="stroke-dashoffset" from="0" to="80" dur="3.5s" repeatCount="indefinite"/>
</line>
<line x1="340" y1="200" x2="240" y2="230" stroke="#ff003c" stroke-width="0.4" opacity="0.15" stroke-dasharray="2 8">
<animate attributeName="stroke-dashoffset" from="0" to="80" dur="3.2s" repeatCount="indefinite"/>
</line>
<line x1="560" y1="200" x2="660" y2="230" stroke="#ff003c" stroke-width="0.4" opacity="0.15" stroke-dasharray="2 8">
<animate attributeName="stroke-dashoffset" from="0" to="-80" dur="3.7s" repeatCount="indefinite"/>
</line>
<line x1="290" y1="140" x2="240" y2="50" stroke="#ff003c" stroke-width="0.35" opacity="0.1" stroke-dasharray="2 10">
<animate attributeName="stroke-dashoffset" from="0" to="100" dur="4s" repeatCount="indefinite"/>
</line>
<line x1="610" y1="140" x2="660" y2="50" stroke="#ff003c" stroke-width="0.35" opacity="0.1" stroke-dasharray="2 10">
<animate attributeName="stroke-dashoffset" from="0" to="-100" dur="4s" repeatCount="indefinite"/>
</line>
<line x1="290" y1="140" x2="240" y2="230" stroke="#ff003c" stroke-width="0.35" opacity="0.1" stroke-dasharray="2 10">
<animate attributeName="stroke-dashoffset" from="0" to="-100" dur="4.5s" repeatCount="indefinite"/>
</line>
<line x1="610" y1="140" x2="660" y2="230" stroke="#ff003c" stroke-width="0.35" opacity="0.1" stroke-dasharray="2 10">
<animate attributeName="stroke-dashoffset" from="0" to="100" dur="4.5s" repeatCount="indefinite"/>
</line>

<!-- Far connections -->
<line x1="240" y1="50" x2="170" y2="35" stroke="#ff003c" stroke-width="0.3" opacity="0.08" stroke-dasharray="2 12">
<animate attributeName="stroke-dashoffset" from="0" to="-70" dur="5s" repeatCount="indefinite"/>
</line>
<line x1="660" y1="50" x2="730" y2="35" stroke="#ff003c" stroke-width="0.3" opacity="0.08" stroke-dasharray="2 12">
<animate attributeName="stroke-dashoffset" from="0" to="70" dur="5s" repeatCount="indefinite"/>
</line>
<line x1="240" y1="230" x2="170" y2="245" stroke="#ff003c" stroke-width="0.3" opacity="0.08" stroke-dasharray="2 12">
<animate attributeName="stroke-dashoffset" from="0" to="70" dur="5.5s" repeatCount="indefinite"/>
</line>
<line x1="660" y1="230" x2="730" y2="245" stroke="#ff003c" stroke-width="0.3" opacity="0.08" stroke-dasharray="2 12">
<animate attributeName="stroke-dashoffset" from="0" to="-70" dur="5.5s" repeatCount="indefinite"/>
</line>

<!-- Energy rings -->
<g class="rt"><ellipse cx="450" cy="140" rx="80" ry="25" fill="none" stroke="#ff003c" stroke-width="0.5" opacity="0.18" filter="url(#gs)"/></g>
<g class="rr"><ellipse cx="450" cy="140" rx="100" ry="30" fill="none" stroke="#ff003c" stroke-width="0.35" opacity="0.12" filter="url(#gs)"/></g>

<!-- Central AI Core -->
<circle cx="450" cy="140" r="25" fill="url(#cg)" filter="url(#gi)"/>
<circle cx="450" cy="140" r="7" fill="#ff003c" filter="url(#gi)" class="pc"/>
<circle cx="450" cy="140" r="11" fill="none" stroke="#ff003c" stroke-width="0.8" opacity="0.5" class="pr" filter="url(#gr)"/>
<circle cx="450" cy="140" r="35" fill="none" stroke="#ff003c" stroke-width="0.4" opacity="0.15" class="pr" filter="url(#gr)"/>
<text x="450" y="146" text-anchor="middle" fill="#ffffff" font-family="monospace" font-size="9" font-weight="bold" opacity="0.85" filter="url(#gs)"></text>

<!-- Core nodes layer 1 -->
<circle cx="340" cy="80" r="5" fill="url(#ng)" filter="url(#gr)"/><circle cx="340" cy="80" r="2" fill="#ffffff" class="p"/>
<circle cx="560" cy="80" r="5" fill="url(#ng)" filter="url(#gr)"/><circle cx="560" cy="80" r="2" fill="#ffffff" class="p" style="animation-delay:0.4s"/>
<circle cx="340" cy="200" r="5" fill="url(#ng)" filter="url(#gr)"/><circle cx="340" cy="200" r="2" fill="#ffffff" class="p" style="animation-delay:0.8s"/>
<circle cx="560" cy="200" r="5" fill="url(#ng)" filter="url(#gr)"/><circle cx="560" cy="200" r="2" fill="#ffffff" class="p" style="animation-delay:1.2s"/>

<!-- Core nodes layer 2 -->
<circle cx="290" cy="140" r="4" fill="url(#ng)" filter="url(#gs)"/><circle cx="290" cy="140" r="1.5" fill="#ffffff" class="p" style="animation-delay:0.2s"/>
<circle cx="610" cy="140" r="4" fill="url(#ng)" filter="url(#gs)"/><circle cx="610" cy="140" r="1.5" fill="#ffffff" class="p" style="animation-delay:0.6s"/>
<circle cx="450" cy="50" r="4" fill="url(#ng)" filter="url(#gs)"/><circle cx="450" cy="50" r="1.5" fill="#ffffff" class="p" style="animation-delay:0.3s"/>
<circle cx="450" cy="230" r="4" fill="url(#ng)" filter="url(#gs)"/><circle cx="450" cy="230" r="1.5" fill="#ffffff" class="p" style="animation-delay:0.9s"/>

<!-- Outer nodes -->
<circle cx="240" cy="50" r="3" fill="url(#ng)" filter="url(#gs)"/><circle cx="240" cy="50" r="1" fill="#ffffff" class="p" style="animation-delay:0.15s"/>
<circle cx="660" cy="50" r="3" fill="url(#ng)" filter="url(#gs)"/><circle cx="660" cy="50" r="1" fill="#ffffff" class="p" style="animation-delay:0.55s"/>
<circle cx="240" cy="230" r="3" fill="url(#ng)" filter="url(#gs)"/><circle cx="240" cy="230" r="1" fill="#ffffff" class="p" style="animation-delay:1.1s"/>
<circle cx="660" cy="230" r="3" fill="url(#ng)" filter="url(#gs)"/><circle cx="660" cy="230" r="1" fill="#ffffff" class="p" style="animation-delay:1.5s"/>

<!-- Far outer nodes -->
<circle cx="170" cy="35" r="2" fill="url(#ng)"/><circle cx="170" cy="35" r="0.8" fill="#ffffff"/>
<circle cx="730" cy="35" r="2" fill="url(#ng)"/><circle cx="730" cy="35" r="0.8" fill="#ffffff"/>
<circle cx="170" cy="245" r="2" fill="url(#ng)"/><circle cx="170" cy="245" r="0.8" fill="#ffffff"/>
<circle cx="730" cy="245" r="2" fill="url(#ng)"/><circle cx="730" cy="245" r="0.8" fill="#ffffff"/>
<circle cx="130" cy="90" r="1.5" fill="#ff003c" opacity="0.3"/>
<circle cx="770" cy="90" r="1.5" fill="#ff003c" opacity="0.3"/>
<circle cx="130" cy="190" r="1.5" fill="#ff003c" opacity="0.25"/>
<circle cx="770" cy="190" r="1.5" fill="#ff003c" opacity="0.25"/>

<!-- Particles -->
<circle cx="140" cy="180" r="1.2" fill="#ff003c" opacity="0.5" class="fp" filter="url(#gs)"/>
<circle cx="280" cy="240" r="0.8" fill="#ff003c" opacity="0.35" class="fp2" style="animation-delay:0.4s"/>
<circle cx="520" cy="260" r="1.2" fill="#ff003c" opacity="0.4" class="fp" style="animation-delay:0.9s"/>
<circle cx="680" cy="230" r="0.8" fill="#ff003c" opacity="0.3" class="fp2" style="animation-delay:1.3s"/>
<circle cx="760" cy="200" r="1.2" fill="#ff003c" opacity="0.25" class="fp" style="animation-delay:1.8s"/>
<circle cx="200" cy="120" r="0.8" fill="#ff003c" opacity="0.4" class="fp2" style="animation-delay:0.6s"/>
<circle cx="700" cy="160" r="0.8" fill="#ff003c" opacity="0.35" class="fp" style="animation-delay:1.1s"/>
<circle cx="380" cy="250" r="1" fill="#ff003c" opacity="0.4" class="fp2" style="animation-delay:2s"/>
<circle cx="70" cy="200" r="0.8" fill="#ff003c" opacity="0.25" class="fp" style="animation-delay:2.5s"/>
<circle cx="830" cy="130" r="0.8" fill="#ff003c" opacity="0.25" class="fp2" style="animation-delay:3s"/>
<circle cx="480" cy="240" r="1" fill="#ff003c" opacity="0.35" class="fp" style="animation-delay:0.2s"/>
<circle cx="90" cy="50" r="0.8" fill="#ff003c" opacity="0.2" class="fp2" style="animation-delay:1.6s"/>

<!-- Signal wave rings from core -->
<circle cx="450" cy="140" r="0" fill="none" stroke="#ff003c" stroke-width="1" opacity="0">
<animate attributeName="r" from="0" to="120" dur="3s" repeatCount="indefinite" begin="0s"/>
<animate attributeName="opacity" values="0.3;0" dur="3s" repeatCount="indefinite" begin="0s"/>
</circle>
<circle cx="450" cy="140" r="0" fill="none" stroke="#ff003c" stroke-width="0.8" opacity="0">
<animate attributeName="r" from="0" to="120" dur="3s" repeatCount="indefinite" begin="1s"/>
<animate attributeName="opacity" values="0.3;0" dur="3s" repeatCount="indefinite" begin="1s"/>
</circle>
<circle cx="450" cy="140" r="0" fill="none" stroke="#ff003c" stroke-width="0.6" opacity="0">
<animate attributeName="r" from="0" to="120" dur="3s" repeatCount="indefinite" begin="2s"/>
<animate attributeName="opacity" values="0.3;0" dur="3s" repeatCount="indefinite" begin="2s"/>
</circle>

<!-- Vertical energy pulse -->
<line x1="450" y1="140" x2="450" y2="50" stroke="#ff003c" stroke-width="1" opacity="0">
<animate attributeName="opacity" values="0;0.4;0" dur="2s" repeatCount="indefinite" begin="0.5s"/>
</line>
<line x1="450" y1="140" x2="450" y2="230" stroke="#ff003c" stroke-width="1" opacity="0">
<animate attributeName="opacity" values="0;0.4;0" dur="2s" repeatCount="indefinite" begin="1.5s"/>
</line>
<line x1="450" y1="140" x2="340" y2="80" stroke="#ff003c" stroke-width="0.8" opacity="0">
<animate attributeName="opacity" values="0;0.3;0" dur="2.5s" repeatCount="indefinite" begin="0.2s"/>
</line>
<line x1="450" y1="140" x2="560" y2="80" stroke="#ff003c" stroke-width="0.8" opacity="0">
<animate attributeName="opacity" values="0;0.3;0" dur="2.5s" repeatCount="indefinite" begin="1.2s"/>
</line>

</svg>

<br/>
<div align="center">

<svg viewBox="0 0 900 120" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:900px;">
<defs>
<filter id="g"><feGaussianBlur stdDeviation="3" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
<filter id="g2"><feGaussianBlur stdDeviation="6" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
<filter id="gc">
<feGaussianBlur in="SourceAlpha" stdDeviation="3" result="b"/>
<feOffset dx="0" dy="0" result="o"/>
<feFlood flood-color="#ff003c" flood-opacity="0.05" result="c"/>
<feComposite in="c" in2="o" operator="in" result="s"/>
<feMerge><feMergeNode in="s"/><feMergeNode in="SourceGraphic"/></feMerge>
</filter>
<linearGradient id="bar1" x1="0%" y1="0%" x2="100%" y2="0%">
<stop offset="0%" stop-color="#ff003c" stop-opacity="0.8"/>
<stop offset="100%" stop-color="#ff003c" stop-opacity="0.2"/>
</linearGradient>
</defs>
<style>
@keyframes fill1{0%{width:0}50%{width:78}100%{width:78}}
@keyframes fill2{0%{width:0}50%{width:45}100%{width:45}}
@keyframes fill3{0%{width:0}50%{width:92}100%{width:92}}
@keyframes fill4{0%{width:0}50%{width:63}100%{width:63}}
@keyframes pulseDot{0%,100%{opacity:1}50%{opacity:0.2}}
.f1{animation:fill1 4s ease-out forwards;animation-delay:0.5s}
.f2{animation:fill2 4s ease-out forwards;animation-delay:0.7s}
.f3{animation:fill3 4s ease-out forwards;animation-delay:0.9s}
.f4{animation:fill4 4s ease-out forwards;animation-delay:1.1s}
.pd{animation:pulseDot 1.5s ease-in-out infinite}
</style>

<rect x="2" y="2" width="896" height="116" rx="14" fill="#050505" stroke="#ff003c" stroke-width="0.8" stroke-opacity="0.12" filter="url(#gc)"/>
<line x1="20" y1="2" x2="880" y2="2" stroke="#ff003c" stroke-width="1.2" opacity="0.3" filter="url(#g)">
<animate attributeName="opacity" values="0.3;0.1;0.3" dur="3s" repeatCount="indefinite"/>
</line>

<circle cx="35" cy="38" r="4" fill="#ff003c" filter="url(#g2)" class="pd"/>
<circle cx="35" cy="38" r="8" fill="none" stroke="#ff003c" stroke-width="0.8" opacity="0.2">
<animate attributeName="r" values="8;14;8" dur="1.5s" repeatCount="indefinite"/>
<animate attributeName="opacity" values="0.2;0.03;0.2" dur="1.5s" repeatCount="indefinite"/>
</circle>
<text x="55" y="34" fill="#ffffff" font-family="monospace" font-size="13" font-weight="bold" opacity="0.9">Solveran</text>
<text x="55" y="50" fill="#777777" font-family="monospace" font-size="10" opacity="0.6">developer &gt; building tools</text>

<line x1="280" y1="15" x2="280" y2="105" stroke="#ff003c" stroke-width="0.5" opacity="0.15"/>

<!-- CPU Gauge -->
<text x="310" y="32" fill="#888888" font-family="monospace" font-size="9" opacity="0.5">CPU</text>
<rect x="310" y="38" width="100" height="4" rx="2" fill="#0a0a0a" stroke="#ff003c" stroke-width="0.3" opacity="0.2"/>
<rect x="310" y="38" width="0" height="4" rx="2" fill="url(#bar1)" filter="url(#g)" class="f1"/>
<text x="420" y="42" fill="#ff003c" font-family="monospace" font-size="9" opacity="0.6">78%</text>

<!-- MEM Gauge -->
<text x="310" y="55" fill="#888888" font-family="monospace" font-size="9" opacity="0.5">MEM</text>
<rect x="310" y="61" width="100" height="4" rx="2" fill="#0a0a0a" stroke="#ff003c" stroke-width="0.3" opacity="0.2"/>
<rect x="310" y="61" width="0" height="4" rx="2" fill="url(#bar1)" filter="url(#g)" class="f2"/>
<text x="420" y="65" fill="#ff003c" font-family="monospace" font-size="9" opacity="0.6">45%</text>

<!-- NET Gauge -->
<text x="310" y="78" fill="#888888" font-family="monospace" font-size="9" opacity="0.5">NET</text>
<rect x="310" y="84" width="100" height="4" rx="2" fill="#0a0a0a" stroke="#ff003c" stroke-width="0.3" opacity="0.2"/>
<rect x="310" y="84" width="0" height="4" rx="2" fill="url(#bar1)" filter="url(#g)" class="f3"/>
<text x="420" y="88" fill="#ff003c" font-family="monospace" font-size="9" opacity="0.6">92%</text>

<!-- GPU Gauge -->
<text x="310" y="101" fill="#888888" font-family="monospace" font-size="9" opacity="0.5">GPU</text>
<rect x="310" y="107" width="100" height="4" rx="2" fill="#0a0a0a" stroke="#ff003c" stroke-width="0.3" opacity="0.2"/>
<rect x="310" y="107" width="0" height="4" rx="2" fill="url(#bar1)" filter="url(#g)" class="f4"/>
<text x="420" y="111" fill="#ff003c" font-family="monospace" font-size="9" opacity="0.6">63%</text>

<line x1="495" y1="15" x2="495" y2="105" stroke="#ff003c" stroke-width="0.5" opacity="0.15"/>

<!-- Status Grid -->
<text x="525" y="32" fill="#666666" font-family="monospace" font-size="9" opacity="0.4">STATUS</text>
<text x="525" y="48" fill="#ff003c" font-family="monospace" font-size="11" opacity="0.85">active</text>
<circle cx="519" cy="44" r="1.5" fill="#ff003c" class="pd" filter="url(#g)" style="animation-delay:0.2s"/>

<text x="600" y="32" fill="#666666" font-family="monospace" font-size="9" opacity="0.4">FOCUS</text>
<text x="600" y="48" fill="#ff003c" font-family="monospace" font-size="11" opacity="0.85">full-stack</text>

<text x="675" y="32" fill="#666666" font-family="monospace" font-size="9" opacity="0.4">MODE</text>
<text x="675" y="48" fill="#ff003c" font-family="monospace" font-size="11" opacity="0.85">creation</text>

<text x="750" y="32" fill="#666666" font-family="monospace" font-size="9" opacity="0.4">UPTIME</text>
<text x="750" y="48" fill="#ff003c" font-family="monospace" font-size="11" opacity="0.85">24/7</text>

<!-- Skill icons row -->
<line x1="525" y1="62" x2="860" y2="62" stroke="#ff003c" stroke-width="0.3" opacity="0.1"/>

<text x="525" y="80" fill="#666666" font-family="monospace" font-size="9" opacity="0.4">STACK</text>
<image href="https://skillicons.dev/icons?i=python&amp;theme=dark" x="578" y="68" width="22" height="22"/>
<image href="https://skillicons.dev/icons?i=javascript&amp;theme=dark" x="604" y="68" width="22" height="22"/>
<image href="https://skillicons.dev/icons?i=typescript&amp;theme=dark" x="630" y="68" width="22" height="22"/>
<image href="https://skillicons.dev/icons?i=react&amp;theme=dark" x="656" y="68" width="22" height="22"/>
<image href="https://skillicons.dev/icons?i=nodejs&amp;theme=dark" x="682" y="68" width="22" height="22"/>
<image href="https://skillicons.dev/icons?i=html&amp;theme=dark" x="708" y="68" width="22" height="22"/>
<image href="https://skillicons.dev/icons?i=css&amp;theme=dark" x="734" y="68" width="22" height="22"/>
<image href="https://skillicons.dev/icons?i=git&amp;theme=dark" x="760" y="68" width="22" height="22"/>
<image href="https://skillicons.dev/icons?i=docker&amp;theme=dark" x="786" y="68" width="22" height="22"/>
<image href="https://skillicons.dev/icons?i=github&amp;theme=dark" x="812" y="68" width="22" height="22"/>

</svg>

<br/><br/>

</div>
<div align="center">

<svg viewBox="0 0 900 40" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:900px;">
<defs><linearGradient id="ll" x1="0%" y1="0%" x2="100%" y2="0%">
<stop offset="0%" stop-color="#ff003c" stop-opacity="0"/>
<stop offset="15%" stop-color="#ff003c" stop-opacity="0.3"/>
<stop offset="50%" stop-color="#ff003c" stop-opacity="0.7"/>
<stop offset="85%" stop-color="#ff003c" stop-opacity="0.3"/>
<stop offset="100%" stop-color="#ff003c" stop-opacity="0"/>
</linearGradient></defs>
<line x1="0" y1="20" x2="900" y2="20" stroke="url(#ll)" stroke-width="0.7"/>
<text x="450" y="24" text-anchor="middle" fill="#ff003c" font-family="monospace" font-size="10" opacity="0.6" letter-spacing="5">MODULES</text>
</svg>

<br/>

<table>
<tr>
<td width="25%" align="center" valign="top">
<svg viewBox="0 0 195 145" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:195px;">
<rect x="2" y="2" width="191" height="141" rx="10" fill="#050505" stroke="#ff003c" stroke-width="0.7" stroke-opacity="0.12"/>
<line x1="10" y1="2" x2="185" y2="2" stroke="#ff003c" stroke-width="1.2" opacity="0.25"/>
<text x="98" y="26" text-anchor="middle" fill="#ffffff" font-family="monospace" font-size="10" font-weight="bold" opacity="0.75">LANGUAGES</text>
<line x1="35" y1="34" x2="160" y2="34" stroke="#ff003c" stroke-width="0.3" opacity="0.1"/>
<image href="https://skillicons.dev/icons?i=python&amp;theme=dark" x="35" y="44" width="38" height="38"/>
<image href="https://skillicons.dev/icons?i=javascript&amp;theme=dark" x="78" y="44" width="38" height="38"/>
<image href="https://skillicons.dev/icons?i=typescript&amp;theme=dark" x="121" y="44" width="38" height="38"/>
<image href="https://skillicons.dev/icons?i=html&amp;theme=dark" x="35" y="88" width="38" height="38"/>
<image href="https://skillicons.dev/icons?i=css&amp;theme=dark" x="78" y="88" width="38" height="38"/>
<image href="https://skillicons.dev/icons?i=md&amp;theme=dark" x="121" y="88" width="38" height="38"/>
</svg>
</td>
<td width="25%" align="center" valign="top">
<svg viewBox="0 0 195 145" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:195px;">
<rect x="2" y="2" width="191" height="141" rx="10" fill="#050505" stroke="#ff003c" stroke-width="0.7" stroke-opacity="0.12"/>
<line x1="10" y1="2" x2="185" y2="2" stroke="#ff003c" stroke-width="1.2" opacity="0.25"/>
<text x="98" y="26" text-anchor="middle" fill="#ffffff" font-family="monospace" font-size="10" font-weight="bold" opacity="0.75">FRAMEWORKS</text>
<line x1="30" y1="34" x2="165" y2="34" stroke="#ff003c" stroke-width="0.3" opacity="0.1"/>
<image href="https://skillicons.dev/icons?i=react&amp;theme=dark" x="35" y="44" width="38" height="38"/>
<image href="https://skillicons.dev/icons?i=nodejs&amp;theme=dark" x="78" y="44" width="38" height="38"/>
<image href="https://skillicons.dev/icons?i=nextjs&amp;theme=dark" x="121" y="44" width="38" height="38"/>
<image href="https://skillicons.dev/icons?i=tailwind&amp;theme=dark" x="35" y="88" width="38" height="38"/>
<image href="https://skillicons.dev/icons?i=fastapi&amp;theme=dark" x="78" y="88" width="38" height="38"/>
<image href="https://skillicons.dev/icons?i=flask&amp;theme=dark" x="121" y="88" width="38" height="38"/>
</svg>
</td>
<td width="25%" align="center" valign="top">
<svg viewBox="0 0 195 145" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:195px;">
<rect x="2" y="2" width="191" height="141" rx="10" fill="#050505" stroke="#ff003c" stroke-width="0.7" stroke-opacity="0.12"/>
<line x1="10" y1="2" x2="185" y2="2" stroke="#ff003c" stroke-width="1.2" opacity="0.25"/>
<text x="98" y="26" text-anchor="middle" fill="#ffffff" font-family="monospace" font-size="10" font-weight="bold" opacity="0.75">TOOLS</text>
<line x1="45" y1="34" x2="150" y2="34" stroke="#ff003c" stroke-width="0.3" opacity="0.1"/>
<image href="https://skillicons.dev/icons?i=git&amp;theme=dark" x="35" y="44" width="38" height="38"/>
<image href="https://skillicons.dev/icons?i=github&amp;theme=dark" x="78" y="44" width="38" height="38"/>
<image href="https://skillicons.dev/icons?i=vscode&amp;theme=dark" x="121" y="44" width="38" height="38"/>
<image href="https://skillicons.dev/icons?i=bash&amp;theme=dark" x="35" y="88" width="38" height="38"/>
<image href="https://skillicons.dev/icons?i=docker&amp;theme=dark" x="78" y="88" width="38" height="38"/>
<image href="https://skillicons.dev/icons?i=postman&amp;theme=dark" x="121" y="88" width="38" height="38"/>
</svg>
</td>
<td width="25%" align="center" valign="top">
<svg viewBox="0 0 195 145" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:195px;">
<rect x="2" y="2" width="191" height="141" rx="10" fill="#050505" stroke="#ff003c" stroke-width="0.7" stroke-opacity="0.12"/>
<line x1="10" y1="2" x2="185" y2="2" stroke="#ff003c" stroke-width="1.2" opacity="0.25"/>
<text x="98" y="26" text-anchor="middle" fill="#ffffff" font-family="monospace" font-size="10" font-weight="bold" opacity="0.75">AI &amp; DEVOPS</text>
<line x1="30" y1="34" x2="165" y2="34" stroke="#ff003c" stroke-width="0.3" opacity="0.1"/>
<image href="https://skillicons.dev/icons?i=tensorflow&amp;theme=dark" x="35" y="44" width="38" height="38"/>
<image href="https://skillicons.dev/icons?i=pytorch&amp;theme=dark" x="78" y="44" width="38" height="38"/>
<image href="https://skillicons.dev/icons?i=opencv&amp;theme=dark" x="121" y="44" width="38" height="38"/>
<image href="https://skillicons.dev/icons?i=linux&amp;theme=dark" x="35" y="88" width="38" height="38"/>
<image href="https://skillicons.dev/icons?i=ngi&amp;theme=dark" x="78" y="88" width="38" height="38"/>
<image href="https://skillicons.dev/icons?i=heroku&amp;theme=dark" x="121" y="88" width="38" height="38"/>
</svg>
</td>
</tr>
</table>

</div>

<br/>
<div align="center">

<svg viewBox="0 0 900 40" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:900px;">
<defs><linearGradient id="l2" x1="0%" y1="0%" x2="100%" y2="0%">
<stop offset="0%" stop-color="#ff003c" stop-opacity="0"/>
<stop offset="15%" stop-color="#ff003c" stop-opacity="0.3"/>
<stop offset="50%" stop-color="#ff003c" stop-opacity="0.7"/>
<stop offset="85%" stop-color="#ff003c" stop-opacity="0.3"/>
<stop offset="100%" stop-color="#ff003c" stop-opacity="0"/>
</linearGradient></defs>
<line x1="0" y1="20" x2="900" y2="20" stroke="url(#l2)" stroke-width="0.7"/>
<text x="450" y="24" text-anchor="middle" fill="#ff003c" font-family="monospace" font-size="10" opacity="0.6" letter-spacing="5">GAMES</text>
</svg>
</svg>

<br/>

<svg viewBox="0 0 900 320" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:900px;"
<!-- SLITHER.IO -->
<svg viewBox="0 0 900 50" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:900px;">
<rect x="2" y="2" width="896" height="46" rx="10" fill="#050505" stroke="#ff003c" stroke-width="0.6" stroke-opacity="0.1"/>
<line x1="20" y1="2" x2="880" y2="2" stroke="#ff003c" stroke-width="1" opacity="0.2"/>
<circle cx="25" cy="25" r="3" fill="#ff003c" opacity="0.6"><animate attributeName="r" values="3;5;3" dur="1.5s" repeatCount="indefinite"/></circle>
<text x="45" y="29" fill="#ffffff" font-family="monospace" font-size="12" font-weight="bold" opacity="0.7">SLITHER.IO</text>
<text x="145" y="29" fill="#555555" font-family="monospace" font-size="9" opacity="0.4">growing snake</text>
</svg>

<svg viewBox="0 0 900 200" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:900px;">
<defs>
<filter id="gS"><feGaussianBlur stdDeviation="3" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
<filter id="gcS"><feGaussianBlur in="SourceAlpha" stdDeviation="3" result="b"/><feOffset dx="0" dy="0" result="o"/><feFlood flood-color="#ff003c" flood-opacity="0.04" result="c"/><feComposite in="c" in2="o" operator="in" result="s"/><feMerge><feMergeNode in="s"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
</defs>
<style>
@keyframes slHead{0%,100%{cx:350;cy:100}20%{cx:420;cy:70}40%{cx:520;cy:90}60%{cx:580;cy:140}80%{cx:500;cy:170}100%{cx:350;cy:100}}
@keyframes slBody1{0%,100%{cx:330;cy:105}20%{cx:400;cy:75}40%{cx:500;cy:95}60%{cx:560;cy:145}80%{cx:480;cy:175}100%{cx:330;cy:105}}
@keyframes slBody2{0%,100%{cx:310;cy:110}20%{cx:380;cy:80}40%{cx:480;cy:100}60%{cx:540;cy:150}80%{cx:460;cy:180}100%{cx:310;cy:110}}
@keyframes slBody3{0%,100%{cx:290;cy:115}20%{cx:360;cy:85}40%{cx:460;cy:105}60%{cx:520;cy:155}80%{cx:440;cy:185}100%{cx:290;cy:115}}
@keyframes slBody4{0%,100%{cx:270;cy:120}20%{cx:340;cy:90}40%{cx:440;cy:110}60%{cx:500;cy:160}80%{cx:420;cy:190}100%{cx:270;cy:120}}
@keyframes slFood{0%,100%{opacity:1}50%{opacity:0.3}}
.sh{animation:slHead 6s ease-in-out infinite}
.sb1{animation:slBody1 6s ease-in-out infinite}
.sb2{animation:slBody2 6s ease-in-out infinite}
.sb3{animation:slBody3 6s ease-in-out infinite}
.sb4{animation:slBody4 6s ease-in-out infinite}
.sf{animation:slFood 1s ease-in-out infinite}
</style>
<rect x="2" y="2" width="896" height="196" rx="10" fill="#050505" stroke="#ff003c" stroke-width="0.6" stroke-opacity="0.1" filter="url(#gcS)"/>
<rect x="100" y="25" width="700" height="150" rx="8" fill="none" stroke="#ff003c" stroke-width="0.5" opacity="0.12"/>
<pattern id="sgrid" width="25" height="25" patternUnits="userSpaceOnUse"><circle cx="12.5" cy="12.5" r="0.5" fill="#ff003c" opacity="0.04"/></pattern>
<rect x="100" y="25" width="700" height="150" fill="url(#sgrid)"/>
<circle cx="200" cy="60" r="4" fill="#ff003c" opacity="0.5" class="sf" filter="url(#gS)"/>
<circle cx="650" cy="50" r="3" fill="#ff003c" opacity="0.3" class="sf" style="animation-delay:0.5s"/>
<circle cx="300" cy="150" r="5" fill="#ffffff" opacity="0.4" class="sf" style="animation-delay:1.3s" filter="url(#gS)"/>
<circle cx="600" cy="160" r="3" fill="#ff003c" opacity="0.3" class="sf" style="animation-delay:2s"/>
<circle cx="700" cy="100" r="4" fill="#ff003c" opacity="0.4" class="sf" style="animation-delay:0.8s" filter="url(#gS)"/>
<circle cx="150" cy="120" r="3" fill="#ffffff" opacity="0.3" class="sf" style="animation-delay:1.7s"/>
<circle cx="0" cy="0" r="8" fill="#ff003c" opacity="0.2" class="sb4"/>
<circle cx="0" cy="0" r="9" fill="#ff003c" opacity="0.25" class="sb3"/>
<circle cx="0" cy="0" r="10" fill="#ff003c" opacity="0.3" class="sb2"/>
<circle cx="0" cy="0" r="11" fill="#ff003c" opacity="0.4" class="sb1"/>
<circle cx="0" cy="0" r="12" fill="#ff003c" opacity="0.8" class="sh" filter="url(#gS)"/>
<circle cx="0" cy="0" r="5" fill="#ffffff" opacity="0.5" class="sh"/>
<text x="790" y="185" fill="#555555" font-family="monospace" font-size="8" opacity="0.3">SCORE: 142</text>
</svg>

<br/><br/>
<!-- SNAKE -->
<svg viewBox="0 0 900 50" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:900px;">
<rect x="2" y="2" width="896" height="46" rx="10" fill="#050505" stroke="#ff003c" stroke-width="0.6" stroke-opacity="0.1"/>
<line x1="20" y1="2" x2="880" y2="2" stroke="#ff003c" stroke-width="1" opacity="0.2"/>
<circle cx="25" cy="25" r="3" fill="#ff003c" opacity="0.6"><animate attributeName="r" values="3;5;3" dur="1.5s" repeatCount="indefinite"/></circle>
<text x="45" y="29" fill="#ffffff" font-family="monospace" font-size="12" font-weight="bold" opacity="0.7">SNAKE</text>
<text x="120" y="29" fill="#555555" font-family="monospace" font-size="9" opacity="0.4">contribution grid</text>
</svg>

<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg"/>
<source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake.svg"/>
<img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" width="100%"/>
</picture>

<br/><br/><svg viewBox="0 0 900 40" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:900px;">
<defs><linearGradient id="l3" x1="0%" y1="0%" x2="100%" y2="0%">
<stop offset="0%" stop-color="#ff003c" stop-opacity="0"/>
<stop offset="15%" stop-color="#ff003c" stop-opacity="0.3"/>
<stop offset="50%" stop-color="#ff003c" stop-opacity="0.7"/>
<stop offset="85%" stop-color="#ff003c" stop-opacity="0.3"/>
<stop offset="100%" stop-color="#ff003c" stop-opacity="0"/>
</linearGradient></defs>
<line x1="0" y1="20" x2="900" y2="20" stroke="url(#l3)" stroke-width="0.7"/>
<text x="450" y="24" text-anchor="middle" fill="#ff003c" font-family="monospace" font-size="10" opacity="0.6" letter-spacing="5">ANALYTICS</text>
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

<svg viewBox="0 0 900 40" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:900px;">
<defs><linearGradient id="l4" x1="0%" y1="0%" x2="100%" y2="0%">
<stop offset="0%" stop-color="#ff003c" stop-opacity="0"/>
<stop offset="15%" stop-color="#ff003c" stop-opacity="0.3"/>
<stop offset="50%" stop-color="#ff003c" stop-opacity="0.7"/>
<stop offset="85%" stop-color="#ff003c" stop-opacity="0.3"/>
<stop offset="100%" stop-color="#ff003c" stop-opacity="0"/>
</linearGradient></defs>
<line x1="0" y1="20" x2="900" y2="20" stroke="url(#l4)" stroke-width="0.7"/>
<text x="450" y="24" text-anchor="middle" fill="#ff003c" font-family="monospace" font-size="10" opacity="0.6" letter-spacing="5">CONTRIBUTIONS</text>
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

<svg viewBox="0 0 900 65" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:900px;">
<defs><filter id="gf"><feGaussianBlur in="SourceAlpha" stdDeviation="3" result="b"/><feOffset dx="0" dy="0" result="o"/><feFlood flood-color="#ff003c" flood-opacity="0.04" result="c"/><feComposite in="c" in2="o" operator="in" result="s"/><feMerge><feMergeNode in="s"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
<filter id="gR2"><feGaussianBlur stdDeviation="3" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter></defs>
<rect x="2" y="2" width="896" height="61" rx="10" fill="#050505" stroke="#ff003c" stroke-width="0.6" stroke-opacity="0.1" filter="url(#gf)"/>
<line x1="20" y1="2" x2="880" y2="2" stroke="#ff003c" stroke-width="1" opacity="0.2" filter="url(#gR2)"/>
<text x="40" y="36" fill="#ffffff" font-family="monospace" font-size="12" font-weight="bold" opacity="0.6">VISITORS</text>
<text x="40" y="50" fill="#555555" font-family="monospace" font-size="8" opacity="0.4">profile tracker</text>
<image href="https://api.visitorbadge.io/api/visitors?path=Solveran601%2FSolveran601&amp;countColor=%23ff003c&amp;style=flat&amp;label=&amp;labelColor=%23000000" x="760" y="16" width="125" height="32"/>
</svg>

<br/><br/>

<svg viewBox="0 0 900 55" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:900px;">
<rect x="2" y="2" width="896" height="51" rx="10" fill="#050505" stroke="#ff003c" stroke-width="0.6" stroke-opacity="0.08"/>
<text x="450" y="20" text-anchor="middle" fill="#555555" font-family="monospace" font-size="8" opacity="0.4" letter-spacing="3">CONNECT</text>
<a href="https://github.com/Solveran601" target="_blank">
<rect x="320" y="25" width="110" height="20" rx="4" fill="none" stroke="#ff003c" stroke-width="0.5" stroke-opacity="0.25"/>
<text x="375" y="39" text-anchor="middle" fill="#ffffff" font-family="monospace" font-size="9" opacity="0.6">github.com/Solveran601</text>
</a>
</svg>

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&amp;color=0:ff003c,30:111111,60:0a0a0a,100:000000&amp;height=180&amp;section=footer&amp;text=%3E+system+operational&amp;fontSize=20&amp;fontColor=ffffff&amp;fontAlignY=55&amp;desc=SOLVERAN+%7C%7C+v2.0&amp;descSize=11&amp;descAlignY=75&amp;descColor=aaaaaa&amp;animation=fadeIn" width="100%"/>

</div>



