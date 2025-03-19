# RdkLedManager
The RDK LED Manager is an application responsible for controlling the LEDs on RDK-B Hubs. It performs three main functions: catching system-wide events using RBUS/Sysevents/etc. and translating them to known event identifiers/keys, checking if a received event causes the LED to change state, and setting the new LED state (e.g., color, pattern)
