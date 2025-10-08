# 28Pins Project – Custom Arduino Board with ESP32 Wireless Upgrade

This project is a **custom Arduino Uno-based PCB designed in Altium Designer**, enhanced with **ESP32-WROOM** to enable **wireless communication via the ESP32 antenna**.  

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



