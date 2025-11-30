
Exp 6 Simulation of Optical Communication System
## Introduction to OptiPerformer 
## Objective
Download and install OptiPerformer software on your computer and run a sample file.

---

## Overview

Optiwave introduces **OptiPerformer**, a free photonic design automation tool that harnesses the full power of OptiSystem and creates specific dynamic design scenarios for student use.

In this exercise, you will:
- Download and install OptiPerformer on your PC/laptop.
- Use your license to load and run OptiSystem simulations prepared for this course.

The first simulation file (`Introduction_OptiPerformer.osp`) models a basic fiber optic system consisting of:
- A transmitter
- A fiber
- A receiver

The system includes:
- An optical power meter at the receiver input (fiber output)
- A Bit Error Rate (BER) analyzer

---

## Instructions

1. Download and install OptiPerformer from [optiwave.com](https://optiwave.com).  
2. Copy the `Introduction_OptiPerformer.osp` file to your PC.  
3. Launch OptiPerformer.  
4. Use the **File** menu or **Open File** button to open the fiber optic system file.  
5. Study the layout:
   - **Transmitter** section includes:
     - Binary source (PRBS generator)
     - Electrical pulse generator
     - Laser diode
     - External modulator  
   - **Receiver** section includes:
     - Photodiode
     - Low-pass filter
     - Decision circuit with BER analyzer  
6. Run the simulation using the **Start** button.  
   - Progress will be displayed.
   - Message “Calculation Finished!” appears upon completion.  
7. Double-click the **optical power meter** and **BER analyzer** windows.  
   - Check “Show Eye Diagram” in the BER window.  
   - Optical power meter shows power in watts and dBm.  
   - BER window displays:
     - Eye diagram
     - Max Q Factor
     - Min BER  
8. The simulation runs 5 iterations with fiber length varying from 50 to 150 km.  
   - Use forward/reverse buttons to step through iterations.  
   - Observe changes in received power, BER, Q factor, and eye diagram.

---

## Report

1. Cover sheet (as per attached example).  
2. Tabulation of received power, Q factor, and BER for 5 fiber lengths.  
3. Plot of received power, Q factor, and BER vs. fiber length.  
4. Description of eye diagram changes with increasing fiber length.

---

## Tabulation

**Transmission Analysis Across Fiber Lengths**

![WhatsApp Image 2025-11-17 at 09 04 19_7b3ed7f1](https://github.com/user-attachments/assets/3132c581-2e0b-4f8d-838b-55ff86aefc1d)


| S.No | Fiber Length (km) | Optical Power (Watts)   | Optical Power (dBm) | Max Q Factor | Min BER | Eye Height       | Decision Instant (Max Q / Min BER) |
|------|--------------------|--------------------------|----------------------|--------------|---------|-------------------|-------------------------------------|
| 1    | 56                 | 36.746 × 10⁻⁶            | -14.340              | 98.60        | 0       | 7.371602 × 10⁻⁵   | 0.5468                              |
| 2    | 57                 | 33.962 × 10⁻⁶            | -14.690              | 87.09        | 0       | 7.003130 × 10⁻⁵   | 0.5468                              |
| 3    | 58                 | 34.052 × 10⁻⁶            | -14.670              | 85.16        | 0       | 6.89320 × 10⁻⁵    | 0.5468                              |
| 4    | 59                 | 32.520 × 10⁻⁶            | -14.870              | 86.767       | 0       | 6.40756 × 10⁻⁵    | 0.5468                              |
| 5    | 60                 | 29.579 × 10⁻⁶            | -15.200              | 99.546       | 0       | 6.137684 × 10⁻⁵   | 0.5469                              |


## Graphs

<img width="623" height="346" alt="image" src="https://github.com/user-attachments/assets/70b3eabe-9200-4513-b690-393a22c903d4" />

<img width="624" height="361" alt="image" src="https://github.com/user-attachments/assets/0976ed4d-4d4a-4908-b934-452d3ac71a7a" />

<img width="625" height="358" alt="image" src="https://github.com/user-attachments/assets/61f92b36-b5ec-43cd-9934-c173d1e178f5" />

<img width="624" height="354" alt="image" src="https://github.com/user-attachments/assets/f881521a-34a4-4c3d-8ec7-f81bedf09917" />

<img width="622" height="353" alt="image" src="https://github.com/user-attachments/assets/44f853ae-5882-4be5-b8f2-572872a1d9ea" />



---

## RESULT

Hence the graphs are verified using optiperformer.
