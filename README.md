# prtg_api

A class library for PRTG API.

Manipulate and monitor a PRTG instance using python.

## Requirements

Uses python libraries: requests, xmltodict, json, datetime, operator.itemgetter, logging, time

## Usage

Create a PRTGServer object, then run server.populate_devices().

Then, access the devices dictionary from server.devices[] where the prtg device object ID is the key.

For each device in server.devices, there is a dictionary of sensors (device.sensor[]), set up in the same way as devices[] is a property of PRTGServer.

There is more to it, but I haven't documented it fully (yet), look as class structure/comments to see what else is possible.
This project is an example of how this library could be employed: <https://github.com/timothyquan/waynes_power_commander>

![UML](/assets/uml.png)

## License

[MIT](https://choosealicense.com/licenses/mit/)
