<p align="center"><img src="images/icon.png" width="128" alt="AI Pro icon"></p>

<h1 align="center">AI Pro</h1>

<p align="center">Select anything on your screen, then copy, translate, search, scan or save it.<br>An Android screen-select assistant in the spirit of Samsung's Smart Select and Circle to Search.</p>

<p align="center"><a href="https://github.com/chinmays-tanx09/ai-pro/releases/latest"><b>Download the latest APK</b></a></p>

## Features

- **Select on screen**: draw a box, a lasso or a line, or tap a card or image to select its whole shape. Text is selected word by word.
- **Act on the selection**: copy (text or a partial screenshot), translate, share, search the selected words, pin it on screen, save it, or make a GIF.
- **On-device text recognition (OCR)** for English and Indian languages: Hindi, Kannada, Marathi, Tamil, Telugu, Malayalam, Gujarati and Bengali.
- **Translate** with on-device language packs, plus **Live translate**: a see-through overlay that re-translates as you scroll.
- **Identify**: on-device guesses for an object you circle; select several and identify them all, or ask about them in Google's AI Mode.
- **Smart actions**: chips for phone numbers, e-mail, links, dates, addresses and UPI IDs.
- **QR and barcodes**: several codes at once, including Wi-Fi details.
- **More**: Song search, Scam check, "AI / edited?" hint, Shop this, Solve (maths), colour picker.
- **Read aloud**: natural sentences with offline voices per language (Hindi, Kannada, Tamil and more), speed and pitch, in a small floating pill.
- **Payment-app mode**: banking and UPI apps refuse to open while an accessibility service is on, so AI Pro switches itself off when one opens and comes back afterwards.
- No ads, no analytics, no telemetry. Monochrome light and dark themes.

## Install

1. Download `AI_Pro_v<version>.apk` from [Releases](https://github.com/chinmays-tanx09/ai-pro/releases/latest) and install it (allow "Install unknown apps" for your browser or file manager).
2. Open AI Pro and turn on its **accessibility service** when asked. Capture needs it.
3. Optional: set AI Pro as the **Digital assistant app** so a long-press on the home or side button opens it. You can also use the Quick Settings tile.

Needs Android 11 or newer on a 64-bit or 32-bit ARM phone (`arm64-v8a`, `armeabi-v7a`).

**Payment-app mode, optional:** to let AI Pro turn itself back on automatically after a payment app closes, grant this once from a computer:
```
adb shell pm grant com.aipro.select android.permission.WRITE_SECURE_SETTINGS
```
Without it, AI Pro shows a notification and an "AI Pro on" tile to turn it back on yourself.

## Verify your download

Package `com.aipro.select`. Every release APK is signed with the same certificate:

`SHA-256 cb7136c2fb74d43fdf00ce3c6e43f4e8935a9d2b8ff4c8e88956e8f201fe4631`

Each release lists the APK's SHA-256 in its notes.

## License

AI Pro is **not open source**. All rights reserved; see [LICENSE](LICENSE). This repository only hosts the official release APKs.
