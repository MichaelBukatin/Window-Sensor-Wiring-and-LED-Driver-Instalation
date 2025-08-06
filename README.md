# Window-Sensor-Wiring-and-LED-Driver-Instalation

This project documents my practical work on installing a basic automation system to control an air conditioner using magnetic window sensors, as well as installing a 24V LED driver.

## 🪟 Window Sensors for AC Control

The purpose of this system is to automatically **disable the air conditioner when any window is open**. This is achieved using magnetic contact sensors wired in **series**.

### 🔧 What I Did:

[Start work striped](
- Connected multiple sensor wires **in series** 
- Stripped and joined wires using **electrician’s scissors**
- Used **heat-shrink tubing** for safe and clean insulation
- Verified continuity — the circuit breaks if any window is open

### 🧠 How It Works:
- Each window has a **magnetic sensor** (reed switch)
- All sensors are wired **in series**
- When any window opens, the circuit is **interrupted**
- This change is detected by the control system, which **turns off the air conditioner**

### 🧵 Cable Info:
- Used 3x2 cables (3 separate cables, each with 2 conductors: red and black)
- Internal structure: red insulation → foil shielding → 2x 1.5mm wires → flame-retardant fabric layer → copper core

---

## 💡 LED Driver Installation

In this part of the project, I installed a basic **24V LED driver**. The process is simple but must be done carefully when working with **230V AC**.

### 🔧 What I Did:
- Connected **2 wires to 230V AC input**
- Connected **2 wires to 24V DC output**
- Placed the driver into a **flush-mounted wall box**
- Covered it with a **standard wall plate**

⚠️ **Note:** Always isolate power before working with AC connections. Work must follow local electrical regulations.

---

## 📸 Photos

You can add photos like this after uploading them to your GitHub repo:

```markdown
![Window Sensor Wiring](./photos/window-sensor.jpg)
![Heat-Shrink Example](./photos/heatshrink.jpg)
![LED Driver in Wall Box](./photos/led-driver.jpg)
