# CV Studio — publish to GitHub Pages

This folder is a ready-to-upload website:

- `index.html` — landing page (this is the link you share; it carries the WhatsApp preview card)
- `CV_Builder.html` — the app itself (empty, no personal data)
- `CV_Data_Starter.xlsx` — the blank starter workbook
- `og-image.png` — the preview card image

## Set up (once, ~5 minutes)

1. Go to **github.com** and sign in (or Sign up — free).
2. Click **+ → New repository**. Name it exactly **cv-studio**, set it to **Public**, click **Create repository**.
3. On the new repo page click **"uploading an existing file"**, drag in all four files from this folder, click **Commit changes**.
4. Open `index.html` in the repo, click the **pencil (Edit)** icon, and replace **YOUR-GITHUB-USERNAME** with your actual GitHub username on the two marked lines near the top. Commit.
5. Go to **Settings → Pages**. Under *Build and deployment*, set Source to **Deploy from a branch**, branch **main**, folder **/ (root)**. Save.
6. Wait a minute or two, then your site is live at:

   `https://YOUR-GITHUB-USERNAME.github.io/cv-studio/`

## Share on WhatsApp

Paste that link into the chat. WhatsApp fetches the page, reads the card details and shows the CV Studio preview (logo, title, tagline, image). Your brother taps it, presses **Open CV Studio**, downloads the starter workbook, and he's away.

## Notes

- **Public means public** — anyone with the link can open the app. That's fine: the uploaded app is empty. **Never upload your own `CV_Data.xlsx` or a saved copy of the app containing your data** to this repo.
- His data stays his: the app runs entirely in the browser; "Save app" downloads his own copy with his data embedded — nothing is stored on GitHub.
- WhatsApp caches previews. If the card doesn't appear at first, give Pages a few minutes after setup and try sending the link again (or add `?v=2` to the end once).
- To update the app later: upload a new `CV_Builder.html` over the old one (same name), commit, done.
