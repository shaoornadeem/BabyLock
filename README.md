# BabyLock 🎈🔒

[![Windows 10/11 Compatible](https://img.shields.io/badge/Platform-Windows%2010%20%7C%2011-0078D6.svg?logo=windows)](https://microsoft.com)
[![Rust](https://img.shields.io/badge/Language-Rust%202021-DEA584.svg?logo=rust)](https://www.rust-lang.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Privacy: 100% Offline](https://img.shields.io/badge/Privacy-100%25%20Offline%20%26%20Safe-success.svg)](#privacy--safety)
[![Audio: Hearing-Safe](https://img.shields.io/badge/Audio--Safe--12dBFS-brightgreen.svg)](#hearing-protection)

> **Tiny, ultra-safe Windows keyboard and mouse lock utility with educational phonics, acoustic sound effects, and cheerful voice pronunciations for toddlers.**

Protect your work, presentations, movies, and video calls from accidental keystrokes while transforming your PC into a delightful sensory playground for your child or pet!

---

## ✨ Features

### 🔒 Total Input Lockdown
- **Zero Input Leaks**: Safely swallows all keyboard keystrokes, mouse buttons, and scroll wheels.
- **Suppresses Windows Shortcuts**: Blocks disruptive system hotkeys including `Windows Key`, `Alt+Tab`, `Alt+F4`, `Ctrl+Esc`, and `Shift x 5` Sticky Keys.
- **Topmost Safety Overlay**: Displays a sleek, non-intrusive floating badge with unlock instructions without stealing window focus.

### 🎨 4 Interactive Play Modes
1. **Educational Phonics (A–Z & 0–9)**: High-contrast alphabet cards teaching early literacy with cheerful voice pronunciations.
2. **Animal & Vehicle Sounds**: Engaging pictures paired with authentic acoustic sounds (Duckling quack, Puppy bark, Steam train, and more).
3. **Pentatonic Musical Synthesizer**: 26-note harmonic scale featuring Xylophone, Piano, and Chimes. Guaranteed pleasant music with zero dissonance even under frantic typing!
4. **Sensory Rainbow Drawing**: Fluid rainbow trail following mouse movements with burst confetti stars and hearts.

### 🎙️ Cute Voice Styles
- Switch instantly between **Cute Little Girl** (bright & encouraging) and **Cute Little Boy** (cheerful & lively).
- Spoken words play concurrently with sound effects for multisensory learning.

### 🛡️ Fail-Safe Unlock Options (Never Get Locked Out)
- **Hold Chord (Default)**: Hold `U` + `K` simultaneously for 3 seconds.
- **Passphrase**: Type your custom word (e.g. `b-a-b-y`) anywhere.
- **Corner Escape**: Push the mouse cursor into the top-left corner for 5 seconds.
- **Auto-Unlock Timer**: Automatically restores input after 5, 15, or 30 minutes.

### 🔊 Hearing Protection
- Built-in **-12 dBFS soft audio limiter** protects toddler ears from sudden volume surges during energetic mashing.
- Selectable safe volume levels: Low (Safe), Medium, and High (Capped).

---

## 🔒 Privacy & Safety
- **100% Offline**: Zero analytics SDKs, zero cloud telemetry, and zero network calls.
- **No Keystroke Recording**: Key events are processed strictly in volatile memory and never saved to disk.
- **COPPA & Family Friendly**: Safe for children of all ages with zero third-party advertisements.

---

## 🚀 Installation & Distribution

### Standard Setup
Download the latest `BabyLock_Setup_v1.0.0.exe` installer from the **[Releases](../../releases)** page.

### Silent / Enterprise Install
```cmd
BabyLock_Setup_v1.0.0.exe /VERYSILENT /SUPPRESSMSGBOXES /NORESTART /SP-
