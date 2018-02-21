# Guessing First Three numbers

สำหรับการเสี่ยงโชคในการซื้อลอตเตอรี่ นักเสี่ยงโชคมีสูตรมากมายในการคำนวณหาเลขเด็ดๆเพื่อเพิ่มความเป็นไปได้ในการถูกรางวัล ซึ่งวิธีการเดาเลขวิธีหนึ่งมีหลักการดังต่อไปนี้
ให้นำเลขรางวัลที่ 1 (6 หลัก) ของงวดที่แล้วมาคิดด้วยวิธีดังนี้
   1. นำเลขหลักหมื่นคูณด้วย 2 จากนั้นให้นำไปบวกกับเลขหลักร้อยของรางวัลที่ 1 ในงวดที่แล้ว
   2. นำเลขหลักร้อยคูณด้วย 3 จากนั้นให้นำไปบวกกับเลขหลักหน่วยของรางวัลที่ 1 ในงวดที่แล้ว
   3. นำผลลัพธ์ที่ได้จากข้อ 1 และ ข้อ 2 มารวมกัน ผลลัพธ์ที่ได้และผลลัพธ์ที่ได้บวกด้วย 2 จะเป็น   ตัวเลขที่น่าจะมีในเลข 3 ตัวแรกของเลขลอตเตอรี่รางวัลที่ 1 ในงวดถัดไป

หมายเหตุ :	
ถ้าผลลัพธ์ในการกระทำใดๆมีค่ามากกว่า 1 หลักให้ใช้เลขหลักสุดท้าย

หากมีการกรอกค่านำเข้าผิดให้ขึ้นประโยคว่า “SORRY, please enter new numbers.”

`<อ้างอิงวิธีการคิดจาก>` : <https://www.youtube.com/watch?v=wytHdSptUnc>


![](https://raw.githubusercontent.com/noonnutchaya/6010405211/master/guessing%20first%20three%20numbers.png)

### ตัวอย่าง Input/Output
ตัวอย่าง Input/Output ที่ 1

Enter first prize winning numbers last time (6 digits) : 12345

SORRY, please enter new numbers.

ตัวอย่าง Input/Output ที่ 2

Enter first prize winning numbers last time (6 digits) :  887102

Next time will have 2 and 4 in first three numbers in a lottery.  




