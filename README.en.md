# BÁSAP Glycine Re:Volume Shampoo Landing Page

A responsive static landing page based on the Wadiz detail page (v2). No build step.

## Structure

```
index.html        Page markup (inline CSS and JS)
assets/img/       Product and model photos, GIFs, logo
assets/fonts/     Pretendard 400/500/700/800, BASAP Serif
```

## Local preview

```
python3 -m http.server 8000
```

Open `http://localhost:8000` in a browser.

## Deploy (GitHub + Vercel)

1. Push this folder to the root of a GitHub repository
2. Vercel > Add New Project > Import the repository
3. Framework Preset: `Other`, leave Build Command and Output Directory empty, then Deploy

## Notes

- The clinical test, tester reviews, supplier data and some FAQ figures are sample data for the mockup.
- Buttons such as "지금 펀딩하기" jump to the on-page reward section (`#reward`). Replace the `href` with the real Wadiz link when available.
