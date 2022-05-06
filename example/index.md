---
layout: challenge
title: Example Challenge
---

## Objectives

- สร้างปุ่มกดรหัสผ่าน เป็นกริด มี 4 แถว แต่ละแถวมี 3 คอลัมน์
  - ประกอบไปด้วยปุ่มตามนี้: ((1, 2, 3), (4, 5, 6), (7, 8, 9), (0, delete))
  - ปุ่มตัวเลขเป็นรูปวงกลม มีขอบสีเทา ส่วนตัวเลขให้จัดให้อยู่ตรงกลางข้างในวงกลม โดยแต่ละปุ่มควรเว้นระยะห่างระหว่างกัน
  - ปุ่ม delete ไม่มีขอบ ใช้รูปจาก URL นี้ได้เลย `https://i.showdown.space/e01/delete-icon.svg`
- สร้างวงกลม 6 วงเล็กๆ เรียงกัน เพื่อแสดงสถานะการใส่รหัสผ่าน PIN
  - ให้วงกลม 2 วงแรกเป็นสีทึบ
- ใส่ข้อความ “กรุณาใส่รหัสผ่าน” ตรงด้านบน
- ใส่ข้อความ “ลืมรหัสผ่าน” ตรงข้างล่าง
  - เนื่องจากเป็นลิงค์ สีควรจะแตกต่างจากสีข้อความทั่วไป และมีขีดเส้นใต้
- ใส่ปุ่มปิดเป็นรูปกากบาท ตรงมุมบนขวาของหน้าจอ
  - ไม่มีรูปให้ ให้วาดเองด้วย HTML
  - เส้นของกากบาทควรหนาแค่ 1px เท่านั้น

### English

- Create a 4x3 grid of buttons input the PIN code.
    - It consists of the following buttons: ((1, 2, 3), (4, 5, 6), (7, 8, 9), (0, delete)).
    - The number keys are circle-shaped, with a gray border, and the numbers are centered inside the circle. Each button should have some space between each other.
    - The delete button is borderless. Use the image from this URL https://i.showdown.space/e01/delete-icon.svg
- Create 6 small circles arranged in a row to indicate the PIN input status.
    - Make the first 2 circles filled.
- Add “Please enter your password” text at the top.
- Add “Forgot your password” link below.
    - Its color should be different from normal text color and it should be underlined.
- Put the close button in the shape of a cross. in the upper-right corner of the screen.
    - No image provided, draw your own in HTML.
    - The line of the cross should only be 1px thick.