# IoT26-HW01
Gachon Univ. IoT Team F HW01

## Project Overview
This project demonstrates how to control Raspberry Pi GPIO digital outputs using Python.  
An LED is connected to the Raspberry Pi and controlled using the gpiozero library.

---

## Objective
- Learn how to use Raspberry Pi GPIO pins
- Control digital output (LED)
- Use Python (gpiozero) to interact with hardware

---

## Hardware Setup
- Raspberry Pi
- Breadboard
- LED
- Resistor
- Jumper wires

---

## Circuit
- LED connected to GPIO pin
- Resistor used to prevent overcurrent

<img src="https://github.com/user-attachments/assets/9d85c9a3-c5e6-45a6-9333-c25adbd57c1f" width="400">

## IDE / Terminal
<img src="https://github.com/user-attachments/assets/7becac96-7ffe-4000-90e0-13ca28a0b4d2" width="400" />

---
## 🎥 Video
[https://youtube.com/shorts/VEWtVfIeT-U?feature=share](https://www.youtube.com/shorts/WOD6z7DadZU?feature=share)

---

## Code
```python
from gpiozero import LED
from time import sleep

led = LED(17)

while True:
    led.on()
    sleep(1)
    led.off()
    sleep(1)
```

---
## Team Roles
- **Raspberry Pi Setup**: 김채윤, 김현보  
  (Raspberry Pi connection and development environment setup)

- **Development**: 김건
  (Code execution and refactoring, version synchronization)

- **Documentation**: 김현보
  (Video recording and GitHub repository organization)
