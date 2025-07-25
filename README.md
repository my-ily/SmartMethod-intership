# Four DC Motors Control with L293D and Arduino Uno

## Project Overview

This project focuses on the implementation of a system to control four DC motors using an L293D motor driver and an Arduino Uno. The project demonstrates how to program and control motor movements in different directions and durations, showcasing practical applications of embedded systems and motor control.

## Objectives

1. Move the motors forward for a duration of 30 seconds.
2. Move the motors backward for a duration of 1 minute.
3. Alternate motor directions between right and left for a duration of 1 minute, with a half-second interval for each direction.

## Components and Tools

### Hardware:
- Arduino Uno (microcontroller board)
- L293D Motor Driver (for motor control)
- Four DC Motors
- Breadboard
- 9V Battery (for power supply)
- Jumper Wires (for circuit connections)

### Software:
- Arduino IDE (for programming and uploading code)
- Tinkercad (for simulation and circuit design, optional)

## Circuit Description

The circuit connects the L293D motor driver to the Arduino Uno to control the direction and speed of the motors. Power is supplied to the motors via a 9V battery. Each motor is connected to the motor driver’s output pins, while the input pins are controlled by the Arduino’s digital pins. The direction of the motors is managed by setting the input pins to HIGH or LOW.

### Pin Configuration:

| Motor    | Input Pin 1 | Input Pin 2 |
|----------|-------------|-------------|
| Motor A  | Pin 2       | Pin 3       |
| Motor B  | Pin 4       | Pin 5       |

## Code Explanation

The program written in C++ controls the motors by sending signals to the L293D driver through the Arduino. The main logic includes:

1. **Forward Movement**: Setting specific input pins to HIGH or LOW to drive the motors forward for 30 seconds.
2. **Backward Movement**: Reversing the input pin states to drive the motors backward for 1 minute.
3. **Alternating Directions**: Alternating the motor directions between right and left every 0.5 seconds for a total of 1 minute using a `for` loop.

The code includes `delay()` functions to control the duration of each movement.

## How to Run the Project

### 1. Assemble the Circuit:
- Connect the L293D motor driver to the Arduino and DC motors as per the pin configuration above.
- Use a breadboard for proper wiring and connections.
- Attach the 9V battery to supply power to the motors.

### 2. Upload the Code:
- Open the Arduino IDE.
- Copy the provided code into a new sketch.
- Connect the Arduino Uno to your computer via USB and upload the code.

### 3. Test the System:
- Observe the motors performing the specified movements in the order described.

## Applications

This project demonstrates the basic principles of motor control, which can be extended to various applications, such as:

- Robotics
- Conveyor belt systems
- Automated vehicles

## Future Enhancements

- Integrating sensors (e.g., ultrasonic sensors) for obstacle detection.
- Adding PWM (Pulse Width Modulation) for speed control.
- Using wireless modules (e.g., Bluetooth or Wi-Fi) for remote control.

## Project Link

To view the project files and code, click here.

https://www.tinkercad.com/things/eK2gh5HeOBb-task2-dc-motor


