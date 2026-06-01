# Power Updater

Public firmware update host for the ESP8266 D1 Mini Power Relay project.

The relay firmware checks:

```text
https://raw.githubusercontent.com/onekevinc/Power-Updater/main/latest.json
```

Firmware binaries live under `firmware/` and are downloaded directly by the D1 Mini using the URL in `latest.json`.

Source code, PWA files, Node-RED flow, and project docs remain in the private `Power` repo.
