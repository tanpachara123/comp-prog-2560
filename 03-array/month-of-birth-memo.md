# Month of Birth Memo #

เด็กหญิงคนหนึ่งอยากที่จะรู้ว่าในแต่ละเดือนนั้นมีเพื่อนเกิดกี่คน เธอจึงคิดที่จะสร้างโปรแกรมบันทึกจำนวนของเพื่อนๆที่เกิดในแต่ละเดือนขึ้น โดยที่โปรแกรมนี้จะรับจำนวนเพื่อนๆ ที่ต้องการบันทึก (อย่างน้อย1คน ถ้านอกเหนือจากนี้ให้แจ้งข้อความ `ERROR` และหยุดการทำงาน) และจึงรับเลขเดือนเกิดของเพื่อนแต่ละคน เช่น 2 หมายถึงเดือนกุมภาพันธ์ (ถ้าข้อมูลเดือนเกิดผิดพลาดให้แจ้งข้อความ `Invalid month.` และให้รับค่าใหม่) หลังจากรับข้อมูลเดือนเกิดของเพื่อนแต่ละคนครบแล้วให้รับเลขเดือนเกิดที่เราสนใจ(ถ้าข้อมูลเดือนเกิดผิดพลาดให้แจ้งข้อความ `Invalid month.` และให้รับค่าใหม่)  และแสดงผลเป็นจำนวนเพื่อนที่เกิดในเดือนนั้น

#### ตัวอย่าง Input/Output:
```
How many friends data do you want for memo: 5
Month for friend #1: 11
Month for friend #2: 12
Month for friend #3: 13
Invalid month.
Month for friend #3: 12
Month for friend #4: 12
Month for friend #5: 12
What month do you want to see: 12
Number of friends who born in December are 4.
```
#### ตัวอย่าง Input/Output:
```
How many friends data do you want for memo: 3
Month for friend #1: 9
Month for friend #2: 4
Month for friend #3: 6
What month do you want to see: 7
Number of friends who born in July is 0.
```