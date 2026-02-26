# CKB ESP Flasher

Web-based flasher for CKB ESP32 node monitor clients. No IDE, no drivers — plug in and click.

**Live site:** https://toastmanau.github.io/ckb-esp-flasher/

## Features
- One-click firmware flashing via Web Serial (Chrome/Edge)
- Board detection — warns if chip doesn't match
- Theme Builder — custom colours + background image, exports `theme.h`
- Auto-built firmware from source on every push via GitHub Actions

## Supported Boards

| Board | Status |
|-------|--------|
| Guition ESP32-S3 4848S040 (480×480 ST7701S) | ✅ Live |
| T-Impulse LoRa (SSD1306 OLED) | 🔜 Soon |
| ESP32-P4 + W5500 Light Client | 🔜 Soon |

## Firmware Source
[toastmanAu/kernel-workspace](https://github.com/toastmanAu/kernel-workspace/tree/target/esp32s3-86box/projects/ckb-lora-client/esp32s3_guition4848_ckb_client)
