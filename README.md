# Color Rush — Privacy Policy

Official Privacy Policy page for **Color Rush**, a fast-paced offline reflex game developed by **Shiva's Gaming Studio**.

This repository hosts a standalone, self-contained HTML/CSS Privacy Policy page that is ready for instant deployment to **GitHub Pages** — satisfying Google Play's requirement for a publicly accessible privacy policy URL.

---

## 📋 Contents

```
privacy-policy/
├── index.html      # Full Privacy Policy page
├── style.css       # Responsive stylesheet (dark + light theme)
├── README.md       # This file
├── LICENSE         # MIT License
└── .gitignore      # Standard web project ignores
```

---

## 🎮 About Color Rush

| Property           | Value                            |
|--------------------|----------------------------------|
| **Game Name**      | Color Rush                       |
| **Developer**      | Shiva's Gaming Studio            |
| **Platform**       | Android (Google Play)            |
| **Engine**         | Flutter + Flame Engine           |
| **Genre**          | Hyper-Casual · Reflex · Arcade   |
| **Internet**       | Offline-First (100% Offline)     |
| **Age Rating**     | Everyone (7+)                    |
| **Monetisation**   | Google AdMob (Free to Play)      |
| **User Accounts**  | None                             |
| **Data Collected** | None (by us)                     |

---

## 🚀 GitHub Pages Deployment Guide

Follow these steps to publish the privacy policy at a public URL.

### Step 1 — Create a GitHub Repository

1. Sign in to [github.com](https://github.com).
2. Click **New repository**.
3. Name it something clear, e.g. `color-rush-privacy-policy`.
4. Set visibility to **Public** (required for GitHub Pages).
5. Click **Create repository**.

### Step 2 — Push This Folder to GitHub

```bash
# Navigate to this folder
cd privacy-policy

# Initialise git (if not already done)
git init

# Add all files
git add .

# Commit
git commit -m "Initial privacy policy page"

# Add remote origin (replace with your repo URL)
git remote add origin https://github.com/YOUR_USERNAME/color-rush-privacy-policy.git

# Push
git push -u origin main
```

### Step 3 — Enable GitHub Pages

1. In your repository, go to **Settings → Pages**.
2. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
3. Click **Save**.
4. After a few seconds, GitHub will display your live URL:
   ```
   https://YOUR_USERNAME.github.io/color-rush-privacy-policy/
   ```

### Step 4 — Add URL to Google Play Console

1. Open [Google Play Console](https://play.google.com/console).
2. Go to your app → **App content → Privacy Policy**.
3. Paste your GitHub Pages URL.
4. Click **Save**.

> **Tip:** Custom domain names (e.g. `privacy.shivasgamingstudio.com`) can be configured under repository Settings → Pages → Custom domain.

---

## 🖥️ Local Preview Guide

No build tools or Node.js are required. The page is pure HTML + CSS.

### Option A — Open Directly in Browser

```bash
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

### Option B — Use Python's Built-In Server (Recommended)

```bash
# Python 3
python -m http.server 8080

# Then open in browser:
# http://localhost:8080
```

### Option C — Use VS Code Live Server Extension

1. Install the **Live Server** extension in VS Code.
2. Right-click `index.html` → **Open with Live Server**.
3. Your browser will open with hot-reload enabled.

---

## ✅ Compliance Checklist

| Requirement                          | Status |
|--------------------------------------|--------|
| Google Play Developer Policy         | ✅     |
| Google AdMob Policy                  | ✅     |
| GDPR Basic Disclosure                | ✅     |
| COPPA (Children's Privacy)           | ✅     |
| Google Play Services Disclosure      | ✅     |
| Publicly Accessible URL              | ✅     |
| Mobile-Friendly Design               | ✅     |
| Dark & Light Theme Support           | ✅     |

---

## 🎨 Design Features

- **Pure HTML + CSS** — zero JavaScript, zero frameworks
- **Responsive** — optimised for all screen sizes (320px–1920px)
- **Dark + Light Theme** — respects `prefers-color-scheme` automatically
- **Google Fonts** — Inter + Space Grotesk for professional typography
- **Fast Loading** — no runtime dependencies; single CSS file
- **Accessible** — semantic HTML5, ARIA labels, keyboard-navigable
- **Print Ready** — clean print stylesheet included

---

## 📄 License

This Privacy Policy page template is released under the [MIT License](LICENSE).

The Privacy Policy *content* is specific to Color Rush and Shiva's Gaming Studio.
If you adapt this for your own app, update all app-specific details accordingly.

---

## 📦 Version

| Field        | Value          |
|--------------|----------------|
| **Version**  | 1.0.0          |
| **Released** | July 27, 2026  |
| **Author**   | Shiva's Gaming Studio |

---

*Built with care by Shiva's Gaming Studio — Karnataka, India.*
