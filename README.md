INFO ESPHome 2026.10.0
INFO Loaded validated config cache for pt-100ds18b20sender.yaml, skipping validation.
INFO Starting log output from 192.168.1.105 using esphome API
INFO Successfully resolved esp32-ds18b20-pt100 @ 192.168.1.105 in 0.000s
INFO Successfully connected to esp32-ds18b20-pt100 @ 192.168.1.105 in 4.124s
INFO Successful handshake with esp32-ds18b20-pt100 @ 192.168.1.105 in 0.014s
[19:56:30.161][I][app:164]: ESPHome version 2026.10.0 compiled on 2026-10-27 19:53:00 +0200
[19:56:30.161][I][app:171]: ESP32 Chip: ESP32 rev3.1, 2 core(s)
[19:56:30.161][W][app:189]: Set flash_chip: generic under esp32 > framework > advanced to save IRAM
[19:56:30.170][W][app:201]: Chip rev >= 3.0 detected. Set minimum_chip_revision: "3.1" under esp32 > framework > advanced to reduce binary size
[19:56:30.170][W][app:228]: Bootloader supports SRAM1 as IRAM (+40KB). Set sram1_as_iram: true under esp32 > framework > advanced
[19:56:30.190][C][logger:218]: Logger:
[19:56:30.190][C][logger:218]:   Max Level: DEBUG
[19:56:30.190][C][logger:218]:   Initial Level: DEBUG
[19:56:30.194][C][logger:225]:   Log Baud Rate: 115200
[19:56:30.194][C][logger:225]:   Hardware UART: UART0
[19:56:30.194][C][logger:234]:   Task Log Buffer Size: 768 bytes
[19:56:30.217][C][spi:066]: SPI bus:
[19:56:30.223][C][spi:131]:   CLK Pin: GPIO18
[19:56:30.224][C][spi:131]:   SDI Pin: GPIO19
[19:56:30.224][C][spi:131]:   SDO Pin: GPIO23
[19:56:30.230][C][spi:074]:   Using HW SPI: SPI2_HOST
[19:56:30.249][C][spi:066]: SPI bus:
[19:56:30.249][C][spi:131]:   CLK Pin: GPIO14
[19:56:30.250][C][spi:131]:   SDI Pin: 
[19:56:30.250][C][spi:131]:   SDO Pin: GPIO13
[19:56:30.250][C][spi:074]:   Using HW SPI: SPI3_HOST
[19:56:30.264][C][gpio.one_wire:020]: GPIO 1-wire bus:
[19:56:30.265][C][gpio.one_wire:131]:   Pin: GPIO4
[19:56:30.265][C][gpio.one_wire:088]:   Found devices:
[19:56:30.265][C][gpio.one_wire:091]:     0x213c01f0959dca28 (DS18B20)
[19:56:30.920][C][ili9xxx:088]: ili9xxx
[19:56:30.920][C][ili9xxx:088]:   Rotations: 90 °
[19:56:30.920][C][ili9xxx:088]:   Dimensions: 320px x 240px
[19:56:30.921][C][ili9xxx:089]:   Width Offset: 0
[19:56:30.921][C][ili9xxx:089]:   Height Offset: 0
[19:56:30.921][C][ili9xxx:098]:   Color mode: 16bit
[19:56:30.921][C][ili9xxx:107]:   Data rate: 27MHz
[19:56:30.921][C][ili9xxx:131]:   Reset Pin: GPIO27
[19:56:30.922][C][ili9xxx:131]:   CS Pin: GPIO26
[19:56:30.922][C][ili9xxx:131]:   DC Pin: GPIO33
[19:56:30.925][C][ili9xxx:113]:   Color order: BGR
[19:56:30.925][C][ili9xxx:113]:   Swap_xy: NO
[19:56:30.925][C][ili9xxx:113]:   Mirror_x: NO
[19:56:30.925][C][ili9xxx:113]:   Mirror_y: NO
[19:56:30.925][C][ili9xxx:113]:   Invert colors: YES
[19:56:30.925][C][ili9xxx:123]:   => Failed to init Memory: YES!
[19:56:30.926][C][ili9xxx:340]:   Update Interval: 2.000s
[19:56:30.926][E][component:143]:   display is marked FAILED: unspecified
[19:56:30.926][C][max31865:017]: MAX31865 'Sauna temperatuur'
[19:56:30.926][C][max31865:017]:   State Class: 'measurement'
[19:56:30.926][C][max31865:017]:   Unit of Measurement: '°C'
[19:56:30.926][C][max31865:017]:   Accuracy Decimals: 1
[19:56:30.926][C][max31865:166]:   Device Class: 'temperature'
[19:56:30.926][C][max31865:131]:   CS Pin: GPIO5
[19:56:30.926][C][max31865:340]:   Update Interval: 2.000s
[19:56:30.927][C][max31865:083]:   Reference Resistance: 430.00Ω
[19:56:30.927][C][max31865:083]:   RTD: 3-wire 100.00Ω
[19:56:30.927][C][max31865:083]:   Mains Filter: 50 Hz
[19:56:30.927][C][dallas.temp.sensor:029]: Dallas Temperature Sensor:
[19:56:30.927][C][dallas.temp.sensor:034]:   Address: 0x213c01f0959dca28 (DS18B20)
[19:56:30.927][C][dallas.temp.sensor:035]:   Resolution: 12 bits
[19:56:30.927][C][dallas.temp.sensor:340]:   Update Interval: 2.000s
[19:56:30.927][C][network:050]: Network:
[19:56:30.927][C][network:050]:   TCP send buffer: 5760 bytes
[19:56:30.930][C][captive_portal:162]: Captive Portal:
[19:56:30.931][C][wifi:1688]: WiFi:
[19:56:30.931][C][wifi:1688]:   Local MAC: E0:8C:FE:2F:B8:64
[19:56:30.931][C][wifi:1688]:   Connected: YES
[19:56:30.931][C][wifi:1392]:   IP Address: 192.168.1.105
[19:56:30.931][C][wifi:1403]:   SSID: 'Mardikas'
[19:56:30.931][C][wifi:1403]:   BSSID: 98:DA:C4:FC:F8:9C
[19:56:30.931][C][wifi:1403]:   Hostname: 'esp32-ds18b20-pt100'
[19:56:30.931][C][wifi:1403]:   Signal strength: -13 dB ▂▄▆█
[19:56:30.931][C][wifi:1403]:   Channel: 11
[19:56:30.931][C][wifi:1403]:   Subnet: 255.255.255.0
[19:56:30.931][C][wifi:1403]:   Gateway: 192.168.1.1
[19:56:30.931][C][wifi:1403]:   DNS1: 192.168.1.1
[19:56:30.931][C][wifi:1403]:   DNS2: 0.0.0.0
[19:56:30.932][C][esphome.ota:129]: Over-The-Air updates:
[19:56:30.932][C][esphome.ota:129]:   Address: esp32-ds18b20-pt100.local:3232
[19:56:30.932][C][esphome.ota:129]:   Version: 2
[19:56:30.932][C][safe_mode:058]: Safe Mode:
[19:56:30.932][C][safe_mode:058]:   Successful after: 60s
[19:56:30.932][C][safe_mode:058]:   Invoke after: 10 attempts
[19:56:30.932][C][safe_mode:058]:   Duration: 300s
[19:56:30.937][C][safe_mode:079]:   Bootloader rollback: supported
[19:56:30.938][C][web_server.ota:256]: Web Server OTA
[19:56:30.938][C][api:368]: Server:
[19:56:30.938][C][api:368]:   Address: esp32-ds18b20-pt100.local:6053
[19:56:30.938][C][api:368]:   Listen backlog: 4
[19:56:30.938][C][api:368]:   Max connections: 5
[19:56:30.938][C][api:380]:   Noise encryption: NO
[19:56:30.938][C][packet_transport:547]: Packet Transport:
[19:56:30.938][C][packet_transport:547]:   Platform: espnow
[19:56:30.938][C][packet_transport:547]:   Encrypted: NO
[19:56:30.938][C][packet_transport:547]:   Ping-pong: NO
[19:56:30.939][C][packet_transport:555]:   Sensor: pt100_sensor
[19:56:30.939][C][packet_transport:555]:   Sensor: boiler_sensor
[19:56:30.944][C][mdns:324]: mDNS:
[19:56:30.944][C][mdns:324]:   Hostname: esp32-ds18b20-pt100
[19:56:30.944][C][espnow:132]: espnow:
[19:56:30.945][C][espnow:145]:   Own address: E0:8C:FE:2F:B8:64
[19:56:30.945][C][espnow:145]:   Version: v2
[19:56:30.945][C][espnow:145]:   Wi-Fi channel: 11
[19:56:30.945][C][espnow:151]:   Wi-Fi enabled: YES
[19:56:31.349][S][sensor]: 'Sauna temperatuur' >> 23.7 °C
[19:56:31.929][D][dallas.temp.sensor:054]: 'Boiler temperatuur': Got Temperature=22.500000°C
[19:56:32.018][S][sensor]: 'Boiler temperatuur' >> 22.5 °C
[19:56:33.339][S][sensor]: 'Sauna temperatuur' >> 23.7 °C
[19:56:33.930][D][dallas.temp.sensor:054]: 'Boiler temperatuur': Got Temperature=22.562500°C
[19:56:34.036][S][sensor]: 'Boiler temperatuur' >> 22.6 °C
[19:56:35.337][S][sensor]: 'Sauna temperatuur' >> 23.7 °C
[19:56:35.931][D][dallas.temp.sensor:054]: 'Boiler temperatuur': Got Temperature=22.500000°C
[19:56:36.031][S][sensor]: 'Boiler temperatuur' >> 22.5 °C
