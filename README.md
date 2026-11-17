# Quy Nhon Family Guide

A light, phone-friendly visitor guide to Quy Nhon (Gia Lai province, formerly Binh Dinh), Vietnam. It's written for families visiting in June–July and staying on the Cat Tien coast north of the city. It covers the sea, culture, food, and a four-day plan.

**Status:** scaffold only. The guide content hasn't been published yet.

## Layout

| Path | What it holds |
|---|---|
| `index.html` | The guide: a single file with inline CSS and a small amount of JS. Currently a placeholder. |
| `images/` | Compressed WebP images, named by place (e.g. `ky-co.webp`). Every image is credited in `data/image-credits.json`. |
| `content/guide.md` | The guide text in Markdown, edited for publication. |
| `data/places.json` | One record per place: name, coordinates, drive time from Cat Tien, effort tag, map link. It drives the place cards and map pins. |
| `data/image-credits.json` | Source URL, author and licence for each image. |
| `LICENSE-images.md` | How images are licensed and credited. |

## Updating

1. Edit `content/guide.md` and `data/places.json`.
2. Rebuild `index.html` from them.
3. Before every push, run the privacy check: no personal names, emails or group details, and image metadata stripped.

## Publishing

GitHub Pages: Settings, then Pages, then "Deploy from a branch", then `main` / root.

## Accuracy

Prices, opening hours and event dates change often. Each section shows the date it was last checked. Check anything marked "check before you go" closer to your trip.
