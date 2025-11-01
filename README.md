<!-- 🌟 Animated Gradient Header -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="banner-dark.png">
    <source media="(prefers-color-scheme: light)" srcset="banner-light.png">
    <img alt="Anubhav Sachan Banner" src="banner-light.png" width="100%">
  </picture>
</p>

<h1 align="center">
  <svg viewBox="0 0 800 120" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <!-- Gradient for Light Mode -->
      <linearGradient id="gradientLight" x1="0" y1="0" x2="1" y2="1">
        <stop offset="0%" stop-color="#7B68EE">
          <animate attributeName="stop-color" values="#7B68EE;#8B5CF6;#9F7AEA;#7B68EE" dur="6s" repeatCount="indefinite" />
        </stop>
        <stop offset="100%" stop-color="#00BFFF">
          <animate attributeName="stop-color" values="#00BFFF;#8B5CF6;#00BFFF" dur="6s" repeatCount="indefinite" />
        </stop>
      </linearGradient>

      <!-- Gradient for Dark Mode -->
      <linearGradient id="gradientDark" x1="0" y1="0" x2="1" y2="1">
        <stop offset="0%" stop-color="#C084FC">
          <animate attributeName="stop-color" values="#C084FC;#8B5CF6;#C084FC" dur="6s" repeatCount="indefinite" />
        </stop>
        <stop offset="100%" stop-color="#60A5FA">
          <animate attributeName="stop-color" values="#60A5FA;#C084FC;#60A5FA" dur="6s" repeatCount="indefinite" />
        </stop>
      </linearGradient>

      <!-- Soft Glow Filter -->
      <filter id="glow">
        <feGaussianBlur stdDeviation="3.5" result="coloredBlur"/>
        <feMerge>
          <feMergeNode in="coloredBlur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
    </defs>

    <!-- Text (Light + Dark Mode Responsive) -->
    <text id="glowText"
          x="50%" y="70%" text-anchor="middle"
          font-size="50" font-weight="700"
          font-family="Poppins, sans-serif"
          fill="url(#gradientLight)" 
          filter="url(#glow)">
      Anubhav Sachan
    </text>

    <style>
      @media (prefers-color-scheme: dark) {
        #glowText {
          fill: url(#gradientDark);
        }
      }
    </style>
  </svg>
</h1>

<p align="center">
  <b>Frontend Developer | Designer | Video Editor</b>
</p>
