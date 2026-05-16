<div align="center">

<!-- ═══════════════════════════════════════════════════════
     MD3 EXPENSIVE SURFACE - BANNER
     ═══════════════════════════════════════════════════════ -->
<<svg width="100%" height="220" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- MD3 Surface Container Elevation 3 -->
    <linearGradient id="surface3" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#4a148c;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#311b92;stop-opacity:1" />
    </linearGradient>
    <!-- MD3 Surface Tint Overlay -->
    <linearGradient id="surfaceTint" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#7c4dff;stop-opacity:0.2" />
      <stop offset="100%" style="stop-color:#b388ff;stop-opacity:0.05" />
    </linearGradient>
    <!-- MD3 Elevation Shadow -->
    <filter id="elevation3" x="-5%" y="-5%" width="110%" height="120%">
      <feDropShadow dx="0" dy="6" stdDeviation="10" flood-color="#000000" flood-opacity="0.5"/>
    </filter>
    <!-- Glow -->
    <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  
  <!-- Surface Container (28dp rounded) -->
  <rect width="100%" height="100%" fill="url(#surface3)" rx="28" filter="url(#elevation3)"/>
  <rect width="100%" height="100%" fill="url(#surfaceTint)" rx="28"/>
  
  <!-- Accent Line (MD3 Primary Container) -->
  <rect x="40" y="30" width="4" height="160" fill="#e0b0ff" rx="2" opacity="0.5"/>
  
  <!-- Title - MD3 Display Large -->
  <text x="70" y="95" font-family="'Google Sans', 'Roboto', system-ui, sans-serif" font-size="56" font-weight="400" fill="#e8d5ff" letter-spacing="3" filter="url(#glow)">AUBEIG</text>
  
  <!-- Subtitle - MD3 Headline Small -->
  <text x="70" y="130" font-family="'Google Sans', 'Roboto', system-ui, sans-serif" font-size="18" font-weight="500" fill="#b388ff" letter-spacing="5">FULLSTACK VIBE CODER</text>
  
  <!-- Status - MD3 Label Large -->
  <text x="70" y="170" font-family="'Roboto Mono', monospace" font-size="14" font-weight="400" fill="#9c7cff" letter-spacing="2">Python → Cython → Go</text>
  
  <!-- Decorative Elements -->
  <circle cx="700" cy="60" r="35" fill="#7c4dff" opacity="0.1"/>
  <circle cx="740" cy="110" r="50" fill="#b388ff" opacity="0.06"/>
  <circle cx="680" cy="150" r="25" fill="#e0b0ff" opacity="0.08"/>
  
  <!-- Corner Accent -->
  <path d="M 740 30 Q 770 30 770 60" stroke="#e0b0ff" stroke-width="2" fill="none" opacity="0.4" stroke-linecap="round"/>
</svg>

<br><br>

<!-- ═══════════════════════════════════════════════════════
     MD3 AVATAR - SHAPE APPEARANCE (28dp rounded)
     ═══════════════════════════════════════════════════════ -->
<<svg width="220" height="220" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <filter id="avatarElevation" x="-20%" y="-20%" width="140%" height="140%">
      <feDropShadow dx="0" dy="8" stdDeviation="14" flood-color="#000000" flood-opacity="0.6"/>
    </filter>
    <clipPath id="avatarClip">
      <rect x="15" y="15" width="190" height="190" rx="28"/>
    </clipPath>
  </defs>
  
  <!-- Container Surface -->
  <rect x="10" y="10" width="200" height="200" fill="#4a148c" rx="28" filter="url(#avatarElevation)"/>
  <rect x="10" y="10" width="200" height="200" fill="#7c4dff" rx="28" opacity="0.15"/>
  
  <!-- Avatar Image -->
  <image x="15" y="15" width="190" height="190" href="https://raw.githubusercontent.com/aubeig/Aubeig/refs/heads/main/IMG_20260516_163751_577.jpg" clip-path="url(#avatarClip)" preserveAspectRatio="xMidYMid slice"/>
  
  <!-- Border Overlay -->
  <rect x="15" y="15" width="190" height="190" rx="28" fill="none" stroke="#e0b0ff" stroke-width="2" opacity="0.3"/>
  
  <!-- Online Status Dot -->
  <circle cx="185" cy="185" r="12" fill="#69f0ae" stroke="#311b92" stroke-width="3"/>
</svg>

<br><br>

<!-- ═══════════════════════════════════════════════════════
     MD3 SOCIAL CHIPS
     ═══════════════════════════════════════════════════════ -->
<a href="https://t.me/Aubeig">
  <img src="https://img.shields.io/badge/Telegram-@Aubeig-8A2BE2?style=for-the-badge&logo=telegram&logoColor=white&labelColor=1a0b2e" />
</a>
<a href="https://t.me/bioAub">
  <img src="https://img.shields.io/badge/Channel-@bioAub-9370DB?style=for-the-badge&logo=telegram&logoColor=white&labelColor=1a0b2e" />
</a>
<a href="https://aubeig-interactive-bio.onrender.com/">
  <img src="https://img.shields.io/badge/Portfolio-Aubeig-4B0082?style=for-the-badge&logo=render&logoColor=white&labelColor=1a0b2e" />
</a>

</div>

---

<!-- ═══════════════════════════════════════════════════════
     MD3 STATUS WINDOW - Карточка как в Solo Leveling
     ═══════════════════════════════════════════════════════ -->

<div align="center">

## ⚡ STATUS WINDOW

<<svg width="500" height="180" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="cardSurface" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#1a0b2e;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#311b92;stop-opacity:1" />
    </linearGradient>
    <filter id="cardElevation" x="-5%" y="-5%" width="110%" height="120%">
      <feDropShadow dx="0" dy="4" stdDeviation="8" flood-color="#000000" flood-opacity="0.4"/>
    </filter>
  </defs>
  
  <rect width="100%" height="100%" fill="url(#cardSurface)" rx="24" filter="url(#cardElevation)"/>
  <rect width="100%" height="100%" fill="#7c4dff" rx="24" opacity="0.1"/>
  
  <!-- Header -->
  <text x="30" y="40" font-family="'Google Sans', sans-serif" font-size="16" font-weight="500" fill="#b388ff" letter-spacing="2">PLAYER STATUS</text>
  
  <!-- Divider -->
  <line x1="30" y1="55" x2="470" y2="55" stroke="#7c4dff" stroke-width="1" opacity="0.3"/>
  
  <!-- Stats -->
  <text x="30" y="90" font-family="'Roboto Mono', monospace" font-size="14" fill="#e8d5ff">CLASS</text>
  <text x="130" y="90" font-family="'Roboto Mono', monospace" font-size="14" fill="#b388ff">Fullstack Vibe Coder</text>
  
  <text x="30" y="120" font-family="'Roboto Mono', monospace" font-size="14" fill="#e8d5ff">MAIN</text>
  <text x="130" y="120" font-family="'Roboto Mono', monospace" font-size="14" fill="#b388ff">Python</text>
  
  <text x="30" y="150" font-family="'Roboto Mono', monospace" font-size="14" fill="#e8d5ff">BOOST</text>
  <text x="130" y="150" font-family="'Roboto Mono', monospace" font-size="14" fill="#b388ff">Cython</text>
  
  <!-- Progress Bars -->
  <rect x="280" y="82" width="180" height="8" fill="#1a0b2e" rx="4"/>
  <rect x="280" y="82" width="160" height="8" fill="#8A2BE2" rx="4"/>
  
  <rect x="280" y="112" width="180" height="8" fill="#1a0b2e" rx="4"/>
  <rect x="280" y="112" width="170" height="8" fill="#9370DB" rx="4"/>
  
  <rect x="280" y="142" width="180" height="8" fill="#1a0b2e" rx="4"/>
  <rect x="280" y="142" width="140" height="8" fill="#4B0082" rx="4"/>
</svg>

</div>

---

<!-- ═══════════════════════════════════════════════════════
     MD3 SKILL TRACKER - GitHub Stats в стиле карточек
     ═══════════════════════════════════════════════════════ -->

<div align="center">

## 📊 SKILL TRACKER

<img src="https://github-readme-stats.vercel.app/api?username=Aubeig&show_icons=true&theme=midnight-purple&hide_border=true&bg_color=0d1117&title_color=e0b0ff&icon_color=8A2BE2&text_color=b388ff&border_radius=24&custom_title=OVERALL+POWER" height="210" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Aubeig&layout=compact&theme=midnight-purple&hide_border=true&bg_color=0d1117&title_color=e0b0ff&text_color=b388ff&border_radius=24&custom_title=LANGUAGE+MASTERY" height="210" />

<br><br>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Aubeig&theme=midnight-purple&hide_border=true&background=0d1117&stroke=e0b0ff&ring=8A2BE2&fire=ff6b6b&currStreakLabel=e0b0ff&sideLabels=b388ff&currStreakNum=ffffff&sideNums=c9d1d9&dates=666666&border_radius=24" width="80%" />

</div>

---

<!-- ═══════════════════════════════════════════════════════
     MD3 EQUIPPED SKILLS - Технологии в стиле карточек
     ═══════════════════════════════════════════════════════ -->

<div align="center">

## 🛡️ EQUIPPED SKILLS

<<svg width="600" height="120" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="skillSurface" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#1a0b2e;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#311b92;stop-opacity:1" />
    </linearGradient>
    <filter id="skillElevation" x="-3%" y="-3%" width="106%" height="110%">
      <feDropShadow dx="0" dy="3" stdDeviation="6" flood-color="#000000" flood-opacity="0.3"/>
    </filter>
  </defs>
  
  <!-- Skill Card -->
  <rect width="100%" height="100%" fill="url(#skillSurface)" rx="20" filter="url(#skillElevation)"/>
  <rect width="100%" height="100%" fill="#7c4dff" rx="20" opacity="0.08"/>
  
  <!-- Skill Icons (using shields as placeholders) -->
  <text x="50%" y="50%" font-family="'Google Sans', sans-serif" font-size="16" fill="#b388ff" text-anchor="middle" dominant-baseline="middle">
    Python • Cython • Go • JavaScript • TypeScript • React • Next.js • Node.js
  </text>
</svg>

<br>

<!-- Иконки навыков -->
<img src="https://skillicons.dev/icons?i=python,go,js,ts,react,nextjs,nodejs,html,css,tailwind,git,docker,linux,vscode,postgresql,mongodb&theme=dark&perline=8" />

</div>

---

<!-- ═══════════════════════════════════════════════════════
     MD3 ACHIEVEMENTS - Трофеи
     ═══════════════════════════════════════════════════════ -->

<div align="center">

## 🏆 ACHIEVEMENTS UNLOCKED

<img src="https://github-profile-trophy.vercel.app/?username=Aubeig&theme=discord&no-frame=true&column=7&margin-w=10&margin-h=10&title_color=e0b0ff" width="100%" />

</div>

---

<!-- ═══════════════════════════════════════════════════════
     MD3 DAILY QUEST - Змея
     ═══════════════════════════════════════════════════════ -->

<div align="center">

## 🐍 DAILY QUEST LOG

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Aubeig/Aubeig/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Aubeig/Aubeig/output/github-contribution-grid-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/Aubeig/Aubeig/output/github-contribution-grid-snake-dark.svg" width="100%" />
</picture>

</div>

---

<!-- ═══════════════════════════════════════════════════════
     MD3 FOOTER - Неоновый как в Solo Leveling
     ═══════════════════════════════════════════════════════ -->

<div align="center">

<<svg width="100%" height="100" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="footerSurface" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#4B0082;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#8A2BE2;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#4B0082;stop-opacity:1" />
    </linearGradient>
  </defs>
  <rect width="100%" height="100" fill="url(#footerSurface)" rx="24" opacity="0.3"/>
  <text x="50%" y="45%" font-family="'Google Sans', sans-serif" font-size="16" fill="#e0b0ff" text-anchor="middle" dominant-baseline="middle" letter-spacing="3">"FROM PYTHON TO CYTHON — SPEED IS POWER"</text>
  <text x="50%" y="70%" font-family="'Roboto Mono', monospace" font-size="12" fill="#b388ff" text-anchor="middle" dominant-baseline="middle" letter-spacing="2">AUBEIG SYSTEM v1.0</text>
</svg>

<br>

<a href="https://t.me/Aubeig">💬 TELEGRAM</a> • 
<a href="https://t.me/bioAub">📢 CHANNEL</a> • 
<a href="https://aubeig-interactive-bio.onrender.com/">🌐 PORTFOLIO</a>

</div>
