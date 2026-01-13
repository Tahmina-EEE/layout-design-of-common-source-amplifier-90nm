# Layout Design of CMOS Common Source Amplifier (90nm)

## Introduction
A common source amplifier is one of the most fundamental CMOS analog amplifier configurations and is widely used for voltage amplification due to its high gain characteristics. This project presents the complete design flow of a CMOS common source amplifier using **Cadence Virtuoso** in **90nm CMOS technology**, including schematic design, device sizing, layout implementation, and physical verification results.



## Tools and Technology
Tool: Cadence Virtuoso  
Technology: 90nm CMOS  
Design Type: Analog IC Layout  



## Circuit Description
NMOS transistor used as the main amplifying device  
PMOS transistor used as active load  
Biasing ensures operation in saturation region  
Output taken from the drain of the NMOS transistor  



## Device Sizing (W/L Ratio)
Proper transistor sizing is crucial to achieve the desired gain, bias current, 
and operating point of the common source amplifier.



## 📷 Design Images

### 🔹 Schematic
![Common Source Amplifier Schematic](Screenshots/cs_amplifier_schematic.png)


### 🔹 PMOS Transistor W/L Ratio
![PMOS W-L Ratio](Screenshots/pmos_wl_ratio.png)


### 🔹 NMOS Transistor W/L Ratio
![NMOS W-L Ratio](Screenshots/nmos_wl_ratio.png)


### 🔹 Layout
![Common Source Amplifier Layout](Screenshots/cs_amplifier_layout.png)


### 🔹 Design Rule Check (DRC)
![DRC Result](Screenshots/cs_amplifier_drc.png)


### 🔹 Layout Versus Schematic (LVS)
![LVS Result](Screenshots/cs_amplifier_lvs.png)


## Verification Summary
Design Rule Check (DRC): **No DRC errors**
Layout Versus Schematic (LVS): **Matched**



## Conclusion
The CMOS common source amplifier was successfully designed and verified in 90nm technology using Cadence Virtuoso. The schematic, transistor sizing, layout, and verification results demonstrate correct functionality and layout reliability.



## Author
**Tahmina Akter**  
Department of EEE  
Green University of Bangladesh





