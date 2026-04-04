# 🎮 BirthdayApp — Fake Error Birthday Surprise for Udochi

A single-page, Roblox Bedwars-themed birthday surprise website that starts as a
convincing fake crash screen and reveals a personalised birthday message (and gift card)
when the recipient clicks the **[ Reconnect ]** button.

---

## 🚀 Deploy to GitHub Pages

1. **Push this repository** to GitHub (it already contains `index.html` at the root).
2. Open the repo on GitHub → **Settings** → **Pages**.
3. Under *Source*, select **Deploy from a branch**.
4. Choose branch `main` (or `master`) and folder `/ (root)`.
5. Click **Save**.
6. After a minute or two your site will be live at:
   ```
   https://<your-github-username>.github.io/<repo-name>/
   ```
7. Share that link with Udochi!

---

## 🎁 Replacing the Gift Card Code

1. Open `index.html` in any text editor.
2. Find the line:
   ```html
   <div id="gift-code-display">[ GIFT CARD CODE HERE ]</div>
   ```
3. Replace `[ GIFT CARD CODE HERE ]` with the actual gift card code, e.g.:
   ```html
   <div id="gift-code-display">ROBUX-XXXX-YYYY-ZZZZ</div>
   ```
4. Commit and push the change — GitHub Pages will update automatically within a minute.

---

## ✨ Features

| Feature | Description |
|---|---|
| Phase 1 | Roblox Bedwars-style fake crash screen with traceback & blinking cursor |
| Phase 2 | Glitch transition → confetti → line-by-line birthday rewrite → cake art → gift card |
| Easter egg 1 | `console.log` message for inspectors |
| Easter egg 2 | Page `<title>` switches from the error title to `🎂 Happy Birthday Udochi!` |
| Easter egg 3 | HTML comment in source: `<!-- No bugs here, only birthday wishes for Udochi -->` |
| Easter egg 4 | Pressing any key before clicking shows a fake `sudo unwrap gift` / `Permission denied` terminal line |

---

## 📁 File Structure

```
BirthdayApp/
├── index.html   ← The entire app (HTML + CSS + JS, all inline)
└── README.md    ← This file
```
