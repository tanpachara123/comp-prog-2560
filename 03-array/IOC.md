#  ค่า IOC
#### เขียนโปรแกรมเพื่อหาค่าความเที่ยงตรงของแบบสอบถาม หรือค่าสอดคล้องระหว่างข้อคำถามกับวัตถุประสงค์( IOC: Index of item objective congruence ) และหาผลการประเมินจากค่า IOC 
ซึ่งจะให้ผู้เชี่ยวชาญตั้งแต่ 3 คนขึ้นไปตรวจสอบ โดยเกณฑ์ในการตรวจพิจารณาข้อคำถาม  มีดังนี้ 


 > * ให้คะแนน  +1 คือ คำถามวัดได้**ตรงตาม**วัตถุประสงค์
 > * ให้คะแนน  0  คือ **ไม่แน่ใจ**ว่าคำถามวัดได้ตรงตามวัตถุประสงค์
> * ให้คะแนน -1 คือ คำถาม**ไม่ได้วัดตรงตาม**วัตถุประสงค์
จากนั้นนำผลคะแนนที่ได้จากผู้เชี่ยวชาญมาคำนวณหาค่า IOC ตามสูตร

**สูตร**        
```
IOC =  ผลรวมของคะแนน      
      _______________
       จำนวนผู้เชี่ยวชาญ 
```

 **เกณฑ์ :**  
 1.  คำถามที่มีค่า IOC ตั้งแต่ 0.50 - 1.00 มีค่าความเที่ยงตรง ใช้ได้ (Usable)
2.  คำถามที่มีค่า IOC ต่ำกว่า 0.50 ต้องปรับปรุงแก้ไข (improve)

### ข้อมูลเข้า :
1. ให้ผู้ใช้ระบุจำนวนของคำถาม
2. ให้ผู้ใช้ระบุจำนวนผู้เชี่ยวชาญ
3. ให้ผู้ใช้ระบุจำนวนคะแนนคำถามของผู้เชี่ยวชาญแต่ละคน 
4. ให้ระบุจํานวนคูปองอาหารเช้าที่ต้องการเพิ่ม

### ข้อมูลออก :
> * ให้แสดงค่าของ IOC (ทศนิยม 2 ตำแหน่ง)ในแต่ละคำถามพร้อมทั้งบอกว่าแต่ละคำถามนั้นมีเกณฑ์ของค่า IOC ใช้ได้ (Usable) หรือปรับปรุง (improve)
พัก

**แหล่งที่มา  :**  http://www.mcu.ac.th/site/articlecontent_desc.php?article_id=656&articlegroup_id=146 

### ตัวอย่าง Input\Output
```
Enter amount of question:  2
Enter amount of virtuoso:  3
Question #1
Enter point of virtuoso #1:  1
Enter point of virtuoso #2:  1
Enter point of virtuoso #3:  1
Question #2
Enter point of virtuoso #1:  1
Enter point of virtuoso #2:  -1
Enter point of virtuoso #3:  0
Question #1 : IOC is 1.00 and result of evaluation is usable.
Question #2 : IOC is 0.00 and result of evaluation is improve.
```
```
Enter amount of question:  3
Enter amount of virtuoso:  3
Question #1
Enter point of virtuoso #1:  -1
Enter point of virtuoso #2:  1
Enter point of virtuoso #3:  0
Question #2
Enter point of virtuoso #1:  -1
Enter point of virtuoso #2:  -1
Enter point of virtuoso #3:  1
Question #3
Enter point of virtuoso #1:  1
Enter point of virtuoso #2:  1
Enter point of virtuoso #3:  1
Question #1 : IOC is 0.00 and result of evaluation is improve.
Question #2 : IOC is -0.33 and result of evaluation is improve.
Question #3 : IOC is 1.00 and result of evaluation is usable.
```


