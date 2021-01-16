# sr-traffic

[![Build Status](https://travis-ci.com/LarsBergqvist/sr-traffic.svg?branch=main)](https://travis-ci.com/LarsBergqvist/sr-traffic)

# Demo

https://larsbergqvist.github.io/sr-traffic/

An Angular 11 application that displays current traffic messages from the Open API of Swedish Public Radio. The messages are fetched per traffic area in Sweden. You can fetch your closest area by letting the application read your position from the browser.  
From a traffic message, you can open a sidebar that contains a map where the event for the message is marked. The map view uses OpenLayers / OpenStreetMap.

# Setup

```
cd sr-traffic
yarn install
yarn startSSL  

https://localhost:4300/

```

# Screenshots

![Alt text](https://github.com/LarsBergqvist/sr-traffic/blob/main/screenshot1.png?raw=true 'Traffic messages list')
![Alt text](https://github.com/LarsBergqvist/sr-traffic/blob/main/screenshot2.png?raw=true 'Map sidebar')
