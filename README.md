# Heart-Equation-

Heart-Equation- is an interactive mathematical-art page built around a heart curve. The top-level `index.html` contains the page and a parameter control for exploring changes to the visual result. The repository also includes `musicplay.mp3` at the root and a tap-to-play prompt. Browser audio policies may require interaction for playback.

## Preview locally

No package installation is required. Open `index.html` in a browser, or serve the repository directory:

```sh
python -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000). No build scripts or deployment configuration are listed.

## Editing the page

The page title is “Heart Equation”. Edit the related content in `index.html` to personalize visible text or colors while preserving the heart-curve presentation and parameter control. If changing the equation or control, keep the mathematical labels consistent with the resulting visual output.

The page requests Dancing Script and Cormorant Garamond from Google Fonts. These external requests require network access; keep the font links and corresponding styling aligned when changing typefaces.

The audio file is `musicplay.mp3` at the repository root. Keep it there or update the audio reference in `index.html` if it moves or is replaced.

## Repository map

- `index.html` — page entry point, heart curve, parameter control, and resource references.
- `musicplay.mp3` — audio asset.

When reviewing edits, try the parameter control and tap-to-play prompt. Check that labels match the selected parameter and that the heart visual, labels, and control remain visible at narrow and wide viewport sizes.