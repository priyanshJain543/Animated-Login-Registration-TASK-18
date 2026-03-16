# 🛡️ Advanced Auth-Flow: Animated Login & Registration

A high-fidelity authentication interface focusing on **Micro-interactions** and **Stateful UI**. This project utilizes Vanilla JavaScript and Modern CSS (Level 4) to create a seamless user journey between authentication states without page refreshes.

## 🔗 Live Experience
**[Explore the Live Demo]( https://priyanshjain543.github.io/Animated-Login-Registration-TASK-18/)**

---

## 💎 Project Highlights

* **State-Driven Transitions:** Leverages a centralized `active` class on the parent container to orchestrate complex synchronized animations.
* **Staggered Keyframe Orchestration:** Utilizes CSS Custom Properties (`--S`, `--D`, `--li`) to calculate dynamic `transition-delay` values, ensuring a natural, "wave-like" entry of form components.
* **Advanced Layout Geometry:** Implements high-performance `skewY` and `rotate` transforms to create a non-linear, modern background aesthetic that adapts to the active form.
* **UX-First Inputs:** * **Contextual Icons:** Integrated via Boxicons for visual cognitive cues.
    * **Persistent Labels:** Smooth floating label transitions that maintain context even after user input.
* **Performance Optimized:** Zero dependencies (Vanilla JS) and GPU-accelerated CSS transforms for 60fps animations.

## 🛠️ Tech Stack

| Category | Technology |
| :--- | :--- |
| **Language** | HTML5 (Semantic), JavaScript (ES6+) |
| **Styling** | CSS3 (Flexbox, Custom Props, Transitions) |
| **Iconography** | Boxicons (High-performance CDN) |
| **Deployment** | GitHub Pages / Vercel |

## 📂 Architecture

```text
├── index.html       # Refined DOM structure with animation tokens
├── style.css        # Core design system & motion logic
└── script.js        # Event-driven state management