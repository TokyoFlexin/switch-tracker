# My Switch OLED

A one-page site styled like the Switch home menu. It tracks the white Switch OLED bought on eBay (14 Oct 2026, arriving 19–21 Oct), holds a case of game cards with box art, and keeps an accessories list with a running total.

Live site: https://tokyoflexin.github.io/switch-tracker/

- `index.html`: the whole site, with no build step. Games, accessories, tracker stage and tracking number are saved in the browser's `localStorage` under `switch-oled-v1`, so each browser keeps its own copy. Uploaded cover art is shrunk to 360 px and saved there too.
- `covers/`: box art for the 43 games in the add-game list. Most come from Wikipedia, and a few Switch editions come from Nintendo's store.
- `console/`: the 10 photos from the eBay listing.

GitHub Pages serves the `main` branch root, so pushing to `main` redeploys the site.
