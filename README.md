<!-- View Count -->
<p align="left"> <img src="https://komarev.com/ghpvc/?username=abdifatah-com&label=Profile%20views&color=0e75b6&style=flat" alt="abdifatah-com" /> </p>

<!-- Intro -->
<h1 align="center">Hi 👋, I'm Abdifatah Faisal Yusuf</h1>
<h3 align="center">A Passionate Digital Marketer, Developer & Content Creator from Somaliland 🇸🇴</h3>

<!-- Snake Animation -->
<p align="center">
  <img src="https://github.com/abdifatah-com/abdifatah-com/blob/output/github-contribution-grid-snake.svg" alt="snake" />
</p>

<!-- Typing effect -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&pause=1000&center=true&vCenter=true&width=440&lines=Digital+Marketer;Frontend+Developer;Content+Creator;Brand+Strategist" alt="Typing SVG" />
</p>

---

### 💻 About Me:
- 🔭 I’m currently building brands at **Digital Boost Agency**  
- 📈 Helping businesses grow with digital strategy & SEO  
- 🎨 Love designing, editing, and content creation  
- 🌱 Currently leveling up in **React, PHP, and Marketing Automation**  
- ✉️ Reach me at: **abdifatahfaisal9@gmail.com**  
- 💬 Ask me about branding, web design, or social media  
- ⚡ Fun fact: I once grew 8,000+ followers in 2 months organically 😎

---

### 🛠️ Tech Stack:
<p align="left">
  <img src="https://skillicons.dev/icons?i=html,css,js,react,php,mysql,figma,github,git,vscode,python,wordpress,linux" />
</p>

---

### 📈 GitHub Stats:
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=abdifatah-com&show_icons=true&theme=radical" alt="Abdifatah's GitHub stats" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=abdifatah-com&theme=radical" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=abdifatah-com&layout=compact&theme=radical" />
</p>

---

### 🔗 Connect with Me:
<p align="left">
  <a href="https://linkedin.com/in/abdifatahfaisal" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@v4/icons/linkedin.svg" alt="linkedin" height="30" width="30" /></a>
  <a href="https://twitter.com/abdifatahfaisal" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@v4/icons/twitter.svg" alt="twitter" height="30" width="30" /></a>
  <a href="https://www.youtube.com/@DigitalBoostSo" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@v4/icons/youtube.svg" alt="youtube" height="30" width="30" /></a>
</p>

---

### 📍 Featured Repos:
[Anime State Brand Awareness Project](https://github.com/abdifatah-com/anime-awareness)  
[Digital Boost Social Media Project](https://github.com/abdifatah-com/digital-boost)  

---

### 🐍 Snake Contribution Magic:
> To activate the snake:
1. Go to your GitHub repo `abdifatah-com/abdifatah-com`
2. Create a folder called `.github/workflows`
3. Inside, create a file named `snake.yml` and paste the following:

```yml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@master
        with:
          github_user_name: abdifatah-com
          outputs: |
            dist/github-contribution-grid-snake.svg
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
