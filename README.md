# Sufiyan Budye — Portfolio Website

A single-file HTML portfolio built from Sufiyan's résumé, using a sticky-sidebar
template with dark/light mode, animated skill bars, and section-tracking navigation.

## Files
- `Sufiyan_Budye_Portfolio.html` — the complete portfolio (open directly in any browser)

## What's Inside
- **Sidebar**: name, title, current role (Full-Stack Developer at Telenor, Oslo),
  contact icons, and a live Oslo clock
- **Impact & Craft**: CMS-driven Telenor portal work, OIDC authentication systems,
  Azure cloud deployment, and reusable component/design-system work
- **Featured Work**: Telenor "Sikre" security portal, Enterprise Dashboard,
  Cloud-Based Management System
- **Top Skills**: Vue.js/Nuxt, JavaScript, .NET Core, OIDC, Azure, React, DevOps, MySQL
- **Career Trajectory**: Telenor (via Infosys) role, Azure certifications, education
- **Core Competencies**: 8-icon grid covering his technical scope

## Known Gaps to Fill In
- **GitHub URL**: the résumé only said "GitHub: link" with no actual address, so the
  GitHub icon in the sidebar currently points to `#`. Replace with the real profile URL.
- **Portrait image**: no photo was supplied, so the sidebar uses a text seal ("SB")
  instead of a photo. Swap in a real headshot by replacing the `.seal` block with an
  `<img>` tag (see the Goutham or Srilatha portfolio for the pattern).
- **Project screenshots**: the "Featured Work" cards use icon placeholders instead of
  real screenshots — add actual images if available.

## How to Customize
- Colors are defined as CSS variables in the Tailwind config block near the top of the
  `<head>` (`primary`, `primary-bright`, `sapphire`, `background-light`, `background-dark`).
- Skill percentages live in the `skills` array near the bottom of the file.
- Toggle dark/light mode using the floating button in the bottom-right corner.