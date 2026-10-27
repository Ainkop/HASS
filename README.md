Logs - ESP32 E-Paper Receiver
OTA
INFO ESPHome 2026.10.0
INFO Loaded validated config cache for esp-now-rectftscreen.yaml, skipping validation.
INFO Starting log output from 192.168.1.107 using esphome API
INFO Successfully resolved esp32-epaper-receiver @ 192.168.1.107 in 0.000s
INFO Successfully connected to esp32-epaper-receiver @ 192.168.1.107 in 4.121s
INFO Successful handshake with esp32-epaper-receiver @ 192.168.1.107 in 0.011s
[20:58:23.892][I][app:164]: ESPHome version 2026.10.0 compiled on 2026-10-27 20:57:28 +0200
[20:58:23.893][I][app:171]: ESP32 Chip: ESP32 rev3.1, 2 core(s)
[20:58:23.894][W][app:189]: Set flash_chip: generic under esp32 > framework > advanced to save IRAM
[20:58:23.894][W][app:201]: Chip rev >= 3.0 detected. Set minimum_chip_revision: "3.1" under esp32 > framework > advanced to reduce binary size
[20:58:23.897][W][app:228]: Bootloader supports SRAM1 as IRAM (+40KB). Set sram1_as_iram: true under esp32 > framework > advanced
[20:58:23.922][C][logger:218]: Logger:
[20:58:23.922][C][logger:218]:   Max Level: DEBUG
[20:58:23.922][C][logger:218]:   Initial Level: DEBUG
[20:58:23.922][C][logger:225]:   Log Baud Rate: 115200
[20:58:23.922][C][logger:225]:   Hardware UART: UART0
[20:58:23.922][C][logger:234]:   Task Log Buffer Size: 768 bytes
[20:58:23.955][C][spi:066]: SPI bus:
[20:58:23.960][C][spi:131]:   CLK Pin: GPIO18
[20:58:23.960][C][spi:131]:   SDI Pin: 
[20:58:23.960][C][spi:131]:   SDO Pin: GPIO23
[20:58:23.964][C][spi:074]:   Using HW SPI: SPI2_HOST
[20:58:23.981][C][waveshare_epaper:481]: Waveshare E-Paper
[20:58:23.981][C][waveshare_epaper:481]:   Rotations: 90 °
[20:58:23.981][C][waveshare_epaper:481]:   Dimensions: 250px x 122px
[20:58:23.982][C][waveshare_epaper:502]:   Model: 2.13in (TTGO B74)
[20:58:23.984][C][waveshare_epaper:514]:   Full Update Every: 1
[20:58:23.984][C][waveshare_epaper:131]:   Reset Pin: GPIO16
[20:58:23.984][C][waveshare_epaper:131]:   DC Pin: GPIO17
[20:58:23.984][C][waveshare_epaper:131]:   Busy Pin: GPIO4
[20:58:23.985][C][waveshare_epaper:340]:   Update Interval: 60.000s
[20:58:24.005][C][network:050]: Network:
[20:58:24.005][C][network:050]:   TCP send buffer: 5760 bytes
[20:58:24.039][C][captive_portal:162]: Captive Portal:
[20:58:24.039][C][wifi:1688]: WiFi:
[20:58:24.039][C][wifi:1688]:   Local MAC: E0:8C:FE:2E:A0:20
[20:58:24.039][C][wifi:1688]:   Connected: YES
[20:58:24.040][C][wifi:1392]:   IP Address: 192.168.1.107
[20:58:24.040][C][wifi:1403]:   SSID: 'Mardikas'
[20:58:24.040][C][wifi:1403]:   BSSID: 98:DA:C4:FC:F8:9C
[20:58:24.040][C][wifi:1403]:   Hostname: 'esp32-epaper-receiver'
[20:58:24.040][C][wifi:1403]:   Signal strength: -40 dB ▂▄▆█
[20:58:24.040][C][wifi:1403]:   Channel: 11
[20:58:24.040][C][wifi:1403]:   Subnet: 255.255.255.0
[20:58:24.040][C][wifi:1403]:   Gateway: 192.168.1.1
[20:58:24.040][C][wifi:1403]:   DNS1: 192.168.1.1
[20:58:24.040][C][wifi:1403]:   DNS2: 0.0.0.0
[20:58:24.075][C][esphome.ota:129]: Over-The-Air updates:
[20:58:24.075][C][esphome.ota:129]:   Address: esp32-epaper-receiver.local:3232
[20:58:24.075][C][esphome.ota:129]:   Version: 2
[20:58:24.076][C][safe_mode:058]: Safe Mode:
[20:58:24.076][C][safe_mode:058]:   Successful after: 60s
[20:58:24.076][C][safe_mode:058]:   Invoke after: 10 attempts
[20:58:24.076][C][safe_mode:058]:   Duration: 300s
[20:58:24.076][C][safe_mode:079]:   Bootloader rollback: supported
[20:58:24.097][C][web_server.ota:256]: Web Server OTA
[20:58:24.118][C][api:368]: Server:
[20:58:24.118][C][api:368]:   Address: esp32-epaper-receiver.local:6053
[20:58:24.118][C][api:368]:   Listen backlog: 4
[20:58:24.118][C][api:368]:   Max connections: 5
[20:58:24.118][C][api:380]:   Noise encryption: NO
[20:58:24.119][S][sensor]: 'Sauna (PT100)' >> 25.3 °C
[20:58:24.133][C][packet_transport:547]: Packet Transport:
[20:58:24.133][C][packet_transport:547]:   Platform: espnow
[20:58:24.133][C][packet_transport:547]:   Encrypted: NO
[20:58:24.133][C][packet_transport:547]:   Ping-pong: NO
[20:58:24.138][C][packet_transport:564]:   Remote host: esp32-ds18b20-pt100
[20:58:24.138][C][packet_transport:565]:     Encrypted: NO
[20:58:24.152][C][packet_transport:570]:     Sensor: boiler_sensor
[20:58:24.153][C][packet_transport:570]:     Sensor: pt100_sensor
[20:58:24.176][C][mdns:324]: mDNS:
[20:58:24.176][C][mdns:324]:   Hostname: esp32-epaper-receiver
[20:58:24.177][C][espnow:132]: espnow:
[20:58:24.177][C][espnow:145]:   Own address: E0:8C:FE:2E:A0:20
[20:58:24.177][C][espnow:145]:   Version: v2
[20:58:24.177][C][espnow:145]:   Wi-Fi channel: 11
[20:58:24.182][C][espnow:151]:   Wi-Fi enabled: YES
[20:58:25.373][S][sensor]: 'Boiler (DS18B20)' >> 22.6 °C
[20:58:26.117][S][sensor]: 'Sauna (PT100)' >> 25.3 °C
