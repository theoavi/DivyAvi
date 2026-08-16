# Avi & Divya — Wedding Site

## Structure
```
index.html      the site (Engagement + Wedding pages)
images/         hero.jpg, img1.jpg, img3.jpg, img4.jpg
```

## Before going live
1. Formspree → create a free form → copy the form ID.
2. In `index.html`, replace both instances of `YOUR_FORM_ID` with it.

## Deploy
1. Push this folder to a new GitHub repo.
2. Import the repo in Vercel → deploy (no build step needed, it's static).
3. Every push to `main` auto-redeploys.

## Adding more pages/images later
Drop new images into `images/`, reference them in `index.html` as `images/filename.jpg`.
