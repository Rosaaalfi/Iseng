# My Identity Card — GitHub Pages

Ready-to-deploy profile card for GitHub Pages + automatic Discord embeds.

## Deploy to GitHub Pages

1. **Create a new repository** on GitHub with any name (e.g., `aniko-profile` or `username.github.io`).
2. **Upload the** `index.html` file to that repository.
3. Go to **Settings → Pages → Source → Deploy from branch → main / root**.
4. Wait a few minutes → your site will be live at `https://username.github.io/aniko-profile/`.

## Discord Embed

Simply paste your GitHub Pages URL directly into a Discord chat:
```
https://username.github.io/aniko-profile/
```
Discord will automatically read the meta tags for `og:title`, `og:description`, and `theme-color: #4afa8a`.

## Making the Embed Image Appear (Optional)

Discord requires an `og:image` tag for image previews. You have two options:

**Option 1 — Manual Screenshot:**
- Open `index.html` in your browser.
- Take a screenshot of the card (1200×630px is ideal).
- Save it as `card.png`.
- Upload it to the same repository.
- Edit `index.html` and replace `https://aniko.github.io/card.png` with your own `card.png` URL.

**Option 2 — Automated with screenshotapi.net or similar services.**

## Editing Content

Open `index.html`, locate the section marked ``, and edit the text/links to fit your needs.
