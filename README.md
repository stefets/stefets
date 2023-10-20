## My repositories defined here are intended to be used for performances of all kinds using the awesome [mididings API](https://github.com/mididings/mididings) as *kernel*.

⚡ [live-config](https://github.com/stefets/live-config) is my *mididings script builder API*, made for my needs but adaptable.

⚡ [flaskdings](https://github.com/stefets/flaskdings) is a Flask API. I wrote it to communicate with my [live-config](https://github.com/stefets/live-config) app. It exposes the following features:
* An OSC service, using LiveOSC
* RESTful endpoints doing direct calls to LiveOSC methods
* A modern HTML5+Bootstrap UI with Flask-SocketIO (A serious alternative to the built-in livedings UI)

⚡ [osc-soundcraft-bridge](https://github.com/stefets/osc-soundcraft-bridge) 
* It is a bridge between the OSC protocol and the SoundCraft UI series. 
* A daemon that translate an OSC message to a socket message understood by the Soundcraft server.
* *It does not depend on mididings*. 
