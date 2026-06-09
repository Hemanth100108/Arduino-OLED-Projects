# Arduino OLED Workshop Projects


## Objective
This repository contains a collection of Arduino projects developed using an SSD1306 OLED Display, Push Buttons, and a Buzzer.
To develop and implement a collection of Arduino-based OLED projects that demonstrate display interfacing, user interaction, timing applications, menu navigation, security systems, and real-time information display.


## Projects Included

1. Button Press Counter With Buzzer
2. Visitor Counter With Buzzer
3. OLED Menu System
4. OLED Stopwatch Using millis()
5. Reaction Time Game 2.0
6. OLED Password Lock
7. OLED Smart Dashboard


## Components Used

### Hardware

* Arduino Uno
* SSD1306 OLED Display (128×64)
* Push Buttons
* Active Buzzer
* Breadboard
* Jumper Wires
* USB Cable

### Software

* Arduino IDE
* Wire Library
* Adafruit GFX Library
* Adafruit SSD1306 Library


## Circuit Diagram

### OLED Connections

| OLED Pin | Arduino Uno |
| -------- | ----------- |
| VCC      | 5V          |
| GND      | GND         |
| SDA      | A4          |
| SCL      | A5          |

### Push Button Connections

| Component | Arduino Pin |
| --------- | ----------- |
| Button 1  | D2          |
| Button 2  | D3          |

### Buzzer Connection

| Buzzer Pin   | Arduino Pin |
| ------------ | ----------- |
| Positive (+) | D8          |
| Negative (-) | GND         |

### Circuit Images


## Code Explanation

### Project 1 – Button Press Counter With Buzzer

* Counts the number of button presses.
* Displays the count on the OLED.
* Generates buzzer feedback for every press.

### Project 2 – Visitor Counter With Buzzer

* Simulates entry and exit counting.
* Updates visitor count in real time.
* Provides buzzer indication for user actions.

### Project 3 – OLED Menu System

* Implements a menu-driven interface.
* Navigation performed using push buttons.
* Demonstrates cursor movement and screen management.

### Project 4 – OLED Stopwatch Using millis()

* Implements a digital stopwatch.
* Supports Start, Stop, Resume, and Reset functions.
* Uses millis() for accurate timing.

### Project 5 – Reaction Time Game 2.0

* Measures user reaction speed.
* Displays reaction time in milliseconds.
* Categorizes results as Excellent, Good, or Needs Practice.

### Project 6 – OLED Password Lock

* Implements password authentication using button sequences.
* Displays Access Granted or Access Denied.
* Uses buzzer feedback for authentication status.

### Project 7 – OLED Smart Dashboard

* Displays a real-time dashboard.
* Includes counter, status indicator, and elapsed time.
* Combines OLED display, buzzer, button input, and millis() timer.


## Output Images

### Button Press Counter With Buzzer

<img width="1600" height="1200" alt="WhatsApp Image 2026-06-09 at 9 13 42 PM" src="https://github.com/user-attachments/assets/6c28e232-d646-4e6d-adb1-58b056226ee5" />
<img width="1600" height="1200" alt="WhatsApp Image 2026-06-09 at 9 13 42 PM (1)" src="https://github.com/user-attachments/assets/53c72dbb-3fd4-4ba6-ab1a-e047a6c35beb" />


### Visitor Counter With Buzzer

<img width="1600" height="1200" alt="WhatsApp Image 2026-06-09 at 9 13 41 PM" src="https://github.com/user-attachments/assets/222b01fd-8403-44d9-ab25-1f643b3484d4" />
<img width="1600" height="1200" alt="WhatsApp Image 2026-06-09 at 9 13 42 PM" src="https://github.com/user-attachments/assets/2144e95b-0290-4163-9d1c-649c791e85d1" />


### OLED Menu System

<img width="1600" height="1200" alt="WhatsApp Image 2026-06-09 at 9 13 40 PM" src="https://github.com/user-attachments/assets/6d493ed2-2320-4907-87c5-52fb647535a4" />
<img width="1600" height="1200" alt="WhatsApp Image 2026-06-09 at 9 13 40 PM" src="https://github.com/user-attachments/assets/9d27795a-9347-492b-87af-f5158d80cf79" />


### OLED Stopwatch Using millis()

<img width="1600" height="1200" alt="WhatsApp Image 2026-06-09 at 9 13 39 PM (1)" src="https://github.com/user-attachments/assets/3a0e618f-24f3-4a15-a4bc-6417c68383be" />
<img width="1600" height="1200" alt="WhatsApp Image 2026-06-09 at 9 13 39 PM" src="https://github.com/user-attachments/assets/f8f92a49-8a13-4b74-a7df-142b321f6804" />


### Reaction Time Game 2.0

<img width="1600" height="1200" alt="WhatsApp Image 2026-06-09 at 9 13 38 PM (1)" src="https://github.com/user-attachments/assets/2816a7e2-2f74-4aca-b74b-1d095ee93f11" />
<img width="1600" height="1200" alt="WhatsApp Image 2026-06-09 at 9 13 38 PM" src="https://github.com/user-attachments/assets/e19e68c2-d953-4cce-a35f-9fe8a537fa1a" />


### OLED Password Lock

<img width="1600" height="1200" alt="WhatsApp Image 2026-06-09 at 9 13 36 PM" src="https://github.com/user-attachments/assets/90fbc730-d16f-4cf0-81b8-ec608766870f" />
<img width="1600" height="1200" alt="WhatsApp Image 2026-06-09 at 9 13 37 PM (1)" src="https://github.com/user-attachments/assets/c276e4b6-a728-4a21-80a4-2c613fd17785" />
<img width="1600" height="1200" alt="WhatsApp Image 2026-06-09 at 9 13 37 PM" src="https://github.com/user-attachments/assets/09f013a0-5064-4359-8d8b-bfa791c384ac" />


### OLED Smart Dashboard

<img width="1600" height="1200" alt="WhatsApp Image 2026-06-09 at 9 13 36 PM (1)" src="https://github.com/user-attachments/assets/2fecdef3-6385-4d59-8425-d292a27dd314" />
<img width="1600" height="1200" alt="WhatsApp Image 2026-06-09 at 9 13 36 PM" src="https://github.com/user-attachments/assets/06bbb985-af81-4981-8eb0-77ca15dc000b" />


## Learning Outcome

Through these projects, the following concepts were learned:

* Arduino Programming Fundamentals
* OLED Display Interfacing
* I2C Communication Protocol
* Push Button Input Handling
* Buzzer Control and Feedback
* Counter Design and Implementation
* Menu Navigation Systems
* Stopwatch Development using millis()
* Event Timing and Measurement
* Reaction Time Analysis
* Password Authentication Logic
* Dashboard Development
* Embedded Systems Programming
* Problem Solving and Hardware Integration


Hemanth A S
