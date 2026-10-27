# NeuroDose — ASM Calculator Prototype

This is an installable-web-app starter prototype for arithmetic calculations only.

## Files
- `index.html`: calculator interface and client-side calculation logic
- `manifest.webmanifest`: install metadata
- `sw.js`: offline caching service worker
- `icon.svg`: app icon

## Run locally
Opening `index.html` directly works for calculations. Service-worker/offline installation requires hosting over HTTPS or running a local web server.

## Deploy (simple route)
1. Create a GitHub repository and upload these files.
2. Enable GitHub Pages for the repository (Settings → Pages → deploy from the main branch/root), or deploy the folder to a static HTTPS host such as Vercel.
3. Open the deployed HTTPS URL in Safari on iPhone.
4. Tap Share → Add to Home Screen.

## Clinical safety
This version deliberately does NOT preload drug-specific dose recommendations. It calculates only from the clinician-entered dose and formulation concentration. Before clinical deployment, have a neurologist, pediatrician, clinical pharmacist and relevant governance team validate a source-cited, version-controlled drug database, age bands, maximum doses, renal/hepatic adjustments, interactions, emergency protocols and rounding rules. Do not use this prototype as the sole basis for prescribing.
