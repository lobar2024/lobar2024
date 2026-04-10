<!-- ===================== README.md ===================== -->

<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=34&duration=2500&pause=800&color=F472B6&center=true&vCenter=true&width=800&lines=Lobar+Farxodova;Future+Software+Engineer;Backend+%7C+Frontend+%7C+Cybersecurity;Building+My+Dream+Career+✨" />
</h1>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=lobar2024&label=Profile+Views&color=F472B6&style=for-the-badge"/>
</p>

---

## 🌸 About Me

<img align="right" width="260" src="https://media.giphy.com/media/f3iwJFOVOwuy7K6FFw/giphy.gif"/>

```yaml
name: Lobar Farxodova
role: Student
location: Khorezm, Uzbekistan

traits:
  - Night Coder 🌙
  - Passionate Learner 📚
  - Tech Explorer 🚀

interests:
  - Backend Development ⚙️
  - Frontend Design 🎨
  - Cybersecurity 🔐

goal: Becoming a strong and creative Software Engineer 💻✨
```

---

## 🚀 Tech Stack

### ⚡ Backend
<p>
<img src="https://skillicons.dev/icons?i=python,django,flask,nodejs"/>
</p>

### 🎨 Frontend
<p>
<img src="https://skillicons.dev/icons?i=html,css,js,react"/>
</p>

### 🛢 Database
<p>
<img src="https://skillicons.dev/icons?i=postgres,mysql,sqlite"/>
</p>

### 🧰 Tools & Others
<p>
<img src="https://skillicons.dev/icons?i=git,github,docker,linux,vscode"/>
</p>

---

## 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=lobar2024&show_icons=true&theme=tokyonight&icon_color=F472B6&title_color=A78BFA&text_color=ffffff&bg_color=0d1117"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=lobar2024&layout=compact&theme=tokyonight&title_color=F472B6&text_color=ffffff&bg_color=0d1117"/>
</p>

---

## 🔥 Contribution Snake

<p align="center">
  <img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg"/>
</p>

---

## 🌟 Fun Zone

💡 I believe coding is not just writing code — it's creating something meaningful  
🌙 I do my best work at night when everything is quiet  
🚀 Always trying to improve myself and learn new technologies  
🎯 Dream: Become a top-level developer and build impactful products  

---

## 📬 Connect With Me

<p align="center">
  <a href="https://t.me/lobaar26">
    <img src="https://img.shields.io/badge/Telegram-F472B6?style=for-the-badge&logo=telegram&logoColor=white"/>
  </a>
  <a href="https://linkedin.com/in/lobar2024">
    <img src="https://img.shields.io/badge/LinkedIn-A78BFA?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:qodirovjavohir2109@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-F9A8D4?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:F472B6,100:A78BFA&height=140&section=footer&animation=fadeIn"/>
</p>

<!-- ===================== SNAKE WORKFLOW ===================== -->
<!-- BUNI .github/workflows/main.yml FILE GA QO'YASAN -->

name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - uses: Platane/snk@master
        with:
          github_user_name: lobar2024
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
