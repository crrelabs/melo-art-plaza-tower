# Art Plaza Tower

Luxury apartment rentals in Edgewater, Miami. A static marketing site for [Melo Group](https://melogroup.com), redesigned from the live WordPress site at [artplazatower.com](https://artplazatower.com).

**58 NE 14th Street, Miami, FL 33132** · 305 800 6000 · info@artplazatower.com

## Preview locally

```bash
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000).

Any static file server works — there is no build step, WordPress, or JavaScript framework. The page is a single `index.html` with Tailwind via CDN, the same pattern used by sibling Melo property sites (25 Mirage, Square Station).

## Structure

| Path | Purpose |
| --- | --- |
| `index.html` | Full single-page site |
| `images/` | Logos, photography, location map |
| `floorplans/` | Unit layouts (downloaded from the live site) |
| `brochure.pdf` | Property brochure |
| `rental-booklet.pdf` | Rental booklet |
| `CNAME` | `artplazatower.com` for GitHub Pages |

The Schedule a Visit form opens a pre-filled `mailto:` to info@artplazatower.com. No backend is required.
