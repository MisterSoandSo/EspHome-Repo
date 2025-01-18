# EspHome Repo
This repository contains project files for ESPHome, compiled using Python Esphome. Most YAML files were initially generated with the `esphome wizard <projectname.yaml>` command.

## Requirements
To get started, ensure you have all the necessary dependencies. You can install them using the following command:
```
pip install esphome
```

## Projects
### Garage
Details to be added.
### Renogy 
Details to be added.

## Troubleshooting
If you encounter issues, consider the following steps:
1. **Verify Device Driver**Ensure your device driver is correctly installed. Download and install the required driver from this [link](https://www.silabs.com/developer-tools/usb-to-uart-bridge-vcp-drivers?tab=overview).

2. **Check Baud Rate and Communication Port** 
- For Windows devices, the initial default baud rate is set to `9600` .
- ESPHome’s default baud rate is `115200`.
Ensure these settings align for proper communication.


Check your esp32/8266 device baud rate and communication port. For windows, the inital default rate is set to 9600. Esphome's default rate is 115000.
3. **Flashing via USB** When flashing locally via usb, make sure to press the 'Enable' button on the board to allow for the writing via the serial port.