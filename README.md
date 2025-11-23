<!-- <p align="center">
<img src="https://raw.githubusercontent.com/VadimLindebaum/EventAppTodoTask/main/public/logo192.png" width="128px" />
</p> -->

# 📝React.js Todo App

<p align="center"><i>A fast and modern Todo app built with React, featuring task sharing via link, P2P Task Sync with WebRTC, theme customization, offline usage as a PWA, and caching for smooth performance.</i></p>

<img src="https://raw.githubusercontent.com/VadimLindebaum/EventAppTodoTask/main/screenshots/baner.png" />

#[(https://eventapptodotask.netlify.app/)](https://eventapptodotask.netlify.app/)/)



<!-- <p align="center">
<img src="https://raw.githubusercontent.com/VadimLindebaum/EventAppTodoTask/main/screenshots/iPhone%20Mockup%20black.png" width="400px" />
</p> -->

## 💻 Tech Stack

<ul style="display: flex; flex-direction: column; gap:10px;">
  <li style="vertical-align: middle;">
    <img src="https://go-skill-icons.vercel.app/api/icons?i=react" alt="react" width="24" style="vertical-align: middle; margin-right: 4px;" /> React
  </li>
    <li style="vertical-align: middle;">
    <img src="https://go-skill-icons.vercel.app/api/icons?i=typescript" alt="typescript" width="20" style="vertical-align: middle;margin-right: 4px;" /> Typescript
  </li>
    <li style="vertical-align: middle;">
    <img src="https://go-skill-icons.vercel.app/api/icons?i=vite" alt="vite" width="24" style="vertical-align: middle;margin-right: 4px;" /> Vite
  </li>
  <li style="vertical-align: middle;">
    <img src="https://go-skill-icons.vercel.app/api/icons?i=vitest" alt="vitest" width="24" style="vertical-align: middle;margin-right: 4px;" /> Vitest
  </li>
  <li style="vertical-align: middle;">
    <img src="https://go-skill-icons.vercel.app/api/icons?i=emotion" alt="emotion" width="24" style="vertical-align: middle;margin-right: 4px;" /> Emotion
  </li>
    <li style="vertical-align: middle;">
    <img src="https://go-skill-icons.vercel.app/api/icons?i=mui" alt="mui" width="24" style="vertical-align: middle;margin-right: 4px;" /> Material UI (MUI)
  </li>
</ul>

## ⚡ Features

### 🔗 Share Tasks by Link or QR Code

Easily share your tasks with others using a link or QR code.


<img src="https://raw.githubusercontent.com/VadimLindebaum/EventAppTodoTask/main/screenshots/ShareDialog.png" width="300px" alt="Shared Task" />

### 🤖 AI Emoji Suggestions

This feature uses Chrome’s experimental `window.LanguageModel` API powered by **Gemini Nano** — an on-device LLM.

⚠️ Requires **Chrome Canary 128+** with the **Gemini Nano model installed** - [Setup guide](https://docs.google.com/document/d/1VG8HIyz361zGduWgNG7R_R8Xkv0OOJ8b5C9QKeCjU0c/view?pli=1&tab=t.0#heading=h.witohboigk0o)

Code: 

<img src="https://raw.githubusercontent.com/VadimLindebaum/EventAppTodoTask/main/screenshots/emoji-ai.gif" alt="AI Emoji" width="360px" style="border-radius:12px" />

### 🔄 P2P Task Sync with WebRTC

Securely sync all the data between devices using peer-to-peer WebRTC connections. Devices pair via QR code, and your data is transferred directly between them — only minimal server involvement for connection setup, with no data stored or processed in the cloud.

- Tasks and categories are auto-merged based on recent edits or deletions
- For settings and other data, you choose which device to sync from


### 🎨 Color Themes & Dark Mode

Choose from various color themes and toggle between light and dark modes to suit your preferences.

<img src="https://raw.githubusercontent.com/VadimLindebaum/EventAppTodoTask/main/screenshots/settings.png" width="500px" />

### 🗣️ Task Reading Aloud

Option to have tasks read aloud using the native `SpeechSynthesis` API, with a selection of voices to choose from.

<img src="https://raw.githubusercontent.com/VadimLindebaum/EventAppTodoTask/main/screenshots/ReadAloud.png" width="260px" alt="Task Reading Aloud" />

### 📥 Import/Export Tasks

Users can import and export tasks to/from JSON files. This feature allows users to back up their tasks or transfer them to other devices easily.

### 📴 Progressive Web App (PWA)

This app is a Progressive Web App (PWA), which means it can be installed on your device, **used even when you're offline** and behave like a native app with shortcuts and app badges.

<img src="https://raw.githubusercontent.com/VadimLindebaum/EventAppTodoTask/main/screenshots/pwaTaskBar.png" alt="taskbar" width="260px" />

### 🔄 Update Prompt

The app features a custom update prompt that notifies users when a new version is available, allowing for easy refresh to access the latest improvements.

<img src="https://raw.githubusercontent.com/VadimLindebaum/EventAppTodoTask/main/screenshots/UpdatePrompt.png" alt="update prompt" width="260px" />

### 📱 Custom Splash Screens

The app automatically generates custom splash screens from a single HTML template for various iOS and iPadOS devices in both light and dark modes. These splash screens provide a smooth, native-like launch experience when the app is opened as a PWA.

<img src="https://raw.githubusercontent.com/VadimLindebaum/EventAppTodoTask/main/screenshots/SplashScreen.png" alt="Splash Screen Example" width="450px" />

To generate splash screens:

```bash
npm run generate-splash
```

Code: [

## 👨‍💻 Installation

To install and run the project locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/maciekt07/TodoApp.git
```

2. Navigate to the project directory:

```bash
cd TodoApp
```

3. Install the dependencies:

```bash
npm install
```

4. Start the development server:

```bash
npm run dev
```

The app will now be running at [http://localhost:5173/](http://localhost:5173/).

> [!TIP]
> For mobile device testing, use `npm run dev:host` to preview the app on your local network with HTTPS (required for camera features) and a QR code in the terminal for quick access. To enable PWA features in development, see [vite.config.ts](vite.config.ts).

## 📷 Screenshots

<img src="https://raw.githubusercontent.com/VadimLindebaum/EventAppTodoTask/main/screenshots/ss1.png" width="300px" />
<img src="https://raw.githubusercontent.com/VadimLindebaum/EventAppTodoTask/main/screenshots/ss2.png" width="300px" />

<img src="https://raw.githubusercontent.com/VadimLindebaum/EventAppTodoTask/main/screenshots/ss3.png" width="300px" />

<!-- <img src="https://raw.githubusercontent.com/VadimLindebaum/EventAppTodoTask/main/screenshots/ss4.png" width="300px" />

<img src="https://raw.githubusercontent.com/VadimLindebaum/EventAppTodoTask/main/screenshots/ss5.png" width="300px" />

<img src="https://raw.githubusercontent.com/VadimLindebaum/EventAppTodoTask/main/screenshots/ss6.png" width="300px" /> -->

<img src="https://raw.githubusercontent.com/VadimLindebaum/EventAppTodoTask/main/screenshots/sspc1.png" width="650px" />

## 🚀 Performance

<img src="https://raw.githubusercontent.com/VadimLindebaum/EventAppTodoTask/main/screenshots/performance.png" width="600px" />

## Credits

Made with and by [code](https://github.com/VadimLindebaum), licensed under [MIT](https://github.com/maciekt07/TodoApp/blob/main/LICENSE).
