# Bus-2.O


### Tagline
Real-time distance measurement using an ultrasonic sensor and buzzer notifications.

---

## Introduction

### What is this project?
The **Ultrasonic Sensor Distance Measurement** project is part of an electronic bus prototype engineered using an Arduino microcontroller and integrated sensors. It includes a robust door lock system designed to enhance passenger safety and security. This specific feature uses an HC-SR04 ultrasonic sensor to measure the distance to an object, providing audio feedback through a buzzer for enhanced interaction.

### Why was this project created?
This project was created to safeguard passengers from getting injured while closing the door of the bus. By utilizing ultrasonic sensors to measure the distance to objects, it ensures that the doors do not close when someone or something is in the way, enhancing passenger safety.


---

## Key Features
- **Distance Measurement**: Uses the HC-SR04 ultrasonic sensor to measure the distance to an object in centimeters.
- **Buzzer Alert**: Provides audio feedback using a buzzer when an object is detected within range.
- **Button Control**: Toggles the measurement and feedback system on and off using a push button.
- **LED Indicators**: Uses LEDs to indicate the state of the system.

---


## Getting Started

### Prerequisites
- Arduino Board
- HC-SR04 Ultrasonic Sensor
- Buzzer
- Push Button
- LEDs
- Breadboard and jumper wires for connections

---

## Connections

### 1. HC-SR04 Ultrasonic Sensor to Arduino:
| **HC-SR04 Pin** | **Arduino Pin** |
|-----------------|-----------------|
| VCC             | 5V              |
| GND             | GND             |
| TRIG            | Pin 8           |
| ECHO            | Pin 9           |

### 2. Buzzer to Arduino:
| **Buzzer Pin**  | **Arduino Pin** |
|-----------------|-----------------|
| Positive Pin    | Pin 11          |
| Negative Pin    | GND             |

### 3. Push Button to Arduino:
| **Button Pin**  | **Arduino Pin** |
|-----------------|-----------------|
| Pin 1           | Pin 7           |
| Pin 2           | GND             |

### 4. LEDs to Arduino:
| **LED Pin**     | **Arduino Pin** |
|-----------------|-----------------|
| LED 1           | Pin 2           |
| LED 2           | Pin 3           |
| LED 3           | Pin 4           |
| LED 4           | Pin 5           |
| LED 5           | Pin 6           |
| LED 6           | Pin 10          |

### 5. Breadboard and Jumper Wires:
- Use jumper wires to connect all components to the breadboard and Arduino for proper grounding and power distribution.

---
## Screenshots
- **Circuit Diagram**
  (https://github.com/user-attachments/assets/e83afc86-e7e2-4a70-8a4e-980b67d13e86)

---
## Installation

1. Connect the ultrasonic sensor, buzzer, push button, and LEDs to the Arduino board as described above.
2. Upload the provided code to the Arduino board using the Arduino IDE.

---

## Usage

1. Press the push button to start measuring distance.
2. The ultrasonic sensor will measure the distance to the nearest object and display the result in the Serial Monitor.
3. The buzzer will sound for one second, and the LEDs will flash to indicate the measurement.

---

