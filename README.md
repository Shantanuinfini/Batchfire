# 🔥 BatchFire — Square API Batch Runner

A powerful tool for running bulk Square API requests — create customers, book appointments, and more — all from a clean browser UI.

## Features
- **cURL Import** — paste cURLs straight from Claude, auto-detects multiple requests
- **Multi-request tabs** — run different endpoints in one batch
- **Smart variable suggestions** — previous API responses auto-populate dropdowns
- **Persistent token** — enter your Square token once, saved in localStorage
- **Sandbox / Production** toggle
- **Bulk import** — paste lists of customer IDs, emails, etc.
- **Live results** with response viewer

---

## 🚀 Deploy to Vercel (recommended — free, instant)

### Option A: Vercel Dashboard (no CLI needed)
1. Push this folder to a GitHub repo (see below)
2. Go to [vercel.com](https://vercel.com) → **Add New Project**
3. Import your GitHub repo
4. Leave all settings as default → click **Deploy**
5. ✅ You'll get a URL like `https://batchfire.vercel.app`

### Option B: Vercel CLI
```bash
npm i -g vercel
vercel
```
Follow the prompts — done in 60 seconds.

---

## 🚀 Deploy to GitHub Pages

1. Push this folder to a GitHub repo
2. Go to repo **Settings** → **Pages**
3. Under **Source**, select `main` branch and `/ (root)` folder
4. Click **Save**
5. ✅ Live at `https://YOUR_USERNAME.github.io/REPO_NAME`

---

## 📁 Push to GitHub (first time)

```bash
git init
git add .
git commit -m "init: BatchFire v1"
gh repo create batchfire --public --push --source=.
```

Or manually on github.com:
1. Create a new repo called `batchfire`
2. Upload `index.html`, `vercel.json`, `README.md`
3. Done

---

## Usage

1. Open the app
2. Paste your Square Access Token in the top bar (saved automatically)
3. Use **cURL Import** tab — paste cURLs from Claude and hit **Parse & Detect**
4. Import to **Requests** tab
5. Fill in variables (customer IDs, etc.) — smart suggestions appear from previous responses
6. Hit **▶ Run All**
