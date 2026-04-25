# My Identity Card — GitHub Pages

A sleek, ready-to-deploy developer profile card for GitHub Pages featuring automatic Discord embeds (Large Image) and a built-in Screenshot engine.

## 🚀 Deploy to GitHub Pages

1. **Create a new repository** on GitHub (e.g., `identity-card` or `username.github.io`).
2. **Upload** the `index.html` file to that repository.
3. Go to **Settings → Pages**. Under **Build and deployment**, set the source to **Deploy from a branch** and select `main` (or `master`) as the root folder.
4. Wait a few minutes → your site will be live at `https://username.github.io/repository-name/`.

## 📸 Setting Up the Discord Embed Image

To make the full card appear as a large image when sharing on Discord, you need to set up the preview image. We've made this incredibly easy with the built-in screenshot feature!

1. Open your live site in your browser.
2. Click the **"Take Screenshot"** button at the bottom of the page. It will automatically download a high-res, transparent-ready image of your card.
3. Rename the downloaded file to `preview-card.png`.
4. Upload `preview-card.png` to your GitHub repository (in the same folder as `index.html`).
5. Open `index.html` and ensure the `og:image` and `twitter:image` meta tags are pointing to your exact live URL (e.g., `https://username.github.io/repository-name/preview-card.png`).

## 💬 Sharing to Discord

Simply paste your GitHub Pages URL directly into a Discord chat. Discord will automatically read the meta tags and display your custom profile card!

**💡 PRO TIP: Bypassing Discord's Cache**
If you update your code or replace the `preview-card.png`, Discord might still show the old version because of aggressive caching. To force Discord to fetch the newest version, just add a dummy parameter to the end of your link when sharing:
```text
[https://username.github.io/repository-name/?v=new_update](https://username.github.io/repository-name/?v=new_update)
