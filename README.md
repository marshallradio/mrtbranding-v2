# Marshall Radio Telemetry · Typography Lab v2

Live exploration of the Matter font faces (Medium 500 + Bold 700) with improved tracking, leading, and color contrast.

**Original brand guidelines remain untouched:** https://github.com/marshallradio/mrtbranding

## How to view online

1. Go to **Settings → Pages** on this repository.
2. Source: Deploy from a branch → `main` → `/ (root)`.
3. Save. The site will be available at **https://marshallradio.github.io/mrtbranding-v2/** after a few minutes.

## Fonts

Upload these files into the `fonts/` folder (create the folder if needed):

- `Matter-Medium.woff`
- `Matter-Bold.woff`

WOFF is the preferred web format. If you only have TTF or OTF, convert them at https://transfonter.org (or similar) to WOFF/WOFF2.

## Why the original may not look striking

The original site only references locally installed Matter via `local()`. Most visitors see the Helvetica/Arial fallback. Hosting the real faces + tighter display tracking + stronger contrast fixes this.

## License note

Displaay’s standard license for Matter restricts hosting the font files on publicly accessible servers. Confirm your license covers web use before publishing this widely.
