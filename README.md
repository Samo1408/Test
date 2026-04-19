# Pixel Devices

Community-maintained device preset files for `Pixel Devices`.

Each preset lives in the repository root as a single JSON file such as:

- `Google Pixel 8 Pro.json`
- `Google Pixel 10 Pro.json`
- `Google Pixel 9 Pro.json`

## Format

```json
{
  "id": "pixel_8_pro",
  "brandLabel": "Google",
  "modelLabel": "Pixel 8 Pro",
  "summary": "Tensor G3 - Android 15",
  "profile": {
    "brand": "google",
    "manufacturer": "Google",
    "model": "Pixel 8 Pro"
  }
}
```

The app reads root-level `.json` files from this repository and turns them into selectable presets.
