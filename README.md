# Layout Design of CMOS Common Source Amplifier, Current Mirror and Op-Amp (90nm)

## Introduction
This repository presents the complete **analog IC design and layout** of a **CMOS Common Source Amplifier**, **Current Mirror**, and **Operational Amplifier (Op-Amp)** using **Cadence Virtuoso** in **90nm CMOS technology**.  
Special emphasis is given to **matching-aware layout techniques**, including **common centroid (ABBA–BAAB pattern)** for precision analog design.



## Tools and Technology
**Tool:** Cadence Virtuoso  
**Technology:** 90nm CMOS  
**Design Type:** Analog IC Design & Layout  



# 1. CMOS Common Source Amplifier

## Circuit Description
NMOS transistor used as the main amplifying device  
PMOS transistor used as active load  
Proper biasing ensures saturation region operation  
Output taken from the drain of the NMOS transistor  

## Device Sizing
Proper transistor sizing is used to achieve the required gain and operating point.



## 📷 Design Files – Common Source Amplifier

### 🔹 Schematic  
`CS_Schematic.png`

### 🔹 PMOS W/L Ratio  
`Pmos_WL_ratio.png`

### 🔹 NMOS W/L Ratio  
`nmos_WL_ratio.png`

### 🔹 Layout  
`CS_Layout.png`

### 🔹 DRC Result  
`CS_NoDRC.png`

### 🔹 LVS Result  
`CS_LVS.png`



## Verification Summary
**DRC:** No DRC errors  
**LVS:** Matched  



# 2. Current Mirror Using Common Centroid Layout

## Introduction
The current mirror is designed using **common centroid layout** to minimize mismatch caused by process gradients and lithographic variations.

## Design Specifications
**Technology:** 90nm CMOS  
**W/L Ratio:** 10  
**Multiplier:** 8  
**Layout Technique:** Common Centroid  
**Pattern:** ABBA–BAAB  

## Layout Methodology
Each transistor is divided into **8 identical unit devices** and placed symmetrically in an **ABBA–BAAB** arrangement to improve current matching accuracy.



## 📷 Design Files – Current Mirror

### 🔹 Schematic  
`CurrentMirror_Schematic.png`

### 🔹 W/L Configuration  
`CurrentMirror_WL.png`

### 🔹 Common Centroid Layout  
`CurrentMirror_CC_Layout.png`

### 🔹 DRC Result  
`CurrentMirror_NoDRC.png`

### 🔹 LVS Result  
`CurrentMirror_LVS.png`



## Verification Summary
**DRC:** Clean  
**LVS:** Matched  
**Matching:** Improved using common centroid layout  



# 3. Operational Amplifier (Op-Amp) Layout Using Common Centroid

## Introduction
To reduce offset voltage and improve symmetry, the Op-Amp is laid out using **common centroid techniques**, especially for the differential input pair.

## Design Specifications
**Technology:** 90nm CMOS  
**Input Pair W/L Ratio:** 10  
**Multiplier:** 8  
**Layout Technique:** Common Centroid  
**Pattern:** ABBA–BAAB  

## Layout Methodology
The differential pair transistors are split into **8 unit fingers** and arranged in an **ABBA–BAAB** pattern to ensure centroid alignment and matching.



## 📷 Design Files – Op-Amp

### 🔹 Schematic  
`OpAmp_Schematic.png`

### 🔹 Differential Pair W/L  
`OpAmp_WL.png`

### 🔹 Common Centroid Layout  
`OpAmp_CC_Layout.png`

### 🔹 DRC Result  
`OpAmp_NoDRC.png`

### 🔹 LVS Result  
`OpAmp_LVS.png`



## Verification Summary
**DRC:** No errors  
**LVS:** Matched  
**Offset Performance:** Improved  



## Conclusion
The **Common Source Amplifier**, **Current Mirror**, and **Op-Amp** were successfully designed and verified in **90nm CMOS technology**.  
The use of **common centroid layout (ABBA–BAAB)** with **W/L = 10** and **multiplier = 8** significantly improves matching accuracy and reliability for analog IC applications.



## Author
**Tahmina Akter**  
Department of Electrical and Electronic Engineering (EEE)  
Green University of Bangladesh

