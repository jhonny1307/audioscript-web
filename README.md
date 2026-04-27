# 🎧 Audio Script

**Audio Script** is a lightweight browser-based tool for recording, organizing, and generating segmented audio from a script.

It started as a challenge:

> *"Can AI replace a developer for this kind of tool?"*

Short answer: yes.  
Long answer: yes… and it kept getting better.

---

## 🚀 Features

* ✂️ Split your script into multiple segments
* 🎙️ Record each segment individually
* 🔁 Re-record any segment instantly
* ⏹️ Stop or interrupt recordings safely
* 📂 Upload external audio files (mp3, wav, etc.)
* ❤️ Toggle favorite segments (include/exclude in final audio)
* 🧠 Automatic saving (no save button needed)
* 💾 Persistent storage using `localStorage`
* 🧹 One-click project reset
* 🧩 Inline comments using `//`

  * Displayed as visual notes (not audio)
* 🔊 Merge selected segments into a single `.wav` file
* 🔀 Option to generate using all segments (ignore toggle)
* ⏱️ Configurable gap between segments
* 📱 Mobile-friendly interactions (including vibration feedback)
* 🎨 Clean UI with improved readability and structure

---

## 🧠 How to Use

1. Paste your script into the text box
2. Add comments using `//` when needed:
```
Line 1
Line 2
// pause here
Line 3
```
3. Click **Split**
4. Record or upload audio for each segment
5. Optionally mark preferred segments using the toggle
6. Click:
- **Generate final audio** (selected only)
- **Generate final audio (with all)** (ignores toggle)
7. Download your final file automatically

---

## 💾 Saving System

* Everything is saved automatically
* Uses browser `localStorage`
* No accounts, no backend, no tracking
* Reopening the page restores your project instantly

---

## ⚠️ Clear Button

The **Clear** button:

* Deletes all saved data
* Reloads the page instantly

There is no undo.  
There is only regret.

---

## 🧱 Tech Stack

* HTML
* CSS
* JavaScript (Vanilla)
* Web Audio API
* MediaRecorder API

No frameworks. No dependencies. No excuses.

---

## 🌍 Live Version

👉 https://audioscript-web.vercel.app/

---

## 📦 Project Repository

👉 https://github.com/jhonny1307/audioscript-web

---

## 🧩 Why This Exists

This project came from a simple experiment:

> Take an existing idea  
> Rebuild it using AI  
> Keep improving it until it stops being simple  

Somewhere between curiosity and chaos… this happened.

---

## 🤖 Credits

Built with the help of **ChatGPT**

---

## 📜 License

Do whatever you want with it.  
Seriously.

---

## 📌 Latest Update - V10  
**Date:** `27/04/2026`

### ➕ Added
- Audio upload support per segment
- Toggle system (select which audios are used)
- Generate audio with all segments option
- Interrupt recording functionality
- Automatic saving system
- Mobile vibration feedback
- Button tooltips (hover help)
- Improved placeholder guidance
- Visual comments spacing improvements

### 🔧 Modified
- UI redesign (rounded corners, darker theme)
- Background updated to `#010101`
- Buttons styled with consistent theme
- Layout restructuring (text → audio → controls)
- Input fields redesigned for dark mode
- Title updated to **🎤AudioScript web**
- Improved spacing and readability

### ➖ Removed
- Manual save button
- Manual load button
- Separate download step (now automatic)
