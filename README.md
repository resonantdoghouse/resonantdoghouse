# Hi 👋, I'm Jim Bennett 🐱

## Developer/CatDad from Vancouver Canada

<img src="./images/moss.gif" />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/resonantdoghouse/resonantdoghouse/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/resonantdoghouse/resonantdoghouse/output/github-contribution-grid-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/resonantdoghouse/resonantdoghouse/output/github-contribution-grid-snake.svg" />
</picture>

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/jim-bennett" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="jim-bennett" height="30" width="40" /></a>
</p>



<!DOCTYPE html>
<html>
<head>
  <style>
    body {
      margin: 0;
      background-color: #0d1117; /* GitHub Dark Background */
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      overflow: hidden;
    }

    .canvas {
      width: 850px;
      height: 400px;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    /* --- COLOR PALETTE --- */
    :root {
      --gh-bg: #0d1117;
      --gh-green: #2ea043;
      --gh-blue: #58a6ff;
      --gh-purple: #bc8cff;
      --gh-grey: #30363d;
      --gh-text: #c9d1d9;
    }

    /* --- HARMONIC RHYTHMS --- */
    /* All durations are multiples of 3 to ensure a perfect loop */
    
    @keyframes spin-slow {
      0% { transform: rotate(0deg); }
      100% { transform: rotate(360deg); }
    }

    @keyframes spin-slow-reverse {
      0% { transform: rotate(360deg); }
      100% { transform: rotate(0deg); }
    }

    @keyframes breathe-deep {
      0%, 100% { transform: scale(1); opacity: 0.5; }
      50% { transform: scale(1.1); opacity: 0.8; }
    }

    @keyframes breathe-sharp {
      0%, 100% { transform: scale(0.8) rotate(0deg); opacity: 0.4; }
      50% { transform: scale(1.2) rotate(180deg); opacity: 0.9; }
    }

    @keyframes pulse-code {
      0%, 100% { transform: scale(1); opacity: 1; }
      50% { transform: scale(1.3); opacity: 0.7; }
    }

    /* --- UTILITY CLASSES --- */
    
    .anchor-center {
      transform-origin: center;
    }

    /* Layer 1: The Background Grid/Cosmos */
    .cosmos-ring {
      fill: none;
      stroke: var(--gh-grey);
      stroke-width: 1;
      stroke-dasharray: 4 8;
      opacity: 0.3;
      animation: spin-slow 60s linear infinite;
    }

    /* Layer 2: The Merkaba (Star of David) - Structure */
    .triangle-up {
      fill: none;
      stroke: var(--gh-blue);
      stroke-width: 1.5;
      animation: spin-slow 24s linear infinite;
    }
    
    .triangle-down {
      fill: none;
      stroke: var(--gh-purple);
      stroke-width: 1.5;
      animation: spin-slow 24s linear infinite; /* Synced with Up */
    }

    /* Layer 3: The Nature/Hexagon Core */
    .hex-core {
      fill: none;
      stroke: var(--gh-green);
      stroke-width: 2;
      animation: breathe-deep 6s ease-in-out infinite;
    }

    /* Layer 4: Satellite Shapes (Variation) */
    .satellite-square {
      fill: none;
      stroke: var(--gh-text);
      stroke-width: 1;
      opacity: 0.3;
      animation: breathe-sharp 12s ease-in-out infinite;
      transform-origin: center;
    }

    .satellite-circle {
      fill: none;
      stroke: var(--gh-blue);
      stroke-width: 1;
      stroke-dasharray: 2 4;
      animation: spin-slow-reverse 12s linear infinite;
    }

    /* Code Typography */
    .code-text {
      font-family: 'Courier New', monospace;
      font-weight: bold;
      font-size: 14px;
      fill: var(--gh-text);
      text-anchor: middle;
      dominant-baseline: middle;
    }

    /* Groups */
    .group-rotate-cw { animation: spin-slow 36s linear infinite; }
    .group-rotate-ccw { animation: spin-slow-reverse 36s linear infinite; }
    
  </style>
</head>
<body>

  <div class="canvas">
    <svg width="800" height="400" viewBox="0 0 800 400">
      
      <!-- === BACKGROUND GEOMETRY (Static Symmetry) === -->
      <!-- Left Side Decor -->
      <g transform="translate(150, 200)">
        <rect x="-40" y="-40" width="80" height="80" class="satellite-square" stroke="#bc8cff" />
        <circle r="30" class="satellite-circle" />
        <text x="0" y="0" class="code-text" style="opacity:0.5;">!=</text>
      </g>

      <!-- Right Side Decor -->
      <g transform="translate(650, 200)">
        <circle r="50" fill="none" stroke="#30363d" stroke-dasharray="1 5" style="animation: spin-slow 12s linear infinite" />
        <polygon points="0,-30 26,15 -26,15" fill="none" stroke="#58a6ff" opacity="0.4" style="animation: breathe-sharp 6s infinite" />
        <text x="0" y="0" class="code-text" style="opacity:0.5;">[]</text>
      </g>

      <!-- === CENTER COSMOMETRY MANDALA (The Main Event) === -->
      <g transform="translate(400, 200)">
        
        <!-- 1. The Event Horizon (Outer Ring) -->
        <circle r="160" class="cosmos-ring" />
        <circle r="150" class="cosmos-ring" style="animation-duration: 40s; opacity: 0.2; stroke-dasharray: 2 10;" />

        <!-- 2. The Merkaba (Interlocking Triangles) -->
        <!-- Rotating Group -->
        <g class="group-rotate-cw">
          <polygon points="0,-100 86.6,50 -86.6,50" class="triangle-up" />
          <polygon points="0,100 -86.6,-50 86.6,-50" class="triangle-down" />
        </g>

        <!-- 3. The Inner Code Hexagon -->
        <!-- This breathes (scales) rather than rotates, anchoring the center -->
        <g style="animation: breathe-deep 6s ease-in-out infinite;">
          <polygon points="0,-60 52,-30 52,30 0,60 -52,30 -52,-30" class="hex-core" />
          
          <!-- Code Symbols at Hexagon Vertices -->
          <!-- We group them to rotate WITH the hexagon if we wanted, but here they stay fixed relative to the breathing shape -->
          <text x="0" y="-75" class="code-text" style="fill: #bc8cff;">01</text>
          <text x="0" y="75" class="code-text" style="fill: #bc8cff;">10</text>
          <text x="-65" y="-35" class="code-text" style="fill: #2ea043;">{</text>
          <text x="65" y="-35" class="code-text" style="fill: #2ea043;">}</text>
          <text x="-65" y="35" class="code-text" style="fill: #58a6ff;">&lt;</text>
          <text x="65" y="35" class="code-text" style="fill: #58a6ff;">&gt;</text>
        </g>

        <!-- 4. The Center Singularity -->
        <g style="animation: spin-slow-reverse 12s linear infinite;">
          <rect x="-15" y="-15" width="30" height="30" fill="none" stroke="#c9d1d9" stroke-width="2" />
        </g>
        <circle r="5" fill="#2ea043" style="animation: pulse-code 3s ease-in-out infinite;" />

      </g> <!-- End Center -->

      <!-- === CONNECTING LINES (Subtle Geometric Web) === -->
      <!-- These lines just fade in/out to suggest connections without moving -->
      <line x1="250" y1="200" x2="300" y2="200" stroke="#30363d" stroke-width="1">
        <animate attributeName="opacity" values="0;0.5;0" dur="6s" repeatCount="indefinite" />
      </line>
      <line x1="500" y1="200" x2="550" y2="200" stroke="#30363d" stroke-width="1">
        <animate attributeName="opacity" values="0;0.5;0" dur="6s" begin="3s" repeatCount="indefinite" />
      </line>

    </svg>
  </div>

</body>
</html>
