<!-- ========================= ULTRA WAR-ZONE PROFILE (FINAL) ========================= -->
<!-- انسخ الملف دا كامل في README.md في ريبُو باسم: ZiadThabet308 -->

<!-- ================= HEADER: NEON GLITCH EXPLOSION SVG ================= -->
<p align="center">
  <!-- عرض SVG مصنع مخصوص: نيـون + غليتش + دخان + انفجار -->
  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 360" width="100%" height="360" role="img" aria-label="Ziad Thabet — WAR THEME">
    <defs>
      <!-- animated gradient -->
      <linearGradient id="g1" x1="0" x2="1">
        <stop offset="0%" stop-color="#ff2d55">
          <animate attributeName="stop-color" dur="6s" values="#ff2d55;#ff9a00;#00e5ff;#9b5cff;#ff2d55" repeatCount="indefinite"/>
        </stop>
        <stop offset="100%" stop-color="#00e5ff">
          <animate attributeName="stop-color" dur="6s" values="#00e5ff;#9bff6a;#ff2d55;#9b5cff;#00e5ff" repeatCount="indefinite"/>
        </stop>
      </linearGradient>

      <!-- neon glow filter -->
      <filter id="neon" x="-200%" y="-200%" width="400%" height="400%">
        <feGaussianBlur stdDeviation="6" result="b"/>
        <feMerge>
          <feMergeNode in="b"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>

      <!-- smoke using turbulence -->
      <filter id="smoke">
        <feTurbulence baseFrequency="0.012" numOctaves="3" seed="8" result="t"/>
        <feDisplacementMap in="SourceGraphic" in2="t" scale="20"/>
        <feGaussianBlur stdDeviation="10"/>
        <feComponentTransfer>
          <feFuncA type="table" tableValues="0 0.35 0.6 0.9"/>
        </feComponentTransfer>
      </filter>

      <!-- glitch displacement -->
      <filter id="glitch">
        <feTurbulence baseFrequency="0.02" numOctaves="1" seed="3" result="n"/>
        <feDisplacementMap in="SourceGraphic" in2="n" scale="6">
          <animate attributeName="scale" dur="2.2s" values="0;8;0;6;0" repeatCount="indefinite"/>
        </feDisplacementMap>
      </filter>

      <!-- scanlines -->
      <pattern id="scan" width="4" height="4" patternUnits="userSpaceOnUse">
        <rect width="4" height="2" fill="rgba(255,255,255,0.03)"/>
      </pattern>
    </defs>

    <!-- background dark rectangle -->
    <rect width="1200" height="360" rx="20" fill="#04060a"/>

    <!-- layered animated explosion blobs -->
    <g transform="translate(100,80)">
      <g opacity="0.6" filter="url(#smoke)">
        <circle cx="480" cy="80" r="36" fill="url(#g1)">
          <animate attributeName="r" dur="6s" values="24;48;30;42;24" repeatCount="indefinite"/>
          <animate attributeName="opacity" dur="6s" values="0.6;0.95;0.5;0.8;0.6" repeatCount="indefinite"/>
        </circle>
      </g>
      <g opacity="0.35" filter="url(#smoke)">
        <circle cx="420" cy="120" r="24" fill="#ff9a00">
          <animate attributeName="r" dur="5s" values="18;34;22;30;18" repeatCount="indefinite"/>
        </circle>
      </g>
    </g>

    <!-- main neon title with glitch group -->
    <g filter="url(#glitch)">
      <text x="50%" y="40%" text-anchor="middle" font-family="Poppins, Inter, system-ui, sans-serif" font-size="56" font-weight="900" fill="url(#g1)" style="letter-spacing:2px">
        Ziad Thabet
      </text>
    </g>

    <!-- subtitle / tagline -->
    <text x="50%" y="58%" text-anchor="middle" font-family="JetBrains Mono, monospace" font-size="18" fill="#dfefff" opacity="0.95">
      <tspan>Welcome to my World</tspan>
      <tspan dx="12" fill="#ffcc66"> • </tspan>
      <tspan>Programmer is coming</tspan>
      <animate attributeName="opacity" dur="2.4s" values="0.6;1;0.6" repeatCount="indefinite"/>
    </text>

    <!-- skills strip -->
    <rect x="360" y="220" width="480" height="38" rx="20" fill="rgba(255,255,255,0.02)" stroke="url(#g1)" stroke-width="1.2" filter="url(#neon)"/>
    <text x="50%" y="245" text-anchor="middle" font-family="JetBrains Mono, monospace" font-size="14" fill="#9ee7ff">Html • Css • Js</text>

    <!-- matrix rain overlay (subtle) -->
    <g opacity="0.06" font-family="monospace" font-size="12" fill="#00ff88">
      <text x="10" y="40">
        <tspan>▮▯▮▯▯▮▯▯▮▯▮▯▮</tspan>
        <animateTransform attributeName="transform" type="translate" from="0 -20" to="0 260" dur="6s" repeatCount="indefinite"/>
      </text>
      <text x="1160" y="40">
        <tspan>▯▮▯▯▮▮▯▮▯▯▮▯▮</tspan>
        <animateTransform attributeName="transform" type="translate" from="0 -40" to="0 260" dur="8s" repeatCount="indefinite"/>
      </text>
    </g>
  </svg>
</p>

<!-- ================= BADGES ================= -->
<p align="center">
  <img src="https://img.shields.io/badge/STYLE-WAR%20NEON-critical?style=for-the-badge&logo=ghost" alt="style"/>
  <img src="https://img.shields.io/badge/FOCUS-FRONTEND-00e5ff?style=for-the-badge" alt="focus"/>
  <img src="https://komarev.com/ghpvc/?username=ZiadThabet308&label=VISITS&style=for-the-badge" alt="visits"/>
</p>

<!-- ================= ASCII WAR LOGO ================= -->
<p align="center">
<pre style="line-height:0.7;margin:0;padding:6px;background:#020204;border-radius:10px;color:#9ff6ff;font-weight:700;">

</pre>
</p>

<!-- ================= ABOUT (glass block) ================= -->
<div align="center">
  <table style="background: rgba(255,255,255,0.03); border-radius:14px; padding:14px; width:90%; max-width:980px;">
    <tr>
      <td style="padding:12px; vertical-align:middle;">
        <h3 style="margin:4px 0 6px 0;">⚔️ About — الحرب الفنية</h3>
        <p style="margin:0;color:#dfeeff;">
          أنا <b>Ziad Thabet</b>. أعمل Frontend — بحوّل أفكار مجنونة لمكونات UI بتتحرك وتصفع العين.  
          <i>Welcome to my World — Programmer is coming.</i>
        </p>
      </td>
      <td style="width:180px; text-align:center;">
        <img src="https://media.giphy.com/media/3oEjI6SIIHBdRxXI40/giphy.gif" alt="explosion" width="160" style="border-radius:10px;"/>
      </td>
    </tr>
  </table>
</div>

<!-- ================= STACK (weapons) ================= -->
<h3 align="center">🛠️ Armory — Tech</h3>
<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,git,github,vscode" alt="skills" />
</p>

<!-- ================= DYNAMIC STATS (neon) ================= -->
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ZiadThabet308&show_icons=true&theme=dracula&hide_border=true&count_private=true" alt="stats" height="150"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ZiadThabet308&layout=compact&theme=dracula&hide_border=true" alt="langs" height="150"/>
</p>

<!-- ================= SNAKE (auto-generated asset) ================= -->
<p align="center">
  <!-- لو عملت GitHub Action لانتاج الـ snake SVG هيظهر هنا -->
  <img src="output/github-contribution-grid-snake.svg" alt="snake contributions" style="max-width:720px;width:100%;border-radius:8px;"/>
</p>

<!-- ================= HIGHLIGHTS CARDS ================= -->
<div align="center">
  <table style="width:100%;max-width:980px;">
    <tr>
      <td style="text-align:center;padding:12px;">
        <div style="background:linear-gradient(135deg, rgba(255,45,85,0.08), rgba(0,229,255,0.04));padding:18px;border-radius:12px;">
          <h4 style="margin:6px 0;">🎮 Micro-UIs</h4>
          <p style="margin:4px 0;color:#cfefff;">Neon HUDs — Glass — Motion</p>
        </div>
      </td>
      <td style="text-align:center;padding:12px;">
        <div style="background:linear-gradient(135deg, rgba(155,95,255,0.06), rgba(255,154,0,0.03));padding:18px;border-radius:12px;">
          <h4 style="margin:6px 0;">⚡ Performance</h4>
          <p style="margin:4px 0;color:#cfefff;">Clean & lightning fast</p>
        </div>
      </td>
      <td style="text-align:center;padding:12px;">
        <div style="background:linear-gradient(135deg, rgba(155,255,106,0.06), rgba(0,229,255,0.03));padding:18px;border-radius:12px;">
          <h4 style="margin:6px 0;">🧠 Craft</h4>
          <p style="margin:4px 0;color:#cfefff;">Pixel-perfect details</p>
        </div>
      </td>
    </tr>
  </table>
</div>

<!-- ================= CTA / CONTACT (NUCLEAR BUTTON) ================= -->
<p align="center">
  <a href="https://github.com/ZiadThabet308" style="text-decoration:none;">
    <img src="https://img.shields.io/badge/ENTER_THE_ARENA-Nuclear%20Contact-ff0055?style=for-the-badge&logo=github" alt="enter"/>
  </a>
</p>

<!-- ================= FOOTER WAVE (neon) ================= -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=100&section=footer&color=gradient" width="100%" alt="wave"/>
</p>

<!-- ================= NOTES: how to make it fully UNIQUE ================= -->
<!--
  1) للحظة "لا يوجد مثلها في الكون" فعلاً: لو عايز أحوّل ال SVG لبانر مخصص حرفيًا باسمك (خطوط مخصصة + أشكال يدوية) أقدر أرسلك ملف SVG واحد مفرود قابل للتعديل. 
  2) لو عايز تأثير Snake حقيقي لازم تشغّل GitHub Action اللي يولّد output/github-contribution-grid-snake.svg (قلّي لو عايز أديك الـ workflow). 
  3) لو حابب لون مختلف (Matrix green, Cyberpunk purple, Black-gold) أعدّل الـ gradients في نفس الملف فوراً.
  4) انسخ الملف بالكامل وحطه في README.md. الصور/GIFs المضمنة موجودة من الإنترنت، تقدر تستبدل برابط GIF خاص لو عايز شيء أندر.
-->
