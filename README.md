# TapTap Revive 🎄

**Keep your Asante TapTap light show box working, now that the Asante app and cloud are gone.**

## 🛑 Don't throw your TapTap away. It still works.

**Asante's app and cloud are gone, but the box isn't broken.** We tested one on November 4, 2026: it still
joined home Wi-Fi, and a computer on the same Wi-Fi turned the lights on and off **with no app, no account
and no internet**.

**If you have a TapTap in a closet or a donation pile, keep it.** Here's what still works:

- ✅ The box joins your Wi-Fi and listens for commands
- ✅ Live light control, outlet by outlet, from a computer or phone on your Wi-Fi
- ✅ Light shows synced to music, with the music playing from **any speaker you like**
  (Bluetooth, a plug-in speaker, or an FM transmitter for a drive-by show)
- ❌ Saving new songs onto the box itself, so it plays with no computer running (we're working on it)

> 🚧 **Status: in development — first test version coming soon.**
> Click **Watch → Custom → Releases** (top right) to get notified when it's ready.
> Have a TapTap? [Open an issue](../../issues) and tell us your model. We'd love more testers.

## What happened

On **February 28, 2026** Asante shut down all of its cloud services. The TapTap app can no longer log in,
and the *Light Show Creator* stopped working.

**The boxes themselves are fine.** They still join your home Wi-Fi and listen for commands. Asante's cloud
was only used for logging in and for delivering new shows to the box. Live light control and playback
work over your home network, with no internet involved.

**TapTap Revive** is a free, open-source replacement app that talks to your TapTap directly over your home
Wi-Fi, with **no account, no login and no cloud**.

## ✅ Confirmed on a real TapTap (November 4, 2026)

We tested a 1st-gen TapTap on a home network, months after the cloud shutdown:

- The box **still joins home Wi-Fi** on its own after power-up.
- **Live light control works with no cloud.** We turned outlets on and off from a computer on the same
  Wi-Fi, and the lights followed every command.
- **Full brightness is level `80`.** The box ignored `90`, so anything that sends `90` for "full on" will
  look broken.
- The box has its own built-in control page (it calls it *Jamboree Amigo!*). Its pads only react to
  **finger taps on a touch screen**, not mouse clicks, so on a computer it can look like it does nothing.
- The box makes **no clicking sound** when it switches. That's normal: it dims lights electronically.
  Plug in a light to test it, and don't listen for a click.

**Not working yet:** putting **new songs and shows onto the box** so it plays with no computer running.
The box used to download those from Asante's cloud. Until that's solved, a computer or spare phone on
your Wi-Fi runs the show live, and the music plays from **any speaker you like**.

## The plan

**Classic mode (default):** looks and works like the TapTap app you know, so there's nothing new to learn.
- My Projects, Light Show Creator, the 6-channel editor, Player, Live Show, Party Mode and Schedule
- **Opens and plays your existing TapTap shows**, in the original show format
- Works on PC and Mac, and on your iPhone or Android phone over home Wi-Fi

**Studio mode (optional switch):** extra features for people who want more.
- Tap along on the keyboard (A S D F G H) and have it **cleaned up onto the beat**
- **Compose from the music**: listens to the song's notes and builds a show
- Song sections (build one chorus, copy it to all of them), a stage view on a photo of your house, playlists
- Mix several boxes in one show: TapTap + ShowBox + WLED RGB strips

## Supported devices

| Device | Status |
|---|---|
| Asante TapTap (1st gen) | 🟢 **Live light control confirmed on real hardware.** Storing new shows on the box: not yet |
| Asante TapTap II | 🟡 Same system as 1st gen, **testers wanted** |
| Asante TapTap 3 | 🔴 Uses a different system, **being worked on** |

## Help wanted

**Own a TapTap, TapTap II or TapTap 3?** Open an [issue](../../issues) and say which model you have.
You'll be first to try it, and testing takes about 5 minutes.

## Legal

Independent, open-source project. **Not affiliated with or endorsed by Asante.** "Asante" and "TapTap"
are trademarks of their owners and are used only to say which devices this works with.
No Asante code, images or files are included. MIT licensed, see [LICENSE](LICENSE).

---

*Search keywords: Asante TapTap app not working, TapTap app replacement, TapTap Light Show Creator
not working, TapTap login error, Asante cloud shut down, Asante TapTap II, Asante TapTap 3,
Christmas light show box, light show to music controller.*
