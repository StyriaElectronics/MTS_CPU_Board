# 🧠 MTS_CPU_Board

The **MTS_CPU_Board** is the central controller card for the **Modular Test System (MTS)**, built around the Raspberry Pi CM4.  
It serves as the master board for communication and control of all plug-in modules via the MTS backplane.

---
![License: CC BY 4.0](https://img.shields.io/badge/license-CC--BY--4.0-lightgrey.svg)
![Made with KiCad](https://img.shields.io/badge/Made%20with-KiCad-005cad?logo=kicad)
![Platform: Raspberry Pi CM4](https://img.shields.io/badge/platform-Raspberry%20Pi%20CM4-red?logo=raspberry-pi)
![Repo Size](https://img.shields.io/github/repo-size/StyriaElectronics/MTS_CPU_Board)
![Last Commit](https://img.shields.io/github/last-commit/StyriaElectronics/MTS_CPU_Board)
![Stars](https://img.shields.io/github/stars/StyriaElectronics/MTS_CPU_Board?style=social)
---

## 📦 Features

- 🧠 Raspberry Pi CM4 for computing and control
- 🔌 Backplane interface: UART, SPI, I²C, GPIO, CAN (optional)
- ⚡ Power input with regulation and monitoring
- 🌐 Optional Web UI (Flask or Node.js based)
- 📷 Camera / display / USB expandability

---

## 📁 Repository Structure

```
MTS_CPU_Board/
├── hardware/       → KiCad project files
├── software/       → UART daemons, webserver, protocols
├── docs/           → Block diagrams, pinouts, descriptions
├── images/         → Project photos and preview graphics
├── LICENSE         → Project license (CC BY 4.0)
├── .gitignore      → Exclude temp files (KiCad, Python, etc.)
└── README.md       → You are here
```

---

## 📷 Preview

> Add preview images to `images/preview.png`  
> and insert them like this:

```markdown
![MTS_CPU_Board Preview](images/preview.png)
```

---

## 🛠 Usage Ideas

- Slot management for plug-in cards
- Monitoring voltages / temperatures
- Logging & remote access via web
- UART/CAN message routing

---

## 📃 License

📢 Commercial Use Available

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**.

This means you are free to use, modify, and share this work **for non-commercial purposes**, as long as proper credit is given.

➡️ **Commercial use is not permitted without a separate license.**  
If you would like to use this project in a commercial context, please contact me to obtain a commercial license.

📬 Contact: [andras.nagy@styria-electronics.at]
---

## 🤝 Contributing

Contributions are welcome! Fork this repo and feel free to open pull requests or issues.

---

## 🚀 Status

🔧 In development – basic structure in place.  
More hardware and software coming soon.
