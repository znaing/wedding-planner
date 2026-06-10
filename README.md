<div align="center">
  
💍 Wedding Seating Planner


A beautiful, all-in-one seating chart tool for your wedding day.
Drag tables, import your guest list, shape your venue — then print a floor plan and entrance board.

</div>

✨ Features
🗺️ Interactive Floor Plan

Drag and drop round tables anywhere on the hall canvas
Zoom in/out with − and + controls, or hit Fit to see the whole venue at once
Tables display number, optional name, and live seat count (e.g. 8 / 10)

🏛️ Venue Shape Customization

Set your hall's width and depth to match the real proportions
Add an L-shaped corner cut-out — choose top-left, top-right, bottom-left, or bottom-right
Tables and fixtures are physically blocked from being dragged into the cut-out area

🪑 Fixtures & Assets
Stamp named elements onto the floor plan:
FixtureFixtureFixtureStageDance floorBuffet tableBarCake tableGift tableDJ boothPhoto boothEntrance / Exit

Resize any fixture by dragging its gold corner handle
Rename fixtures freely (e.g. "Buffet table" → "Dessert station")

👥 Guest List Management

Import from Excel or CSV — drop a .xlsx, .xls, or .csv file onto the panel

Auto-detects columns titled Name, Guest, First Name + Last Name, or falls back to the first non-empty cell per row
Skips duplicates on re-import


Type names manually (one per line) as an alternative
Unassigned section shows everyone awaiting a table, as clickable chips
Assigned section groups seated guests by their table with live counts — click any name to jump to their table, or click × to return them to the pool

🖨️ Print-Ready Outputs
Two print modes via the header buttons:
ButtonWhat you getPrint floor planScaled venue outline with table medallions and each guest's name positioned around their tablePrint entrance listAlphabetical A–Z guest list with table numbers, formatted in three columns — ready to frame at the hall entrance
💾 Save & Load

Save file — downloads your full plan as a .json file (tables, guests, fixtures, venue shape)
Load file — restores a previously saved plan, including venue dimensions and the corner cut-out


🚀 Getting Started
No installation required. It's a single HTML file.
Option 1 — Use the hosted version:
👉 https://znaing.github.io/wedding-planner
Option 2 — Run it locally:
bash# Clone the repo
git clone https://github.com/znaing/wedding-planner.git

# Open in your browser — no server needed
open wedding-planner/index.html

📋 Quick Workflow
1. Venue tab      →  Set hall size + corner cut-out (L-shape, etc.)
2. Venue tab      →  Add Stage, Buffet, Exit… drag them into place
3. Guest list tab →  Drop your .xlsx file  (or paste names)
4. Add Table ×N   →  One per round table in your hall
5. Click a table  →  Click guest chips to fill seats
6. Print          →  Floor plan for vendors · Entrance list for guests
7. Save file      →  Keep your .json safe between sessions

📱 Mobile Support
The app is fully responsive and touch-friendly:

Stacked layout on phones (floor plan on top, panel below)
Auto-fit zoom on load for small screens
Touch-sized controls throughout — no hover required


🛠️ Tech Stack
LayerDetailUIVanilla HTML + CSS + JavaScript — zero frameworksFontsCormorant Garamond (serif headings) + Jost (UI) via Google FontsExcel parsingSheetJS (xlsx) via CDN — handles .xlsx, .xls, .csvHostingGitHub PagesData persistenceLocal file save/load (.json) — no backend, no account needed

🗂️ File Structure
wedding-planner/
├── index.html      ← the entire app (HTML + CSS + JS, self-contained)
└── README.md

🖼️ Screenshots
<table>
  <tr>
    <td align="center"><b>Floor Plan View</b></td>
    <td align="center"><b>L-Shaped Venue</b></td>
  </tr>
  <tr>
    <td><img src="https://znaing.github.io/wedding-planner/screenshot-floor.png" alt="Floor plan" width="420"/></td>
    <td><img src="https://znaing.github.io/wedding-planner/screenshot-venue.png" alt="L-shaped venue" width="420"/></td>
  </tr>
  <tr>
    <td align="center"><b>Guest List Panel</b></td>
    <td align="center"><b>Entrance Print Sheet</b></td>
  </tr>
  <tr>
    <td><img src="https://znaing.github.io/wedding-planner/screenshot-guests.png" alt="Guest list" width="420"/></td>
    <td><img src="https://znaing.github.io/wedding-planner/screenshot-print.png" alt="Print list" width="420"/></td>
  </tr>
</table>

Screenshots will populate automatically once the app is deployed to GitHub Pages.


https://znaing.github.io/wedding-planner

🤝 Contributing
Pull requests are welcome! For significant changes, open an issue first to discuss what you'd like to change.

📄 License
MIT — free to use, fork, and modify.

<div align="center">
  Made with ♡ for the big day
</div>
