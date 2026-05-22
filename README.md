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


## Email update
- Updated the booking/contact email to `rbtechhelper@outlook.com`
- Updated the mailto link to use the new email address


## Support email update
- Updated the booking/contact email to `support@ranchobernardotechhelper.com`
- Updated the mailto link to use the new email address


## Intro icon removal
- Removed the icon next to `Technology should not feel stressful.`


## Schedule Tech Help link update
- Added `schedule-tech-help.html` using the Zoho web-to-case embedded form code.
- Added a `Schedule Tech Help` link to the booking/contact section.
- Updated the booking headline language.


## Update — Experience & Credentials section
- Removed "want someone to come to your home" bullet from "Who This Service Is For"
- Removed the "Flat-Rate Setup Services" card from the Simple Pricing grid
- Removed the entire "Flat-Rate Services" section (full service menu)
- Added new "Experience & Credentials" section featuring:
  - About photo (`about-photo.png`)
  - 5+ years of IT support across higher education, mortgage and lending, and biotech
  - Explanation of CompTIA A+ certification
  - Redacted CompTIA A+ certificate image (`comptia-cert.png`)
- Updated booking/contact email to `support@rbtechhelp.com`
