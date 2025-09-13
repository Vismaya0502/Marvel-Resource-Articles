# L293D Datasheet Summary

## What is L293D?

The L293D is a 16-pin motor driver IC that allows microcontrollers to control the direction and speed of two DC motors. It contains two H-bridge circuits, enabling bidirectional control of motors using low-power control signals.


## Role in Motor Control

Microcontrollers cannot directly drive motors because they operate at low voltage and current levels, which are not sufficient for motors. The L293DE acts as a voltage amplifier, taking the microcontroller’s low-power signals and boosting them to drive high-power components like DC motors.


## Why Understanding the Datasheet Useful?

Reading the datasheet helps us understand how to use the component properly, what it can and can't do, and how to connect it safely in a circuit. The manufacturers add all the necessary know data that is required to design using that component.

---

## Pin Specifications



| **Pins**     | **Pin Numbers**        | **Function**                                                                 |
|-------------|--------------------|---------------------------------------------------------------|
| Enable Pins      | 1, 9                   | Activates H-bridge 1 and 2                                                   |
| Input Pins       | 2, 7, 10, 15           | Control signals from the microcontroller to decide motor direction          |
| Output Pins      | 3, 6, 11, 14           | Connected to the motor terminals                                            |
| Ground Pins      | 4, 5, 12, 13           | Connected to ground (GND)                                                   |
| Motor Supply (VS)| 8                      | Provides power to motors (up to 36V)                                        |
| Logic Supply (VSS)| 16                    | Provides logic power (usually 5V)                                           |

---



## H-Bridge Working Principle

The L293D uses an H-bridge configuration to control the direction of current flow through the motor. By changing the logic levels at the input pins, the motor can be made to rotate forward, backward, or stop.

![H-Bridge Working GIF](https://lastminuteengineers.com/wp-content/uploads/arduino/H-Bridge-Working-Motor-Direction-Control-Animation.gif)


- **One input HIGH and the other LOW** - Motor rotates in one direction.
- **Inputs reversed** - Motor rotates in the opposite direction.
- **Both inputs HIGH or LOW** - Motor stops.

The enable pin must be HIGH for the H-bridge to function.

---

## PWM and Speed Control

Pulse Width Modulation (PWM) is used to control motor speed by rapidly turning the power on and off. The average voltage changes with the duty cycle:

**Duty Cycle**:  (Time the signal is ON / Total cycle time) × 100%
![PWM duty cycle diagram](https://lastminuteengineers.com/wp-content/uploads/arduino/Pulse-Width-Modulation-PWM-Technique-with-Duty-Cycles.png)


- A **higher duty cycle** results in **faster motor speed**.
- A **lower duty cycle** slows the motor down.

In the L293DE, PWM is usually applied to the **Enable pins (1 and 9)** to control the motor’s speed while the input pins control the direction.

---

## Key Electrical Characteristics

| **Parameter**               | **Typical Value** | **Unit** | **Description**                                      |
|----------------------------|-------------------|----------|------------------------------------------------------|
| Logic Supply Voltage       | 4.5 – 5.5         | V        | VSS – powers the internal logic                      |
| Motor Supply Voltage       | Up to 36          | V        | VS – powers the motor outputs                        |
| Output Current (per channel)| 600              | mA       | Continuous current per motor channel                 |
| Peak Output Current        | 1.2               | A        | Maximum short-pulse current                          |

---


---