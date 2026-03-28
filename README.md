<svg viewBox="0 0 840 520" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <clipPath id="c1"><rect x="0" y="-16" height="28" width="0">
      <animate attributeName="width" dur="14s" repeatCount="indefinite" calcMode="discrete"
        values="0; 30; 60; 90; 90; 0"
        keyTimes="0; 0.03; 0.05; 0.07; 0.09; 0.90"/>
    </rect></clipPath>

    <clipPath id="c2"><rect x="0" y="-16" height="28" width="0">
      <animate attributeName="width" dur="14s" repeatCount="indefinite" calcMode="discrete"
        values="0; 400; 0"
        keyTimes="0; 0.10; 0.90"/>
    </rect></clipPath>

    <clipPath id="c3"><rect x="0" y="-16" height="28" width="0">
      <animate attributeName="width" dur="14s" repeatCount="indefinite" calcMode="discrete"
        values="0; 50; 100; 150; 150; 0"
        keyTimes="0; 0.15; 0.17; 0.19; 0.21; 0.90"/>
    </rect></clipPath>

    <clipPath id="c4"><rect x="0" y="-16" height="28" width="0">
      <animate attributeName="width" dur="14s" repeatCount="indefinite" calcMode="discrete"
        values="0; 380; 0"
        keyTimes="0; 0.22; 0.90"/>
    </rect></clipPath>

    <clipPath id="c5"><rect x="0" y="-16" height="28" width="0">
      <animate attributeName="width" dur="14s" repeatCount="indefinite" calcMode="discrete"
        values="0; 48; 96; 145; 145; 0"
        keyTimes="0; 0.27; 0.29; 0.31; 0.33; 0.90"/>
    </rect></clipPath>

    <clipPath id="c6"><rect x="0" y="-16" height="28" width="0">
      <animate attributeName="width" dur="14s" repeatCount="indefinite" calcMode="discrete"
        values="0; 400; 0"
        keyTimes="0; 0.34; 0.90"/>
    </rect></clipPath>

    <clipPath id="c7"><rect x="0" y="-16" height="28" width="0">
      <animate attributeName="width" dur="14s" repeatCount="indefinite" calcMode="discrete"
        values="0; 300; 0"
        keyTimes="0; 0.34; 0.90"/>
    </rect></clipPath>

    <clipPath id="c8"><rect x="0" y="-16" height="28" width="0">
      <animate attributeName="width" dur="14s" repeatCount="indefinite" calcMode="discrete"
        values="0; 52; 104; 155; 155; 0"
        keyTimes="0; 0.40; 0.42; 0.44; 0.46; 0.90"/>
    </rect></clipPath>

    <clipPath id="c9"><rect x="0" y="-16" height="28" width="0">
      <animate attributeName="width" dur="14s" repeatCount="indefinite" calcMode="discrete"
        values="0; 420; 0"
        keyTimes="0; 0.47; 0.90"/>
    </rect></clipPath>

    <clipPath id="c10"><rect x="0" y="-16" height="28" width="0">
      <animate attributeName="width" dur="14s" repeatCount="indefinite" calcMode="discrete"
        values="0; 30; 60; 60; 0"
        keyTimes="0; 0.53; 0.55; 0.57; 0.90"/>
    </rect></clipPath>

    <clipPath id="c11"><rect x="0" y="-16" height="28" width="0">
      <animate attributeName="width" dur="14s" repeatCount="indefinite" calcMode="discrete"
        values="0; 350; 0"
        keyTimes="0; 0.58; 0.90"/>
    </rect></clipPath>

    <clipPath id="c12"><rect x="0" y="-16" height="28" width="0">
      <animate attributeName="width" dur="14s" repeatCount="indefinite" calcMode="discrete"
        values="0; 50; 100; 150; 200; 200; 0"
        keyTimes="0; 0.64; 0.66; 0.68; 0.70; 0.72; 0.90"/>
    </rect></clipPath>
  </defs>

  <!-- Terminal background -->
  <rect width="840" height="520" rx="12" fill="#0d1117"/>

  <!-- Title bar -->
  <rect width="840" height="38" rx="12" fill="#161b22"/>
  <rect y="12" width="840" height="26" fill="#161b22"/>

  <!-- Window buttons -->
  <circle cx="22" cy="19" r="6.5" fill="#ff5f56"/>
  <circle cx="44" cy="19" r="6.5" fill="#ffbd2e"/>
  <circle cx="66" cy="19" r="6.5" fill="#27c93f"/>

  <!-- Title bar text -->
  <text x="420" y="24" text-anchor="middle" fill="#8b949e" font-family="monospace" font-size="13">igor@recife ~ zsh</text>

  <!-- ASCII Art IGOR -->
  <g transform="translate(34, 60)">
    <text y="16"  fill="#58a6ff" font-family="monospace" font-size="12" xml:space="preserve">  ██╗ ██████╗  ██████╗ ██████╗ </text>
    <text y="30"  fill="#58a6ff" font-family="monospace" font-size="12" xml:space="preserve">  ██║██╔════╝ ██╔═══██╗██╔══██╗</text>
    <text y="44"  fill="#58a6ff" font-family="monospace" font-size="12" xml:space="preserve">  ██║██║  ███╗██║   ██║██████╔╝</text>
    <text y="58"  fill="#58a6ff" font-family="monospace" font-size="12" xml:space="preserve">  ██║██║   ██║██║   ██║██╔══██╗</text>
    <text y="72"  fill="#58a6ff" font-family="monospace" font-size="12" xml:space="preserve">  ██║╚██████╔╝╚██████╔╝██║  ██║</text>
    <text y="86"  fill="#58a6ff" font-family="monospace" font-size="12" xml:space="preserve">  ╚═╝ ╚═════╝  ╚═════╝ ╚═╝  ╚═╝</text>
    <text y="86" x="280" fill="#484f58" font-family="monospace" font-size="11">v2.0.26</text>
  </g>

  <!-- Separator -->
  <line x1="34" y1="160" x2="806" y2="160" stroke="#21262d" stroke-width="1"/>

  <!-- Content area -->
  <g transform="translate(34, 182)">

    <g clip-path="url(#c1)">
      <text y="0" fill="#7ee787" font-family="monospace" font-size="14">$</text>
      <text x="18" y="0" fill="#79c0ff" font-family="monospace" font-size="14">whoami</text>
    </g>
    <g clip-path="url(#c2)" transform="translate(0, 24)">
      <text x="18" y="0" fill="#c9d1d9" font-family="monospace" font-size="14">fullstack dev &amp; solo founder @ brazil</text>
    </g>

    <g clip-path="url(#c3)" transform="translate(0, 58)">
      <text y="0" fill="#7ee787" font-family="monospace" font-size="14">$</text>
      <text x="18" y="0" fill="#79c0ff" font-family="monospace" font-size="14">cat stack.txt</text>
    </g>
    <g clip-path="url(#c4)" transform="translate(0, 82)">
      <text x="18" y="0" fill="#c9d1d9" font-family="monospace" font-size="14">typescript  react  node  python  go</text>
    </g>

    <g clip-path="url(#c5)" transform="translate(0, 116)">
      <text y="0" fill="#7ee787" font-family="monospace" font-size="14">$</text>
      <text x="18" y="0" fill="#79c0ff" font-family="monospace" font-size="14">cat projects</text>
    </g>
    <g clip-path="url(#c6)" transform="translate(0, 140)">
      <text x="18" y="0" fill="#d2a8ff" font-family="monospace" font-size="14">coming soon</text>
      <text x="68" y="0" fill="#484f58" font-family="monospace" font-size="14">|</text>
      <text x="84" y="0" fill="#c9d1d9" font-family="monospace" font-size="14">;)</text>
    </g>

    <g clip-path="url(#c8)" transform="translate(0, 198)">
      <text y="0" fill="#7ee787" font-family="monospace" font-size="14">$</text>
      <text x="18" y="0" fill="#79c0ff" font-family="monospace" font-size="14">cat interests</text>
    </g>
    <g clip-path="url(#c9)" transform="translate(0, 222)">
      <text x="18" y="0" fill="#c9d1d9" font-family="monospace" font-size="14">ai tooling / local llms / dev infra / f1</text>
    </g>

    <g clip-path="url(#c10)" transform="translate(0, 256)">
      <text y="0" fill="#7ee787" font-family="monospace" font-size="14">$</text>
      <text x="18" y="0" fill="#79c0ff" font-family="monospace" font-size="14">env</text>
    </g>
    <g clip-path="url(#c11)" transform="translate(0, 280)">
      <text x="18" y="0" fill="#39d353" font-family="monospace" font-size="14">ghostty+zellij</text>
      <text x="152" y="0" fill="#484f58" font-family="monospace" font-size="14">|</text>
      <text x="168" y="0" fill="#e3b341" font-family="monospace" font-size="14">lol: bronze gg</text>
    </g>

    <g clip-path="url(#c12)" transform="translate(0, 314)">
      <text y="0" fill="#7ee787" font-family="monospace" font-size="14">$</text>
      <text x="18" y="0" fill="#79c0ff" font-family="monospace" font-size="14">echo</text>
      <text x="60" y="0" fill="#a5d6ff" font-family="monospace" font-size="14">"building..."</text>
    </g>

    <!-- CURSOR -->
    <rect width="9" height="17" fill="#7ee787" rx="1">
      <animate attributeName="opacity" dur="0.9s" repeatCount="indefinite"
        values="1;1;0;0" keyTimes="0;0.5;0.501;1"/>
      <!-- X: starts at 0 for each command, no margin -->
      <animate attributeName="x" dur="14s" repeatCount="indefinite" calcMode="discrete"
        keyTimes="0;
                  0.02;  0.03;  0.05;  0.07;  0.09;
                  0.14;  0.15;  0.17;  0.19;  0.21;
                  0.26;  0.27;  0.29;  0.31;  0.33;
                  0.39;  0.40;  0.42;  0.44;  0.46;
                  0.52;  0.53;  0.55;  0.57;
                  0.63;  0.64;  0.66;  0.68;  0.70;  0.72;
                  0.90"
        values=" 0;
                  0;     30;    60;    90;    90;
                  0;     50;    100;   150;   150;
                  0;     48;    96;    145;   145;
                  0;     52;    104;   155;   155;
                  0;     30;    60;    60;
                  0;     50;    100;   150;   200;   200;
                  0"/>
      <!-- Y: jumps to each command line -->
      <animate attributeName="y" dur="14s" repeatCount="indefinite" calcMode="discrete"
        keyTimes="0;    0.14;  0.26;  0.39;  0.52;  0.63;  0.90"
        values=" -12;  46;    104;   186;   244;   302;   -12"/>
    </rect>
  </g>

  <!-- Scanline -->
  <rect width="840" height="2" fill="#ffffff" opacity="0.02">
    <animateTransform attributeName="transform" type="translate" from="0 -10" to="0 520" dur="4s" repeatCount="indefinite"/>
  </rect>
</svg>
