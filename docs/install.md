# Install Ultimate UNRAID Dashboard
Last updated on 2020-12-31

This guide will show you how to setup UUD on your UNRAID Server.

## Dependencies
* UNRAID Plugin: Community Applications
* Docker: InfluxDB
* Docker: Telegraf
* Docker: Grafana
* Docker: Tautulli
* Docker: Varken
* CA Plugin: IPMI Tools
* License: GeoLite2

## Guide

### Install Community Applications
This is a must have for any UNRAID Server. If you already have Community Applications (CA) installed, you can skip to the next step.

On your UNRAID server, click on the `Plugins` tab on your toolbar. You should see a option `Enter URL of remote plugin file or local plugin file`. 

Enter `https://raw.githubusercontent.com/Squidly271/community.applications/master/plugins/community.applications.plg` and click on the `Install` buton.

You should now see an `Apps` tab on your toolbar.

### Install InfluxDB
Click on the `Apps` tab in the toolbar.

In the search bar (upper right), search for `InfluxDB` and you should see one from `atribe`. Click the install button on the lower left of the card.

![[influx_01.png]]