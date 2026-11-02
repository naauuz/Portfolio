# Nada Alzahrani — Portfolio

A responsive, single-page portfolio for Nada Alzahrani. Built with plain HTML, CSS, and JavaScript; no build step or dependencies.

## Preview locally

Open `index.html` in a browser. All assets are included.

## Publish on GitHub Pages

1. Create a **public** repository named `portfolio` at https://github.com/new.
2. Upload the **contents** of this folder directly into the repository root (so `index.html` is at the top level), and commit.
3. Open **Settings → Pages → Build and deployment → Deploy from a branch**.
4. Select **main**, folder **/(root)**, then **Save**.
5. The intended site address is `https://naauuz.github.io/portfolio/` after GitHub finishes deploying.

## Easy edits

- **Name, biography, experience, education, certifications and project descriptions:** `index.html`.
- **Colors, layout, font size:** `style.css` (look for the `:root` palette).
- **Mobile menu and active navigation:** `script.js`.
- **Project artwork:** `assets/projects/*.svg`.
- **Resume download:** replace `assets/Nada_Alzahrani_CV.pdf` with an updated PDF using the same filename.
- **Projects:** edit each `<article class="project-card">` in `index.html`. Use real GitHub repository URLs, rather than sample links.

## Source notes and accuracy

Experience, education, contact email, skills and certifications were adapted from the provided CV. The four featured projects link to public repositories verified at github.com/naauuz as of November 2, 2026. Descriptions are intentionally conservative and do not imply unverified performance metrics. Arabic OCR, Arabic chatbot and the cancer-classification graduation project are mentioned in the CV but are not falsely presented as linked GitHub repositories.

No LinkedIn profile URL was confirmed, so the site does not contain an invented LinkedIn link. The visualization is an illustration, not a claim of actual dashboard metrics.

## Security / accessibility

No third-party scripts or trackers, no external fonts. Navigation works on mobile, keyboard focus is visible, project graphics have alt text, and reduced-motion preferences are respected.
