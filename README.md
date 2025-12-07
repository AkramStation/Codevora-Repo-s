# Codevora

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Electron](https://img.shields.io/badge/Electron-v39.2.4-blueviolet.svg)
![React](https://img.shields.io/badge/React-v18.2.0-61dafb.svg)

**Codevora** is a high-performance, minimalist code editor built for developers who appreciate speed and simplicity. Inspired by the legendary Notepad++, Codevora brings the classic lightweight feel into the modern era with a beautiful UI, robust feature set, and the power of the Monaco Editor engine (the same core that powers VS Code).

![Codevora Screenshot](https://via.placeholder.com/800x450.png?text=Codevora+Editor+Preview)

## ✨ Key Features

*   **⚡ Blazing Fast & Lightweight**: Optimized for performance with a minimal footprint.
*   **📝 Monaco Editor Core**: Enjoy industry-standard syntax highlighting, IntelliSense, and editing features.
*   **🎨 Modern Minimalist Design**: A distraction-free interface with glassmorphism touches and smooth animations.
*   **📂 Intelligent File Management**: Smart tab handling, file tree with icon support, and drag-and-drop operations.
*   **🔍 Advanced Search**: Powerful regex-enabled search and replace functionality.
*   **⚙️ Fully Customizable**: Comprehensive settings to tweak typography, themes (Dark/Light), and editor behavior.
*   **🛡️ Secure & Robust**: Built with modern security practices and error reporting.

## 🚀 Installation & Download

### Pre-built Binaries
You can download the latest version of Codevora from our **[Releases Page](#)**.
*Note: Releases will be hosted on GitHub.*

### Building from Source

If you prefer to build Codevora yourself:

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/codevora.git
    cd codevora
    ```

2.  **Install dependencies**:
    ```bash
    npm install
    ```

3.  **Run in Development Mode**:
    ```bash
    npm run electron:dev
    ```

4.  **Build for Production**:
    ```bash
    # Build for Windows (Unpacked)
    npm run electron:build:dir
    ```
    The executable will be located in `dist-electron/win-unpacked/Codevora.exe`.

## 🎮 Shortcuts

| Shortcut | Description |
| :--- | :--- |
| `Ctrl + N` | New File |
| `Ctrl + O` | Open File |
| `Ctrl + S` | Save File |
| `Ctrl + Shift + S` | Save As... |
| `Ctrl + W` | Close Current Tab |
| `Ctrl + F` | Search / Find |
| `Ctrl + H` | Replace |
| `Ctrl + B` | Toggle Sidebar |
| `Ctrl + ,` | Open Settings |

## 🛠️ Technology Stack

*   **Frontend**: React.js, Vite
*   **Backend / Runtime**: Electron
*   **Editor Engine**: Monaco Editor (`@monaco-editor/react`)
*   **Styling**: Vanilla CSS with CSS Variables for theming

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1.  Fork the project
2.  Create your feature branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---
*Built with ❤️ by the Codevora Version 1.0.0 Team*
