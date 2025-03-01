# Niconico-WebOS

ニコニコ動画 WebOS アプリ / Niconico WebOS App.

## Development

### Prerequisites

- Node.js 16 (required by [@webos-tools/cli](https://github.com/webos-tools/cli))
- PNPM

### Setup

```bash
pnpm install
```

### Test on WebOS TV

Please follow the instructions in the [App Testing with Developer Mode App](https://webostv.developer.lge.com/develop/getting-started/developer-mode-app)

```bash
pnpm ares-setup-device
```

Get SSH key from the TV

```bash
pnpm ares-novacom --device <name> --getkey
```

Check whether the device is connected

```bash
pnpm ares-device --system-info --device <name>
```
