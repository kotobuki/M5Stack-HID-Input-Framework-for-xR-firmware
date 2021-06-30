# M5Stack HID Input Framework for xR (firmware)

Regarding the source code of this project, please refer to this repository.

Built with the following packages and libraries:

- Arduino IDE v1.8.15
- ESP32 Arduino Release 1.0.6 based on ESP-IDF v3.3.5
- M5Stack v0.3.1
- ESP32-BLE-Keyboard v0.2.3
- VL53L0X library for Arduino v1.3.0
- Adafruit SGP30 Gas / Air Quality I2C sensor v2.0.0
- Adafruit MPR121 Library v1.1.0

## Notes

- Copied `esp32-1.0.6/tools/partitions/boot_app0.bin` as `boot_0xe000.bin`
- Copied `esp32-1.0.6/tools/sdk/bin/bootloader_qio_80m.bin` as `bootloader_0x1000.bin`
- Copied `AlternativeController.ino.partitions.bin` as `partitions_0x8000.bin`
- Copied `AlternativeController.ino.bin` as `AlternativeController_0x10000.bin`
