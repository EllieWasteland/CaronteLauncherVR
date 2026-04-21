
# CaronteApp
*Bring Flat Games to VR*

## IMPORTANT NOTICE
To download the application, access updated guides, download addons, and get the best possible experience, please visit our official website:
**[CaronteApp Official Website](https://elliewasteland.github.io/CaronteLauncherVR/)**


## What is CaronteApp?
CaronteApp is a standalone, universal tool designed to bring ANY game with SBS (Side-by-Side) or TAB (Top-and-Bottom) output into Virtual Reality with the highest quality and lowest latency possible.

### Why does it exist?
As many of you might know, tools like Geo-11 already offer support for output to Katanga or VRScreencap. However, both of those solutions can be complicated, they do not always work perfectly, they seem outdated, and each uses a different runtime. 

CaronteApp was created with the goal of providing a solution that makes it incredibly easy for everyone to access their favorite content on their favorite headsets, without the hassle. We now also offer **native support for Geo11's KatangaVR output**, bringing even better performance and compatibility.

*(Please keep in mind that this is the work of a single person learning basic programming as a hobby. I kindly ask for your patience with any bugs!)*


## Main Features
* **Universal:** Works with any SBS or TAB output.
* **Low Latency:** Optimized for the smoothest experience.
* **Mod Manager (Addons):** Built-in support to load specific configurations.


## Setup & Usage Guide
The execution method is really simple. Follow these steps:

1. **Prep the Game:** Start your game with any mod that allows 3D stereo output (Geo-11 is great for this, supporting most DX11 games with TAB or SBS output).
2. **Launch the App:** Once you are in the game menu, open the **CaronteApp**.
3. **Configuration:** Select your language, your runtime (OpenXR or OpenVR), and the capture method.
4. **View Profile:** Add your **View Profile** to have the best configuration for your visualization, prepared by your community or created by yourself.
5. **Load Addons:** Drag and drop "Caronte Addons" (`.nexus` config files) into the launcher to enable tracking for specific games!
6. **Connect!:** Select the game window, choose your output format (e.g., TAB), click Next, put on your headset, hit the **Spacebar**... and you're IN!


## Keybindings & Controls
Once inside the game, dial everything in perfectly using the following keybindings:

### General Visual Adjustments
* **Numpad + / Numpad -** : Increase / Decrease IPD
* **Numpad 1 / Numpad 2** : Decrease / Increase Zoom
* **Numpad 4 / Numpad 5** : Decrease / Increase Distortion X
* **Numpad 3 / Numpad 6** : Decrease / Increase Distortion Y

### Advanced Screen Adjustments
* **Insert / Delete** : Increase / Decrease Stretch Y
* **Page Up / Page Down** : Increase / Decrease Stretch X
* **Arrow Keys (Up, Down, Left, Right)** : Eye Shift adjustments (Y+, Y-, X-, X+)

### Misc / Utilities
* **V** : Toggle Vignette
* **End** : Exit CaronteApp
* **Enter (Numpad Ent)** : Initialize Tracking (Requires a loaded Addon)


## Known Issues
* **Mass Effect Tracking Model:** The tracking model for Mass Effect is currently in its early development stages. Because of this, playing on low-end PCs might generate camera jittering.


## Special Guide: Mass Effect Trilogy (Legendary Edition)
Looking to play the Mass Effect Trilogy?

1. **Installation Path:** Consider installing the game outside of the *"Program Files"* folder to avoid issues with the installer.
2. **Enhancement Mods (Recommended):** I highly suggest installing the FPS mod for the first two games and improving your FOV. *(Note: For Mass Effect 3 there isn't an FPS mod yet, but the community is working on it. The Persistent Mod works for all games!)*. Remember to install them using the *ME3Tweaks Mod Manager* app.
3. **Mandatory Installation:** It is mandatory to install the *MEVR Pre-installer* (available on the official website). This package includes the geo11 installation for Mass Effect by DJ-RK and a fix to prevent VR distortions. (If there are errors, run the app as Administrator).
4. **Final Step:** After running the pre-installer, open **CaronteApp**, start in **Katanga** mode, and load your tracking profile (downloadable from the website)!

---
*Project developed by Ellie.N7 - 2026*