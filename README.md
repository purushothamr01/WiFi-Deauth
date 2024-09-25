Wi-Fi Deauth Detector using NodeMCU

This project is a simple Wi-Fi deauthentication detector implemented on the NodeMCU ESP8266. It monitors the Wi-Fi connection status and indicates connectivity with LED indicators. This can be used as a basic framework for more advanced Wi-Fi monitoring applications.

Author
Created by Purushotham R.

Features
Connects to a specified Wi-Fi network.
Uses LEDs to indicate the connection status:
Built-in LED lights up when disconnected.
External LED lights up when connected.
Basic structure for detecting deauthentication attacks (indirectly by monitoring connectivity).
Hardware Requirements
NodeMCU ESP8266 module
LED (for external connection)
Resistor (220Ω for the external LED)
Jumper wires
Breadboard (optional)
Circuit Diagram
Connect the external LED to GPIO pin 2 (D4) of the NodeMCU with a resistor in series.
