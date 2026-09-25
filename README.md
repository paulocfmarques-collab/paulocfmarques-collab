# Hello, I'm Paulo César Furlanetto Marques 👋

## About Me

I am an Embedded Software Engineer, Team Leader at AEL Sistemas, and University Professor with more than 15 years of experience developing high-reliability software for embedded and avionics system[...]

My professional experience includes software architecture, embedded C/C++ development, real-time systems, verification and validation, debugging, systems integration, technical leadership, and engi[...]

I am also interested in networked embedded systems, IoT, observability, automation, and engineering tools that improve system visibility and operational efficiency. I enjoy mentoring technology pro[...]

> Leadership, technical rigor, continuous learning, and engineering excellence are the foundations for building high-performing teams and reliable systems.

---

## 🚀 Engineering Focus

- Embedded Systems and Firmware
- Avionics and High-Reliability Software
- C and C++
- ESP32 and Arduino-based Systems
- Real-Time Operating Systems (RTOS)
- Linux and Windows Development
- Python Automation and Network Tooling
- Wi-Fi, Bluetooth, UDP, TCP, MQTT, HTTP, and WebSocket
- Network Discovery and Asset Inventory
- PostgreSQL and JSON Data Persistence
- Prometheus and Grafana Observability
- Raspberry Pi and IoT Prototyping
- DevOps and Operational Automation
- Technical Leadership and Agile Engineering

---

## 🛠 Technologies

### Languages

<p>
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" alt="C">
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white" alt="C#">
</p>

### Systems and Platforms

<p>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux">
  <img src="https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white" alt="ESP32">
  <img src="https://img.shields.io/badge/Raspberry%20Pi-C51A4A?style=for-the-badge&logo=raspberry-pi&logoColor=white" alt="Raspberry Pi">
  <img src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Windows">
  <img src="https://img.shields.io/badge/WinForms-5C2D91?style=for-the-badge&logoColor=white" alt="WinForms">
</p>

### Data and Observability

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" alt="Prometheus">
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" alt="Grafana">
</p>

### Connectivity and Protocols

<p>
  <img src="https://img.shields.io/badge/Wi--Fi-00A0DC?style=for-the-badge&logo=wifi&logoColor=white" alt="Wi-Fi">
  <img src="https://img.shields.io/badge/Bluetooth-0082FC?style=for-the-badge&logo=bluetooth&logoColor=white" alt="Bluetooth">
  <img src="https://img.shields.io/badge/UDP-0078D4?style=for-the-badge&logoColor=white" alt="UDP">
  <img src="https://img.shields.io/badge/TCP-0078D4?style=for-the-badge&logoColor=white" alt="TCP">
  <img src="https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white" alt="MQTT">
  <img src="https://img.shields.io/badge/HTTP-5C940D?style=for-the-badge&logo=http&logoColor=white" alt="HTTP">
</p>

---

## 🔭 Featured Projects

### [ESP32-P4 Wi-Fi & UDP Control Gateway](https://github.com/paulocfmarques-collab/esp32_wifi_P4)

Field-configurable ESP32-P4 gateway with Wi-Fi provisioning, UDP command control, OLED diagnostics, persistent credentials, LED control, and runtime telemetry.

- Wi-Fi provisioning access point with persistent credentials
- UDP command interface on port `4210`
- HTTP configuration portal at `192.168.4.1`
- OLED and Serial diagnostics
- LED control with finite and continuous blinking modes
- CPU, memory, flash, temperature, uptime, MAC, and network telemetry
- GPIO2 Wi-Fi reset and recovery workflow

**Technologies:** C++, ESP32-P4, Arduino, Wi-Fi, UDP, HTTP, Preferences, SSD1306 OLED, GPIO

### [Network Discovery for Prometheus](https://github.com/paulocfmarques-collab/network-discovery-prometheus)

Python-based network discovery and observability automation for authorized Linux networks.

- Nmap host discovery and service inspection
- ARP/MAC resolution and vendor enrichment
- DNS/mDNS lookup and device classification
- Parallel host processing with `ThreadPoolExecutor`
- Persistent inventory and MAC-based history
- Prometheus `file_sd_config` target generation
- Telegraf ping configuration generation
- Rotating operational logs and monitoring integration

**Technologies:** Python, Nmap, arp-scan, Prometheus, Telegraf, SNMP, Linux

### [MAC Presence Exporter](https://github.com/paulocfmarques-collab/mac-presence-exporter)

Network presence monitoring solution that tracks devices by MAC address and exports operational metrics.

- Automatic device discovery
- Online/offline presence tracking
- Historical presence analysis
- PostgreSQL persistence
- Prometheus metric export
- Grafana dashboard integration
- Raspberry Pi deployment support

**Technologies:** Python, PostgreSQL, Prometheus, Grafana, Nmap, arp-scan, Raspberry Pi

### [Network Discovery Inventory](https://github.com/paulocfmarques-collab/windows_discovery)

Network inventory tooling for discovering and enriching local devices using ARP scanning, Nmap, reverse DNS, and persistent JSON storage.

- Incremental inventory updates
- MAC, IP, vendor, hostname, and operating-system data
- First-seen and last-seen timestamps
- Parallel device processing
- JSON inventory and execution logs

**Technologies:** Python, Nmap, arp-scan, reverse DNS, JSON

### [ESP32 Wi-Fi Card](https://github.com/paulocfmarques-collab/esp32_wifi_card)

Configurable ESP32 network controller with Wi-Fi provisioning, UDP command processing, diagnostics, status indicators, and microSD logging.

- Wi-Fi station mode with SoftAP provisioning fallback
- Persistent credentials using ESP32 `Preferences`
- UDP command interface on port `4210`
- CPU, memory, flash, temperature, uptime, MAC, and network diagnostics
- microSD logging over VSPI
- LED heartbeat, command feedback, and reset recovery
- Remote file and log operations

**Technologies:** C++, ESP32, Arduino, Wi-Fi, UDP, HTTP, NVS, SPI, microSD, OLED

### [ESP32 Wi-Fi Provisioning and UDP Control](https://github.com/paulocfmarques-collab/esp32_wifi)

ESP32 firmware for captive-style Wi-Fi provisioning, persistent network configuration, remote UDP control, hardware supervision, and diagnostics.

- HTTP configuration portal
- Automatic reconnection after reboot
- NVS/Preferences credential storage
- UDP command server
- OLED diagnostic display
- Hardware-button Wi-Fi reset
- Device health and runtime telemetry

**Technologies:** C++, ESP32, Arduino, Wi-Fi, UDP, WebServer, Preferences, SSD1306 OLED

### [ESP32 Central](https://github.com/paulocfmarques-collab/esp32_central)

Touchscreen-based ESP32 control center for monitoring and commanding remote ESP32 nodes over a local Wi-Fi network.

- TFT/XPT2046 touchscreen interface
- Multi-node selection and command dispatch
- UDP command and response protocol
- Local command execution
- Wi-Fi credential provisioning through a configuration portal
- Persistent credentials using NVS
- Remote LED and diagnostic control

**Technologies:** C++, ESP32, Wi-Fi, UDP, TFT_eSPI, XPT2046, WebServer, Preferences

### [ESP32 Bluetooth Remote Control and System Monitor](https://github.com/paulocfmarques-collab/esp32_bluetooth)

Bluetooth Classic SPP firmware for remote control, embedded diagnostics, and interactive command processing.

- Bluetooth serial communication
- LED control and asynchronous blinking with `millis()`
- CPU, RAM, flash, uptime, MAC, and network diagnostics
- Text-based command/response protocol
- Smartphone and desktop terminal support
- Non-blocking embedded control flow

**Technologies:** C++, ESP32, Bluetooth Classic SPP, Arduino, GPIO, embedded diagnostics

### [ESP32 Comm](https://github.com/paulocfmarques-collab/esp32-Comm)

Windows WinForms diagnostic client for bidirectional UDP communication with ESP32 devices.

- IPv4 endpoint and port configuration
- ASCII command transmission
- UTF-8 response decoding
- Dedicated receive thread for UI responsiveness
- Cross-thread UI updates using `Control.Invoke`
- Real-time diagnostic console
- Integration with custom ESP32 command protocols

**Technologies:** C#, .NET Framework, WinForms, UDP/IPv4, multithreading

### [ESP32 Wi-Fi](https://github.com/paulocfmarques-collab/esp32_wifi)

Embedded firmware platform for Wi-Fi commissioning, remote diagnostics, UDP control, and device recovery workflows.

- Provisioning access point when credentials are unavailable
- Persistent Wi-Fi configuration
- Remote device control and health reporting
- LED, reset, temperature, memory, flash, and uptime support
- Local-network automation and monitoring use cases

**Technologies:** C++, ESP32, Arduino, Wi-Fi, UDP, HTTP, NVS, OLED

### [TIniFile](https://github.com/paulocfmarques-collab/inifiles)

Lightweight, dependency-free C++11 INI configuration reader and writer implemented as a single-header library.

- String, integer, and hexadecimal value access
- Section and key creation during writes
- In-memory linked-list representation
- Automatic persistence on object destruction
- Make-based build and example application
- No external runtime dependencies

**Technologies:** C++, C++11, C-style APIs, file I/O, linked-list data structures, GNU Make

---

## 🎓 Professional Experience

- Team Leader at AEL Sistemas
- Embedded software development for high-reliability systems
- Avionics software for civil and military aircraft projects
- Software architecture, integration, debugging, and technical leadership
- University Professor
- Technical training, mentoring, and development of technology professionals

---

## 📊 GitHub Statistics

![Paulo's GitHub Stats](https://github-readme-stats.vercel.app/api?username=paulocfmarques-collab&show_icons=true&theme=tokyonight)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=paulocfmarques-collab&layout=compact&theme=tokyonight)

---

## 🌎 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Paulo%20César%20Furlanetto%20Marques-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/)

[![GitHub](https://img.shields.io/badge/GitHub-@paulocfmarques--collab-181717?style=for-the-badge&logo=github)](https://github.com/paulocfmarques-collab)

---

> "The best technology is the one that solves real problems, improves reliability, and helps people grow."
