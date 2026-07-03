# ideocentric/scoop-bucket

[Scoop](https://scoop.sh) bucket for
[iconsmaker](https://github.com/ideocentric/iconsmaker) — generate platform icon
bundles (macOS, Windows, Linux) from a single SVG.

## Install

```powershell
scoop bucket add ideocentric https://github.com/ideocentric/scoop-bucket
scoop install iconsmaker
```

Supports both `64bit` (x86_64) and `arm64` Windows. The manifest has `checkver` +
`autoupdate` pointing at iconsmaker's GitHub releases, so new versions are picked
up automatically (run `scoop update`).