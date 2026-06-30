# AI Explorers

A landing page for **AI Explorers** — a 6-week summer program that teaches kids in grades 4–7 how AI actually works. Two age-based cohorts, small groups, taught by high schoolers, finishing with a family Demo Day.

🔗 **Live site:** _enable GitHub Pages (see below) and your URL will appear here_

## What's in this repo

```
AI-Explorers/
├── index.html     ← the entire website (one self-contained file)
└── README.md      ← you are here
```

The site is a single HTML file with all styles and scripts inline, so there's nothing to install or build. Just open `index.html` in any browser.

## Features

- Animated starfield hero with the program's key facts
- "Why it works" value section
- Two color-coded cohort cards (Explorers A: grades 4–5, Explorers B: grades 6–7)
- An interactive **6-week journey map** — toggle between the two cohort routes
- Demo Day showcase, plain pricing, scholarship + charity notes
- Fully responsive (desktop → mobile) and respects reduced-motion preferences

## Run it locally

Just double-click `index.html`, or from a terminal:

```bash
# optional: serve it on a local web server
python3 -m http.server 8000
# then open http://localhost:8000
```

## Publish it free with GitHub Pages

1. Go to this repo on GitHub → **Settings** → **Pages**
2. Under **Build and deployment**, set **Source** to *Deploy from a branch*
3. Choose branch **main** and folder **/ (root)**, then **Save**
4. Wait ~1 minute; your site goes live at
   `https://aaravs0202-lang.github.io/AI-Explorers/`

## Customizing

- **Sign-up button** → currently points to the Google interest form.
- **Enroll / contact button** → opens a pre-filled Gmail message to the founders.
- **Pricing** → edit the `#enroll` section in `index.html` ($200 early-bird / $250).
- **Week content** → edit the `ROUTES` object near the bottom of `index.html`.

---

Built by high schoolers, for curious kids. A portion of every tuition is donated to charity 💛
