# AiOrbit Landing Page

A minimal, AdSense-compliant landing page for [aiorbit.info](https://aiorbit.info).

## Overview

This landing page:
- Funnels traffic to [skills.aiorbit.info](https://skills.aiorbit.info)
- Meets Google AdSense verification requirements
- Features clean, conversion-focused design

## Structure

```
.
├── index.html      # Main landing page
├── privacy.html    # Privacy Policy (AdSense requirement)
├── terms.html      # Terms of Service (AdSense requirement)
├── firebase.json   # Firebase Hosting configuration
└── README.md       # This file
```

## Development

Local testing:
```bash
npx serve .
```

## Deployment

Deployed to Firebase Hosting under project `aiorbit-info-firebase`.

```bash
firebase deploy --only hosting:aiorbit-info-firebase
```

## Design

- Dark theme with purple/indigo gradient accents
- Mobile responsive
- Linear/Vercel-inspired minimal aesthetic
- Fast load times (< 2s)

## SEO

- Complete meta tags (title, description, OG, Twitter)
- Semantic HTML structure
- Ready for Google Analytics and AdSense integration
