# Personal Website

## Structure
- `index.html` — markup with Hero, About, Stack, Blog, Beyond, Contact sections
- `styles.css` — dark theme, mint/teal accent, responsive grid
- `script.js` — mobile nav toggle + fade-in animations

## How to use
1. Open `index.html` in a browser, or run a local server:
   ```bash
   cd ~/Desktop/personal-website
   python3 -m http.server 8000
   ```
   Then visit http://localhost:8000

2. Replace placeholders:
   - `Your Name`, `YN`, hero copy, eyebrow text
   - Portrait image URL (currently a placeholder)
   - About paragraphs and side cards (partners, career arc, achievement, hobbies)
   - Stack categories and certifications
   - Blog topics + Substack link
   - "Beyond" hobby cards and images
   - Email and LinkedIn in the Contact section

## Deploy
Drop the folder onto Netlify, Vercel, or GitHub Pages — no build step required.
