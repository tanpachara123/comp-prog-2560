# โจทย์ปัญหา Loop
## ชื่อโจทย์: ตัวเลขในช่วงที่หารด้วย 3, 7 และ 11 ลงตัว แต่หารด้วย 2 ไม่ลงตัว *\(Divide or not divide?\)*

ให้รับช่วงของตัวเลขในรูปแบบ `a-b` เป็นจำนวนเต็มบวกทั้ง `a` และ `b` และค่า `a` เป็นค่าเริ่มต้นของช่วงไปจนถึงค่า `b`  โดยที่ค่าตัวเลขของ `b` จะต้องมีค่ามากกว่า `a`  แล้วให้ทดสอบว่าตัวเลขที่เริ่มต้นตั้งแต่ `a` จนถึง `b` มีตัวเลขใดที่หารด้วย 3, 7 และ11 ลงตัวแต่หารด้วย 2 ไม่ลงตัวบ้าง พร้อมแสดงจำนวนตัวเลขที่หารด้วย 3, 7 และ 11 ลงตัวแต่หารด้วย 2 ไม่ลงตัว และจำนวนตัวที่หารด้วย 2, 3, 7 และ 11 ลงตัว**

**หมายเหตุ**
- ถ้าหากข้อมูลตัวเลขที่รับเข้ามาไม่เป็นตามที่เงื่อนไขกำหนดให้แสดงข้อความ `Invalid input.`
-  ค่า `a` และ `b` จะมีค่าไม่เกิน 2,000,000,000
---
**ข้อมูลนำเข้า \(Input\)**  
ช่วงของตัวเลขที่เริ่มต้นตั้งแต่ `a` ไปจนถึง `b` ในรูปแบบที่กำหนดคือ `a-b`

**ข้อมูลออก \(Output\)**  
- 1) ตัวเลขที่หารด้วย 3, 7 และ 11 ลงตัวแต่หารด้วย 2 ไม่ลงตัว
- 2) จำนวนตัวที่หารด้วย 3, 7 และ 11 ลงตัวแต่หารด้วย 2 ไม่ลงตัว
- 3) จำนวนตัวที่หารด้วย 2, 3, 7 และ 11 ลงตัว

**ตัวอย่างของ Input/Output ดังนี้**

```
Input range :   Enter a range: 0-100
Output      :   >>Invalid input.
```

```
Input range :   Enter a range: 1-100
Output      :   #There are 0 numbers that can be divided by 3,7 and 11 but that can't be divided by 2.
                #There are 100 numbers that can be divided by 2,3,7 and 11.
```

```
Input  range :  Enter a range: 1-500
Output       :  >>231
                #There are 1 number that can be divided by 3,7 and 11 but that can't be divided by 2.
                #There are 499 numbers that can be divided by 2,3,7 and 11.
```

```
Input range :   Enter a range: 1-999
Output      :   >>231
                >>693
                #There are 2 numbers that can be divided by 3,7 and 11 but that can't be divided by 2.
                #There are 997 numbers that can be divided by 2,3,7 and 11.
```
