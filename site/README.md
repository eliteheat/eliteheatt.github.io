# Imran Ali Shah — Personal Academic Website

## File Structure

```
eliteheatt.github.io/
├── index.html                  ← Your entire site
└── assets/
    ├── videos/
    │   ├── fly_through.mp4     ← Hero background (Supplemental_Video_1)
    │   ├── deployment.mp4      ← TAVR research card
    │   └── transparent_dep.mp4 ← Fontan research card (converted from .avi)
    ├── images/
    │   ├── overview.png        ← Coronary research card
    │   └── headshot.jpg        ← ADD YOUR PHOTO HERE
    └── pdf/
        └── Shah-Imran_CV.pdf   ← Your CV
```

## Deploying to GitHub Pages

1. Clone your repo locally:
   ```
   git clone https://github.com/eliteheat/eliteheatt.github.io
   ```

2. Replace everything in the repo with these files. Keep the `.github/` folder.

3. Add your headshot as `assets/images/headshot.jpg`

4. In `index.html`, find the about-photo-placeholder block and replace it with:
   ```html
   <img class="about-photo" src="assets/images/headshot.jpg" alt="Imran Ali Shah">
   ```

5. Update your Google Scholar and LinkedIn URLs in the social-row section.

6. Commit and push:
   ```
   git add .
   git commit -m "New site"
   git push
   ```

7. In your GitHub repo settings → Pages → set source to `main` branch, root `/`

## Things to update before launch

- [ ] Add your headshot photo
- [ ] Update Google Scholar URL in the social links section
- [ ] Update LinkedIn URL
- [ ] Update your email if it changes post-graduation
- [ ] Update title from "PhD" to "Postdoctoral Researcher" once conferred

## Future additions (faculty phase)

When you're ready to expand the site, these sections can be added:
- Lab Members / Team page
- Lab News feed
- Lab Resources
- Alumni page

## Notes

- The site uses **no build step** — it's plain HTML/CSS/JS, just push files
- Videos play silently on loop; browsers require muted + autoplay for this
- The `.avi` file was converted to `.mp4` for web compatibility
