<div align="center">

<!-- Animated Hindi greeting (नमस्कार) -->
<svg width="100%" height="160" viewBox="0 0 800 160" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Animated Namaskar in Hindi">
  <!-- Background (transparent) -->
  <rect width="100%" height="100%" fill="transparent"/>

  <!-- Drop shadow filter for a soft look -->
  <defs>
    <filter id="f" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="4" result="b"/>
      <feOffset dx="0" dy="6" result="o"/>
      <feMerge>
        <feMergeNode in="o"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- The greeting text is split into tspans so each character can animate sequentially -->
  <text x="50%" y="55%" text-anchor="middle" font-family="Devanagari, 'Noto Sans Devanagari', Roboto, sans-serif" font-weight="700" font-size="72" fill="#0b5cff" filter="url(#f)">
    <!-- Use individual tspans for each visible glyph to create a staggered fade-in / slight rise animation -->
    <tspan id="c1" dx="0" dy="0">न</tspan>
    <tspan id="c2" dx="0" dy="0">म</tspan>
    <tspan id="c3" dx="0" dy="0">स</tspan>
    <tspan id="c4" dx="0" dy="0">्</tspan>
    <tspan id="c5" dx="0" dy="0">क</tspan>
    <tspan id="c6" dx="0" dy="0">ा</tspan>
    <tspan id="c7" dx="0" dy="0">र</tspan>

    <!-- small polite ending (optional) -->
    <tspan id="c8" dx="12" dy="0" font-size="36" fill="#0b5cff">👋</tspan>
  </text>

  <!-- Per-letter animations: fade in + tiny upward motion, then subtle bounce -->
  <!-- Character 1 -->
  <animate xlink:href="#c1" attributeName="opacity" from="0" to="1" begin="0s" dur="0.18s" fill="freeze"/>
  <animateTransform xlink:href="#c1" attributeName="transform" type="translate" from="0,10" to="0,0" begin="0s" dur="0.22s" fill="freeze"/>

  <!-- Character 2 -->
  <animate xlink:href="#c2" attributeName="opacity" from="0" to="1" begin="0.14s" dur="0.18s" fill="freeze"/>
  <animateTransform xlink:href="#c2" attributeName="transform" type="translate" from="0,10" to="0,0" begin="0.14s" dur="0.22s" fill="freeze"/>

  <!-- Character 3 -->
  <animate xlink:href="#c3" attributeName="opacity" from="0" to="1" begin="0.28s" dur="0.18s" fill="freeze"/>
  <animateTransform xlink:href="#c3" attributeName="transform" type="translate" from="0,10" to="0,0" begin="0.28s" dur="0.22s" fill="freeze"/>

  <!-- Virama (्) - appears quickly -->
  <animate xlink:href="#c4" attributeName="opacity" from="0" to="1" begin="0.40s" dur="0.12s" fill="freeze"/>
  <animateTransform xlink:href="#c4" attributeName="transform" type="translate" from="0,6" to="0,0" begin="0.40s" dur="0.16s" fill="freeze"/>

  <!-- Character 5 -->
  <animate xlink:href="#c5" attributeName="opacity" from="0" to="1" begin="0.52s" dur="0.18s" fill="freeze"/>
  <animateTransform xlink:href="#c5" attributeName="transform" type="translate" from="0,10" to="0,0" begin="0.52s" dur="0.22s" fill="freeze"/>

  <!-- Character 6 (vowel sign) -->
  <animate xlink:href="#c6" attributeName="opacity" from="0" to="1" begin="0.66s" dur="0.16s" fill="freeze"/>
  <animateTransform xlink:href="#c6" attributeName="transform" type="translate" from="0,8" to="0,0" begin="0.66s" dur="0.18s" fill="freeze"/>

  <!-- Character 7 -->
  <animate xlink:href="#c7" attributeName="opacity" from="0" to="1" begin="0.80s" dur="0.18s" fill="freeze"/>
  <animateTransform xlink:href="#c7" attributeName="transform" type="translate" from="0,10" to="0,0" begin="0.80s" dur="0.22s" fill="freeze"/>

  <!-- Emoji wave -->
  <animate xlink:href="#c8" attributeName="opacity" from="0" to="1" begin="0.96s" dur="0.18s" fill="freeze"/>

  <!-- subtle looped shimmer over the whole text every 4s -->
  <rect x="0" y="0" width="800" height="160" fill="transparent">
    <animate attributeName="opacity" from="0" to="0" begin="0s" dur="4s" repeatCount="indefinite"/>
  </rect>
</svg>

</div>

# 💫 About Me:
I am pursuing Bachelors in Information Technology<br>


![Anime Animation](https://media.giphy.com/media/ohT97gdpR40vK/giphy.gif?cid=ecf05e47a9xpxa7buzyu6xzhhihtg0o63ijuli8716xecyqx&ep=v1_gifs_related&rid=giphy.gif&ct=g)
![When the coding meme](https://media.tenor.com/XwP_bQ8-OMgAAAAC/when-the-coding-when-the-coding.gif)
# 💻 Tech Stack:
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=white) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Node.js](https://img.shields.io/badge/node.js-%2343853d.svg?style=for-the-badge&logo=node.js&logoColor=white)
# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=x-neon-nexus-o&theme=bear&hide_border=false&include_all_commits=false&count_private=false)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=x-neon-nexus-o&theme=bear&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=x-neon-nexus-o&theme=bear&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

---
[![](https://visitcount.itsvg.in/api?id=x-neon-nexus-o&icon=0&color=12)](https://visitcount.itsvg.in)

