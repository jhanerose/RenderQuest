# 🧊 RenderQuest: Computer Graphics Programming - Interactive Exam

An interactive, responsive single-page web assessment application designed for testing foundational knowledge in Computer Graphics Programming, Modern OpenGL (Core Profile), Shader Architecture, and Vector Mathematics.

<div align="center">

### 🚀 Built With

<img src="https://img.shields.io/badge/HTML5-Semantic%20Markup-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
<img src="https://img.shields.io/badge/CSS3-Modern%20Styling-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
<img src="https://img.shields.io/badge/JavaScript-ES6%2B-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
<img src="https://img.shields.io/badge/Canvas-2D%20Graphics-FF6B35?style=for-the-badge&logo=html5&logoColor=white" alt="Canvas">

</div>

---

## ✨ Features

- **Live Mathematical Visualizers (Canvas 2D):**
  - **Vector Angle & Dot Product:** Real-time geometric representation of surface normals ($\vec{N}$) and light vectors ($\vec{L}$) with live scalar dot product calculation.
  - **3D Matrix Transformations:** Real-time orthographic wireframe cube projection simulating the Model $\rightarrow$ View $\rightarrow$ Projection pipeline.
  - **Phong Reflection Model:** Dynamic radial lighting simulation showcasing Ambient, Diffuse, and Specular highlights under a moving light vector.
- **Client-Side Grading Engine:** Instant automated scoring for Multiple-Choice Questions (Part 1) with custom visual feedback (neon green for correct, red for incorrect).
- **Comprehensive Solution Log:** Built-in review key for both Multiple-Choice and Short-Answer explanations.
- **Form Submission Guardrails:** Validation check to prevent accidental submissions with blank text areas or unselected radio inputs.
- **Zero External Dependencies:** Built entirely with pure standard Web APIs. Ideal for direct hosting on **GitHub Pages**.

---

## 📚 Topics Covered

1. **Rendering Pipeline Architecture:** Programmable vs. Fixed stages (Vertex, Geometry, Tessellation, Rasterization, Fragment, Per-Sample Operations).
2. **Buffer & State Management:** VAO vs. VBO data flow, `glBufferData`, and memory layouts.
3. **Linear Algebra & Vector Math:** Vector magnitude, normalization (Unit Vectors), Dot Product ($\cos\theta$), and Cross Product surface normals.
4. **Shader Pipeline:** Vertex Attributes (`in`), Uniform variables (`glGetUniformLocation`), and Shader Program linking (`glLinkProgram`).
5. **Coordinate Systems:** Local/Model $\rightarrow$ World $\rightarrow$ View/Eye $\rightarrow$ Clip $\rightarrow$ NDC ($-1.0$ to $1.0$) $\rightarrow$ Screen/Window Space.
6. **Illumination & Depth:** The classic Phong reflection model (Ambient, Diffuse, Specular) and the Depth/Z-Buffer test.

---
## 🚀 Live Demo & Deployment

<div align="center">

[![Live Demo](https://img.shields.io/badge/🌐%20Live%20Demo-RenderQuest-00C853?style=for-the-badge)](https://jhanerose.github.io/RenderQuest/)
[![GitHub Repository](https://img.shields.io/badge/📦%20Repository-GitHub-181717?style=for-the-badge&logo=github)](https://github.com/jhanerose/RenderQuest)

</div>

### ⚡ Quick Run Locally

Follow these steps to run **RenderQuest** on your local machine:

**1. Clone the repository**

```bash
git clone https://github.com/jhanerose/RenderQuest.git
````

**2. Navigate to the project folder**

```bash
cd RenderQuest
```

**3. Launch the application**

Open `index.html` directly in any modern web browser.

> 💡 **Tip:** For the best experience, use **Google Chrome, Microsoft Edge, or Mozilla Firefox**.


**One important thing:** your original Markdown has the GitHub URL wrapped inside `[ ]( )` *inside* a code block, so it won't work as a clickable link. The version above fixes that.


## 🛠️ Technology Stack


### 🏷️ Markup
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />

**Semantic HTML5**  
Structured using semantic elements to provide a clean, accessible, and well-organized document architecture.

---

### 🎨 Styling
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" />

**Modern CSS3**

- 🎨 CSS Variables for reusable design values
- 📐 Flexbox for responsive layouts
- 🪟 Backdrop Blur for modern glassmorphism effects
- 📱 Responsive styling and UI presentation

---

### ⚙️ Scripting
<img src="https://img.shields.io/badge/JavaScript-ES6%2B-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />

**Vanilla JavaScript (ES6+)**

- ⚡ Dynamic interactions
- 🔄 Animation control
- 🧮 Matrix mathematics
- 🧩 Application logic
- 🚫 No external JavaScript frameworks

---

### 🖼️ Graphics & Animation
<img src="https://img.shields.io/badge/HTML5%20Canvas-2D%20Graphics-FF6B35?style=flat-square&logo=html5&logoColor=white" />

**HTML5 2D Canvas API**

Used for rendering and controlling interactive graphics through:

- 🔢 Matrix mathematics
- 📈 Parametric animation loops
- 🎞️ Real-time rendering
- ✨ Procedural visual effects

---
<div align="center">

[![LIVE DEMO](https://img.shields.io/badge/%20LIVE%20DEMO-181717?style=for-the-badge&logo=github&logoColor=white)](https://jhanerose.github.io/RenderQuest/)

</div>
