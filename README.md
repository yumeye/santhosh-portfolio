# Santhosh Kumar Kuppan — Portfolio

Static single-page site. No build step, no dependencies.

## Run locally
```
cd santhosh-portfolio
python3 -m http.server 8080
```
Open http://localhost:8080

## Deploy to Vercel
1. Push this folder to a GitHub repo (or drag-and-drop the folder at vercel.com/new).
2. In Vercel, "Framework Preset" → **Other** (static site). No build command, no output directory override needed — it serves `index.html` as-is.
3. Deploy.

## Updating content later
- Copy: edit directly in `index.html` (each project "chapter" is a clearly labelled block).
- Images: drop new files in `images/`, update the `src` in `index.html`. Keep images under ~300KB (resize to ~1600px wide max) so the site stays fast.
- Resume: replace `resume/Santhosh_Kumar_Kuppan_Resume.pdf` with an updated file of the same name, or update the filename in the two `<a href="resume/...">` links in `index.html`.
- Colors/fonts/spacing: all in `css/style.css`, under the `:root{ }` token block at the top.
