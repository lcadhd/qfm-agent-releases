# QFM Agent — Releases

Signed APK releases for the QFM Agent companion app (Meta Quest 3/3S).

## Latest Release

**v1.1.0** — H.264 casting, JPEG compression, secure pairing, policy engine.

## Download URLs

### Always-Latest (recommended for HMS)
```
https://github.com/lcadhd/qfm-agent-releases/raw/main/releases/latest/qfm-agent-latest.apk
```
This URL always points to the most recent stable release. Use this in HMS Device Manager.

### Specific Versions
```
https://github.com/lcadhd/qfm-agent-releases/raw/main/releases/v1.1.0/qfm-agent-1.1.0.apk
https://github.com/lcadhd/qfm-agent-releases/raw/main/releases/v1.0.0/qfm-agent-1.0.0.apk
```

### GitHub Releases API (latest)
```
https://github.com/lcadhd/qfm-agent-releases/releases/latest/download/qfm-agent-latest.apk
```

## Install via ADB
```bash
adb install qfm-agent-latest.apk
```

## Deploy via HMS
1. In Admin Center: **Devices > Apps > + New app**
2. App name: `QFM Agent`
3. Link: `https://github.com/lcadhd/qfm-agent-releases/raw/main/releases/latest/qfm-agent-latest.apk`
4. Assign to your device profile as a required app
5. On new releases, devices auto-update on next check-in (same URL, new binary)

## Changelog

### v1.1.0
- H.264 casting via screenrecord (30fps, configurable bitrate)
- JPEG compression (6-10x bandwidth reduction)
- Secure pairing flow (6-digit PIN)
- Rate limiting (100 req/s)
- Complete policy engine (time limit + schedule)
- 29 unit tests

### v1.0.0
- Initial release
- 14 JSON-RPC namespaces, 65+ methods
- Settings, health, casting, spatial, tracking, safety, peer, comm, policy

## Requirements
- Meta Quest 3 or Quest 3S
- Horizon OS v57+ (Android API 32+)
- Developer mode enabled

## License
Private — Digital Outback
