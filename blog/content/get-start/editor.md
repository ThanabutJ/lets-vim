---
title: "Editor/IDE"
date: 2022-04-27T00:08:42+07:00
weight: 1
---

## VIM มีอยู่ทุกที่

ในปัจจุบัน Code Editor ส่วนใหญ่นั้นมีการ support VIM keybinding ในรูปแบบ extension, 
package, หรือ native support แล้ว

ผมมั่นใจว่าเพื่อนน่าจะสามารถลง extension บน editor โปรดของเพื่อนๆกันเป็นปกติอยู่แล้วนะครับ
ขออนุญาตเป็นแนะนำในรูปแบบขี้เป้าแทนการลงลายละเอียดนะครับ

## ชี้เป้า support VIM keybinding ของแต่ละ editor

- VS code :: [Vim extension](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim) 
- IDEs ของตระกูล JetBrains :: [IdeaVim](https://plugins.jetbrains.com/plugin/164-ideavim)
  - เช่น IntelliJ, PyCharm, Goland, Android Studio
- Atom :: [vim-mode package](https://atom.io/packages/vim-mode)
- Sublime :: [vintage](https://www.sublimetext.com/docs/vintage.html)
- xcode (สำหรับ xcode ไม่มีโอกาสได้ทดสอบว่า work ไหมนะครับ)
  - native support on Beta xcode 13
  - [Xvim](https://www.twilio.com/blog/2017/06/adding-vim-keybindings-to-xcode-with-xvim.html)

หรือแม้กระทั่ง online editor อย่างเช่น [codepen](https://codepen.io/) หรือ [codesandbox](https://codesandbox.io/)
เองนั้นก็มีการ support VIM keybinding เช่นกัน

การที่ IDEs หรือ Editors ต่างๆ support VIM กันอย่างแพร่หลายแบบนี้แล้ว ทำให้เราสามารถ transition(ถึงจะไม่เกิดขึ้นบ่อย)
ไปมาระหว่าง editor ต่างๆโดยที่ ประสบการณ์ในการ coding ของเราก็จะมีความใกล้เคียงกัน
