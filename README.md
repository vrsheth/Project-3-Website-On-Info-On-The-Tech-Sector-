A lightweight, student-friendly site that helps newcomers explore the tech world. It covers university pathways (Software Engineering, Computer Science, IT, CIS, Data Science, Computer Engineering), popular job roles, interview prep, and practical ways to level up (internships, projects, certifications, networking). Everything is built with semantic HTML, modern CSS, and a sprinkle of accessible, vanilla JavaScript—no frameworks required.

## Features

* **Clean navigation:** Sticky header with a mobile hamburger menu and keyboard-friendly submenu.
* **Accessible by default:** ARIA labels, focus states, reduced-motion handling, and semantic headings.
* **Readable, fast pages:** Zero build step. Loads quickly on low bandwidth.
* **Interactive bits:** Reveal-on-scroll animations and a modal for “Interview Tips.”
* **Actionable content:** Requirements, competitive averages (where relevant), and role expectations.

## Pages

* **Homepage:** Overview and entry points.
* **Uni Degrees:** Subpages for Software Engineering, Computer Science, IT, CIS, Data Science, and Computer Engineering with short program summaries and high-school requirement comparisons (Alberta-based).
* **Jobs in Tech:** Bite-size profiles for 20+ roles (frontend, backend, SRE, ML, security, PM, etc.).
* **Interview To-Do’s:** Before/During/After tips presented in clickable cards with a modal detail view.
* **Enhancement for Career:** Internships, GitHub hygiene, LinkedIn, personal projects, networking, and key certifications.

## Getting Started

1. **Clone or download** this repository.
2. Open `Index.html` in your browser. That’s it—no install steps.
3. For local development, use any static server (optional):

   ```bash
   # Example
   python3 -m http.server 3000
   # then open http://localhost:3000
   ```

## Project Structure

```
.
├── Index.html
├── UniDegrees.html (and degree subpages)
├── Jobs.html
├── JobInterviews.html
├── Enhance.html
└── images/          # Logos and illustrations
```

All CSS and JS are embedded per page to keep files portable. If you prefer, extract shared styles/scripts to `/assets/css` and `/assets/js`.

## Contributing

Issues and PRs are welcome! Please:

* Keep tone friendly and student-oriented.
* Favor semantic HTML and accessible interactions.
* Test keyboard navigation and reduced-motion behavior.
* Provide alt text for all images and logos.

## Roadmap

* Add search/filter for schools and job roles.
* Dark mode toggle with `prefers-color-scheme` support.
* Print-ready PDFs for checklists and interview prep.
* Lightweight build (optional) to minify assets.

## License

MIT—use, modify, and share freely. If you build on this, a star or mention is appreciated!
