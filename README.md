#  Temperature Meter with Heater and Air Conditioner  

An **embedded real-time temperature control system** using an **ATmega32 microcontroller** and an **LM35 temperature sensor**.  
The system monitors ambient temperature and **automatically activates** a cooling fan or a warming fan.  
A real-time reading is displayed on an **LCD**, with **LED indicators** showing the current state.  

---

## ✨ Features  
- ✅ Real-time temperature monitoring on LCD  
- ✅ Automatic cooling/heating control  
- ✅ LED indicators for fan/heater status  
- ✅ Low-cost and energy-efficient design  
- ✅ Tested in **Proteus simulation** and hardware implementation  

---

## 🛠️ Hardware Components  
- **ATmega32 Microcontroller** – System controller  
- **LM35 Temperature Sensor** – Temperature measurement  
- **LCD Display (16x2)** – Real-time data display  
- **Cooling Fan & Warming Fan** – Environmental control  
- **BC547 Transistors** – Fan switching  
- **Capacitors & Resistors** – Circuit stability  
- **LEDs (Green & Red)** – Status indicators  

---

## ⚙️ How It Works  
1. 🌡️ The **LM35 sensor** measures ambient temperature.  
2. 🔄 The **ATmega32 ADC** converts analog data into digital values.  
3. 🌀 If the temperature is above the threshold → **Cooling Fan ON**.  
4. 🔥 If the temperature is below the threshold → **Warming Fan ON**.  
5. 📟 LCD displays real-time readings.  
6. 💡 LEDs indicate whether heating or cooling is active.  

---

