# Treatcito

One-page website for Treatcito: Basque-style cheesecakes made in Mérida, Yucatán.

`index.html` contains everything (images, fonts, code). Nothing else is needed.

## Publish with GitHub Pages

1. Create a new repository on GitHub (e.g. `treatcito`).
2. Upload `index.html` and this `README.md` (Add file → Upload files → Commit).
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch** → branch `main`, folder `/ (root)` → **Save**.
5. After a minute or two the site will be live at `https://<your-username>.github.io/treatcito/`.

## Custom domain (optional, e.g. treatcito.com)

1. In **Settings → Pages → Custom domain**, enter `treatcito.com` and save.
2. At your domain provider, add DNS records:
   - `A` records for `@` → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - `CNAME` record for `www` → `<your-username>.github.io`
3. Once the DNS check passes, tick **Enforce HTTPS**.

## Making changes

Edit the design in the design project, re-export `index.html`, and upload it again over the old one.
