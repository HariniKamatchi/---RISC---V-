# 🔐 RFID Access System – Scan. Verify. Access.

Welcome to your first line of digital defense!  
This system simulates a secure access gate using an **RFID reader** and a **Red-Yellow-Green (RYG) LED strip**.  
Built on the **VEGA Aries Development Board v3**, it brings real-world access control logic to life — color-coded, of course.

---

## 🧩 What’s Inside?

- **RC522 RFID Module** – the scanner  
- **RYG LED Strip** – the indicator  
- **Buzzer (optional)** – for sound feedback  
- **VEGA Aries V3 Board** – the brain  
- **RFID Cards** – your identity keys  

---

## 🧠 How It Works

1. 🧾 **Scan your card** on the RFID reader.
2. The card’s UID is checked against a **pre-set authorized list**.
3. Based on the result:

   | LED  | Color   | Status              | Meaning                        |
   |------|---------|---------------------|--------------------------------|
   | 🟢   | Green   | ✅ Access Granted    | You're authorized, go ahead!   |
   | 🟡   | Yellow  | ⚠️ Access Denied     | Wrong card — try again.        |
   | 🔴   | Red     | 🚫 Access Blocked    | 3 wrong tries = you're locked. |

4. The **Serial Monitor** prints the status, UID, and count of failed attempts.

---

## 🛠️ Pin Connections (VEGA Aries v3)

### 🔌 RFID RC522 Module

| Pin   | Board GPIO |
|-------|-------------|
| SDA   | GPIO10      |
| SCK   | SCL0        |
| MOSI  | MOSI0       |
| MISO  | MISO0       |
| RST   | GPIO9       |
| VCC   | 3.3V        |
| GND   | GND         |

### 💡 LED Strip (RYG)

| LED Color | GPIO Pin | Function          |
|-----------|-----------|-------------------|
| Red       | GPIO0     | Access Blocked    |
| Yellow    | GPIO1     | Access Denied     |
| Green     | GPIO2     | Access Granted    |

---

## 🎯 What You Can Build With This

- 🔒 Smart door locks
- 🏫 Classroom attendance systems
- 🚪 RFID-controlled drawer/locker
- 👨‍🔬 Lab entry authentication
- 🎮 Game unlock mechanisms

---

## 🌱 Features You Can Add Next

- Store and manage multiple UIDs using EEPROM  
- Attach an OLED display to show names/status  
- Hook up a servo motor to simulate gate opening  
- Connect to Wi-Fi for real-time logging  

---

## ✨ Project Highlights

✅ Real-time feedback  
✅ Secure logic with UID validation  
✅ Visual indicator using color LEDs  
✅ Teaches embedded systems, RFID tech, and GPIO control

---

> 🚀 Created with ❤️ as part of the **VEGA Aries Workshop Projects** — where learning meets hands-on fun!
