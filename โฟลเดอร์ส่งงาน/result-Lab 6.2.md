### ผลลัพธ์1
```
ets Jul 29 2019 12:21:46

rst:0x1 (POWERON_RESET),boot:0x12 (SPI_FAST_FLASH_BOOT)
configsip: 0, SPIWP:0xee
clk_drv:0x00,q_drv:0x00,d_drv:0x00,cs0_drv:0x00,hd_drv:0x00,wp_drv:0x00
mode:DIO, clock div:2
load:0x3fff0030,len:6372
load:0x40078000,len:15928
load:0x40080400,len:3880
entry 0x40080638
I (3192) boot: ESP-IDF v6.0-dev-1002-gbfe5caf58f 2nd stage bootloader
I (3209) boot: compile time Aug  6 2025 03:23:10
I (3210) boot: Multicore bootloader
I (4917) boot: chip revision: v3.0
I (4936) boot.esp32: SPI Speed      : 40MHz
I (4937) boot.esp32: SPI Mode       : DIO
I (4947) boot.esp32: SPI Flash Size : 2MB
I (5243) boot: Enabling RNG early entropy source...
I (5625) boot: Partition Table:
I (5626) boot: ## Label            Usage          Type ST Offset   Length
I (5627) boot:  0 nvs              WiFi data        01 02 00009000 00006000
I (5628) boot:  1 phy_init         RF data          01 01 0000f000 00001000
I (5629) boot:  2 factory          factory app      00 00 00010000 00100000
I (5921) boot: End of partition table
I (9136) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=09634h ( 38452) map
I (10095) esp_image: segment 1: paddr=0001965c vaddr=3ff80000 size=00024h (    36) load
I (10748) esp_image: segment 2: paddr=00019688 vaddr=3ffb0000 size=025e0h (  9696) load
I (11401) esp_image: segment 3: paddr=0001bc70 vaddr=40080000 size=043a8h ( 17320) load
I (12141) esp_image: segment 4: paddr=00020020 vaddr=400d0020 size=0f0ach ( 61612) map
I (12655) esp_image: segment 5: paddr=0002f0d4 vaddr=400843a8 size=08c58h ( 35928) load
I (13893) boot: Loaded app from partition at offset 0x10000
I (13894) boot: Disabling RNG early entropy source...
I (14143) cpu_start: Multicore app
I (26798) cpu_start: Pro cpu start user code
I (26803) cpu_start: cpu freq: 160000000 Hz
I (26805) app_init: Application information:
I (26806) app_init: Project name:     lab6_2_multiple_files
I (26807) app_init: App version:      1
I (26808) app_init: Compile time:     Aug  6 2025 03:21:32
I (26812) app_init: ELF file SHA256:  63cfa9c7d...
I (26816) app_init: ESP-IDF:          v6.0-dev-1002-gbfe5caf58f
I (26818) efuse_init: Min chip rev:     v0.0
I (26818) efuse_init: Max chip rev:     v3.99
I (26821) efuse_init: Chip rev:         v3.0
I (26829) heap_init: Initializing. RAM available for dynamic allocation:
I (26841) heap_init: At 3FFAE6E0 len 00001920 (6 KiB): DRAM
I (1) heap_init: At 3FFB2EA8 len 0002D158 (180 KiB): DRAM
I (11) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
I (12) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
I (13) heap_init: At 4008D000 len 00013000 (76 KiB): IRAM
I (180) spi_flash: detected chip: winbond
I (210) spi_flash: flash io: dio
I (255) main_task: Started on CPU0
I (285) main_task: Calling app_main()
I (285) MAIN: 🚀 Lab 6.2: Multiple Source Files Demo
I (285) MAIN: 📍 Main function from file: ./main/lab6_2_multiple_files.c, line: 13
I (285) MAIN: ESP-IDF Version: v6.0-dev-1002-gbfe5caf58f
I (295) SENSOR: 🔧 Sensor initialized from file: ./main/sensor.c, line: 12
I (295) SENSOR: 📡 Sensor module ready for operation
I (295) MAIN: === Loop 0 ===
I (295) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (305) SENSOR: 🌡️  Temp erature: 30.1°C
I (365) SENSOR: 💧 Humidity: 98.2%
I (2365) MAIN: === Loop 1 ===
I (2365) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (2365) SENSOR: 🌡️  Temperature: 27.6°C
I (2365) SENSOR: 💧 Humidity: 61.6%
I (4365) MAIN: === Loop 2 ===
I (4365) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (4365) SENSOR: 🌡️  Temperature: 27.8°C
I (4365) SENSOR: 💧 Humidity: 74.8%
I (4365) SENSOR: ✅ Sensor status check from file: ./main/sensor.c, line: 30
I (4365) SENSOR: 📈 All sensors operating normally
I (6365) MAIN: === Loop 3 ===
I (6365) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (6365) SENSOR: 🌡️  Temperature: 25.5°C
I (6365) SENSOR: 💧 Humidity: 77.1%
I (8365) MAIN: === Loop 4 ===
I (8365) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (8365) SENSOR: 🌡️  Temperature: 32.2°C
I (8365) SENSOR: 💧 Humidity: 63.5%
I (10365) MAIN: === Loop 5 ===
I (10365) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (10365) SENSOR: 🌡️  Temperature: 26.3°C
I (10365) SENSOR: 💧 Humidity: 96.6%
I (10365) SENSOR: ✅ Sensor status check from file: ./main/sensor.c, line: 30
I (10365) SENSOR: 📈 All sensors operating normally
I (12365) MAIN: === Loop 6 ===
I (12365) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (12365) SENSOR: 🌡️  Temperature: 26.6°C
I (12365) SENSOR: 💧 Humidity: 81.4%
I (14365) MAIN: === Loop 7 ===
I (14365) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (14365) SENSOR: 🌡️  Temperature: 28.5°C
I (14365) SENSOR: 💧 Humidity: 99.0%
I (16365) MAIN: === Loop 8 ===
I (16365) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (16365) SENSOR: 🌡 ️  Temperature: 30.0°C
I (16365) SENSOR: 💧 Humidity: 68.4%
I (16365) SENSOR: ✅ Sensor status check from file: ./main/sensor.c, line: 30
I (16365) SENSOR: 📈 All sensors operating normally
I (18375) MAIN: === Loop 9 ===
I (18375) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (18375) SENSOR: 🌡️  Temperature: 35.3°C
I (18375) SENSOR: 💧 Humidity: 83.5%
I (20375) MAIN: === Loop 10 ===
I (20375) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (20375) SENSOR: 🌡️  Temperature: 28.4°C
I (20375) SENSOR: 💧 Humidity: 94.5%
I (22375) MAIN: === Loop 11 ===
I (22375) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (22375) SENSOR: 🌡️  Temperature: 29.4°C
I (22375) SENSOR: 💧 Humidity: 79.0%
I (22375) SENSOR: ✅ Sensor status check from file: ./main/sensor.c, line: 30
I (22375) SENSOR: 📈 All sensors operating normally
I (24375) MAIN: === Loop 12 ===
I (24375) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (24375) SENSOR: 🌡️  Temperature: 35 .1°C
I (24385) SENSOR: 💧 Humidity: 81.7%
I (26395) MAIN: === Loop 13 ===
I (26395) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (26415) SENSOR: 🌡️  Temperature: 29.5°C
I (26415) SENSOR: 💧 Humidity: 69.4%
I (28415) MAIN: === Loop 14 ===
I (28415) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (28415) SENSOR: 🌡️  Temperature: 28.3°C
I (28415) SENSOR: 💧 Humidity: 79.1%
I (28425) SENSOR: ✅ Sensor status check from file: ./main/sensor.c, line: 30
I (28435) SENSOR: 📈 All sensors operating normally
I (30435) MAIN: === Loop 15 ===
I (30435) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (30435) SENSOR: 🌡️  Temperature: 33.5°C
I (30445) SENSOR: 💧 Humidity: 70.0%
I (32455) MAIN: === Loop 16 ===
I (32455) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (32455) SENSOR: 🌡️  Temperature: 26.1°C
I (32455) SENSOR: 💧 Humidity: 79.2%
I (34455) MAIN: === Loop 17 ===
I (34455) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (34455) SENSOR: 🌡️  Temperature: 32.7°C
I (34455) SENSOR: 💧 Humidity: 72.5%
I (34455) SENSOR: ✅ Sensor status check from file: ./main/sensor.c, line: 30
I (34455) SENSOR: 📈 All sensors operating normally
I (36455) MAIN: === Loop 18 ===
I (36455) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (36455) SENSOR: 🌡️  Temp erature: 30.0°C
I (36465) SENSOR: 💧 Humidity: 77.2%
I (38475) MAIN: === Loop 19 ===
I (38475) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (38475) SENSOR: 🌡️  Temperature: 25.9°C
I (38485) SENSOR: 💧 Humidity: 93.6%
I (40485) MAIN: === Loop 20 ===
I (40485) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (40485) SENSOR: 🌡️  Temperature: 26.2°C
I (40495) SENSOR: 💧 Humidity: 89.8%
I (40505) SENSOR: ✅ Sensor status check from file: ./main/sensor.c, line: 30
I (40505) SENSOR: 📈 All sensors operating normally
I (42505) MAIN: === Loop 21 ===
I (42505) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (42505) SENSOR: 🌡️  Temperature: 33.0°C
I (42525) SENSOR: 💧 Humidity: 62.8%
```

### ผลลัพธ์ 2
```
ets Jul 29 2019 12:21:46

rst:0x1 (POWERON_RESET),boot:0x12 (SPI_FAST_FLASH_BOOT)
configsip: 0, SPIWP:0xee
clk_drv:0x00,q_drv:0x00,d_drv:0x00,cs0_drv:0x00,hd_drv:0x00,wp_drv:0x00
mode:DIO, clock div:2
load:0x3fff0030,len:6372
load:0x40078000,len:15928
load:0x40080400,len:3880
entry 0x40080638
I (1298) boot: ESP-IDF v6.0-dev-1002-gbfe5caf58f 2nd stage bootloader
I (1302) boot: compile time Aug  6 2025 03:23:10
I (1304) boot: Multicore bootloader
I (2023) boot: chip revision: v3.0
I (2030) boot.esp32: SPI Speed      : 40MHz
I (2031) boot.esp32: SPI Mode       : DIO
I (2032) boot.esp32: SPI Flash Size : 2MB
I (2128) boot: Enabling RNG early entropy source...
I (2231) boot: Partition Table:
I (2232) boot: ## Label            Usage          Type ST Offset   Length
I (2233) boot:  0 nvs              WiFi data        01 02 00009000 00006000
I (2236) boot:  1 phy_init         RF data          01 01 0000f000 00001000
I (2241) boot:  2 factory          factory app      00 00 00010000 00100000
I (2343) boot: End of partition table
I (3087) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=09824h ( 38948) map
I (3471) esp_image: segment 1: paddr=0001984c vaddr=3ff80000 size=00024h (    36) load
I (3824) esp_image: segment 2: paddr=00019878 vaddr=3ffb0000 size=025e0h (  9696) load
I (4183) esp_image: segment 3: paddr=0001be60 vaddr=40080000 size=041b8h ( 16824) load
I (4530) esp_image: segment 4: paddr=00020020 vaddr=400d0020 size=0f230h ( 62000) map
I (4878) esp_image: segment 5: paddr=0002f258 vaddr=400841b8 size=08e48h ( 36424) load
I (6502) boot: Loaded app from partition at offset 0x10000
I (6503) boot: Disabling RNG early entropy source...
I (6618) cpu_start: Multicore app
I (12653) cpu_start: Pro cpu start user code
I (12657) cpu_start: cpu freq: 160000000 Hz
I (12657) app_init: Application information:
I (12658) app_init: Project name:     lab6_2_multiple_files
I (12659) app_init: App version:      1
I (12659) app_init: Compile time:     Aug  6 2025 03:21:32
I (12660) app_init: ELF file SHA256:  d93daf9cc...
I (12660) app_init: ESP-IDF:          v6.0-dev-1002-gbfe5caf58f
I (12661) efuse_init: Min chip rev:     v0.0
I (12661) efuse_init: Max chip rev:     v3.99
I (12662) efuse_init: Chip rev:         v3.0
I (12674) heap_init: Initializing. RAM available for dynamic allocation:
I (12677) heap_init: At 3FFAE6E0 len 00001920 (6 KiB): DRAM
I (12678) heap_init: At 3FFB2EA8 len 0002D158 (180 KiB): DRAM
I (12678) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
I (12679) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
I (12680) heap_init: At 4008D000 len 00013000 (76 KiB): IRAM
I (12783) spi_flash: detected chip: winbond
I (12797) spi_flash: flash io: dio
I (12826) main_task: Started on CPU0
I (12846) main_task: Calling app_main()
I (12846) MAIN: 🚀 Lab 6.2: Multiple Source Files Demo
I (12846) MAIN: 📍 Main function from file: ./main/lab6_2_multiple_files.c, line: 14
I (12846) MAIN: ESP-IDF Version: v6.0-dev-1002-gbfe5caf58f
I (12846) SENSOR: 🔧 Sensor initialized from file: ./main/sensor.c, line: 12
I (12856) SENSOR: 📡 Sensor module ready for operation
I (12856) DISPLAY: 🖥️  Display initialized from fil e: ./main/display.c, line: 9
I (12856) DISPLAY: 💡 Display module ready
I (12856) DISPLAY: 📢 Displaying from file: ./main/display.c, line: 15
I (12856) DISPLAY: 📺 Message: System Starting...
I (12856) MAIN: === Loop 0 ===
I (12856) DISPLAY: 🧹 Screen cleared  from file: ./main/display.c, line: 28
I (12866) DISPLAY: ✨ Display ready for new content
I (12866) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (12866) SENSOR: 🌡️  Temperature: 26.1°C
I (12886) SENSOR: 💧 Humidity: 71.7%
I (12886) DISPLAY: 📊 Data display from file: ./main/display.c, line: 21
I (12886) DISPLAY: 📈 Value 1: 26.50
I (12896) DISPLAY: 📉 Value 2: 61.00
I (14896) MAIN: === Loop 1 ===
I (14896) DISPLAY: 🧹 Screen cleared from file: ./main/display.c, line: 28
I (14896) DISPLAY: ✨ Display ready for new content
I (14896) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (14896) SENSOR: 🌡 ️  Temperature: 25.6°C
I (14906) SENSOR: 💧 Humidity: 62.8%
I (14906) DISPLAY: 📊 Data display from file: ./main/display.c, line: 21
I (14906) DISPLAY: 📈 Value 1: 27.50
I (14906) DISPLAY: 📉 Value 2: 62.00
I (16916) MAIN: === Loop 2 ===
I (16916) DISPLAY: 🧹 Screen cleared from file: ./main/display.c, line: 28
I (16916) DISPLAY: ✨ Display ready for new content
I (16916) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (16916) SENSOR: 🌡️  Tempe rature: 35.2°C
I (16926) SENSOR: 💧 Humidity: 71.2%
I (16926) DISPLAY: 📊 Data display from file: ./main/display.c, line: 21
I (16926) DISPLAY: 📈 Value 1: 28.50
I (16926) DISPLAY: 📉 Value 2: 63.00
I (16936) SENSOR: ✅ Sensor status check from file: ./main/sensor.c, line: 30
I (16936) SENSOR: 📈 All sensors operating normally
I (16936) DISPLAY: 📢 Displaying from file: ./main/display.c, line: 15
I (16936) DISPLAY: 📺 Message: Status Check Complete
I (18946) MAIN: === Loop 3 ===
I (18946) DISPLAY: 🧹 Screen cleared from file: ./main/display.c, line: 28
I (18946) DISPLAY: ✨ Display ready for new content
I (18946) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (18946) SENSOR: 🌡️  Temperature: 34.5°C
I (18956) SENSOR: 💧 Humidity: 71.3%
I (18956) DISPLAY: 📊 Data display from file: ./main/display.c, line: 21
I (18956) DISPLAY: 📈 Value 1: 29.50
I (18956) DISPLAY: 📉 Value 2: 64.00
I (20956) MAIN: === Loop 4 ===
I (20956) DISPLAY: 🧹 Screen cleared from file: ./main/display.c, line: 28
I (20956) DISPLAY: ✨ Display ready for new content
I (20976) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (20976) SENSOR: 🌡️  Temperature: 28.8°C
I (20986) SENSOR: 💧 Humidity: 94.8%
I (20986) DISPLAY: 📊 Data display from file: ./main/display.c, line: 21
I (20996) DISPLAY: 📈 Value 1: 30.50
I (20996) DISPLAY: 📉 Value 2: 65.00
I (23006) MAIN: === Loop 5 ===
I (23006) DISPLAY: 🧹 Screen cleared from file: ./main/display.c, line: 28
I (23006) DISPLAY: ✨ Display ready for new content
I (23016) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (23016) SENSOR: 🌡️  Temperature: 33.6°C
I (23016) SENSOR: 💧 Humidity: 64.5%
I (23016) DISPLAY: 📊 Data display from file: ./main/display.c, line: 21
I (23026) DISPLAY: 📈 Value 1: 31.50
I (23026) DISPLAY: 📉 Value 2: 66.00
I (23036) SENSOR: ✅ Sensor status check from file: ./main/sensor.c, line: 30
I (23046) SENSOR: 📈 All sensors operating normally
I (23046) DISPLAY: 📢 Displaying from file: ./main/display.c, line: 15
I (23046) DISPLAY: 📺 Message: Status Check Complete
I (25046) MAIN: === Loop 6 ===
I (25046) DISPLAY: 🧹 Screen cleared from file: ./main/display.c, line: 28
I (25046) DISPLAY: ✨ Display ready for new content
I (25046) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (25046) SENSOR: 🌡️  Temperature: 33.0°C
I (25046) SENSOR: 💧 Humidity: 73.9%
I (25046) DISPLAY: 📊 Data display from file: ./main/display.c, line: 21
I (25046) DISPLAY: 📈 Value 1: 32.50
I (25046) DISPLAY: 📉 Value 2: 67.00
I (27046) MAIN: === Loop 7 ===
I (27046) DISPLAY: 🧹 Screen cleared from file: ./main/display.c, line: 28
I (27046) DISPLAY: ✨ Display ready for new content
I (27046) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (27046) SENSOR: 🌡️  Temperature: 34.2°C
I (27046) SENSOR: 💧 Humidity: 86.4%
I (27046) DISPLAY: 📊 Data display from file: ./main/display.c, line: 21
I (27046) DISPLAY: 📈 Value 1: 33.50
I (27046) DISPLAY: 📉 Value 2: 68.00
I (29056) MAIN: === Loop 8 ===
I (29056) DISPLAY: 🧹 Screen cleared from file: ./main/display.c, line: 28
I (29056) DISPLAY: ✨ Display ready for new content
I (29056) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (29056) SENSOR: 🌡️  Temperature: 32.1 °C
I (29056) SENSOR: 💧 Humidity: 98.5%
I (29056) DISPLAY: 📊 Data display from file: ./main/display.c, line: 21
I (29056) DISPLAY: 📈 Value 1: 34.50
I (29056) DISPLAY: 📉 Value 2: 69.00
I (29056) SENSOR: ✅ Sensor status check from file: ./main/sensor.c, line: 30
I (29056) SENSOR: 📈 All sensors operating normally
I (29056) DISPLAY: 📢 Displaying from file: ./main/display.c, line: 15
I (29056) DISPLAY: 📺 Message: Status Check Complete
```

### ผลลัพธ์ idf.py size
<img width="652" height="365" alt="image" src="https://github.com/user-attachments/assets/89a087a2-4783-4e82-b62c-d1a7aeda1a47" />

### 
```
ets Jul 29 2019 12:21:46

rst:0x1 (POWERON_RESET),boot:0x12 (SPI_FAST_FLASH_BOOT)
configsip: 0, SPIWP:0xee
clk_drv:0x00,q_drv:0x00,d_drv:0x00,cs0_drv:0x00,hd_drv:0x00,wp_drv:0x00
mode:DIO, clock div:2
load:0x3fff0030,len:6372
load:0x40078000,len:15928
load:0x40080400,len:3880
entry 0x40080638
I (1732) boot: ESP-IDF v6.0-dev-1002-gbfe5caf58f 2nd stage bootloader
I (1735) boot: compile time Aug  6 2025 03:23:10
I (1736) boot: Multicore bootloader
I (2659) boot: chip revision: v3.0
I (2668) boot.esp32: SPI Speed      : 40MHz
I (2669) boot.esp32: SPI Mode       : DIO
I (2669) boot.esp32: SPI Flash Size : 2MB
I (2767) boot: Enabling RNG early entropy source...
I (2857) boot: Partition Table:
I (2858) boot: ## Label            Usage          Type ST Offset   Length
I (2859) boot:  0 nvs              WiFi data        01 02 00009000 00006000
I (2861) boot:  1 phy_init         RF data          01 01 0000f000 00001000
I (2863) boot:  2 factory          factory app      00 00 00010000 00100000
I (2960) boot: End of partition table
I (3627) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=09a24h ( 39460) map
I (4020) esp_image: segment 1: paddr=00019a4c vaddr=3ff80000 size=00024h (    36) load
I (4345) esp_image: segment 2: paddr=00019a78 vaddr=3ffb0000 size=025e0h (  9696) load
I (4680) esp_image: segment 3: paddr=0001c060 vaddr=40080000 size=03fb8h ( 16312) load
I (5008) esp_image: segment 4: paddr=00020020 vaddr=400d0020 size=0f3e4h ( 62436) map
I (5332) esp_image: segment 5: paddr=0002f40c vaddr=40083fb8 size=09048h ( 36936) load
I (6425) boot: Loaded app from partition at offset 0x10000
I (6426) boot: Disabling RNG early entropy source...
I (6558) cpu_start: Multicore app
I (12315) cpu_start: Pro cpu start user code
I (12320) cpu_start: cpu freq: 160000000 Hz
I (12322) app_init: Application information:
I (12322) app_init: Project name:     lab6_2_multiple_files
I (12323) app_init: App version:      1
I (12323) app_init: Compile time:     Aug  6 2025 03:21:32
I (12324) app_init: ELF file SHA256:  77400858b...
I (12325) app_init: ESP-IDF:          v6.0-dev-1002-gbfe5caf58f
I (12326) efuse_init: Min chip rev:     v0.0
I (12331) efuse_init: Max chip rev:     v3.99
I (12334) efuse_init: Chip rev:         v3.0
I (12341) heap_init: Initializing. RAM available for dynamic allocation:
I (12344) heap_init: At 3FFAE6E0 len 00001920 (6 KiB): DRAM
I (12345) heap_init: At 3FFB2EB0 len 0002D150 (180 KiB): DRAM
I (12345) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
I (12346) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
I (12353) heap_init: At 4008D000 len 00013000 (76 KiB): IRAM
I (12460) spi_flash: detected chip: winbond
I (12484) spi_flash: flash io: dio
I (12515) main_task: Started on CPU0
I (12535) main_task: Calling app_main()
I (12535) MAIN: 🚀 Lab 6.2: Multiple Source Files Demo
I (12535) MAIN: 📍 Main function from file: ./main/lab6_2_multiple_files.c, line: 15
I (12535) MAIN: ESP-IDF Version: v6.0-dev-1002-gbfe5caf58f
I (12535) SENSOR: 🔧 Sensor initialized from file: ./main/sensor.c, line: 12
I (12535) SENSOR: 📡 Sensor module ready for operation
I (12545) DISPLAY: 🖥️  Display initialized from file: ./main/display.c, line: 9
I (12545) DISPLAY: 💡 Display module ready
I (12545) LED: 💡 LED initialized from file: ./main/led.c, line: 12
I (12545) LED: 🔧 LED module ready
I (12545) DISPLAY: 📢 Displaying from file: ./main/display.c, line: 15
I (12545) DISPLAY: 📺 Message: System Starting...
I (12555) LED: 🚀 Starting LED blink task from file: ./main/led.c, line: 59
I (12555) LED: ✨ LED blink task started from file: ./main/led.c, line: 49
I (12555) LED: ✅ LED ON from file: ./main/led.c, line: 20
I (12555) LED: 🟢 LED is now ON
I (12555) LED: 🔄 LED toggled from file: ./main/led.c, line: 38
I (12565) MAIN: === Loop 0 ===
I (12565) DISPLAY: 🧹 Screen cleared from file: ./main/display.c, line: 28
I (12565) DISPLAY: ✨ Display ready for new content
I (12565) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (12575) SENSOR: 🌡️  Temperature: 30.1°C
I (12595) SENSOR: 💧 Humidity: 78.3%
I (12595) DISPLAY: 📊 Data display from file: ./main/display.c, line: 21
I (12595) DISPLAY: 📈 Value 1: 26.50
I (12595) DISPLAY: 📉 Value 2: 61.00
I (12605) DISPLAY: 📢 Displaying from file: ./main/display.c, line: 15
I (12605) DISPLAY: 📺 Message: LED Status: ON
I (14615) MAIN: === Loop 1 ===
I (14615) DISPLAY: 🧹 Screen cleared from file: ./main/display.c, line: 28
I (14615) DISPLAY: ✨ Display ready for new content
I (14615) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (14615) SENSOR: 🌡️  Temperature: 27.4°C
I (14615) SENSOR: 💧 Humidity: 70.5%
I (14615) DISPLAY: 📊 Data display from file: ./main/display.c, line: 21
I (14615) DISPLAY: 📈 Value 1: 27.50
I (14625) DISPLAY: 📉 Value 2: 62.00
I (14625) DISPLAY: 📢 Displaying from file: ./main/display.c, line: 15
I (14625) DISPLAY: 📺 Message: LED Status: ON
I (15565) LED: ❌ LED OFF from file: ./main/led.c, line: 27
I (15575) LED: 🔴 LED is now OFF
I (15575) LED: 🔄 LED toggled from file: ./main/led.c, line: 38
I (16625) MAIN: === Loop 2 ===
I (16625) DISPLAY: 🧹 Screen cleared from file: ./main/display.c, line: 28
I (16625) DISPLAY: ✨ Display ready for new content
I (16635) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (16635) SENSOR: 🌡️  Temperature: 31.6°C
I (16645) SENSOR: 💧 Humidity: 66.2%
I (16655) DISPLAY: 📊 Data display from file: ./main/display.c, line: 21
I (16655) DISPLAY: 📈 Value 1: 28.50
I (16655) DISPLAY: 📉 Value 2: 63.00
I (16655) DISPLAY: 📢 Displaying from file: ./main/display.c, line: 15
I (16655) DISPLAY: 📺 Message: LED Status: OFF
I (16655) SENSOR: ✅ Sensor status check from file: ./main/sensor.c, line: 30
I (16655) SENSOR: 📈 All sensors operating normally
I (16655) DISPLAY: 📢 Displaying from file: ./main/display.c, line: 15
I (16675) DISPLAY: 📺 Message: Status Check Complete
I (18575) LED: ✅ LED ON from file: ./main/led.c, line: 20
I (18575) LED: 🟢 LED is now ON
I (18575) LED: 🔄 LED toggled from file: ./main/led.c, line: 38
I (18675) MAIN: === Loop 3 ===
I (18675) DISPLAY: 🧹 Screen cleared from file: ./main/display.c, line: 28
I (18675) DISPLAY: ✨ Display ready for new content
I (18675) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (18675) SENSOR: 🌡️  Temperature: 29.3°C
I (18675) SENSOR: 💧 Humidity: 84.4%
I (18675) DISPLAY: 📊 Data display from file: ./main/display.c, line: 21
I (18675) DISPLAY: 📈 Value 1: 29.50
I (18685) DISPLAY: 📉 Value 2: 64.00
I (18685) DISPLAY: 📢 Displaying from file: ./main/display.c, line: 15
I (18685) DISPLAY: 📺 Message: LED Status: ON
I (20685) MAIN: === Loop 4 ===
I (20685) DISPLAY: 🧹 Screen cleared from file: ./main/display.c, line: 28
I (20685) DISPLAY: ✨ Display ready for new content
I (20685) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (20685) SENSOR: 🌡️  Temperature: 30.7° C
I (20695) SENSOR: 💧 Humidity: 96.6%
I (20695) DISPLAY: 📊 Data display from file: ./main/display.c, line: 21
I (20695) DISPLAY: 📈 Value 1: 30.50
I (20695) DISPLAY: 📉 Value 2: 65.00
I (20695) DISPLAY: 📢 Displaying from file: ./main/display.c, line: 15
I (20695) DISPLAY: 📺 Message: LED Status: ON
I (21575) LED: ❌ LED OFF from file: ./main/led.c, line: 27
I (21605) LED: 🔴 LED is now OFF
I (21605) LED: 🔄 LED toggled from file: ./main/led.c, line: 38
I (22695) MAIN: === Loop 5 ===
I (22695) DISPLAY: 🧹 Screen cleared from file: ./main/display.c, line: 28
I (22695) DISPLAY: ✨ Display ready for new content
I (22695) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (22695) SENSOR: 🌡️  Temperature: 26.3°C
I (22695) SENSOR: 💧 Humidity: 91.5%
I (22695) DISPLAY: 📊 Data display from file: ./main/display.c, line: 21
I (22695) DISPLAY: 📈 Value 1: 31.50
I (22695) DISPLAY: 📉 Value 2: 66.00
I (22695) DISPLAY: 📢 Displaying from file: ./main/display.c, line: 15
I (22705) DISPLAY: 📺 Message: LED Status: OFF
I (22705) SENSOR: ✅ Sensor status check from file: ./main/sensor.c, line: 30
I (22705) SENSOR: 📈 All sensors operating normally
I (22705) DISPLAY: 📢 Displaying from file: ./main/display.c, line: 15
I (22705) DISPLAY: 📺 Message: Status Check Complete
I (24605) LED: ✅ LED ON from file: ./main/led.c, line: 20
I (24605) LED: 🟢 LED is now ON
I (24605) LED: 🔄 LED toggled from file: ./main/led.c, line: 38
I (24705) MAIN: === Loop 6 ===
I (24705) DISPLAY: 🧹 Screen cleared from file: ./main/display.c, line: 28
I (24705) DISPLAY: ✨ Display ready for new content
I (24705) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (24705) SENSOR: 🌡️  Temperature: 26.7°C
I (24705) SENSOR: 💧 Humidity: 65.1%
I (24705) DISPLAY: 📊 Data display from file: ./main/display.c, line: 21
I (24705) DISPLAY: 📈 Value 1: 32.50
I (24705) DISPLAY: 📉 Value 2: 67.00
I (24705) DISPLAY: 📢 Displaying from file: ./main/display.c, line: 15
I (24705) DISPLAY: 📺 Message: LED Status: ON
I (26705) MAIN: === Loop 7 ===
I (26705) DISPLAY: 🧹 Scr een cleared from file: ./main/display.c, line: 28
I (26705) DISPLAY: ✨ Display ready for new content
I (26705) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18
I (26705) SENSOR: 🌡️  Temperature: 29.2°C
I (26705) SENSOR: 💧 Humidity: 95.9%
I (26705) DISPLAY: 📊 Data display from file: ./main/display.c, line: 21
I (26705) DISPLAY: 📈 Value 1: 33.50
I (26705) DISPLAY: 📉 Value 2: 68.00
I (26705) DISPLAY: 📢 Displaying from file: ./main/display.c, line: 15
I (26705) DISPLAY: 📺 Message: LED Status: ON
I (27605) LED: ❌ LED OFF from file: ./main/led.c, line: 27
I (27605) LED: 🔴 LED is now OFF
I (27605) LED: 🔄 LED toggled from file: ./main/led.c, line: 38
```

### คำถามทบทวน
1. Multiple Source Files: เหตุใดต้องแยก source code เป็นหลายไฟล์? <br>
```

```
2. CMakeLists.txt Management: การเพิ่มไฟล์ source ใหม่ต้องแก้ไขอะไรบ้าง? <br>
```

```
3. Header Files: บทบาทของไฟล์ .h คืออะไร และทำไมต้องมี? <br>
```

```
4. Include Directories: เหตุใด CMakeLists.txt ต้องระบุ INCLUDE_DIRS? <br>
```

```
5. Git Ignore: ไฟล์ .gitignore ช่วยอะไรในการจัดการ ESP32 project? <br>
```

```
6. Task Management: การใช้ FreeRTOS task ในโมดูล LED ช่วยอะไร? <br>
```

```
7. Code Organization: ข้อดีของการแยกโมดูล sensor, display, led เป็นไฟล์แยกคืออะไร? <br>
```

```

### บันทึกผลการทดลอง
ขั้นตอนที่ 1 (เฉพาะ sensor.c): <br>
จำนวนไฟล์ source: 4 <br>
ขนาด binary: 163041 bytes <br>
การทำงาน: <br>
I (295) SENSOR: 📊 Reading sensor data from file: ./main/sensor.c, line: 18 <br>
I (305) SENSOR: 🌡️  Temp erature: 30.1°C <br>
I (365) SENSOR: 💧 Humidity: 98.2% <br>

ขั้นตอนที่ 2 (เพิ่ม display.c): <br>
จำนวนไฟล์ source: 6 <br>
ขนาด binary: 163925 bytes <br>
การทำงาน: <br>
I (16655) DISPLAY: 📢 Displaying from file: ./main/display.c, line: 15 <br>
I (16675) DISPLAY: 📺 Message: Status Check Complete <br>

ขั้นตอนที่ 3 (เพิ่ม led.c): <br>
จำนวนไฟล์ source: 8 <br>
ขนาด binary: 164873 bytes <br>
การทำงาน: <br>
I (24605) LED: ✅ LED ON from file: ./main/led.c, line: 20 <br>
I (24605) LED: 🟢 LED is now ON <br>
I (24605) LED: 🔄 LED toggled from file: ./main/led.c, line: 38 <br>

### รูปภาพการทดลอง
<img width="751" height="640" alt="image" src="https://github.com/user-attachments/assets/4a93804c-9025-404d-8a36-7fe03a61e5f1" />
