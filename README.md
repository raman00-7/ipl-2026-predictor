# 🏆 IPL 2026 Playoff Predictor

A sleek, interactive web app to simulate and predict IPL 2026 playoff qualifications — with **live match result sync** via CricketData.org API.

![IPL 2026 Predictor](https://scores.iplt20.com/ipl/teamlogos/CSK.png)

---

## ✨ Features

- 📊 **Live Points Table** — 3-zone coloring (Q1 / Qualifier / Danger) with Max Pts badges
- 🗓️ **Remaining Fixtures** — Auto-detects TODAY's match, past pending results, and upcoming games
- 🎯 **Click to Simulate** — Click any team in a fixture to set the winner instantly
- 📈 **NRR Simulator** — Inline Big Win / Small Win / Narrow Loss / Heavy Loss per match
- ⭐ **Team Qualification Tracker** — Pick any team from the dropdown to see their path to the playoffs
- 📡 **Live Sync** — Auto-fetches completed IPL match results using the free CricketData.org API
- 🔄 **Date-aware** — TODAY badge and match status update automatically every day

---

## 🚀 Getting Started

### 1. Clone / Download

```bash
git clone https://github.com/raman00-7/ipl-2026-predictor.git
cd ipl-2026-predictor
```

Or just **[Download ZIP](../../archive/refs/heads/main.zip)** and open `index.html` in your browser.

### 2. Get Your Free API Key

To enable live match result sync:

1. Go to **[cricketdata.org](https://cricketdata.org)**
2. Sign up for a free account (takes ~1 minute)
3. Check your email for your password → log in
4. Copy your **Lifetime Free API Key** from the dashboard

> 💡 The free tier gives **100 requests/day** — more than enough since the app auto-polls every 5 minutes.

### 3. Open the App

Just open `index.html` in any browser. On first launch you'll see:

```
🏆 IPL 2026 Predictor
┌─────────────────────────────────┐
│ Step 1: Visit cricketdata.org   │
│ Step 2: Get your free key       │
│ Step 3: Paste it below          │
│                                 │
│ [_________________________]     │
│  ⚡ Connect & Start Predicting  │
└─────────────────────────────────┘
```

Paste your key → click **Connect** → done! Your key is stored in your browser's `localStorage` only — it's **never shared or uploaded anywhere**.

---

## 🔑 Privacy

- Your API key is saved **only in your own browser** (`localStorage`)
- No data is sent to any server except the CricketData.org API you connect to
- Every user who opens this page uses **their own personal API key**

---

## 📁 Project Structure

```
IPL 2026 Predictor/
└── index.html          # Entire app — single file, no dependencies
└── README.md           # This file
```

No build step. No npm. No framework. Pure HTML + CSS + Vanilla JS.

---

## 🛠️ Tech Stack

| Layer | Tech |
|-------|------|
| Structure | HTML5 |
| Styling | Vanilla CSS (Glassmorphic dark theme) |
| Logic | Vanilla JavaScript |
| Fonts | Google Fonts — Inter |
| Logos | Official IPL CDN |
| Live Data | [CricketData.org API](https://cricketdata.org) (free tier) |

---

## 📸 Preview

| Feature | Screenshot |
|---------|------------|
| Points Table (3-zone coloring) | Q1 → Gold border, Qualifier → Green, Danger → Red |
| Qualification Tracker | Team-colored gauge + dependency analysis |
| NRR Simulator | Inline per-fixture win-margin buttons |
| Live Sync bar | 🟡 Fetching → 🟢 Synced |

---

## 📜 License

MIT — free to use, modify, and share.

---

Made with ❤️ for IPL 2026 fans
