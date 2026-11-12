# UniCars navigation mockup

Interactive static prototype of the UniCars website navigation, footer and sample destination pages.

Preview: https://unicars-navigation-concept.avocadots-9013.chatgpt.site

## Run locally

No dependencies or build step are required. From the repository root run:

```sh
python3 -m http.server 8000 --directory dist
```

Then open http://localhost:8000.

## Files

- `dist/index.html`: page scaffold and dialogs.
- `dist/app.js`: navigation, sample destinations and local form demonstrations.
- `dist/style.css`: base layout.
- `dist/navigation.css`: responsive navigation styles and interaction states.
- `dist/assets/`: images and logo used by the prototype.
- `NAVIGATION-REVIEW.md`: journey rationale and production requirements.

## Current navigation

Explore vehicles, Support, For EVs, Available vehicles, Visit Us and Contact, with a global test-drive action. Vehicle menus include an explicit all-brands route. Group headings are prominent; highlighted links use a blue arrow inside a rounded white square. Search appears on the sample model listing, not in the navigation dropdown.

## Prototype scope

Content, model catalogue, stock and facility information are illustrative. Forms demonstrate interactions locally and do not send or persist requests. Four sample models demonstrate model discovery. Live inventory, complete model data, document downloads, bookings and EN/GR page equivalents require production integration.

This export includes the current static implementation and assets. Sites hosting metadata and repository credentials are excluded. GitHub uploads and Sites publishing are separate operations; automatic synchronisation is not configured.
