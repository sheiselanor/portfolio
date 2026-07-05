# Tasnim Mahdiya — Portfolio

A self-contained animated portfolio site. Your profile photo is embedded directly in `index.html`, and all demo videos, build docs, and n8n workflows live in `assets/`.

```
portfolio/
├── index.html                          ← the site (open this)
├── README.md                           ← this guide
└── assets/
    ├── profile-original.jpg
    ├── demos/                          ← play in the "Watch demo" lightbox
    │   ├── voice-ai-booking-demo.mp4  + poster
    │   └── avatar-coaching-demo.mp4   + poster
    ├── docs/                           ← "Documentation / Build doc / Test results" buttons
    │   ├── voice-booking-build-doc.pdf
    │   ├── avatar-coaching-documentation.pdf / -build-doc.pdf
    │   ├── jewelry-ai-documentation.pdf / -test-results.pdf
    │   ├── welly-whatsapp-documentation.pdf / -test-results.pdf
    │   ├── whatsapp-agent-build-doc.pdf
    │   ├── bplabs-roster-documentation.pdf / -test-results.pdf
    │   ├── crm-telegram-user-guide.pdf / -test-results.pdf
    │   ├── km-ecommerce-test-results.pdf
    │   ├── propertygenie-test-results.pdf
    │   ├── garboguard-walkthrough.pdf
    │   └── upm-booking-demo.pdf / -report.pdf
    └── workflows/                      ← "Workflow" buttons download these n8n JSONs
        ├── voice-booking-workflow.json
        ├── whatsapp-chat-workflow.json
        └── avatar-coaching-workflow.json
```

To preview locally, just double-click `index.html`. (The video and PDFs load from the `assets` folder, so keep them together.)

---

## How to make it public — 3 easy options

### Option A — GitHub Pages (free, uses the GitHub you already have)
1. Create a new repo on GitHub, e.g. **`portfolio`** (make it Public).
2. Upload **everything in this folder** — `index.html` and the whole `assets/` folder — into the repo (drag-and-drop on the GitHub web page works).
3. In the repo, go to **Settings → Pages**.
4. Under "Build and deployment", set **Source: Deploy from a branch**, **Branch: `main`**, folder **`/ (root)`**, then **Save**.
5. Wait ~1 minute. Your site goes live at:
   `https://sheiselanor.github.io/portfolio/`
6. (Optional) Rename the repo to **`sheiselanor.github.io`** and it will live at `https://sheiselanor.github.io/` instead.

### Option B — Netlify (free, drag-and-drop, fastest)
1. Go to **app.netlify.com** and sign up (you can use your GitHub login).
2. On the dashboard, find the **"Deploy manually"** drop zone (or Sites → Add new site → Deploy manually).
3. **Drag this entire `portfolio` folder** onto it.
4. Done — you get a live URL like `https://tasnim-mahdiya.netlify.app` in seconds. You can rename the site in Site settings.

### Option C — Vercel (free)
1. Go to **vercel.com**, sign up with GitHub.
2. Either import the GitHub repo from Option A, or use the Vercel CLI: install it, then run `vercel` inside this folder and follow the prompts.
3. Live at something like `https://tasnim-mahdiya.vercel.app`.

---

## Recommended: GitHub Pages
Since your GitHub is already `github.com/sheiselanor`, Pages keeps everything in one place and gives you a clean `sheiselanor.github.io` address you can put on your LinkedIn and CV.

## Custom domain (optional, ~$10/yr)
All three hosts let you connect a domain like `tasnimmahdiya.com`:
- Buy the domain (Namecheap, Cloudflare, Google Domains).
- In your host's dashboard (Netlify/Vercel/Pages → domain settings), add the domain and follow the DNS instructions they give you.

## Updating later
Edit `index.html` (or swap files in `assets/`), then re-upload / re-drag. On GitHub Pages and Vercel, if you connected the repo, just push your changes and it redeploys automatically.
