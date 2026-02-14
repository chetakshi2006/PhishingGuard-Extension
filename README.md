# PhishingGuard-Extension
# Phishing Guard Extension 🛡️

A browser-based security tool designed to identify and flag potential phishing threats by analyzing webpage URLs and form behaviors in real-time.

## 🚀 Key Features
* **Form Action Analysis:** Scans for forms that send data to external or suspicious domains.
* **Real-time Monitoring:** Uses Chrome's `tabs` API to analyze websites as they load.
* **Phishing Detection:** Flags mismatched hostnames to prevent credential theft.

## 🛠️ Tech Stack
* **Language:** JavaScript (ES6+)
* **Framework:** Chrome Extensions Manifest V3
* **Tools:** OnlineGDB (Initial Development), GitHub

## 📂 Project Structure
* `manifest.json` - Configuration and permissions.
* `background.js` - Service worker for background monitoring.
* `content.js` - Script for page-level DOM analysis.

## ⚙️ How to Install
1. **Download** this repository as a ZIP file and extract it.
2. Open Chrome and go to `chrome://extensions/`.
3. Enable **Developer Mode** (top-right toggle).
4. Click **Load unpacked** and select the project folder.
