## GNAT (MD3) — Seth's Style for Jellyfin
![Homepage with Seth's Spotlight](https://raw.githubusercontent.com/JSethCreates/jellyfin-theme-sethstyle/main/screenshots/1homepage.png)
[![Watch the demo](https://raw.githubusercontent.com/JSethCreates/jellyfin-theme-sethstyle/main/screenshots/2movie.png)](https://vimeo.com/1095523100)

---
**God, Not Another Theme!**  
Originally built with Material Design 3 principles and root color definitions in 2023.  
Redesigned and released with Material 3 Expressive considerations in May 2025.
 
GNAT features a number of quality-of-life changes, with a focus on **media item pages**: prioritizing the **tagline and plot** while de-emphasizing technical data like codecs and stream selections, which are now moved toward the bottom of the page.

GNAT follows MD3 guidelines — primary action buttons are **visually distinct**, the **color system is fully swappable**, and **semantic styling** makes the entire layout more cohesive.  
The code is well commented, making it a solid starting point for anyone creating a new theme. All color targets are already mapped and unified.

---

## Installation

Paste the following into your Jellyfin dashboard:  
**Admin > Dashboard > General > Custom CSS**

```css
@import url("https://cdn.jsdelivr.net/gh/JSethCreates/jellyfin-theme-sethstyle@v1.0.0/sethstyle.css");
```

This theme was designed for use as a lean-back interface for JFWeb on a TV or Android-box, with remote control, at 1080p+.  
At resolutions < 1000 pixels wide, this theme will revert to standard JFWeb, with nominal color changes.

---

![Basic OSD](https://raw.githubusercontent.com/JSethCreates/jellyfin-theme-sethstyle/main/screenshots/3osd.png)
![Color Variant - Movie](https://raw.githubusercontent.com/JSethCreates/jellyfin-theme-sethstyle/main/screenshots/4movie.png)  

## Alternate Color Schemes

Use the code block below and modify the hex values to create your own colorscheme.

```css
@import url("https://cdn.jsdelivr.net/gh/JSethCreates/jellyfin-theme-sethstyle@v1.0.0/sethstyle.css");
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

🎨 [**Launch the MD3 Palette Generator Tool**](https://jsethcreates.github.io/web-tool-md3-palette-lab/)

---

![Series Page](https://raw.githubusercontent.com/JSethCreates/jellyfin-theme-sethstyle/main/screenshots/5series.png)  
![Season View](https://raw.githubusercontent.com/JSethCreates/jellyfin-theme-sethstyle/main/screenshots/6season.png)  
![Episode Detail](https://raw.githubusercontent.com/JSethCreates/jellyfin-theme-sethstyle/main/screenshots/7episode.png)

---

## License

With props to [@tedhinklater](https://github.com/tedhinklater) and [@alexyle](https://github.com/alexyle), whose Who's souls of **Finimalism** and **Glassmorphism** are probably still in here.. 

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

This project is licensed under the [MIT License](LICENSE).
