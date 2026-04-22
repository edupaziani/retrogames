RetroGames 🎮
A static website about classic video game consoles and their most iconic titles, built as a web development assignment (TT905 – Web Programming, UNICAMP FT, 2026).
About
RetroGames covers four classic consoles — PlayStation 2, PlayStation 3, Xbox 360, and Nintendo Wii — featuring three landmark games for each one. The site focuses on pure HTML5 and CSS3, with no frameworks or external dependencies beyond Google Fonts.
Pages
FileContentindex.htmlLanding page with animated hero, console card grid, and timelineps2.htmlPlayStation 2 — Crash Bandicoot, Sonic Heroes, Need for Speed: Most Wantedps3.htmlPlayStation 3 — Modern Warfare 2, Ratchet & Clank, Unchartedxbox.htmlXbox 360 — Minecraft, Just Dance 3, LEGO Batmanwii.htmlNintendo Wii — Wii Sports, Cloudy with a Chance of Meatballs, Mario Kart Wiicss/style.cssSingle shared stylesheet for all pages
Tech Stack

HTML5 — semantic tags (header, nav, section, footer), tables, anchor links
CSS3 — custom properties, CSS Grid, Flexbox, @keyframes animations, clamp(), backdrop-filter, media queries
JavaScript — minimal vanilla JS for the mobile hamburger menu toggle

Features

Responsive layout for both desktop and mobile (breakpoints at 768px and 480px)
Per-console accent color via a single --accent CSS variable override
CRT scanline effect on the hero section
Sticky header with glass-blur effect
External links to YouTube gameplay videos for each game

Structure
retrogames/
├── index.html
├── ps2.html
├── ps3.html
├── xbox.html
├── wii.html
├── css/
│   └── style.css
└── relatorio.pdf
Course Info
Discipline: TT905 – Programação Web
Institution: Universidade Estadual de Campinas — Faculdade de Tecnologia
Semester: 1st semester, 2026
Professor: Prof. Dr. Celmar Guimarães da Silva
