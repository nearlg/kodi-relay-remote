# <img alt="RRC" title="Relay Remote Control" src="./docs/app-inkscape-logo.png"> Relay Remote Control repository
This app for android, allow you to turn ON/OFF a relay connected to a raspberry Pi by a Gpio port.

Master branch [![Master Build Status](https://travis-ci.org/nearlg/gcr-cli-android.svg?branch=master)](https://travis-ci.org/nearlg/gcr-cli-android)

Next branch [![Next Build Status](https://travis-ci.org/nearlg/gcr-cli-android.svg?branch=next)](https://travis-ci.org/nearlg/gcr-cli-android)

## Required
Require the server side installed [Gpio Control Relay server](https://github.com/nearlg/gcr-server).

There is a [plugin for Kodi](https://github.com/nearlg/script.service.relay) based on gcr-server.

## Instructions
Download the apk and install it.
In the main window there is a list view of servers. You can add a new server on the _plus_ floating 
button (in the bottom|right corner).

<img alt="List of server screenshot" title="List of server screenshot" src="./docs/server-list.png" width="200" height="350">

Once a server is selected, there is a list of relays and you can add a new relay (already connected 
physically to the Raspberry Pi), just to configure the server. It is necessary to do only once.
To add a new relay, use the option menu at the top.

<img alt="List of relays screenshot" title="List of relays screenshot" src="./docs/relay-list.png" width="200" height="350">

Also is possible to edit and delete a relay.

<img alt="Relay adding form screenshot" title="Relay adding form screenshot" src="./docs/add-relay.png" width="200" height="350">
<img alt="Relay context menu screenshot" title="Relay context menu screenshot" src="./docs/relay-context-menu.png" width="200" height="350">
