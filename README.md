# Blend Online – product page

Product page and documentation for the **Blend Online** Blender add-on. This repository holds only the description, documentation and media, not the add-on itself.

- Product page: `index.html`, served with GitHub Pages at https://blenderprocedural.github.io/blend-online/
- Documentation: `docs.html`, served at https://blenderprocedural.github.io/blend-online/docs.html
- Images: `images/` (screenshots, cover, logo)
- Video: the promo is on [YouTube](https://www.youtube.com/watch?v=EWpHzKYHCZs), short silent loops are in `media/*.mp4`
- Shared style and iframe helper: `assets/`. Fonts (Inter) are bundled in `fonts/`. The only external request is the YouTube player on the product page.

Both pages work inside an iframe. Links to other pages open in a new tab, and the page posts its height to the parent window (`{type: "blend-online-height", height}`).

![Blend Online](images/cover.jpg)
