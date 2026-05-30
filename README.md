# 🎓 Universal AI Study Companion & Note-Taker (YouTube & pw.live)

> An isolated, elite personal learning assistant that injects an interactive study dashboard directly into YouTube and **`pw.live` (Physics Wallah)**! 

Minimize your terminal and stay focused on your learning. This tool runs in the background, rendering a gorgeous, glassmorphic companion widget directly on your browser lecture pages. Simply pause a video and click a button to let Gemini 3.5's **multimodal vision** read slides/whiteboards and transcribe equations directly into your personal local study notes!

---

## ✨ Features

- **📺 100% In-Browser study Companion**: Minimize your command prompt. Everything happens directly inside LeetCode or Physics Wallah via a custom floating Study panel.
- **📸 Multimodal Whiteboard Capturer**: Pause your lecture on any handwritten equations, slides, code blocks, or diagrams, and click *Capture Lecture & Explain*. Playwright silently grabs a high-resolution screenshot of the `<video>` element on screen and feeds it directly to Gemini 3.5.
- **🧠 Automated Whiteboard OCR**: Gemini 3.5 reads the screen image, decodes formulas, and transcribes them cleanly, outlining core lecture theories and definitions in your sidebar.
- **💾 Local Markdown Notes Vault**: Captured summaries and concepts are logged locally on your PC under a subject folder: `notes/[Subject]/[Lecture_Title].md`. Perfect for off-line reading and Git integration!
- **🌐 Real Daily-Use Browser integration**: Scans your PC at launch for your installed **Google Chrome, Microsoft Edge, or Brave Browser**, letting you run the helper directly in your daily browser where you are already logged into YouTube or Physics Wallah!

---

## 🧭 Multimodal Study Architecture

```mermaid
sequenceDiagram
    participant User as Student (Browser)
    participant Sidebar as Study Sidebar (Shadow DOM)
    participant Script as Local study.js (Node.js & Playwright)
    participant Gemini as Gemini 3.5 (Vision & Multimodal)
    participant Disk as Local Notes Vault

    User->>User: Play video on YouTube or pw.live
    User->>Sidebar: Click "📸 Capture & Explain"
    Sidebar->>Script: Exposed Bridge: bridgeExplainFrame(subject, lecture, query)
    Script->>Script: Playwright screenshots HTML5 <video> element
    Script->>Gemini: Send screenshot + multimodal prompt
    Note over Gemini: OCR math equations, decode diagrams,<br/>and transcribe lecture board.
    Gemini-->>Script: Return structured study notes
    Script->>Disk: Append note to notes/[Subject]/[Lecture].md
    Script-->>Sidebar: Return HTML study guide
    Sidebar->>User: Display beautiful glassmorphic notes on screen
```

---

## 🚀 Installation & Running

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
GEMINI_API_KEY=AIzaSyBic7E224vK8efI-U87aq8KthY_-nd-DpI
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
