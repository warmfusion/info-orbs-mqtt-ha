# Home Assistant - Info Orbs MQTT 

* This repo assumes you are running Home Assistant and also have one or more working [Info Orbs](https://github.com/brettdottech/info-orbs)
* Ensure you have the Info Orbs MQTT widgets configured correctly to communication to MQTT  
* Also requires the MQTT Integration in Home Assistant  
    
[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://raw.githubusercontent.com/warmfusion/info-orbs-mqtt-ha/refs/heads/main/blueprints/info-orb-mqtt-widget.yaml)

## DrawStrings

This variation of [dreed47/info-orbs-mqtt-ha](https://github.com/dreed47/info-orbs-mqtt-ha)'s blueprint, replaces much of their templated parameters with a naieve template only equivalent.

This then uses [!200](https://github.com/brettdottech/info-orbs/pull/200)'s implementation of 'DrawStrings' to render more complex shapes through primitives.

The template has been given a set of example drawings to demonstrate this functionality in more detail.


