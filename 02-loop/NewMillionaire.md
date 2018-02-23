##อายุน้อยร้อยล้าน ในงานเกษตรแฟร์
---

เนื่องจากนิสิตได้มีโอกาสเดินเที่ยวภายในงาน “เกษตรแฟร์” ในปีที่ผ่านมาทำให้ นิสิตมีความคิดริเริ่มที่อยากจะเปิดร้านอาหารขายภายในงาน โดยอาหารที่นิสิตจะขายภายในงานนั้นมี 1.Hamburger Set ราคา 199 บาท 2. Chicken Set ราคา 299 บาท และ 3. Pizza Set ราคา 399 บาท โดยเมื่อจบงานเกษตรแฟร์นิสิตต้องการจะทราบรายการที่นิสิตได้ขายออกไปในแต่ละวัน และคำนวนหากำไรที่นิสิตได้ เนื่องจากนิสิตเป็นโปรแกรมเมอร์ที่ดี นิสิตจึงต้องการเขียนโปรแกรมเพื่อคำนวนยอดขายรวม และกำไรที่ได้

**ให้นิสิตเขียนโปรแกรม** คำนวนยอดขายรวม และกำไรที่ได้ โดยรับ Input เป็นเลขลำดับของรายการอาหาร (1–3) จนกระทั่ง Input เป็น 0 จากนั้นรับ Input เป็นจำนวนเงินต้นทุนทั้งหมด แล้วแสดง Output เป็น ยอดขายรวม และ กำไรที่ได้จากการขาย หรือจำนวนเงินที่ขาดทุน

**หมายเหตุ** เมื่อ Input เป็นเลขอื่นนอกเหนือจาก 0, 1, 2, 3 ให้แสดง “Invalid Input.”


---

### **ตัวอย่าง** **Input / Output**

```
Foods Menu
(1) Hamburger Set		199 baht.
(2) Chicken Set		299 baht.
(3) Pizza Set			399 baht.
(0) To end process.
Enter your sell item(0 - 3): 1
Enter your sell item(0 - 3): 2
Enter your sell item(0 - 3): 3
Enter your sell item(0 - 3): 0
Enter your total cost: 500
Congratulations!!
Your total sales are 897.00 baht.
You earned 397.00 baht.
```

```
Foods Menu
(1) Hamburger Set		199 baht.
(2) Chicken Set		299 baht.
(3) Pizza Set			399 baht.
(0) To end process.
Enter your sell item(0 - 3): 1
Enter your sell item(0 - 3): 2
Enter your sell item(0 - 3): 3
Enter your sell item(0 - 3): 4
Invalid Input.
Enter your sell item(0 - 3): 0
Enter your total cost: 3000
Better luck next time!!
Your total sales are 897.00 baht.
You lose 2103.00 baht.

```