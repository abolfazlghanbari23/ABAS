ABAS
====

*An Android Bluetooth Audio Streamer*

*For the purposes of this document, an audio stream is referred to simply as a 'stream'*

---

The ABAS project is an attempt at an open source bluetooth streaming daemon.  The basic goals are outlined below:

-The daemon will start at system startup

-The daemon will check if something is currently connected on the bluetooth connection

-The daemon will check if there is an active stream

-If the above two conditions are met, the daemon will ask the user if they would like to stream over bluetooth

---

As general design goals (ie not requirements but should be attempted):

-A default of on for specific/any bluetooth connection(s) can be set

-The daemon will take up a minimal of system resources

-The daemon will be unobtrusive and intuitive to the end user

-The daemon will maintain the audio quality of the stream

-The daemon will be compatible with all android devices
