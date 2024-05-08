# Intruder Alert System with ESP32-CAM

## Purpose
This project aims to enhance physical security, particularly for server rooms, by utilizing the ESP32-CAM. In scenarios where traditional security measures like firewalls may not suffice against physical intrusion, this system provides real-time monitoring and alerts. When motion is detected, the system sends an alert message via WhatsApp, providing immediate notification of potential security breaches.

## How to Run
1. **Setup ESP32-CAM**
   - Connect ESP32-CAM to power and ensure it's connected to the Wi-Fi network (add your credentials in utils.cpp).
   - Ensure the ESP32-CAM is configured to communicate with WhatsApp via whatabot or callmebot API (check out callmebot or whatabot website for configuration method).

2. **Start Monitoring**
   - Once powered on, the ESP32-CAM will send its IP address to a designated WhatsApp number.

3. **Receive Alerts**
   - Whenever motion is detected in front of the camera, the system sends an alert message to the designated WhatsApp number, indicating the date and time of the detection.

4. **View Live Stream**
   - Access the provided IP address through WhatsApp to view the live stream and monitor the area remotely.
