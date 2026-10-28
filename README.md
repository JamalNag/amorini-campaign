# Feminist Slogans, Worn by a Young Man

A one-page site about a June 2026 fashion campaign with Amorini Concept, an art and fashion brand in Baku founded by Günay Aliyeva. Jamal Naghizade modelled T-shirts printed with feminist slogans and helped shape the slogans, the shirts and the styling. Static HTML, no build step. Available in English, Azerbaijani and Russian.

## Files

- `index.html`: the page. English text lives here.
- `assets/styles.css`: design tokens (colours, fonts, motion) at the top, then the layout.
- `assets/i18n.js`: Azerbaijani and Russian translations, keyed by each element's `data-i18n` (or `data-i18n-alt` / `data-i18n-aria`) attribute. The slogans stay in English, as printed on the shirts.
- `assets/main.js`: the language switcher, the slogan tabs, the copy-email button, and pausing the carpet bands when they are off screen.
- `assets/img/`: photos, re-encoded without metadata.
- `assets/ornament/`: carpet tiles for the moving band.

## Ornament

The patterns come from a modern Baku carpet (`assets/img/carpet.jpg`): the stepped medallion in the logo, the diagonal-striped outer border, and the rows of buta (paisley) shapes in the field.

## Publishing on GitHub Pages

Push this folder to a GitHub repository. Then go to **Settings → Pages**, choose **Deploy from a branch**, and select `main` with the `/ (root)` folder.
