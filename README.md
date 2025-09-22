name: Contribution snake

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:

jobs:
  build:
    name: Jobs to update snake grid
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: madushadhanushka
          svg_out_path: dist/github-contribution-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
<h1 align="center">
Ramaikan Lalu Hytamkan 😏
</h1>

<!--
**Fadhill21/Fadhill21** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
 <p align="center">
   <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExcmh6YzdmMnZidmtlOGtueXR5aWZmYzB6dzZ2bzJrajJiY3Y1OTVjeSZlcD12MV9naWZzX3NlYXJjaCZjdD1n/mXggOh7xql7MI/giphy.gif" alt="hai" width="300px">
 <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNmhyNWlsaGQxeWFiZDZyZGtvdnJ6OW96NGF1dXJpamlvczcya2NxaCZlcD12MV9naWZzX3NlYXJjaCZjdD1n/HmO7FZjok6mhW/giphy.gif" alt="hai" width="300px">
  </p>

  
<p align="center">
  <img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white">
   <img src="https://img.shields.io/badge/Spotify-1ED760?&style=for-the-badge&logo=spotify&logoColor=white">
  <img src="https://img.shields.io/badge/YouTube_Music-FF0000?style=for-the-badge&logo=youtube-music&logoColor=white">
  <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white">
  <img src="https://img.shields.io/badge/Crunchyroll-F47521?style=for-the-badge&logo=crunchyroll&logoColor=white">
</p>


