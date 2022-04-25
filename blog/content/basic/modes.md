---
title: "1.1 VIM Basic Modes"
date: 2022-04-24T19:26:27+07:00
weight: 1
---

## VIM modes

VIM mode คือ เป็นสิ่งที่เราเปลี่ยนไปมา เพื่อจะได้ทำสิ่งที่เราต้องการได้

> เราสามารถดู mode ปัจุบันของเราได้ที่มุมซ้ายล่างของ EDITOR ของเรา
> ![vim mode indicator on editor](TOADDIMAGE)

VIM มี mode หลากหลาย mode แต่สำหรับในบน basic จะเริ่มจาก 2 mode แรกก่อนก็คือ

- Normal Mode
- Insert Mode

## 1. Normal Mode

Normal Mode นี้เป็น mode ที่อนุญาตให้เรา บังคับ cursor และ ทำ Action ต่างๆ 
(เราจะพูดถึง action ต่างๆในบทต่อๆไป)

ตาม ชื่อของ Normal Mode เลยครับ mode นี้คือ mode ที่เราควรจะอยู่ตลอดเวลา 

เมื่อเราใช้งาน VIM จริงๆจังๆแล้ว
Flow การทำงานของการใช้ VIM ก็จะกลาย loop ประมาณนี้

- อยู่ Normal mode
- เลื่อน cursor ไปทำแหน่งที่ต้องการ
- ทำ action ที่ต้องการ ใน Mode อื่น
- กลับสู่ Normal Mode
- Repeat

ในบทต่อๆไปจะแนะนำความสมารถของ Normal mode ว่าสามารถทำอะไรได้บ้าง ส่วนตอนนี้รู้จัก mode
นี้ประมาณนี้ก่อนครับ

## 2. Insert Mode

คือ Mode ที่เราเปิดใช้เพื่อทำการพิมพ์

แล้วเราจะเปลี่ยนเป็น Insert Mode ได้ยังไงหล่ะ

เราสามารถเข้า mode นี้ด้วยกด key 2 key จาก Normal Mode

| Key | mnemonics | Action |
| --- | --- | --- |
| `i` | `i`nsert | enter to insert mode from the 'LEFT' of cursor |
| `a` | `a`ppend | enter to insert mode from the 'RIGHT' of cursor |

หลังจากที่เราเปลี่ยนเป็น insert mode แล้วก็จะสามารถพิมพิ์สิ่งที่เราต้องการได้

แต่ทำไมต้องมี key ถึง 2 key แล้วอะไรคือ LEFT/RIGHT of cursor หล่ะ คำตอบคือ VIM
cursor นั้นต่างจาก cursor ปกตินั่นเองครับ

### VIM Cursor

ถ้าเราสังเกต cursor ของเราใน ขณะที่อยู่ใน Normal mode ของ VIM จะไม่เหมือน cursor
ปกติทั่วไป

Normal Cursor
![normal cursor](TOADDIMAGE)

VIM Cursor
![vim curosr](TOADDIMAGE)

เราจะเห็นได้ว่าลักษณะของ cursor นั้นเป็นสี่เหลี่ยมอยู่ด้านหลังของ text charactor
ของปัจจุบันของเรา

ดั้งนั้นเวลาที่เราเปลี่ยน Normal mode > Insert Mode เราก็จะสามารถเลือกได้ว่าจะให้
- `i`nsert ตัวหนังสือที่ด้านหน้า cursor ของเรา
- หรือ `a`ppend เข้าไปที่ด้านหลังของ cursor ของเรา

#### เคสตัวอย่าง

สมมติว่าเรามี array ชื่อว่า user อย่างด้านล่าง แต่ที่จริงแล้วเราควรตั้งชื่อว่า users

```javascript
// ชื่อ array ที่อยากจะแก้
const user = ['userA','userB','userC']

// อย่างในเคสนี้เราสามารถ ใช้ normal mode หรือ mouse เราก็ได้
// ขยับ cursor มาที่ตัว r แล้วพิมพ์ s ลงไปต่อท้ายได้เลย
const users = ['userA','userB','userC']
```
---

### กลับสู่ Normal Mode

วิธีการกลับสู่ Normal Mode จาก mode อื่นๆ เพียงแค่กดปุ่ม `ESC`
