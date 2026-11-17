# Giuseppe Giorlando, personal site

Single-file site (`index.html`), no build step. The page opens with a scroll-driven scene: the surf photo grows from a card to full screen, then a waterline rises and the page goes underwater with the scuba photo. The water movement is drawn live with WebGL. Flat sea landscapes (headlands, pines, moving waves) are generated in the browser. Each visit gets its own seed and a palette that follows the visitor's hour.

Without WebGL, or with reduced motion turned on, the opening falls back to a static photo.

Assets live in `assets/`: `og.png` for social previews, the app icons, and the three photos (`dj.jpg`, `surf.jpg`, `scuba.jpg`). Open the file in a browser or serve the folder with any static server.
