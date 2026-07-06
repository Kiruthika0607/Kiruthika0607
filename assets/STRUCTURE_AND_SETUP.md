# 📁 Repository Structure & Setup Guide

```
Kiruthika0607/
├── README.md                                  ← main profile page
├── .github/
│   └── workflows/
│       └── snake.yml                          ← auto-generates the snake animation
└── assets/
    ├── BANNER_SPEC.md                         ← design instructions for a custom banner
    ├── STRUCTURE_AND_SETUP.md                 ← this file
    └── banner.png                             ← (optional) your custom static banner, once made
```

## ✅ Setup Checklist

1. **Repo name must match your username** — this special repo (`Kiruthika0607/Kiruthika0607`)
   is what GitHub renders on your profile page automatically.
2. **Enable the snake workflow**
   - Push `.github/workflows/snake.yml` to `main`.
   - Go to the repo's **Actions** tab → allow workflows to run → manually trigger
     "Generate Snake Contribution Animation" once so the `output` branch gets created.
   - After the first run, it will auto-refresh every 6 hours.
3. **Update placeholder links** in the README's *Connect With Me* section:
   - Replace `youremail@example.com` with your real email
   - Replace `your-linkedin-handle`, `your-handle` (Instagram/Twitter) with your real profile links
   - Remove any social badge you don't use
4. **Verify stats widgets load** — `github-readme-stats`, `github-readme-streak-stats`, and
   `github-profile-trophy` are shared public Vercel/Heroku instances. If one is rate-limited or
   down, GitHub will just show a broken image icon temporarily — no action needed, it self-recovers.
5. **(Optional) Custom banner** — follow `BANNER_SPEC.md` to design a static banner and place it
   at `assets/banner.png`, then update the hero `<img src="...">` in `README.md`.
6. Commit and push — your profile is live at `https://github.com/Kiruthika0607`.

## 🔗 Key Services Used (all free, no API key required)

| Purpose | Service |
|---|---|
| Typing animation | readme-typing-svg.demolab.com |
| Hero banner | capsule-render.vercel.app |
| Tech icons | skillicons.dev |
| Progress bars | progress-bar.dev |
| Stats card | github-readme-stats.vercel.app |
| Streak card | github-readme-streak-stats.herokuapp.com |
| Top languages | github-readme-stats.vercel.app/api/top-langs |
| Activity graph | github-readme-activity-graph.vercel.app |
| Trophies | github-profile-trophy.vercel.app |
| Snake animation | Platane/snk (GitHub Action) |
| Visitor counter | komarev.com/ghpvc |
| Badges | img.shields.io |
