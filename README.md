# GitHub Pages Bundle

## Overview
This repository contains a self-contained GitHub Pages site that generates and serves the requested files directly from the browser:
- ashravan.txt: An original, fan-made short story about Ashravan after Shai’s restoration, culminating in a dramatic decision. Includes a brief style disclaimer.
- dilemma.json: Two autonomous-vehicle ethical cases with boolean recommendations and reasoning.
- about.md: Three-word self-description.
- pelican.svg: A vector SVG of a pelican riding a bicycle.
- restaurant.json: A restaurant recommendation in Kolkata with coordinates and suggested dishes.
- prediction.json: A forward-looking estimate of the Fed Funds rate in December 2025.
- LICENSE: MIT License for the project.
- uid.txt: The provided UID, verbatim.

All files are generated on the client side via JavaScript and made available as links you can open or download.

## Setup
1. Create a new GitHub repository and add the two files from this project: index.html and README.md.
2. Commit and push to your main branch.
3. In your repository’s Settings → Pages:
   - Set Source to “Deploy from a branch”.
   - Select the branch (e.g., main) and the root directory, then Save.
4. After a minute, your site will be live at https://YOUR_USERNAME.github.io/YOUR_REPO/.

No build tools are required. Everything is inline and runs in the browser.

## Usage
- Visit the published GitHub Pages URL.
- The homepage lists each file with:
  - Open link to view in a new tab.
  - Download link to save the file locally.
  - Inline preview for textual files.
- The pelican.svg artwork is also displayed on the page for quick viewing.

If you need the files as physical artifacts in the repo instead of generated at runtime, use the “Download” links to save each file locally and commit them to your repository.

## Round 2 Improvements
N/A (This is Round 1).