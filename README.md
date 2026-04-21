# Rancho Bernardo Tech Helper Website v2

## Main edits in this version
- The bottom section is now **Book an In-Home Visit**
- The **Schedule Now** button now scrolls to that booking section
- The service area text has been updated
- More visual flow was added between sections with soft background color changes
- Simple built-in SVG icons were added for:
  - Technology should not feel stressful
  - Who This Service Is For
  - Simple Pricing
  - Proudly Serving
- Photo areas now include a fallback placeholder if an image file is missing

## Important
If your live site is not showing photos, make sure these files are actually in your GitHub repo:
- `assets/logo.png`
- `assets/hero-tech-setup.png`
- `assets/service-visit.png`

## Files
- `index.html`
- `styles.css`
- `script.js`
- `README.md`
- `assets/logo.png`
- `assets/hero-tech-setup.png`
- `assets/service-visit.png`


## Image fix
The live site was failing because the HTML was pointing to `assets/...` while the GitHub repository had the image files in the repo root. This fixed version points to:
- `logo.png`
- `hero-tech-setup.png`
- `service-visit.png`


## Refresh edits
- Enlarged the header logo for better visibility
- Added a larger logo at the start of the hero copy
- Replaced the intro icon with a meditative pose icon styled to match the site palette
- Added the logo on both sides of the Proudly Serving section
- Removed the small green eyebrow labels that were repeating section titles
