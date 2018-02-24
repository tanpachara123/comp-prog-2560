# Guess The Sum #

จงเขียนโปรแกรมเกมหาผลรวมของเลขฐานสองจำนวน 2 ตัว (Unsigned Binary) และถามหาผลรวมของเลขฐานสองนั้นในรูปแบบของเลขฐานสิบ โดยเลขฐานสองจำนวน 2 ตัวนั้น ให้ผู้ใช้เป็นคนกำหนด ส่วนการตอบคำถามจะสามารถตอบได้เพียง 3 ครั้งเท่านั้น

โดยหากตอบไม่ถูกต้องในครั้งแรกหรือครั้งที่สอง ให้โปรแกรมบอกว่าคำตอบไม่ถูกต้อง ให้ทำการลองใหม่ พร้อมบอกจำนวนครั้งที่เหลือในการลอง

หากตอบครบ 3 ครั้งแล้วยังไม่ถูกต้อง ให้โปรแกรมทำการเฉลยคำตอบ ซึ่งถ้าหากข้อมูลเข้าของส่วนที่รับเลขฐานสองเลขใดไม่ถูกต้อง (ไม่ใช่เลขฐานสอง) ให้แสดงข้อความว่า `Invalid binary number. Try again.` และให้ทำการใส่เลขส่วนนั้นอีกครั้ง

### ตัวอย่างผลรวมเลขฐานสองในรูปแบบเลขฐานสิบ

สมมติให้เลขฐานสองจำนวน 2 ตัวคือ 111 และ 101

111 + 101 = 1100

ซึ่ง 1100 ฐานสอง = 12 ฐานสิบ

เพราะฉะนั้นผลรวมของเลขฐานสองในรูปแบบของเลขฐานสิบคือ 12


### ตัวอย่าง Input/Output
```
Enter the first binary number: 111
Enter the second binary number: 101
What is the sum of two binary numbers in decimal?
Your answer: 12
Good job! The answer is correct.
```
```
Enter the first binary number: 10111011
Enter the second binary number: 1000010
What is the sum of two binary numbers in decimal?
Your answer: 207
Incorrect! Try again. (2 attempts left)
Your answer: 205
Incorrect! Try again. (1 attempt left)
Your answer: 215
3 times incorrect! The answer is 221
```
```
Enter the first binary number: 1112
Invalid binary number. Try again.
Enter the first binary number: 10
Enter the second binary number: 1150
Invalid binary number. Try again.
Enter the second binary number: 100
What is the sum of two binary numbers in decimal?
Your answer: 6
Good job! The answer is correct.
```
