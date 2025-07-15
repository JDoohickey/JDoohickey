<!-- GitHub Profile README.md -->
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <script>
    document.addEventListener('DOMContentLoaded', function() {
      // Animate tech stack icons on hover
      const badges = document.querySelectorAll('.tech-badge');
      badges.forEach(badge => {
        badge.addEventListener('mouseover', function() {
          this.style.transform = 'translateY(-5px)';
          this.style.transition = 'all 0.3s ease';
        });
        badge.addEventListener('mouseout', function() {
          this.style.transform = 'translateY(0)';
        });
      });

      // Project cards animation
      const projectCards = document.querySelectorAll('.project-card');
      projectCards.forEach(card => {
        card.addEventListener('mouseover', function() {
          this.style.boxShadow = '0 10px 25px rgba(0, 247, 255, 0.3)';
        });
        card.addEventListener('mouseout', function() {
          this.style.boxShadow = '0 4px 8px rgba(0, 0, 0, 0.1)';
        });
      });

      // Real-time clock
      function updateClock() {
        const now = new Date();
        const clock = document.getElementById('digital-clock');
        if (clock) {
          clock.innerHTML = now.toLocaleTimeString('en-US', { 
            hour: '2-digit', 
            minute: '2-digit',
            second: '2-digit',
            hour12: true 
          });
        }
      }
      setInterval(updateClock, 1000);
      updateClock();
    });
  </script>
  <style>
    :root {
      --neon-blue: #00F7FF;
      --dark-bg: #0d1117;
      --card-bg: #161b22;
    }
    .tech-badge:hover {
      filter: drop-shadow(0 0 8px var(--neon-blue));
    }
    .project-card {
      transition: all 0.3s ease;
      background: var(--card-bg);
      border-radius: 10px;
      padding: 15px;
      margin-bottom: 15px;
      border-left: 3px solid var(--neon-blue);
    }
    .pulse {
      animation: pulse 2s infinite;
    }
    @keyframes pulse {
      0% { opacity: 1; }
      50% { opacity: 0.7; }
      100% { opacity: 1; }
    }
    #digital-clock {
      font-family: 'Fira Code', monospace;
      color: var(--neon-blue);
      text-shadow: 0 0 10px var(--neon-blue);
    }
  </style>
</head>
<body>
  <h1 align="center">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&pause=1000&color=00F7FF&center=true&vCenter=true&width=700&lines=I+AM+L.+%F0%9F%91%8B;Qualified+Industrial+Engineer;Certified+Full+Stack+Developer;Engineer+%7C+Analyst+%7C+Trader;Flask+%7C+Power+BI+%7C+GitHub+Dev" alt="Typing SVG" />
  </h1>

  <div align="center">
    <div id="digital-clock" class="pulse"></div>
  </div>

  ---

  ### ⚙️ About Me

  💡 **"I AM L."** — a **Qualified Industrial Engineer**, systems thinker, and  
  **certified full-stack developer** with a mission to engineer intelligence into everything.

  - 🧠 **Industrial Engineering + AI**
  - 📊 **Data Analytics** | Power BI | Excel | Python
  - 💹 **Forex Systems & Automation**
  - 💻 **Web Dev** | Flask | HTML | CSS | JavaScript | GitHub
  - 🧬 Passionate about building **AI-powered tools** that make real-world impact

  ---

  ### 📜 Certified In

  - 🏆 **Full Stack Development** (FNB App Academy x ITVarsity – 32 Credits)
  - 🎓 **Bachelor of Engineering (Industrial)** — Class of 2024
  - 🧩 **Simulation & AI Research** (Urban Traffic, Healthcare, SLAM)

  ---

  ### 🛠️ Tech Stack

  <div class="tech-stack">
    <img src="https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white" class="tech-badge">
    <img src="https://img.shields.io/badge/-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" class="tech-badge">
    <img src="https://img.shields.io/badge/-Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" class="tech-badge">
    <img src="https://img.shields.io/badge/-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" class="tech-badge">
    <img src="https://img.shields.io/badge/-CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" class="tech-badge">
    <img src="https://img.shields.io/badge/-Flask-000000?style=for-the-badge&logo=flask&logoColor=white" class="tech-badge">
    <img src="https://img.shields.io/badge/-Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" class="tech-badge">
    <img src="https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" class="tech-badge">
    <img src="https://img.shields.io/badge/-Git-F05032?style=for-the-badge&logo=git&logoColor=white" class="tech-badge">
  </div>

  ---

  ### 🎯 Current Focus

  - 🧠 Building a **scalable Forex AI ecosystem**
  - 📚 Studying **Deep Reinforcement Learning** + Sim-to-Real transfer
  - 📈 Expanding skills in **data visualization** and business systems
  - ✍🏾 Writing a **metaphysical book** on soul, suffering & reincarnation

  ---

  ### 📌 Highlight Projects

  <div class="project-card">
    <h3>🧠 RL Traffic Optimizer</h3>
    <p>Reduced urban congestion using DQN & SUMO</p>
    <p><strong>Stack:</strong> Python, Stable-Baselines3, JavaScript</p>
  </div>

  <div class="project-card">
    <h3>💹 Forex Trading Tool</h3>
    <p>GUI for MT5 with trade overlays & control buttons</p>
    <p><strong>Stack:</strong> MQL5, Python, JavaScript</p>
  </div>

  <div class="project-card">
    <h3>🌐 Interactive Portfolio</h3>
    <p>Modern dev portfolio showcasing my journey</p>
    <p><strong>Stack:</strong> HTML, CSS, JavaScript, GitHub Pages</p>
  </div>

  ---

  ### 📊 GitHub Stats

  <p align="center">
    <img src="https://github-readme-stats.vercel.app/api?username=jdoohickey&show_icons=true&theme=tokyonight" width="48%" />
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=jdoohickey&layout=compact&theme=tokyonight" width="48%" />
  </p>

  <p align="center">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=jdoohickey&theme=tokyonight" width="48%" />
  </p>

  ---

  ### 💬 Quote I Live By

  > “Jack of all trades, **Master of most** — one system at a time.”  
  > – **I AM L.**

  <div align="center">
    <img src="https://komarev.com/ghpvc/?username=jdoohickey&label=PROFILE+VIEWS&color=00F7FF&style=flat" alt="Profile views" />
  </div>
</body>
</html>
