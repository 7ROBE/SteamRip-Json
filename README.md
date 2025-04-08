# 🎮 SteamRip Game List (JSON)

This JSON file contains a comprehensive list of PC games scraped from [SteamRip](https://steamrip.com), including key metadata and multiple download links per game.

---

## 📦 File Overview

- **Filename:** `steamrip_games.json`
- **Encoding:** UTF-8
- **Format:** Standard JSON
- **Top-level key:** `"downloads"` – contains an array of game entries
- **JSON Preview** [SteamRip JSON](https://raw.githubusercontent.com/7ROBE/SteamRip-Json/refs/heads/main/steamrip_games.json)

---

## 📑 JSON Structure

Each entry in the `downloads` array includes the following fields:

```json
{
  "title": "Game Name",
  "version": "v1.0",
  "file_size": "10 GB",
  "genre": "Action, RPG",
  "upload_date": "2025-04-08T14:00:00+00:00",
  "download_urls": [
    "https://gofile.io/...",
    "https://buzzheavier.com/...",
    ...
  ]
}

