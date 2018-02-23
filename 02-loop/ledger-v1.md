# รายรับรายจ่าย
ให้นิสิตเขียนโปรแกรมคำนวณรายรับราบจ่ายใน 1 สัปดาห์  จากนั้นสรุปออกมาว่าในวันนั้นมียอดคงเหลือสำหรับวันนั้นเท่าไหร่ และในสัปดาห์นั้นมีรายรับเท่าไร รายจ่ายเท่าไร และยอดคงเหลือเท่าไร โดยให้สร้างทางเลือกว่าจะรับข้อมูลเป็นรายรับหรือรายจ่าย รวมทั้งให้มีคำสั่งจบการทำงานในวันนั้น  
## INPUT
ให้ปริ้นต์คำสั่งต่อไปนี้ จากนั้นรอรับชนิดของรายการโดยใช้เลขหน้ารายการ  

    ---------DAY x---------
    [1]Income  [2]Expend  [0]end this day
    Type : x
จากนั้นให้รับค่าเงินตามรายการนั้น ได้แก่  
    
-     Incoming Amount : x 
-     Expending Amount : x
## OUTPUT
ให้สรุปยอดคงเหลือในแต่ละวันเป็นเลขทศนิยม 2 ตำแหน่ง โดยมีลักษณะดังนี้  

    today balance = x.xx
และเมื่อครบรอบสัปดาห์ ให้สรุปรายรับ รายจ่าย และยอดเงินคงเหลือในสัปดาห์นั้นเป็นเลขที่มีทศนิยม 2 ตำแหน่ง โดยมีลักษณะดังนี้

    -------------------------
    total incomes = x.xx
    total expends = x.xx
    this week balance = x.xx
### HINT
- ยอดเงินคงเหลือในสัปดาห์นั้นอาจมีค่าติดตัวแดง (มีค่าเป็นลบก็ได้)
- ในหนึ่งวันเราอาจทำธุรกรรมได้หลายครั้ง
  
## ตัวอย่างโปรแกรม  
-       ---------DAY 1---------
        [1]Income  [2]Expend  [0]end this day
        Type : 1
        Incoming Amount : 50
        Type : 2
        Expending Amount : 50
        Type : 0
        today balance = 0.00
        ---------DAY 2---------
        [1]Income  [2]Expend  [0]end this day
        Type : 1
        Incoming Amount : 50
        Type : 2
        Expending Amount : 50
        Type : 0
        today balance = 0.00
        ---------DAY 3---------
        [1]Income  [2]Expend  [0]end this day
        Type : 1
        Incoming Amount : 50
        Type : 2
        Expending Amount : 50
        Type : 0
        today balance = 0.00
        ---------DAY 4---------
        [1]Income  [2]Expend  [0]end this day
        Type : 1
        Incoming Amount : 50
        Type : 2
        Expending Amount : 50
        Type : 00
        today balance = 0.00
        ---------DAY 5---------
        [1]Income  [2]Expend  [0]end this day
        Type : 1
        Incoming Amount : 50
        Type : 2
        Expending Amount : 50
        Type : 0
        today balance = 0.00
        ---------DAY 6---------
        [1]Income  [2]Expend  [0]end this day
        Type : 1
        Incoming Amount : 50
        Type : 2
        Expending Amount : 50
        Type : 0
        today balance = 0.00
        ---------DAY 7---------
        [1]Income  [2]Expend  [0]end this day
        Type : 1
        Incoming Amount : 50
        Type : 2
        Expending Amount : 45.50
        Type : 0
        today balance = 4.50
        -------------------------
        total incomes = 350.00
        total expends = 345.50
        this week balance = 4.50
-       ---------DAY 1---------
        [1]Income  [2]Expend  [0]end this day
        Type : 1
        Incoming Amount : 20
        Type : 2
        Expending Amount : 50
        Type : 0
        today balance = -30.00
        ---------DAY 2---------
        [1]Income  [2]Expend  [0]end this day
        Type : 1
        Incoming Amount : 20
        Type : 2
        Expending Amount : 40
        Type : 0
        today balance = -20.00
        ---------DAY 3---------
        [1]Income  [2]Expend  [0]end this day
        Type : 1
        Incoming Amount : 0
        Type : 2
        Expending Amount : 50
        Type : 0
        today balance = -50.00
        ---------DAY 4---------
        [1]Income  [2]Expend  [0]end this day
        Type : 0
        today balance = 0.00
        ---------DAY 5---------
        [1]Income  [2]Expend  [0]end this day
        Type : 0
        today balance = 0.00
        ---------DAY 6---------
        [1]Income  [2]Expend  [0]end this day
        Type : 0
        today balance = 0.00
        ---------DAY 7---------
        [1]Income  [2]Expend  [0]end this day
        Type : 1
        Incoming Amount : 7
        Type : 2
        Expending Amount : 9
        Type : 0
        today balance = -2.00
        -------------------------
        total incomes = 47.00
        total expends = 149.00
        this week balance = -102.00
