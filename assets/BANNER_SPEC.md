# 🎨 Premium Banner Design Specification

The README currently uses a live **capsule-render** SVG banner (no design work needed — it
renders automatically). If you'd like a custom static PNG banner instead (e.g. designed in
Figma/Canva), use this spec so it matches the rest of the profile.

## Canvas

| Property | Value |
|---|---|
| Dimensions | 1584 × 396 px (GitHub-safe banner ratio, 4:1) |
| Format | PNG (transparent edges optional) or SVG |
| File name | `assets/banner.png` |
| Safe margin | 60px on all sides (keep text inside) |

## Color Palette (Dark Glassmorphism / Purple-Blue)

| Role | Hex | Usage |
|---|---|---|
| Background base | `#0F0C29` → `#302B63` → `#24243E` | Diagonal gradient background |
| Primary accent | `#8A2BE2` | Headings, glow accents |
| Secondary accent | `#6C63FF` | Buttons, badges, highlights |
| Tertiary accent | `#B49CFF` | Subtext, icons |
| Glass panel fill | `rgba(255,255,255,0.06)` | Card background |
| Glass panel border | `rgba(255,255,255,0.15)` | 1px card border |
| Text primary | `#F5F3FF` | Headline text |
| Text secondary | `#C9C3E0` | Subheadline / tagline |

## Typography

- **Headline ("Kiruthika R")**: Poppins SemiBold / Bold, 56–64px, letter-spacing +1px, color `#F5F3FF`
- **Subheadline (role/tagline)**: Inter or Poppins Regular, 20–22px, color `#C9C3E0`
- **Accent word highlight**: apply gradient text fill `#8A2BE2 → #6C63FF`

## Layout

1. Diagonal or radial gradient background (`#0F0C29 → #302B63 → #24243E`)
2. Subtle blurred glowing orbs (purple/blue) top-right and bottom-left for depth
3. Left-aligned or centered text block: Name → Role/tagline → 3 tech icons (React/Python/AI)
4. Optional thin glass "chip" badges (`Full Stack` · `AI` · `UI/UX`) under the tagline
5. Faint grid/noise texture overlay at 4–6% opacity for a premium, non-flat feel

## Icons

Use [skillicons.dev](https://skillicons.dev) or [Simple Icons](https://simpleicons.org) for
consistency with the rest of the README:
`react`, `python`, `java`, `html`, `css`, `js`, `mysql`, `git`, `github`, `figma`, `vscode`, `c`, `cpp`

## Tools to generate it without design software

- **Canva** — search "GitHub profile banner", apply the palette above
- **Figma** — 1584×396 frame, use the gradient + typography specs above
- **capsule-render** (already wired into the README, zero setup):
  `https://capsule-render.vercel.app/api?type=waving&color=0:0F0C29,50:302B63,100:24243E&height=260&section=header&text=Kiruthika%20R&fontSize=60&fontColor=C9B6FF`

Once you export a static banner, drop it at `assets/banner.png` and swap the `<img>` src in the
README's hero section.
