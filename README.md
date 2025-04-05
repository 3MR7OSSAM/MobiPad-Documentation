
# 🎮 MobiPad Gaming App

![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Android%20%7C%20iOS-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

> **Turn your smartphone into a powerful wireless controller for your PC games.**

---

## 📌 Overview

**MobiPad Gaming Server** is a lightweight and intuitive application that transforms your mobile device into a wireless gaming controller for your PC. With a virtual gamepad interface on your smartphone or tablet, MobiPad makes it easy to enjoy your favorite PC games without the need for physical game controllers.
<p align="center">
<img src="https://github.com/user-attachments/assets/c3b0d54f-f016-4d73-b8d7-abfe7279c599" width="300" height="300">
</p>

---

## ✨ Features

### 🖥 Server Application (PC)
- ✅ **Easy Setup**: Clean, user-friendly UI to start and manage your server
- ⚙️ **Performance Configuration**:
  - Input Processing Interval (default: `5ms`)
  - Movement Debounce Time (default: `20ms`)
  - Button Debounce Time (default: `10ms`)
- 💾 **Config Management**: Save/load custom performance profiles
- 🌐 **WebSocket Server**: Runs over LAN using your local IP address
<p align="center">
<img src="https://github.com/user-attachments/assets/b99a9b67-e4fe-4d21-bc3b-ae1fd992d354" alt="Windows App UI" width="400">
</p>

### 📱 Client Application (Mobile)
- 🎮 **Virtual Gamepad**: Includes a full-featured control layout:
  - D-pad
  - Action buttons (▲ ▲ ⬛ ◯ ✖)
  - Shoulder buttons (L1, L2, R1, R2)
- 🎚️ **Sensitivity Modes**: Choose from `LOW`, `MEDIUM`, or `HIGH`
- 🔧 **Custom Key Mapping**: Personalize how mobile controls map to your PC keyboard or mouse
- 🔗 **Quick Reconnect**: Remembers previously used servers for faster reconnection
- 
<p align="center">
  <img src="https://github.com/user-attachments/assets/f3b4fd0e-189d-4231-96dc-f6fb85b7ec9d" alt="MOBI1" width="300"/>
  &nbsp;&nbsp;
  <img src="https://github.com/user-attachments/assets/b6b3e87e-f172-439c-89fa-d922214d8d2e" alt="MOBI2" width="300"/>
</p>



---

## 🚀 Getting Started

### 💻 Server Setup (PC)
1. **Download & install** the MobiPad Gaming Server application.
2. **Launch the app** and go to the `Dashboard` tab.
3. Click **Start Server** to initiate the WebSocket broadcast.
4. Note the server address displayed (e.g., `ws://192.168.1.8:8765`).

### 📱 Client Setup (Mobile)
1. **Install** the MobiPad client app from the Play Store or App Store.
2. Open the app and **enter the server IP and port** from the PC.
3. Tap **Connect** to pair with the server.
4. Once connected, the virtual controller UI will appear on your screen.



---

## ⚙️ Configuration

### 🏎️ Performance Settings
| Setting                  | Description                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| **Input Processing Interval** | Frequency of input polling (`Lower = Faster`, `Higher = Less CPU load`) |
| **Movement Debounce Time**    | Filters out repeated D-pad signals                                       |
| **Button Debounce Time**      | Filters out repeated button presses                                     |

### 🎯 Key Mappings
- Map mobile buttons to any keyboard or mouse input
- Create and save multiple key mapping profiles for different games
- Includes presets for popular game genres (e.g., FPS, racing, platformers)

```json
{
  "A_Button": "Z",
  "B_Button": "X",
  "L1": "Shift",
  "R1": "Ctrl"
}
```



---

## 🖥 System Requirements

### PC (Server)
- **OS**: Windows 7 / 8 / 10 / 11
- **Network**: Must be connected to the same local network as the client

### Mobile (Client)
- **Android**: 7.0+
- **iOS**: 12.0+
- **Network**: Same Wi-Fi or LAN as the server

---

## 🛠️ Troubleshooting

### 🔄 Connection Issues
- Ensure both devices are on the **same local network**
- Check for **firewall rules** blocking the WebSocket port (`default: 8765`)
- Verify the server IP and port are entered correctly

### 🐌 Lag or Input Delay
- Reduce `Input Processing Interval`
- Adjust debounce settings
- Avoid high network load (e.g., streaming, downloads)

---

## 🔐 Privacy & Security

- Works **only** within your local network (LAN)
- **No data** is collected, transmitted, or stored externally
- Your gaming data and preferences remain **private and secure**

---

## 👨‍💻 Developer

**Created by**: Amr Hossam  
📧 Email: [contact@3mr7ossam.me](mailto:contact@3mr7ossam.me)

---

## 🧾 License

This project is licensed under the **MIT License**.  
See the [LICENSE](./LICENSE) file for details.

---

## 🙋 Support

Have feedback, issues, or ideas?

- 📧 Email: [contact@3mr7ossam.me]
---
