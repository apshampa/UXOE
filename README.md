# Journey & Persona Builder

This local HTML application allows students and designers to quickly draft User Personas and map out User Journeys, then export them cleanly as high-resolution images. 

Everything runs in-browser without the need for a server or account.

## Features

- **Split Views:** Navigate easily between building a User Persona and building their Journey Map via the top tabs.
- **User Personas:** A structured, fill-in-the-blank template for defining a persona's goals, blockers, and emotions.
- **Action Bank:** A responsive sidebar for dumping unsorted action cards before organizing them.
- **Customizable Phases:** Drag and drop action cards into distinct columns, labeling both the name of the phase and its underlying *"Goal: What is the user trying to do?"*.
- **Clean Image Export:** Utilizes `html2canvas` to auto-format and download your current view as a polished `.png` image, stripping away unnecessary UI elements for a professional look.

## How to use

1. Open `https://apshampa.github.io/UXOE/` in any modern web browser (Chrome, Firefox, Safari).
2. Start on the **User Persona** tab to define who you are designing for. Click "Download Persona" when finished.
3. Switch to the **Journey Map** tab.
4. Type actions into the top text bar and hit **Add Action** to populate the Action Bank.
5. Hit **Add Phase** to create new columns for your journey.
6. Drag and drop the action cards from your bank into the appropriate phases.
7. Click **Download Map** to save your journey as an image.

## Customization

The script and styling are completely self-contained within `index.html`. 
- Fonts are imported via Google Fonts (`Inter`).
- Color palettes and themes can be customized by editing the CSS Variables block inside `:root` at the top of the file.
- The `html2canvas` dependency is loaded via CDN.
