# LD2410C human presence radar

This project is for setup of LD2410C radar working with ld2410 library.
The LD2410C version is improved version from the LD2410 sensor family.

Be aware that this sensor draws high amount od current, so the precautions on the power management should be considered

---

### Supporting library:
- (current branch)
https://registry.platformio.org/libraries/ncmreynolds/ld2410 
- (more extensive library)
https://registry.platformio.org/libraries/iavorvel/MyLD2410

---

### Specs:
- manufacturer: Hi-Link
- microwave human presence detector
- detects moving & stationary people
- 60° detection angle
- FMCW radar technology (Frequency Modulated Continuous Wave)
- bluetooth enabled
- light level detection

---

### Connection diagram:

![ESP32-C#_LD2410C](https://raw.githubusercontent.com/RobertNeat/LD2410C_human_presence/refs/heads/main/images/connection_diagram.png)

* out pin will have high state if it senses presence according to the sensor configuration
---
To configure the sensor connect:
- throuth USB-UART and windows .exe application
- through USB-UART and the web application
- through android application "HLKRadarTool"

---

### Resource links:
- comperhansive tutorial link:
https://dronebotworkshop.com/ld2410c-human-sensor/

- online tool for monitoring and configuration (direct USB-UART connection to sensor):
https://ld2410.albert.nz/

- link for official desktop application  (direct USB-UART connection to sensor):
https://drive.google.com/drive/folders/1lCQv3mfHJ3XKXzweeHPFnJ_8_D_EWEKk

- android bluetooth application "HLKRadarTool"
https://play.google.com/store/apps/details?id=com.hlk.hlkradartool

- official producer product website:
https://www.hlktech.com/en/Goods-239.html


Additional links:
https://www.printables.com/model/767970-presence-sensor-case-esp32-c3-super-mini-ld2410c-r
