# 🔦 IR Proximity Alert System

A compact safety and automation project using the VEGA Aries board and an IR sensor.  
This system detects nearby objects and instantly alerts you using a buzzer and LED indicators.

---

## 🧩 Components Used

- VEGA Aries Development Board v3  
- IR Sensor (HW-201)  
- RYG LED Strip  
- Piezo Buzzer  
- USB Cable  

---

## 🔌 Pin Connections

| Component      | VEGA Aries Connection          |
|----------------|-------------------------------|
| **IR Sensor**  | VCC → 3.3V                     |
|                | GND → GND                      |
|                | OUT → GPIO1 (Analog Input)     |
| **Buzzer**     | VCC → 3.3V                     |
|                | I/P → GPIO0                    |
|                | GND → GND                      |
| **LED Strip**  | GND → GND                      |
|                | Red → PWM0 (GPIO0)             |
|                | Yellow → PWM1 (**unused**)     |
|                | Green → PWM2 (GPIO2)           |

> 🧠 Note: GPIO0 is shared between the **Red LED** and **Buzzer**. Control them in sequence to avoid conflict.

---

## ⚙️ How It Works

1. The IR sensor monitors for objects within a short range.
2. If an object is detected:
   - 🔊 **Buzzer beeps**
   - 🔴 **Red LED turns ON**
3. If no object is nearby:
   - 🟢 **Green LED remains ON**
   - System stays in standby mode

All activity is logged on the **Serial Monitor** for real-time feedback.

---

## ✅ Applications

- Smart home alert systems 🚪  
- Proximity-based robot sensors 🤖  
- Social distancing alerts 🧍↔️🧍  
- Entry detection for doors or drawers 🚪

---

## 💡 Possible Enhancements

- Add an OLED display to show detection status  
- Control alert duration via potentiometer  
- Send alerts to phone via Wi-Fi/Bluetooth

---

> Built with ❤️ as part of the **VEGA Aries Workshop Projects**
