# 🏎️ F1 Reaction Time Tester

Ever wondered how fast your reflexes are?  
Inspired by Formula 1 race starts, this project puts your reaction time to the test using the VEGA Aries microcontroller!

---

## 🧠 How It Works

1. Wait patiently until the **RED LED lights up** and you hear a **buzzer**.
2. As soon as the signal appears, **touch the sensor** as fast as you can.
3. The system calculates your reaction time in milliseconds and displays it via the Serial Monitor.
4. Tracks:
   - ✅ Your current reaction time
   - 🏆 Best score so far
   - 📊 Average time
   - 🔁 Total tests completed

---

## 💡 Hardware Connections

| Component     | GPIO Pin | Description            |
|--------------|----------|------------------------|
| Touch Sensor | GPIO 3   | Input for user action  |
| Buzzer       | GPIO 0   | Audio cue              |
| Red LED      | GPIO 0   | "GO" signal            |
| Green LED    | GPIO 2   | Ready/Idle indicator   |

---

## 🎯 Objective

Train your reflexes and try to beat your best time!  
Can you react faster than an F1 driver? (Hint: Their average is ~200ms! 👀)

---

## 🛠️ Made With

- VEGA Aries Microcontroller  
- Arduino IDE  
- A little bit of competitive spirit 🧠💥

---

## 🚀 Future Add-ons

- Display scores on an OLED screen 📺  
- Save high scores to EEPROM 🧠  
- Multiplayer mode with multiple touch inputs ⚔️

---

> Designed as part of the **VEGA Aries Workshop Projects**.


Create folder for F1 Reaction Time Tester
