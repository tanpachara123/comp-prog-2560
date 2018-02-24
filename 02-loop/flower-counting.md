# จัดช่อดอกไม้

มีดอกไม้อยู่กองหนึ่ง ซึ่งดอกไม้กองนั้นประกอบด้วยดอกไม้จำนวน 5 ชนิดซึ่งคละกันอยู่ จงเขียนโปรแกรมรับหมายเลขของดอกไม้แต่ละชนิดเพื่อจำแนกชนิดดอกไม้
แสดงข้อความ "Types of flowers: " ก่อนรับค่าหมายเลข โดย

หมายเลข 1 คือ ดอกกุหลาบ

หมายเลข 2 คือ ดอกทิวลิป

หมายเลข 3 คือ ดอกเดซี่

หมายเลข 4 คือ ดอกเยอบีร่า และ

หมายเลข 5 คือ ดอกกล้วยไม้

เมื่อจำแนกชนิดของดอกไม้จนหมดกอง ให้ใส่เลข -1 เพื่อหยุดนับ หลังจากนั้นให้พิมพ์จำนวนของดอกไม้แต่ละชนิด (ข้อความ "The number of " ตามด้วยชื่อดอกไม้) พิมพ์ "The number of flowers: " ตามด้วยจำนวนดอกไม้ทั้งหมด และพิมพ์ "The number of flower bouquets: " ตามด้วยจำนวนช่อดอกไม้
โดยกำหนดให้ช่อหนึ่งมีดอกไม้จำนวน 5 ดอก

หมายเหตุ หากการใส่ตัวเลขผิดพลาด ให้พิมพ์คำว่า “Try again”


---

**ตัวอย่าง** **Input และ Output**

```
Types of flowers (1-5): 1
Types of flowers (1-5): 2
Types of flowers (1-5): 3
Types of flowers (1-5): 4
Types of flowers (1-5): 5
Types of flowers (1-5): -1
The number of Roses: 1
The number of Tulips: 1
The number of Carnations: 1
The number of Daisies: 1
The number of Orchids: 1
The number of flowers: 5
The number of flower bouquets: 1
```

```
Types of flowers (1-5): 1
Types of flowers (1-5): -9
Try again
Types of flowers (1-5): 7
Try again
Types of flowers (1-5): 2
Types of flowers (1-5): -1
The number of Roses: 1
The number of Tulips: 1
The number of Carnations: 0
The number of Daisies: 0
The number of Orchids: 0
The number of flowers: 2
The number of flower bouquets: 0
```
