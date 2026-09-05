# pubp-6725 — WiCyS Login Page Recreation

A static, front-end recreation of the [Women in CyberSecurity (WiCyS) Member Portal login page](https://womenincybersecuritywicys.my.site.com/s/login/), built for coursework in **PUBP 6725**.

## What this is

A faithful HTML/CSS clone of the WiCyS Salesforce Experience Cloud login screen — matching layout, colors, typography, and assets. It is a **visual/front-end reproduction only**: the form is inert and does not send, store, or validate any credentials.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Page markup (logo, login form, links) |
| `styles.css` | All styling — brand purple `#812A90`, Lato type, translucent card, purple buttons |
| `assets/background.jpg` | The full scene (gradient, "Recruit / Retain / Advance", "Women in Cybersecurity", shield, photo) |
| `assets/wicys-logo.jpg` | WiCyS Member Portal logo |

## Design details (captured from the live page)

- **Font:** Lato (400 / 700 / 900), loaded from Google Fonts
- **Brand purple:** `#812A90`
- **Card:** 328px wide, `rgba(255,255,255,0.5)`, 4px radius
- **Inputs:** white pills, 2px radius, gray person/lock icons
- **Buttons:** solid purple, 2px radius, 700 weight, white text
- **Background:** one image sized `cover`, centered, with a purple fallback color

## Run locally

Because the page loads a stylesheet and images with relative paths, open it through a local web server rather than a `file://` URL:

```bash
python -m http.server 8777
```

Then visit <http://localhost:8777/index.html>.

## Note

This is an educational reproduction for a class assignment. The WiCyS name, logo, and imagery are the property of Women in CyberSecurity; they are used here only to study how the page is constructed.
