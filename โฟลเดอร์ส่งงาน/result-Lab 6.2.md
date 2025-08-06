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


```

```
