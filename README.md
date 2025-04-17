# Drawing-a-Face-in-assembly-RISC-V
Draw a pixel face using RISC-V on the Ripes simulator
# 😄 RISC-V Smiley Face Renderer

Welcome to my **RISC-V Assembly** project! This program draws a colorful **smiley face** using low-level graphics plotting functions written in assembly.  
It was built and tested on the [Ripes](https://github.com/mortbopet/Ripes) visual RISC-V emulator.

---

## 🖼️ Output Preview

Here's a rough idea of the output:

<p align="center">
 <img src="https://i.ibb.co/TqJBy3ks/Screenshot-2025-04-17-204041.jpg" width="500"/>

</p>



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


