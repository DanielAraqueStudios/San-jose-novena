# Novena a San José

## Project Overview
This project is a dedicated web application for the "Novena a San José" (Novena to Saint Joseph). It is designed to provide users with a clean, modern, and accessible interface to read, follow, and pray the 9-day devotion to St. Joseph.

The site is fully responsive and focuses on reading accessibility, peaceful aesthetics, and a clear daily structure for the nine days of prayer.

## Tech Stack
- HTML5
- CSS3 (Custom styles)
- Vanilla JavaScript
- Google Fonts (Cormorant Garamond & DM Sans)

## Folder Structure
```
/
├── index.html            # Main application entry point showing the Novena
├── style.css             # Main stylesheet (renamed from templatemo template)
├── main.js               # Interactivity and UI behaviors (renamed from templatemo template)
├── images/               # Directory containing all assets (updated to fit the new theme)
└── README.md             # This documentation file
```

## How to Install, Run, and Build
Since this is a static website:
1. **Clone or Download** the repository to your local machine.
2. **Open `index.html`** directly in any web browser to view the site, or use a tool like VS Code Live Server for local development.
3. No build tools (like Webpack or Vite) are required. The site is vanilla HTML/CSS/JS and is ready to be hosted as-is on platforms like GitHub Pages, Vercel, Netlify, or any traditional web host.

## Refactoring Decisions
- **Purged TemplateMo Branding:** All textual, visual, code-level, and metadata references to "Maison Dorée" and "TemplateMo 611" were completely removed.
- **Renamed Core Assets:** 
  - `templatemo-maison-style.css` -> `style.css`
  - `templatemo-maison-doree.js` -> `main.js`
  - `maison-templatemo.html` -> Deleted (redundant template file)
- **Content Overhaul:** Replaced jewelry-focused sections (Collections, Craftsmanship) with Novena-specific content (Days 1-9, Prayers, Intentions).
- **Exact Devocionario Integration:** Incorporated the exact traditional texts for the Preparatory Prayer, the 9 Daily Reflections, and the Final Prayer, directly sourced from official Novena resources.
- **Asset Cleanup:** Removed generic jewelry template images in the `/images/` folder to make room for religious/devotional imagery.
- **UI Tweaks:** Adapted the color palette and typography from a luxury brand feel to a more serene, peaceful, and traditionally Catholic aesthetic.

## Pending Improvements
- Add High-Quality images of St. Joseph for each day's meditation.
- Consider adding an audio player for guided audio prayers.
- Implement a daily progress tracker (Local Storage) so users can remember which day they are on.

