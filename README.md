# 12V Regulated DC Power Supply (AC-DC)

A reliable and high-safety 12V DC power supply designed to convert AC input (from a transformer) into a stable DC output. This project emphasizes industrial safety standards with a focus on high-voltage isolation and thermal stability.

### 🛠 Hardware Specifications
- **PCB Type:** Single Sided (Bottom Layer) with Top Silkscreen.
- **Board Dimensions:** 124 mm x 91 mm.
- **Safety Feature:** **18 mm clearance** between AC primary and DC secondary sections.
- **Thermal Management:** Dedicated M3 mounting hole for a TO-220 heatsink.

## 📂 Files
- **/KiCad-Project**: Schematic (`.kicad_sch`) and PCB layout (`.kicad_pcb`) files.
- **/Fabrication**: Production-ready Gerber and Drill files (RS-274X format).
  - **Note:** Also includes a **Mirrored PDF** for DIY toner transfer (home-made) production.
- **/Images**: 3D renders, schematic, and PCB layout captures.

## 📋 Footprints
- **Voltage Regulator:** `Package_TO_SOT_THT:TO-220-3_Vertical` (L7812)
- **Bridge Rectifier:** `Diode_THT:Diode_Bridge_10.5x10.5x5.0mm_P5.0mm` (B40C1500G)
- **Capacitors:** - 2200µF: `Capacitor_THT:CP_Radial_D12.5mm_P5.00mm`
  - 100nF/330nF: `Capacitor_THT:C_Disc_D5.0mm_W2.5mm_P5.00mm`
- **Fuse Holder:** `Fuse:Fuseholder_Cylinder-5x20mm_Schurter_0031_8201_Horizontal`
- **Switch:** `Button_Switch_THT:SW_DPST_KAE_LS11_Straight` (AC Mains Isolation)
- **Terminals:** `TerminalBlock_Phoenix:TerminalBlock_Phoenix_MKDS-1,5-2_1x02_P5.00mm_Horizontal`
- **LED:** `LED_THT:LED_D5.0mm` (Power Status Indicator)

## ⚖️ License
Licensed under the **MIT License**. See `LICENSE` for more information.

---
**Design:** Onur Yurtsever  
