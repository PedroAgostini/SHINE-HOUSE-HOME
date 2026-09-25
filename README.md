<div align="center">
  <img src="favicon-512.png" width="112" alt="Shine House Home Service logo" />

  # Shine House Home Service

  **Reliable home cleaning in South Yarmouth and surrounding Cape Cod communities.**

  [![Website](https://img.shields.io/badge/Website-shinehouseservice.com-48503A?style=for-the-badge)](https://shinehouseservice.com/)
  [![Static Site](https://img.shields.io/badge/Build-Static_HTML-D0C8A8?style=for-the-badge&labelColor=363D2B)](#technology)
  [![Language](https://img.shields.io/badge/Language-English-C8C8A8?style=for-the-badge&labelColor=363D2B)](#pages)

  [Website](https://shinehouseservice.com/) · [Instagram](https://www.instagram.com/shinehouseservice/) · [Facebook](https://www.facebook.com/shinehousehs/)
</div>

---

## About

This repository contains the production-ready static website for **Shine House Home Service**, a locally owned cleaning company serving South Yarmouth, Cape Cod communities through Eastham, and Plymouth, Massachusetts.

The website is focused on clear local service information, trust, accessibility, fast loading, and easy quote requests on desktop and mobile.

## Pages

- Home page with services, results, reviews, service area, and quote form
- Regular Cleaning
- Deep Cleaning
- Move-In/Out Cleaning
- Post-Construction Cleaning
- Commercial Cleaning
- Airbnb Cleaning
- Privacy Policy
- Terms of Use
- Digital contact card at `/redirect/`
- Custom 404 page

## Features

- Responsive, mobile-first interface
- Accessible navigation, forms, focus states, and reduced-motion support
- Web3Forms quote request integration
- Layered anti-spam protection
- LocalBusiness, WebSite, Service, and Breadcrumb structured data
- Canonical URLs, Open Graph, Twitter cards, and semantic metadata
- `sitemap.xml`, `robots.txt`, `llms.txt`, `auth.md`, and web app manifest
- Apache redirects, security headers, compression, caching, and custom 404 rules
- Self-hosted variable fonts and optimized WebP images

## Technology

The deployed artifact is a fully static website:

```text
HTML5 · CSS · JavaScript · JSON-LD · WebP · WOFF2
```

No server runtime, database, or customer login is required. The contact form sends quote requests through Web3Forms.

## Repository structure

```text
├── index.html                  # Home page
├── */index.html                # Service and policy pages
├── css/styles.css              # Shared production stylesheet
├── js/main.js                  # Shared interactions and form behavior
├── assets/                     # Optimized images and brand assets
├── fonts/                      # Self-hosted variable fonts
├── .well-known/security.txt    # Security contact
├── .htaccess                   # Apache production rules
├── sitemap.xml                 # Search engine sitemap
├── robots.txt                  # Crawler directives
├── llms.txt                    # AI-readable business summary
└── site.webmanifest            # Web app metadata
```

## Deployment

### Hostinger or Apache hosting

Upload the repository contents directly to the domain's document root, usually `public_html`. Keep `.htaccess` and `.well-known/` in place.

### GitHub Pages

Configure Pages to deploy from the `main` branch and the repository root. The included `.nojekyll` file keeps the exported structure unchanged.

## Contact

- **Phone:** [(508) 360-0628](tel:+15083600628)
- **Email:** [shinehousehs@gmail.com](mailto:shinehousehs@gmail.com)
- **Service area:** South Yarmouth and surrounding Cape Cod communities

## Maintenance

This repository is a generated production artifact. Source changes should be made in the Astro project and exported again before publishing, so the HTML, CSS, JavaScript, metadata, and optimized assets remain synchronized.

---

<div align="center">
  <sub>Shine House Home Service · South Yarmouth, Massachusetts</sub><br />
  <sub>Designed and developed by <a href="https://github.com/PedroAgostini">Pedro Agostini</a></sub>
</div>
