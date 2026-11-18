# AZVox

**Crystal-clear calls, fully offline.** AZVox removes background noise and other people's voices from your microphone in real time, for any calling app: Zoom, Discord, Microsoft Teams, Google Meet, Skype, OBS and more.

Everything runs on your own PC. **No audio ever leaves your device**, no account, no subscription, free.

Developed by **Art Midnight**.

---

## Download

👉 **[Download the latest AZVox for Windows](https://github.com/artmidnight/AZVox-releases/releases/latest)**: open the newest release and download `AZVox_x.y.z_x64-setup.exe` under **Assets**.

- Windows 10 or 11, 64-bit
- Works on any PC: no graphics card needed
- Installs for your user only (no administrator rights needed for the app itself)

> **Windows SmartScreen** may say "Windows protected your PC" because AZVox is new and not yet code-signed. Click **More info → Run anyway**.

AZVox updates itself: when a new version is out, the app shows **Update** or **Remind me later**. Click **Update** and AZVox downloads, installs and restarts on its own.

---

## Features

- **Noise removal**: fans, keyboards, traffic, dogs, roosters, cafés. Presets (Gentle, Balanced, Strong) plus a noise reduction slider up to **300%**: above 100% a second cleaning pass, above 200% the mic is also muted between your words.
- **Two engines**: *Lite* (almost no CPU) and *Quality* (DeepFilterNet, cleaner; one-time model download inside the app).
- **Reduce background voices**: lowers people talking farther away than you.
- **Your voice only**: learns your voice and mutes other voices (one-time model download).
- **Test my mic**: record yourself and compare *Original* vs *With AZVox* on the speaker or headset you choose, no setup needed.
- **Echo cancellation** and noise removal for the other callers' audio.
- Tray icon, **Ctrl+Alt+N** hotkey to flip noise removal, start with Windows.

---

## How to use

### How it works

AZVox sits between your real microphone and your call app. It cleans your voice and sends it to a **virtual microphone**, which you then select in your call app.

```
Your mic  →  AZVox  →  AZVox Clean Mic  →  Zoom / Discord / Teams / Meet
```

### Step 1 · Install AZVox

Run the downloaded `AZVox_..._x64-setup.exe` and follow the installer. AZVox opens when it's done.

**Just want to hear it first?** Click **Test my mic**, talk for 6 seconds with your usual background noise, then play **Original** and **With AZVox**. This works without any other setup.

### Step 2 · Get the virtual microphone (one time)

Most PCs don't have a virtual microphone yet. AZVox can set up the free **VB-Audio Virtual Cable** for you:

1. In AZVox, open **Calls & cable** in the sidebar and click **Get free virtual cable**.
2. Click **Yes** on the Windows permission prompt. VB-Audio's setup window opens: click **Install Driver**, then **OK**.
3. If AZVox asks, **restart your PC**, open AZVox again and click **Rename to AZVox Clean Mic**.
4. You now have two new audio devices:
   - **AZVox Clean Output**: AZVox sends your clean voice here (selected automatically).
   - **AZVox Clean Mic**: the microphone you choose in your call app.

VB-Audio Virtual Cable is donationware by VB-Audio Software ([vb-audio.com](https://vb-audio.com/Cable/)) and is not part of AZVox. Already have a virtual cable (VB-Cable, Virtual Audio Cable, VoiceMeeter)? Just pick it under **Send cleaned voice to**.

### Step 3 · Turn AZVox on

1. On **Home**, under **Devices**, set **Microphone you talk into** to your mic or headset.
2. Check **Send cleaned voice to** shows **AZVox Clean Output**.
3. Click the big **power button**. "Your mic" moves when you talk; "Callers hear" shows the cleaned sound.

### Step 4 · Pick the microphone in your call app

| App | Where |
|---|---|
| **Zoom** | Settings → Audio → Microphone → **AZVox Clean Mic**. Set "Background noise suppression" to **Low**. |
| **Discord** | User Settings → Voice & Video → Input Device → **AZVox Clean Mic**. Turn off Discord's noise suppression. |
| **Microsoft Teams** | Settings → Devices → Microphone → **AZVox Clean Mic** |
| **Google Meet** | ⋮ → Settings → Audio → Microphone → **AZVox Clean Mic** |
| **Anything else** | Choose **AZVox Clean Mic** wherever it asks for a microphone |

Leave your speakers/headphones setting as it is; AZVox only changes your microphone.

### Tips

- **Gentle** keeps your voice most natural, **Balanced** (100%) removes most noise, **Strong** (200%) adds a second cleaning pass. Drag the slider to **300%** to also mute dogs, roosters, horns and phones between your words. The **Quality** engine gives the cleanest result.
- Voice sounds thin, robotic, or words get cut? Lower the **Noise reduction** slider or choose **Gentle**.
- Other people's voices from a phone or TV: use **Your voice only** (Noise & voices → Learn my voice).
- **Ctrl+Alt+N** flips noise removal from any app, so you can compare during a call.
- Closing the window keeps AZVox running in the tray (bottom-right of the taskbar). Right-click the tray icon → **Quit AZVox** to exit.

### Troubleshooting

- **Callers can't hear me**: AZVox must be on (power button lit), and your call app must use **AZVox Clean Mic**, not your real microphone.
- **"Your mic" doesn't move**: pick the right microphone under Devices, and check Windows Settings → Privacy & security → Microphone → *Let desktop apps access your microphone*.
- **No microphone found**: plug in a mic or headset; AZVox detects it automatically.
- **Robotic voice**: choose Gentle or lower the slider.

---

## Privacy

All audio processing happens on your PC. AZVox never uploads audio and has no telemetry. It only goes online to check for AZVox updates and, when you ask for them, to download the optional models and the virtual cable.

## Support

Need help, found a bug, or have an idea? Want a **custom app or automation** for your work or business?
📧 **devartmidnight@gmail.com**

---

AZVox is free to use but not open source. Copyright © 2026 Art Midnight. All rights reserved. This repository only hosts installers and update information.
