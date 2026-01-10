## Electron App Template 

**IMPORTANT:** Click & open README.md for full instruction. The preview gets cut off. 

A simple ElectronJS starter template for building desktop applications using HTML, CSS, and JavaScript.

This repo is part of my YouTube tutorial on setting up your very first Electron desktop app. It’s designed to be simple, beginner-friendly, and easy to customize for any project.

---

## Tutorial Video

This repo is a part of my Youtube video tutorial on how to set up your very first desktop application. See the video here: 

This repo is only for the basic Electron template that you can clone to build whatever you want. But if you're interested in a beginner demonstration tutorial too, see this repositary for a simple Calendar Widget: https://github.com/nasha-wanich/little-calendar 

---

## What’s Included

- Basic Electron setup
- Single window configuration
- Frameless, non-resizable window
- Draggable app window using CSS
- Plain HTML / CSS / JavaScript (no frameworks)

You can now customize the UI, add features, or turn this into any desktop app you want.

---

## What this template is for 

This template is great if you are:

- New to ElectronJS
- A designer or frontend developer exploring desktop apps
- Building quick prototypes or side projects
- Looking for a clean starting point without extra complexity

If you’re looking for a guided beginner project after setting up this template, check out this calendar demo repo: https://github.com/nasha-wanich/little-calendar

---

## Project Structure

```
electron-app-template
├── node_modules
├── main.js
├──index.html
├── styles.css
├── script.js
├── package.json
└── package-lock.json
```

### Core Files Explained

- **`main.js`**
    
    Electron’s main process. Creates the app window and loads the HTML file.
    
- **`index.html`**
    
    The main UI layout of your desktop app.
    
- **`styles.css`**
    
    Styles for your app UI, including draggable window behavior.
    
- **`script.js`**
    
    Frontend JavaScript logic for interactivity.
    
- **`package.json`**
    
    App configuration, dependencies, and run scripts.


---

## Prerequisites

Before using this template, make sure you have:

- **Node.js**
- **Homebrew** (macOS)
- A code editor (VS Code recommended)

---

## Step by step set up

### 1. Install Package Managers (if you don’t have one on your computer)

MacOS: Homebrew ([https://brew.sh](https://brew.sh/))

Window: Chocolatey (https://chocolatey.org/install)

### 2. Install Node.js

You can install Node.js in two ways:

### Option A: Use a package manager (mine is Homebrew which I used in the tutorial)

```bash
brew install node
```

Verify installation:

```bash
node -v
npm -v
```

If both commands return version numbers, you’re good to go 

### Option B: Download Installer

Download Node.js directly from: https://nodejs.org

and follow their installation instructions.


### 3. Clone This Repo

```bash
git clone https://github.com/nasha-wanich/electron-app-template.git
cd electron-app-template
```

### 4. Install Dependencies

```bash
npm install
```

### 5. Run the App

```bash
npm run start
```

This will launch a simple Electron desktop window.

---

## Next Steps

- Modify `index.html` to build your app layout
- Style your app UI in `styles.css`
- Add your app logic in `script.js`
- Adjust window behavior in `main.js`  (ex. size, transparency etc.)

---

## Want a Beginner Walkthrough Project?

If you want a step-by-step desktop app beginner tutorial, check out this repo where we build a calendar widget together: https://github.com/nasha-wanich/little-calendar
