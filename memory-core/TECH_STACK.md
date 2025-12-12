# 💻 Yeatz Tech Stack

## ⚡ Core Technologies
We prefer **Vanilla** over complex frameworks for longevity and performance, unless necessary.

1.  **Frontend**:
    -   HTML5 (Semantic)
    -   CSS3 (Variables, Flexbox, Grid) - No Tailwind unless requested.
    -   JavaScript (ES6+) - Pure, modular `script.js`.

2.  **App Wrapper (PWA & Desktop)**:
    -   **Electron**: For native Windows/Mac desktop experiences.
    -   **Capacitor**: For converting web apps to iOS and Android APKs.
    -   **Service Workers**: For offline capabilities.

3.  **Deployment**:
    -   GitHub Pages (Web)
    -   GitHub Releases (Binaries)

## 📂 Standard Folder Structure
For consistency across the 30 apps:

```text
AppName/
├── .github/workflows/    # CI/CD (No secret-dependent builds)
├── assets/               # Images, Icons (.png, .svg)
├── electron/             # Electron specific main.js
├── index.html            # Main Entry
├── styles.css            # Styles
├── script.js             # Logic
├── manifest.json         # PWA Manifest
└── README.md             # Documentation
```

## 🔧 Preferred Tools
-   **Terminal**: PowerShell
-   **Editor**: VS Code
-   **Design**: Figma / AI Generation
