# Robin Mugambi — Interactive Portfolio Website

> A personal portfolio website for Robin Mugambi, IT Support Professional based in Nairobi, Kenya. Built with vanilla HTML, CSS, and JavaScript — no frameworks, no backend required.

🔗 **Live Site:** [robin1610.github.io/robinmugambiportfolio](https://robin1610.github.io/robinmugambiportfolio/)

---

## Overview

This portfolio presents Robin's professional profile as an IT Support Professional transitioning into Management, Consulting & Operations. It is designed to be visually engaging, easy to navigate, and low-maintenance — combining a neon-accented pastel UI with interactive elements that reward curious visitors without overwhelming first-time viewers.

---

## Features

### 🎨 UI & Design
- Dual **light and dark mode** with a toggle switch in the navigation bar
- Custom pastel + neon colour palette with smooth CSS variable transitions
- Animated gradient orbs, floating particles, and a custom cursor
- **Switchable font pairs** — includes Syne/DM Sans, Playfair Display/Lato, Raleway/Open Sans, Josefin Sans/Nunito, and Cormorant Garamond/Inter
- Fully responsive layout tested across iOS, Android, and multiple browsers

### 🗂️ Sections
| Section | Description |
|---|---|
| **Hero** | Introduction, animated ticker bar, and quick-access CTA buttons |
| **Tools & Systems** | Flip cards revealing details about platforms and technologies used |
| **Career Timeline** | UFO-style floating bubbles — hover to reveal full role details |
| **Projects** | Z-pattern layout with robot companions — hover to reveal project stories |
| **Technical Skills** | Flip cards grouped by domain (Cloud, ITSM, Infrastructure, etc.) |
| **Certifications & Education** | Flip cards for all credentials and academic background |
| **Contact** | Functional contact form + email, LinkedIn, and CV download buttons |

### ⚙️ Functionality
- **Contact form** powered by [EmailJS](https://www.emailjs.com/) — works without a backend
- **CV download** — PDF served directly from the site, no external hosting needed
- **Email and LinkedIn buttons** link directly from the contact section
- All interactive elements (cards, bubbles, bots) use hover/click to reveal in-depth information, reducing scroll fatigue

### 🤖 Projects: Robot Companions
Each project card features a unique SVG robot icon that animates on hover and displays a tooltip with the full project story. Robots are selectable from a library via the Admin Panel.

---

## Admin Panel

The portfolio includes a custom-built **Admin Panel** (`portfolio-admin.html`) that allows full content management without touching any code. All changes are saved to `portfolio-data.json` and applied to the live site on reload.

### Admin Panel Capabilities
- **Appearance** — Switch font pairs and toggle section visibility
- **Section Intros** — Edit taglines and descriptions for each section
- **Hero Section** — Update badge text, subtitle, and intro prose
- **CV / Resume** — Upload or replace the downloadable CV (PDF)
- **Contact Form (EmailJS)** — Update Service ID, Template ID, and Public Key
- **Contact Details & Links** — Edit email, LinkedIn, and other contact links
- **Ticker Bar** — Add, edit, reorder, or remove scrolling ticker items
- **Tools & Systems** — Manage flip cards (icon, name, category, description, colour)
- **Career Timeline** — Add or edit career bubbles (role, company, dates, bullet points)
- **Projects** — Manage project cards and assign robot companions from the library
- **Technical Skills** — Edit skill groups and their associated tags
- **Certifications & Education** — Manage credential cards

The Admin Panel layout itself is drag-and-drop reorderable, and the panel order is saved automatically.

---

## File Structure

```
/
├── index.html              # Main portfolio page
├── portfolio-admin.html    # Admin Panel for content management
├── portfolio-data.json     # All portfolio content (edited via Admin Panel)
└── README.md
```

---

## Tech Stack

- **HTML5 / CSS3 / Vanilla JavaScript** — no frameworks or build tools
- **[EmailJS](https://www.emailjs.com/)** — contact form delivery without a backend
- **[Google Fonts](https://fonts.google.com/)** — multiple font pairs loaded on demand
- **GitHub Pages** — static site hosting

---

## Content Snapshot

**Tools & Platforms:** Microsoft 365, Microsoft Entra ID, Microsoft Intune, NinjaOne RMM, Freshservice, IT Glue, Google Workspace, Active Directory, Salesforce, Genetec Security, Microsoft Teams

**Skill Domains:** Microsoft Cloud & Endpoint · RMM & Patch Management · ITSM & Service Desk · Infrastructure & Security · Collaboration & Productivity · Operations & Management

**Certifications:** Kaseya Certified Technician · Cisco Operating Systems Support · Oracle AI Foundations Associate · ITIL V4 · Asana Workflow Specialist · ICT Competence Certificate · BSc Business Information Technology, and more

---

## Contact

- 📧 [rbnmugambi@gmail.com](mailto:rbnmugambi@gmail.com)
- 💼 [linkedin.com/in/rbnmugambi](https://linkedin.com/in/rbnmugambi)
- 🌍 Nairobi, Kenya

---

*Designed & built with ❤️ — © 2026 Robin Mugambi*
