<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 500 50" width="500" height="50">
  <style>
    @keyframes fade {
      0%   { opacity: 0; }
      25%  { opacity: 1; }
      75%  { opacity: 1; }
      100% { opacity: 0; }
    }
    @keyframes starpulse {
      0%   { opacity: 0; }
      30%  { opacity: 0; }
      55%  { opacity: 1; }
      70%  { opacity: 0.6; }
      85%  { opacity: 1; }
      100% { opacity: 0; }
    }
    .txt {
      font-family: Georgia, 'Times New Roman', serif;
      font-style: italic;
      font-size: 14px;
      fill: #888888;
      text-anchor: middle;
      animation: fade 8s ease-in-out infinite;
    }
    .star {
      font-size: 10px;
      fill: #aaaaaa;
      text-anchor: middle;
      animation: starpulse 8s ease-in-out infinite;
    }
  </style>
  <text x="237" y="30" class="txt">catch flights, not feelings.</text>
  <text x="337" y="24" class="star">✦</text>
</svg>
