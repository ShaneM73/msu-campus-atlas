# Missouri State Campus Atlas

**▶ Open the live web app: [shanem73.github.io/msu-campus-atlas](https://shanem73.github.io/msu-campus-atlas/)**

**Designer and main contributor:** Prof. Xin (Shane) Miao, Missouri State University ([@ShaneM73](https://github.com/ShaneM73))

An interactive 3D infographic of the Missouri State University campus, built from the campus SketchUp model.

## Files
- `index.html` - the page
- `campus-app.js` - page code with the 3D engine (three.js) bundled in
- `campus-model.txt` - the campus model (gzipped glTF, base64 text)

Keep all three files in the same folder. The page does not work when opened by double-clicking `index.html`,
because browsers block loading the model from a local file. Serve it from any web server instead.

## Publish free on GitHub Pages
1. Create a new public repository on GitHub, for example `msu-campus-atlas`.
2. Upload the three files (Add file > Upload files) and commit.
3. Go to Settings > Pages. Under "Build and deployment", choose "Deploy from a branch",
   pick `main` and `/ (root)`, then Save.
4. After a minute or two the site is live at `https://<your-username>.github.io/msu-campus-atlas/` — this copy is live at https://shanem73.github.io/msu-campus-atlas/.

## Preview on your own computer
In this folder run `python3 -m http.server 8000`, then open http://localhost:8000.

## Other hosts
Any static host works the same way (Netlify Drop, Cloudflare Pages, a university web server):
upload the folder as-is.
