# URL
## Problem
ตรวจสอบว่าข้อความที่รับเข้ามาเป็น url หรือไม่ โดยในที่นี้กำหนดให้ url ต้องมีลักษณะดังนี้

- ขึ้นต้นด้วย www.
- ห้ามมีเว้นวรรค
- ต้องมีรูปแบบเป็น www.a.b.c. … เมื่อ a, b และ c เป็นสายอักขระใดๆ โดยต้องมีจุดอย่างน้อย 2 จุด และต้องไม่มีจุดอยู่ท้ายสุดของ url เช่น www.chornerman.xyz

วนลูปรับข้อความและนำมาตรวจสอบไปเรื่อยๆ จนกว่าผู้ใช้จะพิมพ์ 0 จึงออกจากโปรแกรม หากเป็น url ให้แสดงผลว่า URL หากไม่ใช่ให้แสดงผลว่า NOT URL

หมายเหตุ: ข้อความที่รับเข้ามาต้องมีความยาวไม่เกิน 19 อักขระ

## Input/Output
- Input
    - ข้อความที่ต้องการตรวจสอบ (String)
- Output
    - ผลการตรวจสอบ (URL or NOT URL)

## Test case
```
//Test case #1
Enter your text here (max 19 char): www.a.b.c.com
URL

//Test case #2
Enter your text here (max 19 char): www.a.
NOT URL

//Test case #3
Enter your text here (max 19 char): www.a b.com
NOT URL
```