# coolruns09.github.io
Launch Command: A Chrome extension and landing page for real-time global spaceflight tracking, precision countdowns, and smart live-stream routing. Built by DJF Industries, LLC.


# 🚀 Launch Command

**Your Personal Mission Control. Never miss a liftoff.**

Launch Command is a sleek, powerful browser extension that transforms your new tab into a real-time tracking console for global spaceflight operations. This repository contains the source code for the Chrome Extension (Manifest V3) as well as the static HTML/CSS files for the official landing page and Privacy Policy.

## 🛰️ Key Features

* **Real-Time Precision Countdown:** A dynamic "T-Minus" clock that tracks the exact seconds until the next liftoff, complete with a UI that glows as the launch window approaches.
* **Smart Live-Stream Routing:** A multi-tier fallback system that checks for official API streams, routes to provider channels, or deploys dynamic YouTube Live searches to ensure you always find the broadcast.
* **Global Launch Telemetry:** Tracks missions from every major provider worldwide (NASA, SpaceX, ULA, Rocket Lab, ISRO, ESA, JAXA, CASC, and more) using The Space Devs API.
* **OS-Level Push Notifications:** Runs quietly in the background, pinging your desktop the moment a launch is less than 30 minutes away.
* **Immersive "Console" UI:** Designed with a dark-mode sci-fi aesthetic featuring scanlines, metallic gradients, and glowing readouts.

## 📂 Repository Structure

* `manifest.json` - The Manifest V3 configuration file for the Chrome Web Store.
* `popup.html` / `popup.css` / `popup.js` - The frontend interface and logic for the extension console.
* `background.js` - The service worker handling background data fetching and push notifications.
* `ExtPay.js` - Secure payment and subscription token verification via ExtensionPay.
* `index.html` / `styles.css` - The static landing page and privacy policy hosted via GitHub Pages.

## 🛠️ How to Install Locally (Developer Mode)

If you want to test the extension directly from this source code:
1. Download or clone this repository to your local machine.
2. Open Chrome and navigate to `chrome://extensions/`.
3. Toggle **Developer mode** on in the top right corner.
4. Click **Load unpacked** in the top left corner.
5. Select the folder containing this repository's files.

## 📄 License & Copyright

&copy; 2026 DJF Industries, LLC. All rights reserved. 
Data provided by [The Space Devs API](https://ll.thespacedevs.com/).
