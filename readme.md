My set of OpenHAB config files to automate the door on my hen house.

# Installation

    sudo apt-get install openhab-addon-binding-astro openhab-addon-binding-gpio openhab-addon-binding-http openhab-addon-binding-ntp openhab-addon-binding-weather openhab-addon-persistence-db4o openhab-addon-persistence-logging openhab-addon-persistence-rrd4j openhab-addon-binding-exec openhab-addon-action-astro

# OpenHAB config

Add to openhab.cfg

```
############################## Astro Binding ##############################
#
# Your latitude
astro:latitude=47.399023

# Your longitude
astro:longitude=8.405904

# Refresh interval for some properties in seconds (optional, defaults to disabled)
astro:interval=3600
```

# Electronics

(This section follows later...)