# esp32-ot-rcp-builder

based on @rayanamal's [$5 OTBR guide](https://community.home-assistant.io/t/make-your-own-thread-border-router-for-just-5/962780)

this repository exists solely to build the 3 images in a clean CI environment

### flashing

using [esptool](https://github.com/espressif/esptool), run

```bash
esptool -p PORT write-flash 0x0 firmware.bin
```
