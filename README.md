[README.md](https://github.com/user-attachments/files/31597264/README.md)
# Tailwind Project

My first front-end design project — a landing page for a job/talent marketplace platform, built with **HTML** and **Tailwind CSS**.

🔗 **Live demo:** [cmidul.github.io/tailwind-project](https://cmidul.github.io/tailwind-project/)

## About

This is a static landing page that showcases a "find talent / find work" style platform. It was built as practice for learning Tailwind CSS utility classes and responsive layout — no backend, no JavaScript logic, just markup and styling.

## Sections

- **Header & Hero** — navbar, search bar (role + location), and call-to-action
- **Featured Talent Strip** — row of profile thumbnails
- **Job Categories** — Developer, UI Designer, Project Manager, Designer, Accountant, HR, Marketing
- **Talent Cards Grid** — rated profile cards with skill tags
- **Why Choose Us** — feature highlights (showcase work, resume builder, networking, active users)
- **How It Works** — 3-step signup flow
- **Portfolio Showcase** — talent portfolio carousel
- **Client Testimonial**
- **FAQ**
- **Newsletter / Join CTA**
- **Footer** — links and social icons

## Built With

- HTML5
- [Tailwind CSS](https://tailwindcss.com/) (via the [Tailwind CDN](https://tailwindcss.com/docs/installation/play-cdn) — `@tailwindcss/browser@4`)
- [GitHub Pages](https://pages.github.com/) for deployment

## Project Structure

```
tailwind-project/
├── index.html          # Main page markup + Tailwind utility classes
├── tailwind.config.js  # Tailwind configuration
├── images/             # SVG icons and illustrations
└── .github/workflows/  # GitHub Pages deployment workflow
```

## Running Locally

No build step is required since Tailwind is loaded via CDN.

1. Clone the repo:
   ```bash
   git clone https://github.com/cmidul/tailwind-project.git
   ```
2. Open `index.html` directly in your browser, or serve it locally:
   ```bash
   npx serve .
   ```

## Notes

- Text content is placeholder (Lorem ipsum) — this project is focused on layout and styling practice, not final copy.
- Deployed automatically via GitHub Pages / GitHub Actions.
- **Not responsive** — the layout uses fixed pixel widths and is designed for desktop screens only. It has not yet been adapted for tablet or mobile viewports.

## Status

This was a learning exercise to get comfortable with Tailwind's utility-first workflow (flexbox/grid layouts, gradients, rounded shapes, spacing). Planned next step: rebuild the layout using responsive utilities (`sm:`, `md:`, `lg:` breakpoints) and relative sizing instead of fixed widths, and replace placeholder text/images with real content.
