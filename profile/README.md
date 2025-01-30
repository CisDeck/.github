# CisDeck
## Streamdeck with custom Software and Hardware

### Hardware
The Hardware consists out of 2 main Components:
- A 4x4 Matrix Membrane Keypad
- An Arduino Nano

The packaging is made out of cardboard and tape due to missing materials.

Images:

<img src="https://github.com/user-attachments/assets/9bfa8628-f640-4805-8b57-b1044274ed63" width="400" height="500">
<img src="https://github.com/user-attachments/assets/56e1524d-17e3-4fe5-9542-ea4ddf31f7c5" width="400" height="500">


### Software
There are 2 software for this project.
1. Software on the Arduino

*The Software on the Arduino consists of a 4x4 matrix Keypad Reader code.
The key that got clicked gets printed into a defined serial output/console.*

2. Software on a Device/Computer

*This is a C# Software consisting of a GUI for User-Interaction and a back-end Script that checks the serial output for pressed keys.
If a key is pressed, the code will execute the configured action in the GUI.
Every configured Option is saved in a file in the main directory.*
