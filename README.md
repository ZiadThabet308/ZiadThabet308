<!-- ===================== ULTRA STYLISH / ḤARF THEME ===================== -->

<!-- Animated Neon / Glitch SVG Header -->
<p align="center">
  <svg width="100%" height="240" viewBox="0 0 1200 240" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Ziad Thabet — Welcome to my World — Programmer is coming">
    <defs>
      <!-- Gradient -->
      <linearGradient id="g" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%"  stop-color="#ff0055">
          <animate attributeName="stop-color" values="#ff0055;#ffcc00;#00e5ff;#ff0055" dur="8s" repeatCount="indefinite"/>
        </stop>
        <stop offset="100%" stop-color="#00e5ff">
          <animate attributeName="stop-color" values="#00e5ff;#8aff00;#ff0055;#00e5ff" dur="8s" repeatCount="indefinite"/>
        </stop>
      </linearGradient>

      <!-- Neon Glow -->
      <filter id="neon" x="-50%" y="-50%" width="200%" height="200%">
        <feGaussianBlur stdDeviation="6" result="blur"/>
        <feMerge>
          <feMergeNode in="blur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>

      <!-- Glitch -->
      <filter id="glitch">
        <feTurbulence type="fractalNoise" baseFrequency="0.008" numOctaves="2" seed="2" result="noise"/>
        <feDisplacementMap in="SourceGraphic" in2="noise" scale="8" xChannelSelector="R" yChannelSelector="G">
          <animate attributeName="scale" values="0;10;0;8;0" dur="4s" repeatCount="indefinite"/>
        </feDisplacementMap>
      </filter>

      <!-- Scanline mask -->
      <pattern id="scan" width="4" height="4" patternUnits="userSpaceOnUse">
        <rect width="4" height="2" fill="rgba(255,255,255,0.06)"/>
      </pattern>
      <mask id="scanMask">
        <rect width="1200" height="240" fill="white"/>
        <rect width="1200" height="240" fill="url(#scan)">
          <animate attributeName="y" from="-240" to="240" dur="3.5s" repeatCount="indefinite"/>
        </rect>
      </mask>
    </defs>

    <!-- Border / Frame -->
    <rect x="10" y="10" width="1180" height="220" rx="24" ry="24" fill="rgba(10,12,16,0.85)" stroke="url(#g)" stroke-width="2" filter="url(#neon)"/>

    <!-- Title -->
    <g filter="url(#glitch)" mask="url(#scanMask)">
      <text x="50%" y="42%" text-anchor="middle" font-family="Poppins, Segoe UI, Roboto, sans-serif" font-size="52" font-weight="800" fill="url(#g)" letter-spacing="2">
        Ziad Thabet
      </text>
    </g>

    <!-- Taglines -->
    <text x="50%" y="65%" text-anchor="middle" font-family="JetBrains Mono, Consolas, monospace" font-size="22" fill="#e7e7e7" opacity="0.95">
      Welcome to my World • Programmer is coming
      <animate attributeName="opacity" values="0.6;1;0.6" dur="2.2s" repeatCount="indefinite"/>
    </text>

    <!-- Tech Strip -->
    <text x="50%" y="82%" text-anchor="middle" font-family="JetBrains Mono, Consolas, monospace" font-size="16" fill="#9ee7ff">
      Html • Css • Js
    </text>
  </svg>
</p>

<!-- Glassmorphism quick intro -->
<p align="center">
  <img src="https://img.shields.io/badge/STYLE-ULTRA%20NEON-ff0055?style=for-the-badge">
  <img src="https://img.shields.io/badge/FOCUS-FRONTEND-00e5ff?style=for-the-badge">
  <img src="https://komarev.com/ghpvc/?username=ZiadThabet308&style=for-the-badge&label=VISITS">
</p>

<!-- ===================== ABOUT / INTRO ===================== -->
<div align="center">
  <table>
    <tr>
      <td align="center" width="900" style="background: rgba(255,255,255,0.04); border-radius:16px; padding:18px;">
        <h3>✨ Welcome to my World</h3>
        <p><b>I'm Ziad Thabet</b> — Frontend dev turning wild ideas into clean, living interfaces.<br/>
        <i>Programmer is coming.</i></p>
      </td>
    </tr>
  </table>
</div>

<!-- ===================== STACK ===================== -->
<h3 align="center">⚙️ Stack</h3>
<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,vscode,git,github" />
</p>

<!-- Minimal animated divider -->
<p align="center">
  <img src="https://svg-banners.vercel.app/api?type=glitch&text1=Ziad%20Thabet&width=1000&height=100" alt="glitch banner"/>
</p>

<!-- ===================== HIGHLIGHTS ===================== -->
<div align="center">
  <table>
    <tr>
      <td width="300" align="center">
        <h4>🎨 Micro-UIs</h4>
        <sub>Neon / Glass / Motion</sub>
      </td>
      <td width="300" align="center">
        <h4>⚡ Performance</h4>
        <sub>Clean, fast, sharp</sub>
      </td>
      <td width="300" align="center">
        <h4>🧠 Craft</h4>
        <sub>Details > Everything</sub>
      </td>
    </tr>
  </table>
</div>

<!-- ===================== STATS ===================== -->
<h3 align="center">📊 Stats</h3>
<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=ZiadThabet308&show_icons=true&hide_border=true&theme=tokyonight&bg_color=0d1117"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ZiadThabet308&layout=compact&hide_border=true&theme=tokyonight&bg_color=0d1117"/>
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com?user=ZiadThabet308&theme=highcontrast&hide_border=true" />
</p>

<!-- ===================== CTA / LINKS ===================== -->
<h3 align="center">🌐 Links</h3>
<p align="center">
  <a href="https://github.com/ZiadThabet308">
    <img src="https://img.shields.io/badge/GitHub-ZiadThabet308-111?style=for-the-badge&logo=github">
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/Portfolio-Coming%20Soon-ff0055?style=for-the-badge">
  </a>
</p>

<!-- ===================== FOOTER WAVE ===================== -->
<img src="https://capsule-render.vercel.app/api?type=waving&height=140&section=footer&color=gradient"/>
