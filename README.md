# ESP32_PCB
# A pcb using espressif ESP32-S3-DEV
This project involves making a devboard using the ESP32-s3 module by Espressif.
We know ESP are the go-to microcontrollers when we want speed and integrated Wifi Bluetooth in out projects.
<img width="927" height="642" alt="image" src="https://github.com/user-attachments/assets/a39f4c8c-99d2-4e39-99cd-7fd4b0ac056e" />

<img width="985" height="641" alt="image" src="https://github.com/user-attachments/assets/b3a8cca2-d32e-4c08-8596-360907bca914" />

<img width="903" height="619" alt="image" src="https://github.com/user-attachments/assets/6a199409-9fc5-464a-a713-03ebd29f0080" />

<img width="903" height="611" alt="image" src="https://github.com/user-attachments/assets/ac4fe3b2-52b3-479d-95f8-ad44c1e51a3b" />

# Features
1. Fully designed in KiCad
2. Features a USB-C USB 2.0 for convenience
3. ESP32 DevBoard features a design under 100*100mm, making it ideal for production houses.
4. 2-Layer PCB
5. Built in AdaFruit NeoPixel as an actuator
6. Built in Zero-PCB/protoboard with ~600 holes to make deployment after prorotype as easy as it can get!

# Main components used
1. Espressif ESP32-S3-Mini-N8
2. Adafruit Neopixel 5mm
3. Texas Instruments tlv758p
4. USB-C 2.0

# Schematic
Designed in KiCad
<img width="1568" height="1011" alt="image" src="https://github.com/user-attachments/assets/2fb2ba4b-c398-4ff3-95d0-4a56512b38fe" />


# resources I used for this project:
1. https://docs.espressif.com/projects/esp-hardware-design-guidelines/en/latest/esp32s3/esp-hardware-design-guidelines-en-master-esp32s3.pdf
2. https://docs.espressif.com/projects/esp-idf/en/stable/esp32s3/get-started/index.html
3. https://www.ti.com/lit/ds/symlink/tlv758p.pdf?ts=1764750861284
4. https://documentation.espressif.com/esp32-s3_technical_reference_manual_en.pdf
5. https://cdn-shop.adafruit.com/datasheets/WS2812B.pdf

# Developer note:
If you do anufacture this PCB, when you get it for the first time, it is necessary to do the initialization boot sequence when esp is powered.
hold boot> click reset once> release boot
This allows ESP to go into coding mode where you can upload code into your board.
