ESP32-LoRa-Chat
A web-based chat application using ESP32 and LoRa communication for long-range wireless messaging.

🌟 Features
💬 Real-time messaging over LoRa
🌐 Web-based interface accessible via WiFi
📡 Long-range communication using SX1278 LoRa Module Ra-02
📱 Mobile-friendly responsive design
🔄 Automatic message synchronization
📊 Message history storage
🚦 Connection status indicators
⚡ Easy setup and configuration
📋 Hardware Requirements
ESP32 Development Board
SX1278 LoRa Module Ra-02
433MHz Spring Antenna
Center frequency: 433MHz
Gain: 3dBi
Input impedance: 50 ohm
Interface: IPX1
🔌 Wire Connections
ESP32 -> LoRa Module
- GPIO5  -> NSS/CS
- GPIO18 -> SCK
- GPIO19 -> MISO
- GPIO23 -> MOSI
🚀 Setup Instructions
Install Required Libraries:

WiFi.h
WebServer.h
ArduinoJson
SPI.h
LoRa.h
SPIFFS.h
Upload Code:

Download the code from this repository
Open in Arduino IDE
Select ESP32 board
Upload to two ESP32 devices
For second device, change LoRa addresses in code:
// First ESP32
byte localAddress = 0xAA;    
byte destination = 0xBB;     

// Second ESP32
byte localAddress = 0xBB;    
byte destination = 0xAA;     
Connect:

Network name: ESP32-LoRa-Chat
Password: chatpass123
Web interface: 192.168.4.1
💻 Usage
Power on both ESP32 devices
Connect to either ESP32's WiFi network
Open web browser and go to 192.168.4.1
Enter username in the prompt
Start chatting!
📡 Hardware Specifications
LoRa Module (SX1278 Ra-02)
Frequency: 433MHz
Spreading Factor: 10
Bandwidth: 125kHz
Coding Rate: 4/5
Maximum Range: Several kilometers (line of sight)
Antenna Specifications
Type: Spring Antenna
Center Frequency: 433MHz
VSWR: ≤1.5
Gain: 3dBi
Maximum Power: 10W
Input Impedance: 50 ohm
Interface: IPX1
