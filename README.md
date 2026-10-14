# Property Repair & Solutions — GitHub Pages

Static website files for Property Repair & Solutions in Saginaw, Michigan.

## Publish with GitHub Pages

1. Create a GitHub repository (for example, `property-repair-website`).
2. Upload **all files in this folder** to the repository root. Keep `index.html`, `robots.txt`, `sitemap.xml`, and `.nojekyll` at the root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then save.
5. Wait for the published URL shown on the Pages settings screen.

## Important notes

- GitHub Pages is static hosting. The quote form currently opens the visitor's email app with a prefilled email; it does not submit to a server or database.
- To receive form submissions without relying on the visitor's email app, connect a form backend (for example, Formspree or another form service) and update the form action.
- The included `robots.txt` and `sitemap.xml` use `https://www.propertyrepairsolution.com/`. If you publish on a different domain, update both files and the canonical/Open Graph URLs in `index.html` to match the live domain.
- The HTML references images in a `media/` folder. Add your actual logo and project photos in a `media` folder in the repository, using the same filenames: `logo.jpg`, `kitchen-before.jpg`, `kitchen-after.jpg`, `living-room-before.jpg`, `living-room-after.jpg`, `bedroom-before.jpg`, and `bedroom-after.jpg`. If you do not have those images, the page will still load, but those images will not appear.
- Verify business details, reviews, and structured data before publishing.
