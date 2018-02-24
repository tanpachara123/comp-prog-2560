## โปรแกรมแลก Coin!!  
เขียนโปรแกรมโดยรับค่า 5 ค่า โดย  
1. บรรทัดที่    1   รับจำนวนเงินที่เราต้องการแลก Coin  
2. บรรทัดที่    2    รับค่าของ Coin ชนิดแรก โดยแสดงข้อความ   “Input Coin 1 :” ก่อนรับค่า  
3. บรรทัดที่    3    รับค่าของ Coin ชนิดที่สองโดยแสดงข้อความ  “Input Coin 2 :” ก่อนรับค่า  
4. บรรทัดที่    4    รับค่าของ Coin ชนิดที่สามโดยแสดงข้อความ  “Input Coin 3 :” ก่อนรับค่า  
5. บรรทัดที่    5     รับจำนวนความเป็นไปได้ที่ต้องการให้แสดงผล   
   * ความเป็นไปได้ในการแลกเหรียญมีมากจึงให้กำหนดจำนวนที่ต้องการแสดง  

### เพิ่มเติม  
ค่าของ Coin ต้องไม่น้อยกว่า 1 และไม่มากกว่า 10 ถ้าเกินจะทำการ ใส่เหรียญใหม่  
โดยเมื่อ Coin ค่าของ Coin น้อยกว่า 1 หรือมากกว่า 10 จะแสดงข้อความ “Invalid Coin”  
และจะมีข้อความ “Input again :” เพื่อรอรับค่า Coin อีกครั้ง  
แล้วจึงแสดงผลจำนวนของ Coin  ทั้ง 3 ชนิด ที่รวมกันแล้วได้เท่ากับจำนวนเงินที่เรามี และ  ต้องมี Coin ทั้ง 3 ชนิด  
โดยแสดงคำว่า Count of Coin 1,2,3 ก่อนแสดงค่า และแสดงจำนวนความเป็นไปได้ตามที่ผู้ใช้ต้องการให้แสดง   
ผลที่ได้ จะเป็นไปตามสูตร    
`Coin1xCount of coin 1+Coin2xCount of coin2+Coin3xcount of coin3 = จำนวนเงินที่ต้องการแลก`

## Test case  
ตัวอย่าง input/output 1  
```
50  
Input Coin 1: 1    
Input Coin 2: 2    
Input Coin 3: 5  
1  
Count coin 1:   1 Count coin 2:    2 Count coin 3:   9
```
ตัวอย่าง input/output 2
```
50  
Input Coin 1: 1    
Input Coin 2: 2    
Input Coin 3: 5  
3  
Count coin 1:   1 Count coin 2:    2 Count coin 3:   9   
Count coin 1:   1 Count coin 2:    7 Count coin 3:   7   
Count coin 1:   1 Count coin 2:    12 Count coin 3:   5   
```
ตัวอย่าง input/output 3  
```
50  
Input Coin 1: 5    
Input Coin 2: 1    
Input Coin 3: 2  
4  
Count coin 1:   1 Count coin 2:    1 Count coin 3:   22   
Count coin 1:   1 Count coin 2:    3 Count coin 3:   21   
Count coin 1:   1 Count coin 2:    5 Count coin 3:   20  
Count coin 1:   1 Count coin 2:    7 Count coin 3:   19
```
