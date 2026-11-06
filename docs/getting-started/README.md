# Getting Started with mannaNAUTA

**Language:** English | [Português (Brasil)](README.pt-BR.md)

1. Prepare your mannaNAUTA board and a compatible USB data cable.
2. Install the latest stable Arduino IDE.
3. In Boards Manager, install **esp32 by Espressif Systems**.
4. Until mannaNAUTA is included in the official ESP32 Arduino core, select
   **ESP32S3 Dev Module** as the board.
5. Connect the board and select its serial port in Arduino IDE.
6. Explore the [pinout map](../pinout/README.md) before connecting external components.
7. Consult the dedicated [WS2812](https://github.com/wuigor/mannaNAUTA_WS2812_Lib)
   and [LSM6DS](https://github.com/wuigor/mannaNAUTA_LSM6DS_Lib) libraries for
   installation instructions and examples.

## Important built-in pins

- Addressable LEDs: GPIO47
- LSM6DS I²C: SDA GPIO5, SCL GPIO4, address `0x6A`
- Touch pads: GPIO7 (left) and GPIO6 (right)
- BOOT button: GPIO0
