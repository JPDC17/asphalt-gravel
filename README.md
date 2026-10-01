# Asphalt & Gravel Tonnage Calculator

A single-page, phone-friendly calculator (`index.html`) for estimating material tonnage in metric tonnes.

- **Asphalt** — density 2.5 t/m³
- **Gravel** — density 2.2 t/m³
- Add as many measurements as you need; the total tonnage stays pinned to the bottom of the screen.
- Each measurement can be entered as **Length × Width × Depth**, **Area × Depth**, or a straight **Volume**.
- Metric and imperial units: m, cm, mm, ft, in, yd · m², ha, ft², yd², acre · m³, yd³, ft³.
- Every number needs its unit picked (nothing is assumed). The metric conversion shows under each entry, and the app flags values that look like the wrong unit (e.g. a 50 m deep pavement).
- A general calculator tab that can pull in the asphalt/gravel totals. Finished calculations are saved in a history list; tap one to reuse it, tap × to delete it, or clear them all.
- Entries are saved on the device, and "Copy summary" copies a formatted breakdown for texting or email.

Tonnes = volume (m³) × density.

## Using it on a phone

It's a plain HTML file with no build step. To host it for free with GitHub Pages:

1. In the repo on GitHub, go to **Settings → Pages**.
2. Under "Build and deployment", choose **Deploy from a branch**, pick the branch and `/ (root)`, and save.
3. Open the URL GitHub gives you on your phone. Use "Add to Home Screen" to keep it like an app.

## Versions

The version number is shown at the bottom of the page. Each update goes up by 0.01.

| Version | Changes |
|---|---|
| 1.01 | Cleaner "Copy summary" layout (date, per-measurement size/area/volume/weight, totals, note about incomplete entries). Calculator history is saved, and each entry can be deleted. Version number shown in the footer. |
