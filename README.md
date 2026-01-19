# Vi-Connect 🎵
**Bond Beyond the Beats**

Vi-Connect is a lightweight desktop **music player application** built using **C# and the .NET Framework**.  
It allows users to play, pause, manage, and persist playlists from their local device with a clean and intuitive UI.

This project was developed as part of the **Advanced Programming (CSC-412)** course.

---

## ✨ Features

- Play, Pause, Stop, Next, Previous controls  
- Playlist management with persistent storage  
- Supports common audio formats (`.mp3`, `.wav`, `.m4a`, `.wma`, `.aac`)  
- Volume control, mute, repeat, and seek functionality  
- Keyboard shortcuts for media control  
- Album art extraction (when available)  
- SQLite database integration for saved songs  

---

## 🛠️ Tech Stack

- **Language:** C#  
- **Framework:** .NET Framework (WinForms)  
- **Database:** SQLite  
- **Media Engine:** Windows Media Player (WMPLib)  

---

## 📁 Project Structure

```
Project_Mp/
├── Form1.cs
├── Form1.Designer.cs
├── songs.db
├── App.config
├── Project_Mp.exe
└── README.md
```

---

## 🚀 How to Run

### Option 1: Run Executable (Windows)
1. Download `Project_Mp.exe`
2. Double-click to launch the application

### Option 2: Run from Visual Studio
1. Open the project in **Visual Studio**
2. Restore NuGet packages if required
3. Build and run the solution

---

## 🗄️ Database Design

- **Database:** `songs.db`
- **Table:** `Songs`

| Column | Type |
|------|------|
| Name | TEXT |
| Path | TEXT |

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|---|---|
| Space | Play / Pause |
| ↑ | Volume Up |
| ↓ | Volume Down |
| ← | Seek Backward |
| → | Seek Forward |
| M | Mute |
| R | Repeat |
| S | Stop |

---



## 📜 License

This project is intended for **educational purposes only**.  
You are free to study, modify, and extend it.

---

⭐ If you like this project, consider giving the repository a star!
