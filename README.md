The idea is to implement a library for the esp8266 (e.g. NodeMCU uC) to control local Sonos sound boxes with rfid cards to play specific albums from spotify.

# my motivation
the build a children friendly, rfid cards contrallable device to play music and sound books for children.

# to do
- done: playing single tracks from spotify on defined sonos devices
to do:
- extend the lib to play whole spotify albums
- implement the rfid card reader
- implement the look up "dictionary" (rfid id-number to spotify URI album id)
- fancy and easy management of the dictonary
- multiple device / esp8266 support (web config of every device -> definde the sonos boxes to controll with this uC)



# Thanks, inspiration and help found here...

- https://github.com/ebartz/esp8266-rfid-sonos 
- https://github.com/hoveeman/music-cards
- https://github.com/Zepheus/esp8266-sonos-rfid Another esp8266 sonos example with code for discovering sonos devices
- https://github.com/jishi/node-sonos-http-api
- https://gist.github.com/dogrocker/f998dde4dbac923c47c1 - very basic connection manager that lacks some vital parts
- https://github.com/tzapu/WiFiManager ESP8266 WiFi Connection manager with web captive portal. Works well but I didn't want the captive portal
- http://jpmens.net/2010/03/16/sonos-pause-switch/ A simple arduino sonos pause swich that showed me the basics
- https://github.com/DjMomo/sonos/blob/master/sonos.class.php a nice sonos php library that I based my arduino functions on
- https://github.com/tmittet/sonos Yet another well working sonos ESP library


# old description ... 


this fork should be the port for esp8266
# sonos
This library makes interfacing an Arduino with your Sonos system a breeze. The library supports both controlling and reading the state of your Sonos components.  Playing URIs, files, online radio stations, playlists, and line-in is supported as well as the most common commands like play, pause, skip, mute, volume and speaker grouping.  What sets this library apart from similar libraries written for the Arduino platform it its ability to read the state of most of the Sonos functions: getting current source, state, track number, track position, volume and more.  The library is relatively compact and has a small enough memory footprint to function on Arduino Uno and Duemilanove.
