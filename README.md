# <img alt="RRC" title="Relay Remote Control" src="./app/src/main/ic_launcher-web.png" width="100" height="100"> Relay Remote Control repository
This app for android, allow you to turn ON/OFF a relay connected to a raspberry Pi by a Gpio port.

## Required
Require the server side installed [Gpio Control Relay server](https://github.com/nearlg/gcr-server).

There is a [plugin for Kodi](https://github.com/nearlg/script.service.relay) based on gcr-server.

## Instructions
Download the apk and install it.
In the main window there is a list view of servers. You can add a new server on the _plus_ floating 
button (in the bottom|right corner).

<img alt="List of server screenshot" title="List of server screenshot" src="./doc/server-list.png" style="max-width:30%;">

Once a server is selected, there is a list of relays and you can add a new relay (already connected 
physically to the Raspberry Pi), just to configure the server. It is necessary to do only once.
To add a new relay, use the option menu at the top.

<img alt="List of relays screenshot" title="List of relays screenshot" src="./doc/relay-list.png" style="max-width:30%;">

Also is possible to edit and delete a relay.

<img alt="Relay adding form screenshot" title="Relay adding form screenshot" src="./doc/add-relay.png" style="max-width:30%;">
<img alt="Relay context menu screenshot" title="Relay context menu screenshot" src="./doc/relay-context-menu.png" style="max-width:30%;">
