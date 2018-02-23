นักขายมือใหม่
---

  เนื่องจากนิสิตเป็นคนรุ่นใหม่ไฟแรง มีความต้องการที่จะหารายได้ระหว่างเรียน ด้วยการเปิดธุรกิจขายของออนไลน์ ซึ่งช่วงที่นิสิตกำลังเปิดร้านอยู่นั้นตรงกับช่วงเทศกาล “ตรุษจีน” นิสิตเลยมีความคิดที่จะจัดโปรโมชั่นลดราคาสินค้า เพื่อเฉลิมฉลองเทศกาลตรุษจีน กับการเปิดร้านใหม่ และจากการที่นิสิตเป็นโปรแกรมเมอร์ที่ดี ทำให้นิสิตต้องการจะเขียนโปรแกรม คำนวนราคาสินค้า จากส่วนลด(เปอร์เซนต์)ที่นิสิตต้องการจะลดราคา โดยโปรแกรมจะรับข้อมูลชุดละ 10 ข้อมูล

**ให้นิสิตเขียนโปรแกรม** รับจำนวนจริงเป็นราคาสินค้า และส่วนลดที่นิสิตต้องการจะลดสำหรับสินค้าชิ้นนั้น(เปอร์เซนต์) คั่นด้วยช่องว่าง ให้ครบ 10 ชุดข้อมูล จากนั้นให้แสดงผลเป็นราคาสินค้าที่ลดราคาแล้วทีละบรรทัด(ทศนิยม 2 ตำแหน่ง)

**หมายเหตุ** ถ้าราคาสินค้า และส่วนลดมีค่าน้อยกว่า 0 และส่วนลดเกิน 100% ให้แสดง “Invalid Input.”


---

### **ตัวอย่าง** **Input / Output**

```
Enter product price and discount.
Product (1 of 10): 100 10
Product (2 of 10): 200 10
Product (3 of 10): 500 -30
Invalid Input.
Product (3 of 10): 500 30
Product (4 of 10): 450 20
Product (5 of 10): 1200 120
Invalid Input.
Product (5 of 10): 1200 20
Product (6 of 10): 5900 -30
Invalid Input.
Product (6 of 10): 5900 30
Product (7 of 10): -6900 80
Invalid Input.
Product (7 of 10): 6900 80
Product (8 of 10): 4000 20
Product (9 of 10): 5000 50
Product (10 of 10): 5900.96 30

Price after discount.
Price of product 1 is 90.00 baht.
Price of product 2 is 180.00 baht.
Price of product 3 is 350.00 baht.
Price of product 4 is 360.00 baht.
Price of product 5 is 960.00 baht.
Price of product 6 is 4130.00 baht.
Price of product 7 is 1380.00 baht.
Price of product 8 is 3200.00 baht.
Price of product 9 is 2500.00 baht.
Price of product 10 is 4130.67 baht.

```
