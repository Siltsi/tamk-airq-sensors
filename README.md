# TAMK AIRQ SENSORS  

## TEAM25  

**Members**  
- Eino Lausmaa ([@eino](https://github.com/LausmaaEino))  
- Samu Ojala ([@samu](https://github.com/SamuOj))  
- Tomi Tienhaara ([@tomi](https://github.com/TomiTien))  
- Totti Sillanpää ([@totti](https://github.com/Siltsi))  

## About  

This repository contains a hardware project developed for the **TAMK Summer Training 2025**. The project goal is to design and manifacture a custom circuit board and enclosure for **PCB-based particle sensor systems**.  

All PCBs in this project were designed using **KiCad**.  

## Models  

### ttgo_airq  

The **ttgo_airq** model is based on the LILYGO [T-Display](https://lilygo.cc/products/t-display). This model is currently in a **usable and tested state**.  

**Features:**  
- ESP32 with integrated display  
- Custom-designed PCB  
- 2 enclosure options  

**Enclosures:**  
- **Medium enclosure**  
  - Supports Sensirion [SEN5x](https://sensirion.com/products/catalog/SEK-SEN5x)  
  - Supports Sensirion [SCD41](https://sensirion.com/products/catalog/SEK-SCD41)  
- **Small enclosure**  
  - Supports Sensirion [SCD41](https://sensirion.com/products/catalog/SEK-SCD41) only  

### nodemcu_airq  

The **nodemcu_airq** model is based on the Joy-IT [NodeMCU ESP32](https://joy-it.net/en/products/SBC-NodeMCU-ESP32).  
This model is **still a work in progress**.  

**Current status:**  
- PCB design is expected to be functional  
- System-level development is ongoing  

**Display options:**  
- Large display using the Velleman [VMP400](https://www.velleman.eu/products/view/3-5-320-x-480-touchscreen-for-raspberry-pi-vmp400/?id=438240)  
- Smaller display  
- No display  

**Enclosures:**  
- No enclosures have been designed yet for this model  