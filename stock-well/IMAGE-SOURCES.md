# Image Sources & Licenses — Stock-Well Preview (Visual Pass 3)

All images in `public/img/` are properly-licensed free stock photos, all
downloaded 2026-08-16. Every image is a **derivative**: center-window cropped
to the site's aspect ratio, resized to the published pixel size, and encoded
as WebP (≤ 200 KB each).

**Smart-cooler imagery (pass 3 requirement):** hero, service, and all city
pages now depict modern commercial smart-cooler installations (illuminated
glass-door beverage coolers with digital menu displays / ordering terminals)
instead of the pass-2 office, generic-vending, and desert-landscape photos.

**License key:** CC BY-SA = attribution + share-alike (all pass-3 assets).

**Honesty note:** the city-page images are **illustrations of the
installation type** Stock-Well places — they are not photographs of the
named Arizona city, and the alt text says so. Two source photographs are
used: one Munich E-Kiosk installation (primary) and one Kyoto smart-kiosk
station installation (city pages), rotated across the six city routes.

Full attribution also rendered in image `alt` text and the per-page credit
line.

---

## Source A — Munich E-Kiosk (primary; hero, service, contact, glendale, surprise, west-valley)

| | |
|---|---|
| File | Automaten im E-Kiosk in der Albert-Roßhaupter-Straße 2 München 2024-12-18.jpg |
| Author | Strubbl |
| License | CC BY-SA 4.0 — https://creativecommons.org/licenses/by-sa/4.0/ |
| Source | https://upload.wikimedia.org/wikipedia/commons/d/d7/Automaten_im_E-Kiosk_in_der_Albert-Ro%C3%9Fhaupter-Stra%C3%9Fe_2_M%C3%BCnchen_2024-12-18.jpg |
| Native size | 5472 × 3648 |
| Derived | Each asset: window crop (exact box in `staged-manifest.json`), resized, WebP |
| Attribution | Strubbl, “Automaten im E-Kiosk in der Albert-Roßhaupter-Straße 2 München 2024-12-18”, CC BY-SA 4.0, via Wikimedia Commons |

### Assets derived from Source A

| Asset | Served size | Crop box (px, top-left, bottom-right) |
|---|---|---|
| `hero.webp` | 1024 × 683 | full frame (1, 0, 5470, 3648) |
| `service.webp` | 1000 × 1250 | (1778, 285, 4240, 3362) — center coolers + displays |
| `contact.webp` | 1200 × 800 | (0, 693, 3392, 2954) — left coolers |
| `glendale.webp` | 1200 × 800 | (2517, 1313, 4049, 2334) — mid coolers zoom |
| `surprise.webp` | 1200 × 800 | (1477, 1094, 4213, 2918) — coolers + ordering terminal (re-cropped rightward 2026-08-16) |
| `west-valley.webp` | 1200 × 800 | (820, 912, 3556, 2736) — wider left-center |

---

## Source B — Kyoto smart kiosk (city pages: phoenix, scottsdale, peoria)

| | |
|---|---|
| File | Smart Kiosk Kyoto Station No2-3Homes.jpg |
| Author | Mr.ちゅらさん |
| License | CC BY-SA 4.0 — https://creativecommons.org/licenses/by-sa/4.0/ |
| Source | https://upload.wikimedia.org/wikipedia/commons/0/0d/Smart_Kiosk_Kyoto_Station_No2-3Homes.jpg |
| Native size | 3840 × 2160 |
| Derived | Each asset: window crop, resized, WebP |
| Attribution | Mr.ちゅらさん, “Smart Kiosk Kyoto Station No2-3Homes”, CC BY-SA 4.0, via Wikimedia Commons |

### Assets derived from Source B

| Asset | Served size | Crop box (px) |
|---|---|---|
| `phoenix.webp` | 1200 × 800 | (600, 0, 3840, 2160) — kiosk zone |
| `scottsdale.webp` | 1200 × 800 | (1460, 287, 3840, 1873) — right kiosk zoom |
| `peoria.webp` | 1200 × 800 | (346, 287, 2726, 1873) — left kiosk zoom |

---

## Superseded pass-2 assets (replaced in pass 3)

hero (BAKOKO, office aisle, CC BY-ND), service (Kritzolina, generic food
vending machine, CC BY-SA), contact (Damian Patkowski, workspace, CC0), and
the six desert-landscape city textures (neepster, Jovonni Pharr,
Cygnusloop99, inkknife_2000, Nicholas Hartmann, Katja Schulz) were removed
from `public/img/` in pass 3 and are no longer served.
