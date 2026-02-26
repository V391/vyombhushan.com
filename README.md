# vyombhushan.com

Personal portfolio website for Vyom Bhushan.

## Deploy to GitHub Pages

### 1. Create repo & push

```bash
cd vyombhushan.com
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/v391/vyombhushan.com.git
git branch -M main
git push -u origin main
```

### 2. Enable GitHub Pages

- Go to **github.com/v391/vyombhushan.com** → **Settings** → **Pages**
- Source: **Deploy from a branch**
- Branch: **main** / root
- Click **Save**

### 3. Point your domain

At your domain registrar (GoDaddy, Namecheap, Cloudflare, etc.), add these DNS records:

**Option A — Apex domain (`vyombhushan.com`):**

| Type | Name | Value |
|------|------|-------|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | v391.github.io |

### 4. Enable HTTPS

- Back in GitHub Pages settings, check **Enforce HTTPS** (may take a few minutes after DNS propagates)

---

That's it! Site should be live at **https://vyombhushan.com** within minutes.
