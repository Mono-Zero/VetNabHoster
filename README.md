# VetNab

**Know what's inside a QR code before it opens.**

VetNab is an Android QR scanner that works completely offline. It scans a code, weighs what it finds, and shows you a risk score with a plain-language explanation of each finding.

**Download page:** https://vetnab.vercel.app
**Direct download:** [VetNab APK](https://github.com/Mono-Zero/VetNabHoster/releases/download/VetNab/VetNab.apk)

This repo only hosts the download page and the APK. VetNab's source code isn't public.

## What it does

- Scans a QR code and runs it through a list of checks (the full list is in the app under Advanced options)
- Shows a risk score and a short explanation for every finding
- Limits what you can do based on the score: safe codes open directly, and dangerous ones are copy-only

## Privacy

- Camera permission only
- Fully offline: no server, no outside calls
- No tracking
- Scan history is off by default. If you turn it on, it keeps only a short fragment of each scan, enough to jog your memory and never the full contents.

## Requirements

Android 8 or newer.

## Installing

1. Download `VetNab.apk` and tap it.
2. If Android asks, allow installs from your browser for this one time.
3. Tap Install, then turn that setting back off.

## Verify your download

The file fingerprint (SHA-256) of the APK is:

```
d76fc9b54b89801d64871eb4fc48fbfa3b20f07492eb004da6b5bce32f8815f3
```

To check yours, run this in a terminal from the folder where you saved it:

```
sha256sum VetNab.apk
```

If the result matches, the file hasn't been tampered with. If it doesn't, don't install it.

## Why isn't it on the Play Store?

Google charges a fee to publish apps on Play, and I want VetNab to stay free for everyone, me included. So you get it straight from here: no store, no account, no cost.

## Limits

VetNab gives a risk score, not a guarantee. It can't catch every bad QR code, so treat it as a second pair of eyes.

---

Made by MonoZero.
