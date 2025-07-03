# STM32-RF-PCB
STM32 based radio-frequency transceiver PCB for IoT applications on KiCad:

This project is a fully custom 2-layer PCB designed around the STM32L432 microcontroller and the NRF24L01+ RF transceiver. Built using KiCad 7, it features USB power/data, an SWD debug interface, and an impedance-matched antenna section.
---
![Screenshot 2025-07-01 174706](https://github.com/user-attachments/assets/f88b9dc2-baa0-480f-a831-3dccb6e972e5)

---
## Features

- **MCU**: STM32L432K (32-bit ARM Cortex-M4)
- **RF**: NRF24L01+ 2.4 GHz transceiver
- **Power**: USB 5V input, onboard 3.3V regulation
- **Interface**:
  - SWD header for debugging/programming
  - USB interface for data/power
- **RF Matching Network** for antenna output
- **SMD-Only Design** for compact assembly
- **2-Layer PCB**

---

## Design Tools & Stack

- **KiCad 7**
  - Schematic capture
  - PCB layout
  - 3D visualization
  - DRC/ERC validation
- **ST-Link v2** for programming/debugging

---

## What I Learned

- Net class management, trace width/spacing tuning  
- RF layout constraints (short matched lines, clean ground returns, Differential pairing)  
- SWD routing and antenna network integration  
- 3D verification and design-for-manufacturability (DFM)

---

## Repo Contents

| Folder / File           | Description                               |
|-------------------------|-------------------------------------------|
| `pcb.kicad_sch          | KiCad schematic           |
| `pcb.kicad_pcb          | KiCad layout              |



## Next Steps

- Assemble and test the board
- Flash custom STM32 firmware
- Implement RF comm layer (transmit/receive)
- Explore sensor integration over SPI/UART/I2C



## Contact

Feel free to reach out or connect if you're working on RF or PCB hardware!
