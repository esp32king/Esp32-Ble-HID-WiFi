# 🚀 ESP32 WiFi Controlled Bluetooth HID Keyboard

Control your PC or Mobile using ESP32 as a WiFi-based webserver which sends commands over Bluetooth HID (BLE Keyboard).
You just open ESP32’s webpage → tap a button → and ESP32 will type or run shortcuts on the paired device ✨


---

# ✨ Features

📡 WiFi Web Server hosted at 192.168.4.1

🌐 Web Control Panel (HTML/JS) to send commands

⌨️ Bluetooth HID (Keyboard) output to connected device

# ⚡ Predefined Shortcuts:

✂️ ShortCut Key Available 

📝 Custom Text Typing directly from browser

🔗 Works with Windows, Linux, macOS, Android



---

# 🛠 Requirements

 Esp32 Board
 Laptop or Pc For Flashing Code




---


# 1️⃣ Flash to ESP32

<br> Check <a href="https://github.com/esp32king/Esp32-Ble-HID-WiFi/Releases">Releases</a></br>
<a href="https://github.com/esp32king/Esp32-Ble-HID-WiFi/releases/download/Esp32-BLE-HID-WiFi/bootloader.bin">bootloader.bin</a> → 0x1000

<a href="https://github.com/esp32king/Esp32-Ble-HID-WiFi/releases/download/Esp32-BLE-HID-WiFi/partitions.bin">partitions.bin</a> → 0x8000

<a href="https://github.com/esp32king/Esp32-Ble-HID-WiFi/releases/download/Esp32-BLE-HID-WiFi/Esp32-BLE-HID-WiFi.bin">ESP32-BLE-HID-WIFI.bin</a> → 0x10000


# 2️⃣ Connect & Control

1. 🔗 Connect ESP32 via Bluetooth to your PC / Mobile (shows as Free 5G)


2. 📶 Connect WiFi → SSID: BLE WiFi (default password: 12345678)


3. 🌐 Open browser → http://192.168.4.1


4. 🎛 Use the Web Panel to send commands




---

# 🖥 Web Panel

The ESP32 hosts a webpage with:

🔘 Buttons: ALT+F4, WIN+D, PrintScreen..etc

📝 Input Box: Type custom text → send via BLE HID

📡 Status Info: Bluetooth connected / disconnected



---

# 🎬 Demo Flow

1. 📱 Phone connects to ESP32 WiFi


2. 🌐 User opens 192.168.4.1


3. 🖱️ Press WIN+D on webpage


4. 💻 ESP32 sends shortcut → PC minimizes all windows instantly




---

⚠️ Disclaimer

⚡ This project is for educational, automation, and testing purposes only.
❌ Do NOT use it for malicious or unauthorized actions.


---
<img src="https://raw.githubusercontent.com/esp32king/Esp32-Ble-HID-WiFi/refs/heads/main/Files/Test.jpg"></img>
These are all buttons Only Tap to Run 
<img src="https://raw.githubusercontent.com/esp32king/Esp32-Ble-HID-WiFi/refs/heads/main/Files/Test2.jpg"></img>

created By Krishna Rajput UP61

