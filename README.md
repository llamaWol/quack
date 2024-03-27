<h1> ⊙.⊙ </h1>

### Features

### Todo Features

- Webserver
    - [example http server](https://github.com/espressif/esp-idf/tree/v5.2.1/examples/protocols/http_server)
    - [example https server](https://github.com/espressif/esp-idf/tree/v5.2.1/examples/protocols/https_server)
- Wifi
    - Host access point
    - Beacon spam
    - Deauth attack
    - Connect to access point (mim/dns spoof attack)
    - Sniff packets (capture handshakes, detect deauth attack)
    - [example ap && sta](https://github.com/espressif/esp-idf/tree/v5.2.1/examples/wifi/softap_sta)
    - [example ap || sta](https://github.com/espressif/esp-idf/tree/v5.2.1/examples/wifi/getting_started)
    - [example sniffer](https://github.com/espressif/esp-idf/tree/v5.2.1/examples/network/simple_sniffer)
- Bluetooth
    - [examples](https://github.com/espressif/esp-idf/tree/v5.2.1/examples/bluetooth)
- HID
    - Control keyboard & mouse, maybe midi?
    - [examples](https://github.com/espressif/esp-idf/tree/v5.2.1/examples/preripherals/usb/device)
- &micro;SD Card
    - Show up as USB MSC
    - Store scripts or config (maybe to separate (hidden) partition)
    - [example sdmmc](https://github.com/espressif/esp-idf/tree/v5.2.1/examples/storage/sd_card/sdmmc)
    - [example USB MSC](https://github.com/espressif/esp-idf/tree/v5.2.1/examples/peripherals/usb/device/tusb_msc)
- LED
    - Show attack status (nothing, attacking, done)
    - Show station status (connected to ap or not)
    - [examples](https://github.com/espressif/esp-idf/tree/v5.2.1/examples/peripherals/ledc)
- Parser for [hak5 3.0 syntax](https://docs.hak5.org/hak5-usb-rubber-ducky/duckyscript-tm-quick-reference)
