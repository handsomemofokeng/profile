# Interactive Mobile Developer Portfolio

This project is a single-page, interactive portfolio for **Handsome Mofokeng**, a Mobile Developer
specializing in Kotlin and Jetpack Compose. It is designed to be visually engaging, responsive,
and "ICT friendly" for both web viewing and printing.

## Features

* **Interactive Dashboard:** Visualizes key competencies and technical skills using `Chart.js`.
* **Responsive Design:** Built with Tailwind CSS to ensure a seamless experience across devices (
  desktop, tablet, mobile).
* **Print-Friendly:** Optimized CSS (`@media print`) for generating clean, high-contrast PDF resumes
  directly from the browser.
* **Dynamic Content:** Uses vanilla JavaScript to manage tab switching (Dashboard, Experience,
  Projects) and chart rendering.
* **Project Showcase:** Filters projects by technology stack (Kotlin, Java, Flutter).

## Tech Stack

* **HTML5:** Semantic markup for structure.
* **Tailwind CSS:** Utility-first CSS framework for styling and responsiveness.
* **JavaScript (ES6):** Handles interactivity, chart generation, and DOM manipulation.
* **Chart.js:** Renders the Competency Radar and Tech Stack Doughnut charts.

## Project Structure

```
profile/
├── index.html          # Main entry point containing HTML, CSS, and JS
├── .github/            # GitHub Actions workflows
│   └── workflows/
│       └── deploy.yml  # Workflow for deploying to GitHub Pages
└── README.md           # This file
```

## How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/handsomemofokeng/profile.git
   ```
2. Open `index.html` in your web browser.

## Deployment

This project is configured to deploy automatically to **GitHub Pages**.
The `.github/workflows/deploy.yml` workflow triggers on every push to the `main` branch.

## PDF Generation

To generate a PDF version of the portfolio:

1. Open the live site or local `index.html`.
2. Click the **"Download PDF"** button located below the header.
3. In the print dialog, ensure "Save as PDF" is selected.
    * *Tip:* Enable "Background graphics" in your print settings if colors appear washed out, though
      the print stylesheet is optimized for high contrast without them.

