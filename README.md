## 名前
楊謙鈺(やんちぇんゆ)
## プロフィール写真
<img src="profile-qianyu.jpg" width="300">

## 近況
今年から中学1年生になりました
# ターミナルSVG
<svg width="100%" viewBox="0 0 900 260" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="900" y2="260">
      <stop stop-color="#0B1020"/>
      <stop offset="1" stop-color="#0F172A"/>
    </linearGradient>

    <linearGradient id="danger" x1="0" y1="0" x2="900" y2="0">
      <stop stop-color="#EF4444"/>
      <stop offset="1" stop-color="#F97316"/>
    </linearGradient>

    <filter id="shadow">
      <feDropShadow dx="0" dy="10" stdDeviation="16" flood-color="#000" flood-opacity="0.4"/>
    </filter>
  </defs>

  <!-- terminal frame -->
  <rect x="20" y="20" width="860" height="220" rx="18" fill="url(#bg)" filter="url(#shadow)"/>
  <rect x="20" y="20" width="860" height="220" rx="18" stroke="url(#danger)" stroke-opacity="0.35"/>

  <!-- title bar -->
  <rect x="20" y="20" width="860" height="40" rx="18" fill="#111827"/>
  <circle cx="48" cy="40" r="6" fill="#EF4444"/>
  <circle cx="70" cy="40" r="6" fill="#F59E0B"/>
  <circle cx="92" cy="40" r="6" fill="#22C55E"/>

  <text x="450" y="46" text-anchor="middle"
        font-family="ui-monospace, SFMono-Regular, Menlo, Consolas, monospace"
        font-size="13" fill="#94A3B8">
    terminal • simulation mode
  </text>

  <!-- warning -->
  <text x="52" y="92"
        font-family="ui-monospace, SFMono-Regular, Menlo, Consolas, monospace"
        font-size="16" fill="#F97316">
    ⚠ WARNING: destructive command detected (simulation only)
  </text>

  <!-- command -->
  <text x="52" y="132"
        font-family="ui-monospace, SFMono-Regular, Menlo, Consolas, monospace"
        font-size="18" fill="#22C55E">
    $ rm -rf /
  </text>

  <!-- fake output -->
  <text x="52" y="164"
        font-family="ui-monospace, SFMono-Regular, Menlo, Consolas, monospace"
        font-size="16" fill="#E2E8F0">
    deleting system files...
  </text>

  <text x="52" y="190"
        font-family="ui-monospace, SFMono-Regular, Menlo, Consolas, monospace"
        font-size="16" fill="#EF4444">
    permission denied (just kidding. don't try this.)
  </text>

  <!-- blinking cursor -->
  <rect x="52" y="205" width="10" height="18" fill="#E2E8F0">
    <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite"/>
  </rect>
</svg>
