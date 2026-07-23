

<div align="center">
  <h1>
    <span id="greeting">👋 Hi, I'm</span>
    <span style="color:#FF69B4;" id="name">Asiya Ibrahim Ismail</span>
  </h1>
  
  <h3 id="subtitle" style="min-height: 30px;">
    <!-- Animated text will appear here -->
  </h3>

  <p align="center" id="status-indicator">
    <span style="font-size: 20px; animation: pulse 2s infinite;">🟢 Available for Projects</span>
  </p>
</div>

<script>
  // Animated typing effect
  const subtitle = "✨ Full-Stack Web App Developer | Creative Problem Solver | Tech Enthusiast ✨";
  const subtitleElement = document.getElementById('subtitle');
  let index = 0;

  function typeWriter() {
    if (index < subtitle.length) {
      subtitleElement.textContent += subtitle.charAt(index);
      index++;
      setTimeout(typeWriter, 50);
    }
  }

  // Greeting animation
  const greetingElement = document.getElementById('greeting');
  greetingElement.style.animation = 'wave 0.6s ease-in-out';

  // Name color animation
  const nameElement = document.getElementById('name');
  nameElement.style.animation = 'glow 2s ease-in-out infinite';

  // Start typing on page load
  window.addEventListener('load', typeWriter);

  // Add CSS animations
  const style = document.createElement('style');
  style.textContent = `
    @keyframes wave {
      0% { transform: rotate(0deg); transform-origin: 70% 70%; }
      10% { transform: rotate(14deg); transform-origin: 70% 70%; }
      20% { transform: rotate(-8deg); transform-origin: 70% 70%; }
      30% { transform: rotate(14deg); transform-origin: 70% 70%; }
      40% { transform: rotate(-4deg); transform-origin: 70% 70%; }
      50% { transform: rotate(10deg); transform-origin: 70% 70%; }
      60% { transform: rotate(0deg); transform-origin: 70% 70%; }
      100% { transform: rotate(0deg); transform-origin: 70% 70%; }
    }

    @keyframes glow {
      0%, 100% { 
        text-shadow: 0 0 10px #FF69B4, 0 0 20px #FF1493;
        color: #FF69B4;
      }
      50% { 
        text-shadow: 0 0 20px #FF69B4, 0 0 40px #FF1493, 0 0 60px #FF69B4;
        color: #FF1493;
      }
    }

    @keyframes pulse {
      0%, 100% { opacity: 1; }
      50% { opacity: 0.7; }
    }

    #subtitle {
      color: #00D9FF;
      font-weight: 600;
      font-size: 1.1em;
      min-height: 30px;
    }

    h1 {
      font-size: 3em;
      margin-bottom: 10px;
    }

    h1 span#greeting {
      display: inline-block;
      margin-right: 10px;
    }
  `;
  document.head.appendChild(style);
</script>

---

## 🚀 About Me  
🌟 Full-Stack Developer with strong passion for building **modern**, **responsive**, and **scalable** web applications.  
💡 Specializing in **Frontend (React, JS)** and **Backend (Express nodejs, PHP, SQL, APIs)** development.  
🎨 Love crafting beautiful UI/UX and functional business web-apps.  
🔥 Always learning, always building.

---

## 🛠️ Tech Stack & Skills

### 🎨 **Frontend**
<p>
  <img src="https://skillicons.dev/icons?i=html,css,js,react,bootstrap,tailwind" />
</p>

### ⚙️ **Backend**
<p>
  <img src="https://skillicons.dev/icons?i=php,mysql,nodejs,python" />
</p>

### 🧰 **Tools & Platforms**
<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode,figma,postman" />
</p>

---

## 🌟 Highlighted Strengths
✨ Building **clean & responsive UI**  
✨ Creating **real-world university & business systems**  
✨ Crafting **REST APIs**, authentication, dashboards  
✨ Writing optimized & maintainable code  

---

## 🚧 Projects I Build
🔹 Management Systems (University,Inventory & Arts)  
🔹 Weather Project 
🔹 Full-Stack CRUD Projects  
🔹 Real-world APIs  
🔹 Machine Learning Mini-Apps (Streamlit)

---

## 📊 GitHub Stats
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=AsiyaIbrahimIsmail&show_icons=true&theme=radical" height="170">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=AsiyaIbrahimIsmail&theme=radical" height="170">
</p>

---

## 🌐 Connect With Me  
<p align="left">
  <a href="#"><img src="https://www.linkedin.com/in/asiya-ibrahim-2310a72a2/" /></a>
  <a href="#"><img src="https://www.instagram.com/azuibrahim9/" /></a>
  <a href="#"><img src="https://skillicons.dev/icons?i=twitter" /></a>
</p>

---

<p align="center">
  ✨ *Thanks for visiting my profile — Always open to collaborations!* ✨
</p>
