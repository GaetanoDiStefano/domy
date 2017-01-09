Also the GUI is in MQTT system with use of websocket in standard MQTT from 3.1 version.

GUI is based on a simple mechanism of svg widgets each one containing all the animation and transmission system to work alone and inside an html container. html has only the responsability to recognize topics and forward the relative message to the widget. The widget can act a command sending it through send method of html. Each svg widgets has an Update method that can recognize and update the image in order to be consequential to new data.
