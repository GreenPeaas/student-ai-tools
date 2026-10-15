# Student AI Tools

Four browser-based AI tools for college students, built with the Anthropic API.

## Tools
- **Flashcard Generator** — paste notes, get a full Q&A deck
- **Syllabus Extractor** — pull every deadline into a checkable list
- **Citation Formatter** — MLA, APA, Chicago from a URL or raw info
- **Explain It** — plain-English breakdown of any dense passage

## Setup
1. Clone or download this repo
2. Open `index.html` in a browser (or deploy to GitHub Pages / Netlify)
3. Get a free API key at [console.anthropic.com](https://console.anthropic.com)
4. Paste your key into any tool — it stays in your browser session only, never sent to any server

## Deploy to GitHub Pages
```bash
git init
git add .
git commit -m "initial commit"
gh repo create student-ai-tools --public --source=. --push
# Then enable GitHub Pages in repo Settings → Pages → Deploy from branch (main)
```

## Tech
- Pure HTML/CSS/JS — no build step, no dependencies, no backend
- All AI calls go directly from your browser to Anthropic's API
- Your API key is never stored on any server
