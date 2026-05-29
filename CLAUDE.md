# claudedammit

## What this is
A personal site showcasing AI-powered apps and demos with a comedic, satirical tone — proving AI tools are powerful AND weird. The mascot is Lemon Grab from Adventure Time (ClaudeLemon.png), screaming at a burning computer. That energy is the brand.

## Owner
B_Shappy (brschappert@gmail.com)

## Live site
https://claudedammit.com

## Hosting
- GitHub repo: https://github.com/brschappert/claudedammit
- Hosted on Vercel — auto-deploys on every push to main
- DNS managed via Namecheap pointing to Vercel

## Stack
- Plain HTML/CSS for now (no framework)
- Output directory: /public
- No build step required

## Structure
```
public/
  index.html      # main landing page
  ClaudeLemon.png # mascot image — keep this
```

## Style / tone
- Dark background (#0a0a0a), yellow accent (#f5d800), red accent (#ff4444)
- Monospace font (Courier New)
- Lowercase branding, irreverent, funny but technically impressive
- Think: satirical AI demos, comedy tools, things that make people laugh AND go "wait, that's actually powerful"

## Deploy workflow
```bash
# make changes
git add .
git commit -m "describe what changed"
git push
# Vercel auto-deploys in ~30 seconds
```
