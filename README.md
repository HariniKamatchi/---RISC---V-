💡 Hands-On Embedded Systems Journey with VEGA Aries (RISC-V)

In a world of Arduinos, Raspberry Pis, and STM32s, getting hands-on with the indigenously built 🇮🇳 VEGA Aries v3.0 RISC-V board felt like a refreshing detour — one filled with bugs, beeps, and “why isn’t it working?!” moments (that eventually turned into “Look, it’s working!!” 🎉).

This repository contains the embedded projects we built during the
🛠️ Hands-On Workshop on VEGA Processors and Ecosystem
📍 VIT Chennai | 📅 Feb 22 – Apr 14, 2025

We explored real-time embedded systems from the ground up — working with GPIOs, sensors, displays, feedback modules, and logic building blocks — all without relying on plug-and-play libraries. Every line of code mattered. Every connection taught us something new.

🔧 Projects We Built
1️⃣ F1 Lights Out Reaction Tester – Reflex Challenge
A reaction-time game inspired by Formula 1 — with touch sensors, LEDs, and buzzer feedback.

🟥 Red light & buzzer signal "Go!"

🟢 Tap the sensor ASAP

⏱️ Serial Monitor tracks reaction time, best score, and average

Tech used: Touch Sensor, Buzzer, Red/Green LEDs, Serial Monitor
Concept: Human Reflex Measurement + Serial Communication

2️⃣ IR Proximity Alert System – Object Detection Logic
A simple yet effective safety system using IR sensors and LEDs for visual and sound-based alerts.

🟩 Green LED when clear

🟥 Red LED + Buzzer when object is nearby

📟 Serial monitor logs proximity status in real time

Tech used: IR Sensor, Buzzer, R/Y/G LEDs
Concept: Obstacle Detection + Feedback System

3️⃣ RFID Access Control System – UID Logic with Visual Feedback
A basic security prototype using RFID UID verification and R-Y-G LEDs.

✅ Match → Green LED (Access Granted)

❌ Mismatch → Yellow LED (Access Denied)

🚫 3 wrong attempts → Red LED (Access Blocked)

Tech used: RFID RC522 Module, R/Y/G LEDs
Concept: Authentication System + Lockout Logic

👥 Team
N. Chandana – 23BEC1219 | GitHub: @NChandana12

Harini Kamatchi Velrajan – 23BEC1136 | GitHub: @HariniKamatchi

🙌 Acknowledgements
Huge thanks to our incredible mentors
Dr. Vydeki Vijayakumar & Dr. Jagannath M
for your patience, knowledge, and belief in learning-by-building.

Big shoutout to VIT Chennai for hosting a workshop that was more than just practical — it was personal. From tangled wires to blinking LEDs, it was an unforgettable deep dive into real embedded systems.


