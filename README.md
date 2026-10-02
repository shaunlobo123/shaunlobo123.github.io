# Shaun Lobo — Portfolio (GitHub Pages)

This is a static portfolio site, ready to push to GitHub Pages and link on your CV.

## Preview locally
```bash
cd portfolio
python3 -m http.server 5173
# open http://localhost:5173
```

## Deploy to GitHub Pages (2 mins)
1. Create a new public repo on GitHub named `shaunlobo.github.io` (use your GitHub username)
   OR use any repo name e.g. `placement-portfolio` and enable Pages from `main / root`.
2. Push this folder's contents:
```bash
cd portfolio
git init
git add .
git commit -m "portfolio v1"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/shaunlobo.github.io.git
git push -u origin main
```
3. Go to repo Settings → Pages → Deploy from branch → `main` + `/ (root)`
4. Your URL will be `https://YOUR-USERNAME.github.io/` — put that on your CV.

Files:
- `index.html` — edit text, project descriptions, links here
- `styles.css` — colours / layout
- `images/` — drop your photos here (see images/README.md)
- `assets/` — put `Shaun_Lobo_CV.pdf` here to enable CV download button

## Next to add (send me these and I'll wire them in)
- [ ] Glove photos: `glove-hero.jpg`, `glove-1.jpg`, `glove-2.jpg`, `glove-demo.gif`
- [ ] Line-follower + beacon-bot photos
- [ ] Simulink plots PNG
- [ ] App screenshots
- [ ] GitHub / LinkedIn URLs
- [ ] CV PDF
