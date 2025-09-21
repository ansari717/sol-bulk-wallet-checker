# sol-bulk-wallet-checker
# 🚀 Free GMGN Bulk Wallet Balance Checker (100% Free Forever)

> ✅ No API keys • No proxies • No Render/Heroku/Vercel • No credit card • Educational Use Only  
> Built with ❤️ using only **GitHub Pages + GitHub Actions** — 100% free, forever.

---

## 🌟 What This Tool Does

This tool lets you **check Solana wallet balances in bulk** using GMGN.ai’s public API — without hitting Solana RPC rate limits.

It’s designed for:
- Traders tracking multiple wallets
- Researchers analyzing on-chain activity
- Educators & students learning web3 scraping
- Anyone who wants free, automated balance checks

---

## 🔧 How It Works (Simple!)

1. **Frontend**: Hosted on **GitHub Pages** → `index.html` runs in your browser.
2. **Backend**: **GitHub Actions** runs every hour → scrapes GMGN → updates `balances.json`.
3. **Data Storage**: Results saved in `/data/balances.json` → served via GitHub’s raw CDN.
4. **Zero Cost**: No servers, no databases, no APIs — just Git + Actions.

---

## 🖥️ Live Demo

👉 [https://your-github-username.github.io/gmgn-bulk-checker/](https://your-github-username.github.io/gmgn-bulk-checker/)

*(Replace `your-github-username` with your actual GitHub username after deploying)*

---

## 🛠️ How to Deploy Your Own (Free in <5 mins)

### Step 1: Fork This Repo
Click "Fork" → create your own copy.

### Step 2: Enable GitHub Pages
1. Go to **Settings → Pages**
2. Branch: `main`
3. Folder: `/ (root)`
4. Click **Save**

→ Your site will be live at:  
`https://your-username.github.io/gmgn-bulk-checker/`

### Step 3: Enable GitHub Actions (Auto-Scraping)
1. Go to **Actions** tab → click “I understand...” → Enable Actions.
2. Go to **Actions → Scrape GMGN Balances → Run workflow** → click “Run workflow”

→ Every hour, it auto-updates balances!

---

## 📂 Project Structure
