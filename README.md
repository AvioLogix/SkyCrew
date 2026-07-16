<div align="center">

# ✈️ SkyCrew

### Flightdeck Utilities incl Voice Controlled Copilot

![Version](https://img.shields.io/badge/version-0.3.0-5c3fa1)
![Platform](https://img.shields.io/badge/platform-Windows%20x64-0078D6)
![Runs](https://img.shields.io/badge/AI%20Engine-100%25%20Local-2ecc71)
![License](https://img.shields.io/badge/license-Proprietary-626891)

<a href="https://aviologix.com/skycrew/download">
  <b>⬇️ Download the latest release</b>
</a>
<br>
<a href="https://discord.com/invite/ksQRq25Hcz" style="display: inline-flex; align-items: flex-end; text-decoration: none; color: inherit;">
  <img src="https://cdn3.emoji.gg/emojis/9738-discord-ico.png" 
       width="24" height="24" 
       style="margin-right: 8px;" 
       alt="discord_ico"> 
  <b>Join our Discord!</b>
</a>

</div>

> [!IMPORTANT]
> **SkyCrew is in early development (v0.3.0).** Some features may be incomplete, not work fully yet, or change significantly between releases. You're flying an early build — expect rapid changes, and thanks for being part of it! ✈️

---

## What is SkyCrew?

SkyCrew is a desktop companion app that turns your voice into cockpit actions inside **Microsoft Flight Simulator**. Instead of reaching for the mouse to find a switch mid-approach, you simply *talk to your copilot* — naturally, the way you would to a real first officer:

> *"Copilot, gear down."*
> *"Can you bring the flaps up, please."*
> *"Set the parking brake."*

Copilot hears you, understands what you meant, and performs the action in the sim — then gives you a short spoken confirmation so you can keep your eyes outside and your hands on the yoke.

---

## ✨ Key Features

- 🎙️ **Natural voice control** — speak conversationally; no rigid command syntax to memorize.
- 🧠 **Built-in AI brain** — a local language model interprets your *intent*, not just keywords.
- 🛩️ **Live aircraft dashboard** — real-time airspeed, altitude, heading, vertical speed, and more.
- ✈️ **Aircraft-specific profiles** — dedicated command mappings for each supported airframe, so the right cockpit input is sent for the aircraft you're actually flying. Currently covers the **Boeing 737 MAX 8 BBJ**, **Boeing 747-8i**, **iniBuilds Airbus A350-1000 / A350-900 / A350-900 ULR** (one shared cockpit profile), **PMDG 777-300ER**, **Cessna 172SP G1000**, **Cirrus SF50 Vision Jet**, **Cessna 208B Grand Caravan**, **Cessna 400 Corvalis**, **Diamond DA40 NG**, **Cessna Citation CJ4**, **Airbus A310**, **FlyByWire A380X**, **FlyByWire A32NX (A320neo)**, **iniBuilds A320neo V2 VIP**, **Beechcraft Bonanza G36** — the first retractable-gear GA single in the fleet —, **Beechcraft King Air 350**, and **Airbus A400M Cargo** — a four-engine turboprop, the largest aircraft in the fleet — with profile-aware command filtering that dims irrelevant commands in the UI (e.g. autothrottle on a fixed-gear single).
- 📋 **Interactive Checklists** — full Preflight/Inflight/Postflight checklists that load automatically for whatever you're flying (currently the **Cessna 172SP G1000** and the **iniBuilds A350 family**), with tick-off progress, per-checklist and reset-all buttons, and must-verify items highlighted.
- ⛽ **Optimize Fuel (C172SP, C400 Corvalis & Bonanza G36)** — "optimize fuel" or "lean the mixture" leans the mixture step by step to true peak RPM, working either direction, in the background without blocking other commands.
- 🔧 **Engine Feather (Beechcraft King Air 350)** — "optimize engine" or "feather the prop" hill-climbs both propeller levers together to the peak-RPM point, the same technique as Optimize Fuel for aircraft with prop/feather levers instead of a leanable mixture.
- 🕹️ **Monitor Speed (no-autothrottle aircraft)** — "monitor speed 250" / "maintain speed 210" holds a target airspeed by working the throttles for you, on the **Citation CJ4**, **Cessna 172SP**, **Cessna 400 Corvalis**, **Cessna 208B Grand Caravan**, **Diamond DA40 NG**, **Beechcraft Bonanza G36**, and **Beechcraft King Air 350** (plus the **Cirrus SF50 Vision Jet** as a manual-autothrottle-off fallback). It anticipates each airframe's own throttle response, easing off before the speed arrives instead of chasing it, settling within 1–3 knots and holding steady — say "stop speed monitoring" any time to take the throttles back.
- 🎚️ **Live voice-sensitivity sliders** — adjust the background noise gate, minimum speech length, and silence-before-processing thresholds in Settings, applied instantly with no restart.
- 🎛️ **Full autopilot control** — heading, altitude, vertical speed, LNAV, localizer, approach, level change, speed, and autothrottle arm/speed hold by voice. VNAV is available on the A350, A320neo V2 VIP, 747-8i, Bonanza G36, and King Air 350; A350 pilots also get Open Descent and Open Climb via FCU knob pulls.
- ⚡ **Optional GPU acceleration** — with a compatible NVIDIA/AMD/Intel GPU and spare video memory, Copilot loads a larger, sharper voice model on your graphics card, automatically stepping down if the simulator needs the memory back. A **VRAM Safety Margin** slider in Settings lets you decide exactly how much headroom to always leave for the sim.
- 🔔 **Automatic altimeter reminders** — Copilot speaks up when you cross the transition altitude climbing or descending, so you never miss a baro switch.
- 🔇 **Echo-free conversations** — the microphone automatically pauses for the exact length of Copilot's own spoken reply, so it can never hear (and act on) itself.
- 🔊 **Spoken confirmations** — every action is read back so you always know it was heard.
- 💬 **SkyChat** — open the built-in LLaMA AI as a standalone chat window directly from the app header for quick lookups, aircraft questions, or general conversation.
- ⚙️ **Customizable settings** — adjust Copilot's volume, switch between voice-activation and push-to-talk, and configure regional transition altitudes to match where you fly.
- 🔐 **AvioLogix account sign-in** — sign in with your AvioLogix account (the same one used for the dashboard) to launch SkyCrew; SkyCrew securely remembers your session between launches.
- 🔒 **AI runs 100% locally** — voice, transcripts, prompts, and flight data are processed entirely on your machine and never leave it. No telemetry, no analytics, no cloud AI. The only network calls SkyCrew makes are signing in to your AvioLogix account and checking for app updates.
- 🚀 **Auto-updating** — new versions install themselves seamlessly in the background.
- 🪟 **One-click installer** — a single Windows setup file; no dependencies to hunt down.

---

## ⬇️ Download & Installation

1. Head to the **[Download page](https://aviologix.com/skycrew/download)**.
2. Download the latest **`SkyCrew-Setup-x.x.x.exe`** installer.
3. Run it. The installer sets up a Start Menu and desktop shortcut automatically.
4. Launch **SkyCrew**, start Microsoft Flight Simulator, and you're ready to fly.

> 💡 From here on, SkyCrew keeps itself up to date — when a new version is released, it downloads and installs in the background with a visible progress indicator. You'll always be on the latest build without lifting a finger.

**No additional software or runtimes need to be installed separately** — everything Copilot needs is bundled inside the app, except for the voice/AI models themselves. Those (a few GB) download automatically and only once, the very first time you launch SkyCrew after installing — you'll see a real download progress bar on the splash screen. This keeps the installer itself small and fast to download. If that first-run download ever fails (no internet, a firewall, etc.), see [Manual Model Download](#-manual-model-download) below.

---

## 📦 Manual Model Download

If the automatic first-run download fails, or you'd rather grab the models yourself:

1. Download **[Models.zip](https://drive.google.com/file/d/1F9vItLrBNCclTdfOBY7-HaVPOZTDIvJv/view?usp=sharing)** (~3 GB).
2. Extract it directly into your SkyCrew **userData** models folder: `%APPDATA%\SkyCrew\models\` (create the `models` folder if it isn't there yet).
3. You should end up with these four files sitting directly in that folder: `Llama-3.2-1B-Instruct-Q4_K_M.gguf`, `Llama-3.2-3B-Instruct-Q4_K_M.gguf`, `ggml-small.en.bin`, `ggml-silero-v6.2.0.bin`.
4. Restart SkyCrew — it'll find the files already in place and skip straight to normal startup.

---

## 🎧 How To Use It

1. **Start SkyCrew** and **Microsoft Flight Simulator**. The dashboard shows a green **Online** indicator once it's linked to the sim.
2. **Just talk.** Copilot is always listening in the background, but it only acts when you include an *activation phrase* so it won't react to ATC chatter or cabin conversation.
3. Activation phrases are intentionally natural — things like **"copilot"**, **"computer"**, **"can you…"**, **"please…"**, or **"set…"**. So all of these work:
   - *"Copilot, gear up."*
   - *"Can you lower the flaps?"*
   - *"Please set the parking brake."*

### Currently supported commands

| Command | Example phrasings |
|---|---|
| **Gear Down** | "gear down", "lower the gear", "wheels down" |
| **Gear Up** | "gear up", "retract the gear", "wheels up" |
| **Flaps Down** | "flaps down", "deploy flaps", "lower the flaps" |
| **Flaps Up** | "flaps up", "retract flaps", "raise the flaps" |
| **Flaps 1** *(A350, A380X, A32NX, A310, PMDG 777, A320neo VIP, 747-8i & A400M Cargo)* | "flaps one" |
| **Flaps 2 / 3** *(A350, A380X, A32NX, A320neo VIP & A400M Cargo; A310 has 1/2 only)* | "flaps two", "flaps three" |
| **Flaps 4** *(A400M Cargo only)* | "flaps four" |
| **Flaps Full** *(Airbus-family aircraft)* | "flaps full", "flaps down" |
| **Flaps 5 / 15 / 25** *(PMDG 777 has all three; 747-8i has 5/25; King Air 350 has 15 as its approach setting; A400M Cargo has 5 as its full-flaps detent)* | "flaps five", "flaps fifteen", "flaps twenty-five" |
| **Flaps 10°** *(C172SP, C208B, 747-8i & Bonanza G36)* | "flaps 10" |
| **Flaps 20°** *(C172SP, C208B, 747-8i & PMDG 777)* | "flaps 20" |
| **Flaps 30°** | "flaps 30" (same as "flaps down" on most airframes; a distinct literal command on the PMDG 777) |
| **Flaps 35°** *(Beechcraft King Air 350 only — full flaps)* | "flaps 35" |
| **Optimize Fuel** *(C172SP, C400 Corvalis & Bonanza G36 only)* | "optimize fuel", "lean the mixture" |
| **Engine Feather** *(Beechcraft King Air 350 only)* | "optimize engine", "feather the prop" |
| **Open Descent / Open Climb** *(A350 & A320neo VIP only)* | "open descent"/"OP DES", "open climb"/"OP CLB" |
| **VNAV** *(A350, A320neo VIP, 747-8i, Bonanza G36 & King Air 350 only)* | "engage VNAV", "vertical navigation" |
| **Parking Brake Set / Release** | "set parking brake", "apply the brakes", "release parking brake", "release the brakes" |
| **Set Heading** | "set heading 251", "turn heading 030", "fly heading 180" |
| **Engage Heading Hold** | "engage heading hold", "hold heading", "activate heading hold" |
| **Autopilot On / Off** | "autopilot on", "engage autopilot", "autopilot off", "disengage autopilot" |
| **Set Altitude** | "set altitude 210", "descend and maintain 5000 feet", "climb and maintain flight level 350", "set altitude five thousand", "set altitude twenty-five hundred" |
| **Engage Altitude Hold** | "engage altitude hold", "hold altitude", "capture the altitude" |
| **Set Vertical Speed** | "set vertical speed 1500", "vertical speed minus 1000", "descend at vertical speed 800" |
| **Engage Vertical Speed Mode** | "engage vertical speed", "vertical speed mode", "hold vertical speed" |
| **Lateral Navigation (LNAV)** | "engage LNAV", "activate lateral navigation", "follow the flight plan" |
| **Localizer (LOC)** | "engage the localizer", "capture the localizer", "arm the localizer" |
| **Approach (APP)** | "arm approach", "engage approach mode", "activate approach" |
| **Level Change (FLC)** | "engage level change", "activate level change", "flight level change mode", "flight level change please", "level change please" |
| **Set Speed** | "set speed 250", "select airspeed two five zero", "set the airspeed to 280" |
| **Arm / Disarm Autothrottle** | "arm the autothrottle", "engage the autothrottle", "disarm the autothrottle", "turn off the autothrottle" |
| **Engage Speed Hold** | "speed hold", "engage speed mode", "activate speed hold" (arms the autothrottle first if it isn't already) |
| **Monitor Speed** *(CJ4, C172SP, C400 Corvalis, C208B, DA40 NG, Bonanza G36, King Air 350; Vision Jet as a fallback)* | "monitor speed 250", "maintain speed 210", "monitor the airspeed" — holds the target by working the throttles; "stop speed monitoring" to end |

> [!NOTE]
> Commands marked with a specific aircraft list only take effect on those profiles — an unsupported command on your current airframe responds "Command Unavailable" instead of doing nothing or firing the wrong system, and the in-app **Commands** page dims it automatically. The standard **Flaps Down / Flaps Up** always work for a quick full-travel move on every airframe; the numbered detents above give precise control of each individual lever position where that airframe actually has one. On Airbus-family FCUs, **Open Descent**, **Open Climb**, and **VNAV** act on the altitude knob itself — pull for Open Descent/Climb, push for VNAV — mirroring the physical gesture you'd make in the cockpit; on the 747-8i and Bonanza G36, VNAV is its own dedicated FCU button instead.

Each command understands many natural variations — the examples above are just a taste. The in-app **Commands** tab lists every phrase for each action, and the command set is actively growing release over release.

---

## 📊 The Live Aircraft Dashboard

The **Copilot** tab is a real-time glass panel fed directly by the simulator, refreshing several times a second:

- **Aircraft identity** — the current airframe's name and type, with a live connection indicator.
- **Primary instruments** — airspeed, altitude, heading, and vertical speed (with a climb/descent trend indicator).
- **True ground distance** — the altitude tile shows your real height above the terrain below you, accurate no matter how the altimeter is set.
- **System states** — landing gear, landing lights, parking brake, autopilot, and flaps.
- **Altimeter setting** — shown in both **inHg** and **hPa**, so it reads correctly no matter which region's procedures you fly.
- **Altimeter transition reminder** — triggers "SET STD" or "SET local pressure" alarms based on flight altitude and your region's configured transition altitude (see "Settings & Customization" below).
- **Speed limit warning** — displays custom visual and vocal alerts for exceeding 250 kts below 10,000 ft.
- **Landing lights reminder** — warns when landing lights are off below 10,000 ft or still active above 10,000 ft.
- **Autopilot Configuration panel** — every selector and mode (HDG, LNAV, FLC, ALT, V/S, LOC, APP, SPD, autothrottle) lit up live when it's engaged, with the selected target values shown alongside.
- **Weather, Airport & Runway panel** — live wind, temperature, QNH and visibility; the head/crosswind component for a landing on your current heading; the nearest airport's ICAO code, elevation, distance and bearing; and your tuned COM/NAV radios and ILS details.

This gives you an at-a-glance overview of your aircraft without digging through cockpit menus — and it lays the groundwork for smarter, aircraft-aware commands in future updates.

---

## ⚙️ Settings & Customization

A dedicated **Settings** tab lets you tailor Copilot to how you fly, with every choice saved automatically on your PC:

- **Copilot Volume** — a slider for the voice and interface sound volume, applied live as you drag.
- **Listening Mode** — stick with continuous voice activation, or switch to **push-to-talk** and bind any key: press once to arm a single command, no wake word needed.
- **Remember App Position** — reopens the window at the size, position, and monitor you last used.
- **Transition Altitude Zones** — the altitude where you switch between local pressure and standard (1013 hPa / 29.92 inHg) varies by region. Configure it per zone with simple sliders (1,000 ft steps) — Default (Europe & anywhere unrecognized), North America, and Japan ship as examples, each independently adjustable to match real-world or custom procedures.

---

## ⚙️ How It Works (Under the Hood)

SkyCrew is a self-contained pipeline that takes raw microphone audio and turns it into a precise simulator action — all locally. At a high level, a spoken command travels through several stages:

1. **🎙️ Audio capture** — your voice is captured at the system level through an embedded, high-performance audio engine and normalized for speech processing. No external audio tools or driver setup required.

2. **🗣️ Speech detection** — rather than naively reacting to volume, a dedicated voice-activity model distinguishes genuine speech from background engine and cabin noise, so Copilot knows exactly when you start and stop talking.

3. **🔑 Activation gating** — before anything is interpreted, the sentence has to contain one of a broad, deliberately natural set of activation phrases. If none are present, the input is dropped immediately and never reaches the AI — so idle conversation, ATC, and cabin chatter never trigger an action.

4. **📝 Speech-to-text** — your words are transcribed by a built-in speech-recognition model that runs as a persistent, always-warm background service. Keeping it loaded between commands (instead of spinning it up each time) is a big part of why responses feel near-instant rather than laggy.

5. **🧠 Intent interpretation** — the transcribed text is handed to a compact, locally-run language model that works out what you actually *meant* and maps it onto one of your real, configured commands. This is where most of Copilot's engineering lives: the model's output is tightly constrained so it can only ever return a genuine command (or "unknown"), and additional validation layers independently sanity-check the result — for instance, catching cases where a control might otherwise be moved in the opposite direction to what you asked, or where two similarly-worded commands (like the autothrottle and the autopilot) could be confused for one another. Anything the system isn't confident enough about is quietly ignored rather than risking the wrong input.

6. **🎮 Execution** — the confirmed command is sent to Microsoft Flight Simulator through its **official SimConnect interface** — the same channel professional add-ons use. It sets the native simulator variable directly, exactly as if you'd moved the control yourself, so each aircraft's own systems and operating limits still apply.

7. **🔊 Confirmation** — a short spoken cue plays so you know the action was heard and carried out, without ever needing to glance away from the windscreen. The microphone is automatically paused for exactly as long as that reply takes to play, measured from the actual audio clip rather than guessed — so Copilot's own voice can never be picked back up and misread as your next command.

Alongside this command pipeline, SkyCrew keeps a separate, always-on link to the simulator that feeds the **live aircraft dashboard** and will power increasingly aircraft-aware behavior over time. Both connections re-establish themselves automatically if the simulator restarts or a flight is reloaded, so you rarely have to think about them.

### Technology at a glance

SkyCrew is an **Electron**-based Windows application that bundles a **local large language model** for reasoning, an **on-device speech-recognition engine** for transcription, a **neural voice-activity detector**, and a native **SimConnect** bridge to the simulator. The models are quantized and tuned to run efficiently on everyday gaming hardware, entirely offline.

> ℹ️ *SkyCrew is in active early development. The finer details of our prompt design, model tuning, reliability safeguards, and command-matching logic are part of what makes Copilot dependable — so while this overview explains the architecture, some of the secret sauce stays in the cockpit.* 😉

---

## 🔒 Privacy & Local AI Guarantee

**SkyCrew's AI and voice pipeline run entirely on your machine.**

- ✅ **The language model, the speech engine, and the voice detector never touch the internet.** All command interpretation happens locally, in real time, on your own hardware.
- ✅ **Your voice, transcripts, prompts, and flight data are never collected, transmitted, or stored anywhere but your computer.** There are no analytics and no cloud AI services.
- ✅ Audio is processed in-the-moment and discarded — it is not logged or retained.
- ✅ SkyCrew does make a small number of network calls that are **not** part of the AI pipeline: signing in with your AvioLogix account (the same account used for the AvioLogix dashboard) and SkyCrew's built-in auto-updater checking for new releases. Your email/callsign and session credentials are sent to AvioLogix's servers only to authenticate you — never your voice, transcripts, prompts, or flight data.
- ✅ Every AI feature is fully self-contained and used strictly to power the application's core functionality.

In short: what happens in your cockpit stays in your cockpit — signing in is the one exception, and it never touches the AI pipeline.

---

## 💻 System Requirements

- **OS:** Windows 10 / 11 (64-bit)
- **Simulator:** Microsoft Flight Simulator, connected via SimConnect
- **Microphone:** any working input device
- **Hardware:** a typical flight-sim-capable PC; the AI runs comfortably alongside the simulator on everyday gaming hardware

---

## ⚠️ Disclaimer

SkyCrew is an independent, fan-made tool and is **not affiliated with, endorsed by, or associated with Microsoft, Asobo Studio, or any aircraft manufacturer.** It sends the same control inputs you could send yourself, so it remains bound by each aircraft's own flight model and operating limits. Always fly responsibly and treat Copilot as an assistant, not a replacement for pilot judgment.

---

**Made with ❤️ for the flight sim community by [DevDokus](https://github.com/DevDokus)**

<a href="https://aviologix.com/skycrew/download">
  <b>⬇️ Download the latest release</b>
</a>
<br>
<a href="https://discord.com/invite/ksQRq25Hcz" style="display: inline-flex; align-items: flex-end; text-decoration: none; color: inherit;">
  <img src="https://cdn3.emoji.gg/emojis/9738-discord-ico.png" 
       width="24" height="24" 
       style="margin-right: 8px;" 
       alt="discord_ico"> 
  <b>Join our Discord!</b>
</a>

---

## 📜 Full Changelog

<details>
<summary>Click to expand full history</summary>

### v0.3.0
- **New Aircraft — Beechcraft King Air 350:** The default MSFS King Air 350 is now supported. Commands cover its autopilot (heading, altitude, and vertical speed selection, heading hold, NAV, approach, level change, altitude hold, and VNAV), retractable gear, and full flap control ("flaps up", "flaps 15", or "flaps 35" for full flaps). "Optimize engine" (or "feather the prop") hill-climbs both propeller levers together to peak RPM — this aircraft's equivalent of Optimize Fuel, since it has no leanable mixture. "Monitor speed [X]" holds a target airspeed with the throttles, since this twin turboprop has no autothrottle. Its autopilot disconnect bar latches out when pulled — Copilot automatically pushes it back in before re-engaging, matching the real aircraft's own procedure.
- **New Aircraft — Airbus A400M Cargo:** The default MSFS Airbus A400M Atlas (a four-engine turboprop cargo aircraft) is now supported. Commands fly its Airbus-style FCU: heading, altitude, speed, and vertical-speed selection, plus heading select, managed NAV, selected-speed, and vertical-speed modes. Retractable gear and a six-position flap lever ("flaps up", "flaps 1/2/3/4", and "flaps 5"/"flaps full"). Autopilot on/off via the AP1 channel. This aircraft's autothrottle currently can't be reliably armed, disarmed, or held by voice — a limitation in the add-on itself, not something SkyCrew can work around yet — and altitude hold, localizer, and approach mode remain unavailable on this airframe for the same reason, rather than risk acting on the wrong control.

### v0.2.9
- **New Aircraft — Boeing 747-8i:** The default MSFS 2024 Boeing 747-8i is now fully supported. Commands are wired to its real FCU: heading, altitude, speed and vertical-speed selectors, LNAV/VNAV/HDG SEL/V·S/LOC/APP/Level Change/Speed Hold mode engagement, autopilot engage and disconnect (including the AP disconnect bar's real latch interlock — it must be pushed back in before re-engaging, matching the physical switch), autothrottle arm/disarm, landing gear, parking brake, and every flap detent (1, 5, 10, 20, 25, 30).
- **New Aircraft — Beechcraft Bonanza G36:** The default MSFS 2024 Bonanza G36 is now supported — the first piston single in the fleet with real retractable gear. Commands cover its Garmin G1000 autopilot (heading, altitude, speed, vertical speed, heading hold, NAV, approach, level change, altitude hold, and VNAV), gear up/down, a two-position flap schedule ("flaps 10" for the approach setting, "flaps down"/"flaps 30" for full), Optimize Fuel (lean-to-peak mixture), and Monitor Speed (this airframe has no factory autothrottle).
- **iniBuilds A350-900 & A350-900 ULR Promoted to Supported:** These share the A350-1000's cockpit systems and now carry the same dedicated profile, tags, and full checklist set on the Supported Aircraft page.
- **Stay Signed In on the App and Dashboard Together:** Signing in to the website no longer logs you out of the app — each now keeps its own session, so you can be signed in to both at once. Your account still can't be spread across more than one app login and one dashboard login at a time.
- **Supported-Aircraft List Corrections:** The FlyByWire A32NX, FlyByWire A380X, and iniBuilds A320neo V2 VIP are now correctly shown as Supported — these aircraft already worked, only the list itself was out of date.

### v0.2.8
- **New Aircraft — iniBuilds A320neo V2 VIP:** The stock MSFS 2024 "A320neo V2 VIP," built on iniBuilds' study-level systems, is now supported. Commands are wired to its real FCU: heading, altitude, speed and vertical speed selection, HDG/NAV and altitude/speed mode engagement, localizer and approach capture, autopilot and autothrust, landing gear, flaps 1/2/3/up/down, and the parking brake. Setting a value updates the real FCU display, not just an internal target. One known gap: the real A320's FCU has no standalone "ALT hold" button at all — the Commands page shows it grayed out.

### v0.2.7
- **New Aircraft — FlyByWire A380X:** Full FCU-wired support: heading, altitude, speed and vertical speed selection, mode engagement (HDG/NAV, level change, open climb/descent, VNAV, speed hold, vertical speed, localizer, approach), autopilot and autothrust, landing gear, all five flap detents, and the parking brake. The standalone FCU "ALT" hold button has no effect on this airframe (confirmed non-functional in the addon itself, not a SkyCrew limitation).
- **New Aircraft — FlyByWire A32NX (A320neo):** Same full FCU-wired command set as the A380X above. Same "ALT hold" gap — the real A320's FCU has no standalone button for it.
- **PMDG 777-300ER — Full Flap Lever Support:** Every detent now works by voice — "flaps 1", "flaps 5", "flaps 15", "flaps 20", "flaps 25" each move the lever straight to that exact position, alongside "flaps up"/"flaps down". "Flaps 30" is now its own command distinct from "flaps down", matching how crews actually call out that detent.

### v0.2.6
- **New Aircraft — Airbus A310:** The stock MSFS 2024 Airbus A310 is now supported — autopilot modes (altitude hold, level change, NAV, approach, localizer), FCU selectors, landing gear, flaps (0/15/20/full), and the parking brake all work by voice, including altitudes with hundreds like 12,500 ft. The three-position gear lever is handled correctly: "gear down"/"gear up" always reach the fully up/down position, and repeating a command that's already satisfied does nothing.
- **"Monitor Speed" Extended to Five More Aircraft:** The Citation CJ4's automatic speed-hold-by-throttle command now also works on the **Cessna 172 Skyhawk**, **Cessna 400 Corvalis**, **Cessna 208B Grand Caravan**, **Diamond DA40 NG**, and (as a manual-autothrottle-off fallback) the **Cirrus SF50 Vision Jet** — each with its own live-tuned, non-oscillating control logic for that airframe's engine/prop type.
- **More Reliable "Game Status" Indicator:** Fixed a bug where the status pill could stay stuck on "Offline" for a whole session if the simulator was already running when SkyCrew launched, even though the connection was fine underneath.
- **Fixed: "70" Sometimes Misheard as "17":** Speech recognition would occasionally mishear "seventy" as "seventeen" for a spoken speed; since 17 knots is never a realistic target, SkyCrew now recognizes and corrects this specific mix-up automatically instead of ignoring the command.

### v0.2.5
- **AvioLogix Account Login:** SkyCrew now opens with a sign-in screen. Use the same email/callsign and password as your AvioLogix dashboard account — one account works everywhere.
- **New Pilot? Register on the Website:** Selecting "Register" opens the AvioLogix sign-up page in your browser. Once your account is created, come back and sign in here.
- **Stay Signed In:** SkyCrew securely remembers your session between launches, so you won't need to sign in every time you open the app.

### v0.2.4
- **Automatic Speed Hold on the Citation CJ4 ("Monitor Speed"):** The CJ4 has no autothrottle, so the Copilot can now hold a target airspeed by working the throttles itself. Say *"monitor speed 250"* or *"maintain speed 210"* and it anticipates the jet's slow spool-up — easing the throttles off *before* the speed arrives rather than chasing it — so it settles within 1–3 knots of the target and holds steady, instead of hunting back and forth (flight-tuned). Say *"monitor speed"* with no number and it asks you for the target; say *"stop speed monitoring"* any time to take the throttles back yourself.
- **Commands That Match Your Aircraft:** Commands an aircraft doesn't have now clearly respond **"Command Unavailable"** instead of doing nothing or firing the wrong system. On the CJ4 this covers the localizer, autothrottle, and Airbus-style flap detents; a "navigation mode"/VNAV request is correctly handled as LNAV (the CJ4 flies its lateral path through LNAV).
- **More Varied Copilot Voice:** The Copilot now detects how many voice clips exist for each command and picks from all of them, instead of assuming a fixed number — so commands with more recordings sound more varied and none go unused.

### v0.2.3
- **Under the Hood — Aircraft Profiles Reorganized:** Each supported aircraft's voice-command mapping now lives in its own self-contained module, so fine-tuning one airframe can no longer have any side effect on another. No change to how anything works — every command behaves exactly as before.
- **PMDG 777 Heading Fixes:** "Set heading" now dials the value into the MCP window and pushes the HDG SEL switch, matching the real aircraft's control flow. "Heading hold" now simply engages HDG HOLD instead of incorrectly trying to select a heading first.
- **Cessna 400 Corvalis — Altitude Preselect Fixed:** "Set altitude" now reliably dials in the target altitude, resolving a long-standing issue where the preselect display could get stuck or fail to update.
- **Supported Aircraft List — New "Checklist" Tag:** The Supported Aircraft popup now flags which airframes have a full interactive checklist set with a cyan **Checklist** tag — currently the iniBuilds Airbus A350-1000 and the Cessna 172 Skyhawk G1000.

### v0.2.2
- **Six New Supported Aircraft:** Full voice-command profiles added for the **PMDG 777-300ER**, **Cirrus SF50 Vision Jet**, **Cessna 208B Grand Caravan** (incl. floats), **Cessna 400 Corvalis**, **Diamond DA40 NG**, and **Cessna Citation CJ4** — each with commands automatically filtered to what that airframe actually has fitted.
- **PMDG 777 Fixes:** Gear lever now lowers correctly in flight; autothrottle engage now waits the few seconds the real aircraft needs after arming; "autopilot off" now silences the disconnect warning automatically; parking-brake release now simulates toe-brake pressure, matching this aircraft's real ratchet behavior.
- **Vision Jet Flaps Fixed:** Flaps were not moving at all — now correctly drive this aircraft's flap lever.
- **Altitude Preselect Reliability:** Fixed several G1000/G3000-family aircraft either ignoring the first altitude command or overshooting and taking a long time to settle.
- **Fewer False Warnings:** Loading into a flight or switching aircraft could briefly show wildly wrong altitude/speed while things settle, incorrectly triggering the overspeed/altimeter voice warnings — Copilot now recognizes this settling period and holds off until instruments are genuinely stable.
- **More Reliable GPU Model Switching:** Fixed a bug where the Copilot could get stuck on the larger GPU model even when video memory ran tight, instead of stepping down.
- **Known Issues:** The Copilot dashboard doesn't yet show the PMDG 777's autopilot mode lights or selected heading/altitude (needs deeper PMDG integration, planned for an upcoming release); Speed Set and Lateral Nav don't yet work on the Citation CJ4 due to its custom autopilot software.

### v0.2.1
- **Rebrand to SkyCrew (AvioLogix):** FSCopilot is now **SkyCrew**, part of the **AvioLogix** family of aviation tools. The voice copilot, wake word, and every command work exactly as before — only the name and app identity have changed. The in-app AI chat window (formerly *CoChat*) is now **SkyChat**. Because SkyCrew is a fresh identity, it uses a new settings folder, so the voice models download once more on first launch.

### v0.2.0
- **GPU Acceleration:** An opt-in <em>GPU Acceleration</em> switch (Settings → AI Engine) loads a larger, sharper Llama-3.2-3B voice model on a compatible NVIDIA/AMD/Intel GPU, automatically stepping down to a smaller model — and back — as free video memory changes, with the CPU model always warm as a fallback.
- **More Reasoning Headroom:** Doubled the model's context window so longer spoken commands no longer risk a rare "context size exceeded" error.
- **Accurate Video-Memory Awareness:** Free VRAM is now read the same way Windows' own Task Manager reads it, making GPU model switching far more reliable under real load.
- **VRAM Safety Margin Slider:** A new Settings slider lets you choose exactly how much video memory to always leave free for the simulator, applied live with no restart.
- **Smaller, Faster Installer:** The installer no longer bundles the voice models directly; they download automatically (with a visible progress bar) the first time you launch SkyCrew after installing, then never again.

### v0.1.6
- **GPU-Accelerated Tiered LLM Mode:** Initial release of the GPU acceleration feature described above under v0.2.0.

### v0.1.5
- **Cessna Checklist Cleanup:** Combined the Flight Prep and Exterior checklists into a single Preflight checklist, and renamed Cabin to Before Engine Start to match the real-world checklist name.
- **Fewer Accidental Voice Activations:** Switching listening modes (or stopping the Copilot) mid-sentence no longer executes a half-heard command; background noise (keyboard clicks, wind, taps) is reliably ignored instead of occasionally firing a command; and simply mentioning a word like "altitude" or "heading" in conversation no longer engages that autopilot mode unless you clearly ask for it.

### v0.1.4
- **Streamlined Copilot Page:** The Overview sub-tab is gone — the Copilot page now opens straight on the Aircraft dashboard, with the Aircraft/Weather/Airport buttons moved to the top, right below the response bar.
- **New Checklists Menu:** Checklists now live under three fixed phase tabs — Preflight, Inflight, Postflight — with a second row of buttons for the individual checklists in that phase, automatically matching whichever aircraft you're flying.
- **Full Cessna C172SP G1000 Checklists:** Flight Prep, Exterior, Cabin, Engine Start, After Engine Start, Before Taxi, Before Takeoff; Normal Takeoff, Climb, Cruise, Descent, ILS Approach, Before Landing, Go Around, Normal Landing; After Landing, After Parking, Securing Aircraft.
- **Full iniBuilds A350-1000 Checklists:** The complete Airbus flow — Flight Prep through Takeoff on the ground, After Takeoff through Landing (including an OANS & BTV arrival-prep checklist) in the air, and After Landing through Securing the Aircraft on the ground — with must-verify items researched and highlighted since the source card carries no bold markup.
- **Tick Items Off as You Go:** Click any line to check it off. Each checklist shows a live progress bar and count, the menu button tracks how far you are, and a finished checklist gets a green tick. Reset just the current checklist or all of them with a button.
- **Progress Is Per-Flight:** Ticks are remembered while you fly, reset automatically when you switch aircraft, and aren't kept between app restarts.
- **Scales With the Window:** Rows resize cleanly as you shrink or grow the app — dotted leaders reflow, and long reference values wrap instead of being pushed off the right edge.

### v0.1.3
- **New Aircraft: Cessna C172SP G1000:** Dedicated command profile, listed as Supported (In Development), with the Commands page graying out systems this airframe doesn't have (gear, speed set/hold, localizer, autothrottle).
- **Cessna Flap Commands:** "flaps 10", "flaps 20", and "flaps 30" for precise notch control, exclusive to the C172SP.
- **New Command — Optimize Fuel:** "optimize fuel" or "lean the mixture" leans to true peak RPM by watching engine RPM, working either direction, in the background.
- **Cessna Autopilot Altitude Fix:** The ALT SEL knob is now turned automatically so a spoken altitude takes effect immediately, instead of sitting on "-----" until manually nudged.
- **Sharper Recognition:** Cessna flap numbers are read directly from speech instead of AI guesswork; closed a flaps/gear mix-up; autothrottle vs. autopilot safeguards now also cover "autothrottle" as a single word.
- **Adjustable Voice Sensitivity:** New Settings sliders for Background Noise Gate, Minimum Speech Length, and Silence Before Processing, applied instantly.
- **Faster Startup:** Engine warmup now happens automatically during startup, so the first spoken command is as fast as every one after it; a new "Engine Warmup…" status pill shows progress.
- **Command Details Popup:** Now opens reliably every time, scrolls for long phrase lists, and keeps the Close button pinned on screen.
- **Logo Audio:** Clicking the logo mid-line now stops it instead of skipping ahead, with clearer hover cues.

### v0.1.2
- **Open Descent / Open Climb (A350):** Say "open descent" / "OP DES" or "open climb" / "OP CLB" to pull the A350's FCU altitude knob and engage the respective vertical mode.
- **VNAV (A350):** Say "engage VNAV" or "vertical navigation" to push the altitude knob and hand vertical guidance to the FMS.
- **Automatic Altimeter Reminders:** Copilot now speaks a reminder when you climb through the transition altitude (set STD) or descend back through it (set local QNH). The trigger altitude follows whatever you've configured in Settings.
- **Profile-Aware Commands Page:** The Commands page now sorts by the aircraft you're flying — applicable commands appear at the top, inapplicable ones are dimmed and moved to the bottom. The list refreshes live when you switch aircraft.
- **Speed Hold Fix (Default 737 MAX 8 BBJ):** The SPEED hold command was being sent through an event the 737 BBJ quietly ignores; it now uses the correct MCP input event.
- **Streamlined Header Navigation:** Updates and Info buttons moved from the sidebar into the app header, left of the clock, so they're reachable from any view without leaving the current page.
- **SkyChat:** New header button that opens the built-in LLaMA AI as a standalone popup window — the same chat previously only accessible via the link on the Info page.
- **Supported Aircraft Browser:** New header button opening a popup that lists all considered aircraft with tiered status tags (Supported, Possibly Compatible, Unsupported).
- **Minimum Window Size:** The main app window now enforces a minimum of 1500 × 820 px to prevent layout elements shuffling at narrow sizes.

### v0.1.1
- **Automatic Aircraft Detection:** Copilot reads the active airframe from the simulator on connect and live mid-session, selecting a matching command profile automatically. Falls back to the default mapping for any aircraft without a dedicated profile.
- **First Addon Profile — iniBuilds A350-1000:** Full Airbus flap detent support (0, 1, 2, 3, FULL); Airbus-correct LNAV engagement (no heading-hold prime needed); Airbus-correct speed engagement (no forced autothrottle arm); self-correcting FCU knobs for speed, heading, altitude and vertical speed (turns, re-reads, corrects until the value matches); working gear lever; fixed autopilot and autothrottle buttons.
- **Extensible Profile System:** Each aircraft profile inherits the default command set and overrides only what that airframe does differently, so adding a new aircraft is a matter of defining just its differences.

### v0.1.0
- **Improved ATC Altitude Recognition:** "Descend and maintain" and "climb and maintain" clearances are now deterministically recognized as Set Altitude commands.
- **Fixed Flight Level Change Routing:** Requests such as "flight level change please" and "level change please" now correctly engage FLC instead of Altitude Hold.
- **Improved Spoken Number Parsing:** Magnitude-based numbers such as "five thousand" and "twenty-five hundred" are now interpreted correctly for altitude, heading, vertical speed, and airspeed. Singular and plural forms ("thousand"/"thousands", "hundred"/"hundreds") are both supported.
- **Removed VNAV Voice Command:** Deprecated and removed because SimConnect provides no standard event for this function.
- **New Default Settings:** Fresh installations now default the push-to-talk key to **Space** and Copilot volume to **50%**.

### v0.0.9
- **Settings Page:** New tab for Copilot volume, push-to-talk binding, remember-window-position, and per-region transition altitudes — all saved to disk.
- **Push-to-Talk:** Optional alternative to continuous listening; press a bound key once to arm a single command, no wake word required.
- **Altitude & Vertical Speed by Voice:** Set a target altitude or vertical speed, or engage their hold modes, by voice.
- **More Autopilot Voice Commands:** LNAV, Localizer, Approach, Level Change, and Speed Set.
- **Autothrottle Arm & Speed Hold:** Arm/disarm the autothrottle and engage speed-hold mode by voice; speed hold auto-arms the autothrottle first if needed.
- **More Reliable LNAV:** Engaging LNAV now primes heading mode first, matching a confirmed default-737 engagement quirk.
- **Accurate Ground Distance:** The altitude tile's "GND" reading now shows true height above terrain, independent of the altimeter setting, instead of raw terrain elevation.
- **Configurable Transition Altitudes:** Move the hardcoded region values into Settings, with adjustable sliders per zone.
- **Echo-Loop Prevention:** The microphone now pauses for the exact measured duration of Copilot's own spoken reply, so it can't hear and misinterpret itself.
- **Sharper Command Recognition:** Hardened the AI against confusing similarly-worded commands (notably autothrottle vs. autopilot), including a safety net that blocks a misrouted command from acting on the wrong system.
- **Autopilot Configuration Panel:** Live state of every autopilot selector and mode at a glance.
- **Weather, Airport & Runway Panel:** Live weather, landing wind components, nearest airport, and tuned radios/ILS.
- **Altitude & Heading Reference Cues:** Visual climb/descend and turn-to-heading reminders when a new target is selected.

### v0.0.8
- **Voice-Activated Standby:** Copilot sits quietly in "Standby" and only listens when it hears your voice.
- **Improved PC Performance:** Reduced idle background processing.
- **Parking Brake:** Set & Release functionality implemented.
- **Set Heading:** Dial in any heading via voice (e.g., "set heading 251").
- **Heading Hold:** Engage heading hold via voice.
- **Autopilot On/Off:** Voice control for autopilot with secure activation.
- **Altimeter Reminder:** Alerts for Standard/Local pressure settings based on altitude/region.
- **Speed Limit:** Warning for overspeed (>250 kts) below 10,000 ft.
- **Landing Lights:** Reminder for lights off/on based on 10,000 ft threshold.
- **Interface Polish:** Adjustable sound volume and faster status readiness.

### v0.0.7
- **Live Aircraft Dashboard:** Real-time data from the sim.
- **Simulator Data Fixes:** Modernized data requests and variable alignment.
- **Stability:** Fixed shutdown crashes and improved trend arrow smoothness.
- **Info Refresh:** Updated in-app documentation.
- **Speed-Up:** Faster transcription by keeping the engine loaded.
- **Logo Sound Fix:** Consistent sound playback.
- **Refactor:** Modularized codebase.
- **Build:** Leaner installer sizes.

### v0.0.6
- **Voice Commands:** Improved intent recognition and direction correction.
- **Speech Recognition:** Upgraded model and vocabulary priming.
- **Faster Reaction:** Dedicated VAD for better speech/noise detection and faster cutoff.
- **Security:** Sandboxed main window.
- **Cleanup:** Leaner builds and startup reliability fixes.

### v0.0.5
- **MSFS24 Connectivity:** Initial integration for gear and flaps.
- **UI/UX:** New Info hub, Commands view, and details modals.

### v0.0.4
- **AI Hardening:** Improved conversational grounding and directional logic.
- **UI:** Persistent response bar, dynamic versioning.

### v0.0.3
- **Voice Interaction:** Smart VAD and fluid sentence recognition.
- **AI Engine:** Contextual hints and JSON output hardening.
- **Stability:** Binary path fixes and artifact filtering.
- **UI:** Standby state and low-latency IPC.

### v0.0.2
- **Auto-Updater:** Seamless background updates with progress indicators.
- **Fixes:** Artifact standardization and ESM/CommonJS compatibility.

### v0.0.1
- **Launch:** Initial production framework and core AI integration.
</details>

