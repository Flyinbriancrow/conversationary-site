# Conversationary website

These static files provide the public marketing, support, and privacy-policy URLs needed for the App Store listing. They require no database, account system, or paid hosting.

## Preview locally

Open `index.html` in a browser. The privacy and support links use relative paths and work without a web server.

## Publish for free with GitHub Pages

1. Put this repository in a private or public GitHub repository.
2. In GitHub, open **Settings → Pages**.
3. Choose the branch containing these files and the `/Website` folder if that option is available. If GitHub only permits `/` or `/docs`, rename `Website` to `docs` before publishing.
4. Save and wait for the public URL.
5. Enter the resulting URLs in App Store Connect:
   - Privacy Policy URL: `https://YOUR-DOMAIN/privacy.html`
   - Support URL: `https://YOUR-DOMAIN/support.html`
   - Marketing URL (optional): `https://YOUR-DOMAIN/`

Before publishing, replace `YOUR-DOMAIN` with the actual generated address and test every link in a private browser window.
