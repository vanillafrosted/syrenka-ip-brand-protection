# Syrenka IP & Brand Protection - English Sister Site

A completely independent English-language website for Syrenka IP & Brand Protection, featuring real strategies from 36+ lawsuits and 15+ years of experience.

## Overview

This is an **independent sister site** to the original Japanese Syrenka blog. It is:
- ✅ Completely separate GitHub repository
- ✅ Completely separate Vercel project
- ✅ English-language optimized for Google Search
- ✅ Syrenka brand identity preserved (colors, tone, character)
- ✅ Foundation phase (article placeholders for replacement later)

## Key Features

### Pages
- **Home** - Hero section with article links and experience highlights
- **About** - Mission, story, and 36+ lawsuits experience
- **Articles** - Article listing with 5 featured content pieces
- **Contact** - Contact form for inquiries
- **Privacy Policy** - Data handling practices
- **Disclaimer** - Legal disclaimer and educational notice

### SEO Configuration
- ✅ `<html lang="en">` on all pages
- ✅ English meta tags (title, description, keywords)
- ✅ OpenGraph tags (English)
- ✅ Twitter Card tags (English)
- ✅ hreflang tags linking Japanese version
- ✅ Structured data (JSON-LD)
- ✅ robots.txt with English site configuration
- ✅ sitemap.xml with all URLs and Japanese hreflang references

### Design
- **Color Palette**: Teal (#20B2AA) primary brand color
- **Responsive**: Mobile-first design, tested at 768px breakpoint
- **Accessible**: Semantic HTML, readable typography
- **Modern**: Smooth transitions, hover effects, gradient backgrounds

## Technology Stack

- **Framework**: Next.js 15
- **Styling**: CSS-in-JS (inline styles)
- **Static Content**: HTML files in `/public` directory
- **Deployment**: Vercel (standalone project)
- **Version Control**: Git/GitHub (standalone repository)

## Project Structure

```
syrenka-ip-brand-protection/
├── public/
│   ├── index.html          # Home page
│   ├── about.html          # About page
│   ├── articles.html       # Articles listing
│   ├── contact.html        # Contact form page
│   ├── privacy.html        # Privacy Policy
│   ├── disclaimer.html     # Disclaimer
│   ├── robots.txt          # SEO robots configuration
│   └── sitemap.xml         # SEO sitemap
├── package.json            # Project metadata
├── next.config.js          # Next.js configuration
├── .gitignore              # Git ignore rules
└── README.md               # This file
```

## Getting Started

### Local Development

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Visit http://localhost:3000
```

### Build for Production

```bash
npm run build
npm start
```

## Deployment

This project is deployed to a standalone Vercel project: `syrenka-ip-brand-protection`

### GitHub Setup
- Repository: `syrenka-ip-brand-protection`
- Branch: `main`
- Connected to Vercel for automatic deployment

### Vercel Setup
- Project: `syrenka-ip-brand-protection`
- Domain: `syrenka-ip-brand-protection.vercel.app`
- Auto-deployment: Enabled on push to main branch

## Important Notes

### Protection of Japanese Site
The original Japanese website (`https://syrenka-blog.vercel.app`) remains:
- ✅ Completely untouched
- ✅ Production website (live and stable)
- ✅ Read-only reference only (for this project)
- ✅ In separate repository and Vercel project

### This English Site Is
- ✅ Completely independent
- ✅ New GitHub repository
- ✅ New Vercel project
- ✅ Zero impact on Japanese site

## Future Improvements

After foundation is complete, planned enhancements:
- Real experience-based articles (replacing placeholders)
- English header image
- Typography refinement
- Mobile UX optimization
- SEO improvements based on analytics
- CTA optimization

## Article Placeholders

Current articles are placeholders:
1. Building Your Brand's Legal Foundation
2. Protecting Your Business Across Borders
3. When and How to Take Legal Action
4. Understanding Copyright and Intellectual Property
5. Trademark Registration and Protection Strategies

These will be replaced with real, detailed articles from Syrenka's experience base.

## SEO & Language

This site is optimized as an **English-language website** for Google Search:
- English language tag on all pages
- English metadata throughout
- hreflang links to Japanese version
- Separate sitemap configuration
- English robots.txt configuration

This ensures Google recognizes it as a distinct English website, not a translation.

## Legal Compliance

All pages include:
- Disclaimer (no legal advice claim)
- Privacy Policy (data handling)
- Contact information

## Support

For issues or questions, use the contact form at `/contact`

---

**Status**: Foundation Phase Complete ✅
**Last Updated**: July 2026
**Maintained by**: Syrenka Team
