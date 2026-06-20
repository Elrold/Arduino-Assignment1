# Arduino Assignment 1 — Smart Countdown

This is my submission for Assignment 1 in the
Programming C++ for Engineers Using Arduino course
at Ghana Communication Technology University (GCTU).

## What this program does
This program counts down from 5 to 1 using a while loop. On each step of the countdown, it:
- Prints the current count (e.g. "Count: 5") to the Serial Monitor.
- Calls a function called flashLED() which blinks the on-board LED that same number of times.
- Waits 1 second before moving to the next count.

Once the countdown reaches 1 and finishes, the program prints "=== Countdown Complete ===" to the Serial Monitor.

## Concepts demonstrated
- Variables (int)
- Functions with parameters (flashLED)
- The while loop
- Digital output (digitalWrite, pinMode)
- The Serial Monitor (Serial.begin, Serial.print, Serial.println)

## How to run it
1. Open the .ino file in the Arduino IDE.
2. Connect an Arduino Uno via USB.
3. Select Tools > Board > Arduino Uno and the correct Port.
4. Click Upload, then open Tools > Serial Monitor (9600 baud).

## Author
Elrold Annoh Plange

