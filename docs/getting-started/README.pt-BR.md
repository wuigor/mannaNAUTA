# Primeiros Passos com a mannaNAUTA

**Idioma:** [English](README.md) | Português (Brasil)

1. Prepare sua placa mannaNAUTA e um cabo USB de dados compatível.
2. Instale a versão estável mais recente da Arduino IDE.
3. No Gerenciador de Placas, instale **esp32 by Espressif Systems**.
4. Enquanto a mannaNAUTA não estiver incluída no core Arduino ESP32 oficial,
   selecione **ESP32S3 Dev Module** como placa.
5. Conecte a placa e selecione sua porta serial na Arduino IDE.
6. Consulte o [mapa de pinos](../pinout/README.pt-BR.md) antes de conectar componentes externos.
7. Consulte as bibliotecas [WS2812](https://github.com/wuigor/mannaNAUTA_WS2812_Lib)
   e [LSM6DS](https://github.com/wuigor/mannaNAUTA_LSM6DS_Lib) para instruções
   de instalação e exemplos.

## Pinos importantes do hardware integrado

- LEDs endereçáveis: GPIO47
- LSM6DS via I²C: SDA GPIO5, SCL GPIO4, endereço `0x6A`
- Pads touch: GPIO7 (esquerdo) e GPIO6 (direito)
- Botão BOOT: GPIO0
