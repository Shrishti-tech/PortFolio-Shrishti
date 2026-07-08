# Shrishti.dev Portfolio

Deployed : https://portfolio-shrishti-dev-uo9x.vercel.app/

Personal portfolio website for Shrishti Dixit, built as a static HTML, CSS, and JavaScript page. The main page is `index.html` and presents profile information, skills, experience, projects, certificates, achievements, and contact details.

## Preview

Open `index.html` in a browser to view the portfolio.

```text
index.html
```

No build step is required for the portfolio page itself.

## Features

- Responsive personal portfolio layout
- Hero section with typing animation
- About section with profile summary and quick stats
- Technical skills grid
- Experience timeline
- Featured projects section
- Certifications gallery
- Achievements section
- Contact section with social links
- Scroll-to-top button
- Smooth scrolling for in-page navigation

## Tech Stack

- HTML5
- CSS3
- JavaScript
- Google Fonts
- Font Awesome icons

## Important Files

| File | Purpose |
| --- | --- |
| `index.html` | Main portfolio page |
| `styles.css` | Styling, layout, responsiveness, and visual design |
| `app.js` | Typing animation, smooth scrolling, scroll-to-top button, and contact form alert |
| `photo_6190391077773185587_y.jpg` | Profile image |
| `bot.html` | Linked AI bot page |

## Page Sections

The portfolio includes these main sections:

- Home / Hero
- About
- Skills
- Experience
- Projects
- Certificates
- Achievements
- Contact

## Local Setup

1. Clone or download the project.
2. Keep `index.html`, `styles.css`, `app.js`, and the image assets in the same relative paths.
3. Open `index.html` directly in a browser.

Optional server-based run:

```bash
npm install
npm start
```

The Express server is mainly useful for backend/contact-form work. The current `p.html` contact form uses a JavaScript alert and does not submit to the backend API.

## Assets

This page depends on local image files such as:

- `photo_6190391077773185587_y.jpg`
- `riseee.jpg`
- `hero-image.jpg.png`
- `ChatGPT Image ... .png`
- `Screenshot ... .png`
- `assets/certificates/salesforce.jpg` is referenced by `p.html`; add this file or update the image path before deployment.

Make sure these files are included when moving or deploying the portfolio.

## Contact Links

- Email: `shrishtidixit7388@gmail.com`
- GitHub: `https://github.com/Shrishti-tech`
- LinkedIn: `https://linkedin.com/in/shrishti-dixit-7735382b3`

## Notes

- `p.html` links to `index.html` and `about.html` in the navbar, but those files may need to exist separately if the site is deployed as a multi-page project.
- Font Awesome and Google Fonts are loaded from CDN, so an internet connection is needed for those external resources.
