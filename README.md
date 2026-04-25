<img width="940" height="616" alt="image" src="https://github.com/user-attachments/assets/6f388022-6ba2-476a-970d-5accd23003a1" /># Overview
This project is part of a two-phase system. This specific repository focuses on reading 100 alphabets previously stored in an EEPROM, and displaying it on an OLED screen via SPI. 
- For the first phase of the project—writing data from a PC to the EEPROM via I2C, please refer to the `EEPROM` branch of (https://github.com/vuha-05/Storage-data-in-EEPROM-and-transmit-via-UART/tree/EEPROM).

# Hardware 
- Chip: STM32F103C8T6 (Blue Pill)
- AT24C256 I2C Interface EEPROM Module
- LCD OLED SSD1306 0.96-inch 128x64 White Text 7-Pin SPI Interface

# Tools 
- IDE: STM32CubeIDE
- Configuration: STM32CubeMX
- Library: ssd1306 (for LCD)

# Pinout 
- I2C1: PB7 (SDA), PB6 (SCL)
- SPI1: PA0 (RESET), PA1 (DC), PA2 (CS), PA5 (SPI_SCK), PA6 (SPI_MISO), PA7 (SPI_MOSI)

