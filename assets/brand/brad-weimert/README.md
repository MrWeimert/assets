# Brad Weimert personal brand

BWT ornate script monogram, headshots, and derived favicon assets.

Last verified: 2026-07-25

## Files

| File | Use |
|---|---|
| `brad_weimert_logo_black.png` | Master monogram, black on transparent. Use on light/cream backgrounds. 760x635, RGBA. |
| `brad_weimert_logo_cream.png` | Cream on transparent. Use on dark/turquoise backgrounds. 760x635, RGBA. |
| `favicon.ico` | Multi-size ICO (16/32/48/64) for browser tabs |
| `favicon_16.png` | 16x16 PNG favicon |
| `favicon_32.png` | 32x32 PNG favicon |
| `favicon_512.png` | 512x512 PNG for high-DPI use |
| `apple_touch_icon.png` | 180x180 for iOS home screen |

## Brand color reference

- Brand green / turquoise: `#30C4A0`
- Cream: `#F3ECDC`
- Ink black: `#1b1b1b`
- Amber accent: `#f3b23b`

## Referencing from HTML

```html
<link rel="icon" href="https://raw.githubusercontent.com/MrWeimert/assets/main/assets/brand/brad-weimert/favicon.ico">
<link rel="icon" type="image/png" sizes="32x32" href="https://raw.githubusercontent.com/MrWeimert/assets/main/assets/brand/brad-weimert/favicon_32.png">
<link rel="apple-touch-icon" href="https://raw.githubusercontent.com/MrWeimert/assets/main/assets/brand/brad-weimert/apple_touch_icon.png">
```

## Notes

- Master source of the monogram: derived from the SMBulge02 ornate script design
- The ornate script does not compress cleanly to 16-32px favicons; small sizes render as an inkblot but the monogram is recognizable at 64px+ and on modern high-DPI tab bars
- For image overlays on generated LinkedIn/BAM content, always use the full-resolution PNG (not the favicon variants)
