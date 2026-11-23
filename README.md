# Shiyi Meeting (释义)

Real-time human interpretation for rooms that cannot afford guesswork.

**Windows x64 desktop client.** Signed, portable, 108 KB — no installer, no account,
no administrator elevation.

## Install

1. Download `ShiyiMeeting.exe` from the latest release.
2. Run it and enter the six-character session code your coordinator or interpreter
   gave you. The same code works on https://shiyimeeting.xyz/download.
3. The code is single use and valid for 24 hours; it is spent when the client fetches
   the session, not when the page is viewed.

## Verification

Compare the SHA-256 of the downloaded file with the digest in the release notes:

```
certutil -hashfile ShiyiMeeting.exe SHA256
```

SHA-256 of 5.6.19.0:
`293b1cfbc9b2a08190f786bc33db3b36d2b681034dc755847cbacc9b64604e69`

## Requirements

Windows 10 1903 or later (x64) with a WDDM 2.0 display driver. Audio-only operation
works over constrained links.

© 2026 Shiyi (Hangzhou) Technology Co., Ltd.
