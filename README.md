# Traffic Light Controller

This Arduino project simulates a real traffic signal system. It follows the normal light sequence, but when a pedestrian presses a button, the signal turns red to allow safe crossing. After a short delay, it returns to its regular cycle.

## Features

* Simulates real-life traffic signals
* Automatic sequence (Green → Yellow → Red)
* Pedestrian button for crossing
* Instant red signal on button press
* Resumes normal cycle automatically

## Working

* Runs a continuous traffic light cycle
* LEDs change with fixed time delays
* Button press interrupts the cycle
* Signal turns red for pedestrian crossing
* System resumes normal operation after a delay

## Components Required

* Arduino Uno
* Breadboard
* Jumper Wires
* Push Button
* Red, Yellow, and Green LEDs
* 1 × 1kΩ Resistor (button)
* 3 × 220Ω Resistors (LEDs)
