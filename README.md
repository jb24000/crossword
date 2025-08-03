# 🎮 NES Crossword  

A retro NES‑style crossword puzzle game with leaderboard, light/dark mode, sound effects, and multiplayer support. Built with modern web tech but designed to feel like a classic 8‑bit game.  

---

## 🚀 Features  

- 🕹️ **Retro Pixel Design** with [Press Start 2P](https://fonts.google.com/specimen/Press+Start+2P)  
- 🌗 **Dark / Light Mode** toggle  
- 👥 **Single Player & Two‑Player Modes**  
- 🏆 **Local Leaderboard** stored in browser `localStorage`  
- 🔊 **Background Music & Sound Effects** (toggleable)  
- 🧩 **Dynamic Crossword Generation** with live dictionary clues  
- 💡 **Hints, Puzzle Reveal, & Word Checking**  
- 📱 **Responsive & PWA‑ready**  

---

## 📸 Screenshots  

<p align="center">
  <img src="assets/screenshot-dark.png" alt="NES Crossword Dark Mode" width="45%">
  <img src="assets/screenshot-light.png" alt="NES Crossword Light Mode" width="45%">
</p>  

---

## 🛠️ Tech Stack  

<p align="center">
  <a href="https://developer.mozilla.org/en-US/docs/Web/HTML">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" alt="HTML5" width="40" height="40"/>
  </a>
  <a href="https://developer.mozilla.org/en-US/docs/Web/CSS">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" alt="CSS3" width="40" height="40"/>
  </a>
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" width="40" height="40"/>
  </a>
  <a href="https://dictionaryapi.dev/">
    <img src="https://img.icons8.com/?size=100&id=lH1eEc9NMRnw&format=png&color=000000" alt="Dictionary API" width="40" height="40"/>
  </a>
  <a href="https://developers.google.com/youtube/iframe_api_reference">
    <img src="https://img.icons8.com/?size=100&id=19318&format=png&color=000000" alt="YouTube API" width="40" height="40"/>
  </a>
</p>  

---

## 📂 Installation  

```bash
git clone https://github.com/jb24000/nes-crossword.git
cd nes-crossword
Then open index.html in your browser,
or serve locally for PWA caching:

python3 -m http.server 8080
Visit http://localhost:8080.

🎮 How to Play
Enter player name(s) in the lobby.

Select a difficulty (Kids, Easy, Medium, Hard).

Use 🌙 Dark/Light Mode toggle and 🔊 Sound toggle.

Press Start Game.

Type letters on your keyboard into the highlighted squares.

Complete all words before the timer runs out.

Scoring System:

✅ +10 points per solved word
⏱️ Time bonus for fast completion
⚠️ Hints deduct points (first hint free)

🏆 Leaderboard
. Saves best scores per difficulty in your browser
. Displays top 5 players for each mode
. Persistent using localStorage

📜 License
MIT License.
Feel free to fork, play, and contribute 🎮

⭐ Acknowledgements
. 🎨 Font: Press Start 2P
. 📚 Clues: Free Dictionary API
. 🎵 Music: YouTube IFrame API


