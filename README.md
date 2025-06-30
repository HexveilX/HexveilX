<p align="center">
  <img src="https://capsule-render.vercel.app/api?text=Hey+There!&animation=fadeIn&type=waving&color=gradient&height=100"/>
</p>

<h1 align="center">I'm Hexveil👋</h1>

```yaml
name: ZYAD
current_work: TaleForge AI
learning: Web Dev + AI Integration
ask_me_about: dev, design, AI
```

---

### 🎯 Skills

![HTML](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=fff&style=flat)
![CSS](https://img.shields.io/badge/-CSS3-1572B6?logo=css3&logoColor=fff&style=flat)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=000&style=flat)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?logo=typescript&logoColor=fff&style=flat)
![React](https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=000&style=flat)
![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=fff&style=flat)
![C#](https://img.shields.io/badge/-C%23-239120?logo=c-sharp&logoColor=fff&style=flat)

---

### 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=HexveilX&show_icons=true&include_all_commits=true&count_private=true&theme=dracula&hide_border=false" height="150" />
  <img src="https://streak-stats.demolab.com?user=HexveilX&theme=dracula&hide_border=false" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=HexveilX&layout=compact&langs_count=8&theme=onedark&hide_border=false" height="140" />
</div>

---

### 🔸 Personal Touch

<p align="center">
  <img height="150" src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExdnh3OWx3ejRrYzFocnFpaDJxZ2dmOXd4endobGhnOGd5cmxleGNyZCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/4Ev0Ari2Nd9io/giphy.gif"/>
</p>

---

### 📢 Connect With Me

<p align="center">
  <a href="https://discord.com/users/zezolz" target="_blank">
    <img src="https://img.shields.io/badge/Discord-Zezolz-5865F2?logo=discord&logoColor=white" />
  </a>
</p>

---

### 🔥 AI + Design Projects

- 🧀 AI-powered Story Generator (TaleForge AI)
- 🎨 Logo & Design Tools with DALL·E / Leonardo
- 🛠️ Frontend Projects with React + Firebase

---

### 🔄 Contribution Snake

<details>
  <summary>Click to show animated graph</summary>

  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/HexveilX/HexveilX/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/HexveilX/HexveilX/output/github-contribution-grid-snake.svg">
    <img alt="github contribution graph" src="https://raw.githubusercontent.com/HexveilX/HexveilX/output/github-contribution-grid-snake.svg">
  </picture>
</details>

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=HexveilX&style=flat-square&color=blue" alt="GitHub Profile Views" />
  <img src="https://img.shields.io/github/followers/HexveilX?label=Followers&style=flat-square" />
</p>

---

### 🧞‍♂️ GitHub Actions Snake.yml

```yaml
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 0 * * *"  # كل يوم
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout 🕎️
        uses: actions/checkout@v3

      - name: Generate GitHub Contribution Snake 🐍
        uses: Platane/snk@v3
        with:
          github_user_name: HexveilX
          outputs: |
            ./output/github-contribution-grid-snake.svg
            ./output/github-contribution-grid-snake-dark.svg

      - name: Push snake.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: ./output
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
