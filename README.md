# Eye Closure Detection Alarm System

## Project Description
This project uses computer vision to detect whether the user's eyes are open or closed.
When the eyes remain closed for a certain duration, an Arduino activates a buzzer to
produce a sound alarm to wake the user.

## Objective
- Detect eye closure using a webcam
- Alert the user using a buzzer
- Improve safety and attention monitoring

## Components Used
### Hardware
- Arduino Uno
- Buzzer
- USB cable
- Jumper wires

### Software
- Python
- OpenCV
- MediaPipe Face Mesh
- Arduino IDE

## System Workflow
1. Webcam captures live video
2. Python detects eye status (open/closed)
3. Signal is sent to Arduino via serial communication
4. Buzzer turns ON when eyes are closed

## Applications
- Driver drowsiness detection
- Safety alert systems
- Focus monitoring

