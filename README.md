INFO ESPHome 2026.10.0
INFO Loaded validated config cache for pt-100ds18b20sender.yaml, skipping validation.
INFO Starting log output from 192.168.1.105 using esphome API
INFO Successfully resolved sauna-saatja @ 192.168.1.105 in 0.000s
INFO Successfully connected to sauna-saatja @ 192.168.1.105 in 4.205s
INFO Successful handshake with sauna-saatja @ 192.168.1.105 in 0.014s
[12:12:54.139][I][app:164]: ESPHome version 2026.10.0 compiled on 2026-10-26 12:05:32 +0200
[12:12:54.139][I][app:171]: ESP32 Chip: ESP32 rev3.1, 2 core(s)
[12:12:54.139][W][app:189]: Set flash_chip: generic under esp32 > framework > advanced to save IRAM
[12:12:54.139][W][app:201]: Chip rev >= 3.0 detected. Set minimum_chip_revision: "3.1" under esp32 > framework > advanced to reduce binary size
[12:12:54.143][W][app:228]: Bootloader supports SRAM1 as IRAM (+40KB). Set sram1_as_iram: true under esp32 > framework > advanced
[12:12:54.167][C][logger:218]: Logger:
[12:12:54.167][C][logger:218]:   Max Level: DEBUG
[12:12:54.167][C][logger:218]:   Initial Level: DEBUG
[12:12:54.167][C][logger:225]:   Log Baud Rate: 115200
[12:12:54.167][C][logger:225]:   Hardware UART: UART0
[12:12:54.167][C][logger:234]:   Task Log Buffer Size: 768 bytes
[12:12:54.194][C][spi:066]: SPI bus:
[12:12:54.196][C][spi:131]:   CLK Pin: GPIO18
[12:12:54.197][C][spi:131]:   SDI Pin: GPIO19
[12:12:54.197][C][spi:131]:   SDO Pin: GPIO23
[12:12:54.201][C][spi:074]:   Using HW SPI: SPI2_HOST
[12:12:54.217][C][gpio.one_wire:020]: GPIO 1-wire bus:
[12:12:54.217][C][gpio.one_wire:131]:   Pin: GPIO4
[12:12:54.217][C][gpio.one_wire:088]:   Found devices:
[12:12:54.217][C][gpio.one_wire:091]:     0x213c01f0959dca28 (DS18B20)
[12:12:54.773][C][max31865:017]: MAX31865 'Sauna temperatuur'
[12:12:54.773][C][max31865:017]:   State Class: 'measurement'
[12:12:54.773][C][max31865:017]:   Unit of Measurement: '°C'
[12:12:54.773][C][max31865:017]:   Accuracy Decimals: 1
[12:12:54.774][C][max31865:166]:   Device Class: 'temperature'
[12:12:54.774][C][max31865:131]:   CS Pin: GPIO5
[12:12:54.775][C][max31865:340]:   Update Interval: 2.000s
[12:12:54.779][C][max31865:083]:   Reference Resistance: 430.00Ω
[12:12:54.779][C][max31865:083]:   RTD: 3-wire 100.00Ω
[12:12:54.779][C][max31865:083]:   Mains Filter: 50 Hz
[12:12:54.781][C][dallas.temp.sensor:029]: Dallas Temperature Sensor:
[12:12:54.781][C][dallas.temp.sensor:034]:   Address: 0x213c01f0959dca28 (DS18B20)
[12:12:54.781][C][dallas.temp.sensor:035]:   Resolution: 12 bits
[12:12:54.781][C][dallas.temp.sensor:340]:   Update Interval: 2.000s
[12:12:54.781][C][network:050]: Network:
[12:12:54.781][C][network:050]:   TCP send buffer: 5760 bytes
[12:12:54.783][C][wifi:1688]: WiFi:
[12:12:54.783][C][wifi:1688]:   Local MAC: E0:8C:FE:2F:B8:64
[12:12:54.783][C][wifi:1688]:   Connected: YES
[12:12:54.783][C][wifi:1392]:   IP Address: 192.168.1.105
[12:12:54.783][C][wifi:1403]:   SSID: 'Mardikas'
[12:12:54.783][C][wifi:1403]:   BSSID: 98:DA:C4:FC:F8:9C
[12:12:54.783][C][wifi:1403]:   Hostname: 'sauna-saatja'
[12:12:54.783][C][wifi:1403]:   Signal strength: -14 dB ▂▄▆█
[12:12:54.783][C][wifi:1403]:   Channel: 11
[12:12:54.783][C][wifi:1403]:   Subnet: 255.255.255.0
[12:12:54.783][C][wifi:1403]:   Gateway: 192.168.1.1
[12:12:54.783][C][wifi:1403]:   DNS1: 192.168.1.1
[12:12:54.783][C][wifi:1403]:   DNS2: 0.0.0.0
[12:12:54.786][C][esphome.ota:129]: Over-The-Air updates:
[12:12:54.786][C][esphome.ota:129]:   Address: sauna-saatja.local:3232
[12:12:54.786][C][esphome.ota:129]:   Version: 2
[12:12:54.786][C][safe_mode:058]: Safe Mode:
[12:12:54.786][C][safe_mode:058]:   Successful after: 60s
[12:12:54.786][C][safe_mode:058]:   Invoke after: 10 attempts
[12:12:54.786][C][safe_mode:058]:   Duration: 300s
[12:12:54.787][C][safe_mode:079]:   Bootloader rollback: supported
[12:12:54.787][C][api:368]: Server:
[12:12:54.787][C][api:368]:   Address: sauna-saatja.local:6053
[12:12:54.787][C][api:368]:   Listen backlog: 4
[12:12:54.787][C][api:368]:   Max connections: 5
[12:12:54.787][C][api:380]:   Noise encryption: NO
[12:12:54.788][C][mdns:324]: mDNS:
[12:12:54.788][C][mdns:324]:   Hostname: sauna-saatja
[12:12:55.265][E][max31865:100]: SPI bus read all 0 or all 1 (0x0000), check MAX31865 wiring & power.
[12:12:55.373][S][sensor]: 'Sauna temperatuur' >> nan °C
[12:12:56.003][D][dallas.temp.sensor:054]: 'Vee temperatuur': Got Temperature=21.625000°C
[12:12:56.106][S][sensor]: 'Vee temperatuur' >> 21.6 °C
[12:12:57.264][E][max31865:100]: SPI bus read all 0 or all 1 (0x0000), check MAX31865 wiring & power.
[12:12:57.368][S][sensor]: 'Sauna temperatuur' >> nan °C
[12:12:58.002][D][dallas.temp.sensor:054]: 'Vee temperatuur': Got Temperature=21.625000°C
[12:12:58.102][S][sensor]: 'Vee temperatuur' >> 21.6 °C
[12:12:59.263][E][max31865:100]: SPI bus read all 0 or all 1 (0x0000), check MAX31865 wiring & power.
[12:12:59.368][S][sensor]: 'Sauna temperatuur' >> nan °C
[12:13:00.005][D][dallas.temp.sensor:054]: 'Vee temperatuur': Got Temperature=21.625000°C
[12:13:00.100][S][sensor]: 'Vee temperatuur' >> 21.6 °C
[12:13:01.364][E][max31865:100]: SPI bus read all 0 or all 1 (0x0000), check MAX31865 wiring & power.
[12:13:01.369][S][sensor]: 'Sauna temperatuur' >> nan °C
[12:13:02.012][D][dallas.temp.sensor:054]: 'Vee temperatuur': Got Temperature=21.625000°C
