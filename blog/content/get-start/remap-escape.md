---
title: "Remap Escape"
date: 2022-04-27T01:10:48+07:00
weight: 2
---

## Esc มันอยู่ไกล

ในการใช้ VIM keybinding เราจะต้องมีการกดปุ่ม escape บ่อยมากๆ

ปัญหาคือ ปุ่ม escape บน keyboard อยู่ไกลทำให้ต้องเอื้อมไปกดพอสมควร

หรือที่แย่กว่านั้นถ้าใครใช้ mac รุ่นที่ไม่มีปุ่ม Esc แยกจะทำให้เราติดขัดอยู่มากเลยทีเดียว

ดังนั้นเลยโดยทั่วไป เราจะแนะนำให้ remap ปุ่ม escape ไปที่ปุ่ม cap-lock

## Remap Caplock to Escape

ในหลายๆ OS ก็มีวิธีแตกต่างกันไป ขอแนะนำสำหรับ Mac กับ Windows

### Remap บน MAC

การ remap ที่ mac นี่ทำได้ง่ายโดยการไปที่

`System Preferences > Keyboard > Modifier Keys > map caps lock to escape` [ดูภาพจากที่นี่](https://vim.fandom.com/wiki/Map_caps_lock_to_escape_in_macOS#:~:text=To%20map%20the%20caps%20lock,as%20well%20as%20other%20actions.)

### Remap บน Windows

การ remap บน windows จะไม่ได้มีวิธี setting แบบบน Mac ตรงๆ

ผมวิธีที่ผมแนะนำคือ ลง [Microsoft PowerToys](https://docs.microsoft.com/en-us/windows/powertoys/)
แล้วใช้ feature [Keyboard manager](https://docs.microsoft.com/en-us/windows/powertoys/keyboard-manager) 
ของ PowerToys ในการจัดการเรื่อง remap
