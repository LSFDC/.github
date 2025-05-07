# Lost Saga Community Rebuild (Open Source Project)

![Banner](https://wallpapercave.com/wp/wp1899234.jpg)

Welcome to the Lost Saga open-source revival — a learning-focused initiative built on the 2014 legacy source. Our mission is to explore how the game works, improve its systems, and grow a passionate development community around it.

> [!NOTE] 
> This project is for educational and development purposes only. We do **not** support or encourage cheating in any official versions (KR, TW, CN, or ORIGIN).  
> This is a freely shared project, based on publicly available 2014 source code. **Commercial use or resale is strictly prohibited.**

---

## 🔧 Dev Environment

To get started, you’ll need:

- [Visual Studio 2010 Ultimate](https://my.visualstudio.com/Downloads?q=visual%20studio%202010%20Ultimate)
- [Visual Studio 2022 or newer](https://visualstudio.microsoft.com/vs/)
- [DirectX SDK (June 2010)](https://www.microsoft.com/en-us/download/details.aspx?id=6812)
- [Docker](https://www.docker.com/)
- [Navicat Premium (for DB)](https://discord.com/channels/1087610713821958184/1102622792534470747/1102623066229592176)

---

## 📦 Project Resources

- [2014 Lost Saga Source Base](https://drive.google.com/file/d/1kUgJKnl6CeoCsSUpEkD7qIMF7aix7dbR/view)
- [Merged Client Pack](https://drive.google.com/file/d/1XW8TpDMp8FkK3fcG0Zh5zr5izTbbWX-j/view)
- [Boost Libraries (Vanilla)](https://www.boost.org/users/history/version_1_50_0.html)

---

### Boost Build Example

```
bootstrap.bat
b2 threading=multi --build-type=complete --stagedir=./stage/ --toolset=msvc-10.0 -j 12
```

## 🤝 Connect & Contribute

Whether you're experimenting, debugging, or developing a private project — you're welcome here.  
Join our growing community:

[![Discord](https://img.shields.io/badge/Join-Discord-5865F2?logo=discord&style=flat-square)](https://discord.gg/b5MeZxYEZf)  
[![YouTube](https://img.shields.io/badge/Watch-YouTube-FF0000?logo=youtube&style=flat-square)](https://www.youtube.com/@lsfdyt)

---

## ❤️ Community First

This is a community-led project. No ego, no gatekeeping — just developers and fans learning together.  
Feel free to fork, improve, or open discussions. Let's keep Lost Saga's legacy alive in code.
