# Bowerbird Landing Page

Landing page for [Bowerbird](https://bowerbird.ai) — an AI-powered real estate agent by Rockhood, Inc.

## Features

- **Hero with focused tab interaction** — click a category tab (First Home / Family / Investor / Seller) to dim the background and reveal four example questions; clicking a question fills the input.
- **Highlights carousel** — horizontally scrolling cards; click any card to smooth-scroll it to center.
- **How It Works** — three-step visual breakdown with illustrated icons.
- **Adaptive nav** — inverts to light-on-dark automatically whenever the nav sits over a dark section (focused hero or dark CTA band) and reverts on light content.
- **Invite gate** — circular send button inside the input scrolls directly to the access-request section.
- **Responsive** — desktop 4-column layouts collapse to 2×2 on mobile.

## Project Structure

```
bowerbird/
├── index.html              # Single-file landing page (HTML + inline CSS + inline JS)
├── assets/
│   └── images/
│       ├── hero-bg.jpg / hero-bg.png    # Hero background
│       ├── card-01.png … card-05.png    # Highlight carousel cards
│       ├── 1.png / 2.png / 3.png        # How It Works step illustrations
│       ├── Vector.svg … Vector-5.svg    # Hero speech-bubble / decorative icons
│       ├── ic_baseline-apple.svg        # Apple icon for Download App button
│       └── nvidia.png                   # NVIDIA Inception badge (footer)
└── README.md
```

## Development

No build step required. Open `index.html` directly in a browser:

```bash
open index.html
```

Or serve locally with Python:

```bash
python3 -m http.server 8080
# then visit http://localhost:8080
```

## Deployment

Hosted via GitHub Pages. Push to `main` branch to deploy.

Live URL: `https://wangyifan-design.github.io/bowerbird/`

## Credits

Designed & built by [Wang Yifan](https://wangyifan-design.github.io)
Product: Bowerbird / Rockhood Inc.
