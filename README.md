## Hi there 👋
<svg width="400" height="200" viewBox="0 0 400 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="gradient" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#3498db" />
      <stop offset="50%" stop-color="#9b59b6" />
      <stop offset="100%" stop-color="#e74c3c" />
    </linearGradient>
  </defs>
  
  <!-- 背景 -->
  <rect width="400" height="200" fill="#f0f0f0" />
  
  <!-- 动态粒子效果 -->
  <circle cx="50" cy="50" r="10" fill="url(#gradient)">
    <animate attributeName="cx" values="50;350;50" dur="15s" repeatCount="indefinite" />
    <animate attributeName="cy" values="50;150;50" dur="10s" repeatCount="indefinite" />
    <animate attributeName="r" values="10;20;10" dur="5s" repeatCount="indefinite" />
  </circle>
  
  <circle cx="100" cy="100" r="15" fill="#2ecc71">
    <animate attributeName="cx" values="100;300;100" dur="12s" repeatCount="indefinite" />
    <animate attributeName="cy" values="100;50;100" dur="8s" repeatCount="indefinite" />
  </circle>
  
  <circle cx="200" cy="50" r="8" fill="#e67e22">
    <animate attributeName="cx" values="200;100;200;300;200" dur="18s" repeatCount="indefinite" />
    <animate attributeName="cy" values="50;150;50" dur="14s" repeatCount="indefinite" />
  </circle>
  
  <circle cx="300" cy="150" r="12" fill="#9b59b6">
    <animate attributeName="cx" values="300;200;300" dur="10s" repeatCount="indefinite" />
    <animate attributeName="cy" values="150;100;150" dur="6s" repeatCount="indefinite" />
    <animate attributeName="r" values="12;5;12" dur="7s" repeatCount="indefinite" />
  </circle>
  
  <!-- 你的名字或标语 -->
  <text x="200" y="120" font-family="Arial" font-size="24" text-anchor="middle" fill="#333">Hello GitHub!</text>
  
  <!-- 小装饰线 -->
  <line x1="150" y1="140" x2="250" y2="140" stroke="url(#gradient)" stroke-width="2">
    <animate attributeName="x1" values="150;100;150" dur="15s" repeatCount="indefinite" />
    <animate attributeName="x2" values="250;300;250" dur="15s" repeatCount="indefinite" />
  </line>
</svg>

<!--
**laoliandekeren/laoliandekeren** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🌱 I’m currently studying at BIBS in China

