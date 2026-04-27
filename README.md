# 🧮 8-bit Calculator (Logisim Evolution)

## 📄 Authors
- Dzhanteliev Adilkhan
- Usenkanov Ularbek
- Sakybaev Meder

  ### Note: If the application says that there are no 'Multiplie', 'Multiplie10' or 'Divider' files, then you should download them also from github repository and select them when the logisim program will propose

## 📌 Project Overview
This project is an **8-bit digital calculator** designed in **Logisim Evolution**.  
It simulates arithmetic operations using basic digital logic components such as adders, subtractors, multipliers, and display decoders.

The calculator performs operations on 8-bit binary numbers and displays the result on 7-segment displays.

---

## ⚙️ Features
- 8-bit arithmetic operations
- Addition, subtraction, multiplication
- Binary to BCD conversion
- Output using 7-segment displays
- Built using digital logic (no programming languages)

---

## 🧩 Components Description

<img width="224" height="402" alt="image" src="https://github.com/user-attachments/assets/af89b82b-a62f-4294-a91e-ca30137db989" />


### ➕ Addition Components
- **FullAdder** – 1-bit full adder (A, B, Carry-in -> sum, carry-out)


  <img width="775" height="296" alt="image" src="https://github.com/user-attachments/assets/665744ef-ca6c-4d7b-a9fc-3a29fabd9b61" />

- **Adder8bit** – chain of FullAdders for 8-bit addition

  <img width="1908" height="161" alt="image" src="https://github.com/user-attachments/assets/4cbd78bf-3ad3-45a5-9a8d-00ccf36e897f" />

- **AdderComponent** – main addition module

  <img width="1278" height="760" alt="image" src="https://github.com/user-attachments/assets/4380fe48-c084-4460-9fd5-67ea27b4d4c5" />


### ➖ Subtraction
- **SubComponent** – subtraction using two’s complement method

  <img width="1511" height="775" alt="image" src="https://github.com/user-attachments/assets/1bc344b6-de78-4750-9c6a-74a01bae797c" />


### ✖️ Multiplication
- **Multiplie10** – multiplication module (likely optimized for specific logic)

  <img width="1416" height="1331" alt="image" src="https://github.com/user-attachments/assets/35312aaa-e96f-4c51-acdb-e599321d14a1" />


---

## 🔢 Binary to Decimal Conversion

- **B8TOBCD** – converts 8-bit binary to BCD

  <img width="1081" height="582" alt="image" src="https://github.com/user-attachments/assets/6f20c084-c966-445e-b1cf-0101f53efbfb" />

- **B8TCTOBCD** – extended version of BCD conversion (with carry/tens correction)

  <img width="1093" height="539" alt="image" src="https://github.com/user-attachments/assets/f6798247-3f0c-42ae-96fd-bf0c019b9b80" />

- **ADD 3 IF THE AMOUNT IS GREATER THAN OR EQUAL TO 5**

  <img width="1559" height="1193" alt="image" src="https://github.com/user-attachments/assets/78ed4c23-b91c-490c-9f5b-b02ca45aa969" />

  Part of the **Double Dabble algorithm** used in binary → BCD conversion

---

## 💡 Display

- **IC7448** – BCD to 7-segment decoder  
  Converts BCD values into signals for display output
  <img width="535" height="347" alt="image" src="https://github.com/user-attachments/assets/3628e237-eb8c-4108-a37e-cd9425834c27" />


---

## 🧠 Main Modules

- **main**  
  Connects multiplier and display

  <img width="1705" height="729" alt="image" src="https://github.com/user-attachments/assets/d95a06a7-1b2b-4ab5-a6c7-711cabe01155" />


- **CALCULATOR**
  - Handles inputs (buttons)
  - Uses SR and D flip-flops
  - Performs calculations
  - Outputs to 7-segment display
 
    <img width="1349" height="765" alt="image" src="https://github.com/user-attachments/assets/dc1783e1-f048-4437-a0cb-3894962e5be1" />


---

## 🔌 Technologies
- Logisim Evolution
- Digital Electronics
- Combinational Logic
- Sequential Logic (Flip-Flops)

---

## 🧠 Concepts
- Binary arithmetic
- Two’s complement
- Multiplication logic
- Double Dabble algorithm
- BCD encoding
- 7-segment decoding

---

## ▶️ How to Run
1. Open project in Logisim Evolution
2. Open `CALCULATOR` circuit
3. Click on the 'Simulate', then 'Auto-Tick enabled' to turn it on
4. Input values using switches/buttons
5. Observe output on displays

---

### Examples:
<img width="1151" height="695" alt="image" src="https://github.com/user-attachments/assets/6a950e9a-65f0-4158-8c95-a7054d75957c" />
<img width="1153" height="612" alt="image" src="https://github.com/user-attachments/assets/03cb96e2-037a-4291-a62e-f3a4fcaa9357" />
<img width="1163" height="625" alt="image" src="https://github.com/user-attachments/assets/08f61f55-4da2-46d9-9b81-ff8a3bd6e36d" />
<img width="1167" height="609" alt="image" src="https://github.com/user-attachments/assets/b31240fa-e931-4746-a4b5-25c81c1a2e01" />



---

## 📄 Authors
- Dzhanteliev Adilkhan
- Usenkanov Ularbek
- Sakybaev Meder
