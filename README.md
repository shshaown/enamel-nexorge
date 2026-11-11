# Enamel — a Nexorge portfolio experience

An interactive dental-studio concept combining editorial design, a live 3D dental explorer, and smooth scroll storytelling.

## Live portfolio

https://shshaown.github.io/enamel-nexorge/

## Explore the experience

- Original procedural 3D model with 32 individually selectable teeth
- Distinct incisors, canines, premolars, and molars
- Full smile, upper jaw, lower jaw, and separated anatomy views
- Adjustable separation, optional roots, and gum/tongue visibility controls
- Click a tooth in the model or use the numbered tooth selector
- Mouse/touch rotation, keyboard controls, and animated open/close bite
- Four treatment previews, responsive layouts, scroll reveals, and image parallax
- Reduced-motion support and a demo consultation dialog

Enamel is a fictional clinic, created as a Nexorge portfolio project. The model is an artistic anatomy study, not a diagnostic model. The consultation flow does not save or send information or book real appointments.

## Run locally

Open `index.html` in a modern browser, or run:

```sh
python3 -m http.server 8080
```

Then open http://localhost:8080. No build or package installation is required.

## Files

`index.html` — page structure and controls  
`style.css` — responsive styling and motion  
`app.js` — procedural geometry, interaction, and scroll effects  
`assets/` — bundled Three.js library, photograph, favicon, and library license

## Credits

Design and experience: **Nexorge**. Reference inspiration: [Vitreonique by Sajjad Hossen Shaown](https://shshaown.github.io/vitreonique/index.html). Clinic photography: [Ozkan Guner on Unsplash](https://unsplash.com/photos/ein-zahnarztzimmer-mit-stuhl-und-monitor-Pc8lpKJwecM). See `credits.html` for details. Three.js is MIT licensed. Google Fonts are optionally loaded online with system-font fallbacks.
