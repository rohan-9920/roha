# 🎨 Smart Voice Gallery


> A next-generation, single-file image gallery featuring **AI Voice Control**, **Holographic 3D Tilt**, and **Audio Visualization**. 

---

## ✨ Features

### 🧠 AI & Interaction
* **🎙️ Jarvis Voice Control:** Control the entire gallery using your voice. Just speak commands like *"Next"* or *"Music"*.
* **🧊 3D Holographic Tilt:** The card reacts to your mouse movement in 3D space with realistic physics.
* **📱 Touch Swipe:** Native swipe left/right support for mobile devices.
* **🎹 Keyboard Support:** Navigate quickly using arrow keys.

### 🎨 Visuals & Aesthetics
* **🔮 Glassmorphism UI:** Premium "Frosted Glass" aesthetic.
* **🌈 5 Dynamic Themes:**
    * 🦄 **Unicorn (Default)**
    * 🌙 **Midnight Dark**
    * 👾 **Cyberpunk Neon**
    * ☕ **Cozy Coffee**
    * 🎉 **New Year Gold**
* **❄️ Particle Physics:** Realistic snowfall animation in the background.

### 🎵 Audio Experience
* **🔊 Built-in Lo-Fi Player:** Integrated chill beats.
* **💓 Beat Visualization:** The gallery card **pulses** and glows in sync with the music.

---

## 🎮 How to Use

### 🗣️ Voice Commands (Microphone Mode)
Click the **🎙️ Mic Icon** to activate. (Works best in Chrome/Edge/Safari).

| Say This... | To Do This... |
| :--- | :--- |
| **"Next"** or **"Go"** | Slide to the next image |
| **"Back"** or **"Previous"** | Go to the previous image |
| **"Music"** or **"Play"** | Toggle the Lo-Fi beat player |
| **"Theme"** or **"Color"** | Cycle through the 5 color themes |

### ⌨️ Keyboard Shortcuts

| Key | Action |
| :--- | :--- |
| **Right Arrow (→)** | Next Image |
| **Left Arrow (←)** | Previous Image |
| **K** | Play/Pause Music |
| **T** | Change Theme |

---

## 🚀 Installation & Setup

This project uses a **Single File Architecture**. No servers, no Node.js, no installation required!

1.  **Download** the `index.html` file.
2.  **Open** it in any modern web browser (Chrome recommended for Voice API).
3.  **Enjoy!**

---

## 🖼️ How to Add Your Own Images

Open `index.html` in a text editor (like VS Code or Notepad) and look for the `galleryData` section around line 350:

```javascript
const galleryData = [
    {
        url: 'YOUR_IMAGE_LINK_HERE.jpg',
        title: 'Your Title',
        quote: 'Your cool quote goes here.'
    },
    // Add more blocks like this...
];
