# MADE BY LUCKERIS
# ESP32 PC Control with Wake-on-LAN

This project allows you to control your PC via Wake-on-LAN (WOL) technology using the ESP32. With the help of a web interface, you can turn on your PC or restart the ESP32.

## Requirements
- ESP32 board (e.g., ESP32 Dev Kit)
- WiFi connection
- PC with Wake-on-LAN support

## How to Use
1. **Set up configuration**:
   - Set the values for `ssid`, `password`, `macAddress`, and `pcIP` in the code to match your network and the PC you want to control.
     - `ssid`: The name of your WiFi network
     - `password`: The password of your WiFi network
     - `macAddress`: The MAC address of the PC you want to turn on
     - `pcIP`: The IP address of the PC you want to turn on

2. **Upload the code to ESP32**:
   - Open this project in Arduino IDE.
   - Select the correct ESP32 board.
   - Upload the code to your ESP32.

3. **Connect to the ESP32**:
   - After successfully connecting ESP32 to your WiFi network, the device's IP address will be shown on the serial monitor.
   - Open this IP address in a web browser on a device connected to the same network.

4. **Control the PC**:
   - The webpage will contain two buttons:
     - **Turn On PC**: Sends a Wake-on-LAN packet to turn on your PC.
     - **Restart ESP32**: Restarts the ESP32 device.

## License
This project is open-source and available under the MIT License.
