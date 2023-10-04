# Labsheet 2 ทำงานกับ branch บน Visual stidio code

## คำแนะนำ

การทดลองนี้ จะสร้าง branch เพื่อพัฒนาหลักสูตรในส่วนของแผนการเรียนรู้ของนักศึกษาในหลักสูตรครุศาสตร์วิศวกรรม ซึ่งมี 3 แขนง

ในระหว่างการพัฒนา จะมีการแยกแขนง และทำ commit ครั้งละ 1 ภาคเรียน 

เมื่อพัฒนาเสร็จแล้ว จะนำมา merge รวมกันเพื่อนำข้อมูลไปใช้ในรูปแบบต่าง ๆ 

โดยข้อมูลแผนการศึกษาจะดูได้จากเล่มหลักสูตรในเว็บสำนักทะเบียนฯ สจล. หรือดูได้จากที่นี่

https://github.com/Computer-Lab-I-2566/Eng-EDU_Curriculum_2562/blob/main/Part_3.md

## การทดลอง


1. สร้าง folder ทำงานใหม่ แล้ว initial git ใน folder นั้น


![Alt text](./Pictures/Picture-40.png)

2. เปิด terminal เพื่อใช้งาน github command

![Alt text](./Pictures/Picture-41.png)

3. ทำคำสั่งที่ปรากฏในรูปต่อไปนี้ เพื่อสร้างไฟล์ที่มีเนื้อหาง่ายๆ  

![Alt text](./Pictures/Picture-42.png)

4. สร้าง branch แรก และย้ายไปทำงานกับ branch นั้น (Telecommunication)

![Alt text](./Pictures/Picture-43.png)

4. สร้างไฟล์ Telecommunication.md โดยคำสั่ง `echo`

![Alt text](./Pictures/Picture-44.png)

5. เพิ่มเนื้อหาแผนการเรียนรู้ในไฟล์

![Alt text](./Pictures/Picture-45.png)


5. ตรวจสอบสถานะ เพิ่มไฟล์เข้า staged changes (`git add`)

![Alt text](./Pictures/Picture-46.png)

6. commit change (`git commit`)

#### ในการ commit ให้ใช้รูปแบบ <ชื่อแขนง>_Year<x>_Semester<y> เช่น computer_year1_semester1

![Alt text](./Pictures/Picture-47.png)


7. เพิ่มเนื้อหาของภาคเรียนที่ 2

![Alt text](./Pictures/Picture-48.png)

8. add, commit เนื้อหา

![Alt text](./Pictures/Picture-49.png)

9. แสดง git graph

![Alt text](./Pictures/Picture-50.png)

10. สร้าง branch สำหรับแขนงคอมพิวเตอร์และเพิ่มไฟล์พร้อมเนื้อหา

![Alt text](./Pictures/Picture-51.png)


   - คำสั่ง  `git branch -v` ใช้เรียกดู branch ทั้งหมดใน repository

   - คำสั่ง  `git checkout master` ใช้เปลี่ยน branch ไปอยู่ที่ master 

   - คำสั่ง  `git branch Computer` ใช้สร้าง branch ชื่อ  Computer

   - คำสั่ง  `git checkout Computer` ใช้เปลี่ยน branch จาก master ไปอยู่ที่ Computer 

   - คำสั่ง  `echo "# Computer" >> Computer.md`   ใช้สร้างไฟล์ Computer.md โดยมีเนื้อหาเริ่มต้นเป็นคำว่า  Computer ขนาด Heading 1


11. เพิ่มเนื้อหาแผนการเรียนรู้ของชั้นปีที่ 1 ภาคเรียนที่ 1 แขนงคอมพิวเตอร์   บันทึกไฟล์,  add และ commit

![Alt text](./Pictures/Picture-52.png)

12. ทำลักษณะเดียวกันกับแขนงอิเล็กทรอนิกส์

![Alt text](./Pictures/Picture-53.png)

13. ดู git graph สังเกตการเปลี่ยนแปลงในแต่ละขั้นของการ add, commit

![Alt text](./Pictures/Picture-54.png)

14. ตรวจสอบการ commit, branch โดยคำสั่ง `git log --oneline`

![Alt text](./Pictures/Picture-55.png)


14. ย้ายไปที่ branch `master`

![Alt text](./Pictures/Picture-56.png)

15. merge แขนงคอมพิวเตอร์เข้ามา

![Alt text](./Pictures/Picture-57.png)

16. merge แขนงอื่นๆ เข้ามา

![Alt text](./Pictures/Picture-58.png)


17. ตรวจสอบโดย  git log --oneline

![Alt text](Pictures/Picture-59.png)


## คำสั่ง

- เพิ่มข้อมูลแผนการศึกษาให้ครบถ้วนและตรงตามแขนงวิชา

- capture ภาพ git gpraph แนบมาในรายงานการทดลองด้วย


## จบการทดลอง
