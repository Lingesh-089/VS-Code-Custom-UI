# 🎨 VS Code UI Customization (Custom CSS & JS Injection)

A highly customized **Visual Studio Code UI transformation** using injected CSS and JavaScript to enhance aesthetics, readability, and overall developer experience.

---

## 📸 Preview

> ⚠️ Add your screenshots/GIFs here (VERY IMPORTANT for impact)

### 🔥 Before vs After

<img src="images/before.png" width="400"/> <img src="images/after.png" width="400"/>

---

### 🎥 Live Demo

<img src="images/demo.gif" width="800"/>

---

## 🚀 Overview

This project modifies the default VS Code interface using the **"Custom CSS and JS Loader" extension**, allowing deep customization of UI components such as the sidebar, editor, command palette, and toolbars.

The goal is to create a **minimal, modern, and visually immersive coding environment**.

---

## ✨ Features

### 🎨 Visual Enhancements

* Custom shadows and depth effects for editor and sidebar
* Improved typography using **JetBrains Mono** and **Google Sans**
* Clean and minimal toolbar (hidden unnecessary UI elements)
* Styled command palette with blur and gradient effects

---

### 🧭 UI Improvements

* Better file explorer highlighting
* Simplified top bar (distraction-free coding)
* Cleaner search interface
* Improved hover tooltips with modern design

---

### ⚡ Experience Upgrades

* Reduced visual clutter
* Enhanced focus on code
* Smooth and consistent UI styling
* Premium IDE-like appearance

---

## 🧠 How It Works

* VS Code does not officially support deep UI customization
* This project uses a workaround via **CSS & JS injection**
* Custom styles are applied to internal VS Code classes

Example:

```css id="csssample2"
.monaco-editor .scroll-decoration {
    box-shadow: 0px 0px 20px rgba(0, 0, 0, .75) !important;
}
```

---

## 🛠️ Tech Stack

* **CSS (UI Styling)**
* **JavaScript (UI Behavior Tweaks)**
* **VS Code Internal DOM Styling**
* **Custom CSS and JS Loader Extension**

---

## 📂 Project Structure

```plaintext id="structure4"
project/
│
├── custom_vscode.css
├── custom_vscode.js
├── images/
│   ├── before.png
│   ├── after.png
│   └── demo.gif
└── README.md
```

---

## ▶️ How to Apply / Run

### ✅ Step 1: Install Extension

Install the VS Code extension:

👉 **Custom CSS and JS Loader**

---

### ✅ Step 2: Open Settings JSON

Press:

```id="cmd1"
Ctrl + Shift + P
```

Search:

```id="cmd2"
Preferences: Open Settings (JSON)
```

---

### ✅ Step 3: Add Configuration

```json id="config2"
"vscode_custom_css.imports": [
    "file:///FULL_PATH/custom_vscode.css",
    "file:///FULL_PATH/custom_vscode.js"
]
```

👉 Replace `FULL_PATH` with your actual file path

---

### ✅ Step 4: Enable Custom Styling

Run:

```id="cmd3"
Enable Custom CSS and JS
```

---

### ✅ Step 5: Restart VS Code

👉 Your UI will now be transformed 🎉

---

## ⚠️ Important Notes

* Run VS Code as **Administrator** if styles don’t apply
* VS Code updates may reset custom styles
* Re-run **Enable Custom CSS and JS** after updates

---

## 🎯 Customizations Included

* Sidebar styling
* Editor shadows and depth
* Command palette redesign
* Tooltip redesign
* File explorer highlighting
* UI simplification (removing unnecessary elements)

---

## 📸 Screenshots 

```md id="extrascreenshot"
<img src="images/sidebar.png" width="400"/>
<img src="images/command-palette.png" width="400"/>
```<img width="1919" height="1199" alt="Screenshot 2026-05-03 211425" src="https://github.com/user-attachments/assets/a261d54c-da76-4446-8bc4-a0ba9983f2a8" />
<img width="1919" height="1199" alt="Screenshot 2026-05-03 211152" src="https://github.com/user-attachments/assets/13b238e4-448e-447c-a5f4-bda440cb196e" />


---

## 🔥 Highlights

* Deep UI customization beyond default VS Code capabilities
* Clean, distraction-free development environment
* Modern aesthetic inspired by premium tools
* Lightweight and highly customizable

---

## 🧪 Future Improvements

* Multiple theme presets
* Dynamic theme switching
* Animation effects
* Packaging as a VS Code extension

---

## 📄 License

MIT License

