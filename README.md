<svg width="1000" height="180" viewBox="0 0 1000 180" xmlns="http://www.w3.org/2000/svg">

  <defs>
    <linearGradient id="blue" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#07182d"/>
      <stop offset="100%" stop-color="#087cff"/>
    </linearGradient>

    <filter id="glow">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- C++ -->
  <g filter="url(#glow)">
    <polygon
      points="0,10 150,10 135,70 0,70"
      fill="url(#blue)"
      stroke="#1683ff"
      stroke-width="2"/>
    <text x="75" y="47"
          text-anchor="middle"
          fill="white"
          font-family="Arial"
          font-size="18"
          font-weight="bold">
      C++
    </text>
  </g>

  <!-- JavaScript -->
  <g filter="url(#glow)">
    <polygon
      points="165,10 315,10 300,70 165,70"
      fill="url(#blue)"
      stroke="#1683ff"
      stroke-width="2"/>
    <text x="240" y="47"
          text-anchor="middle"
          fill="white"
          font-family="Arial"
          font-size="18"
          font-weight="bold">
      JavaScript
    </text>
  </g>

  <!-- TypeScript -->
  <g filter="url(#glow)">
    <polygon
      points="330,10 480,10 465,70 330,70"
      fill="url(#blue)"
      stroke="#1683ff"
      stroke-width="2"/>
    <text x="405" y="47"
          text-anchor="middle"
          fill="white"
          font-family="Arial"
          font-size="18"
          font-weight="bold">
      TypeScript
    </text>
  </g>

  <!-- React -->
  <g filter="url(#glow)">
    <polygon
      points="495,10 645,10 630,70 495,70"
      fill="url(#blue)"
      stroke="#1683ff"
      stroke-width="2"/>
    <text x="570" y="47"
          text-anchor="middle"
          fill="white"
          font-family="Arial"
          font-size="18"
          font-weight="bold">
      React
    </text>
  </g>

  <!-- Next.js -->
  <g filter="url(#glow)">
    <polygon
      points="660,10 810,10 795,70 660,70"
      fill="url(#blue)"
      stroke="#1683ff"
      stroke-width="2"/>
    <text x="735" y="47"
          text-anchor="middle"
          fill="white"
          font-family="Arial"
          font-size="18"
          font-weight="bold">
      Next.js
    </text>
  </g>

  <!-- Backend -->
  <g filter="url(#glow)">
    <polygon
      points="825,10 975,10 960,70 825,70"
      fill="url(#blue)"
      stroke="#1683ff"
      stroke-width="2"/>
    <text x="900" y="47"
          text-anchor="middle"
          fill="white"
          font-family="Arial"
          font-size="18"
          font-weight="bold">
      Backend
    </text>
  </g>

  <!-- Reverse Engineering -->
  <g filter="url(#glow)">
    <polygon
      points="165,90 400,90 385,150 165,150"
      fill="url(#blue)"
      stroke="#1683ff"
      stroke-width="2"/>
    <text x="282" y="127"
          text-anchor="middle"
          fill="white"
          font-family="Arial"
          font-size="17"
          font-weight="bold">
      Reverse Engineering
    </text>
  </g>

  <!-- API -->
  <g filter="url(#glow)">
    <polygon
      points="415,90 565,90 550,150 415,150"
      fill="url(#blue)"
      stroke="#1683ff"
      stroke-width="2"/>
    <text x="490" y="127"
          text-anchor="middle"
          fill="white"
          font-family="Arial"
          font-size="18"
          font-weight="bold">
      API
    </text>
  </g>

  <!-- Git -->
  <g filter="url(#glow)">
    <polygon
      points="580,90 730,90 715,150 580,150"
      fill="url(#blue)"
      stroke="#1683ff"
      stroke-width="2"/>
    <text x="655" y="127"
          text-anchor="middle"
          fill="white"
          font-family="Arial"
          font-size="18"
          font-weight="bold">
      Git
    </text>
  </g>

</svg>
