# Sirius Platforms — Landing Page

Marketing landing page for **Sirius Platforms, Inc.**, a Delaware-based software
development company focused on the proptech sector.

> _"Software that powers the future of real estate."_

---

## 1. Purpose

A single, professional landing page that presents Sirius Platforms as a real,
operating software company. The primary goal is **credibility**: it should give
business reviewers (e.g. **Dun & Bradstreet / DUNS number** verification),
partners, and prospective clients a clear, trustworthy picture of who we are,
what we build, and how to reach us.

This is intentionally **simple** — one page, fast, no backend, no forms wired to
servers. Just a clean, premium presence on the web.

## 2. Company information

| Field | Value |
|-------|-------|
| Legal name | Sirius Platforms, Inc. |
| Sector | Software development / Proptech |
| Address | 800 North King Street, St 304 #3623, Wilmington, DE 19801, US |
| Email | siriusplatforms@gmail.com |
| Language | English |

> Phone number and founding year are intentionally omitted for now and can be
> added later without changing the structure.

## 3. What we do

Sirius Platforms is a software development company that delivers custom projects
across multiple domains, with a strong focus on **proptech**. We build and
operate our own products in addition to client work:

- **Envivienda.com — Property Portal:** a real estate portal where end clients
  can search, explore and find properties.
- **Real Estate CRM:** a CRM tailored for real estate agencies to manage
  listings, leads and clients.
- **Custom software development:** scalable, cloud-native solutions built for
  other businesses.

## 4. Technology we work with

Showcased on the site to convey engineering maturity:

- **AWS** — cloud infrastructure
- **Flutter** — cross-platform mobile/web apps
- **Node.js** — backend services
- **Microservices** — modular, independently deployable services
- **Scalable architectures** — built to grow

## 5. Visual identity

**Cosmic / dark** theme, inspired by Sirius — the brightest star in the night sky.

- Deep dark-navy / near-black backgrounds.
- Bright blue / cyan accents for highlights, buttons and links.
- Subtle starfield / glow details for a premium, technological feel.
- Clean, modern typography with generous spacing.
- Fully responsive (mobile-first).

## 6. Page structure (single page, scroll)

1. **Hero** — company name, tagline, short subtitle, primary contact CTA.
2. **About / Who we are** — short statement about Sirius Platforms.
3. **Products** — Envivienda.com (Property Portal) + Real Estate CRM.
4. **Services / Capabilities** — custom software development beyond our own products.
5. **Technology** — AWS, Flutter, Node.js, microservices, scalable architectures.
6. **Contact / Footer** — Delaware address, email, copyright.

A lightweight top navigation links to these sections.

## 7. Website tech stack

- **[Astro](https://astro.build/)** — static site generation, ships minimal JS.
- **Custom CSS** with design tokens (CSS custom properties) — no heavy UI
  framework, to keep the look distinctive and the site fast.
- No backend; contact is a `mailto:` link to the company email.

### Planned project structure

```
sirius-platforms-landing-page/
├── public/                 # static assets (favicon, og-image)
├── src/
│   ├── components/         # Nav, Hero, About, Products, Services, Technology, Contact, Footer
│   ├── layouts/
│   │   └── BaseLayout.astro
│   ├── styles/
│   │   └── global.css      # design tokens + base styles
│   └── pages/
│       └── index.astro     # assembles all sections
├── astro.config.mjs
├── package.json
└── README.md
```

## 8. Getting started

```bash
# install dependencies
npm install

# start the dev server (http://localhost:4321)
npm run dev

# build the production site into ./dist
npm run build

# preview the production build locally
npm run preview
```

## 9. Deployment

The output is a fully static site (`./dist`) and can be hosted anywhere. Good
options:

- **AWS S3 + CloudFront** (consistent with our own AWS stack) — recommended.
- Vercel / Netlify / Cloudflare Pages / GitHub Pages.

---

© Sirius Platforms, Inc. — Wilmington, Delaware, USA.
