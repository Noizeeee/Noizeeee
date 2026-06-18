<p align="center">
<svg width="100%" viewBox="0 0 900 120" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="hg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#0f2027"/>
      <stop offset="50%" stop-color="#203a43"/>
      <stop offset="100%" stop-color="#2c5364"/>
    </linearGradient>
    <linearGradient id="shine" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00f2fe" stop-opacity="0"/>
      <stop offset="50%" stop-color="#00f2fe" stop-opacity="0.15"/>
      <stop offset="100%" stop-color="#00f2fe" stop-opacity="0"/>
      <animateTransform attributeName="gradientTransform" type="translate" from="-1 0" to="1 0" dur="3s" repeatCount="indefinite"/>
    </linearGradient>
  </defs>

  <!-- background -->
  <rect width="900" height="120" rx="12" fill="url(#hg)"/>
  <rect width="900" height="120" rx="12" fill="url(#shine)"/>

  <!-- animated circuit dots -->
  <g fill="none" stroke="#00f2fe" stroke-opacity="0.25" stroke-width="1">
    <circle cx="60" cy="60" r="30">
      <animate attributeName="r" values="28;34;28" dur="3s" repeatCount="indefinite"/>
      <animate attributeName="stroke-opacity" values="0.15;0.4;0.15" dur="3s" repeatCount="indefinite"/>
    </circle>
    <circle cx="60" cy="60" r="18">
      <animate attributeName="r" values="16;22;16" dur="3s" begin="0.4s" repeatCount="indefinite"/>
    </circle>
    <circle cx="840" cy="60" r="30">
      <animate attributeName="r" values="28;34;28" dur="3s" begin="0.8s" repeatCount="indefinite"/>
      <animate attributeName="stroke-opacity" values="0.15;0.4;0.15" dur="3s" begin="0.8s" repeatCount="indefinite"/>
    </circle>
    <circle cx="840" cy="60" r="18">
      <animate attributeName="r" values="16;22;16" dur="3s" begin="1.2s" repeatCount="indefinite"/>
    </circle>

    <!-- horizontal lines -->
    <line x1="90" y1="60" x2="200" y2="60" stroke-dasharray="4 6">
      <animate attributeName="stroke-dashoffset" from="0" to="-20" dur="1.5s" repeatCount="indefinite"/>
    </line>
    <line x1="700" y1="60" x2="810" y2="60" stroke-dasharray="4 6">
      <animate attributeName="stroke-dashoffset" from="0" to="-20" dur="1.5s" repeatCount="indefinite"/>
    </line>

    <!-- small corner accents -->
    <rect x="20" y="20" width="12" height="12" rx="2" fill="#00f2fe" fill-opacity="0.2" stroke="none">
      <animate attributeName="fill-opacity" values="0.1;0.35;0.1" dur="2.5s" repeatCount="indefinite"/>
    </rect>
    <rect x="868" y="20" width="12" height="12" rx="2" fill="#00f2fe" fill-opacity="0.2" stroke="none">
      <animate attributeName="fill-opacity" values="0.1;0.35;0.1" dur="2.5s" begin="1s" repeatCount="indefinite"/>
    </rect>
    <rect x="20" y="88" width="12" height="12" rx="2" fill="#00f2fe" fill-opacity="0.2" stroke="none">
      <animate attributeName="fill-opacity" values="0.1;0.35;0.1" dur="2.5s" begin="0.5s" repeatCount="indefinite"/>
    </rect>
    <rect x="868" y="88" width="12" height="12" rx="2" fill="#00f2fe" fill-opacity="0.2" stroke="none">
      <animate attributeName="fill-opacity" values="0.1;0.35;0.1" dur="2.5s" begin="1.5s" repeatCount="indefinite"/>
    </rect>
  </g>

  <!-- name text -->
  <text x="450" y="52" text-anchor="middle" font-family="monospace" font-size="28" font-weight="700" fill="#ffffff" letter-spacing="4">
    Raine Ocampo
    <animate attributeName="fill-opacity" values="0.8;1;0.8" dur="4s" repeatCount="indefinite"/>
  </text>

  <!-- tagline -->
  <text x="450" y="80" text-anchor="middle" font-family="monospace" font-size="13" fill="#00f2fe" letter-spacing="2" fill-opacity="0.85">
    ⚡ Embedded Systems · IoT · Computer Vision · Software Dev ⚡
  </text>

  <!-- bottom border glow line -->
  <line x1="80" y1="108" x2="820" y2="108" stroke="#00f2fe" stroke-opacity="0.3" stroke-width="1" stroke-dasharray="8 12">
    <animate attributeName="stroke-dashoffset" from="0" to="-40" dur="2s" repeatCount="indefinite"/>
  </line>
</svg>
</p>

🎓 Computer Engineering Student at Pampanga State University

I'm passionate about Embedded Systems, IoT, Computer Vision, and Software Development. I enjoy building projects that combine hardware and software to solve real-world problems.

---

## 🚀 About Me

* 🔭 Currently exploring Embedded Systems and IoT Development
* 🌱 Learning Advanced Python Development and Computer Vision
* 💡 Interested in Automation, Signal Processing, and Smart Systems
* 🎯 Goal: Become a Software / Embedded Systems Engineer

---

## 🌐 Digital Portfolio

<p align="center">
  <a href="https://noizeeee.github.io" target="_blank">
    <img src="https://img.shields.io/badge/🚀_Visit_My_Portfolio-0A66C2?style=for-the-badge&logo=google-chrome&logoColor=white" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Embedded%20Systems-Expertise-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/IoT-Projects-success?style=flat-square" />
  <img src="https://img.shields.io/badge/Computer%20Vision-OpenCV-orange?style=flat-square" />
  <img src="https://img.shields.io/badge/Software-Development-purple?style=flat-square" />
</p>

<p align="center">
  <i>
    Explore my engineering projects, technical portfolio,
    certifications, and project documentation.
  </i>
</p>

---

## 💭 Developer Quote

<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" />
</p>

---

## 🛠️ Technical Skills

### Languages

<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="45"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="45"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" width="45"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="45"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" width="45"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" width="45"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="45"/>
</p>

### Tools & Technologies

<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="45"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="45"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" width="45"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/opencv/opencv-original.svg" width="45"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/qt/qt-original.svg" width="45"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/firebase/firebase-plain.svg" width="45"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/arduino/arduino-original.svg" width="45"/>
</p>

---

## 📈 GitHub Stats

<p align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=Noizeeee&show_icons=true&theme=tokyonight" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Noizeeee&theme=tokyonight" />
</p>

---

## 📂 Featured Projects

### 🤖 ESP32-S3 CAM-Based Automated Resistor Sorter

Automated resistor classification system using ESP32-S3 CAM, OpenCV, and servo-based sorting mechanisms.

**Tech Stack:** ESP32-S3, OpenCV, Python, Arduino IDE
**Repository:** Coming Soon

---

### 📊 Digital Signal Processing Application

Desktop application for signal analysis, filtering, Fourier transforms, Z-transforms, and spectral visualization.

**Tech Stack:** Python, Qt, NumPy, Matplotlib
**Repository:** [DSP Simulator](https://github.com/alphrancis/DSP-Simulator-ng-mga-GOAT-w-Feedback-from-Lebron)

---

### 🔐 IoT-Based Smart Locker

RFID and keypad-secured locker system with real-time monitoring and database integration.

**Tech Stack:** Arduino, RFID, Firebase, Embedded C

---

### 💧 IoT-Based Smart Plant Watering System

Automated irrigation system using soil moisture sensors and web-based monitoring.

**Tech Stack:** ESP32, Sensors, Firebase, IoT

---

### ⚙️ Operating System Algorithm Visualizer

Interactive simulator for CPU scheduling and page replacement algorithms.

**Tech Stack:** Java, GUI Development, Operating Systems

**Repository:** [OS Visualizer](https://github.com/clarencze/OS-VISUALIZER)

**Live Demo:** https://osvisualizer.onrender.com/

---

### 🧮 Web-Based Numerical Methods Calculator

Web application for solving systems of linear equations using various numerical methods and interactive result visualization.

**Tech Stack:** JavaScript, HTML/CSS, Firebase, Git

**Repository:** [WebBased Numerical Methods Calculatror](https://github.com/Jviscoding/Numerical-Method)

**Live Demo:** https://numerical-method.pages.dev/

---

## 🎯 Current Focus

* Embedded Systems Development
* Computer Vision with OpenCV
* Internet of Things (IoT)
* Software Engineering Best Practices
* Data Structures & Algorithms

---

## 📫 Connect With Me

* 📧 Email: [raineaveryocampo@gmail.com](mailto:raineaveryocampo@gmail.com)
* 💻 GitHub: https://github.com/Noizeeee

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Noizeeee&label=Profile%20Views&color=0e75b6&style=flat" />
</p>
