# Image Sources — Stock-Well Preview (Visual Pass 4)

Pass 4 (2026-08-16) replaces the pass-3 licensed stock photography with
imagery from the live **stock-well.com** site — Stock-Well's own
installation photo, its logo, and its skyline photo. All assets are
crops/derivatives of three source files, resized to the published pixel
size and encoded as WebP (≤ 200 KB each).

## Source A — Stock-Well West Valley, AZ smart-cooler installation (primary)

| | |
|---|---|
| File | `smart-vending-machine-west-valley-az.jpg` |
| Owner | Stock-Well Vending (served at https://www.stock-well.com/images/smart-vending-machine-west-valley-az.jpg) |
| Native size | 2000 × 1091 |
| Content | Real Stock-Well installation: illuminated glass-door smart beverage coolers with digital menu displays and an ordering terminal |
| Derived | Each asset: window crop (exact box in `staged-manifest.json`), resized, WebP |
| Attribution | Photo: Stock-Well Vending, West Valley AZ smart-cooler installation |

### Assets derived from Source A

| Asset | Served size | Crop box (px, left, top, right, bottom) | |
|---|---|---|---|
| `hero.webp` | 1024 × 683 | (182, 0, 1818, 1091) | centered: both coolers + ordering terminal |
| `service.webp` | 1000 × 1250 | (473, 105, 1265, 1095) | 4:5 portrait: left smart cooler + door + menu display |
| `contact.webp` | 1200 × 800 | (0, 0, 1636, 1091) | left window: main cooler, large menu display |
| `phoenix.webp` | 1200 × 800 | (40, 0, 1676, 1091) | |
| `glendale.webp` | 1200 × 800 | (80, 0, 1716, 1091) | |
| `peoria.webp` | 1200 × 800 | (120, 0, 1756, 1091) | |
| `scottsdale.webp` | 1200 × 800 | (160, 0, 1796, 1091) | |
| `surprise.webp` | 1200 × 800 | (364, 0, 2000, 1091) | right window: side cooler + ordering terminal |
| `west-valley.webp` | 1200 × 800 | (280, 0, 1916, 1091) | |

All city-page images now show the **actual installation type Stock-Well
places** (the real West Valley installation), so the pass-3
"illustration / not a photo of the named city" caveats were removed from
the alt text.

## Source B — Stock-Well logo (header brand)

| | |
|---|---|
| File | `stock-well-vending-logo.jpg` |
| Owner | Stock-Well Vending (served at https://www.stock-well.com/images/stock-well-vending-logo.jpg) |
| Native size | 795 × 194 |
| Derived | `logo.webp` — white background removed (alpha), 795 × 194, WebP |
| Usage | Header brand on all pages (`components/Header.tsx`), `h-8 sm:h-9` |

## Source C — Phoenix skyline (about page)

| | |
|---|---|
| File | `phoenix-skyline-west-valley.jpg` |
| Owner | Stock-Well Vending (served at https://www.stock-well.com/images/phoenix-skyline-west-valley.jpg) |
| Native size | 612 × 408 |
| Derived | `phoenix-skyline.webp` — 612 × 408, WebP |
| Usage | About page figure (added in pass 4), alt: "The Phoenix skyline at sunset — the metro area Stock-Well Vending serves." |

## Favicon

| | |
|---|---|
| File | `favicon.svg` (289 B) |
| Owner | Stock-Well Vending (served at https://www.stock-well.com/favicon.svg) |
| Usage | `public/favicon.svg`, wired via root layout metadata `icons.icon = /stock-well/favicon.svg` |

## Superseded pass-3 assets

The pass-3 CC BY-SA 4.0 derivatives (hero/service/contact/city crops from
the Munich E-Kiosk photo by Strubbl and the Kyoto smart-kiosk photo by
Mr.ちゅらさん) were replaced in pass 4 and are no longer served. The
Wikimedia attribution is removed from all alt text and credit lines.
