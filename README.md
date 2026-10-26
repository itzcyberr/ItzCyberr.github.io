# ItzCyberr Marketplace (static starter)

A responsive, premium dark aubergine/purple Minecraft resource marketplace frontend.

## Files
- `index.html` — page structure
- `styles.css` — theme and responsive layout
- `products.js` — sample product data
- `app.js` — search, filters, favorites and product detail modal
- `assets/itzcyberr-character.png` — replace with your own Minecraft character image

## Publish to GitHub Pages
1. Open your repository: `https://github.com/itzcyberr/itzcyberr.github.io`
2. Upload `index.html`, `styles.css`, `products.js`, `app.js`, and the `assets` folder to the repository root. Keep the names unchanged.
3. Commit the files to the `main` branch.
4. In Settings → Pages, select `Deploy from a branch`, branch `main`, folder `/(root)`.
5. Wait for deployment, then visit `https://itzcyberr.github.io/`.

## Add your logo
Replace `assets/itzcyberr-character.png` with your own transparent PNG or WebP converted to PNG, keeping the same filename. This starter uses a fallback monogram if the image is absent.

## Edit products
Edit `products.js`. Each product has an `id`, `name`, `category`, `type`, `version`, `minecraft`, `platform`, `description`, `features`, `downloadUrl`, `cover`, `featured`, and `date`.

Use a publicly downloadable release URL in `downloadUrl` only after you have uploaded and tested your own file. Replace demo data; demo products are not real downloads.

## Important limitation
This is a **static frontend**, not a secure upload platform. Favorites are saved in the visitor's browser. A private admin dashboard, secure authentication, database-backed product editing, and direct `.jar` uploads require a backend (for example, a compatible app host plus a database/auth/storage provider). Do not put secrets or admin credentials in these public files. Do not expose untested downloads.
