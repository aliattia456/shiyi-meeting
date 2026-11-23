# Shiyi Meeting (释义)

Real-time human interpretation for rooms that cannot afford guesswork.

**Windows x64 desktop client.** Signed, portable, 113 KB — no installer, no account.

## Install

1. Download `ShiyiMeeting.exe` from the latest release.
2. Run it and enter the six-character session code your coordinator or interpreter gave you.
3. The code is valid for 24 hours and works once. It is spent when the client fetches the
   session, so a forwarded link still costs one install.

## Verification

Compare the SHA-256 of the downloaded file with the digest published on
https://shiyimeeting.xyz/download before launching on a regulated network:

```
certutil -hashfile ShiyiMeeting.exe SHA256
```

## Requirements

Windows 10 1903 or later (x64) with a WDDM 2.0 display driver. Audio-only operation works
over constrained links.

© 2026 Shiyi (Hangzhou) Technology Co., Ltd.
