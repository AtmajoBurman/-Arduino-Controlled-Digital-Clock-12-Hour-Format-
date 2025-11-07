# 🕒 Arduino Controlled Digital Clock (12-Hour Format)

### 📘 Project Overview
This mini-project demonstrates a **real-time digital clock** built using **Arduino UNO** and a **16x2 LCD display**.  
The clock displays **hours, minutes, and seconds** (`hh:mm:ss`) in **12-hour format** with AM/PM indication.  
The entire setup was **simulated in Proteus Professional**, and a **demo video** along with the **Arduino code** and **project files** are included.

---
### 🎥 Demo
Watch the demonstration video included in the repository:  
`Demo_Video.mp4`

---

### 🧠 Features
- Displays time in **12-hour format (hh:mm:ss)**  
- Uses a **16x2 LCD** for clear time visualization  
- Built and tested in **Proteus Professional simulation environment**  
- **Accurate real-time clock logic** implemented in Arduino  
- Easy to modify or expand (e.g., add buttons for time adjustment)

---

### 🧩 Components Used
| Component | Quantity | Description |
|------------|-----------|-------------|
| Arduino UNO | 1 | Microcontroller board (ATmega328P) |
| 16x2 LCD Display | 1 | To display the current time |
| Resistors | As required | For current limiting |
| Jumper Wires | - | For circuit connections |
| Proteus Professional 8| - | Simulation environment |

---

### ⚙️ Working Principle
- The **Arduino UNO** keeps track of time using programmed logic in its internal loop.  
- The **16x2 LCD** displays the current **hour, minute, and second**.  
- Time rolls over automatically at **12:59:59 → 01:00:00**, maintaining the **12-hour cycle**.  
- Optional AM/PM indicator can be displayed beside the time.

---

### 🧾 Circuit Design (Proteus)
The circuit was designed and simulated in **Proteus Professional**:
- The **LCD** is connected in **4-bit mode** to Arduino digital pins.  
- The **contrast pin (V0)** of the LCD is controlled using a **10kΩ potentiometer**.  
- Simulation verifies the time updates every second accurately on the LCD.

---

### 💻 Arduino Code
The Arduino code (provided in the repository) handles:
- Initialization of the LCD in 4-bit mode  
- Time variables (`hour`, `minute`, `second`)  
- Incrementing seconds and managing rollovers  
- Display formatting with leading zeros for single digits  
- Optional AM/PM toggle

> 📂 File: `clock_12hr.ino`

---

### 🧪 Simulation
The project was **simulated successfully in Proteus Professional**.  
You can open the `.pdsprj` file from the repository to view and run the simulation.  
The demo video (`demo.mp4`) demonstrates the real-time operation of the clock.

---

### 🗂️ Repository Contents


---

### 🚀 How to Run
1. Open **Proteus Professional**.
2. Load the provided `.pdsprj` file.
3. Double-click the Arduino UNO component → Load `clock_12hr.hex` or upload code directly from Arduino IDE.
4. Run the simulation.
5. Observe real-time clock updates on the **16x2 LCD** display.

---

### 🧭 Future Enhancements
- Add **Real-Time Clock (RTC) module (DS3231/DS1307)** for real-world accuracy.  
- Add **buttons** for manual time setting.  
- Implement **AM/PM indicator** or **date display**.  

---

### 🧑‍💻 Developed By
**Atmajo Burman**  
📚 *Arduino | Embedded Systems | Proteus Simulation | Mini Projects*


⭐ *If you found this project helpful, don’t forget to star the repository!*

