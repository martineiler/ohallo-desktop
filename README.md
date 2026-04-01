# oHallo Desktop

Desktop application for the oHallo customer operations platform.

## Download

Download the latest version for your platform from the [Releases](https://github.com/martineiler/ohallo-desktop/releases) page.

| Platform | Format |
|---|---|
| macOS (Apple Silicon) | `.dmg` |
| macOS (Intel) | `.dmg` |
| Windows | `.exe` installer |
| Linux | `.AppImage` |

## Configuration

On first launch the app connects to `https://api.ohallo.eu`. To point to a different environment, create `~/.ohallo/config.json`:

```json
{
  "apiBaseUrl": "https://api.staging.ohallo.eu",
  "kindeDomain": "https://auth.ohallo.eu",
  "kindeClientId": "519c6d2894ec484ca3f97fc940e5e79b",
  "kindeAudience": "https://api.staging.ohallo.eu"
}
```

## Auto-updates

The app checks for updates automatically. When a new version is available you will be prompted to install it. If the server requires a newer version than what you have installed, a mandatory update screen will appear.
