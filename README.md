# ⚡ DeauthStrom — The Ultimate Wi-Fi Attack & Jamming Framework

> Created by **Uwes Kulabkar**  
> 📡 Telegram: [@collectingnoobs](https://t.me/collectingnoobs)

---

## 🔥 Overview

**DeauthStrom** is the **ultimate Python-based Wi-Fi attack and jamming framework**, designed for wireless penetration testers, red teamers, and cybersecurity enthusiasts. It delivers a comprehensive and automated suite of 802.11 wireless exploits, allowing professionals to dominate any local wireless environment with precision and control.

Unlike basic scripts or GUI tools, **DeauthStrom integrates multiple attack vectors**, real-time scanning, MAC spoofing, and full interface automation into a single unified terminal experience — making it one of the most powerful Wi-Fi attack tools available today.

---

## 💣 Key Features

- 🛰️ **Targeted Deauthentication**  
  Kick a single client or all clients off a specific access point using `aireplay-ng`.

- 🔐 **Authentication Flood**  
  Flood target APs with fake auth requests using `mdk4`.

- 🌪️ **Beacon Flood**  
  Create hundreds of fake SSIDs to confuse or overload client devices.

- ⚔️ **Mass Deauth (Global Attack)**  
  Automatically deauthenticate all detected networks in range.

- 📡 **Channel Jamming**  
  Jam all 2.4GHz and/or 5GHz channels in a rotating attack.

- 🧠 **Smart Scanning**  
  Live scan Wi-Fi networks and identify connected clients using `airodump-ng`.

- 🧰 **Interface Auto Handling**  
  Auto-detects wireless interfaces and enables monitor mode via `airmon-ng`.

- 🛡️ **MAC Address Randomization**  
  Anonymize each attack session with randomized MAC addresses (`macchanger`).

- 🖥️ **Attack Sessions in External Terminals**  
  All attacks launch in individual `xterm` or `gnome-terminal` windows.

- 📝 **Detailed Logging**  
  Session activity and errors logged to `/tmp/deauthstrom.log`.

---

## 🚀 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/deauthstrom.git
cd deauthstrom
```

### 2. Install Dependencies

```bash
sudo apt update
sudo apt install aircrack-ng mdk4 macchanger iw xterm -y
```

> 💡 If using GNOME desktop, replace `xterm` with `gnome-terminal`.

---

## ⚙️ Usage

Run the tool with root privileges:

```bash
sudo python3 deauthstrom.py
```

---

### 🧭 Main Menu

```text
1. Scan Networks
2. Global Attacks
3. Exit
```

---

### 🎯 Attack Options (Post Scan)

```text
1. Deauth Attack (Single Client)
2. Deauth Attack (All Clients)
3. Auth Flood
4. Beacon Flood (Fake APs)
5. Mass Deauth (All Networks)
6. Jam All Channels
7. Back to Main Menu
```

---

## 🔬 Technical Stack

| Component        | Description                                       |
|------------------|---------------------------------------------------|
| **Language**      | Python 3                                          |
| **Wireless Tools**| `aircrack-ng`, `mdk4`, `macchanger`, `iw`, `iwconfig` |
| **Execution**     | External terminals for each attack (`xterm`)     |
| **Scanning**      | CSV parsing of `airodump-ng` output              |
| **Security**      | Interface validation, MAC spoofing, cleanup      |
| **Logging**       | Full session logging at `/tmp/deauthstrom.log`  |

---

## ⚠️ Legal Disclaimer

> This project is intended for **educational purposes and authorized penetration testing only**. Unauthorized access or interference with wireless networks is illegal and punishable by law.  
>  
> The author **Uwes Kulabkar** and the contributors are **not responsible** for any misuse or damages caused by this tool.

Use it responsibly.

---

## 👤 Author

**Uwes Kulabkar**  
📨 Telegram: [@collectingnoobs](https://t.me/collectingnoobs)

---

## 💬 Community & Support

📢 Join our Telegram group for updates, discussions, and support:  
[https://t.me/collectingnoobs](https://t.me/collectingnoobs)

---

## 📁 License

This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for more details.
