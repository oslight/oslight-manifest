OS Light Manifest
===============

A simple open source lightbulb project built on the Open Source Foundries Zephyr microPlatform.  This sample is built against the latest public releases available at [Open Source Foundries on Github](http://github.com/opensourcefoundries.com).

----------
To rebuild the OSLight applications, setup your environment according to Open Source Foundries Zephyr microPlatform guidelines and then you can use repo and the zmp command-line application to rebuild and flash.  The following samples work on MacOS and Linux.

Get the source code:
```
repo init -u https://github.com/oslight/oslight-manifest
```
Build the application(s):
```
./zmp build -b nrf52_blenano2 oslight-samples/lwm2m-light/
or
./zmp build -b nrf52_blenano2 oslight-samples/ble-mesh/
```
Flash the code to the BLE Nano2:
```
./zmp flash -b nrf52_blenano2 oslight-samples/lwm2m-light/
or
./zmp flash -b nrf52_blenano2 oslight-samples/ble-mesh/
```
