# Firefighting-Robot-with-SMS-Call-Alerts
This firefighting robot is designed to detect and extinguish fires while sending real-time alerts via SMS and calls. It uses an Arduino Uno as the main controller and integrates various sensors and modules for fire detection and response. This system is ideal for areas prone to fire hazards, helping reduce risks and enhance safety.
# Abstract
The firefighting robot is a smart device that can detect and put out fires while also sending alerts through SMS and calls. It uses an Arduino Uno as the main controller and includes a SIM800L GSM module for communication. A flame sensor helps detect fire, and an MQ2 gas sensor checks for smoke or gas leaks. The robot moves using four BO motor wheels, controlled by an L293D motor driver. A relay module and an SG90 servo motor help operate a small 5V water pump to spray water on the fire. The LM2596 buck converter ensures a stable power supply from 18650 batteries. When a fire or gas leak is detected, the robot automatically sprays water and sends an alert message or call to emergency contacts. This system is useful for places prone to fire accidents, helping reduce risks and improving safety.    
# Features
Fire Detection: Uses a flame sensor to detect fire.
Gas & Smoke Detection: The MQ2 gas sensor detects harmful gases and smoke.
Automatic Fire Extinguishing: A 5V water pump is activated to spray water on the fire.
Real-Time Alerts: Sends SMS and calls to emergency contacts using the SIM800L GSM module.
Autonomous Movement: Moves using four BO motor wheels controlled by an L293D motor driver.
Stable Power Supply: The LM2596 buck converter regulates power from 18650 batteries.
# Components Used
Microcontroller: Arduino Uno
Sensors: Flame sensor, MQ2 gas sensor
Communication Module: SIM800L GSM module
Motor Control: L293D motor driver, BO motors
Water Spraying System: SG90 servo motor, relay module, mini 5V water pump
Power Supply: LM2596 buck converter, 18650 batteries
# How It Works
The flame sensor detects a fire, and the MQ2 gas sensor checks for gas leaks.
If a fire or gas is detected, the robot moves toward the source and activates the water pump.
At the same time, the SIM800L module sends an SMS or makes a call to emergency contacts.
The system continuously monitors and responds to fire hazards, ensuring safety.
This project is a great step toward automated fire detection and suppression, making it useful for homes, offices, and industries.
