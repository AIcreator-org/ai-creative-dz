# AI Creative DZ — GitHub Pages

## Publish
1. Create a new GitHub repository (for example `ai-creative-dz`).
2. Upload `index.html` to the repository root.
3. In **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Wait for GitHub Pages to publish the site.

## Before publishing
Open `index.html` and find:

```js
const BUSINESS_EMAIL = "YOUR_EMAIL@example.com";
```

Replace it with the business email address that should receive enquiries. The contact form uses `mailto:` and opens the visitor's email application; it does not store submissions or send them through a server.

## Important
- Portfolio entries are illustrative concept samples, not real client projects. Keep that disclosure visible unless you replace them with genuine work.
- Prices are starter estimates. Adjust them to your skills, scope and market.
- The site is static and does not include a database, payment processing, authentication or a backend.
- The language selector supports English, French and Arabic. The chosen language is saved in the visitor's browser local storage.
