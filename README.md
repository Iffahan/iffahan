<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?lines=Welcome+to+my+GitHub+Profile!;Hi+there+👋,+I'm+Iffahan+Suksuwan&center=true&width=380&height=45">

  <p align="center">
    <img src="https://img.shields.io/badge/Focus-Web%20Development-brightgreen" />
    <img src="https://img.shields.io/badge/Focus-Mobile%20Apps-blue" />
    <img src="https://img.shields.io/badge/Focus-Embedded%20Systems-red" />
  </p>
</div>

## 🚀 About Me

I'm a passionate developer focused on creating innovative solutions across web, mobile, and embedded systems. I love learning new technologies and building things that make a difference.

```bash
const developer = {
    name: "Iffahan Suksuwan",
    interests: ["Web Development", "Mobile Apps", "Embedded Systems"],
    email: "iffahan.suksuwan@gmail.com",
    currentlyLearning: ["Python", "JavaScript", "Dart"],
    lookingToCollaborate: true
}
```markdown project="GitHub Profile" file="README.md"
...
```

## 💻 Tech Stack

### Languages

`<p align="left">
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" />
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" />
</p>`### Frameworks & Libraries

`<p align="left">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vue.js&logoColor=4FC08D" />
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Express.js-404D59?style=for-the-badge" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Go_Fiber-00ADD8?style=for-the-badge&logo=go&logoColor=white" />
</p>`### Hardware & IoT

`<p align="left">
  <img src="https://img.shields.io/badge/Microcontrollers-CC0000?style=for-the-badge&logo=arduino&logoColor=white" />
</p>`## 📊 GitHub Stats

`<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&theme=radical" alt="GitHub Stats" />
</div>``<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_GITHUB_USERNAME&theme=radical" alt="GitHub Streak" />
</div>`## 🌐 Connect with Me

`<p align="left">
  <a href="mailto:iffahan.suksuwan@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>`---

`<div align="center">
  <img src="https://komarev.com/ghpvc/?username=YOUR_GITHUB_USERNAME&color=blueviolet&style=flat-square&label=Profile+Views" />
</div>``<!-- Snake animation -->`



```plaintext

To make this README fully functional, you'll need to:

1. Replace `YOUR_GITHUB_USERNAME` with your actual GitHub username in the URLs.

2. To get the snake animation working, you'll need to create a GitHub Action. Create a new file `.github/workflows/snake.yml` with this content:

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: YOUR_GITHUB_USERNAME
          svg_out_path: dist/github-contribution-grid-snake.svg
          
      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```
