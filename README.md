# Vineet Nair — Technical Content Portfolio

A responsive, static portfolio site built with HTML, CSS, and vanilla JavaScript. No build step or package installation is needed.

## Preview locally

Open `index.html` in a browser, or run a local static server from this folder:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Publish or update with GitHub Pages

This public account-level Pages repository is [kvineetnair.github.io](https://github.com/kvineetnair/kvineetnair.github.io), and its default website address is <https://kvineetnair.github.io/>. The deployment workflow is intentionally manual: pushing files does **not** publish or update the site automatically.

To publish or update the site, open **Settings → Pages** and set the build/deployment source to **GitHub Actions**, then manually run **Actions → Deploy portfolio to GitHub Pages → Run workflow**. The Actions run reports the live URL when deployment completes.

### Use a custom domain

If you own a domain such as `kvineetnair.com`, add that domain under **Settings → Pages → Custom domain**, then configure DNS with your domain provider (GitHub Pages supports an apex domain and `www` subdomain). Add a root-level `CNAME` file containing the exact domain after choosing and verifying it. GitHub's current setup guide: <https://docs.github.com/pages/configuring-a-custom-domain-for-your-github-pages-site>.

## Update the portfolio

- Edit biography, work history, links, or tools in `index.html`.
- Tune colors, typography, and responsive layouts in `styles.css`.
- Mobile navigation and the footer year are handled by `script.js`.
- Replace the résumé PDF in the repository root when you publish an updated version, keeping its current filename or updating the link in `index.html`.

The résumé PDF contains personal contact details and is publicly accessible when deployed. Review its contents before publishing or updating the site.
