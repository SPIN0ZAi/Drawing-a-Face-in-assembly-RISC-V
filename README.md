# Drawing-a-Face-in-assembly-RISC-V
Draw a pixel face using RISC-V on the Ripes simulator
# 😄 RISC-V Smiley Face Renderer

Welcome to my **RISC-V Assembly** project! This program draws a colorful **smiley face** using low-level graphics plotting functions written in assembly.  
It was built and tested on the [Ripes](https://github.com/mortbopet/Ripes) visual RISC-V emulator.

---

## 🖼️ Output Preview

Here's a rough idea of the output:

<p align="center">
  <img src="[https://imagekit.io/tools/asset-public-link?detail=%7B%22name%22%3A%22Screenshot%202025-04-17%20204041.jpg%22%2C%22type%22%3A%22image%2Fjpeg%22%2C%22signedurl_expire%22%3A%222028-04-16T18%3A41%3A58.535Z%22%2C%22signedUrl%22%3A%22https%3A%2F%2Fmedia-hosting.imagekit.io%2F9cb16517f9ee418a%2FScreenshot%25202025-04-17%2520204041.jpg%3FExpires%3D1839523319%26Key-Pair-Id%3DK2ZIVPTIP2VGHC%26Signature%3DLQni~2OLhgvpwpa7D8nUp41C4BxNCRNOzvbqr0v3S2a~8xgjgfw3-7RLrEd5JZhRFn6UqCjLMnZCEzGA1CRKllUigvTMKvIyv5kz0hund-zglpSBgt9kBoqmq8heh0QK-1MWVFw2TbCJUEF9CdScg7iXB5Ejm-5in-rjn8NOL-MHzt3zz70~3xqB8I1jTgYTWgPnVGLmloo11lh2iveLASGSBmTTMeXbCpRYsVOtwq5G4Jv5hrlm-EPNvZz4Z3px1VO9TvuImzhbSRinF9kON-2QEWYoLiuFaLMN9TEFoW9A9af489z5QwDTxDXICvUubIUrfgUQ4CvttX2mM4QFHA__%22%7D](https://drive.google.com/file/d/109DyuNGBoIrDfOSTLyWt7LvZneI_00vb/view?usp=drive_link)"/>
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


