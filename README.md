# easun-smg-ii-ha-config

Home Assistant configuration to monitor and control a EASUN SMG II inverter wireless using elfin EW10A dongle linked to RS232 port.

# Installation

Copy easun_smg_ii*.yaml files to the config directory or subdirectory.
In the easun_smg_ii.yaml file, set the correct host and port for your EW10A module.

Add the following to /config/configuration.yaml:
```bash
homeassistant:
   packages:
     easun_smg_ii: !include [subdirectory/]easun_smg_ii.yaml
````
