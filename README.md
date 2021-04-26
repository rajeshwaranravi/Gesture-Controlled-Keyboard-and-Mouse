# Gesture-Controlled-Keyboard-and-Mouse

A gesture controlled keyboard and mouse using Arduino and Ultrasonic sensor

This project uses Arduino UNO, Ultrasonic sensors and Python to move a mouse cursor and operate keys on a keyboard using gesture controls. 
The ultrasonic sensors hooked to the Arduino are used to determine the distance of the hands from the ultrasonic sensors. 
The code loaded in Arduino finds the respective keyword for the distance found and sends it to the Python GUI running in the computer. 
Python code that is running in the background, recognizes the keywords and generates the corresponding virtual keystrokes for Windows. 
The hotkeys then control particular function of the application that is running.

<img src = https://github.com/rajeshwaranravi/Gesture-Controlled-Keyboard-and-Mouse/blob/main/Blockdiagram.jpg>
