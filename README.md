# Terry Weber - Executive Personal Brand Website

Professional website for Terry Weber, healthcare executive and board director.

## Structure

```
terryweber-site/
├── index.html           # Home page
├── about.html           # About/Bio page  
├── track-record.html    # Career accomplishments
├── thought-leadership.html # Speaking, articles, insights
├── contact.html         # Contact form and info
├── css/
│   └── main.css         # All styles
├── img/                 # Images (headshots, etc.)
├── assets/              # Downloadable files (PDFs)
├── netlify.toml         # Netlify configuration
└── README.md
```

## Setup

1. Add images to `/img/`:
   - `terry-weber-hero.jpg` (400x500px recommended, professional headshot)
   - `terry-weber-about.jpg` (300x375px recommended)
   - `favicon.svg` (simple TW monogram or similar)

2. Add downloadable assets to `/assets/`:
   - `terry-weber-board-bio.pdf`
   - `terry-weber-media-kit.pdf` (bio, headshots, speaking topics)

3. Update content placeholders:
   - Replace `[bracketed content]` with actual information
   - Update metrics with real numbers
   - Add real testimonial quotes
   - Set up Formspree form ID in contact.html

4. Domain setup:
   - Register domain (terryweber.com or similar)
   - Connect to Netlify
   - Update Open Graph URL in index.html

## Deployment

This is a static HTML site. Deploy to Netlify:

1. Push to GitHub
2. Connect repo to Netlify
3. Deploy settings are in `netlify.toml`

## Design

- **Colors**: Navy (#1a2332), Gold (#b8860b), Cream (#faf8f5)
- **Fonts**: Libre Baskerville (display), Source Sans 3 (body)
- **Style**: Refined executive minimalism, sophisticated, gravitas

## Contact Form

Uses Formspree. Replace `YOUR_FORM_ID` in contact.html with actual Formspree endpoint after creating form at formspree.io.

---

Built by [Josh Pirtle / mygeekmmac](https://mygeekmac.com)
