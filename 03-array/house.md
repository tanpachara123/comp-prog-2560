# จัดหนังสือบนชั้น

จงเขียนโปรแกรมจัดเรียงความสูงของบ้านแต่ละหลังในหน่วยเมตร โดยแสดงข้อความ “Enter the height of houses: “ แล้วรับข้อมูลบ้านจำนวน 5 หลังในบรรทัดต่อมาเป็นจำนวนเต็ม แล้วนำมาเรียง โดยเรียงจากบ้านที่มีความสูง น้อยที่สุด ไปจนถึงบ้านที่มีความสูงมากที่สุด แล้วแสดงข้อมูลออกมาเป็นข้อความ “The height of houses.” ตามด้วยความสูงของบ้านก่อนเรียงลำดับในบรรทัดต่อมา พิมพ์ข้อความ “The height of houses after arranging.” และความสูงของบ้านหลังเรียงลำดับเสร็จแล้ว พิมพ์ข้อความ ‘The height of the shortest house: ’’ตามด้วยความสูงบ้านที่มีความสูง น้อยที่สุด และพิมพ์ข้อความ “The height of the tallest house:” ตามด้วยความสงูของบ้านที่มากที่สุด 
หมายเหต ุหากตวัเลขที่ได้รับมามีค่าติดลบ ให้พิมพ์ค าวา่ “Error”

---

**ตัวอย่าง** **Input และ Output**

```
Enter the height of houses: 
1 
6 
2 
8 
4 
The height of houses. 
1 6 2 8 4 
The height of houses after arranging. 
1 2 4 6 8 The height of the shortest house: 1 
The height of the tallest house: 8
```

```
Enter the height of houses: 
-1 
Error 
5 
7 
9 
6 
4 
The height of houses. 
5 7 9 6 4 
The height of houses after arranging. 
4 5 6 7 9 
The height of the shortest house: 4 
The height of the tallest house: 9 
```