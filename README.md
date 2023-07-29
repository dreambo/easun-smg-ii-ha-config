# easun-smg-ii-ha-config

Home Assistant configuration to monitor and control a EASUN SMG II inverter wirelessly using elfin EW10A dongle linked to RS232 port.
many thanks to https://github.com/gregoriusin/easun-smg-ii-ha-config and https://github.com/syssi/esphome-smg-ii

# Installation

Copy easun_smg_ii*.yaml files to the config directory or subdirectory.
In the easun_smg_ii.yaml file, set the correct host and port for your EW10A module.

Add the following to /config/configuration.yaml:
```bash
homeassistant:
   packages:
     easun_smg_ii: !include [subdirectory/]easun_smg_ii.yaml
````
