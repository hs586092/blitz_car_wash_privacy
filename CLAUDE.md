# CLAUDE.md - AI Assistant Guide for Blitz Car Wash Privacy Policy

## Project Overview

This repository contains the privacy policy (개인정보처리방침) for the **Blitz car wash** mobile application. It is a static website consisting of a single HTML file with embedded CSS, written in Korean to comply with South Korean personal information protection regulations (「개인정보 보호법」).

- **Project Type**: Static website / Privacy policy page
- **Language**: Korean (한국어)
- **Effective Date**: January 20, 2026
- **Contact**: ke8945@gmail.com

## Repository Structure

```
blitz_car_wash_privacy/
├── CLAUDE.md       # This file - AI assistant guide
├── README.md       # Minimal project description
└── index.html      # Main privacy policy page (HTML + CSS)
```

## Technology Stack

| Technology | Details |
|------------|---------|
| HTML5 | Semantic markup with proper meta tags |
| CSS3 | Embedded styles with CSS custom properties (variables) |
| Google Fonts | Noto Sans KR (weights: 400, 500, 700) for Korean text |
| No JavaScript | Purely static content, no client-side scripting |
| No Build Tools | No compilation or bundling required |

## Key Files

### index.html

The main (and only) content file containing:
- Complete privacy policy in Korean (11 sections)
- Embedded responsive CSS with mobile-first design
- SEO-optimized meta tags
- Professional styling with CSS variables for theming

**CSS Color Scheme (defined in `:root`):**
```css
--primary-color: #1a365d    /* Dark blue */
--accent-color: #2b6cb0     /* Lighter blue */
--text-primary: #2d3748     /* Dark gray */
--text-secondary: #4a5568   /* Medium gray */
```

## Development Workflow

### No Build Process Required

This is a static site with no build dependencies. To work with it:

1. **View locally**: Open `index.html` directly in a browser
2. **Edit**: Modify `index.html` directly
3. **Deploy**: Upload to any static hosting service

### Testing Changes

- Open `index.html` in a browser
- Test responsive design by resizing the browser (breakpoint at 640px)
- Verify Korean text renders correctly with Noto Sans KR font

## Coding Conventions

### HTML

- Use semantic HTML5 elements (`<header>`, `<section>`, `<footer>`)
- Maintain proper heading hierarchy (h1 > h2 > h3)
- Keep all content in Korean unless otherwise specified
- Use proper HTML entities for Korean text

### CSS

- Use CSS custom properties defined in `:root` for consistent theming
- Mobile-responsive design with max-width container (800px)
- Maintain accessibility with proper color contrast
- Use transitions for interactive hover effects (0.2s ease)

### Content Guidelines

The privacy policy follows South Korean legal requirements:
- Reference 「개인정보 보호법」 (Personal Information Protection Act)
- Include all 11 required sections (제1조 through 제11조)
- Clearly state collected data items (currently: email only)
- Provide contact information for the privacy officer

## Deployment

This site can be deployed to any static hosting service:

- GitHub Pages
- Netlify
- Vercel
- AWS S3 + CloudFront
- Any standard web server (Apache, Nginx)

No environment variables or server-side configuration needed.

## Common Tasks

### Update Contact Information

Edit the following locations in `index.html`:
1. Line 370: Contact email in privacy officer section
2. Line 385: Footer contact email

### Update Effective Date

Edit the following locations in `index.html`:
1. Line 258: Header effective date (`시행일: 2026년 1월 20일`)
2. Line 379: Highlight box in section 11

### Add New Privacy Policy Sections

Follow the existing `<section>` pattern:
```html
<section>
    <h2>제N조 (Section Title in Korean)</h2>
    <p>Content here...</p>
</section>
```

### Modify Color Theme

Update CSS custom properties in the `:root` selector (lines 19-29 in `index.html`).

## Important Notes for AI Assistants

1. **Language**: All content should remain in Korean unless specifically asked otherwise
2. **Legal Compliance**: This document must comply with Korean privacy law - verify any content changes maintain legal requirements
3. **Minimal Changes**: Avoid unnecessary modifications; this is a legal document
4. **No External Dependencies**: Do not add JavaScript or external CSS libraries
5. **Responsive Design**: Maintain mobile responsiveness when making layout changes
6. **Accessibility**: Ensure color contrast and semantic HTML are preserved

## Git Workflow

- Main content is straightforward - make atomic commits for changes
- Test changes locally before committing
- Use clear, descriptive commit messages (preferably in English)

## Resources

- [Korean Personal Information Protection Act](https://www.law.go.kr/LSW/lsInfoP.do?lsiSeq=123210)
- [Google Fonts - Noto Sans KR](https://fonts.google.com/noto/specimen/Noto+Sans+KR)
