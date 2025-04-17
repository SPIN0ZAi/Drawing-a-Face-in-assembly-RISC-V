# Drawing-a-Face-in-assembly-RISC-V
Draw a pixel face using RISC-V on the Ripes simulator
# 😄 RISC-V Smiley Face Renderer

Welcome to my **RISC-V Assembly** project! This program draws a colorful **smiley face** using low-level graphics plotting functions written in assembly.  
It was built and tested on the [Ripes](https://github.com/mortbopet/Ripes) visual RISC-V emulator.

---

## 🖼️ Output Preview

Here's a rough idea of the output:

<svg viewBox="0 0 300 400" xmlns="http://www.w3.org/2000/svg">
  <!-- Blue background -->
  <rect x="0" y="0" width="300" height="400" fill="#0000ff" />
  
  <!-- Left Eye (Green Box) -->
  <rect x="70" y="60" width="60" height="60" fill="#00ff00" />
  
  <!-- Right Eye (Green Box) -->
  <rect x="180" y="60" width="60" height="60" fill="#00ff00" />
  
  <!-- Nose (Magenta Rectangle) -->
  <rect x="145" y="140" width="20" height="30" fill="#ff00ff" />
  
  <!-- Mouth (White Rectangle) -->
  <rect x="90" y="200" width="120" height="40" fill="#ffffff" />
  
  <!-- Add grid lines to show pixel structure (optional) -->
  <g stroke="#444444" stroke-width="0.5" opacity="0.3">
    <!-- Vertical grid lines -->
    <line x1="0" y1="0" x2="0" y2="400" />
    <line x1="30" y1="0" x2="30" y2="400" />
    <line x1="60" y1="0" x2="60" y2="400" />
    <line x1="90" y1="0" x2="90" y2="400" />
    <line x1="120" y1="0" x2="120" y2="400" />
    <line x1="150" y1="0" x2="150" y2="400" />
    <line x1="180" y1="0" x2="180" y2="400" />
    <line x1="210" y1="0" x2="210" y2="400" />
    <line x1="240" y1="0" x2="240" y2="400" />
    <line x1="270" y1="0" x2="270" y2="400" />
    <line x1="300" y1="0" x2="300" y2="400" />
    
    <!-- Horizontal grid lines -->
    <line x1="0" y1="0" x2="300" y2="0" />
    <line x1="0" y1="40" x2="300" y2="40" />
    <line x1="0" y1="80" x2="300" y2="80" />
    <line x1="0" y1="120" x2="300" y2="120" />
    <line x1="0" y1="160" x2="300" y2="160" />
    <line x1="0" y1="200" x2="300" y2="200" />
    <line x1="0" y1="240" x2="300" y2="240" />
    <line x1="0" y1="280" x2="300" y2="280" />
    <line x1="0" y1="320" x2="300" y2="320" />
    <line x1="0" y1="360" x2="300" y2="360" />
    <line x1="0" y1="400" x2="300" y2="400" />
  </g>
  
  <!-- Add a border around the visualization -->
  <rect x="0" y="0" width="300" height="400" fill="none" stroke="#000000" stroke-width="2" />
  
  <!-- Label -->
  <text x="150" y="390" text-anchor="middle" fill="white" font-family="Arial" font-size="16">RISC-V Smiley Face Output</text>
</svg>



---

## 💻 Project Overview

This project uses custom subroutines to draw:
- 🟩 Two green eyes
- 💜 A magenta nose
- ⬜ A white mouth  
- All on a 🟦 blue background

Written entirely in **RISC-V Assembly**, it demonstrates:
- Stack handling
- Parameter passing via registers
- Basic framebuffer pixel plotting

---

## 📁 Files

| File              | Description                         |
|-------------------|-------------------------------------|
| `Screen playing.s`  | Main assembly code                  |
| `README.md`       | This documentation                  |

---

## 🚀 How to Run It

1. Install [Ripes](https://github.com/mortbopet/Ripes)  
2. Open `face_drawing.s` inside Ripes  
3. Click ▶️ Run and enjoy the face being drawn!
4. make sure to add matrix LED with 30 width and 40 height

---

## 🛠️ Functions Implemented

- `FillScreen` — fills the background with a solid color  
- `PlotBox` — draws rectangles (used for eyes, nose, mouth)  
- `PlotPixel` — plots a single pixel at given coordinates  

---

## ✨ Why?

I wanted to play around with RISC-V Assembly and challenge myself to do pixel graphics using **nothing but low-level instructions**.

---

## 📸 Want to Help?

If you run the project and capture a **screenshot of the smiley face**, feel free to contribute by submitting a pull request with the image!

---

## 📬 Contact

Made with ❤️ by a curious learner.


