# Node-RedSmartSolar-150-70
Get data from **Victron SmartSolar 150/70** using Node-Red Serial.

Install **[node-red-node-serialport](https://flows.nodered.org/node/node-red-node-serialport)**

Use Node-Red Serial In followed by a function.

Copy-Paste code into it and deploy. You will receive data every second until you stop the serial port.

![serial](https://github.com/user-attachments/assets/e15672b2-0e73-4b19-bd79-4d2ba6b8bd39)

**Data that you will get:**
- Product ID
- Firmware Version
- Serial Number
- Battery Voltage
- Battery Current
- Solar Voltage
- Solar Current calculated by function not received from controller
- Solar Power
- Charging Mode
- Tracking Mode
- Errors
- Running Days
- Max Solar Power Today
- Max Solar Power Yesterday
- Yield Today
- Yield Yesterday
- Yield Total
- and you can add more if you read **[ve.direct protocol](https://www.victronenergy.com/upload/documents/VE.Direct-Protocol-3.33.pdf)**
