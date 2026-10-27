<div align="center">

# Ayush Kumar — Developer Portfolio

**A fast, themeable React portfolio with a graphite look, live skill search, project showcase, certificate viewer and a built-in assistant chatbot.**

<p>
  <img src="https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React 18" />
  <img src="https://img.shields.io/badge/Vite-5-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite 5" />
  <img src="https://img.shields.io/badge/CSS3-Responsive-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/Deploy-Netlify%20%7C%20Vercel-00C7B7?style=for-the-badge&logo=netlify&logoColor=white" alt="Deploy" />
</p>

<p>
  <a href="https://github.com/vermaayush84300-alt"><img src="https://img.shields.io/badge/GitHub-vermaayush84300--alt-181717?style=flat-square&logo=github" alt="GitHub" /></a>
  <a href="https://www.linkedin.com/in/ayush-kumar-15a04a401/"><img src="https://img.shields.io/badge/LinkedIn-Ayush%20Kumar-0A66C2?style=flat-square&logo=linkedin" alt="LinkedIn" /></a>
  <a href="mailto:vermaayush84300@gmail.com"><img src="https://img.shields.io/badge/Email-vermaayush84300%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<img src="docs/screenshots/hero.png" alt="Portfolio hero section" width="100%" />

</div>

---

## Table of Contents

- [Highlights](#highlights)
- [Screenshots](#screenshots)
- [Tech Stack](#tech-stack)
- [Featured Projects](#featured-projects)
- [Themes](#themes)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Customising the Portfolio](#customising-the-portfolio)
- [Deployment](#deployment)
- [Contact](#contact)

---

## Highlights

| Feature | What it does |
| --- | --- |
| **Resume download** | One-click PDF download from the nav bar, mobile menu and hero section (`public/resume.pdf`). |
| **5 live colour themes** | Switch between Executive Gold, Corporate Sapphire, Capital Emerald, Campus Ruby and Pure Titanium without reloading. |
| **Animated hero** | Rotating role text, availability badge, tech chips and quick stats. |
| **Interactive skills** | Category tabs plus a live search box to filter skills instantly. |
| **Project showcase** | Filter pills, tech-stack tags and live demo links for each build. |
| **Certificate lightbox** | Click a certificate to open a full-size viewer (close with `Esc` or by clicking outside). |
| **Portfolio assistant** | Floating chatbot that answers questions about projects, skills, resume and contact details. |
| **Contact section** | Copy email to clipboard with toast feedback, plus GitHub and LinkedIn shortcuts. |
| **Polish** | Scroll progress bar, back-to-top button, reveal-on-scroll animations, fully responsive layout. |

---

## Screenshots

### Skills

<img src="docs/screenshots/skills.png" alt="Skills section" width="100%" />

### Projects

<img src="docs/screenshots/projects.png" alt="Projects section" width="100%" />

### Certificates

<img src="docs/screenshots/certificates.png" alt="Certificates section" width="100%" />

### Mobile

<div align="center">
  <img src="docs/screenshots/mobile.png" alt="Mobile view" width="280" />
</div>

---

## Tech Stack

### Languages and frameworks

<p>
  <img src="https://skillicons.dev/icons?i=js,html,css,react,tailwind,bootstrap,cpp,python&theme=dark" alt="Languages and frameworks" />
</p>

### Tools

<p>
  <img src="https://skillicons.dev/icons?i=vite,npm,git,github,vscode,postman,figma,netlify,vercel&theme=dark" alt="Tools" />
</p>

### Skills matrix

| Category | Technologies |
| --- | --- |
| **Languages** | JavaScript (ES6+), C++ (DSA), HTML5, CSS3, Python |
| **Frontend** | React.js, React Router, Redux Toolkit, Context API, Tailwind CSS, Bootstrap 5 |
| **Tools and workflow** | Git and GitHub, Vite and npm, VS Code, Chrome DevTools, Postman, Figma |
| **Core concepts** | REST API integration, component architecture, responsive and fluid UI, state management, web performance, semantic HTML and accessibility |

### This project uses

| Layer | Choice |
| --- | --- |
| Framework | React 18 |
| Build tool | Vite 5 |
| Icons | Lucide React |
| Fonts | Space Grotesk, Plus Jakarta Sans, JetBrains Mono |
| Styling | Plain CSS3 with CSS variables, Flexbox, Grid, glassmorphism and micro-animations |

---

## Featured Projects

| Project | Type | Stack | Live demo |
| --- | --- | --- | --- |
| **Krashi App** | AgriTech web platform | React.js, JavaScript, REST API, CSS3 | [Open](https://snazzy-entremet-031081.netlify.app/) |
| **AbTalks Redesign** | UI/UX redesign | React.js, Tailwind CSS, Vite, CSS3 | [Open](https://abtalks-redesign-9be6f9.netlify.app/) |
| **SmartFlex** | Smart web application | React.js, JavaScript, Tailwind CSS, Vite | [Open](https://smartflex-67cc24.netlify.app/) |

---

## Themes

| Theme | Accent | Best for |
| --- | --- | --- |
| Executive Gold (default) | ![gold](https://img.shields.io/badge/-%20%20%20-E0B25C?style=flat-square) `#E0B25C` | General and executive look |
| Corporate Sapphire | ![blue](https://img.shields.io/badge/-%20%20%20-5B8DEF?style=flat-square) `#5B8DEF` | IT services and product companies |
| Capital Emerald | ![green](https://img.shields.io/badge/-%20%20%20-2FCB9A?style=flat-square) `#2FCB9A` | Finance, consulting and analytics |
| Campus Ruby | ![red](https://img.shields.io/badge/-%20%20%20-F0566E?style=flat-square) `#F0566E` | College and placement portals |
| Pure Titanium | ![silver](https://img.shields.io/badge/-%20%20%20-E4E7EC?style=flat-square) `#E4E7EC` | Minimal monochrome |

---

## Getting Started

**Requirements:** Node.js 18 or newer and npm.

```bash
# 1. Install dependencies
npm install

# 2. Start the dev server
npm run dev
# open http://localhost:5173

# 3. Build for production
npm run build

# 4. Preview the production build
npm run preview
```

| Script | Description |
| --- | --- |
| `npm run dev` | Start Vite with hot reload |
| `npm run build` | Create an optimised bundle in `dist/` |
| `npm run preview` | Serve the production build locally |

---

## Project Structure

```text
portfolio-project/
├── public/
│   ├── resume.pdf          # Downloadable resume
│   └── graphite-bg.webp    # Background texture
├── src/
│   ├── App.jsx             # All sections, data, chatbot and styles
│   └── main.jsx            # React entry point
├── docs/screenshots/       # Images used in this README
├── index.html
├── vite.config.js
└── package.json
```

---

## Customising the Portfolio

All content lives in `src/App.jsx`.

| What to change | Where |
| --- | --- |
| Resume PDF | Replace `public/resume.pdf` (keep the same file name) |
| Skills | `SKILL_PANELS` array |
| Projects | `PROJECTS` array: name, summary, stack, `live` link |
| Certificates | `CERTIFICATES` array |
| Education | `EDUCATION` array |
| Hero roles | `ROLES` array |
| Colour themes | `THEMES` array |
| Social links | `SOCIALS` array |
| Nav menu | `NAV_LINKS` array |

---

## Deployment

| Platform | Steps |
| --- | --- |
| **Netlify** | Build command `npm run build`, publish directory `dist`. Or drag and drop the `dist/` folder. |
| **Vercel** | Import the repo, framework preset *Vite*, defaults work. |
| **GitHub Pages** | Build, then publish `dist/`. Set `base` in `vite.config.js` if the site lives in a sub-path. |

---

## Contact

<p>
  <a href="mailto:vermaayush84300@gmail.com"><img src="https://skillicons.dev/icons?i=gmail" height="36" alt="Gmail" /></a>
  <a href="https://github.com/vermaayush84300-alt"><img src="https://skillicons.dev/icons?i=github" height="36" alt="GitHub" /></a>
  <a href="https://www.linkedin.com/in/ayush-kumar-15a04a401/"><img src="https://skillicons.dev/icons?i=linkedin" height="36" alt="LinkedIn" /></a>
</p>

Ghaziabad, Uttar Pradesh, India · B.Tech CSE (AI and ML), ABES Engineering College · 2025 – 2029

<div align="center">

If you like this portfolio, consider giving the repo a star.

</div>
