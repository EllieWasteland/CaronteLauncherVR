# CaronteRelayVR
*Bring Flat Games to VR*

[ Windows ] | [ VR ] | [ OpenXR ] | [ OpenVR ] | [ Material Design ] | [ Material Expressive ]


## IMPORTANT NOTICE
To download the application, access updated guides, download addons, and get the best possible experience, please visit our official website:
**[CaronteLauncherVR Official Website](https://elliewasteland.github.io/CaronteLauncherVR/)**


## What is CaronteRelayVR?
CaronteRelayVR is a standalone, universal tool designed to bring ANY game with SBS (Side-by-Side) or TAB (Top-and-Bottom) output into Virtual Reality with the highest quality and lowest latency possible.

### Why does it exist?
As many of you might know, tools like Geo-11 already offer support for output to Katanga or VRScreencap. However, both of those solutions can be complicated, they do not always work perfectly, they seem outdated, and each uses a different runtime. 

CaronteRelayVR was created with the goal of providing a solution that makes it incredibly easy for everyone to access their favorite content on their favorite headsets, without the hassle.

*(Please keep in mind that this is the work of a single person learning basic programming as a hobby. I kindly ask for your patience with any bugs!)*


## Main Features
* **Universal:** Works with any SBS or TAB output.
* **Low Latency:** Optimized for the smoothest experience.
* **Mod Manager (Addons):** Built-in support to load specific configurations.


## Setup & Usage Guide
The execution method is really simple. Follow these 6 steps:

1. **Prep the Game:** Start your game with any mod that allows 3D stereo output (Geo-11 is great for this, supporting most DX11 games with TAB or SBS output).
2. **Launch the App:** Once you are in the game menu, open the *CaronteRelayLauncher*.
3. **Configuration:** Select your language, your runtime (OpenXR or OpenVR), and the capture method.
4. **Viewing Mode:** Choose your visualizer mode. We highly recommend *Immersive Mode* for stability.
5. **Load Addons:** Drag and drop "Caronte Addons" (`.nexus` config files) into the launcher to enable tracking for specific games!
6. **Connect!:** Select the game window, choose your output format (e.g., TAB), click Next, put on your headset, hit the *Spacebar*... and you're IN!


## Controls & Tracking Features
Once inside the game, dial everything in perfectly.

### Visual Adjustments
* **Numpad +** and **Numpad -** : Configure your IPD.
* **Numpad 1** and **Numpad 2** : If views are misaligned, use these until you get a perfectly clear 3D image.

### Tracking Modes (Requires a loaded Addon)
*Press **Enter** during gameplay to initialize tracking.*
* **Numpad 7 (Safe Mode):** 3DOF with Head Aiming (Enabled by default). Stable, avoids camera jitter while in cover.
* **Numpad 8 (Exploration Mode):** 6DOF without aiming (Movement decoupled from head).
* **Numpad 9 (Full Immersion):** 6DOF with Head Aiming. (Expect some jittering in cover - a fix is in progress!).


## Known Issues
* **Mass Effect Tracking Model:** The tracking model for Mass Effect is currently in its early development stages. Because of this, playing on low-end PCs might generate camera jittering.


## Special Guide: Mass Effect Trilogy (Legendary Edition)
Looking to play the Mass Effect Trilogy?

1. **Installation Path:** Consider installing the game outside of the *"Program Files"* folder to avoid issues with the installer.
2. **Enhancement Mods (Recommended):** I highly suggest installing the FPS mod for the first two games and improving your FOV (The persistent FOV mod works for all games). Remember to install them using the *ME3Tweaks Mod Manager* app.
3. **Mandatory Installation:** It is mandatory to install the *MEVR Pre-installer* (available on the official website). This package includes the geo11 installation for Mass Effect by DJ-RK and a fix to prevent VR distortions. (If there are errors, run the app as Administrator).
4. **Final Step:** After running the pre-installer, open *CaronteLauncher*, start in *Katanga* mode, and load your tracking profile (downloadable from the website)!

---
*Project developed by Ellie.N7 - 2026*