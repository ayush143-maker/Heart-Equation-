# Heart-Equation-

An interactive mathematical-art page built around a heart curve. The top-level `index.html` contains the page and a parameter control for exploring changes to the visual result. The repository also includes the top-level audio file `musicplay.mp3` and a tap-to-play prompt. Browser audio policies may require interaction for playback.

## Preview locally

No package installation is required. Open `index.html` in a browser, or serve the repository directory:

```sh
python -m http.server 8000
```

Then visit http://localhost:8000. No deployment configuration is documented; serve the page and audio as static files with their relative paths intact.

## Personalizing the page

The page title is “Heart Equation”. To personalize its visible text or colors, make the related edits in `index.html` while preserving the heart-curve presentation and parameter control. If you change the equation or control, keep its mathematical labels consistent with the resulting visual output. The page links to Dancing Script and Cormorant Garamond through Google Fonts; keep those links aligned with any changes to the corresponding font styling.

The audio file is at the repository root as `musicplay.mp3`. Preserve that location or update the audio reference in `index.html` if you move or replace it.

## Manual review checklist

Use these actions as a review guide; they are not verified results.

- Open the known entry page, `index.html`, in a browser, or visit `http://localhost:8000` after starting the local server above.
- Try the parameter control and check that the heart-curve presentation and mathematical labels correspond to the selected parameter.
- Try the tap-to-play prompt. If audio does not start, interact with the page again; browser audio policies may require user interaction. Check that the `musicplay.mp3` reference matches the top-level file location.
- Inspect the page at a narrow phone-sized viewport and a wide desktop-sized viewport. Check that the parameter control, labels, and heart visual remain visible and usable.
- If you changed typography, check that the Google Fonts links and corresponding styles in `index.html` remain aligned.
