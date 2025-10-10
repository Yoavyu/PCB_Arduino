# 28Pins Project – Custom Arduino Board with ESP32 Wireless Upgrade

This project is a **custom Arduino Uno–based PCB designed in Altium Designer**, enhanced with an **integrated ESP32-WROOM module**.  
The ESP32 communicates **directly with the Arduino via UART**, allowing the Arduino to **operate independently while leveraging the ESP32 for wireless connectivity**.  
This enables the board to send and receive data over **Wi-Fi and Bluetooth** without requiring additional modules, making it a **fully functional, wireless-capable development platform**.


> **Note:** The base Arduino Uno board was recreated **following the Udemy course by Robert Feranec**, which guided me step-by-step through schematic capture, PCB layout, and generating manufacturing files.  
> The **ESP32 wireless upgrade was designed and integrated independently**, without course guidance, showcasing additional hardware design and integration skills.
> 
> **Tip:** To get a better view of the schematics and PCB layout, it is recommended to **download the PDF files and open them using Adobe Acrobat**.

---

## Project Highlights

I started from the **Arduino Uno reference schematic** and went through the full PCB design workflow:

**1. Schematic Design & Component Creation**  
- Created **all schematic symbols and footprints from scratch**  
- Re-drew and improved the Arduino Uno schematic as guided by the course  
- **Integrated ESP32-WROOM independently** to enable wireless communication  

<img width="925" height="756" alt="image" src="https://github.com/user-attachments/assets/b20a44b0-1c9e-405f-ac55-9e4d60d0c610" />


**2. PCB Layout**  
- Placed all components on the PCB and routed connections professionally  
- Optimized layout for signal integrity, manufacturability, and proper ESP32 antenna routing  

<img width="1382" height="808" alt="image" src="https://github.com/user-attachments/assets/e7a920f3-dd5c-4854-9d84-1b9a82f790f1" />
  

**3. 3D Visualization**  
- Created a 3D model of the board to verify component placement and clearances  
- Checked mechanical fit and overall design before manufacturing  

<img width="1259" height="745" alt="image" src="https://github.com/user-attachments/assets/73e7869a-5b16-4949-819f-d2faa893330d" />
 

**4. Features & Enhancements**  
- Full Arduino Uno functionality recreated  
- **ESP32-WROOM integrated for wireless capabilities independently**  
- All schematic symbols and footprints created from scratch  
- Manufacturing-ready outputs: Gerbers, BOM, Drill files  
- Board variants with optional components  
- Assembly documentation included

**5. PCB Fabrication** 
After completing the schematic and PCB layout design, I took the project one step further by **sending the board for fabrication through JLCPCB**.  
This stage marked the transition from **digital design** to a **real, manufacturable prototype**.

During this process I:
- Exported **Gerber**, **BOM**, and **Pick & Place** data for assembly  
- Learned about DFM concepts such as hole sizing, tolerances, and copper clearances  
- Gained valuable experience bridging **theory and hardware reality**, even knowing the first revision might require debugging  

> This fabrication phase completed the learning cycle — from concept to a tangible PCB — providing real-world insight into professional hardware design.

<img width="1435" height="369" alt="image" src="https://github.com/user-attachments/assets/9c16e787-fa08-450a-aa9e-a994b95cc16d" />

---

## Repository Contents

- `28Pins_Schematic.SchDoc` – Main schematic  
- `28Pins_Project_V1I1.PcbDoc` – PCB layout  
- `28Pins_Project_V1I1.PcbLib` – PCB library  
- `28Pins_Project_V1I1.SchLib` – Schematic library  
- `28Pins_Project_V1I1.OutJob` – Output job for Gerbers/BOM  
- `28Pins_Project_V1I1_PCB.pdf` – Schematic PDF  
- `28Pins_Project_V1I1-1.pdf` – 3D PCB View (Available only in Adobe Acrobat) 

---

## How to Explore

1. Open `.PrjPcb` in **Altium Designer**  
2. Inspect schematic and PCB layout  
3. Check 3D model and board variants  
4. Generate manufacturing files with `.OutJob`  

---

## What I Learned

Throughout this project, I gained comprehensive, hands-on experience in **end-to-end PCB design**, from schematic creation to PCB layout and manufacturing documentation.  

While the Udemy course by *Robert Feranec* provided a strong foundation for recreating the Arduino Uno design in **Altium Designer**, I didn’t stop there — I challenged myself to **go beyond the tutorial** and implement a real hardware enhancement that adds meaningful functionality.

### Key Takeaways:
- **Schematic Design:**  
  Learned to create professional and structured schematics entirely from scratch, including hierarchical design, labeling, and electrical rule checking.  
  Designed clear and maintainable circuit diagrams that follow industry standards.

- **Layout Design:**  
  Practiced professional PCB layout techniques, including component placement, routing optimization, and design-for-manufacturing (DFM) considerations.  
  Applied **design rules**, **trace width calculations**, and **ground plane optimization** to ensure signal reliability and board robustness.

- **Component Creation:**  
  Built **custom schematic symbols** and **footprints** for every component, ensuring full control over accuracy and alignment between schematic and layout.  
  Created libraries that can be reused across future projects.

- **Integration & System Thinking:**  
  Designed and implemented a reliable hardware interface between **ATmega328P** and **ESP32-WROOM**, enabling **wireless communication (Wi-Fi + Bluetooth)** directly on the board.  
  Considered voltage compatibility, serial communication routing, and power domain separation between 5V (Arduino) and 3.3V (ESP32) systems.

- **Documentation & Manufacturing:**  
  Generated complete, production-ready documentation — **Gerbers, Pick & Place files, BOM, drill files**, and **assembly drawings** — suitable for PCB fabrication and assembly at JLCPCB or similar manufacturers.

- **Innovation & Independent Design:**  
  The most valuable part of this project was taking a guided design and **transforming it into something original**.  
  By integrating the **ESP32-WROOM module**, I evolved the standard Arduino Uno into a **wireless-capable development platform** that can communicate with other devices, upload data to the cloud, or be programmed remotely.  
  This process required understanding both the **hardware limitations** of the original design and the **electrical interfacing challenges** introduced by the ESP32 — such as UART multiplexing, logic-level compatibility, and antenna clearance.  
  Through experimentation and iteration, I developed a deeper understanding of **system-level design**, **hardware-software integration**, and the mindset needed to turn an existing idea into an innovative, real-world product.

This experience taught me how to approach hardware design not just as replication, but as **creative engineering** — improving, optimizing, and innovating on top of established systems to deliver added value.

