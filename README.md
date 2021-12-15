# Sprinkler Controller
Sprinkler Controller Firmware For ESP8266

When booting for the first time the controller can be
setup using an Access Point with a designated SSID.

Contoller recieves commands via MQTT over the topics defined in setup.


# Sprinkler Server
Server Built With The Python Flask Module And Jinja2

Serves a control panel UI over port 8080.
Reads from configuration file.
Can edit configuration via ui at server_ip:8080/configc .
Uses a background task scheduler module to turn on valves at specific time.
