# The Repositiories

Different architectonical elements of the Pick By Light project are stored in different repositories.
So to help you find what you need, here is a list of repos with their contents.

## [Backend](https://github.com/PBL-Pick-By-Light/BE-Backend)

The [backend repo](https://github.com/PBL-Pick-By-Light/BE-Backend) contains code for a server with
- authorization
- database
- controllers
- http-Tests
- docker
  You can also start by reading the [documentation](https://git.thm.de/softwaretechnik-projekt-pick-by-light-system-wise21_22/pbl-backend/pbl-backend/-/wikis/home).

## [Frontend](https://github.com/PBL-Pick-By-Light/FE-Frontend)

All the GUIs!
[This repo](https://github.com/PBL-Pick-By-Light/FE-Frontend) contains the code for a webapplication to comfortably send requests to backend and embedded systems. There are pages for login, search results, viewing items, options…
Of course there is also [documentation](https://github.com/PBL-Pick-By-Light/FE-Wiki-and-Documentation) for all these files.

## Embedded Systems

Everything you need to physically build the project and code for low-level servers.

### [Hardware Design](https://github.com/PBL-Pick-By-Light/ES-hardware-design)
Files for 3D-printing and explainations on how to upgrade your shelves using LEDs.

### [HTTP to MQTT](https://github.com/PBL-Pick-By-Light/ES-HttpToMqtt)
Code for a server that translates HTTP-Requests and sends corresponding MQTT messages to the ESP32s.

### [Firmware](https://github.com/PBL-Pick-By-Light/ES-ESP32-firmware)
Firmware of the ESP32s, which receive the MQTT messages and control the LEDs.

### [ES Documentation](https://github.com/PBL-Pick-By-Light/ES-Wiki-and-Documentation)
Further infos on the embedded systems part of the project.
