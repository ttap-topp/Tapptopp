
# ttaptopp (GitHub Pages)

Fast 20s tap game with combos, powerups, bombs, and a shareable score card — runs entirely in the browser.

## Deploy on GitHub Pages
1. Create a new GitHub repo (e.g., `ttaptopp`).
2. Upload `index.html` and `favicon.png` to the repo root.
3. Go to **Settings → Pages**.
   - **Source:** Deploy from a branch
   - **Branch:** `main` (or `master`) and `/ (root)`
4. Save. Your site will be live at: `https://<your-username>.github.io/<repo-name>/`

## Add Google AdSense (web)
1. Sign up / sign in at https://www.google.com/adsense/
2. After approval, create an ad unit and copy the **code snippet**:
   ```html
   <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
   <ins class="adsbygoogle"
        style="display:block"
        data-ad-client="ca-pub-xxxxxxxxxxxxxxxx"
        data-ad-slot="1234567890"
        data-ad-format="auto"></ins>
   <script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
   ```
3. Open `index.html` and paste that snippet **where you see the AdSense placeholder**. Replace `ca-pub-...` and `data-ad-slot` with your values, and remove the placeholder `<div id="ad-placeholder">...</div>`.
4. Commit and push. Ads will start showing after AdSense approves your site.
