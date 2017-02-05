# SmartTable
Monitor Table Top - Alexa Controlled - Raspberry Pi 

Hardware:  Table (aluminium extrusion frame, glass top), Computer monitor (embeded into table frame),  Raspberry Pi, Alexa device
Language: Python

This project integrates Alexa, using IFTTT, grok, and flask, to controll a "Smart Table".  
User provides a command to Alexa : "Trigger: Smart Table" and a command is sent to IFTTT,  which then sends a HTTP message to the Pi to trigger a command.
