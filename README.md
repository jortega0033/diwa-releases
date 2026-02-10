# 🌐 Diwa Copilot — Your AI Interview Partner

**Real-time AI coaching that floats invisibly over your screen during video interviews.**  
*Never blank on a question again.*

[![Version](https://img.shields.io/badge/version-1.5.4-10a37f?style=for-the-badge)](https://github.com/jortega0033/diwa-copilot/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/jortega0033/diwa-copilot/total?style=for-the-badge&color=22c55e)](https://github.com/jortega0033/diwa-copilot/releases)
[![Platform](https://img.shields.io/badge/platform-macOS%20%7C%20Windows-71717a?style=for-the-badge)](https://github.com/jortega0033/diwa-copilot/releases/latest)

---

[**⬇️ Download**](#-download) · [**✨ Features**](#-features) · [**🚀 How It Works**](#-how-it-works) · [**💬 Support**](https://github.com/jortega0033/diwa-copilot/issues)

</div>

---

## ⬇️ Download

> 🔒 **For your safety, download only from this website. Third-party sources may be unsafe.**

| Platform | Download | Requirements |
|----------|----------|--------------|
| **macOS** (Universal) | [Download .dmg](https://github.com/jortega0033/diwa-copilot/releases/latest) | macOS 11+ |
| **Windows** (x64) | [Download .exe](https://github.com/jortega0033/diwa-copilot/releases/latest) | Windows 10+ |

> 💡 **Free to use** — Just bring your own [OpenAI API key](https://platform.openai.com/api-keys)

---

## ✨ Features

### 🎤 Native System Audio Capture
Captures system audio using native OS APIs—**no third-party drivers required**. Works with **Zoom**, **Google Meet**, **Teams**, and any app that plays audio.

- **macOS:** Automatic loopback audio capture
- **Windows:** Native WASAPI loopback (no setup required)
- **Smart Audio:** Mic button only appears when needed (with "FALLBACK" badge when system audio fails)

### 🎭 Mock Interview Mode
Practice before your real interview with AI-generated sessions:

- **5 tailored questions** based on your role and company
- **Live speech-to-text** as you answer each question
- **Detailed feedback** including clarity scores (0-100), STAR method analysis, strengths, and improvement areas
- **Session history** to track your progress over time

### 👻 Ghost Mode
Click-through transparency lets mouse events pass through. The overlay is **truly invisible** to screen shares.

### 📄 Context Injection
Upload your CV, job description, and company docs. AI tailors responses to your specific background.

### ⚡ ~200ms Latency
Real-time pipeline delivers responses fast enough to use mid-conversation. No awkward pauses.

### 👤 Multi-Persona System
Create personas for different roles. The AI becomes "Jake, Senior Engineer" with your background baked in.

### 🎨 Custom Response Styles
Choose from 8 built-in styles (Bullet Points, Conversational, STAR Method, etc.) or create your own custom prompt with optional "strict mode" for plain prose responses.

### 🔒 Secure & Private
API keys encrypted via OS keychain. **No data leaves your machine except to OpenAI.** No telemetry.

### 🚀 Native Splash Screen
Polished launch experience with an animated splash screen while the app initializes. No white flash or loading delays.

---

## 🚀 How It Works

| Step | Action |
|------|--------|
| 1️⃣ | **Download & Install** — Grab the installer. No sign-up needed. |
| 2️⃣ | **Add Your API Key** — Paste your [OpenAI key](https://platform.openai.com/api-keys). Stored locally & encrypted. |
| 3️⃣ | **Start Your Interview** — Launch Diwa Copilot, join your call, let AI handle the rest. |

**Up and running in 3 minutes.**

---

## 📋 Requirements

- **OpenAI API Key** — [Get one here](https://platform.openai.com/api-keys)
- **macOS 11+** or **Windows 10+**
- Active internet connection

---

## ❓ Frequently Asked Questions

### 🚨 Why does my computer say the app is "Unrecognized"?
Because we are in early Beta, we haven't bought expensive code-signing certificates yet.

- **macOS:** Right-click the app icon and select **Open**. (If you double-click, it might block you.)
- **Windows:** Click "More Info" → "Run Anyway".

### 🔑 Is my API Key safe?
Yes. We are a "Bring Your Own Key" app. Your key is stored **locally on your device** (encrypted via your OS Keychain). It is sent directly to OpenAI's servers to generate answers. It never touches our servers because **we don't have any servers**.

### 🎧 Why do I need Screen Recording permission on Mac?
macOS requires Screen & System Audio Recording permission to capture audio from other apps. Diwa uses native Chromium loopback (via `MacLoopbackAudioForScreenShare`)—no third-party audio drivers like BlackHole are needed.

**Pro Tip:** After enabling the permission, quit and relaunch Diwa Copilot to activate audio capture.

### 🪟 How does audio capture work on Windows?
Windows uses native WASAPI loopback to capture system audio automatically. When you click "Start Capture", audio begins recording immediately—no screen picker or extra steps required.

### 💰 Is it really free?
The app is free during the Beta period (until May 1, 2026). You only pay OpenAI for the API usage, which is usually pennies per interview.

### 🎤 What are the different AI models available?
Diwa supports multiple OpenAI models:

- **GPT-4o** — Fast, multimodal flagship (recommended for most interviews)
- **GPT-4 Turbo** — Previous generation flagship with 128K context
- **GPT-3.5 Turbo** — Fast and affordable for simple questions
- **Realtime API** — Native low-latency voice interaction (~200ms)

### 🎭 How does Mock Interview Mode work?
Click the "Mock Interview" button in the sidebar, select your target role and company, and Diwa will generate 5 tailored questions. Answer each question out loud, and get instant feedback on clarity, structure, and content. All sessions are saved locally so you can review your progress.

---

## 🎨 Interface Design

### Obsidian Glass HUD
The overlay features a **minimalist "glass panel" design** that stays out of your way:

- **Floating Window** — Appears as a subtle, translucent panel above your video call
- **Real-Time Messages** — See both interviewer questions and AI responses in a clean chat-like interface
- **Status Indicator** — A pulsing green dot shows when Diwa is listening or processing
- **Smart Controls** — Compact control bar at the bottom with intuitive buttons:
  - ▶️ **Start/Stop** — Activate the session
  - 📌 **Pin** — Keep on top of other windows
  - 👻 **Ghost Mode** — Make even more invisible (click-through)
  - 🏠 **Main Window** — Quick access to settings
  - 🎤 **Mute** — Pause AI assistance
  - 🗑️ **Clear** — Reset transcript
  - 👁️ **Opacity Slider** — Adjust transparency (30-100%)

The entire interface is designed for **under 20ms of visual attention** — glance down, grab the answer, get back to the conversation. The glass aesthetic evokes a "layer of intelligence" floating invisibly above your screen.

---

## 💬 Support

Having issues? [Open an issue](https://github.com/jortega0033/diwa-copilot/issues) and we'll help you out.

---

<div align="center">

**Built with Electron + React + Vite**

*Native system audio capture — no third-party drivers required*

Made with ❤️ for job seekers everywhere
