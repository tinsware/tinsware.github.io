# tinsware — branding page

One-page branding site for **tinsware** with a matrix rain background animation.

## Files

| File | Description |
|------|-------------|
| `index.html` | Single-file site (HTML + CSS + JS) |
| `logo.jpg` | tinsware logo |
| `matrix.otf` | Matrix Code NFI font for rain animation |

## Deployment (GitHub Pages)

1. Push this repo to GitHub.
2. Go to **Settings > Pages**.
3. Set source to the branch and root folder (`/`).
4. Site will be live at `https://<username>.github.io/<repo-name>/`.

## Customization

All animation settings are at the top of the `<script>` block in `index.html`:

```
OPACITY       — Letter visibility (0.0 – 1.0)
SPEED         — Animation speed (0.2 slow, 1 default, 2 fast)
FONT_SIZE     — Character cell size in px
COLOR         — Letter color (hex)
COL_WIDTH     — Column width in cells
COL_GAP       — Empty cells between columns
TRAIL_MIN     — Minimum rows a column writes
TRAIL_MAX     — Maximum rows a column writes
ERASE_DELAY   — Frames to wait before erasing starts
ERASE_SPEED   — Rows the erase cursor advances per frame
FADE_STEPS    — Steps to fully fade out a cell
FADE_IN_STEPS — Steps to fully fade in a new cell
```

## Links to update

In `index.html`, replace the placeholder values:

- **Discord** — change `https://discord.gg/LINKINI-YAZ` to your invite link
- **Contact** — change `mailto:contact@tinsware.com` to your email
- **GitHub** — verify `https://github.com/tinsware` is correct
