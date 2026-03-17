# SpeakForMe

A single-file offline web app for non-verbal communication in hospital settings, designed for use on iPhone via Safari.

## Features

- **Quick-tap phrase buttons** — pre-defined phrases spoken aloud via text-to-speech
- **Pain scale** — 0–10 visual scale with spoken output
- **Letter grid** — spell out custom words letter by letter; tap "Antippen zum Buchstabieren" to jump directly to the grid
- **Clear button** — × button appears in the input field whenever there is text, clearing it in one tap
- **Customizable buttons** — long-press any button to enter edit mode; add, edit, or delete buttons
- **Share configuration** — export your custom button layout as a URL
- **ElevenLabs TTS** — connect an ElevenLabs API key for high-quality AI voices; preferred voice is remembered across sessions
- **Multi-language** — DE, EN, ES, ZH, AR, HI
- **Offline capable** — add to home screen via Safari → Share → Add to Home Screen

## Usage

Open in Safari on iPhone. No server or internet connection required after the first load.

### Edit Mode

Tap **✎ Bearbeiten** in the footer or long-press any button to enter edit mode. The page stays at your current scroll position when entering and leaving edit mode.

In edit mode the **Vorlesen** button is replaced by a **Teilen** button to share your configuration.

## Install to Home Screen (iOS)

1. Open in Safari
2. Tap the Share icon
3. Select "Add to Home Screen"

## Live

https://smon1127.github.io/speakforme/
