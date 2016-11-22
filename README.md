
Agile Bluetooth Low Energy components
===

This repository contains the alpha version of Agile Bluetooth Low Energy protocol implementation:


Exposes the [iot.agile.Protocol](http://agile-iot.github.io/agile-api-spec/docs/html/api.html#iot_agile_Protocol) interface

- DBus interface name **iot.agile.protocol.BLE**
- DBus interface path **/iot/agile/protocol/BLE**

Launching the Protocol
---

Under the `scripts` directory you can find different scripts to setup and start / stop the modules.

*Note* A `java` 8 compatible JDK and maven (`mvn`) must be already available in the system.

- `./scripts/start.sh` will install (if not available) all the dependencies required to run and start the module.

- `./scripts/stop.sh` will stop/kill the modules.

-  `./scripts/install-deps.sh` is used to setup all the java and native dependencies to a local directory (placed in the `./deps` folder)
