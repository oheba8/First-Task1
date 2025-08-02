Button-Controlled LED System
Project Description
This project demonstrates how to control multiple LEDs using push buttons. When a button is pressed, the corresponding LED lights up for a short period, then turns off automatically.

Components Used
• Microcontroller board (e.g., Arduino UNO)
• 3 push buttons
• 3 LEDs
• 3 resistors (220 ohm recommended)
• Breadboard
• Jumper wires
• USB cable for power and programming

How It Works
Each button is connected to a specific LED. When a button is pressed:
• The corresponding LED turns on for a few seconds.
• After the time passes, the LED turns off automatically.
• If no button is pressed, all LEDs remain off.

Circuit Setup
The circuit includes:
• Push buttons connected to digital input pins on the board.
• LEDs connected to digital output pins.
• Resistors in series with LEDs to limit current.
• Power and ground rails shared through the breadboard.
Make sure to connect the components as shown in the circuit diagram.

Circuit Diagram
Include the following image in your repository to visualize the connections:
markdown
Copy code
![Circuit Diagram](Task1.png)

Notes
• No additional libraries are required for this project.
• The setup is ideal for beginners learning how to use digital input and output.
• You can expand this project by adding more buttons, LEDs, or adding sound/buzzer indicators.
