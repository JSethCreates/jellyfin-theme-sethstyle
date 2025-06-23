## GNAT (MD3) — Seth's Style for Jellyfin
![Homepage with Seth's Spotlight](https://raw.githubusercontent.com/JSethCreates/jellyfin-theme-sethstyle/main/screenshots/1homepage.png)
![Media Item Page](https://raw.githubusercontent.com/JSethCreates/jellyfin-theme-sethstyle/main/screenshots/2movie.png)
▶️ [Watch the Demo](https://vimeo.com/1095523100)
---
**God, Not Another Theme!**  
Originally built with Material Design 3 principles and root color definitions in 2023.  
Redesigned and released with Material 3 Expressive considerations in May 2025 for jellyfin v10.10.x.
 
GNAT features a number of quality-of-life changes, with a focus on media item pages: -Fixing the primary action panel, and flex-wraping secondary info containers,
-Prioritizing the cinematic elements (logo, tagline, plot, cast) while shifting more technical buckets like codecs and stream selections lower on the page.
-Custom slider thumb designs on WebKit/Firefox, fixed-position progress bar to prevent bouncing, OSD time text styling and placement
-Replacing header Text-button tabs with Material Icons (or Emoji example coded)

GNAT follows MD3 guidelines -primary action buttons are **visually distinct**, the **color system is fully swappable**, and **semantic styling** makes the entire layout more cohesive.
-MD3 Subtle growth, shadow, and background color transitions, Rounded corners everywhere, Typography & Headings unified, -Styles buttons, FABs, progress indicators, list-item hovers, 
checkboxes, sliders, spinners, and card placeholders all styled within the 9 color MD3 palette, including hover/focus tints and mix-in backgrounds. 

I tried to make it a solid starting point for anyone creating a new theme. All color targets are already mapped and unified in the initial sections of the CSS.
🎓 [Learn more about MD3](https://material-foundation.github.io/material-theme-builder/)

---
## Installation

Paste the following into your Jellyfin dashboard:  
**Admin > Dashboard > General > Custom CSS**

```css
@import url("https://cdn.jsdelivr.net/gh/JSethCreates/jellyfin-theme-sethstyle@v5.2.7/jellyfin-theme-sethstyle.css");
```

**Note:** This theme was designed for use as a lean-back interface for JFWeb on a TV or Android-box, with remote control, at 1080p+.  
At resolutions < 1000 pixels wide, this theme will revert to standard JFWeb, with nominal color changes.

![Basic OSD](https://raw.githubusercontent.com/JSethCreates/jellyfin-theme-sethstyle/main/screenshots/3osd.png)

---

## Alternate Color Schemes
![Color Variant - Movie](https://raw.githubusercontent.com/JSethCreates/jellyfin-theme-sethstyle/main/screenshots/4movie.png)  
Use the code block below and modify the hex values to create your own colorscheme.

```css
@import url("https://cdn.jsdelivr.net/gh/JSethCreates/jellyfin-theme-sethstyle@v5.2.7/jellyfin-theme-sethstyle.css");
:root {
  --md-sys-color-primary:               #81d3df !important;
  --md-sys-color-secondary:             #b1cbcf !important;
  --md-sys-color-tertiary:              #b9c6ea !important;

  --md-sys-color-on-primary:            #00363c !important;
  --md-sys-color-primary-container:     #004f57 !important;
  --md-sys-color-on-primary-container:  #9df0fc !important;

  --md-sys-color-surface:               #0e1415 !important;
  --md-sys-color-on-surface:            #dee4e4 !important;
  --md-sys-color-outline:               #899294 !important;
}

```
> “Yo dog, Google heard you like themes, so they put a scheme on your theme on your style on your media player..”

Material 3 Expressive promotes more vibrant palettes and you can test, request, adjust, copy and paste MD3 schemes with this tool here:

🎨 [**Launch Seth's MD3 Palette Generator Tool**](https://jsethcreates.github.io/web-tool-md3-palette-lab/)

---

![Series Page](https://raw.githubusercontent.com/JSethCreates/jellyfin-theme-sethstyle/main/screenshots/5series.png)  
![Season View](https://raw.githubusercontent.com/JSethCreates/jellyfin-theme-sethstyle/main/screenshots/6season.png)  
![Episode Detail](https://raw.githubusercontent.com/JSethCreates/jellyfin-theme-sethstyle/main/screenshots/7episode.png)

---

## License

With props to [@tedhinklater](https://github.com/tedhinklater) and [@alexyle](https://github.com/alexyle), who's souls of **Finimalism** and **Glassmorphism** are probably still in here.. 

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

This project is licensed under the [MIT License](LICENSE).
