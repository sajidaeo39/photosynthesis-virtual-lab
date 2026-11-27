# Photosynthesis Virtual Lab

A self-contained, responsive Urdu interactive science activity for classes 4–8.

## Files
- `index.html` — complete application; CSS and JavaScript are included. No build tools or external libraries are required.

## Run locally
Open `index.html` in a modern browser. Internet is not required for the simulation. Urdu text-to-speech depends on the browser/device having an Urdu voice installed; if unavailable, all explanations remain visible.

## Publish with GitHub Pages
1. Create a GitHub repository, for example `photosynthesis-virtual-lab`.
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then press **Save**.
6. Wait for the deployment and open the URL shown in the Pages section.

## Teaching notes
- The experiment uses a simplified limiting-factor model: the lowest of light, CO₂ and water levels determines the displayed relative rate.
- This is an illustrative classroom model, not a calibrated biological prediction.
- Turning light off stops the modeled light-dependent photosynthesis; it does not imply that a plant dies immediately. Respiration continues.
- Browser speech synthesis is used for Urdu narration where a suitable voice is installed.
