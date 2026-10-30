# Heart-Equation-

An interactive mathematical-art page built around a heart curve. The top-level `index.html` contains the page and a parameter control for exploring changes to the visual result. The repository also includes the top-level audio file `musicplay.mp3` and a tap-to-play prompt. Browser audio policies may require interaction for playback.

## Preview locally

No package installation is required. Open `index.html` in a browser, or serve the repository directory:

```sh
python -m http.server 8000
```

Then visit http://localhost:8000. After changing the equation or controls, use the parameter control to review the result and keep mathematical labels and output in sync. If audio does not play, try the tap-to-play prompt. No deployment configuration is documented; serve the page and audio as static files with their relative paths intact.