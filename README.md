# ProCraft Solutions Website

## Deploy to Railway (Free)

### Option A — Deploy from GitHub (recommended)

1. **Create a free GitHub account** at github.com if you don't have one
2. **Create a new repository** called `procraft-solutions`
3. **Upload these 3 files** into the repo: `index.html`, `server.js`, `package.json`
4. **Go to railway.app** and sign up for free (use your GitHub login)
5. Click **"New Project" → "Deploy from GitHub repo"**
6. Select your `procraft-solutions` repo
7. Railway auto-detects Node.js and deploys — takes about 60 seconds
8. Click **"Generate Domain"** to get your free URL (e.g. procraft-solutions.up.railway.app)

### Option B — Deploy with Railway CLI

```bash
npm install -g @railway/cli
railway login
railway init
railway up
railway domain
```

## Files included

- `index.html` — The full website
- `server.js` — Minimal Express server Railway uses to serve the site
- `package.json` — Node dependencies

## Customize

- Edit `index.html` to update text, phone, email, services, colors
- The blue brand color is `#2c5fad` throughout — search & replace to change it
- To add a real contact form backend, look into Formspree (free) or EmailJS

## Custom domain (optional)

In Railway dashboard → your project → Settings → Domains → add your own domain.
