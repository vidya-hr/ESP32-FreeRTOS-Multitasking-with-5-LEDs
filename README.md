# 💡 ESP32 FreeRTOS Multitasking with 5 LEDs

## 📖 Introduction

The **ESP32 FreeRTOS Multitasking with 5 LEDs** project demonstrates the multitasking capabilities of the ESP32 microcontroller using the built-in **FreeRTOS (Real-Time Operating System)**. In this project, five independent FreeRTOS tasks are created, with each task controlling a separate LED at a unique blinking interval. The project showcases concurrent task execution, efficient CPU scheduling, and real-time task management, making it an excellent introduction to embedded multitasking and RTOS concepts.

---

## 🛠️ Components & Technologies Used

### Hardware Components

- ESP32 Development Board
- 5 LEDs (Red, Green, Blue, Yellow, Pink)
- 5 × 220Ω Resistors
- Breadboard
- Jumper Wires
- USB Cable (for programming)

### Software & Technologies

- Arduino IDE
- ESP32 Board Package
- FreeRTOS (Built into ESP32)
- Wokwi Simulator
- C++ (Arduino Programming)

---

## ⚙️ Methodology

1. Configured five GPIO pins on the ESP32 as digital outputs, each connected to an individual LED.
2. Created five independent FreeRTOS tasks using the `xTaskCreate()` function.
3. Assigned each task the responsibility of controlling a specific LED.
4. Used the `vTaskDelay()` function to define different blinking intervals for each LED:
   - 🔴 Red LED – 5000 ms
   - 🟢 Green LED – 4000 ms
   - 🔵 Blue LED – 3000 ms
   - 🟡 Yellow LED – 2000 ms
   -     Pink LED – 1000 ms
5. Leveraged the FreeRTOS scheduler to execute all tasks concurrently without blocking one another.
6. Continuously monitored the independent blinking patterns to demonstrate real-time multitasking and task scheduling.

---

## 🎯 Outcomes

- Successfully implemented multitasking on the ESP32 using FreeRTOS.
- Demonstrated concurrent execution of multiple independent tasks.
- Controlled five LEDs simultaneously with different blinking intervals.
- Gained practical experience with FreeRTOS task creation, scheduling, and timing.
- Improved understanding of real-time operating systems and embedded system programming.
- Built a scalable foundation for developing advanced IoT and embedded applications involving multiple sensors, actuators, and communication protocols.

---
