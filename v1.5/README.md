# Ultimate UNRAID Dashboard 1.5.x
The Ultimate UNRAID Dashboard <span style="color:green">Version 1.5</span> is here! This is another HUGE 😁 update adding <span style="color:green">INTEGRATED PLEX Monitoring</span> via Varken/Tautulli. This update is loosely derived from the official Varken dashboard, but I stripped it down to the bolts, modded the crap out of it, and streamlined it with a straight Plex focus. Honestly, the only code that sill remains from their official dash is the single geo-mapping graph, as it is not actually an editable panel, but rather straight JSON code. I wanted to say thank you to that team for providing a great baseline to start from, and all of their previous work!

The UUD Version 1.5 adds <span style="color:green">50 new Panels within 3 new sections</span>. I have placed these strategically within the UUD right below the Overwatch section, as this is the second data set that I would want to see, right after my overall server health. As always, with greater features, comes a greater need for plugins and dependencies. I have provided links and resources below to help you along.

## <span style="color:red">New Dependencies</span>

* <span style="color:red">Install guides/tutorials:</span>
    * [https://github.com/Boerderij/Varken](https://github.com/Boerderij/Varken)
    * [https://wiki.cajun.pro/books/varken/chapter/installation](https://wiki.cajun.pro/books/varken/chapter/installation)
    * [https://dev.maxmind.com/geoip/geoip2/geolite2/](https://dev.maxmind.com/geoip/geoip2/geolite2/)
* <span style="color:red">Dockers:</span>
    * Varken (Install with default setup / Follow current project install guide)
    * Tautuilli (Install with default setup / Follow current project install guide)
* <span style="color:red">Docker AppData:</span>
    * Varken config (Follow varken install guide)
* <span style="color:red">New Grafana data source:</span>
    * "Varken"
* <span style="color:red">New Grafana plugins</span>
    * Pie Chart Panel
        * Run following command in Docker: <span style="color:green">grafana-cli plugins install grafana-piechart-panel</span>
    * World Map
        * Run following command in Docker: <span style="color:green">grafana-cli plugins install grafana-worldmap-panel</span>
* <span style="color:red">Third party:</span>
    * FREE GeoLite2 license registration (Follow Varken install guide)
        * Without this, the MAP WILL NOT WORK.

<span style="color:red">Please Note: This release is an example tailored to MY Plex setup/library. The intent here is that you will take this and modify it for your Plex Library/Setup. You have everything you require to template new panels and to add new media sections as needed!</span>

## <span style="color:red">Highlights</span>

* <span style="color:green">Real time Plex monitoring</span>
    * Extremely detailed breakdown of all current streams
    * Current number of streams
    * Internal and external streaming bandwidth breakdown
    * Stream origination (geo location) with interactive map
    * Streaming types
    * Streaming devices
    * Detailed user monitoring
    * Current library statistics broken out by library sections
* <span style="color:green">Plex library growth</span>
    * Plex library growth over time (day/week/month/year)
        * Currently templated for following media sections
            * TV shows
            * Movies
            * Documentary TV shows
            * Documentary movies
            * Anime shows
            * Music
            * You can add more...
* <span style="color:green">Historical Plex monitoring</span>
    * Heat maps to see your overall streaming saturation (last day/week/month/year)
    * Device types (last month)
    * Stream types (last month)
    * Media types (last month)
    * Media streaming qualities (last month)
    * Stream log (last week with limit of last 1,000 for performance reasons)
        * Log captures all streaming activity via 10 minute intervals

## Screenshots
![[02.png]]
![[03.png]]
![[04.png]]