# 🎧 Audio Script

**Audio Script** is a lightweight browser-based tool for recording, organizing, previewing, and generating segmented audio from a script.

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
* ❤️ Toggle favorite segments (include/exclude in preview/export)
* 🎧 Real-time preview of selected segments
* 📥 Download individual audio tracks
* 🧠 Automatic saving (no save button needed)
* 💾 Persistent storage using `localStorage`
* 🧹 One-click project reset
* 🧩 Inline comments using `//`

  * Displayed as visual notes (not audio)
* 🔊 Merge segments into a single `.wav` file
* 🔀 Option to export all segments (ignore toggle)
* ⏱️ Configurable gap between segments
* 📱 Mobile-friendly interactions (including vibration feedback)
* 🎨 Clean UI with improved readability and structure
* 📌 Floating preview player (always visible)

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
6. Use the **Preview player** to listen before exporting
7. Download:
   - **Download Selected** (only marked segments)
   - **Download All** (ignores toggle)
8. Individual tracks can also be downloaded separately

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

Built with the help of [**ChatGPT**](https://chatgpt.com/share/69efb636-ea20-83e9-b798-548f8353fe56)

---

## 📜 License

Do whatever you want with it.  
Seriously.

---

## 📌 Latest Update - V11.1  
**Date:** `27/04/2026`

| ➕ Added | 🔧 Modified | ➖ Removed |
|---|---|---|
| Floating preview player<br>Manual preview refresh button (🔄)<br>Per-track download button | Preview system redesigned (real-time updates)<br>Audio generation split into preview/export logic<br>Preview now updates on stop, upload, toggle, and gap change<br>Layout updated to support fixed preview<br>Extra bottom spacing for UI safety | Generate final audio button |
