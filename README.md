# Node Sonos Youtube service

## Usage

* npm install
* Copy config.json.example to config.json
* Edit config.json
* Tip, install https://github.com/codealchemist/youtube-audio-server for the mediaServer
* run `node app.js

## Sonos setup

Go to: http://{IP address of player}:1400/customsd.htm

* SID: ex. 255
* Service Name: <name>
* Endpoint URL: http://host:port/soap
* Secure Endpoint URL: http://host:port/soap
* Polling Interval: 60
* Authentication SOAP Header Policy: Anonymous
* Presentation map: http://host:port/static/PresentationMap.xml
* Strings: http://host:port/static/Strings.xml
* ContainerType: Music Service
* Capabilities: Search
