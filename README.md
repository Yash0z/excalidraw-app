# Excalidraw Desktop App

This project packages the [Excalidraw](https://excalidraw.com/) web application into a standalone desktop application using Electron.

## Features 🚀

-  **Standalone Desktop Application:** Run Excalidraw as a native app on your desktop without the need for a browser.
-  **Cross-Platform Compatibility:** Can be adapted to work on Linux, Windows, and macOS.
-  **Simple and Lightweight:** Uses Electron to wrap the web app in a minimal, efficient package.

## Installation ⚙️

### Prerequisites

-  **Node.js and npm:** Install from your package manager (e.g., `sudo pacman -S nodejs npm`).
-  **Electron Packager:** Install globally via npm:
   ```bash
   npm install -g electron-packager
   ```

### Setting Up the Project

-  Clone the repository and navigate to the project directory:

       git clone https://github.com/Yash0z/excalidraw-app.git
       cd excalidraw-app

-  Install dependencies:

       npm install
       npm install electron --save-dev
       npm install -g electron-packager
       

-  Package the application for Linux:

       electron-packager . Excalidraw --platform=linux --arch=x64 --out=release-build

-  Running the App

       cd release-build/Excalidraw-linux-x64
       ./Excalidraw

## Acknowledgements 🏆

-  [Excalidraw](https://github.com/excalidraw/excalidraw): The amazing web-based drawing tool.
-  [Electron](https://github.com/electron/electron): Framework for building cross-platform desktop apps with JavaScript, HTML, and CSS.
