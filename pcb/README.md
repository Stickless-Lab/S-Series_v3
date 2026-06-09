## Circuit

This project does not use a custom PCB. Instead, the circuit is documented with:

* an image of the full circuit
* a wiring table showing every connection
* a Cirkit Designer link to the complete circuit design

**Cirkit Designer link:** [Cirkit](https://app.cirkitdesigner.com/project/98a8d149-222e-4ded-919d-9952a3b7c41c)

---

## Wiring Table

| From                      | To                             |
| ------------------------- | ------------------------------ |
| **ESC 1 5V power supply** | **ESP32 VIN**                  |
| **ESC 1 ground**          | **ESP32 GND**                  |
| **ESC 2 5V power supply** | **Receiver CH1 +**             |
| **ESC 2 ground**          | **Receiver CH1 - / GND**       |
| **Receiver CH2 +**        | **Servo positive**             |
| **Receiver CH2 - / GND**  | **Servo negative**             |
| **Receiver GND**          | **ESP32 GND**                  |
| **Receiver CH1 signal**   | **ESP32 D32**                  |
| **Receiver CH2 signal**   | **ESP32 D33**                  |
| **ESP32 D21**             | **Servo signal wire**          |
| **ESP32 D18**             | **ESC 1 signal wire**          |
| **ESP32 D19**             | **ESC 2 signal wire**          |
| **Main battery +**        | **ESC 1 positive power cable** |
| **Main battery -**        | **ESC 1 negative power cable** |
| **Main battery +**        | **ESC 2 positive power cable** |
| **Main battery -**        | **ESC 2 negative power cable** |
