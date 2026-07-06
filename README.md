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
<text x="715" y="218" fill="#ff003c" font-family="monospace" font-size="10" opacity="0.6">
<animate attributeName="opacity" values="0;0.6" dur="5s" repeatCount="indefinite"/>
<tspan>
<animate attributeName="textContent" values="0%;15%;38%;62%;84%;100%" dur="5s" repeatCount="indefinite"/>
</tspan>100%</text>

<!-- Loading Dots -->
<text x="200" y="245" fill="#666666" font-family="monospace" font-size="10" opacity="0.4">
<tspan>status</tspan>
<tspan fill="#ff003c" opacity="0.7">
<animate attributeName="textContent" values=".....;......;.......;......;....." dur="5s" repeatCount="indefinite"/>
.......</tspan>
</text>

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
<text x="35" y="255" fill="#ff003c" font-family="monospace" font-size="8" opacity="0.3">CORE::ACTIVE</text>
<text x="790" y="255" fill="#ff003c" font-family="monospace" font-size="8" opacity="0.3">NODE::v2.0</text>
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
<text x="450" y="146" text-anchor="middle" fill="#ffffff" font-family="monospace" font-size="9" font-weight="bold" opacity="0.85" filter="url(#gs)">NX</text>

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
<image href="https://skillicons.dev/icons?i=nginx&amp;theme=dark" x="78" y="88" width="38" height="38"/>
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
<text x="450" y="24" text-anchor="middle" fill="#ff003c" font-family="monospace" font-size="10" opacity="0.6" letter-spacing="5">ARCADE</text>
</svg>

<br/>

<svg viewBox="0 0 900 320" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:900px;">
<defs>
<filter id="gR"><feGaussianBlur stdDeviation="3" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
<filter id="gI"><feGaussianBlur stdDeviation="5" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
<filter id="gc2"><feGaussianBlur in="SourceAlpha" stdDeviation="3" result="b"/><feOffset dx="0" dy="0" result="o"/><feFlood flood-color="#ff003c" flood-opacity="0.04" result="c"/><feComposite in="c" in2="o" operator="in" result="s"/><feMerge><feMergeNode in="s"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
</defs>
<style>
@keyframes gShow{0%,6%{opacity:1}7%,100%{opacity:0}}
@keyframes gLabel{0%,6%{opacity:0.8}7%,100%{opacity:0}}
@keyframes scanLn{0%{transform:translateY(-320px)}100%{transform:translateY(640px)}}
@keyframes loadingBar{0%{width:0}100%{width:540}}
@keyframes pulseTxt{0%,100%{opacity:0.6}50%{opacity:1}}
.sl2{animation:scanLn 4s linear infinite}
.g1{animation:gShow 75s infinite}
.g2{animation:gShow 75s infinite;animation-delay:5s}
.g3{animation:gShow 75s infinite;animation-delay:10s}
.g4{animation:gShow 75s infinite;animation-delay:15s}
.g5{animation:gShow 75s infinite;animation-delay:20s}
.g6{animation:gShow 75s infinite;animation-delay:25s}
.g7{animation:gShow 75s infinite;animation-delay:30s}
.g8{animation:gShow 75s infinite;animation-delay:35s}
.g9{animation:gShow 75s infinite;animation-delay:40s}
.g10{animation:gShow 75s infinite;animation-delay:45s}
.g11{animation:gShow 75s infinite;animation-delay:50s}
.g12{animation:gShow 75s infinite;animation-delay:55s}
.g13{animation:gShow 75s infinite;animation-delay:60s}
.g14{animation:gShow 75s infinite;animation-delay:65s}
.g15{animation:gShow 75s infinite;animation-delay:70s}
.l1{animation:gLabel 75s infinite}
.l2{animation:gLabel 75s infinite;animation-delay:5s}
.l3{animation:gLabel 75s infinite;animation-delay:10s}
.l4{animation:gLabel 75s infinite;animation-delay:15s}
.l5{animation:gLabel 75s infinite;animation-delay:20s}
.l6{animation:gLabel 75s infinite;animation-delay:25s}
.l7{animation:gLabel 75s infinite;animation-delay:30s}
.l8{animation:gLabel 75s infinite;animation-delay:35s}
.l9{animation:gLabel 75s infinite;animation-delay:40s}
.l10{animation:gLabel 75s infinite;animation-delay:45s}
.l11{animation:gLabel 75s infinite;animation-delay:50s}
.l12{animation:gLabel 75s infinite;animation-delay:55s}
.l13{animation:gLabel 75s infinite;animation-delay:60s}
.l14{animation:gLabel 75s infinite;animation-delay:65s}
.l15{animation:gLabel 75s infinite;animation-delay:70s}
@keyframes snakeMove{0%{x:175}50%{x:265}100%{x:175}}
@keyframes snakeFood{0%,100%{opacity:1;r:4}50%{opacity:0.3;r:6}}
@keyframes pongBall{0%,100%{cx:380;cy:140}25%{cx:480;cy:100}50%{cx:530;cy:140}75%{cx:480;cy:180}}
@keyframes pongP1{0%,100%{y:120}50%{y:160}}
@keyframes pongP2{0%,100%{y:160}50%{y:100}}
@keyframes tetrisFall{0%{y:-10;opacity:0}5%{opacity:1}95%{opacity:1}100%{y:180;opacity:0}}
@keyframes invaderMove{0%,100%{transform:translateX(0)}50%{transform:translateX(100px)}}
@keyframes pacMove{0%,100%{cx:280}25%{cx:400}50%{cx:520}75%{cx:400}}
@keyframes pacMouth{0%,100%{d:M 20 0 A 20 20 0 0 1 20 40 Z}50%{d:M 20 0 A 20 20 0 0 1 20 40 L 20 20 Z}}
@keyframes breakBall{0%,100%{cx:440;cy:160}25%{cx:500;cy:120}50%{cx:540;cy:160}75%{cx:500;cy:190}}
@keyframes raceRoad{0%{transform:translateY(0)}100%{transform:translateY(40px)}}
@keyframes platformRun{0%,100%{cx:360}25%{cx:420}50%{cx:500}75%{cx:440}}
@keyframes astRotate{from{transform:rotate(0deg)}to{transform:rotate(360deg)}}
@keyframes fighterPunch{0%,100%{transform:translateX(0)}30%{transform:translateX(15px)}40%{transform:translateX(-5px)}50%{transform:translateX(0)}}
@keyframes ddrArrow{0%{transform:translateY(100px);opacity:0}10%{opacity:1}90%{opacity:1}100%{transform:translateY(-50px);opacity:0}}
@keyframes flappyBird{0%,100%{cy:140}25%{cy:120}50%{cy:160}75%{cy:130}}
@keyframes flappyPipe{0%{transform:translateX(200px)}100%{transform:translateX(-200px)}}
@keyframes mazeDot{0%,100%{cx:340;cy:170}25%{cx:440;cy:170}50%{cx:440;cy:130}75%{cx:340;cy:130}}
@keyframes shootTarget{0%,100%{cx:500;cy:120}50%{cx:500;cy:180}}
@keyframes shootCross{0%,100%{transform:translateX(0)}50%{transform:translateX(60px)}}
@keyframes creditsScroll{0%{transform:translateY(150px)}100%{transform:translateY(-100px)}}
.inv{animation:invaderMove 2s ease-in-out infinite}
.pac{animation:pacMove 3s ease-in-out infinite}
.brk{animation:breakBall 2.5s ease-in-out infinite}
.race{animation:raceRoad 0.5s linear infinite}
.plat{animation:platformRun 2s ease-in-out infinite}
.ast{animation:astRotate 3s linear infinite;transform-origin:450px 150px}
.fgt{animation:fighterPunch 1.5s ease-in-out infinite}
.flp{animation:flappyBird 1.8s ease-in-out infinite}
.flpipe{animation:flappyPipe 3s linear infinite}
.mzd{animation:mazeDot 4s ease-in-out infinite}
.shoot{animation:shootCross 2s ease-in-out infinite}
</style>

<rect x="2" y="2" width="896" height="316" rx="14" fill="#050505" stroke="#ff003c" stroke-width="0.8" stroke-opacity="0.12" filter="url(#gc2)"/>
<line x1="20" y1="2" x2="880" y2="2" stroke="#ff003c" stroke-width="1.2" opacity="0.25" filter="url(#gR)"/>

<!-- Scan lines overlay -->
<rect x="30" y="30" width="840" height="260" fill="none" stroke="#ff003c" stroke-width="0.5" opacity="0.08" stroke-dasharray="2 4"/>
<rect x="0" y="0" width="900" height="2" fill="#ff003c" opacity="0.12" class="sl2" filter="url(#gR)"/>

<!-- Title bar -->
<text x="450" y="22" text-anchor="middle" fill="#666666" font-family="monospace" font-size="8" opacity="0.4" letter-spacing="3">ARCADE // GAME LOADING</text>

<!-- Loading indicator -->
<rect x="180" y="298" width="540" height="3" rx="1.5" fill="#0a0a0a" stroke="#ff003c" stroke-width="0.3" opacity="0.15"/>
<rect x="180" y="298" width="0" height="3" rx="1.5" fill="#ff003c" opacity="0.4" filter="url(#gR)">
<animate attributeName="width" from="0" to="540" dur="75s" repeatCount="indefinite"/>
</rect>

<!-- NOW PLAYING label -->
<text x="450" y="295" text-anchor="middle" fill="#777777" font-family="monospace" font-size="8" opacity="0.3">NOW PLAYING</text>

<!-- GAME 1: SNAKE -->
<g class="g1">
<text x="450" y="50" text-anchor="middle" fill="#ff003c" font-family="monospace" font-size="11" font-weight="bold" opacity="0.7" filter="url(#gR)">SNAKE</text>
<rect x="350" y="65" width="200" height="200" rx="4" fill="none" stroke="#ff003c" stroke-width="0.5" opacity="0.15"/>
<!-- Grid lines -->
<line x1="400" y1="65" x2="400" y2="265" stroke="#ff003c" stroke-width="0.2" opacity="0.06"/>
<line x1="450" y1="65" x2="450" y2="265" stroke="#ff003c" stroke-width="0.2" opacity="0.06"/>
<line x1="500" y1="65" x2="500" y2="265" stroke="#ff003c" stroke-width="0.2" opacity="0.06"/>
<line x1="350" y1="115" x2="550" y2="115" stroke="#ff003c" stroke-width="0.2" opacity="0.06"/>
<line x1="350" y1="165" x2="550" y2="165" stroke="#ff003c" stroke-width="0.2" opacity="0.06"/>
<line x1="350" y1="215" x2="550" y2="215" stroke="#ff003c" stroke-width="0.2" opacity="0.06"/>
<!-- Snake body -->
<rect x="400" y="215" width="10" height="10" fill="#ff003c" opacity="0.4" rx="2"/>
<rect x="410" y="215" width="10" height="10" fill="#ff003c" opacity="0.5" rx="2"/>
<rect x="420" y="215" width="10" height="10" fill="#ff003c" opacity="0.6" rx="2"/>
<rect x="430" y="215" width="10" height="10" fill="#ff003c" opacity="0.7" rx="2"/>
<!-- Snake head moving -->
<rect x="440" y="215" width="10" height="10" fill="#ff003c" opacity="0.95" rx="2" filter="url(#gR)">
<animate attributeName="x" values="440;470;470;470;470;440;440;440;440;390;390;390;390;440" dur="4s" repeatCount="indefinite"/>
<animate attributeName="y" values="215;215;165;115;65;65;115;165;215;215;165;115;65;65" dur="4s" repeatCount="indefinite"/>
</rect>
<!-- Food -->
<circle cx="470" cy="115" r="4" fill="#ffffff" opacity="0.6" filter="url(#gR)">
<animate attributeName="opacity" values="0.6;0.2;0.6" dur="0.8s" repeatCount="indefinite"/>
</circle>
</g>

<!-- GAME 2: PONG -->
<g class="g2">
<text x="450" y="50" text-anchor="middle" fill="#ff003c" font-family="monospace" font-size="11" font-weight="bold" opacity="0.7" filter="url(#gR)">PONG</text>
<rect x="320" y="65" width="260" height="195" rx="4" fill="none" stroke="#ff003c" stroke-width="0.5" opacity="0.15"/>
<line x1="450" y1="65" x2="450" y2="260" stroke="#ff003c" stroke-width="0.3" opacity="0.1" stroke-dasharray="4 6"/>
<!-- Paddle 1 -->
<rect x="332" y="120" width="6" height="30" rx="3" fill="#ff003c" opacity="0.7">
<animate attributeName="y" values="120;160;120" dur="3s" repeatCount="indefinite"/>
</rect>
<!-- Paddle 2 -->
<rect x="562" y="160" width="6" height="30" rx="3" fill="#ff003c" opacity="0.7">
<animate attributeName="y" values="160;100;160" dur="3.5s" repeatCount="indefinite"/>
</rect>
<!-- Ball -->
<circle cx="450" cy="140" r="5" fill="#ffffff" opacity="0.8" filter="url(#gR)">
<animate attributeName="cx" values="380;530;380" dur="2s" repeatCount="indefinite"/>
<animate attributeName="cy" values="140;100;140" dur="2s" repeatCount="indefinite"/>
</circle>
<!-- Score -->
<text x="410" y="90" text-anchor="middle" fill="#ff003c" font-family="monospace" font-size="14" opacity="0.4">3</text>
<text x="490" y="90" text-anchor="middle" fill="#ff003c" font-family="monospace" font-size="14" opacity="0.4">2</text>
</g>
<!-- GAME 3: TETRIS -->
<g class="g3">
<text x="450" y="50" text-anchor="middle" fill="#ff003c" font-family="monospace" font-size="11" font-weight="bold" opacity="0.7" filter="url(#gR)">TETRIS</text>
<rect x="350" y="65" width="200" height="200" rx="4" fill="none" stroke="#ff003c" stroke-width="0.5" opacity="0.15"/>
<line x1="400" y1="65" x2="400" y2="265" stroke="#ff003c" stroke-width="0.2" opacity="0.06"/>
<line x1="450" y1="65" x2="450" y2="265" stroke="#ff003c" stroke-width="0.2" opacity="0.06"/>
<line x1="500" y1="65" x2="500" y2="265" stroke="#ff003c" stroke-width="0.2" opacity="0.06"/>
<line x1="350" y1="115" x2="550" y2="115" stroke="#ff003c" stroke-width="0.2" opacity="0.06"/>
<line x1="350" y1="165" x2="550" y2="165" stroke="#ff003c" stroke-width="0.2" opacity="0.06"/>
<line x1="350" y1="215" x2="550" y2="215" stroke="#ff003c" stroke-width="0.2" opacity="0.06"/>
<!-- Stacked blocks at bottom -->
<rect x="400" y="245" width="90" height="20" fill="#ff003c" opacity="0.3" rx="2"/>
<rect x="450" y="225" width="90" height="20" fill="#ff003c" opacity="0.25" rx="2"/>
<rect x="400" y="205" width="40" height="20" fill="#ff003c" opacity="0.2" rx="2"/>
<!-- Falling piece -->
<g opacity="0.7">
<rect x="400" y="0" width="20" height="20" fill="#ff003c" rx="2">
<animate attributeName="y" from="65" to="195" dur="4s" repeatCount="indefinite"/>
</rect>
<rect x="420" y="0" width="20" height="20" fill="#ff003c" rx="2">
<animate attributeName="y" from="65" to="195" dur="4s" repeatCount="indefinite"/>
</rect>
<rect x="440" y="0" width="20" height="20" fill="#ff003c" rx="2">
<animate attributeName="y" from="65" to="195" dur="4s" repeatCount="indefinite"/>
</rect>
<rect x="460" y="0" width="20" height="20" fill="#ff003c" rx="2">
<animate attributeName="y" from="65" to="195" dur="4s" repeatCount="indefinite"/>
</rect>
</g>
<text x="460" y="253" fill="#ff003c" font-family="monospace" font-size="9" opacity="0.4">4</text>
<text x="505" y="233" fill="#ff003c" font-family="monospace" font-size="9" opacity="0.3">3</text>
</g>

<!-- GAME 4: INVADERS -->
<g class="g4">
<text x="450" y="50" text-anchor="middle" fill="#ff003c" font-family="monospace" font-size="11" font-weight="bold" opacity="0.7" filter="url(#gR)">INVADERS</text>
<rect x="320" y="65" width="260" height="200" rx="4" fill="none" stroke="#ff003c" stroke-width="0.5" opacity="0.15"/>
<!-- Aliens row 1 -->
<g class="inv">
<circle cx="370" cy="95" r="8" fill="none" stroke="#ff003c" stroke-width="1.2" opacity="0.5"/>
<circle cx="390" cy="95" r="8" fill="none" stroke="#ff003c" stroke-width="1.2" opacity="0.5"/>
<circle cx="410" cy="95" r="8" fill="none" stroke="#ff003c" stroke-width="1.2" opacity="0.5"/>
<circle cx="430" cy="95" r="8" fill="none" stroke="#ff003c" stroke-width="1.2" opacity="0.5"/>
<circle cx="450" cy="95" r="8" fill="none" stroke="#ff003c" stroke-width="1.2" opacity="0.5"/>
<circle cx="470" cy="95" r="8" fill="none" stroke="#ff003c" stroke-width="1.2" opacity="0.5"/>
<circle cx="490" cy="95" r="8" fill="none" stroke="#ff003c" stroke-width="1.2" opacity="0.5"/>
</g>
<!-- Aliens row 2 -->
<g class="inv" style="animation-delay:-1s">
<circle cx="370" cy="125" r="8" fill="none" stroke="#ff003c" stroke-width="1" opacity="0.35"/>
<circle cx="390" cy="125" r="8" fill="none" stroke="#ff003c" stroke-width="1" opacity="0.35"/>
<circle cx="410" cy="125" r="8" fill="none" stroke="#ff003c" stroke-width="1" opacity="0.35"/>
<circle cx="430" cy="125" r="8" fill="none" stroke="#ff003c" stroke-width="1" opacity="0.35"/>
<circle cx="450" cy="125" r="8" fill="none" stroke="#ff003c" stroke-width="1" opacity="0.35"/>
<circle cx="470" cy="125" r="8" fill="none" stroke="#ff003c" stroke-width="1" opacity="0.35"/>
<circle cx="490" cy="125" r="8" fill="none" stroke="#ff003c" stroke-width="1" opacity="0.35"/>
</g>
<!-- Ship -->
<polygon points="440,240 460,240 455,255 445,255" fill="#ff003c" opacity="0.7" filter="url(#gR)">
<animate attributeName="opacity" values="0.7;1;0.7" dur="0.3s" repeatCount="indefinite"/>
</polygon>
<!-- Laser -->
<line x1="450" y1="240" x2="450" y2="200" stroke="#ff003c" stroke-width="1.5" opacity="0">
<animate attributeName="opacity" values="0;0;0.6;0" dur="2s" repeatCount="indefinite" begin="0.5s"/>
</line>
<line x1="410" y1="240" x2="410" y2="210" stroke="#ff003c" stroke-width="1.5" opacity="0">
<animate attributeName="opacity" values="0;0;0.4;0" dur="2s" repeatCount="indefinite" begin="1.5s"/>
</line>
</g>

<!-- GAME 5: PAC-MAN -->
<g class="g5">
<text x="450" y="50" text-anchor="middle" fill="#ff003c" font-family="monospace" font-size="11" font-weight="bold" opacity="0.7" filter="url(#gR)">PAC-MAN</text>
<rect x="280" y="65" width="340" height="190" rx="4" fill="none" stroke="#ff003c" stroke-width="0.5" opacity="0.15"/>
<!-- Dots -->
<circle cx="320" cy="155" r="2" fill="#ff003c" opacity="0.3"/>
<circle cx="350" cy="155" r="2" fill="#ff003c" opacity="0.3"/>
<circle cx="380" cy="155" r="2" fill="#ff003c" opacity="0.3"/>
<circle cx="410" cy="155" r="2" fill="#ff003c" opacity="0.3"/>
<circle cx="440" cy="155" r="2" fill="#ff003c" opacity="0.3"/>
<circle cx="470" cy="155" r="2" fill="#ff003c" opacity="0.3"/>
<circle cx="500" cy="155" r="2" fill="#ff003c" opacity="0.3"/>
<circle cx="530" cy="155" r="2" fill="#ff003c" opacity="0.3"/>
<circle cx="560" cy="155" r="2" fill="#ff003c" opacity="0.3"/>
<!-- Pac-Man -->
<g class="pac" filter="url(#gR)">
<path d="M 290 145 A 15 15 0 0 1 290 175 L 295 160 Z" fill="#ff003c" opacity="0.8">
<animate attributeName="d" values="M 280 145 A 15 15 0 0 1 280 175 L 285 160 Z;M 400 145 A 15 15 0 0 1 400 175 L 405 160 Z;M 520 145 A 15 15 0 0 1 520 175 L 525 160 Z;M 400 145 A 15 15 0 0 1 400 175 L 405 160 Z;M 280 145 A 15 15 0 0 1 280 175 L 285 160 Z" dur="3s" repeatCount="indefinite"/>
</path>
</g>
<!-- Ghost -->
<g class="pac" style="animation-delay:-1.5s" opacity="0.4">
<rect x="355" y="140" width="14" height="14" rx="7" fill="none" stroke="#ff003c" stroke-width="1" opacity="0.5"/>
</g>
</g>

<!-- GAME 6: BREAKOUT -->
<g class="g6">
<text x="450" y="50" text-anchor="middle" fill="#ff003c" font-family="monospace" font-size="11" font-weight="bold" opacity="0.7" filter="url(#gR)">BREAKOUT</text>
<rect x="320" y="65" width="260" height="200" rx="4" fill="none" stroke="#ff003c" stroke-width="0.5" opacity="0.15"/>
<!-- Bricks -->
<rect x="335" y="80" width="34" height="14" rx="3" fill="#ff003c" opacity="0.5"/>
<rect x="373" y="80" width="34" height="14" rx="3" fill="#ff003c" opacity="0.45"/>
<rect x="411" y="80" width="34" height="14" rx="3" fill="#ff003c" opacity="0.5"/>
<rect x="449" y="80" width="34" height="14" rx="3" fill="#ff003c" opacity="0.45"/>
<rect x="487" y="80" width="34" height="14" rx="3" fill="#ff003c" opacity="0.5"/>
<rect x="525" y="80" width="34" height="14" rx="3" fill="#ff003c" opacity="0.45"/>
<rect x="353" y="100" width="34" height="14" rx="3" fill="#ff003c" opacity="0.35"/>
<rect x="391" y="100" width="34" height="14" rx="3" fill="#ff003c" opacity="0.3"/>
<rect x="429" y="100" width="34" height="14" rx="3" fill="#ff003c" opacity="0.35"/>
<rect x="467" y="100" width="34" height="14" rx="3" fill="#ff003c" opacity="0.3"/>
<rect x="505" y="100" width="34" height="14" rx="3" fill="#ff003c" opacity="0.35"/>
<!-- Paddle -->
<rect x="415" y="245" width="50" height="8" rx="4" fill="#ff003c" opacity="0.7" filter="url(#gR)">
<animate attributeName="x" values="415;445;415" dur="3s" repeatCount="indefinite"/>
</rect>
<!-- Ball -->
<circle cx="450" cy="160" r="4" fill="#ffffff" opacity="0.6" class="brk" filter="url(#gR)"/>
</g>
<!-- GAME 7: RACING -->
<g class="g7">
<text x="450" y="50" text-anchor="middle" fill="#ff003c" font-family="monospace" font-size="11" font-weight="bold" opacity="0.7" filter="url(#gR)">RACING</text>
<rect x="350" y="65" width="200" height="200" rx="4" fill="none" stroke="#ff003c" stroke-width="0.5" opacity="0.15"/>
<!-- Road -->
<rect x="390" y="65" width="120" height="200" fill="#ff003c" opacity="0.03"/>
<line x1="450" y1="65" x2="450" y2="265" stroke="#ff003c" stroke-width="0.3" opacity="0.08" stroke-dasharray="8 12"/>
<!-- Road dashes moving -->
<line x1="400" y1="70" x2="420" y2="70" stroke="#ff003c" stroke-width="1" opacity="0.2" class="race"/>
<line x1="480" y1="90" x2="500" y2="90" stroke="#ff003c" stroke-width="1" opacity="0.2" class="race" style="animation-delay:-0.2s"/>
<line x1="405" y1="120" x2="420" y2="120" stroke="#ff003c" stroke-width="1" opacity="0.15" class="race" style="animation-delay:-0.4s"/>
<line x1="485" y1="140" x2="495" y2="140" stroke="#ff003c" stroke-width="1" opacity="0.15" class="race" style="animation-delay:-0.1s"/>
<!-- Car 1 -->
<g>
<rect x="410" y="190" width="20" height="35" rx="4" fill="#ff003c" opacity="0.6" filter="url(#gR)">
<animate attributeName="y" values="190;130;190" dur="2.5s" repeatCount="indefinite"/>
</rect>
<rect x="414" y="195" width="12" height="10" rx="2" fill="#0a0a0a" opacity="0.5"/>
</g>
<!-- Car 2 -->
<g>
<rect x="470" y="140" width="18" height="30" rx="4" fill="#ff003c" opacity="0.35">
<animate attributeName="y" values="140;200;140" dur="3s" repeatCount="indefinite"/>
</rect>
<rect x="474" y="145" width="10" height="8" rx="2" fill="#0a0a0a" opacity="0.4"/>
</g>
<text x="460" y="253" fill="#ff003c" font-family="monospace" font-size="9" opacity="0.3">LAP 3/5</text>
</g>

<!-- GAME 8: PLATFORMER -->
<g class="g8">
<text x="450" y="50" text-anchor="middle" fill="#ff003c" font-family="monospace" font-size="11" font-weight="bold" opacity="0.7" filter="url(#gR)">PLATFORMER</text>
<rect x="320" y="65" width="260" height="200" rx="4" fill="none" stroke="#ff003c" stroke-width="0.5" opacity="0.15"/>
<!-- Ground -->
<line x1="320" y1="245" x2="580" y2="245" stroke="#ff003c" stroke-width="1" opacity="0.3"/>
<!-- Platform -->
<line x1="370" y1="180" x2="440" y2="180" stroke="#ff003c" stroke-width="1.5" opacity="0.2"/>
<!-- Obstacles -->
<rect x="500" y="225" width="15" height="20" rx="2" fill="#ff003c" opacity="0.25"/>
<circle cx="540" cy="225" r="10" fill="none" stroke="#ff003c" stroke-width="1" opacity="0.2"/>
<!-- Character running -->
<circle cx="360" cy="230" r="8" fill="#ff003c" opacity="0.7" class="plat" filter="url(#gR)">
<animate attributeName="cy" values="230;170;170;230;230" dur="2s" repeatCount="indefinite" keyTimes="0;0.3;0.5;0.8;1"/>
</circle>
<rect x="356" y="238" width="8" height="10" rx="2" fill="#ff003c" opacity="0.5" class="plat">
<animate attributeName="y" values="238;178;178;238;238" dur="2s" repeatCount="indefinite" keyTimes="0;0.3;0.5;0.8;1"/>
</rect>
<text x="530" y="40" fill="#ff003c" font-family="monospace" font-size="7" opacity="0.25">SCORE: 0420</text>
</g>

<!-- GAME 9: ASTEROIDS -->
<g class="g9">
<text x="450" y="50" text-anchor="middle" fill="#ff003c" font-family="monospace" font-size="11" font-weight="bold" opacity="0.7" filter="url(#gR)">ASTEROIDS</text>
<rect x="320" y="65" width="260" height="200" rx="4" fill="none" stroke="#ff003c" stroke-width="0.5" opacity="0.15"/>
<!-- Ship -->
<polygon points="450,200 440,225 460,225" fill="#ff003c" opacity="0.7" filter="url(#gR)">
<animate attributeName="points" values="450,200 440,225 460,225;450,200 435,230 465,230;450,200 440,225 460,225" dur="2s" repeatCount="indefinite"/>
</polygon>
<!-- Asteroids -->
<g class="ast" style="transform-origin:380px 120px">
<circle cx="380" cy="120" r="18" fill="none" stroke="#ff003c" stroke-width="1" opacity="0.35"/>
<circle cx="380" cy="120" r="12" fill="none" stroke="#ff003c" stroke-width="0.5" opacity="0.15"/>
<circle cx="380" cy="120" r="6" fill="#ff003c" opacity="0.1"/>
</g>
<g class="ast" style="transform-origin:540px 160px;animation-delay:-1s">
<circle cx="540" cy="160" r="14" fill="none" stroke="#ff003c" stroke-width="0.8" opacity="0.3"/>
<circle cx="540" cy="160" r="9" fill="none" stroke="#ff003c" stroke-width="0.5" opacity="0.12"/>
</g>
<g class="ast" style="transform-origin:350px 180px;animation-delay:-2s">
<circle cx="350" cy="180" r="10" fill="none" stroke="#ff003c" stroke-width="0.6" opacity="0.25"/>
</g>
<!-- Stars -->
<circle cx="340" cy="85" r="1" fill="#ffffff" opacity="0.3">
<animate attributeName="opacity" values="0.3;0.1;0.3" dur="2s" repeatCount="indefinite"/>
</circle>
<circle cx="500" cy="90" r="0.8" fill="#ffffff" opacity="0.2">
<animate attributeName="opacity" values="0.2;0.05;0.2" dur="3s" repeatCount="indefinite"/>
</circle>
<circle cx="560" cy="110" r="1.2" fill="#ffffff" opacity="0.25"/>
</g>

<!-- GAME 10: FIGHTER -->
<g class="g10">
<text x="450" y="50" text-anchor="middle" fill="#ff003c" font-family="monospace" font-size="11" font-weight="bold" opacity="0.7" filter="url(#gR)">FIGHTER</text>
<rect x="320" y="65" width="260" height="200" rx="4" fill="none" stroke="#ff003c" stroke-width="0.5" opacity="0.15"/>
<!-- Health bars -->
<rect x="340" y="75" width="80" height="8" rx="4" fill="#0a0a0a" stroke="#ff003c" stroke-width="0.3" opacity="0.2"/>
<rect x="340" y="75" width="65" height="8" rx="4" fill="#ff003c" opacity="0.5"/>
<text x="380" y="72" text-anchor="middle" fill="#ff003c" font-family="monospace" font-size="7" opacity="0.4">P1</text>
<rect x="480" y="75" width="80" height="8" rx="4" fill="#0a0a0a" stroke="#ff003c" stroke-width="0.3" opacity="0.2"/>
<rect x="495" y="75" width="65" height="8" rx="4" fill="#ff003c" opacity="0.35"/>
<text x="520" y="72" text-anchor="middle" fill="#ff003c" font-family="monospace" font-size="7" opacity="0.4">P2</text>
<!-- Fighter 1 -->
<g class="fgt">
<circle cx="380" cy="180" r="18" fill="none" stroke="#ff003c" stroke-width="1.5" opacity="0.5" filter="url(#gR)"/>
<circle cx="380" cy="180" r="12" fill="#ff003c" opacity="0.1"/>
<circle cx="380" cy="172" r="6" fill="#ff003c" opacity="0.4"/>
<rect x="374" y="190" width="12" height="18" rx="3" fill="#ff003c" opacity="0.35"/>
</g>
<!-- Fighter 2 -->
<g class="fgt" style="animation-delay:-0.7s">
<circle cx="520" cy="180" r="18" fill="none" stroke="#ff003c" stroke-width="1.5" opacity="0.35"/>
<circle cx="520" cy="180" r="12" fill="#ff003c" opacity="0.07"/>
<circle cx="520" cy="172" r="6" fill="#ff003c" opacity="0.25"/>
<rect x="514" y="190" width="12" height="18" rx="3" fill="#ff003c" opacity="0.2"/>
</g>
<!-- Impact flash -->
<circle cx="450" cy="170" r="0" fill="#ff003c" opacity="0">
<animate attributeName="r" values="0;15;0" dur="3s" repeatCount="indefinite" begin="0.8s"/>
<animate attributeName="opacity" values="0;0.4;0" dur="3s" repeatCount="indefinite" begin="0.8s"/>
</circle>
<text x="450" y="120" text-anchor="middle" fill="#ff003c" font-family="monospace" font-size="10" opacity="0">
<animate attributeName="opacity" values="0;0;0.6;0" dur="3s" repeatCount="indefinite" begin="0.5s"/>
HIT!</text>
</g>
<!-- GAME 11: DDR -->
<g class="g11">
<text x="450" y="50" text-anchor="middle" fill="#ff003c" font-family="monospace" font-size="11" font-weight="bold" opacity="0.7" filter="url(#gR)">DDR</text>
<rect x="350" y="65" width="200" height="200" rx="4" fill="none" stroke="#ff003c" stroke-width="0.5" opacity="0.15"/>
<!-- Target arrows -->
<polygon points="430,240 440,225 450,240" fill="none" stroke="#ff003c" stroke-width="1" opacity="0.3"/>
<polygon points="450,240 460,225 470,240" fill="none" stroke="#ff003c" stroke-width="1" opacity="0.3"/>
<polygon points="440,240 450,255 460,240" fill="none" stroke="#ff003c" stroke-width="1" opacity="0.3"/>
<!-- Scrolling arrows -->
<g class="ddr">
<text x="450" y="250" fill="#ff003c" font-family="monospace" font-size="16" text-anchor="middle" opacity="0.6">
<animate attributeName="y" values="280;65" dur="1.5s" repeatCount="indefinite"/>
&#9650;</text>
</g>
<g class="ddr" style="animation-delay:-0.5s">
<text x="450" y="250" fill="#ff003c" font-family="monospace" font-size="16" text-anchor="middle" opacity="0.4">
<animate attributeName="y" values="280;65" dur="1.5s" repeatCount="indefinite"/>
&#9660;</text>
</g>
<g class="ddr" style="animation-delay:-1s">
<text x="450" y="250" fill="#ff003c" font-family="monospace" font-size="16" text-anchor="middle" opacity="0.5">
<animate attributeName="y" values="280;65" dur="1.5s" repeatCount="indefinite"/>
&#9650;</text>
</g>
<g class="ddr" style="animation-delay:-0.3s">
<text x="450" y="250" fill="#ff003c" font-family="monospace" font-size="16" text-anchor="middle" opacity="0.35">
<animate attributeName="y" values="280;65" dur="1.5s" repeatCount="indefinite"/>
&#9660;</text>
</g>
<text x="460" y="253" fill="#ff003c" font-family="monospace" font-size="8" opacity="0.25">COMBO x12</text>
</g>

<!-- GAME 12: FLAPPY -->
<g class="g12">
<text x="450" y="50" text-anchor="middle" fill="#ff003c" font-family="monospace" font-size="11" font-weight="bold" opacity="0.7" filter="url(#gR)">FLAPPY</text>
<rect x="320" y="65" width="260" height="200" rx="4" fill="none" stroke="#ff003c" stroke-width="0.5" opacity="0.15"/>
<!-- Bird -->
<circle cx="370" cy="140" r="8" fill="#ff003c" opacity="0.7" class="flp" filter="url(#gR)"/>
<circle cx="375" cy="138" r="2" fill="#ffffff" opacity="0.5"/>
<line x1="378" y1="140" x2="384" y2="138" stroke="#ff003c" stroke-width="1.2" opacity="0.4"/>
<!-- Pipes -->
<g class="flpipe" style="animation-delay:0s">
<rect x="450" y="65" width="25" height="70" rx="3" fill="#ff003c" opacity="0.25"/>
<rect x="447" y="125" width="31" height="8" rx="3" fill="#ff003c" opacity="0.3"/>
<rect x="450" y="175" width="25" height="90" rx="3" fill="#ff003c" opacity="0.25"/>
<rect x="447" y="167" width="31" height="8" rx="3" fill="#ff003c" opacity="0.3"/>
</g>
<g class="flpipe" style="animation-delay:-1.5s">
<rect x="450" y="65" width="25" height="50" rx="3" fill="#ff003c" opacity="0.2"/>
<rect x="447" y="105" width="31" height="8" rx="3" fill="#ff003c" opacity="0.25"/>
<rect x="450" y="195" width="25" height="70" rx="3" fill="#ff003c" opacity="0.2"/>
<rect x="447" y="187" width="31" height="8" rx="3" fill="#ff003c" opacity="0.25"/>
</g>
<text x="530" y="45" fill="#ff003c" font-family="monospace" font-size="7" opacity="0.25">BEST: 042</text>
</g>

<!-- GAME 13: MAZE -->
<g class="g13">
<text x="450" y="50" text-anchor="middle" fill="#ff003c" font-family="monospace" font-size="11" font-weight="bold" opacity="0.7" filter="url(#gR)">MAZE</text>
<rect x="320" y="65" width="260" height="200" rx="4" fill="none" stroke="#ff003c" stroke-width="0.5" opacity="0.15"/>
<!-- Maze walls -->
<line x1="330" y1="80" x2="570" y2="80" stroke="#ff003c" stroke-width="1" opacity="0.2"/>
<line x1="330" y1="250" x2="570" y2="250" stroke="#ff003c" stroke-width="1" opacity="0.2"/>
<line x1="330" y1="80" x2="330" y2="150" stroke="#ff003c" stroke-width="1" opacity="0.15"/>
<line x1="570" y1="150" x2="570" y2="250" stroke="#ff003c" stroke-width="1" opacity="0.15"/>
<line x1="330" y1="150" x2="400" y2="150" stroke="#ff003c" stroke-width="1" opacity="0.15"/>
<line x1="500" y1="150" x2="570" y2="150" stroke="#ff003c" stroke-width="1" opacity="0.15"/>
<line x1="400" y1="150" x2="400" y2="200" stroke="#ff003c" stroke-width="1" opacity="0.12"/>
<line x1="500" y1="150" x2="500" y2="200" stroke="#ff003c" stroke-width="1" opacity="0.12"/>
<line x1="400" y1="200" x2="500" y2="200" stroke="#ff003c" stroke-width="1" opacity="0.15"/>
<line x1="330" y1="200" x2="360" y2="200" stroke="#ff003c" stroke-width="1" opacity="0.12"/>
<line x1="540" y1="200" x2="570" y2="200" stroke="#ff003c" stroke-width="1" opacity="0.12"/>
<line x1="360" y1="200" x2="360" y2="250" stroke="#ff003c" stroke-width="1" opacity="0.12"/>
<line x1="540" y1="200" x2="540" y2="250" stroke="#ff003c" stroke-width="1" opacity="0.12"/>
<!-- Start -->
<text x="345" y="95" fill="#ff003c" font-family="monospace" font-size="8" opacity="0.3">S</text>
<!-- End -->
<text x="555" y="238" fill="#ff003c" font-family="monospace" font-size="8" opacity="0.3">E</text>
<!-- Dot moving -->
<circle cx="340" cy="0" r="4" fill="#ff003c" opacity="0.7" class="mzd" filter="url(#gR)">
<animate attributeName="cx" values="340;440;440;340;340" dur="5s" repeatCount="indefinite"/>
<animate attributeName="cy" values="90;90;130;130;200" dur="5s" repeatCount="indefinite"/>
</circle>
</g>

<!-- GAME 14: SHOOTER -->
<g class="g14">
<text x="450" y="50" text-anchor="middle" fill="#ff003c" font-family="monospace" font-size="11" font-weight="bold" opacity="0.7" filter="url(#gR)">SHOOTER</text>
<rect x="320" y="65" width="260" height="200" rx="4" fill="none" stroke="#ff003c" stroke-width="0.5" opacity="0.15"/>
<!-- Targets -->
<circle cx="500" cy="120" r="15" fill="none" stroke="#ff003c" stroke-width="1.2" opacity="0.3">
<animate attributeName="cy" values="120;180;120" dur="2.5s" repeatCount="indefinite"/>
</circle>
<circle cx="500" cy="120" r="8" fill="none" stroke="#ff003c" stroke-width="0.8" opacity="0.2">
<animate attributeName="cy" values="120;180;120" dur="2.5s" repeatCount="indefinite"/>
</circle>
<circle cx="500" cy="120" r="3" fill="#ff003c" opacity="0.3">
<animate attributeName="cy" values="120;180;120" dur="2.5s" repeatCount="indefinite"/>
</circle>
<circle cx="520" cy="95" r="12" fill="none" stroke="#ff003c" stroke-width="1" opacity="0.2">
<animate attributeName="cy" values="95;155;95" dur="3s" repeatCount="indefinite"/>
</circle>
<circle cx="520" cy="95" r="5" fill="none" stroke="#ff003c" stroke-width="0.6" opacity="0.15">
<animate attributeName="cy" values="95;155;95" dur="3s" repeatCount="indefinite"/>
</circle>
<!-- Crosshair -->
<g class="shoot">
<line x1="390" y1="150" x2="410" y2="150" stroke="#ff003c" stroke-width="1" opacity="0.5" filter="url(#gR)"/>
<line x1="400" y1="140" x2="400" y2="160" stroke="#ff003c" stroke-width="1" opacity="0.5" filter="url(#gR)"/>
<circle cx="400" cy="150" r="12" fill="none" stroke="#ff003c" stroke-width="0.5" opacity="0.3"/>
</g>
<!-- Bullet trails -->
<line x1="410" y1="150" x2="490" y2="120" stroke="#ff003c" stroke-width="0.5" opacity="0">
<animate attributeName="opacity" values="0;0;0.4;0" dur="2s" repeatCount="indefinite" begin="0.3s"/>
</line>
<line x1="410" y1="150" x2="510" y2="95" stroke="#ff003c" stroke-width="0.5" opacity="0">
<animate attributeName="opacity" values="0;0;0.3;0" dur="2s" repeatCount="indefinite" begin="1.2s"/>
</line>
<!-- Score -->
<text x="460" y="253" fill="#ff003c" font-family="monospace" font-size="8" opacity="0.25">SCORE: 2850</text>
</g>

<!-- GAME 15: SNAKE II -->
<g class="g15">
<text x="450" y="50" text-anchor="middle" fill="#ff003c" font-family="monospace" font-size="11" font-weight="bold" opacity="0.7" filter="url(#gR)">SNAKE II</text>
<rect x="350" y="65" width="200" height="200" rx="4" fill="none" stroke="#ff003c" stroke-width="0.5" opacity="0.15"/>
<line x1="400" y1="65" x2="400" y2="265" stroke="#ff003c" stroke-width="0.2" opacity="0.06"/>
<line x1="450" y1="65" x2="450" y2="265" stroke="#ff003c" stroke-width="0.2" opacity="0.06"/>
<line x1="500" y1="65" x2="500" y2="265" stroke="#ff003c" stroke-width="0.2" opacity="0.06"/>
<line x1="350" y1="115" x2="550" y2="115" stroke="#ff003c" stroke-width="0.2" opacity="0.06"/>
<line x1="350" y1="165" x2="550" y2="165" stroke="#ff003c" stroke-width="0.2" opacity="0.06"/>
<line x1="350" y1="215" x2="550" y2="215" stroke="#ff003c" stroke-width="0.2" opacity="0.06"/>
<!-- Snake body (longer) -->
<rect x="440" y="165" width="10" height="10" fill="#ff003c" opacity="0.3" rx="2"/>
<rect x="440" y="175" width="10" height="10" fill="#ff003c" opacity="0.35" rx="2"/>
<rect x="440" y="185" width="10" height="10" fill="#ff003c" opacity="0.4" rx="2"/>
<rect x="440" y="195" width="10" height="10" fill="#ff003c" opacity="0.45" rx="2"/>
<rect x="440" y="205" width="10" height="10" fill="#ff003c" opacity="0.5" rx="2"/>
<rect x="440" y="215" width="10" height="10" fill="#ff003c" opacity="0.55" rx="2"/>
<rect x="440" y="225" width="10" height="10" fill="#ff003c" opacity="0.6" rx="2"/>
<rect x="440" y="235" width="10" height="10" fill="#ff003c" opacity="0.65" rx="2"/>
<!-- Head -->
<rect x="440" y="245" width="10" height="10" fill="#ff003c" opacity="0.95" rx="2" filter="url(#gR)">
<animate attributeName="x" values="440;470;470;470;470;440;440;440;440;390;390;390;390;440" dur="3.5s" repeatCount="indefinite"/>
<animate attributeName="y" values="245;245;195;145;95;95;145;195;245;245;195;145;95;95" dur="3.5s" repeatCount="indefinite"/>
</rect>
<!-- Food -->
<circle cx="390" cy="145" r="3" fill="#ffffff" opacity="0.5">
<animate attributeName="opacity" values="0.5;0.1;0.5" dur="0.6s" repeatCount="indefinite"/>
</circle>
<text x="460" y="253" fill="#ff003c" font-family="monospace" font-size="8" opacity="0.25">SCORE: 8</text>
</g>

</svg>

</div>

<br/>
<div align="center">

<svg viewBox="0 0 900 40" width="100%" xmlns="http://www.w3.org/2000/svg" style="max-width:900px;">
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
