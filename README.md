# 🎲 RandomGameLauncher

![GitHub release](https://img.shields.io/github/v/release/RMAipassa/RandomGameLauncher)
![License](https://img.shields.io/github/license/RMAipassa/RandomGameLauncher)
![Repo Size](https://img.shields.io/github/repo-size/RMAipassa/RandomGameLauncher)

RandomGameLauncher is a lightweight Windows desktop app that **launches a random installed game** across multiple launchers — perfect for defeating decision fatigue and tackling that ever-growing backlog.

---

## 🚀 Features

- ✅ Detects installed games from:
  - Steam (multi-library support)
  - Epic Games
  - GOG
  - Riot (VALORANT / League of Legends)
  - Amazon Games
  - Xbox (Xbox/Gaming Services titles only)
  - Ubisoft Connect
- 🎲 Launch a truly random game
- ⭐ Favorites system & Favorites-only mode
- 🚫 Exclude games you don’t want included
- 🏷️ Tagging + tag-based filtering + pick random from selected tags (no typing required)
- ⬇️ Import Steam tags (Steam Store tags + genres)
- ⏱️ Playtime:
  - Steam API playtime fetch (SteamID auto-detect + API key)
  - Tracked playtime for any launcher (time launched via this app)
- 📜 Random history & statistics (stored locally)
- 🔎 Search + keyboard shortcuts (Ctrl+R, Ctrl+F)
- 🖥 Tray icon support
- 🎨 Themes (Light/Dark/System) with Fluent-style backdrop (Mica/Acrylic) + Windows accent color integration

---

## 📦 Installation

Download the latest release and run:

```
RandomGameLauncher.exe
```

Config is stored at:

```
%APPDATA%\RandomGameLauncher\config.json
```

If you’re upgrading from older dev builds and run into config load issues, you can delete the config file above (you’ll lose favorites/tags/history).

---

## 🛠 Built With

- .NET 8 (WPF)
- Steam manifest parsing
- Epic manifest parsing
- Windows DPAPI for secure Steam API key storage
- Microsoft.Data.Sqlite (used for Amazon Games local data discovery)

---

## 🙌 Support

If you enjoy what I create, you can support me at:

https://ko-fi.com/rubenaipassa
