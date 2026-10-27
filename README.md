# Geeta Creations

Website for Geeta Creations: hand-painted chiffon and kota sarees and suits by Jaipur artist Geeta Chauhan.

A single static page (`index.html`) with product photos in `img/`. No build step. It is served by GitHub Pages from the `main` branch.

## Editing

- **Catalogue:** the `pieces` list in the `<script>` at the bottom of `index.html`. Each piece has an id, price (empty = "Price on request"), English and Hindi name, type, colour, fabric, motif, description and photo(s).
- **Hindi text:** the `HI` (page text) and `PIECE_HI` (catalogue) objects in the same script.
- **WhatsApp number:** the `WHATSAPP` constant.
- **Display order:** the `ORDER` list. Cards at positions 0, 7, 14 and 21 are shown wide.
