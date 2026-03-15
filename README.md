# Wallet Trading Analysis Dashboard

BSC wallet analysis — `0xa593d6e617e3d7165a1cbdc93c9ea3e55bbee85c`  
Period: Mar 4–15 2026 · 36,824 TXs · $1.5M volume

## Deploy to Vercel via GitHub

### 1. Create a GitHub repository

```bash
git init
git add .
git commit -m "Initial commit — wallet dashboard"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/wallet-dashboard.git
git push -u origin main
```

### 2. Deploy on Vercel

1. Go to [vercel.com](https://vercel.com) and sign in with GitHub
2. Click **Add New → Project**
3. Import your `wallet-dashboard` repository
4. Vercel will auto-detect the static site — no build settings needed
5. Click **Deploy**

Your dashboard will be live at `https://wallet-dashboard-xxx.vercel.app`

### 3. Custom domain (optional)

In Vercel project settings → Domains → add your domain.

---

## Files

| File | Description |
|------|-------------|
| `index.html` | The full dashboard — self-contained, no dependencies |
| `vercel.json` | Vercel deployment config |
| `README.md` | This file |
