# Portfolio — Sarah Yuzi Sandström

HR Technology & Systems · Data Protection · GRC · Automation

**Live site:** https://yuzi2021.github.io/portfolio-HR-tech-admin/

A static portfolio presenting HR technology and systems work alongside applied data-protection and GRC projects, built as plain HTML and CSS and deployed with GitHub Pages.

## Pages

- `/` — homepage
- `/projects/` — project index
- `/projects/privacy-security-awareness/` — Privacy & Security Awareness case study
- `/about/` — about
- `/cv/` — CV

The CV PDF has been removed pending an updated version. To restore the download button, drop the new PDF into `documents/` and uncomment the block above the contact list in `cv/index.html`, adjusting the filename to match.

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000. Serve it this way rather than opening the files directly, so the fonts and styles load.

## Structure

Plain HTML per route with a shared `styles.css` for base styling and responsive breakpoints. Internal links are relative, so the site works both at the GitHub Pages sub-path and under a custom domain.

Note that `styles.css` targets the inline `style` strings in the markup (for example `[style*="300px minmax(0, 1fr)"]` and `[style*="padding: 0 80px 128px"]`) to fold the desktop layout down for tablet and mobile. New markup should reuse those exact inline strings, or it will not respond at the breakpoints.
