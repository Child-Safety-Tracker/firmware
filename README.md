
# **ESP32 Firmware for Find My Device Tracker**
This repository contains the firmware code for the ESP32 module used in the Find My Device Tracker project. The firmware enables the ESP32 to communicate with Apple's Find My network using Bluetooth Low Energy (BLE) signals.
## **Project Overview**

This firmware is designed to transform the ESP32 into a low-power, BLE-based tracking device compatible with the Find My network. By broadcasting BLE signals, the ESP32 can be detected by nearby devices that relay its location to the Find My app.

## **Maintainer**

- **Nguyen Duc Hung** - Responsible for the development and maintenance of the firmware.

## **Firmware Features**

- **Bluetooth Low Energy (BLE):** Core functionality for communication with the Find My network.
- **Low Power Mode:** Optimized to conserve battery life when idle, enabling long-term use.
- **Configurable Parameters:** Users can modify the BLE device name and UUID for personalized tracking.
- **Open Source:** The code is open for modification to suit various use cases.

## **Installation**

1. Clone this repository to your local machine:
    \`\`\`bash
    git clone https://github.com/Child-Safety-Tracker/firmware
    \`\`\`
2. Install Arduino IDE or PlatformIO if not already installed.
3. Install the required libraries for the ESP32:
    - **ESP32 BLE Arduino Library**
4. Open the firmware code in your IDE.
5. Configure the device name and UUID to suit your application.
6. Connect the ESP32 to your PC via USB and flash the firmware.

## **Usage Instructions**

Once the firmware is flashed to the ESP32, the device will begin advertising its BLE signal. The Find My network will detect this signal, enabling the object it's attached to, to be tracked via the Find My app.

### **Step-by-step Process:**

1. Flash the firmware onto the ESP32 using Arduino IDE or PlatformIO.
2. Ensure BLE is enabled and the device is set to broadcast.
3. Monitor the device’s performance, and check if it shows up in the Find My app.

## **Future Improvements**

- Integrating GPS modules for more precise location tracking.
- Further improving battery management for extended use.
- Enhancing signal strength for improved BLE range.

## **Contributors**

- **Nguyen Duc Hung** - Firmware development and maintenance.
- **Project Team Members**:
    - Vo Tuan Kiet
    - Dang Tuan Anh
    - Tran Chi Thanh
    - Hoang Thi Tuyet My
