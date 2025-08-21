<p align="center">
  <svg width="100%" height="300" viewBox="0 0 1200 300">
    <defs>
      <linearGradient id="grad1" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" style="stop-color:#00ffff;stop-opacity:1" />
        <stop offset="50%" style="stop-color:#ff00ff;stop-opacity:1" />
        <stop offset="100%" style="stop-color:#ffff00;stop-opacity:1" />
      </linearGradient>
      <filter id="glow">
        <feGaussianBlur stdDeviation="4.5" result="blur"/>
        <feMerge>
          <feMergeNode in="blur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
    </defs>

    <text x="50%" y="50%" text-anchor="middle" font-size="60" font-family="monospace"
          fill="url(#grad1)" filter="url(#glow)">
      Ziad Thabet
      <animate attributeName="y" values="150;140;150" dur="1s" repeatCount="indefinite"/>
    </text>

    <text x="50%" y="80%" text-anchor="middle" font-size="40" font-family="monospace"
          fill="url(#grad1)" filter="url(#glow)">
      Welcome to my World
      <animate attributeName="x" values="600;590;600" dur="1s" repeatCount="indefinite"/>
    </text>
  </svg>
</p>
