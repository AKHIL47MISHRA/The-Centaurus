# The-Centaurus


<h2 align="left">Hi 👋! My name is AKHIL MISHRA and I'm a BEGINNER DEVELOPER, from INDIA.</h2>

###

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=maurodesouza&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=dracula&locale=en&hide_border=false" height="150" alt="stats graph"  />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=maurodesouza&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=dracula&hide_border=false" height="150" alt="languages graph"  />
</div>

###

<img align="right" height="150" src="https://i.imgflip.com/65efzo.gif"  />

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="30" alt="javascript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="30" alt="typescript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="30" alt="react logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="30" alt="html5 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="30" alt="css3 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="30" alt="python logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" height="30" alt="csharp logo"  />
</div>

###

<div align="left">
  <img src="https://img.shields.io/static/v1?message=Youtube&logo=youtube&label=&color=FF0000&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="youtube logo"  />
  <img src="https://img.shields.io/static/v1?message=Instagram&logo=instagram&label=&color=E4405F&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="instagram logo"  />
  <img src="https://img.shields.io/static/v1?message=Twitch&logo=twitch&label=&color=9146FF&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="twitch logo"  />
  <img src="https://img.shields.io/static/v1?message=Discord&logo=discord&label=&color=7289DA&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="discord logo"  />
  <img src="https://img.shields.io/static/v1?message=Gmail&logo=gmail&label=&color=D14836&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="gmail logo"  />
  <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="linkedin logo"  />
</div>

###

<br clear="both">

<img src="https://raw.githubusercontent.com/maurodesouza/maurodesouza/output/snake.svg" alt="Snake animation" />
name: Generate snake animation

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"

  workflow_dispatch:

  push:
    branches:
    - master

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    timeout-minutes: 5

    steps:
      - name: generate snake.svg
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: dist/snake.svg?palette=github-dark


      - name: push snake.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

###

# 👨‍💻 Hi, I'm [AKHIL MISHRA]! 👩‍💻

### Full-Stack Developer | Python Enthusiast

Welcome to my GitHub profile! I’m passionate about building web applications, solving problems, and learning new technologies. I’m currently diving deep into **Full-Stack Development** and learning **Python** AND IN UPCOMING TIME WILL DO MORE.

![Profile Image]([https://your-image-url.com](https://avatars.githubusercontent.com/u/156499973?v=4)) <!-- Replace with your image URL -->

---

## 🔧 Technologies & Tools

**Frontend:**  
- HTML, CSS, JavaScript, MONGODB, node.js  
- Tailwind CSS, Bootstrap

**Backend:**  
- Node.js, Express.js, Django, Flask (Python)  
- RESTful APIs, GraphQL



**Version Control & DevOps:**  
- Git, GitHub, Docker, 

**Learning Python:**  
- Python basics, OOP, Web scraping, Automation  
- Working with libraries like Flask and Django

---

## 📈 GitHub Stats

![Your GitHub Stats](https://github-readme-stats.vercel.app/api?username=akhil47mishra&show_icons=true&hide_title=true&count_private=true&hide=prs)  
<!-- Replace 'your-username' with your GitHub username -->

---

## 🌱 Currently Learning

- Advanced **Python** (Data Structures, Algorithms, Flask)
- **node.js** ( concepts)
- **Machine Learning** with Python
- **web development** (Expanding frontend skills)
- **blackhat work**(just keep eye's on..) 

---

## 💼 Projects

Here are some of the projects I’ve worked on:

### 1. [Project Name 1](https://github.com/your-username/project-1)
- **Description:** A full-stack web app built with React, Node.js, and MongoDB.  
- **Technologies:** React, Node.js, MongoDB, Express.js  
- **Live Demo:** [Link to live demo](https://your-demo-link.com)

### 2. [Project Name 2](https://github.com/your-username/project-2)
- **Description:** A Python-based web scraper that collects data from various websites.  
- **Technologies:** Python, BeautifulSoup, Requests  
- **Demo:** [Link to demo](https://your-demo-link.com)

---

## 🌟 Connect with Me

- [LinkedIn](https://www.linkedin.com/in/akhil-kumar-11518128a?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)
- [Twitter](https://twitter.com/your-profile)
- [Website/Portfolio](https://your-portfolio.com)

---

## 📫 How to reach me

Feel free to open an issue or send me a message if you want to collaborate or have questions! You can also contact me via:

- Email:akhilkumar017147@gmail.com

---

> “The only way to learn a new programming language is by writing programs in it.” – Dennis Ritchie

---























<h1 align="center">Hi 👋, I'm AKHIL MISHRA</h1>
<h3 align="center">A passionate developer from India</h3>

<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=akhil47mishra" alt="akhil47mishra" /></a> </p>

- 🔭 I’m currently working on **PYTHON LANGUAGE**

- 🌱 I’m currently practicing **FULL STACK DEVELOPMENT,PYHTON**

- 👨‍💻 All of my projects are available at [https://github.com/AKHIL47MISHRA](https://github.com/AKHIL47MISHRA)

- 📫 How to reach me **https://www.linkedin.com/in/akhil-kumar-11518128a?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app**

- ⚡ Fun fact **ALSO GIVE TIME TO TG AND CALLED A TECHINAL BANDA**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/akhil kumar" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="akhil kumar" height="30" width="40" /></a>
<a href="https://www.youtube.com/c/the mishra's code" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="the mishra's code" height="30" width="40" /></a>
<a href="https://www.codechef.com/users/akhil47mishra" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.1.0/icons/codechef.svg" alt="akhil47mishra" height="30" width="40" /></a>
<a href="https://www.leetcode.com/akhil47mishra" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/leet-code.svg" alt="akhil47mishra" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>

<p><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=akhil47mishra&show_icons=true&locale=en&layout=compact" alt="akhil47mishra" /></p>
