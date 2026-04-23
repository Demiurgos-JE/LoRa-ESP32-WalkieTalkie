- developed in Arduino IDE v2 on bazzite OS
- put together with additional assistence from CLAUDE

- hardware:
- HelTec LoRa Esp32 V3
- 20 cm LoRa antenna
- 4 buttons
- 1 buzzer
- 3000 mAh Li-Ion rechargable battery

- functions:
- SLEEP mode: button press sends ESP32 in deep sleep mode for battery saving, pressing the same button again wakes it up
- PING mode: button press sends a PING message with its own ID (last four MAC adress indicators) and can receive a PONG message with the receiving device's ID as a response
- HELLO mode: button press sends a "Hello from ...!" text message
- HEART mode: button press sends a heart graphic 
