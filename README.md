# Portfolio — Sarah Yuzi Sandström

GRC · Customer Trust · Compliance Automation · Security Awareness

**Live site:** https://yuzi2021.github.io/portfolio-GRC/

A static portfolio presenting applied privacy, security-awareness and operational GRC work, built as plain HTML and CSS and deployed with GitHub Pages.

## Pages

- `/` — homepage
- `/projects/` — project index
- `/projects/grc-ops-lab/` — GRC Ops Lab
- `/projects/privacy-security-awareness/` — Privacy & Security Awareness
- `/projects/grc-change-monitor/` — GRC Change Monitor
- `/about/` — about
- `/cv/` — CV, with a downloadable PDF at `documents/Sarah_Sandstrom_GRC_CV.pdf`

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000. Serve it this way rather than opening the files directly, so the fonts and styles load.

## Structure

Plain HTML per route with a shared `styles.css` for base styling and responsive breakpoints. Internal links are relative, so the site works both at the GitHub Pages sub-path and under a custom domain.
