# CreativeLab Alif — Portfolio Website

Premium graphics design portfolio. Static HTML site hosted on GitHub + Cloudflare Pages.

## 🚀 Deploy to Cloudflare Pages

### Method 1: Cloudflare Pages (Recommended)
1. Push this repo to GitHub
2. Go to [Cloudflare Pages](https://pages.cloudflare.com/)
3. Click **Create a project → Connect to Git**
4. Select this repository
5. Build settings:
   - **Framework preset:** None
   - **Build command:** *(leave empty)*
   - **Build output directory:** `/` (root)
6. Click **Save and Deploy**

Your site is live in ~30 seconds! ⚡

### Method 2: GitHub Pages (backup)
1. Go to repo **Settings → Pages**
2. Source: **Deploy from a branch → main → / (root)**
3. Save — live at `https://yourusername.github.io/repo-name`

## 📁 File Structure

```
/
├── index.html          # Main portfolio page
├── README.md           # This file
└── _redirects          # Cloudflare/Netlify routing rules
```

## 🔧 Customization Checklist

Update these before going live:

- [ ] **WhatsApp link** in `index.html`: Replace `https://wa.me/` with `https://wa.me/YOUR_PHONE_NUMBER`
- [ ] **Fiverr link**: Replace with your actual Fiverr profile URL
- [ ] **Upwork link**: Replace with your actual Upwork profile URL
- [ ] **Facebook link**: Replace with your actual Facebook page URL
- [ ] **Pinterest link**: Replace with your actual Pinterest profile URL
- [ ] **Footer year**: Update `© 2025` if needed
- [ ] **Stats**: Update hero numbers (projects completed, client count, etc.)
- [ ] **Contact button**: Link "Start a Project" to your preferred contact method

## 🌐 Custom Domain (Cloudflare)

1. In Cloudflare Pages → your project → **Custom domains**
2. Add your domain (e.g. `creativelablaif.com`)
3. Update your domain's DNS to point to Cloudflare — handled automatically if domain is on Cloudflare

## ⚡ Performance

- Pure HTML/CSS/JS — no build step, no framework
- Fonts loaded from Google Fonts CDN
- Lazy scroll animations via IntersectionObserver
- Cloudflare CDN delivers assets globally from edge nodes

## 🎨 Tech Stack

- **HTML5** — semantic, SEO-friendly structure
- **CSS3** — custom properties, grid, flexbox, glassmorphism
- **Vanilla JS** — scroll reveal animations only
- **Hosting** — GitHub + Cloudflare Pages (free tier)
