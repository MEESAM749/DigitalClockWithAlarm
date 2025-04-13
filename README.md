# Digital Clock with Alarm 🕒🔔

This project was part of our semester coursework for the **Digital Logic Design** course at **NUST College of EME**. We designed and built a **digital clock with an alarm** system using **breadboards**. The design was first prototyped and simulated in **Proteus**, and then implemented using readily available **logic gate ICs**, **timer ICs (555)**, and **counter ICs**. Below are the key components and details of the project.

---

## 🔧 Components Required

- **1x 555 Timer IC**  
- **21x 4026 Counter ICs**  
- **12x 7485 Comparator ICs**  
- **13x Push Buttons**  
- **1x Simple ON/OFF Switch**  
- **21x 7-Segment LEDs (Common Cathode)**  
- **15x 2-Input AND Gates**  
- **4x 5-Input AND Gates**  
- **3x Capacitors**  
- **2x Diodes**  
- **1x Buzzer** (for alarm; replaced by an LED in Proteus schematic)  
- **173x 470Ω Resistors**  
- **1x NOR Gate**  
- **5x NOT Gates**  
- **3x NPN Transistors**  
- **2x 5-Input OR Gates**  
- **1x 1k TrimPot**  
- **1x 9V Voltage Source**

---

## 🎯 What We Implemented

We implemented the following main features:
- **Basic Clock**: Displays current time using 7-segment LEDs.
- **Alarm Module**: Set an alarm time, and trigger an alarm when the time matches.
- **Time Zone**: Built-in functionality to handle time zone adjustments.

Below is a screenshot of the clock and alarm setup:

![Digital Clock and Alarm](https://github.com/user-attachments/assets/bb6ae577-14e5-4afa-8baf-dd4713234229)

---

## 🔨 How to Build It

This is a complex project that involves multiple modules, so I recommend breaking it down into manageable sections. Each module is designed to be independent, which means you can build and test each part separately before integrating everything together. 

For your convenience, the schematic below shows each module separately. This should help in building specific sections you might be interested in.

If you prefer a cleaner view of the circuit than the clutter in Proteus, I've included an SVG file as well.

![Modules Breakdown](https://github.com/user-attachments/assets/ac47cd9d-d098-4e0f-90a1-cf859984fe19)

---

## 📜 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

---

## 🙏 Acknowledgements

- **NUST College of EME** for offering the **Digital Logic Design** course.
- **Dawood Ali Khan** and **Syed Faqih Ali Zamin**, my group members, for their collaboration on this project.

---

Feel free to explore the schematic, test individual modules, and adapt the project to your needs. Happy building! 😎
