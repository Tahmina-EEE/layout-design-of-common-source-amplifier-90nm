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
<img width="307" height="404" alt="CS amp schemetic" src="https://github.com/user-attachments/assets/938dde8d-d8a8-481c-b887-9d2a87915e4a" />

### 🔹 Layout  
<img width="437" height="410" alt="CS amp for layout" src="https://github.com/user-attachments/assets/5cbc6c07-799b-4872-91a2-d81ee61df735" />


### 🔹 DRC Result  
<img width="389" height="368" alt="CM_NoDRC" src="https://github.com/user-attachments/assets/6789b5d4-27c9-47d5-90b7-a03cdce8ffb5" />


### 🔹 LVS Result  
<img width="238" height="245" alt="CS_Amplifier_NoLVS" src="https://github.com/user-attachments/assets/25afa349-33c6-4c0b-b982-b2d0240ebc84" />




## Verification Summary
**DRC:** No DRC errors  
**LVS:** Matched  



# 2. Current Mirror Using Interdigitated Layout

## Introduction
The current mirror is designed using **interdigitated layout** to minimize mismatch caused by process gradients and lithographic variations.

## Design Specifications
**Technology:** 90nm CMOS  
**W/L Ratio:** 10  
**Multiplier:** 8  
**Layout Technique:** Interdigitated 


## Layout Methodology
Each transistor is divided into **8 identical unit devices** 


## 📷 Design Files – Current Mirror

### 🔹 Schematic  
<img width="726" height="403" alt="Current_Mirror_Schematic" src="https://github.com/user-attachments/assets/fdb81a3e-f467-43ef-b862-08c0a48089ef" />


### 🔹 W/L Configuration  
<img width="647" height="365" alt="CM_Multiplier" src="https://github.com/user-attachments/assets/d2242598-f614-4252-8ac8-79a087dffc94" />
<img width="596" height="296" alt="CM_Multiplier2" src="https://github.com/user-attachments/assets/7a094ff5-c0f9-4deb-aad8-5165b0bd3ad4" />


### 🔹 Common Centroid Layout  
<img width="103" height="419" alt="Current_Mirror_Layout" src="https://github.com/user-attachments/assets/d9dc8122-a965-4e17-b3a7-9aaea8104423" />


### 🔹 DRC Result  
<img width="186" height="404" alt="Current_Mirror_NoDRC" src="https://github.com/user-attachments/assets/c9f4a369-4083-4cdf-88f5-1496fa2bcb1a" />


### 🔹 LVS Result  
<img width="103" height="419" alt="Current_Mirror_Layout" src="https://github.com/user-attachments/assets/09fc13f0-5556-41c0-b4e1-81ee6e540c1a" />




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
<img width="419" height="404" alt="OP_Amp_Schematic" src="https://github.com/user-attachments/assets/90c77dad-65df-4acd-ad3c-3a5c3e2c4f8f" />


### 🔹 Differential Pair W/L  
<img width="572" height="407" alt="OP_Amp_Multiplier" src="https://github.com/user-attachments/assets/7c010c49-5978-472a-a3cd-2261b58d453e" />
<img width="535" height="395" alt="OP_Amp_Multiplier2" src="https://github.com/user-attachments/assets/27b59680-b08a-4105-8bd1-badf0480bd5a" />


### 🔹 Common Centroid Layout  
<img width="128" height="380" alt="OP_Amp_Layout" src="https://github.com/user-attachments/assets/673549f9-45c7-4531-b3a9-fbb46d8dcac9" />


### 🔹 DRC Result  
<img width="241" height="382" alt="OP_Amp_NoDRC" src="https://github.com/user-attachments/assets/75030214-d0f5-4247-afe7-98a06f2a8df3" />


### 🔹 LVS Result  




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

