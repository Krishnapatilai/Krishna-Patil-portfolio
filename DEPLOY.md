# Krishna Patil Portfolio — Deployment Guide

## What's included
- `index.html` — complete single-file portfolio (zero dependencies, zero build step)
- Place your resume PDF as `Krishna_Patil_resume_PM.pdf` in the same folder
- Photography: replace placeholder divs with `<img src="your-photo.jpg">` inside `.photo-item`

---

## Deploy to GitHub Pages (Free, 5 minutes)

### Step 1 — Create GitHub repo
1. Go to https://github.com/new
2. Name it `krishna-patil-portfolio` (or `yourusername.github.io` for a root URL)
3. Set to **Public**
4. Click **Create repository**

### Step 2 — Push your files
```bash
# In your portfolio folder
git init
git add .
git commit -m "Initial portfolio launch"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/krishna-patil-portfolio.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: **main** · Folder: **/ (root)**
4. Click **Save**

Your site will be live at:
`https://YOUR_USERNAME.github.io/krishna-patil-portfolio/`

---

## Custom Domain (Optional)
1. Buy a domain (e.g. `krishnapatil.me`) from Namecheap/GoDaddy (~$10/yr)
2. In GitHub Pages settings, enter your custom domain
3. In your DNS provider, add:
   - A records pointing to GitHub IPs: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - Or CNAME: `YOUR_USERNAME.github.io`

---

## Customization Checklist
- [ ] Add LinkedIn URL in contact section (search `href="https://linkedin.com"`)
- [ ] Add GitHub URL (search `href="https://github.com"`)
- [ ] Add your resume PDF as `Krishna_Patil_resume_PM.pdf`
- [ ] Replace photo placeholders with real photos
- [ ] Update conversation cards with real stories
- [ ] Update achievement #2 with specific competition details

---

## Updating later
```bash
git add .
git commit -m "Updated case studies / new project"
git push
```
Site auto-updates within 1-2 minutes.
