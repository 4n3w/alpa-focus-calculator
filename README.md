# Alpa Tools

Two single-page calculators for Alpa 12 technical cameras with Phase One and Hasselblad digital backs.

## Stitch Calculator (`index.html`)

Pick a back, lens, body, orientation, shifts and print resolution to see:

- stitched pixel dimensions, megapixels and aspect ratio
- print size in inches and centimetres
- full-frame equivalent focal length and angle of view
- a to-scale frame layout against the lens's image circle
- the same setup on every back, flagged when it passes Alpa's published shift limits or leaves the image circle

## Hyperfocal Table (`hyperfocal.html`)

Hyperfocal distance for every lens at every stop, sized to the selected back:

- sharpness standard by pixel pitch, the film-era diagonal ÷ 1500, or a custom circle of confusion
- near and far limits for any focus distance, with close-focus limits
- diffraction shading by stop, with a blur zone marked for visible light or 590, 720 and 850 nm infrared
- metric or imperial units, full or third stops

## Coverage

- **Bodies:** Alpa 12 TC, SWA, STC, PLUS, PANO
- **Lenses:** Rodenstock/Alpa HR Alpagon 23, 32, 40, 50, 70, 90, 138 and HR Alpar 180
- **Backs:** Phase One IQ3 50MP, IQ3 100MP, IQ4 150MP; Hasselblad CFV-50c, CFV II 50C, CFV 100C

Lens image circles, movement limits, effective focal lengths and close-focus distances are Alpa's published figures. Sensor figures are from the manufacturers' datasheets.

## Use

Open either page in a browser. There is no build step and no dependency beyond Google Fonts.

To host on GitHub Pages: Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main`, folder `/ (root)` → Save.

---

Not an official Alpa tool. Check your own setup before relying on these numbers.
