<a id="readme-top"></a>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#features">Features</a></li>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#what-makes-this-different">What Makes This Different?</a></li>
    <li><a href="#current-limitations">Current Limitations</a></li>
  </ol>
</details>

---

## About The Project

**Ctrl+Shift+Fix** is a **VS Code extension** designed to boost developer productivity by automating **code completion, bug fixes with GUI, automated builds and testing**. It helps developers write code faster and with fewer errors by offering **AI-powered suggestions**, **real-time error detection**, and **one-click bug fixing & auto-build**.
---

📄 [Pitch Deck – HackOrbit 2025](./docs.pdf/Ctrl+Shift+Fix.pdf)
---

### Features 

- **AI-powered code completion** - Get real-time code suggestions as you type.  
- **Live bug detection & quick fixes with GUI** - Instantly spot and fix errors in your code.  
- **One-click auto-build** - Fix all bugs and compile your code with a single button.  
- **Seamless VS Code integration** - Works smoothly with your coding workflow.  
- **Minimal manual intervention** - Reduces debugging time, allowing you to focus on coding.  

---

### Built With 

- [TypeScript](https://www.typescriptlang.org/)
- [Node.js](https://nodejs.org/)
- [VS Code API](https://code.visualstudio.com/api)
- [Gemini API](https://ai.google.dev/)

---

## Getting Started

Here are some instructions to make your own copy of Ctrl+Shift+Fix and get started with it locally.

### Prerequisites

  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/zainabfatima097/Ctrl+Shift+Fix
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
3. Make `.env` file and add your API credentials in it.
   ```js
   API_KEY = 'ENTER YOUR API KEY';
   ```
4. Change git remote url to avoid accidental pushes to base project
   ```sh
   git remote set-url origin https://github.com/zainabfatima097/Ctrl+Shift+Fix
   git remote -v # confirm the changes
   ```


## Usage
1. After cloning the repository, run these commands in terminal.
   ```sh
   npm run compile
   code .
   ```
2. Press FN + F5 to start deubug console and open Extension Development Host.
   
3. Press Ctrl + Shift + P and type Ctrl+Shift+Fix.

4. Ctrl+Shift+Fix is live!

## What Makes This Different?

While tools like **GitHub Copilot**, **Cursor**, and **Claude** assist with AI-powered code suggestions, **Ctrl+Shift+Fix** stands out with a few *unique power-ups*:


 Inline Bug Detection & Fixing
  Instantly detects bugs and displays AI-generated fixes inside a webview sidebar.
  You can apply a fix with one click – no need to copy/paste from another tab.

 Gamified UI
  Comes with a retro pixel-art inspired GUI for error fixes, making debugging more fun.
  It's not just helpful, it's ✨ vibey ✨.

 Auto-Build Support (Experimental)
  After applying all fixes, Ctrl+Shift+Fix can auto-compile your code from within VS Code.

 No Fluff, Just Fixes
  Fixes are *surgical*. The AI is instructed to only change the error line and nothing else.
  No hallucinated code, no unwanted edits.

 Made for Beginners (by a Beginner)
  Designed with simplicity in mind, especially for early-stage devs who want guided debugging.
  Built entirely by a first-year CS student — so it’s relatable and real.

 Fully Open Source
  You can view, edit, and extend everything. Want it to fix CSS too? You can totally make it happen.

## Current Limitations
Due to continuous large number of API calls for auto-completion and suggestion of possible bugs, resource might get exhausted.


*Built as a solo project by a first-year Computer Science undergrad — crafted during midnight vibe-coding sessions and a ton of trial & error.*










