# 🌿 HLSL Layer-Based Grass Shader for Unity URP  
**Author:** Jaswanth Gnanasekar  
**Tested On:** Unity URP (2022+), Mobile (Android – OpenGL ES 3.0)  
**Performance:** 90+ FPS on mid-range devices  

## 📦 Overview  
This Unity shader package provides a **lightweight, mobile-optimized grass system** written entirely in **HLSL** for the **Universal Render Pipeline (URP)**. Designed specifically for **real-time performance on OpenGL ES**, it uses **layered vertex animation** instead of geometry or compute shaders—making it ideal for mobile and WebGL.

## ✨ Features  
- 🔹 Fully custom **HLSL Shader** (no Shader Graph)  
- 🔹 Designed for **URP**  
- 🔹 Runs at **90 FPS** on mobile devices (OpenGL ES 3.0)  
- 🔹 **Layered animation** simulating natural wind sway  
- 🔹 Efficient **vertex displacement** using world noise  
- 🔹 Adjustable **grass density**, **length**, and **color**  
- 🔹 Minimal performance cost  
- 🔹 **No geometry shader**, **no compute shader** — 100% mobile-friendly  

## 🚀 Installation  
1. Clone or download the repository:  
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   ```
2. Open your Unity URP project.  
3. Drag the `GrassShader` folder into your project’s `Assets/` directory.  
4. Assign the material to a plane or terrain mesh.  
5. Tweak the material parameters to fit your scene.

## 📱 Mobile Performance  
- Tested on **mid-range Android devices**  
- Delivers **stable 90 FPS** with default settings  
- Uses **OpenGL ES 3.0**, ensuring wide compatibility  

## 🔍 Google Search Tags  
`jaswanth gnanasekar unity urp grass shader mobile hlsl opengl es`  
`layer based grass shader unity mobile`  
`hlsl grass shader urp open gl android`  

## 📸 Demo  
(Insert video/GIF preview or screenshot here)  

## 🛠️ Customization  
- Wind speed/direction  
- Blade density & scale  
- Ground blending  
- Animation frequency & noise strength  

## 📄 License  
MIT – Free for personal and commercial use.