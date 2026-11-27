<div align="center">
  <a href="https://hemang2601.github.io/portfolio/">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="./assets/hero-dark.svg" />
      <source media="(prefers-color-scheme: light)" srcset="./assets/hero-light.svg" />
      <img src="./assets/hero-dark.svg" width="100%" alt="Hemang Lakhadiya — Full Stack Developer & Mobile Architect — The Digital Engineering Showcase" />
    </picture>
  </a>

  <br /><br />

  <h1>HEMANG LAKHADIYA</h1>
  <p>
    <strong>Full Stack Developer &amp; Mobile Architect</strong> · App Full Stack Developer Intern @ <strong>Zennaxx Technology</strong><br />
    <sub>Rajkot, Gujarat, India</sub>
  </p>

  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2800&pause=900&color=37DFFF&center=true&vCenter=true&width=760&height=42&lines=Full+Stack+Developer+%26+Mobile+Architect;App+Full+Stack+Developer+Intern+%40+Zennaxx+Technology;1st+Place+Winner+%E2%80%94+Code+Carnival+3.0;Backend+Systems+%E2%80%A2+APIs+%E2%80%A2+Cryptographic+Security" />
    <source media="(prefers-color-scheme: light)" srcset="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2800&pause=900&color=0284C7&center=true&vCenter=true&width=760&height=42&lines=Full+Stack+Developer+%26+Mobile+Architect;App+Full+Stack+Developer+Intern+%40+Zennaxx+Technology;1st+Place+Winner+%E2%80%94+Code+Carnival+3.0;Backend+Systems+%E2%80%A2+APIs+%E2%80%A2+Cryptographic+Security" />
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2800&pause=900&color=37DFFF&center=true&vCenter=true&width=760&height=42&lines=Full+Stack+Developer+%26+Mobile+Architect;App+Full+Stack+Developer+Intern+%40+Zennaxx+Technology;1st+Place+Winner+%E2%80%94+Code+Carnival+3.0;Backend+Systems+%E2%80%A2+APIs+%E2%80%A2+Cryptographic+Security" alt="Hemang Lakhadiya Roles & Milestones" />
  </picture>

  <p>
    I build modern web applications, scalable backend systems, cross-platform mobile apps, and practical software products.
    My engineering work emphasizes backend architecture, relational and NoSQL database design, REST API development, cryptographic security, and end-to-end delivery.
  </p>

  <p>
    <a href="https://hemang2601.github.io/portfolio/">
      <img src="https://img.shields.io/badge/Portfolio-080D1A?style=for-the-badge&logo=googlechrome&logoColor=37DFFF" alt="Portfolio Website" />
    </a>
    <a href="https://github.com/Hemang2601">
      <img src="https://img.shields.io/badge/GitHub-111A2D?style=for-the-badge&logo=github&logoColor=F4F7FF" alt="GitHub Profile" />
    </a>
    <a href="https://www.linkedin.com/in/hemang-lakhadiya/">
      <img src="https://img.shields.io/badge/LinkedIn-111A2D?style=for-the-badge&logoColor=9A86FF" alt="LinkedIn Profile" />
    </a>
    <a href="mailto:lakhadiyahemang@gmail.com">
      <img src="https://img.shields.io/badge/Email-111A2D?style=for-the-badge&logo=gmail&logoColor=F3C77B" alt="Email Hemang Lakhadiya" />
    </a>
  </p>
</div>

<img src="./assets/divider.svg" width="100%" alt="" />

## Professional Impact Dashboard

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/kpi-dashboard-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="./assets/kpi-dashboard-light.svg" />
    <img src="./assets/kpi-dashboard-dark.svg" width="100%" alt="14+ Software Projects, 1st Place Code Carnival 3.0, 5x Hackathon Participation, 16 Professional Certifications, BCA CGPA 9.32, MCA CGPA 8.83" />
  </picture>
</div>

<p align="center">
  <strong>14+ Software Projects</strong> ·
  <strong>1st Place – Code Carnival 3.0</strong> ·
  <strong>5x Hackathon Participation</strong> ·
  <strong>16 Professional Certifications</strong> ·
  <strong>BCA CGPA: 9.32</strong> ·
  <strong>MCA CGPA: 8.83</strong>
</p>

<img src="./assets/divider.svg" width="100%" alt="" />

## Featured Project Showcase

### Flagship Project — TrustDoc (Secure Document Management &amp; Verification Platform)

<div align="center">
  <a href="https://hemang2601.github.io/portfolio/#projects">
    <img src="./assets/trustdoc-showcase.svg" width="100%" alt="TrustDoc Architecture: TipTap Creation & Upload, AES-256-GCM Encryption, RSA-PSS & HMAC-SHA256 Signatures, SHA-256 Integrity Verification, RBAC & Real-Time SOC" />
  </a>
</div>

<br />

<table>
  <tr>
    <td>
      <p><strong>Category:</strong> Cryptographic Document Security &amp; Enterprise Verification Platform (Flagship MCA Project)</p>
      <p><strong>Description:</strong> Full-stack security platform engineered for tamper-evident document creation, encrypted storage, cryptographic integrity verification, and permissioned stakeholder sharing. Major modules have been implemented and verified in local testing.</p>
      <ul>
        <li><strong>Document Creation, Upload &amp; PDF Engine:</strong> In-browser rich-text editor powered by TipTap with instant PDF export, cryptographic watermarking (<code>pdf-lib</code>), and secure file upload validation (magic-byte, MIME, and sanitization checks).</li>
        <li><strong>AES-256-GCM Encryption at Rest:</strong> Authenticated file encryption using per-operation 96-bit random IVs and 128-bit GCM authentication tags (<code>EncryptionService</code>), rejecting corrupted or tampered ciphertext.</li>
        <li><strong>RSA-PSS &amp; HMAC-SHA256 Digital Signatures:</strong> Cryptographic signing using 2048-bit RSA-PSS keypairs and timing-safe HMAC-SHA256 certification stamps (<code>SignatureService</code>) for author non-repudiation.</li>
        <li><strong>SHA-256 Integrity Verification &amp; Diffing:</strong> Content and version hashing with a public verification portal and PDF stream diff inspection to detect single-bit modifications.</li>
        <li><strong>RBAC, Permissioned Sharing &amp; Security Ops:</strong> Role-based access control (Admin, Organization Manager, User), granular share permissions (<code>view</code>, <code>download</code>, <code>edit</code>, <code>verify</code>) with expiration and revocation, real-time Socket.IO audit logs, rate-limiting, and IP threat blocking.</li>
      </ul>
      <p>
        <strong>Architecture Stack:</strong> <code>React</code> <code>TypeScript</code> <code>Node.js</code> <code>Express</code> <code>MongoDB</code> <code>TipTap</code> <code>Tailwind CSS</code> <code>Socket.IO</code> <code>AES-256-GCM</code> <code>RSA-PSS</code> <code>SHA-256</code><br />
        <strong>Status &amp; Reference:</strong> Major modules implemented and verified locally (Private Repository) · <a href="https://hemang2601.github.io/portfolio/#projects">View Portfolio Case Study →</a>
      </p>
    </td>
  </tr>
</table>

<br />

### Core Portfolio &amp; Production Systems

<div align="center">
  <img src="./assets/projects-showcase.svg" width="100%" alt="Featured Systems: Web & Commerce, Mobile & Real-Time, Algorithms & Fleet" />
</div>

<br />

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🛒 Shivashine Jewellery</h3>
      <p><strong>Category:</strong> Web Application &amp; E-Commerce Platform</p>
      <p>Production-ready online jewellery storefront built for multi-criteria catalog discovery, secure online payments, and live stock consistency.</p>
      <ul>
        <li>Razorpay payment gateway integration for verified checkout flows</li>
        <li>Google OAuth user sign-in and session management</li>
        <li>Multi-attribute product catalog search and pricing filters</li>
        <li>Real-time inventory deduction preventing overselling on checkout</li>
      </ul>
      <p><strong>Stack:</strong> <code>Laravel</code> <code>PHP</code> <code>Tailwind CSS</code> <code>JavaScript</code> <code>Razorpay API</code> <code>Google OAuth</code> <code>MySQL</code></p>
      <p><strong>Status:</strong> Private / Team Repository · <a href="https://hemang2601.github.io/portfolio/#projects">Portfolio Case Study →</a></p>
    </td>
    <td width="50%" valign="top">
      <h3>📊 Enterprise Inventory Management System</h3>
      <p><strong>Category:</strong> Web Application &amp; ERP Analytics</p>
      <p>Commercial stock tracking and billing system built with interactive dashboards to surface sales trends, stock turnover, and reorder thresholds.</p>
      <ul>
        <li>Interactive Chart.js visualizations for daily, monthly, and annual sales</li>
        <li>Automated minimum-threshold alerts for low-stock depletion</li>
        <li>Multi-role access separation between storekeepers and managers</li>
        <li>Billing and tax engine generating printable invoice receipts</li>
      </ul>
      <p><strong>Stack:</strong> <code>Laravel</code> <code>Bootstrap</code> <code>Chart.js</code> <code>PHP</code> <code>MySQL</code></p>
      <p><strong>Status:</strong> Private Repository · <a href="https://hemang2601.github.io/portfolio/#projects">Portfolio Case Study →</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🗓️ Automated Class Timetable Generator</h3>
      <p><strong>Category:</strong> Web Application &amp; Algorithmic Matrix Engine</p>
      <p>Algorithmic scheduling engine that generates conflict-free multi-department academic timetables with heavy server-side optimizations.</p>
      <ul>
        <li>Matrix conflict-resolution logic balancing faculty and room availability</li>
        <li>Multi-department constraint mapping across lecture and lab sessions</li>
        <li>Server-side performance tuning preventing request timeouts</li>
        <li>One-click timetable generation with manual override support</li>
      </ul>
      <p><strong>Stack:</strong> <code>Laravel</code> <code>PHP</code> <code>Bootstrap</code> <code>Matrix Logic</code> <code>MySQL</code></p>
      <p><strong>Status:</strong> Private Institutional Repository · <a href="https://hemang2601.github.io/portfolio/#projects">Portfolio Case Study →</a></p>
    </td>
    <td width="50%" valign="top">
      <h3>📱 Shree Shakti Billing App</h3>
      <p><strong>Category:</strong> Cross-Platform Mobile Utility (Flutter)</p>
      <p>Mobile billing and client ledger utility engineered for on-field electrical service contractors needing reliable offline access.</p>
      <ul>
        <li>Cross-platform responsive mobile UI constructed in Flutter and Dart</li>
        <li>Synchronized customer ledger tracking outstanding client balances</li>
        <li>Instant digital PDF invoice generation for on-field billing</li>
        <li>Offline-first local SQLite storage with client and job-work lookup</li>
      </ul>
      <p><strong>Stack:</strong> <code>Flutter</code> <code>Dart</code> <code>SQLite Offline Storage</code></p>
      <p><strong>Status:</strong> Public Repository · <a href="https://github.com/Hemang2601/Bill">github.com/Hemang2601/Bill →</a> <sub>(<a href="https://github.com/Hemang2601/Bill-MERN">MERN Edition</a>)</sub></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🚕 Automated Taxi Service Manager</h3>
      <p><strong>Category:</strong> Web Application &amp; Fleet Operations</p>
      <p>Full-stack fleet operations dashboard designed to track vehicles, manage active bookings, and compute mileage-based fares cleanly.</p>
      <ul>
        <li>Real-time administrative dispatch console for vehicles and bookings</li>
        <li>Conflict-detection logic preventing overlapping driver shift schedules</li>
        <li>Relational data models handling dynamic mileage-based fare rules</li>
        <li>Customer trip history logs with itemized fare receipts</li>
      </ul>
      <p><strong>Stack:</strong> <code>Laravel</code> <code>PHP</code> <code>Bootstrap</code> <code>MySQL</code></p>
      <p><strong>Status:</strong> Private Repository · <a href="https://hemang2601.github.io/portfolio/#projects">Portfolio Case Study →</a></p>
    </td>
    <td width="50%" valign="top">
      <h3>🎓 Certificate &amp; Placement Analytics</h3>
      <p><strong>Category:</strong> Web Portal &amp; Automated PDF Generation</p>
      <p>Centralized campus portal where students upload extracurricular credentials for administrative validation and recruiter placement filtering.</p>
      <ul>
        <li>Categorized credential vault for Sports, Technical, and Cultural records</li>
        <li>Multi-attribute recruiter filtering for campus placement shortlists</li>
        <li>On-demand PDF certificate rendering powered by TCPDF</li>
        <li>Student authentication, upload validation, and admin verification desk</li>
      </ul>
      <p><strong>Stack:</strong> <code>Core PHP</code> <code>TCPDF</code> <code>Bootstrap</code> <code>JavaScript</code> <code>MySQL</code></p>
      <p><strong>Status:</strong> Public Repository · <a href="https://github.com/Hemang2601/HACKTHON2">github.com/Hemang2601/HACKTHON2 →</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🌾 Farmer Bidding &amp; Marketplace</h3>
      <p><strong>Category:</strong> Web Marketplace &amp; Agricultural E-Commerce</p>
      <p>Two-sided marketplace connecting farmers directly with wholesale produce buyers for transparent crop listing and open price discovery.</p>
      <ul>
        <li>Open pricing bidding workflow empowering competitive buyer offers</li>
        <li>Real-time crop inventory listings with quantity, grade, and photos</li>
        <li>Direct farmer-to-buyer communication removing broker intermediaries</li>
        <li>Lightweight UI tailored for low-bandwidth rural mobile devices</li>
      </ul>
      <p><strong>Stack:</strong> <code>PHP</code> <code>JavaScript</code> <code>HTML5</code> <code>CSS3</code> <code>MySQL</code></p>
      <p><strong>Status:</strong> Public Repository · <a href="https://github.com/Hemang2601/Farmar">github.com/Hemang2601/Farmar →</a></p>
    </td>
    <td width="50%" valign="top">
      <h3>🎟️ EventEase — College Event Registration &amp; Check-In</h3>
      <p><strong>Category:</strong> Full-Stack Web Platform (Team NexGen Coders)</p>
      <p>Real-time college event registration and check-in platform built as Team Leader to eliminate duplicate entries and slow gate queues.</p>
      <ul>
        <li>Organizer event creation with automated registration capacity limits</li>
        <li>Instant student registration generating unique check-in passes</li>
        <li>Type-safe React + TypeScript frontend integrated with Drizzle &amp; Supabase</li>
        <li>Real-time attendance tracking dashboard for event coordinators</li>
      </ul>
      <p><strong>Stack:</strong> <code>TypeScript</code> <code>React</code> <code>Drizzle</code> <code>Supabase</code></p>
      <p><strong>Status:</strong> Public Repository · <a href="https://github.com/Hemang2601/EventEase">github.com/Hemang2601/EventEase →</a></p>
    </td>
  </tr>
</table>

<p>
  <strong>Additional Verified Public Repositories:</strong>
  <a href="https://github.com/Hemang2601/ELECTION_PROJECT">ELECTION_PROJECT</a> (PL/SQL &amp; Database Triggers) ·
  <a href="https://github.com/Hemang2601/Cryptography_4091">Cryptography_4091</a> (Python AES/DES/RSA/SHA) ·
  <a href="https://github.com/Hemang2601/hackathon1">hackathon1</a> (PHP Certificate Portal) ·
  <a href="https://github.com/Hemang2601/portfolio">portfolio</a> (Personal Portfolio Website)
</p>

<img src="./assets/divider.svg" width="100%" alt="" />

## Technical Expertise

| Category | Technology Icons | Core Technologies |
| :--- | :--- | :--- |
| **Frontend** | <picture><source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=html,css,js,react,tailwind,bootstrap&theme=dark" /><source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=html,css,js,react,tailwind,bootstrap&theme=light" /><img src="https://skillicons.dev/icons?i=html,css,js,react,tailwind,bootstrap&theme=dark" height="30" alt="HTML, CSS, JavaScript, React, Tailwind CSS, Bootstrap" /></picture> | `HTML` · `CSS` · `JavaScript` · `React` · `Tailwind CSS` · `Bootstrap` · `Chart.js` |
| **Backend** | <picture><source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=nodejs,express,php,laravel&theme=dark" /><source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=nodejs,express,php,laravel&theme=light" /><img src="https://skillicons.dev/icons?i=nodejs,express,php,laravel&theme=dark" height="30" alt="Node.js, Express.js, PHP, Laravel" /></picture> | `Node.js` · `Express.js` · `PHP` · `Laravel` · `REST APIs` · `SMTP` |
| **Mobile** | <picture><source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=flutter,dart,androidstudio,java&theme=dark" /><source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=flutter,dart,androidstudio,java&theme=light" /><img src="https://skillicons.dev/icons?i=flutter,dart,androidstudio,java&theme=dark" height="30" alt="Flutter, Dart, Android, Java" /></picture> | `Flutter` · `Dart` · `Android` · `Java` |
| **Database** | <picture><source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=mongodb,mysql&theme=dark" /><source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=mongodb,mysql&theme=light" /><img src="https://skillicons.dev/icons?i=mongodb,mysql&theme=dark" height="30" alt="MongoDB, MySQL, SQL" /></picture> | `MongoDB` · `MySQL` · `SQL` |
| **Programming** | <picture><source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=py,c,cpp&theme=dark" /><source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=py,c,cpp&theme=light" /><img src="https://skillicons.dev/icons?i=py,c,cpp&theme=dark" height="30" alt="Python, C, C++" /></picture> | `Python` · `C` · `C++` <sub>(plus JavaScript, PHP, Java, Dart)</sub> |
| **Tools &amp; Platforms** | <picture><source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=git,github,vscode,postman,firebase,gcp&theme=dark" /><source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=git,github,vscode,postman,firebase,gcp&theme=light" /><img src="https://skillicons.dev/icons?i=git,github,vscode,postman,firebase,gcp&theme=dark" height="30" alt="Git, GitHub, VS Code, Postman, Firebase, Google Cloud" /></picture> | `Git` · `GitHub` · `VS Code` · `Postman` · `Firebase` · `Google Cloud` |

<img src="./assets/divider.svg" width="100%" alt="" />

## Experience, Education &amp; Achievements

### Professional Experience

<div align="center">
  <img src="./assets/experience-timeline.svg" width="100%" alt="Career Timeline: Rajeshwar Infotech (Aug 2023–Dec 2024) to Zennaxx Technology (Oct 2026–Present)" />
</div>

<br />

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>Zennaxx Technology — Full Stack Developer Intern</h4>
      <p><sub>October 2026 – Present · Rajkot, Gujarat, India</sub></p>
      <ul>
        <li>Developing full-stack application features, REST APIs, and MongoDB schema architecture using <code>Node.js</code> and <code>Express.js</code>.</li>
        <li>Collaborating on backend engineering workflows and practical software product delivery.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>Rajeshwar Infotech — Web &amp; App Development Intern</h4>
      <p><sub>August 2023 – December 2024 · Rajkot, Gujarat, India</sub></p>
      <ul>
        <li>Built native <code>Android (Java)</code> applications and full-stack web projects in <code>Laravel</code> and <code>PHP</code>.</li>
        <li>Designed and managed relational <code>MySQL</code> databases ensuring data integrity and reliable query performance.</li>
      </ul>
    </td>
  </tr>
</table>

### Education

<div align="center">
  <img src="./assets/education-roadmap.svg" width="100%" alt="Education: BCA at Atmiya University (CGPA 9.32) and MCA at Marwadi University (CGPA 8.83)" />
</div>

<br />

* **Master of Computer Applications (MCA)** — Marwadi University *(2025 – Present, Exp. 2027)* · **CGPA: 8.83**
* **Bachelor of Computer Applications (BCA)** — Atmiya University *(2022 – 2025)* · **CGPA: 9.32 (Distinction)**

### Achievements &amp; Certifications

<div align="center">
  <img src="./assets/achievement-spotlight.svg" width="100%" alt="1st Rank Code Carnival 3.0, 5x Hackathon Participation, Team Leadership, 16 Certifications" />
</div>

<br />

* 🏆 **1st Rank – Code Carnival 3.0**, Atmiya Developer Students Club, Atmiya University *(October 2026)* — Architected, implemented, and pitched a complete working software product under competitive hackathon conditions.
* **5x Hackathon Participation &amp; Team Leadership** — Led development teams across five 24–36 hour hackathons, coordinating system architecture, sprint tasks, debugging, and technical jury presentations.
* **16 Professional Certifications** — Verified credentials across **CII Centre for AI** (*Applied ML &amp; AI*), **Infosys Springboard** (*Node.js/Express/MongoDB, Database Design, Normalization*), **Coursera** (*Mastering Laravel &amp; PHP*), **Cisco Networking Academy** (*Python Essentials*), **Google Cloud** (*Foundations &amp; 3 Skill Badges*), **Great Learning** (*Android, Python for Data Science, SQL*), and **Udemy** (*Prompt Engineering for Data Analysis*) — [View Showcase on Portfolio →](https://hemang2601.github.io/portfolio/#certifications).

<img src="./assets/divider.svg" width="100%" alt="" />

## GitHub Analytics

<div align="center">
  <p>
    <img src="https://komarev.com/ghpvc/?username=Hemang2601&color=37DFFF&style=flat-square&label=PROFILE+VISITORS" alt="Profile Visitors Counter" />
  </p>

  <table>
    <tr>
      <td width="52%" align="center">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=Hemang2601&show_icons=true&hide_border=true&bg_color=080D1A&title_color=F4F7FF&icon_color=37DFFF&text_color=9AA9C0" />
          <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=Hemang2601&show_icons=true&hide_border=true&bg_color=F4F7FF&title_color=080D1A&icon_color=0284C7&text_color=334155" />
          <img src="https://github-readme-stats.vercel.app/api?username=Hemang2601&show_icons=true&hide_border=true&bg_color=080D1A&title_color=F4F7FF&icon_color=37DFFF&text_color=9AA9C0" width="100%" alt="Hemang2601 GitHub Profile Statistics" />
        </picture>
      </td>
      <td width="48%" align="center">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Hemang2601&layout=compact&hide_border=true&bg_color=080D1A&title_color=F4F7FF&text_color=9AA9C0" />
          <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Hemang2601&layout=compact&hide_border=true&bg_color=F4F7FF&title_color=080D1A&text_color=334155" />
          <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Hemang2601&layout=compact&hide_border=true&bg_color=080D1A&title_color=F4F7FF&text_color=9AA9C0" width="100%" alt="Hemang2601 Most-Used Programming Languages" />
        </picture>
      </td>
    </tr>
    <tr>
      <td width="52%" align="center">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=Hemang2601&hide_border=true&background=080D1A&stroke=1F2C48&ring=37DFFF&fire=F3C77B&currStreakNum=F4F7FF&sideNums=F4F7FF&currStreakLabel=37DFFF&sideLabels=9AA9C0&dates=9A86FF" />
          <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com/?user=Hemang2601&hide_border=true&background=F4F7FF&stroke=CBD5E1&ring=0284C7&fire=B45309&currStreakNum=080D1A&sideNums=080D1A&currStreakLabel=0284C7&sideLabels=334155&dates=6D5DF6" />
          <img src="https://streak-stats.demolab.com/?user=Hemang2601&hide_border=true&background=080D1A&stroke=1F2C48&ring=37DFFF&fire=F3C77B&currStreakNum=F4F7FF&sideNums=F4F7FF&currStreakLabel=37DFFF&sideLabels=9AA9C0&dates=9A86FF" width="100%" alt="Hemang2601 GitHub Contribution Streak" />
        </picture>
      </td>
      <td width="48%" align="center">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Hemang2601&theme=github_dark" />
          <source media="(prefers-color-scheme: light)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Hemang2601&theme=default" />
          <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Hemang2601&theme=github_dark" width="100%" alt="Hemang2601 GitHub Contribution Activity Graph" />
        </picture>
      </td>
    </tr>
  </table>

  <br />

  <a href="https://github.com/Hemang2601">
    <img src="https://ghchart.rshah.org/37DFFF/Hemang2601" width="92%" alt="Hemang2601 GitHub Contribution Heatmap" />
  </a>

  <p><sub>Live repository insights &amp; contributions: <a href="https://github.com/Hemang2601?tab=repositories">github.com/Hemang2601?tab=repositories</a></sub></p>
</div>

<img src="./assets/divider.svg" width="100%" alt="" />

## Connect

<div align="center">

| Portfolio | GitHub | LinkedIn | Email | Location |
| :---: | :---: | :---: | :---: | :---: |
| [hemang2601.github.io/portfolio](https://hemang2601.github.io/portfolio/) | [github.com/Hemang2601](https://github.com/Hemang2601) | [linkedin.com/in/hemang-lakhadiya](https://www.linkedin.com/in/hemang-lakhadiya/) | [lakhadiyahemang@gmail.com](mailto:lakhadiyahemang@gmail.com) | Rajkot, Gujarat, India |

<br />

<a href="https://hemang2601.github.io/portfolio/">
  <img src="./assets/footer.svg" width="100%" alt="Hemang Lakhadiya // Digital Engineering Showcase" />
</a>

</div>
