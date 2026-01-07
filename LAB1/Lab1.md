# Lab 1: Establishing Network Device Connections Using Ethernet Cables

## Objective
To prepare Ethernet cables using RJ45 connectors and verify their functionality by creating both straight-through and crossover cables and testing them with a cable tester.

---

## Part A: Fabrication of Ethernet Cable with RJ45 Connectors

### Equipment and Tools Used
- UTP Ethernet cable (Category 5e / Category 6)
- RJ45 modular connectors
- Crimping tool
- Wire stripping tool
- Network cable tester

---

## Part B: Cable Preparation Procedure

### 1. Straight-Through Ethernet Cable

A straight-through cable is commonly used to connect unlike network devices such as a computer to a switch.

#### Procedure
1. The Ethernet cable was cut to the required length.
2. About one inch of the outer insulation was stripped from both ends.
3. The twisted wire pairs were untwisted and arranged according to the **T568B wiring standard**:
   - Pin 1: White–Orange  
   - Pin 2: Orange  
   - Pin 3: White–Green  
   - Pin 4: Blue  
   - Pin 5: White–Blue  
   - Pin 6: Green  
   - Pin 7: White–Brown  
   - Pin 8: Brown  
4. All wires were trimmed evenly.
5. The wires were inserted into the RJ45 connector in the correct order.
6. The connector was crimped using a crimping tool.
7. The same T568B arrangement was repeated on the other end.
8. The cable was tested using a cable tester.

---

### 2. Crossover Ethernet Cable

A crossover cable is typically used to connect similar devices such as two computers.

#### Procedure
1. The Ethernet cable was cut and stripped as before.
2. One end of the cable was arranged according to the **T568A wiring standard**:
   - Pin 1: White–Green  
   - Pin 2: Green  
   - Pin 3: White–Orange  
   - Pin 4: Blue  
   - Pin 5: White–Blue  
   - Pin 6: Orange  
   - Pin 7: White–Brown  
   - Pin 8: Brown  
3. The other end was arranged using the **T568B wiring standard**.
4. The wires were trimmed evenly and inserted into RJ45 connectors.
5. Both ends were crimped securely.
6. The cable was tested using a cable tester.

---

## Part C: Cable Testing and Verification

### Testing Procedure
1. One end of the cable was connected to the transmitter unit of the cable tester.
2. The other end was connected to the receiver unit.
3. The tester was powered on and LED indicators were observed.

### Expected Results
- **Straight-through cable:** Pins 1 through 8 light up in the same order on both ends.
- **Crossover cable:** Transmit and receive pairs are crossed:
  - Pin 1 ↔ Pin 3  
  - Pin 2 ↔ Pin 6  
  - Pin 3 ↔ Pin 1  
  - Pin 6 ↔ Pin 2  

---

## Observations and Results
- The cable tester showed correct continuity for all wire pairs.
- No shorts, open circuits, or miswiring were detected.
- Test outputs were captured and stored in the respective *straight-through* and *crossover* image folders.

---

## Conclusion
This lab demonstrated the successful construction and testing of Ethernet cables using RJ45 connectors. Both straight-through and crossover cables were prepared following standard wiring schemes and verified using a cable tester.
