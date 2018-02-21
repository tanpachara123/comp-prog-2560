# Borrow or Refund?

          จงเขียนโปรแกรมที่ให้ลูกค้ากู้เงินและคืนเงิน  โดยที่สามารถกู้ได้แค่คนละ 100,000 บาท เท่านั้น โปรแกรมจะสามารถรับลูกค้าได้หลายคน
        ในครั้งเดียว และสามารถกู้เงินหรือคืนเงินหลายครั้งได้ แล้วโปรแกรมจะแสดงผลว่าวันนี้ลูกค้าคนไหนได้กู้เงินหรือคืนเงินเท่าไหร่บ้าง


**หมายเหตุ 1** : ถ้าใส่จำนวนเงินเกิน 100,000 บาท จะขึ้นข้อความว่า **Sorry, just only 100,000 baht/person.** และโปรแกรมจะบังคับให้ใส่จำนวนใหม่จนกว่าจะถูก 

**หมายเหตุ 2** : 
* ถ้าผู้ใช้ต้องการที่จะหยุดการรับเงินในครั้งนั้น ให้ใส่ -1 ในข้อความที่ถามจำนวนเงิน
* ถ้าผู้ใช้ต้องการจบการทำงานของโปรแกรม ให้ใส่ -1 ในข้อความที่ให้รับลูกค้าคนต่อไป

**หมายเหตุ 3** : ถ้าลูกค้าคนใด **คืนเงิน** ครบจำนวนแล้ว ให้แสดงข้อความว่า **You have already refunded. Thank you for using our service!!** แล้วจึงรับลูกค้าคนถัดไป


**ตัวอย่าง Input/Output**

1. **Input**
```
Would you like a loan or a refund for people #1? (1 to loan, 2 to refund and -1 to exit) : 1
How much? (-1 to stop) : 200000
Sorry, just only 100,000 baht/person.
How much? (-1 to stop) : 1500
How much? (-1 to stop) : 200
How much? (-1 to stop) : -1
Would you like a loan or a refund for people #2? (1 to loan, 2 to refund and -1 to exit) : 2
How much do you borrow me before? (-1 to stop): 3500
How much do you refund in this time? (-1 to stop) : 2000
How much do you refund in this time? (-1 to stop) : 1500

You have already refunded. Thank you for using our service!!

Would you like a loan or a refund for people #3? (1 to loan, 2 to refund and -1 to exit) : -1

```
**Output**
```
For people #1
Borrow : 1700.00 Baht.
Refund : 0.00 Baht.

For people #2
Borrow : 0.00 Baht.
Refund : 3500.00 Baht.

```

2. **Input**
```
Would you like a loan or a refund for people #1? (1 to loan, 2 to refund and -1 to exit) : 2
How much do you borrow me before? (-1 to stop): 1570
How much do you refund in this time? (-1 to stop) : 500
How much do you refund in this time? (-1 to stop) : -1
Would you like a loan or a refund for people #2? (1 to loan, 2 to refund and -1 to exit) : -1

```
**Output**
```
For people #1
Borrow : 0.00 Baht
Refund : 500.00 Baht
```
