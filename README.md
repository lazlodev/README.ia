# ✨ README.IA: Your AI-Powered README Generator for VS Code

[![Version](https://img.shields.io/badge/version-0.0.3-blue.svg)](https://marketplace.visualstudio.com/items?itemName=lazlodev.readme-ia)
[![VS Code Marketplace](https://img.shields.io/badge/VS%20Code%20Marketplace-Install%20Now-informational?logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=lazlodev.readme-ia)
[![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-brightgreen?logo=github)](https://github.com/lazlodev/README.IA)

Elevate your project documentation instantly with **README.IA**, an innovative Visual Studio Code extension designed to automatically generate high-quality `README.md` files. Leveraging the power of Google Gemini's Artificial Intelligence, README.IA analyzes your project's codebase to craft comprehensive and visually appealing documentation, saving you valuable time and effort.

## 🚀 Technologies

*   **TypeScript** 📘: Primary language for robust and scalable development.
*   **Node.js** 🟢: Runtime environment powering the extension.
*   **Visual Studio Code API** 💻: For seamless integration within the VS Code ecosystem.
*   **Google Gemini API** ✨: The intelligent core for code analysis and README generation.
*   **ESLint** 🧹: For maintaining code quality and consistency.
*   **Markdown** 📝: The standard format for the generated READMEs.

## ✨ Features

*   **AI-Powered README Generation**: Instantly create comprehensive `README.md` files for your projects using Google Gemini.
*   **Codebase Analysis**: Intelligently reads and understands your project's source code to generate relevant documentation.
*   **VS Code Integration**: Seamlessly available as a command within your Visual Studio Code environment.
*   **Google Gemini API Key Management**: Easily set and reinitialize your API key directly from VS Code.
*   **Multi-language Support**: Provides UI messages and generates READMEs in both English and French.
*   **Progress Indicators**: Keep track of the generation process with informative progress messages.

## 📦 Installation & Usage

### Installation

1.  Open Visual Studio Code.
2.  Go to the Extensions view (`Ctrl+Shift+X` or `Cmd+Shift+X`).
3.  Search for "README.IA".
4.  Click "Install".
5.  Alternatively, install directly from the [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=lazlodev.readme-ia).

### Setup your Google Gemini API Key

Before generating your first README, you'll need to provide your Google Gemini API key:

1.  Open the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P`).
2.  Type and select `README.IA: Generate README.md`.
3.  If no API key is set, a prompt will appear asking for your Google Gemini API key.
4.  Enter your key and press `Enter`. The key will be stored locally for future use.

If you need to change or remove your API key:

1.  Open the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P`).
2.  Type and select `README.IA: Reinitialize gemini key`.

### Generating a README

1.  **Open your project folder** in Visual Studio Code. (The extension needs an open folder to read your project's code).
2.  Open the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P`).
3.  Type and select `README.IA: Generate README.md`.
4.  The extension will analyze your code and generate a `README.md` file in your project's root directory.
5.  You'll see progress notifications and a success message upon completion.

## 🙏 Credits

Developed with ❤️ by [@lazlodev](https://github.com/lazlodev).
