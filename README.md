Temperature Meter with Heater and Air Conditioner
Overview

This project is an embedded real-time temperature control system built with an ATmega32 microcontroller. It monitors ambient temperature using an LM35 sensor and automatically activates a cooling fan or a warming fan to maintain stable conditions. The current temperature is displayed on an LCD, with LEDs indicating system status.

Features

Real-time temperature monitoring via LCD

Automatic cooling and heating control

LED indicators for fan/heater status

Cost-effective and energy-efficient design

Tested in simulation (Proteus) and implemented in hardware

Hardware Components

ATmega32 Microcontroller – Core processing unit

LM35 Temperature Sensor – Reads ambient temperature

LCD Display – Shows real-time temperature

Cooling Fan & Warming Fan – Controlled by the microcontroller

Transistors, Capacitors, Resistors – For stable circuit operation

LEDs – Indicate cooling/heating status

Circuit Workflow

The LM35 sensor measures ambient temperature.

The ATmega32 converts the sensor’s analog signal via its ADC.

Based on thresholds, the microcontroller activates the cooling fan or warming fan.

The LCD displays the current temperature.

LEDs show which system (cooling/heating) is active.
