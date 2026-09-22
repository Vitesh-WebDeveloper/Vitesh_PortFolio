# Pulluri Sai Vitesh — Portfolio

A recruiter-focused portfolio built with plain HTML and CSS.

## Files

- `index.html` — complete portfolio page
- `style.css` — all styling and responsive layout
- `assets/profile.png` — profile photo
- `assets/resume.pdf` — resume (actual PDF, linked from the nav and hero buttons)
- `assets/vibecart-preview.png` — real screenshot used in the VibeCart feature card
- `assets/techstore-preview.png` — real screenshot used in the TechStore card
- `assets/movie-engine-preview.png` — real screenshot used in the Movie Engine card
- `assets/weather-preview.png` — real screenshot used in the Weather Dashboard card

## Folder structure

Keep this exactly as it is so the relative links keep working:

```text
portfolio/
├── index.html
├── style.css
└── assets/
    ├── profile.png
    ├── resume.pdf
    ├── vibecart-preview.png
    ├── techstore-preview.png
    ├── movie-engine-preview.png
    └── weather-preview.png
```

## Deploy

Static site — deploy the folder with GitHub Pages, Netlify or Vercel.

For Vercel:
1. Put these files in a GitHub repository.
2. Import the repository into Vercel.
3. Deploy with the default static settings.

## Changes in this update

- Logo: replaced the plain "PSV." text with a small gradient monogram + wordmark.
- Resume button: now links to the real resume PDF at `assets/resume.pdf` (previously pointed at a placeholder, so it opened a blank/plain PDF).
- Added a "Contact" link to the nav bar (the section existed but wasn't linked).
- About section: removed the "recruiters do not see" phrasing; reworded to sound less like it's performing for a reader.
- Project previews: swapped the drawn CSS mockups for your real project screenshots.
- Removed the "Country Search Dashboard" entry entirely.
- Verified the Email and Call buttons use valid `mailto:` and `tel:` links — if they still don't respond after redeploying, it's most likely a stale cached build; a hard refresh or redeploy should fix it.
