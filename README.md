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

## Main Code Structure & Functionality

### 1. index.html (Markup & UI Layout)
The main structure consists of several semantic HTML5 sections:
- **#inicio (Hero):** The landing area featuring the main image of St. Joseph and navigation.
- **#oraciones (Fixed Prayers):** A two-column grid displaying the Preparatory Prayer and the Final Prayer that must be recited every day.
- **#dias (9-Day Devotion):** An interactive 2-column tabbed interface. The left column holds 9 buttons (one for each day), and the right column dynamically displays the text for the selected day.
- **#historia & #intenciones:** Informational sections with additional context and a layout for sending prayer intentions.

### 2. style.css (Styling & Animations)
- **Variables:** Utilizes CSS variables for consistent theming (typography, gold and earthy color tones).
- **Flexbox & Grid:** Relies on modern CSS layout techniques, particularly in the .novena-tabs-container which neatly divides the left navigation buttons from the right content pane.
- **Transitions:** Applies CSS transitions for a smooth fade-in effect when toggling between the days in the Novena section, ensuring stable and comfortable reading.

### 3. main.js (Interactivity)
- **Tabbed Interface Logic:** Uses Vanilla JavaScript to handle the "Camino de 9 Días" section. It listens for click events on the .novena-tab-btn buttons, hides inactive panes, and displays the chosen day's pane by toggling the .active class and checking the data-day attribute.
- **Scroll & Navigation:** Manages sticky header scrolling effects and mobile hamburger menu toggling.

## Pending Improvements

- Consider adding an audio player for guided audio prayers.
- Implement a daily progress tracker (Local Storage) so users can remember which day they are on.


