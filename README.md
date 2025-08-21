<p align="center">
  <!-- Hero SVG Animation -->
  <svg width="100%" height="300" viewBox="0 0 1200 300">
    <defs>
      <!-- Gradient for Neon Text -->
      <linearGradient id="grad1" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" style="stop-color:#00ffff;stop-opacity:1" />
        <stop offset="50%" style="stop-color:#ff00ff;stop-opacity:1" />
        <stop offset="100%" style="stop-color:#ffff00;stop-opacity:1" />
      </linearGradient>

      <!-- Glow Effect -->
      <filter id="glow">
        <feGaussianBlur stdDeviation="4.5" result="blur"/>
        <feMerge>
          <feMergeNode in="blur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
    </defs>

    <!-- Ziad Thabet Neon -->
    <text x="50%" y="40%" text-anchor="middle" font-size="60" font-family="monospace"
          fill="url(#grad1)" filter="url(#glow)">
      Ziad Thabet
      <animate attributeName="y" values="120;110;120" dur="1s" repeatCount="indefinite"/>
    </text>

    <!-- Welcome to my World -->
    <text x="50%" y="60%" text-anchor="middle" font-size="40" font-family="monospace"
          fill="url(#grad1)" filter="url(#glow)">
      Welcome to my World
      <animate attributeName="x" values="600;590;600" dur="1s" repeatCount="indefinite"/>
    </text>

    <!-- Programmer is coming -->
    <text x="50%" y="80%" text-anchor="middle" font-size="35" font-family="monospace"
          fill="url(#grad1)" filter="url(#glow)">
      Programmer is coming
      <animate attributeName="y" values="180;170;180" dur="1s" repeatCount="indefinite"/>
    </text>

    <!-- Spark Particles -->
    <circle cx="100" cy="50" r="3" fill="#0ff">
      <animateTransform attributeName="transform" type="translate" values="0,0;1100,250" dur="3s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="1;0" dur="3s" repeatCount="indefinite"/>
    </circle>

    <circle cx="200" cy="100" r="2" fill="#ff0">
      <animateTransform attributeName="transform" type="translate" values="0,0;900,200" dur="4s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="1;0" dur="4s" repeatCount="indefinite"/>
    </circle>

    <circle cx="300" cy="150" r="4" fill="#f0f">
      <animateTransform attributeName="transform" type="translate" values="0,0;800,300" dur="5s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="1;0" dur="5s" repeatCount="indefinite"/>
    </circle>
  </svg>
</p>

<p align="center" style="font-size:18px; color:#fff; text-shadow:0 0 5px #0ff,0 0 10px #f0f;">
  <strong>المجالات:</strong> Html | Css | Js
</p>

<p align="center">
  <!-- Badges -->
  <img src="https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
</p>

<p align="center" style="font-size:20px; color:#0ff; text-shadow:0 0 10px #0ff, 0 0 20px #f0f, 0 0 30px #ff0;">
  أكبر وأعظم README في تاريخ البشرية 💥🔥
</p>
