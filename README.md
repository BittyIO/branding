Welcome to the Bitty Brand Assets repository! 

This repository contains all the branding assets related to the Bitty projects. 

Whether you are a developer, designer, or contributor, this is the go-to place to access and download the official Bitty branding materials.

## Contents

- `svg/horizontal/`, `svg/vertical/` — "Bitty" wordmark lockups with the vault mark, in each wordmark colour variant.
- `svg/bitty-vault/` — "Bitty Vault" logo as used on the website: the app icon beside the wordmark. `white.svg` is for dark backgrounds, `black.svg` for light ones. "Bitty" is the original wordmark; "Vault" is set in Paytone One (SIL Open Font License) at the same weight and spacing. The icon is embedded as a 256px PNG, so it stays sharp at header sizes.
- `svg/mark.svg` — vault mark (vault wheel with engraved "B" hub, B rotated −19°), transparent background.
- `svg/app-icon.svg` — full app icon (mark on brushed-steel square), vector source.
- `PNG/app-icon/` — app icon PNGs, 16 → 1024px.
- `AppIcon.appiconset/` — drop-in Xcode asset catalog icon set (square, opaque; iOS applies the corner mask).
- `PNG/x/` — X/Twitter avatar (`x-avatar-400.png` to upload; X crops to a circle).
- `favicon/` — website favicons + `site.webmanifest`. `favicon.svg` / `.ico` / `favicon-*.png` are the handles + B only (the SVG adapts to light/dark mode); `apple-touch-icon.png` and `icon-*.png` are the full app icon. Copy into the site root and add:

  ```html
  <link rel="icon" href="/favicon.ico" sizes="any">
  <link rel="icon" href="/favicon.svg" type="image/svg+xml">
  <link rel="apple-touch-icon" href="/apple-touch-icon.png">
  <link rel="manifest" href="/site.webmanifest">
  ```

The "B" letterform is Inter ExtraBold (SIL Open Font License).
