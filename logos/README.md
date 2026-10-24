# Refine logo kit

Download these from the live site at: `https://refineweb.io/logos/<filename>` (or `http://localhost:8787/logos/<filename>` locally).

| File | Use |
| --- | --- |
| `refine-mark.svg` | Primary mark — `<r>` on deep-ink card. Social avatars, app icons, favicons. 512×512 square. |
| `refine-mark-light.svg` | Mark on warm-canvas card — use when the dark card would clash with the background. 512×512. |
| `refine-mark-mono.svg` | Single-color mark via `currentColor`. Drop in anywhere you need one-color engraving, embroidery, or newsprint. |
| `refine-logo.svg` | Full horizontal lockup for **light** backgrounds (mark card + "refine" wordmark). 1200×400. |
| `refine-logo-reversed.svg` | Full horizontal lockup for **dark** backgrounds. 1200×400. |
| `refine-wordmark.svg` | "refine" wordmark only, Inter 700. Use when the mark would be redundant (e.g. next to a bigger "r" avatar). 900×240. |
| `refine-social-og.svg` | 1200×630 Open Graph / social share card with mark + tagline. Export to PNG for Twitter/LinkedIn/Facebook. |

## Colors (brand palette)

```
Deep ink      #0B1014   primary text, logo card
Warm canvas   #F5F1E8   primary background
Accent teal   #1F4E4A   brackets, links, CTAs
Accent soft   #2F6E68   reversed-state brackets, highlights
```

## Exporting to PNG

If you need raster versions for platforms that don't accept SVG (Instagram, some older CMS), the easiest ways:

- **macOS Preview**: Open the SVG, File → Export… → Format: PNG, pick resolution.
- **Browser**: Open the SVG, right-click → Save As PNG (Chrome has this via DevTools).
- **CLI** (if you have `rsvg-convert` or ImageMagick):
  ```bash
  rsvg-convert -w 1024 refine-mark.svg -o refine-mark-1024.png
  ```

## Clear space

Keep clear space equal to the height of the `<` bracket around any instance of the mark or lockup. Don't crop the brackets, don't rotate, don't change the colors.
