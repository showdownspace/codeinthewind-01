---
layout: challenge
title: 'Qualifiers #1: Chat'
---

## Objectives

- สร้าง Chat dialog ที่มีเนื้อหาดังนี้
  - _ทำไรอยู่_ (ซ้าย)
  - _ไม่ได้ทำไร นั่งเปื่อยๆอยู่_ (ขวา)
  - _นอนดึกจัง_ (ขวา)
  - _ว่าจะทำงาน แต่ตอนนี้ไม่มีอารมณ์แล้ว_ (ซ้าย)
  - _ติสท์จัง_ (ขวา)
  - พื้นหลังของข้อความของทั้งสองฝั่งต้องมีสีที่ต่างกัน
  - และมี Timestamp บอกเวลาเป็นตัวสีเทาด้านบน _a few seconds ago_
- มี Avatar ของฝั่งคู่สนทนา (ด้านซ้าย) เป็นวงกลม ไม่ต้องใส่ภาพ
- มี Read Indicator ว่าคู่สนทนาอ่านข้อความของเราแล้ว อยู่ทางด้านขวาของข้อความสุดท้าย
  - เหมือนสีกับ Avatar ของฝั่งคู่สนทนา แต่ขนาดเล็กกว่า
- มีช่องไฟในแนวตั้งระหว่างข้อความ โดยหากเป็นข้อความของคนเดียวกันจะอยู่ชิดกว่าข้อความจากอีกฝ่าย
- ข้อความจะอยู่ใน Bubble ที่มีขอบมน ยกเว้นมุมที่ติดกันหากข้อความเป็นของคนเดียวกัน (ข้อความที่ 2 และ 3 มุมที่ติดกันจะต้องไม่ใช้ขอบมน)

### English

- Create a chat dialog with the following content:
  - _ทำไรอยู่_ (left)
  - _ไม่ได้ทำไร นั่งเปื่อยๆอยู่_ (right)
  - _นอนดึกจัง_ (right)
  - _ว่าจะทำงาน แต่ตอนนี้ไม่มีอารมณ์แล้ว_ (left)
  - _ติสท์จัง_ (right)
  - Text backgrounds on both sides must be of different colors.
  - At the top, add time indicator in gray: _a few seconds ago_
- Add a circle avatar on the left of partner’s message. No image needed.
- Add a read indicator to the right of your last message.
  - Same as the avatar on the left, but smaller.
- There is a vertical gap between each bubble. If it is the same person's message, it will be closer than the message from different person.
- Make bubbles have rounded corners, unless the adjacent corners between consecutive messages from the same person (the 2nd and 3rd bubbles have adjacent corners).