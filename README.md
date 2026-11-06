# 02_ESP_IDF_ST7789_LVGL

## What It Does

LVGL display and no touch.

## Hardware Required

ESP32-S3-LCD-1.69 development board and a USB data cable.

## How to Run

Activate an ESP-IDF version v6.0.2, open a terminal in this example directory, and run:

```bash
idf.py set-target esp32s3 build flash monitor
```

## Expected Result

The LVGL demo appears on the LCD and responds to touch.

## Troubleshooting

The first build requires network access to download the managed components declared in main/idf_component.yml.
