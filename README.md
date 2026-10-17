# Alan Thomas — Personal Portfolio

My personal portfolio website: a single-page site introducing who I am, my skills, projects, education and how to reach me. Built as a clean, fast static site with no frameworks.

🔗 **Live sections:** About · Skills · Projects · Education & Certifications · Contact

## Features

- Sticky navigation with active-section highlighting and a mobile hamburger menu
- Hero section with name, tagline and call-to-action buttons
- About, Skills grid, and Projects cards (including "In progress" placeholders)
- Education timeline and certifications
- Contact section with email, LinkedIn and GitHub links
- Reveal-on-scroll animations (respect `prefers-reduced-motion`)
- Fully responsive — stacks cleanly on mobile
- Auto-updating footer year

## Tech Stack

- HTML5
- CSS3 (custom properties, Grid, Flexbox — no frameworks)
- Vanilla JavaScript (mobile menu, smooth scrolling, IntersectionObserver reveals)
- Inter font via Google Fonts

## How to Run

No build step needed. Open `index.html` in any modern browser, or serve the folder locally:

```bash
npx serve .
# or
python3 -m http.server 8000
```

## Project Structure

```
├── index.html   # Page structure: nav, hero, about, skills, projects, education, contact, footer
├── style.css    # Light theme with indigo accent, responsive layout, animations
├── script.js    # Mobile menu, smooth scroll, active nav highlighting, reveal animations
└── README.md
```

---

© Alan Thomas — BCA undergraduate, St. Berchmans College. Open to internships and learning opportunities.
