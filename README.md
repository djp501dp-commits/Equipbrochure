# Biorenewables Development Centre - Facilities & Equipment Brochure

This repository contains the interactive, single-page web brochure for the Biorenewables Development Centre (BDC).

## Features
- **Interactive Equipment Explorer**: Search and filter through BDC's extensive equipment list.
- **Responsive Design**: Works on desktop and mobile devices.
- **Print-Ready**: Cleanly prints to PDF from the browser (hiding navigation and expanding details).
- **No Dependencies**: Built with vanilla HTML, CSS, and JavaScript.

## How to use locally
1. Clone the repository.
2. Open `index.html` directly in any modern web browser. No build system or local server is strictly required, although you can use one (like `python3 -m http.server`) if you prefer.
3. If images become available, place them in the `assets/equipment/` folder ensuring the filenames match those referenced in the `equipmentData` array inside `index.html`.

## Publishing via GitHub Pages
1. Go to your repository's **Settings** tab.
2. On the left sidebar, click on **Pages**.
3. Under the "Build and deployment" section, select **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder.
5. Click **Save**.
6. GitHub will process the site, and within a few minutes, the generated URL will be displayed at the top of the Pages settings page. Share this link publicly!