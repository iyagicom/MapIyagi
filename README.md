# MapIyagi

**A map for looking at land in Korea — cadastral parcels, zoning, sunlight hours and street view on one 3D VWorld map. For land surveys and solar site hunting.**

[English](README.md) · [한국어](README_ko.md)

![MapIyagi](mapiyagi.png)

## Why MapIyagi?

- **Click parcels, get the area.** Every parcel you click is added to a list with lot number, land category, area (m²) and zone — with a running **total in m² and pyeong**.
- **See the rules that actually apply.** Zones are looked up per parcel from the official land-use plan, and the one that really restricts the land is shown first.
- **Sunlight hours for solar sites.** Average daily sunlight for each selected parcel, taking the surrounding mountains and terrain into account — the same method solar site-analysis tools use.
- **Look without driving there.** Street view opens side by side with the map and searches nearby roads, even for rural parcels with no road of their own.
- **Real terrain in 3D.** Slopes and ridgelines on an elevation-aware 3D map.

## Features

- VWorld 3D map; search by lot address, road address or place; recent searches; my location
- Cadastral lot numbers and boundaries as separate toggles; right-click for lot number, elevation and full address
- Selected-parcel list with totals; save and restore parcel groups
- Zoning layers: urban, management, agricultural/forest, nature conservation, farmland promotion, development promotion
- Solar sunlight analysis (12-month average, clear-sky theoretical hours)
- Distance and slope between two points, spot elevation
- Satellite map + street view split screen that follows your clicks

## Download

**[⬇ Latest release](https://github.com/iyagicom/MapIyagi/releases/latest)**

| Your system | File to pick |
|---|---|
| Ubuntu · Debian | `.deb` |
| Any other Linux | `.AppImage` (run without installing) or `.zip` |

```bash
sudo apt install ./mapiyagi_*_amd64.deb      # Ubuntu / Debian
```

Uses Korean national map and cadastral data (VWorld, National Spatial Data Platform). An internet connection is required.
