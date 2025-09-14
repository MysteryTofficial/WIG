# 🚀 Windows Installer Generator (WIG)

<p align="center">
  <img src="WIG_logo.png" alt="WIG Logo" width="150"/>
</p>

<p align="center">
  <b>Generate a custom Windows installer from the Winget library!</b><br>
  Install or update multiple apps at once with a single .bat file.
</p>

---

## 🏷️ Badges

![License](https://img.shields.io/badge/License-MIT-blue.svg)  
![Version](https://img.shields.io/badge/version-1.0.0-brightgreen)  
![Build Status](https://img.shields.io/badge/build-passing-success)  
![Contributions](https://img.shields.io/badge/contributions-welcome-orange)

---

## 📑 Table of Contents

- [About the Project](#-about-the-project)
- [Getting Started](#-getting-started)
- [Screenshots / GIFs](#-screenshots--gifs)
- [How It Works](#-how-it-works)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)
- [License](#-license)
- [Acknowledgements](#-acknowledgements)

---

## 📖 About the Project

**Windows Installer Generator (WIG)** is a web-based tool that lets you generate a **custom .bat installer** using apps from the **Winget library**.  
Think of it like **Ninite**, but powered by Microsoft’s package manager.

### ✨ Why WIG?

- Installing multiple apps one by one is slow and tedious.  
- Updating software manually is error-prone.  
- WIG automates app installation, saving time and avoiding repetitive work.  

### ✅ Features

- ✅ Web interface to select apps from the Winget library  
- ✅ Generates a single `.bat` installer for Windows  
- ✅ Automatic updates for selected apps  
- ✅ Lightweight, fast, and easy to share  
- ✅ No dependencies other than Winget  

---

## ⚡ Getting Started

### 🔧 Prerequisites

- 🖥️ Windows 10/11  
- 📦 [Winget](https://learn.microsoft.com/en-us/windows/package-manager/winget/) installed  

### 📥 Installation

Clone the repo:

```bash
git clone https://github.com/yourusername/WIG.git
cd WIG
```

Launch the web app locally (example with Python Flask):

```bash
python app.py
```

Then open `http://localhost:5000` in your browser.

### ▶️ Example Usage

1. Open the WIG web interface.  
2. Select the apps you want to include.  
3. Click **Generate Installer**.  
4. Run the downloaded `.bat` file to install or update apps automatically.

---

## 🖼️ Screenshots / GIFs

> 🎥 Web interface demo and installer in action coming soon!

<p align="center">
  <img src="docs/images/demo.gif" alt="WIG Demo" width="600"/>
</p>

---

## ⚙️ How It Works

1. User selects apps on the web interface.  
2. WIG generates a `.bat` file with Winget commands.  
3. Running the `.bat` installs or updates all selected apps.  

### Example .bat snippet

```bat
@echo off
winget install --id=Google.Chrome -e --silent
winget install --id=Microsoft.VisualStudioCode -e --silent
winget install --id=Spotify.Spotify -e --silent
pause
```

---

## 🗺️ Roadmap

- [ ] Advanced web UI for app search and categories  
- [ ] Auto-update feature for generated installers  
- [ ] Support for offline installations  
- [ ] Downloadable config templates  

---

## 🤝 Contributing

Contributions are welcome! 🎉  
1. Fork the repo  
2. Create a branch (`git checkout -b feature/YourFeature`)  
3. Commit (`git commit -m 'Add YourFeature'`)  
4. Push (`git push origin feature/YourFeature`)  
5. Open a Pull Request  

Check [issues](https://github.com/yourusername/WIG/issues) for tasks.

---

## 📄 License

MIT License – see [LICENSE](LICENSE) for details.

---

## 🙏 Acknowledgements

- 📌 [Winget](https://learn.microsoft.com/en-us/windows/package-manager/winget/) – Microsoft’s package manager  
- 📌 Inspired by Ninite and other installer automation tools  
- 📌 Thanks to the open-source community 💙  

---

<p align="center">✨ Made with passion by MysteryT (Péter) ✨</p>
