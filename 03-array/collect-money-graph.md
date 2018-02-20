#ARRAY
##โจทย์ปัญหา
**"กราฟออมทรัพย์"**
    โรงเรียนแห่งหนึ่งมีมาตรการให้นักเรียนได้ทำกราฟสะสมเงินเก็บของตนเอง เพื่อปลูกฝังให้นักเรียนนั้นได้เก็บออมเพื่อจะได้มีเงินไว้ใช้ โดยนักเรียนทุกคนนั้นได้เงินมาโรงเรียนวันละ 100 บาท จากผู้ปกครอง 
    ดังนั้นให้นิสิตเขียนโปรแกรมช่วยนักเรียนเหล่านั้นทำกราฟสะสมเงินเก็บของแต่ละคน โดยรับข้อมูลเข้าในบรรทัดแรกเป็นจำนวนวันที่นักเรียนเก็บออม บรรทัดที่สอง รับชื่อของนักเรียนคนนั้นๆ และให้รับจำนวนเงินเก็บในแต่ละวัน โดยที่เงินเก็บในแต่ละวันจะไม่สามารถติดลบได้ ถ้าหากติดลบหรือมากกว่า 100 บาท ให้แสดงข้อความออกสองบรรทัดว่า "Invalid input." และ "Please Input again." ทำการรับข้อมูลเข้าในวันนั้นใหม่ เมื่อรับข้อมูลครบทุกวันให้ทำกราฟสรุปของแต่ละวันว่าได้ออมเงินจำนวนเท่าไหร่ โดยเก็บเป็นสัญลักษณ์แทนจำนวนเงิน 10, 5, 1 บาท ในกราฟแต่ละวันนั้นให้แสดงสัญลักษณ์ ที่แทนจำนวนเงินจากมากไปน้อย และในบรรทัดสุดท้ายให้แสดงผลจำนวนเงินที่นักเรียนคนนั้นสะสมได้ 
    **กำหนดให้** สัญลักษณ์ "*" แทนจำนวนเงิน 10 บาท "+" แทน 5 บาท และ "-" แทน 1 บาท และจำนวนของอักขระในชื่อต้องไม่เกิน 20 อักขระ
## ตัวอย่าง TEST CASE ที่ใช้ตรวจสอบชุดคำสั่งดังกล่าว 
--------
How many day(s) to collect: 3 

What is your name: Birddy 

How much Birddy's collect in day 1: -1 

Invalid input. 

Please Input again. 

How much Birddy's collect in day 1: 101 

Invalid input. 

Please Input again. 

How much Birddy's collect in day 1: 22 

How much Birddy's collect in day 2: 33 

How much Birddy's collect in day 3: 44 

day  1  **-- 

day  2  ***--- 

day  3  ****---- 

Birddy collect 99 baht. 

-----------
How many day(s) to collect: 5 

What is your name: Birddy 

How much Birddy's collect in day 1: 0 

How much Birddy's collect in day 2: 9 

How much Birddy's collect in day 3: 4 

How much Birddy's collect in day 4: 5 

How much Birddy's collect in day 5: 100 

day  1 

day  2  +---- 

day  3  ---- 

day  4  + 

day  5  ********** 

Birddy collect 118 baht. 

---------