# VidSecure Protector — Windows Guide

The Protector is where you encrypt videos, set rules, build players, and generate keys.

## Install
1. Download `VidSecure-Setup.exe` from the [Releases page](../../../releases/latest).
2. Run it and follow the installer. Launch **VidSecure Protector** from the Start menu.

## 1. Encrypt a video
1. Go to **Encrypt Video**.
2. (Optional) enter a course name.
3. Enter an **encryption key** (remember it — it is required to generate keys later).
4. Add your video(s) and pick a custom file extension (e.g. `vdx`).
5. Choose a protection mode:
   - **Per-PC** — locked to each viewer's device (you issue a key per device).
   - **Fixed password** — a single password unlocks the file on any device.
6. Click **Encrypt**. You get `.vdx` file(s).

## 2. Set the rules (Security tab)
Toggle anti-capture, anti-record, anti-VM/RDP, expiry date, play-count, hardware
swipe, and internet policy (require ON / OFF / either). These are stored **inside
each encrypted file at the moment you Encrypt**, so set them first.

## 3. Build your player
On **Player Generation**, set your app name, icon, colour, logo, splash, watermark,
notice text and pop-ups, then:
- **Build Player (.exe only)** → a ready-to-run folder on your Desktop, or
- **Build Setup Installer** → a single `Setup.exe` to hand to customers.

> Tip: to build installers automatically, put Inno Setup's files in a `setup` folder
> next to the Protector, or install Inno Setup 6.

## 4. Generate keys
On **Generate Keys**, paste the viewer's **Hardware ID** (shown in their player) and
your encryption key → copy the generated **play key** and send it to them.

## 5. Records
The **Records** tab keeps an encrypted, machine-locked log of everything you've
encrypted and every key you've generated. You can search, copy, delete, and export
to PDF. The log only opens on the computer that created it.
