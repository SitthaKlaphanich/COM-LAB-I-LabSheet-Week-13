# การใช้งาน Github ร่วมกับ Visual studio code
## แนวทางการทำงานกับ branch

ส่งงาน 65030258 สิทธา กล้าพานิช 

https://github.com/SitthaKlaphanich/github_VSCode.git

1. สร้าง folder ใหม่เพื่อใช้เป็น local repository

![Alt text](./Pictures/Picture-11.png)

[1] คลิกที่ menu

[2] ปิด folder ที่อาจจะเปิดค้างอยู่

[3] เปิด folder ใหม่ (ถ้ายังไม่มี สามารถไปสร้างได้บน file explorer ขณะที่เลือก local fodler)

2. เลือก folder บน harddisk (ถ้ายังไม่มี สามารถสร้างใหม่ได้ตามต้องการ) 

![Alt text](./Pictures/Picture-12.png)

ต้องไม่อยู่ใน folder ที่เป็น local repo อยู่ก่อนแล้ว ซึ่งในกรณีนั้นจะเป็นการสร้าง submodule ซึ่งอยู่นอกเหนือจากขอบเขตของใบงานนนี้

![Alt text](./Pictures/Picture-13.png)

ภาพจากเครื่องคอมพิวเตอร์ 65030258 สิทธา กล้าพานิช 

![Alt text](./Pictures/Picture-60.png)

[1] กดปุ่มสร้างไฟล์ใหม่

[2] ตั้งชื่อเป็น README.md

3. เพิ่มเติมเนื้อหาใน README.md และตรวจสอบโดยการ preview

![Alt text](./Pictures/Picture-14.png)


4. ทำให้ folder ที่เก็บ readme.md เป็น local repository  

![Alt text](./Pictures/Picture-15.png)
 
[1] คลิกปุ่ม git

[2] Initialize Repository


5. ใส่ข้อความ commit และกด commit

![Alt text](./Pictures/Picture-16.png)

6. publish branch ขึ้นบน remote 

![Alt text](./Pictures/Picture-17.png)

7. เลือกชนิดของ repository

![Alt text](./Pictures/Picture-18.png)

8. เมื่อ publish เสร็จ ให้ตามไปดูบน github.com

![Alt text](./Pictures/Picture-19.png)


9. ตัวอย่าง repository ที่สร้างขึ้นจากฝั่ง Local เมื่อมองจากฝั่ง github derver

![Alt text](./Pictures/Picture-20.png)


10. ค้นหา extension `git graph` เพื่อติดตั้งไว้ดูสถานะของ branch  

![Alt text](./Pictures/Picture-21.png)

11. install extension `git graph`

![Alt text](./Pictures/Picture-22.png)


12. ตรวจสอบ branch ที่มีบน repository 

![Alt text](Pictures/Picture-23.png)

13. เปิด terminal เพื่อทดลองด้วยคำสั่ง  git

![Alt text](./Pictures/Picture-24.png)

14. ตรวจสอบว่า git command ทำงานได้ โดยสั่ง `git status` ดูผลที่เกิดขึ้น ควรจะเป็นตามภาพต่อไปนี้

![Alt text](./Pictures/Picture-25.png)


15. สร้าง branch ใหม่

![Alt text](./Pictures/Picture-26.png)

ชื่อ branch คือ `DEV-1` 
(ใช้คำสั่ง `git branch DEV-1`)

16. เปลี่ยนไปยัง branch `DEV-1`

![Alt text](./Pictures/Picture-27.png)


[1] ใช้คำสั่ง `git checkout DEV-1`

17. เพิ่มเนื้อหาใน readme.md


![Alt text](./Pictures/Picture-28.png)


18. เพิ่มไฟล์ไปยัง staging area (เตรียม commit)


![Alt text](./Pictures/Picture-29.png)

ภาพจากเครื่องคอมพิวเตอร์ 65030258 สิทธา กล้าพานิช ก่อนกด +

![Alt text](./Pictures/Picture-61.png)

ภาพจากเครื่องคอมพิวเตอร์ 65030258 สิทธา กล้าพานิช หลังกด +

![Alt text](./Pictures/Picture-62.png)

 ![Alt text](./Pictures/Picture-30.png)

19. commit change

![Alt text](./Pictures/Picture-31.png)

ภาพจากเครื่องคอมพิวเตอร์ 65030258 สิทธา กล้าพานิช

![Alt text](./Pictures/Picture-63.png)

20. publish branch ขึ้นไปยัง server 

![Alt text](./Pictures/Picture-32.png)

git extension จะถามว่าต้องการทำ pull request หรือไม่ ยังไม่ต้องทำในตอนนี้

![Alt text](./Pictures/Picture-33.png)

21. ตรวจสอบการเปลี่ยนแปลงบน web

![Alt text](./Pictures/Picture-34.png)

22. ตรวจสอบเนื้อหาว่าตรงตามที่ edit ใน VSCODE หรือไม่

![Alt text](./Pictures/Picture-35.png)

23. กลับไปที่ VSCODE สร้างไฟล์ hello.md โดยใช้คำสั่ง echo


![Alt text](./Pictures/Picture-36.png)

24. เพิ่มไฟล์ hello.md เข้าไปใน stagine area  (`git add <files>`)

![Alt text](./Pictures/Picture-37.png)


25.  commit hello.md เข้าไปใน local repository  (`git commit -m"..."`)

![Alt text](./Pictures/Picture-38.png)

26. sync กับ remote repository ยีห้
 
![Alt text](./Pictures/Picture-39.png)







