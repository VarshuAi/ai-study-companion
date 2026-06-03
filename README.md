<!-- ========================================================================= -->
<!--                        AI-STUDY-COMPANION — README                            -->
<!--       Cyberpunk Premium Theme  |  Animated SVGs  |  Live Badges          -->
<!-- ========================================================================= -->

<div align="center">

<!-- ============================== BANNER ============================== -->

<img src="https://capsule-render.vercel.app/api?type=color_wave&color=0:000000,30:002E1A,70:001A0D,100:000000&height=180&section=header&text=ai-study-companion&fontSize=48&fontColor=00FF88&fontAlignY=38&animation=fadeIn" width="100%"/>

<!-- ============================== TYPING SVG ============================== -->

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains%20Mono&weight=500&size=22&duration=3500&pause=800&color=00FF88&center=true&vCenter=true&multiline=true&repeat=true&random=false&width=700&height=80&lines=%3E%20Welcome%20to%20ai-study-companion%20%F0%9F%9A%80;%3E%20Built%20using%20JavaScript%20%7C%20Optimized%20%26%20Secure;%3E%20Cyberpunk%20Premium%20Theme%20Applied.)](https://github.com/VarshuAi/ai-study-companion)

<br/>

![Version](https://img.shields.io/badge/Version-1.0-00FF88?style=for-the-badge&logo=github&logoColor=black)
![Language](https://img.shields.io/badge/JavaScript-Tech-00CC66?style=for-the-badge&logo=javascript&logoColor=black)
![Status](https://img.shields.io/badge/Status-Active-14354C?style=for-the-badge&logo=git&logoColor=white)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,30:002E1A,70:001A0D,100:000000&height=60&section=header&text=&fontSize=0" width="100%"/>

</div>

<!-- ============================== ABOUT ============================== -->

<h2>
<img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30">
<samp>&nbsp;ABOUT</samp>
</h2>

```yaml
name: ai-study-companion
version: 1.0
type: Repository
author: VarshuAi
description: >
  No description available for this project.
primary_tech: JavaScript
```

<!-- ============================== CENTRAL GRAPHIC ============================== -->

<div align="center">
<br>
<div align="center"><img src="https://media.giphy.com/media/QasoFJEWN61ig/giphy.gif" alt="Cyberpunk Grid Animation" width="100%"/></div>
<br>
</div>

<!-- ============================== FEATURES ============================== -->

<h2>
<img src="https://media2.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif?cid=ecf05e47a0n3gi1bfqntqmob8g9aid1oyj2wr3ds3mg700bl&rid=giphy.gif" width="28">
<samp>&nbsp;FEATURES</samp>
</h2>

- **📺 100% In-Browser study Companion**: Minimize your command prompt. Everything happens directly inside LeetCode or Physics Wallah via a custom floating Study panel.
- **📸 Multimodal Whiteboard Capturer**: Pause your lecture on any handwritten equations, slides, code blocks, or diagrams, and click *Capture Lecture & Explain*. Playwright silently grabs a high-resolution screenshot of the `<video>` element on screen and feeds it directly to Gemini 3.5.
- **🧠 Automated Whiteboard OCR**: Gemini 3.5 reads the screen image, decodes formulas, and transcribes them cleanly, outlining core lecture theories and definitions in your sidebar.
- **💾 Local Markdown Notes Vault**: Captured summaries and concepts are logged locally on your PC under a subject folder: `notes/[Subject]/[Lecture_Title].md`. Perfect for off-line reading and Git integration!
- **🌐 Real Daily-Use Browser integration**: Scans your PC at launch for your installed **Google Chrome, Microsoft Edge, or Brave Browser**, letting you run the helper directly in your daily browser where you are already logged into YouTube or Physics Wallah!

---

<!-- ============================== COMMANDS ============================== -->

<h2>
<img src="https://media.giphy.com/media/iY8CRBdQXODJSCERIr/giphy.gif" width="28">
<samp>&nbsp;COMMANDS & USAGE</samp>
</h2>

### Prerequisites
- Make sure you have [**Node.js (v18+)**](https://nodejs.org/) installed.
- Playwright requires browser dependencies. Run the following commands in this directory:

### Step 1: Install Dependencies
Open your terminal inside the `ai-study-companion` directory and execute:
```bash
npm install
```

### Step 2: Configure Gemini API Key
We have pre-copied your Gemini key to the `.env` file in this directory. If you ever need to change it, simply update:
```env
GEMINI_API_KEY=cccdsdccvsffvfb-U87aq8KthY_-nd-DpI
```

### Step 3: Start the Study Helper!
Launch your standalone study assistant:
```bash
npm start
```
1. Select your preferred daily browser (Chrome, Edge, or Brave).
2. Go to YouTube or `pw.live` and log into your account.
3. Observe the glowing pink **`[Study AI]`** capsule button floating in the bottom-right corner.
4. Input your subject (e.g. Physics JEE) and lecture title, and click **Capture Lecture & Explain** to compile notes in real time!

---

*Keep your notes vault local, git-versioned, and completely customized. Happy studying! 🎓*

<!-- ============================== TECH STACK ============================== -->

<h2>
<img src="https://media2.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif?cid=ecf05e47a0n3gi1bfqntqmob8g9aid1oyj2wr3ds3mg700bl&rid=giphy.gif" width="28">
<samp>&nbsp;TECH STACK</samp>
</h2>

<div align="center">

#### `>> SYSTEM INVENTORY`
![JavaScript](https://img.shields.io/badge/JavaScript-Primary_Language-00FF88?style=for-the-badge&logoColor=black)
![Git](https://img.shields.io/badge/Git-VCS-00CC66?style=for-the-badge&logo=git&logoColor=white)

</div>

<!-- ============================== SETUP ============================== -->

<h2>
<img src="https://media.giphy.com/media/LnQjpWaON8nhr21vNW/giphy.gif" width="28">
<samp>&nbsp;SETUP</samp>
</h2>

```bash
# 1. Clone repository remote
git clone https://github.com/VarshuAi/ai-study-companion.git
cd ai-study-companion

# 2. Check technical prerequsites
# Ensure runtime matches requirements (JavaScript)
```

<!-- ============================== STRUCTURE ============================== -->

<h2>
<samp>&nbsp;📁 STRUCTURE</samp>
</h2>

```
ai-study-companion/
├── src/             # Source code entrypoints
├── docs/            # Project documentation files
├── README.md        # Interactive readme sheet
└── LICENSE          # Permission details
```

<!-- ============================== FOOTER ============================== -->

<div align="center">

<br/>

<img src="https://capsule-render.vercel.app/api?type=color_wave&color=0:000000,30:002E1A,70:001A0D,100:000000&height=80&section=footer&text=&fontSize=0" width="100%"/>

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains%20Mono&size=14&duration=4000&pause=1000&color=00FF88&center=true&vCenter=true&width=500&lines=Made+with+%E2%9D%A4%EF%B8%8F+by+VarshuAi;Build+Fast.+Ship+Secure.+Scale+Infinite.)](https://github.com/VarshuAi)

<br/>

[![GitHub](https://img.shields.io/badge/VarshuAi-Profile-00FF88?style=for-the-badge&logo=github&logoColor=black)](https://github.com/VarshuAi)
[![Repo](https://img.shields.io/badge/ai-study-companion-Repo-00CC66?style=for-the-badge&logo=github&logoColor=black)](https://github.com/VarshuAi/ai-study-companion)

<br/>

</div>
