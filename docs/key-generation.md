# How per-device keys work

VidSecure's per-PC mode locks a video to one device without any server.

1. The viewer opens the file in the player. The player shows a **Hardware ID** — a
   unique fingerprint of their device.
2. They send you that Hardware ID.
3. In the Protector's **Generate Keys** tab, you paste their Hardware ID and your
   **encryption key**. It produces a **play key**.
4. You send the play key back. It only works on that one device.

- The same Hardware-ID → key flow works across **Windows and Android** because both
  players use identical cryptography.
- Enable **Hardware Swipe** when encrypting so a viewer's key keeps working after an
  OS reinstall or hardware change.
- For convenience, a single key or password can unlock a **whole batch** of videos.
