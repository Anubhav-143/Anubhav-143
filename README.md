<!-- Animated Hero Header -->
<p align="center">
  <svg viewBox="0 0 800 250" width="100%" height="250" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <!-- Light Gradient -->
      <linearGradient id="gradientLight" x1="0" y1="0" x2="1" y2="1">
        <stop offset="0%" stop-color="#60A5FA">
          <animate attributeName="stop-color" values="#60A5FA;#A78BFA;#F472B6;#60A5FA" dur="8s" repeatCount="indefinite" />
        </stop>
        <stop offset="100%" stop-color="#C084FC">
          <animate attributeName="stop-color" values="#C084FC;#60A5FA;#A78BFA;#C084FC" dur="8s" repeatCount="indefinite" />
        </stop>
      </linearGradient>

      <!-- Dark Gradient -->
      <linearGradient id="gradientDark" x1="0" y1="0" x2="1" y2="1">
        <stop offset="0%" stop-color="#8B5CF6">
          <animate attributeName="stop-color" values="#8B5CF6;#EC4899;#60A5FA;#8B5CF6" dur="8s" repeatCount="indefinite" />
        </stop>
        <stop offset="100%" stop-color="#60A5FA">
          <animate attributeName="stop-color" values="#60A5FA;#8B5CF6;#EC4899;#60A5FA" dur="8s" repeatCount="indefinite" />
        </stop>
      </linearGradient>

      <!-- Glow Filter -->
      <filter id="glow">
        <feGaussianBlur stdDeviation="4" result="blur" />
        <feMerge>
          <feMergeNode in="blur" />
          <feMergeNode in="SourceGraphic" />
        </feMerge>
      </filter>

      <!-- Floating Orbs Gradient -->
      <radialGradient id="orbGradient" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stop-color="#C084FC" stop-opacity="0.6" />
        <stop offset="100%" stop-color="#60A5FA" stop-opacity="0" />
      </radialGradient>
    </defs>

    <!-- Animated Orbs -->
    <circle cx="200" cy="120" r="90" fill="url(#orbGradient)">
      <animateMotion dur="15s" repeatCount="indefinite" path="M0,0 C100,100 300,-100 400,0 C500,100 700,-100 800,0 Z" />
    </circle>
    <circle cx="600" cy="100" r="70" fill="url(#orbGradient)">
      <animateMotion dur="18s" repeatCount="indefinite" path="M0,0 C-100,50 -300,-50 -400,0 C-500,50 -700,-50 -800,0 Z" />
    </circle>

    <!-- Main Title -->
    <text id="glowText" x="50%" y="55%" text-anchor="middle"
          font-size="55" font-weight="700"
          font-family="Poppins, sans-serif"
          fill="url(#gradientLight)"
          filter="url(#glow)">
      Anubhav Sachan
    </text>

    <!-- Subtitle (Typing Effect Simulation) -->
    <text id="subtitle" x="50%" y="75%" text-anchor="middle"
          font-size="22" font-family="Poppins, sans-serif"
          fill="#6B7280">
      Frontend Developer | Designer | Video Editor
    </text>

    <style>
      @keyframes typing {
        from { clip-path: inset(0 100% 0 0); }
        to { clip-path: inset(0 0 0 0); }
      }
      @keyframes blink {
        50% { opacity: 0; }
      }
      #subtitle {
        animation: typing 4s steps(40) 1s forwards, blink 1s infinite 4s;
        white-space: nowrap;
        overflow: hidden;
      }
      @media (prefers-color-scheme: dark) {
        #glowText {
          fill: url(#gradientDark);
        }
        #subtitle {
          fill: #D1D5DB;
        }
      }
    </style>
  </svg>
</p>

---

### 🌟 About Me  
Hi there! I’m **Anubhav Sachan**, a passionate **Frontend Developer, Designer, and Video Editor**.  
I love turning ideas into interactive, eye-catching digital experiences.

---

### ⚡ Tech Stack  
💻 **Languages:** HTML, CSS, JavaScript, Python  
🎨 **Design Tools:** Figma, Adobe XD, Canva  
🚀 **Frameworks & Tools:** React, Tailwind CSS, Firebase, Git

---

### 📊 GitHub Stats (Dark/Light Mode Optimized)
<p align="center">
  <!-- Stats -->
  <picture>
    <source 
      srcset="https://github-readme-stats.vercel.app/api?username=anubhavsachan&show_icons=true&theme=tokyonight&hide_border=true" 
      media="(prefers-color-scheme: dark)" />
    <img 
      src="https://github-readme-stats.vercel.app/api?username=anubhavsachan&show_icons=true&theme=default&hide_border=true" 
      alt="Anubhav's GitHub Stats" />
  </picture>
</p>

<p align="center">
  <!-- Streak -->
  <picture>
    <source 
      srcset="https://streak-stats.demolab.com?user=anubhavsachan&theme=tokyonight&hide_border=true" 
      media="(prefers-color-scheme: dark)" />
    <img 
      src="https://streak-stats.demolab.com?user=anubhavsachan&theme=default&hide_border=true" 
      alt="GitHub Streak" />
  </picture>
</p>

---

### 🧠 Currently Learning
- Advanced React Animations  
- Modern UI/UX with Framer Motion  
- Firebase Integration

---

### 🌐 Connect with Me
<p align="center">
  <a href="https://www.linkedin.com/in/anubhavsachan" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://anubhavsachan.com" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-111827?style=for-the-badge&logo=vercel&logoColor=white"/>
  </a>
  <a href="mailto:anubhavsachan@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>

---

⭐ *“Code. Create. Inspire.”*


---

## ⚡ GitHub Stats

<p align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=Anubhav-143&show_icons=true&theme=tokyonight" />
  <img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=Anubhav-143&theme=tokyonight" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Anubhav-143&theme=tokyonight" width="90%" />
</p>

---

## ✨ Fun Fact

💭 *I love designing futuristic UIs and crafting visuals that tell stories through light, color, and motion.*

---

## 🪄 Quote of the Day

> *“Design is not just what it looks like and feels like. Design is how it works.”* — **Steve Jobs**

---

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Poppins&size=22&pause=1000&color=4F46E5&center=true&vCenter=true&width=700&lines=Thank+You+for+Visiting+💜;Connect+with+me+on+LinkedIn+✨;Let's+build+something+awesome+together!+🚀" alt="Typing SVG" />
</p>

---

### 🌟 Thanks for visiting!  
⭐ **Star some repositories** or connect with me on LinkedIn 😊
