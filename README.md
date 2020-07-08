Example project for ESP8266/NodeMCU showing how to create an access point with a captive portal, loading files from the SPIFFS file server. Requires installation of https://github.com/esp8266/arduino-esp8266fs-plugin . Files to be used in the captive portal should be placed in the sketch "data" folder, and uploaded using the plugin. The landing page must be named "index.html"; all other files can have any name.

---

Serlecu: I'll try to adapt it to ES32.

Will require a [filesystem uploader](https://github.com/me-no-dev/arduino-esp32fs-plugin.git). Files to be used in the captive portal should be placed in the sketch "data" folder, and uploaded using the plugin. The landing page must be named "index.html"; all other files can have any name.
