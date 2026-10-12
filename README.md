<!-- J.A.R.V.I.S. boot animation: keep jarvis-boot.svg in the same repo, next to this README -->

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 300" width="900" height="300" role="img" aria-label="J.A.R.V.I.S. boot sequence — Aaditya Tyagi, Full Stack Developer">
  <defs>
    <radialGradient id="glow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#00D8FF" stop-opacity="0.55"/>
      <stop offset="100%" stop-color="#00D8FF" stop-opacity="0"/>
    </radialGradient>
    <linearGradient id="bar" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#0EA5E9"/>
      <stop offset="100%" stop-color="#00D8FF"/>
    </linearGradient>
    <pattern id="grid" width="30" height="30" patternUnits="userSpaceOnUse">
      <path d="M30 0H0V30" fill="none" stroke="#00D8FF" stroke-opacity="0.05" stroke-width="1"/>
    </pattern>
  </defs>

  <!-- background -->
  <rect width="900" height="300" rx="14" fill="#0D1117"/>
  <rect width="900" height="300" rx="14" fill="url(#grid)"/>
  <rect x="1" y="1" width="898" height="298" rx="13" fill="none" stroke="#00D8FF" stroke-opacity="0.25"/>

  <!-- corner brackets -->
  <g fill="none" stroke="#00D8FF" stroke-width="2" stroke-opacity="0.7">
    <path d="M18 40V18H40"/>
    <path d="M860 18H882V40"/>
    <path d="M882 260V282H860"/>
    <path d="M40 282H18V260"/>
  </g>

  <!-- arc reactor -->
  <g transform="translate(150 150)">
    <circle r="95" fill="url(#glow)">
      <animate attributeName="opacity" values="0.5;1;0.5" dur="2.4s" repeatCount="indefinite"/>
    </circle>
    <circle r="84" fill="none" stroke="#00D8FF" stroke-opacity="0.25" stroke-width="1"/>
    <circle r="76" fill="none" stroke="#00D8FF" stroke-width="3" stroke-dasharray="90 30 20 30" stroke-linecap="round">
      <animateTransform attributeName="transform" type="rotate" from="0" to="360" dur="7s" repeatCount="indefinite"/>
    </circle>
    <circle r="60" fill="none" stroke="#38BDF8" stroke-width="6" stroke-dasharray="6 10" stroke-opacity="0.8">
      <animateTransform attributeName="transform" type="rotate" from="360" to="0" dur="12s" repeatCount="indefinite"/>
    </circle>
    <circle r="44" fill="none" stroke="#00D8FF" stroke-width="2" stroke-dasharray="60 20" stroke-linecap="round">
      <animateTransform attributeName="transform" type="rotate" from="0" to="360" dur="4s" repeatCount="indefinite"/>
    </circle>
    <circle r="28" fill="#0D1117" stroke="#00D8FF" stroke-width="2"/>
    <circle r="12" fill="#00D8FF">
      <animate attributeName="r" values="10;14;10" dur="1.6s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.7;1;0.7" dur="1.6s" repeatCount="indefinite"/>
    </circle>
  </g>


  <g font-family="'JetBrains Mono','Fira Code',Consolas,Menlo,monospace" font-size="14" fill="#8B949E">
    <animate attributeName="opacity" from="1" to="0" begin="5s" dur="0.4s" fill="freeze"/>

    <text x="290" y="62" fill="#00D8FF" font-size="16" font-weight="700" letter-spacing="3" opacity="0">
      J.A.R.V.I.S. // BOOT SEQUENCE
      <animate attributeName="opacity" from="0" to="1" begin="0.3s" dur="0.3s" fill="freeze"/>
    </text>

    <text x="290" y="98" opacity="0">
      &gt; loading ui modules: react · next.js · react native <tspan fill="#3FB950">[OK]</tspan>
      <animate attributeName="opacity" from="0" to="1" begin="1s" dur="0.2s" fill="freeze"/>
    </text>
    <text x="290" y="124" opacity="0">
      &gt; starting services: node.js · express · graphql <tspan fill="#3FB950">[OK]</tspan>
      <animate attributeName="opacity" from="0" to="1" begin="1.8s" dur="0.2s" fill="freeze"/>
    </text>
    <text x="290" y="150" opacity="0">
      &gt; connecting data: mongodb · postgresql · redis <tspan fill="#3FB950">[OK]</tspan>
      <animate attributeName="opacity" from="0" to="1" begin="2.6s" dur="0.2s" fill="freeze"/>
    </text>
    <text x="290" y="176" opacity="0">
      &gt; waking ai core: openai · claude <tspan fill="#00D8FF">[ONLINE]</tspan>
      <animate attributeName="opacity" from="0" to="1" begin="3.4s" dur="0.2s" fill="freeze"/>
    </text>
    <text x="290" y="202" opacity="0">
      &gt; deploy target: aws ec2 · s3 · cloudfront <tspan fill="#3FB950">[READY]</tspan>
      <animate attributeName="opacity" from="0" to="1" begin="4.1s" dur="0.2s" fill="freeze"/>
    </text>

    <!-- progress bar -->
    <rect x="290" y="232" width="560" height="8" rx="4" fill="#161B22" stroke="#30363D"/>
    <rect x="290" y="232" width="0" height="8" rx="4" fill="url(#bar)">
      <animate attributeName="width" from="0" to="560" begin="0.5s" dur="4.2s" fill="freeze"/>
    </rect>
    <text x="290" y="262" font-size="12" fill="#58A6FF">
      INITIALIZING SYSTEMS
      <animate attributeName="opacity" values="1;0.3;1" dur="1s" repeatCount="indefinite"/>
    </text>
  </g>


  <g font-family="'JetBrains Mono','Fira Code',Consolas,Menlo,monospace" opacity="0">
    <animate attributeName="opacity" from="0" to="1" begin="5.4s" dur="0.8s" fill="freeze"/>

    <text x="290" y="88" font-size="13" fill="#3FB950" letter-spacing="3">● SYSTEM ONLINE
      <animate attributeName="opacity" values="1;0.4;1" dur="1.8s" repeatCount="indefinite"/>
    </text>
    <text x="290" y="112" font-size="14" fill="#8B949E">Welcome back, sir. Loading profile of</text>
    <text x="288" y="166" font-size="46" font-weight="800" fill="#FFFFFF" letter-spacing="2">AADITYA TYAGI</text>
    <rect x="290" y="184" width="0" height="3" rx="1.5" fill="url(#bar)">
      <animate attributeName="width" from="0" to="430" begin="5.8s" dur="0.9s" fill="freeze"/>
    </rect>
    <text x="290" y="216" font-size="17" fill="#00D8FF" letter-spacing="2">FULL STACK DEVELOPER</text>
    <text x="290" y="244" font-size="13" fill="#8B949E">MERN · Next.js · TypeScript · React Native · AI / LLMs</text>
  </g>
</svg>
</p>

<h1 align="center">Hi 👋, I'm Aaditya Tyagi</h1>

<p align="center"><b>Full Stack Developer</b></p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=2500&pause=1000&color=00D8FF&center=true&vCenter=true&width=620&height=32&lines=Build.+Ship.+Scale.;MERN+%C2%B7+Next.js+%C2%B7+TypeScript+%C2%B7+React+Native;AI-powered+products+with+OpenAI+%26+Claude" alt="Build. Ship. Scale." />
</p>

<p align="center">
  Building scalable web and mobile products with clean architecture and production-grade AI.
</p>

<br />

<h2 align="center">🧑‍🚀 About Me</h2>

<img align="right" width="300" src="https://github-readme-stats.vercel.app/api/top-langs/?username=aadityagi84&layout=donut&langs_count=6&hide_border=true&bg_color=0D1117&title_color=00D8FF&text_color=C9D1D9" alt="Most used languages" />

**Aaditya Tyagi** is a Full Stack Developer from Noida, India with **3+ years** of experience shipping production applications.

I work across the stack with **React, Next.js, React Native, Node.js, TypeScript, MongoDB, PostgreSQL and AWS**, own features from architecture to deployment, lead code reviews and mentor junior developers.

Currently building **AI-powered B2B platforms** at Wishgeeks Techserve: LLM chatbots, conversational workflows and OCR-based document verification.

```yaml
shipped:
  page_load: 35% faster
  production_bugs: 40% fewer
  api_response: 25% faster
  users_served: 5,000+
```

<br clear="right" />

<h2 align="center">🤝 Connect</h2>

<p align="center">
  <a href="https://github.com/aadityagi84"><img src="https://skillicons.dev/icons?i=github&theme=dark" height="42" alt="GitHub" /></a>
  &nbsp;
  <a href="https://linkedin.com/in/aaditya-tyagi"><img src="https://skillicons.dev/icons?i=linkedin&theme=dark" height="42" alt="LinkedIn" /></a>
  &nbsp;
  <a href="mailto:tyagiadityagi@gmail.com"><img src="https://skillicons.dev/icons?i=gmail&theme=dark" height="42" alt="Email" /></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=aadityagi84&label=profile%20views&color=00D8FF&style=flat-square" alt="Profile views" />
  <img src="https://img.shields.io/github/followers/aadityagi84?label=followers&style=flat-square&color=00D8FF&labelColor=0D1117" alt="Followers" />
</p>

<br />

<h2 align="center">💻 Tech Stack</h2>

<p align="center">
  <img src="https://skillicons.dev/icons?i=react,nextjs,ts,js,redux,tailwind,materialui,html,css&theme=dark" alt="Frontend" />
</p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=nodejs,express,graphql,mongodb,postgres,mysql,redis&theme=dark" alt="Backend and databases" />
</p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=aws,nginx,git,github,bitbucket,postman,vercel,netlify&theme=dark" alt="Cloud and tools" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React%20Native-0D1117?style=flat-square&logo=react&logoColor=61DAFB" alt="React Native" />
  <img src="https://img.shields.io/badge/OpenAI%20API-0D1117?style=flat-square" alt="OpenAI API" />
  <img src="https://img.shields.io/badge/Anthropic%20Claude-0D1117?style=flat-square" alt="Anthropic Claude" />
  <img src="https://img.shields.io/badge/Socket.IO-0D1117?style=flat-square" alt="Socket.IO" />
  <img src="https://img.shields.io/badge/WebRTC-0D1117?style=flat-square" alt="WebRTC" />
  <img src="https://img.shields.io/badge/BullMQ-0D1117?style=flat-square" alt="BullMQ" />
  <img src="https://img.shields.io/badge/JWT-0D1117?style=flat-square" alt="JWT" />
  <img src="https://img.shields.io/badge/OAuth%202.0-0D1117?style=flat-square" alt="OAuth 2.0" />
  <img src="https://img.shields.io/badge/RBAC-0D1117?style=flat-square" alt="RBAC" />
  <img src="https://img.shields.io/badge/PM2-0D1117?style=flat-square" alt="PM2" />
  <img src="https://img.shields.io/badge/CI%2FCD-0D1117?style=flat-square" alt="CI/CD" />
</p>

<br />

<h2 align="center">📊 GitHub Stats</h2>

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=aadityagi84&show_icons=true&include_all_commits=true&hide_border=true&bg_color=0D1117&title_color=00D8FF&text_color=C9D1D9&icon_color=00D8FF&ring_color=00D8FF" alt="GitHub stats" />
  <img height="170" src="https://streak-stats.demolab.com?user=aadityagi84&hide_border=true&background=0D1117&ring=00D8FF&fire=00D8FF&currStreakLabel=00D8FF&currStreakNum=C9D1D9&sideNums=C9D1D9&sideLabels=C9D1D9&dates=8B949E" alt="GitHub streak" />
</p>

<br />

<h2 align="center">📈 Activity Graph</h2>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=aadityagi84&bg_color=0D1117&color=00D8FF&line=00D8FF&point=FFFFFF&area=true&area_color=00D8FF&hide_border=true" alt="Contribution activity graph" width="100%" />
</p>

<br />

<h2 align="center">🏆 Trophies</h2>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=aadityagi84&theme=darkhub&no-frame=true&no-bg=true&margin-w=6&row=1&column=6" alt="GitHub trophies" />
</p>

<br />

<h2 align="center">🎓 Certifications</h2>

<p align="center">
  <img src="https://img.shields.io/badge/HackerRank-Frontend%20Developer%20(React)-0D1117?style=flat-square&logo=hackerrank&logoColor=00EA64" alt="HackerRank Frontend Developer (React)" />
  <img src="https://img.shields.io/badge/Linux%20Foundation-Introduction%20to%20Node.js%20(LFW111)-0D1117?style=flat-square&logo=linuxfoundation&logoColor=white" alt="Linux Foundation LFW111" />
  <br />
  <img src="https://img.shields.io/badge/The%20Digital%20Adda-React.js%20%26%20Node.js-0D1117?style=flat-square" alt="The Digital Adda React.js and Node.js" />
  <img src="https://img.shields.io/badge/DUCAT-MERN%20Stack%20Development-0D1117?style=flat-square" alt="DUCAT MERN Stack Development" />
</p>

<p align="center"><sub>BCA · Chaudhary Charan Singh University, Meerut · 2022–2025</sub></p>
