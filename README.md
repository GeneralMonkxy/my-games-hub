# my-games-hub
# My Games Hub - Documentation & Cheat Sheet

Welcome to **My Games Hub**! This README contains instructions, tips, and notes for adding new games without touching the website HTML.

---

## 📝 Quick Add Guide

### 1️⃣ Prepare Your Game
- Host your game somewhere (GitHub Pages is easiest).
- Example URL: `https://yourusername.github.io/my-new-game/`
- Create a **preview image** (PNG or JPG, recommended 180×120px).

### 2️⃣ Upload Preview Image
- Go to your `my-games-hub` repo.
- Upload the image into the repo folder.
- Example: `newgame-preview.png`

### 3️⃣ Add Game to `games.json`
- Open your `games.json` file.
- Add a new entry in this format:

```json
{
  "name": "My New Game",
  "url": "https://yourusername.github.io/my-new-game",
  "image": "newgame-preview.png"
}
