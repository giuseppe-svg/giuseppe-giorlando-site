# Giuseppe Giorlando, personal site

Single-file site (`index.html`), no build step. The page opens with a scroll-driven scene: the DJ photo grows from a brushed card to full screen, then six strokes of colour sweep across and leave the scuba photo behind. The strokes and the water movement are drawn live with WebGL. Flat sea landscapes (headlands, pines, moving waves) are generated in the browser. Each visit gets its own seed and a palette that follows the visitor's hour.

Without WebGL, or with reduced motion turned on, the opening falls back to a static photo.

Assets live in `assets/`: `og.png` for social previews, the app icons, and the photos (`dj.jpg`, its cropped copy `dj-hero.jpg` for the opening, `scuba.jpg`; `surf.jpg` is no longer used on the page). Open the file in a browser or serve the folder with any static server.
