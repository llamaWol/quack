<h1> ⊙.⊙ </h1>

### Features

- Startup
    1. Configure GPIO pins
    1. Autorun
        - If GPIO0 low (<note>or no autorun configured, optional</note>): USB MSC
        - If not GPIO0 low, autorun configured script
    1. Start webserver & access point
- Webserver
    - Run scripts
    - Show available storage on flash and &micro;SD card
    - Settings
        - Autorun
        - Show up as USB MSC if no autorun
        - Wifi ssid, password & channel
        - Webserver URL
        - Beacon spam list, landing page?
        - Access point to connect to (<note>ssid, password</note>)
        - Channel to sniff on
    - [http server](https://github.com/espressif/esp-idf/tree/v5.2.1/examples/protocols/http_server)
    - [https server](https://github.com/espressif/esp-idf/tree/v5.2.1/examples/protocols/https_server)
- Wifi
    - Host access point
    - (<note>optional</note>) beacon spam
    - (<note>optional</note>) deauth attacc
    - (<note>optional</note>) connect to access point (<note>mim/dns spoof attack</note>)
    - (<note>optional</note>) sniff packets (<note>capture handshakes, detect deauth attacc</note>)
    - [ap && sta](https://github.com/espressif/esp-idf/tree/v5.2.1/examples/wifi/softap_sta)
    - [ap || sta](https://github.com/espressif/esp-idf/tree/v5.2.1/examples/wifi/getting_started)
    - [sniffer](https://github.com/espressif/esp-idf/tree/v5.2.1/examples/network/simple_sniffer)
- Bluetooth
    - Logging / HID stuff or something I dont know
    - [example(s)](https://github.com/espressif/esp-idf/tree/v5.2.1/examples/bluetooth)
- HID
    - Control keyboard & mouse, maybe midi?
    - [example(s)](https://github.com/espressif/esp-idf/tree/v5.2.1/examples/preripherals/usb/device)
- &micro;SD Card
    - Show up as USB MSC
    - Store scripts or config (<note>maybe to separate (hidden) partition</note>)
    - [sdmmc](https://github.com/espressif/esp-idf/tree/v5.2.1/examples/storage/sd_card/sdmmc)
    - [USB MSC](https://github.com/espressif/esp-idf/tree/v5.2.1/examples/peripherals/usb/device/tusb_msc)
- LED
    - Show attacc status (<note>attacking, done, nothing?</note>)
    - [example(s)](https://github.com/espressif/esp-idf/tree/v5.2.1/examples/peripherals/ledc)

### Duckyscript

- Write parser for [official 3.0 syntax](https://docs.hak5.org/hak5-usb-rubber-ducky/duckyscript-tm-quick-reference)
- No LED control (<note>because will be done automatically</note>)

### Useful Repositories

<p></p>
Spacehuhn

- [WiFiDuck](https://github.com/SpacehuhnTech/WiFiDuck)
- [DeauthDetector](https://github.com/SpacehuhnTech/DeauthDetector)
- [esp8266_deauther](https://github.com/SpacehuhnTech/esp8266_deauther)
- [esp8266_beaconSpam](https://github.com/spacehuhn/esp8266_beaconSpam)
- [USBNova](https://github.com/SpacehuhnTech/USBNova)

<p></p>
Other

- [mmMikeKn/ESP32-WiFi-tool](https://github.com/mmMikeKn/ESP32-WiFi-tool)
- [wasdwasd0105/SuperWiFiDuck](https://github.com/wasdwasd0105/SuperWiFiDuck)
- [gloglas/WifiDuckV2](https://github.com/gloglas/WifiDuckV2)
- [tobozo/WUD-Ducky](https://github.com/tobozo/WUD-Ducky)
