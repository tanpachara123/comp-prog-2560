## Student's BMI List.....

**โจทย์การเก็บค่า  BMI ของนักเรียนกลุ่มหนึ่ง  :**

จงเขียนโปรแกรมคำนวณค่า BMI โดยให้บรรทัดแรกแสดงข้อความ *Enter number of student:*  เพื่อรับค่าจำนวนเต็มบวกซึ่งหมายถึงจำนวนนักเรียนในกลุ่ม หากใส่จำนวนนักเรียนผิดพลาดให้แสดงข้อความ *ERROR* หากใส่ข้อมูลส่วนสูงหรือน้ำหนักผิดให้แสดงข้อความบรรทัดแรกคือ *Invalid height or weight.* บรรทัดต่อมาคือ *Please check the accuracy again.*  หากข้อมูลเข้าถูกให้บรรทัดต่อไปแสดงข้อความ *Enter student(ลำดับของนักเรียนคนนั้น) height(m):* รับค่าส่วนสูงในหน่วยเมตร และแสดงข้อความ *Enter student(ลำดับของนักเรียนคนนั้น) weight(kg):*  รับน้ำหนักในหน่วยกิโลกรัมในบรรทัดต่อมาจนกระทั่งครบจำนวน แล้วให้โปรแกรมคำนวณหาค่า BMI ของแต่ละคนออกมา โดยในส่วนของ output ให้แสดงข้อความว่า ****All information**** ตามตัวอย่าง input/output ต่อไปนี้
---

### **ตัวอย่าง** **input** **output**
```
--input--
Enter number of student:  2

Enter student(1) height(m):  1.68
Enter student(1) weight(kg):  57

Enter student(2) height(m):  1.57
Enter student(2) weight(kg):  48

    
--output--
**All information**
>>>>BMI of student(1) is 20.20 
>>>>BMI of student(2) is 19.47

```

```
--input--
Enter number of student: 0
    
--output--
ERROR
```

```
--input--
Enter number of student:  1
Enter student(1) height(m):  0
Enter student(1) weight(kg):  48

    
--output--
Invalid height or weight.
Please check the accuracy again.
```
---
**หมายเหตุ :**
1. มีการเว้นบรรทัดระหว่าง input  ของแต่ละคน
2. สูตรในการหาค่า BMI  คือ  (weight(kg))/〖height(m)〗^2 
3. Output  ที่แสดงค่า BMI ให้แสดงด้วยทศนิยม 2 ตำแหน่ง
---

