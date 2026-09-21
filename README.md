# SD4G — Service Design for Good

Website for the **SD4G Lab** at Dongseo University, Busan.

Implemented from Figma as a single static page — no build step, no
dependencies, no backend.

## Files

- `index.html` — the whole page (markup + CSS)
- `assets/img/` — photography and artwork exported from Figma

## Viewing it

Open `index.html` in any browser. Live at
<https://kimbabchapati664.github.io/sd4g-website/>.

## Sections

Header · hero · three mission pillars · recent projects · research areas and
publications · study with us · lab director · blog · keyword marquee ·
photo gallery · call to action · footer.

## Notes

- Type is Plus Jakarta Sans with Noto Sans KR for the Korean publication titles.
- The design is authored at 1280px. Below 1100px the grids collapse to a single
  column and the nav links are hidden.
- The keyword marquee respects `prefers-reduced-motion`.
- Nav links are in-page anchors; the sub-pages they imply do not exist yet.
