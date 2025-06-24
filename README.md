# ⚡ DeauthStrom — Advanced Wi-Fi Attack Framework

> Created by **Uwes Kulabkar**  
> 📡 Telegram: [@collectingnoobs](https://t.me/collectingnoobs)

---

## 🔥 Overview

**DeauthStrom** is a cutting-edge, modular Wi-Fi attack framework built for offensive wireless testing. It empowers security researchers, penetration testers, and Wi-Fi auditing professionals with a complete suite of 802.11-based attacks — all from an elegant terminal-driven interface.

Whether you're launching targeted deauths, performing authentication floods, or conducting full-spectrum jamming, DeauthStrom provides **reliable automation, real-time feedback, and smart interface control**.

---

## 💣 Key Features

- 🛰️ **Targeted Deauthentication**
  - Kick a single client or all clients off a specific access point using `aireplay-ng`.

- 🔐 **Authentication Flood**
  - Flood target APs with fake auth requests using `mdk4`.

- 🌪️ **Beacon Flood**
  - Create hundreds of fake SSIDs to confuse or overload client devices.

- ⚔️ **Mass Deauth (Global Attack)**
  - Automatically deauthenticate all detected networks in range.

- 📡 **Channel Jamming**
  - Jam all 2.4GHz and/or 5GHz channels in a rotating attack.

- 🧠 **Smart Scanning**
  - Live scan Wi-Fi networks and identify connected clients using `airodump-ng`.

- 🧰 **Interface Auto Handling**
  - Auto-detects wireless interfaces and enables monitor mode via `airmon-ng`.

- 🛡️ **MAC Address Randomization**
  - Anonymize each attack session with randomized MAC addresses (`macchanger`).

- 🖥️ **Attack Sessions in External Terminals**
  - All attacks launch in individual `xterm` or `gnome-terminal` windows.

- 📝 **Detailed Logging**
  - Session activity and errors logged to `/tmp/deauthstrom.log`.

---

## 📸 Screenshots

> *(Optional: Add images of the tool in action here)*

---

## 🚀 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/deauthstrom.git
cd deauthstrom
