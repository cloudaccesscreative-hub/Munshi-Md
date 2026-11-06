# Munshi Md | Video Editing Portfolio

Open `index.html` in a browser. No build step needed.

## Fonts
`fonts/` contains Nexa **trial** fonts (Fontfabric), converted to WOFF2:
Nexa Regular, Regular Italic, Light Italic, Nexa Text Bold and Black Italic.

Trial fonts disable punctuation, symbols and accented letters, so these files keep only the
characters that work. Anything else (' + & → © ā …) falls back to Helvetica/Arial.

When you buy the full Nexa licence, replace these files with the full versions using the same
names, and add `Nexa-Light.woff2`, `Nexa-Bold.woff2` and `Nexa-Heavy.woff2` for the full weight range.

## Add a new reel
1. Put the video (`my-reel.mp4`) and a still image (`my-reel.jpg`) in `assets/`.
2. In `index.html`, copy one `<button class="reel-card"> ... </button>` block, paste it below and change the file names, title and text.

## Add your photo
Put `portrait.jpg` in `assets/`, then in `index.html` replace `<span class="monogram">MM</span>` with
`<img src="assets/portrait.jpg" alt="Munshi Md Mohaimenul Huda">`.

## Contact form
The form opens the visitor's email app with a message addressed to mohaimunshi2005@gmail.com.
There is no phone number or pricing anywhere on the site.
