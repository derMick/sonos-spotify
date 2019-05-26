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



# old description ... 


this fork should be the port for esp8266
# sonos
This library makes interfacing an Arduino with your Sonos system a breeze. The library supports both controlling and reading the state of your Sonos components.  Playing URIs, files, online radio stations, playlists, and line-in is supported as well as the most common commands like play, pause, skip, mute, volume and speaker grouping.  What sets this library apart from similar libraries written for the Arduino platform it its ability to read the state of most of the Sonos functions: getting current source, state, track number, track position, volume and more.  The library is relatively compact and has a small enough memory footprint to function on Arduino Uno and Duemilanove.
