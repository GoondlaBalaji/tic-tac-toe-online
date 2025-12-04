<p align="center">
  <img src="screenshots/banner.png" width="100%" alt="KA-POW Banner">
</p>

<h1 align="center">🎮 TIC-TAC-TOE: KA-POW! EDITION</h1>
<p align="center"><strong>A High-Impact Comic-Book Style Tic-Tac-Toe Game (Offline + Online Multiplayer)</strong></p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/JAVASCRIPT-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/FIREBASE-%23FFCA28.svg?style=for-the-badge&logo=firebase&logoColor=black"/>
  <img src="https://img.shields.io/badge/TONE.JS-%23733CFC.svg?style=for-the-badge&logoColor=white"/>
</p>

---

# 🚀 Test Run Link  
👉 **https://Goondlabalaji.github.io/tic-tac-toe-online/mode.html**

---

# 🎥 Game Preview (GIF)
<p align="center">
  <img src="screenshots/gameplay.gif" width="300" alt="Gameplay GIF">
</p>

---

# 🖼 Screenshots


<!-- MAIN TWO-COLUMN SCREENSHOT LAYOUT -->
<div style="display:flex; justify-content:center; gap:50px; margin-top:20px;">


<table align="center">
<tr>
<td>

<!-- LEFT COLUMN (3 Images) -->
<table align="center">
<tr>
<td>

<!-- LEFT COLUMN (3 Images with names) -->
<p align="center">
  <img src="images/online.png" width="300" style="border:4px solid #000; border-radius:6px;"><br>
  <b>Online Gameplay</b><br><br>

  <img src="images/offline.png" width="300" style="border:4px solid #000; border-radius:6px;"><br align="center">
  <b>Offline Gameplay</b><br><br>

  <img src="images/win.png" width="300" style="border:4px solid #000; border-radius:6px;"><br>
  <b>Win Animation</b><br><br>
</p>

</td>
<td>

<!-- RIGHT COLUMN (2 Images with names) -->
<p align="center">

  <img src="images/menu.png" width="300" style="border:4px solid #000; border-radius:6px;"><br>
  <b>Home Menu</b><br><br>

  <img src="images/mobileui.jpg" width="300" style="border:4px solid #000; border-radius:6px;"><br>
  <b>Mobile UI</b><br><br>

</p>

</td>
</tr>
</table>



</td>
</tr>
</table>


</div>



---

# ✨ Features

## 🧩 Offline Features
- Comic book-style UI  
- Explosive animations  
- Particle effects  
- Sound effects for every move  
- Win animations  
- Bonus fight-scene GIFs  
- No scrollbars  
- Full mobile support  

## 🌐 Online Multiplayer Features
- Create room / join room  
- Auto room code generator  
- Random first-player assignment  
- Live sync using Firebase  
- Win-line sync  
- GIF bonus scene sync  
- Real-time UI updates  

## 🔊 Audio System (Tone.js)
- X and O each have unique sound  
- Win fanfare  
- Draw noise  
- Comic-style floating text  

## 🎨 Pop-Art Comic UI
- Halftone background  
- Thick black comic borders  
- Skewed panels  
- Animated buttons  
- High-contrast shadows  

---

# 🗂 Folder Structure

```bash
project/
│
├── mode.html        
├── offline.html     
├── online.html      
├── ai.html          # optional
│
├── animation/       # GIF or MP4 scenes
│   ├── ani1.mp4
│   ├── ani2.mp4
│   ├── ani3.mp4
│   └── ...
│
├── images/          # Screenshots for README
│   ├── menu.png
│   ├── offline.png
│   ├── win.png
│   ├── online.png
│   ├── mobileui.jpg
│
├── screenshots/
│   ├── banner.png
│   └── gameplay.gif
│
└── scripts/
    └── main.js
