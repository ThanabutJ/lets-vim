---
title: "1.2 Mnemonics"
date: 2022-04-24T20:22:23+07:00
weight: 2
---

จากบทที่แล้ว ได้แนะนำให้รู้จัก `i` `a` ไปเรียบร้อยแล้ว 

| Key | mnemonics | Action |
| --- | --- | --- |
| `i` | `i`nsert | enter to insert mode from the 'LEFT' of cursor |
| `a` | `a`ppend | enter to insert mode from the 'RIGHT' of cursor |

เราจะสังเกตุเห็นได้ว่า ใน keymapping table มี column mnemonics อยู่ 
บทนี้เราจะแนะนำให้รู้จักกับ mnemonics ว่าคืออะไร

> Mnemonics (n) คำหรือวลีที่ช่วยในการจำ

Keymapping ต่างๆใน VIM ไม่ได้ถูกเลือกมาแบบสุ่ม 

แต่ส่วนใหญ่จะมีความพยายามให้ action กับ key บน keyboard มีความเชื่อมโยงกัน

จากบทที่แล้ว เราก็จะมี
| action | key |
| --- | --- |
| insert | `i` |
| append | `a` |

การที่ VIM ทำ keymapping เป็นลักษณะนี้ทำให้เราเวลาใช้งาน VIM เราก็สามารถคิดถึงเฉพาะ
action ที่เราอยากทำ เช่น อยาก insert ก็ i อยาก append ก็ a

> Pattern แบบนี้ ก็ไม่ได้มีเฉพาะแค่ใน VIM
>
> short-cut ที่เราใช้กันตลอด Ctrl+c ตัว c นี้ก็มาจาก copy เหมือนกัน

### ตัวอย่างอื่นๆ

keymapping ด้านล่างนี้จะเป็น spoiler ซักหน่อย แต่ว่าเพื่อให้เห็นภาพว่า VIM มีการนำ mnemonics
มาใช้ด้วย parttern ที่แบบนี้ มากกว่า `a` `i` ที่เราได้รู้จักกัน

| action | key |
| --- | --- |
| delete | `d` |
| change | `c` |
| undo | `u` |
| redo | `ctrl+r` |

นอกจาก action ต่างๆก็ยังไม่ movement เช่นกัน

ตัวอย่าง cursor movement keymapping
> ลองอ่าน column cursr movement นำหน้าด้วยคำว่า move cursor to ...
>
> เช่น move cursor to word ถัดไป

| cursor movement | key |
| --- | --- | 
| word ถัดไป | `w` |
| before this word | `b` |
| end of this word | `e` |
