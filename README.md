#  Simple Traffic Light Simulation with ESP8266

This project simulates a basic traffic light system using an **ESP8266 (NodeMCU)** and three LEDs: **Red**, **Yellow**, and **Green**.  

---

##  Overview
- **Red LED**: ON for 2 seconds
- **Green LED**: ON for 3 seconds
- **Yellow LED**: ON for 2 seconds
- Repeats indefinitely to mimic traffic light behavior.

---

##  Hardware Components
- **Microcontroller**: ESP8266 (NodeMCU)
- **Red LED**: Connected to `D8`
- **Yellow LED**: Connected to `D5`
- **Green LED**: Connected to `D2`
- Resistors (220Ω–330Ω recommended)
- Breadboard and jumper wires

---

##  Pin Configuration
| LED Color | ESP8266 Pin |
|-----------|--------------|
| Red       | D8           |
| Yellow    | D5           |
| Green     | D2           |

---

##  How It Works
The code turns on one LED at a time, representing the traffic light sequence:
1. **Red ON** for 2 seconds.
2. **Green ON** for 3 seconds.
3. **Yellow ON** for 2 seconds.
4. Loops back to Red.

---

##  Usage Instructions
1. **Wiring**:  
   - Connect the Red LED (with resistor) to D8.
   - Connect the Yellow LED (with resistor) to D5.
   - Connect the Green LED (with resistor) to D2.
   - All LED cathodes go to GND.

2. **Upload the Code**:  
   - Open the code in **Arduino IDE** or **PlatformIO**.
   - Select your board: **NodeMCU 1.0 (ESP-12E Module)**.
   - Connect the ESP8266 and upload.

3. **Power On**:  
   - Watch the traffic light simulation on the LEDs.

---

##  Customization
- Modify `delay()` durations for different light timings.
- Use a **button input** to simulate pedestrian crossing.
- Add **buzzer or display** for advanced signaling.

---


##  Future Ideas
- Expand to a **4-way intersection** simulation.
- Use **RGB LED** instead of separate LEDs.
- Integrate with **IoT** for remote control.

---

##  circuit Image
![Traffic Light Simulation](Traffic_Light.png
)

---

