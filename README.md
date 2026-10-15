# My Switch OLED

A Claude artifact styled like the Switch home menu. It tracks the white Switch OLED bought on eBay (14 Oct 2026, arriving 19–21 Oct), holds a case of game cards with box art, and keeps an accessories list with a running total.

Live page: https://claude.ai/artifact/5wdmqU9TWE7hiTRqzP3hcS (private)

- `index.html`: the whole page. It saves through the artifact's `db` capability (`games`, `acc`, `tracker/main`) and uploads custom cover art through `assets`. Opened anywhere else, it runs in memory and saves nothing.
- `covers/`: box art for the 43 games in the add-game list. Most come from Wikipedia, and a few Switch editions come from Nintendo's store.
- `console/`: the 10 photos from the eBay listing.

To change the page, edit `index.html` and republish it to the same artifact URL.
