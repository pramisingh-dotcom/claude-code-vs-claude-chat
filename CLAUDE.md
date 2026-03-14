# CLAUDE.md

## Project Overview
A static HTML comparison page explaining the differences between **Claude Code** and **Claude Chat** — deployed on GitHub and Vercel.

## Project Structure
```
/
└── index.html   # Single-page static site (all HTML/CSS/JS inline)
```

## Design
- **Theme**: Dark editorial split-layout
- **Left panel**: Claude Code (terminal aesthetic, green accents, JetBrains Mono)
- **Right panel**: Claude Chat (conversational feel, amber accents, Fraunces serif)
- **Fonts**: Fraunces (display), JetBrains Mono (code), DM Sans (body) via Google Fonts
- **No build step** — pure HTML/CSS/JS, no framework, no dependencies

## Deployment
- **GitHub**: https://github.com/pramisingh-dotcom/claude-code-vs-claude-chat
- **Vercel**: Auto-deploys from `main` branch on every push

## Making Changes
Edit `index.html` directly. Push to `main` to trigger a Vercel redeploy:
```bash
git add index.html
git commit -m "your message"
git push origin main
```

## Content Sections
1. **Split panels** — feature highlights for each product with live demos (terminal animation / chat bubbles)
2. **Comparison table** — 12-row side-by-side capability breakdown
3. **Use cases** — when to reach for each product
4. **Footer** — links to claude.ai and Claude Code docs
