# โครงงานหนังสือ: สถาปัตยกรรมคอมพิวเตอร์

# 5.1 SEMICONDUCTOR MAIN MEMORY  

---

## 1. Organization  
หน่วยความจำหลักในปัจจุบันใช้ Semiconductor โดยมีหน่วยพื้นฐานคือ Memory Cell  
Memory cell สามารถเขียน (Write) และอ่าน (Read) ได้ โดยเก็บข้อมูลเป็น 0 และ 1  

---

## 2. DRAM and SRAM  
Semiconductor Memory แบ่งได้ 2 ประเภทหลัก  

### 2.1 RAM (Volatile)  
สามารถอ่านและเขียนได้ แต่ข้อมูลจะหายเมื่อไฟดับ  

DRAM เก็บข้อมูลในรูปประจุไฟฟ้า ต้อง Refresh ตลอดเวลา  
ราคาถูก ความจุสูง → ใช้เป็น Main Memory  

SRAM ใช้วงจร Flip-Flop ไม่ต้อง Refresh  
เร็วกว่าแต่ราคาแพง → ใช้เป็น Cache  

### 2.2 ROM (Non-Volatile)  
เก็บข้อมูลถาวร เน้นอ่าน ไม่เหมาะกับการเขียน  

---

## 3. Types of ROM  
ROM : เขียนมาจากโรงงาน แก้ไม่ได้  
PROM : เขียนได้ครั้งเดียว  
EPROM : ลบด้วยแสง UV และเขียนใหม่ได้  
EEPROM : ลบ/เขียนใหม่ด้วยไฟฟ้า (ระดับ Byte)  
Flash Memory : ลบเร็วกว่า และเก็บข้อมูลหนาแน่นกว่า  

---

## 4. Chip Logic (Organization & Chip Logic)  
การจัดเรียง : Memory Cell เรียงเป็น Row/Column (1 cell = 1 bit)  
การเข้าถึงข้อมูล : ใช้ Address และสัญญาณควบคุม เช่น WE, OE  
DRAM ใช้ RAS และ CAS เพื่อเลือก Row และ Column  
DRAM ต้อง Refresh ตลอดเวลา  

---

## 5. The Trade-off  
ไม่มีหน่วยความจำที่ดีที่สุด ต้องแลกกันระหว่าง Speed, Price, Capacity  

SRAM : เร็วมาก แต่แพง → Cache  
DRAM : ช้ากว่า แต่ถูกและจุเยอะ → Main Memory  
ROM : ใช้เก็บข้อมูลถาวร  

---
