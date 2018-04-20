# Automatic-watering-machine

## Introduction
โปรเจคเราเกี่ยวกับเครื่องรดน้ำต้นไม้อัตโนมัติ ช่วยเพิ่มความสะดวกสบายในการดูแลรักษาต้นไม้ อีกทั้งยังมีการแจ้งสถานะความชื้นของดินและอุณหภูมิภาพจอLCD

## Working
เครื่องรดน้ำต้นไม้ทำงานโดยวัดความชื้นของดินและอุณหภูมิของสภาพแวดล้อมในขณะนั้น หากค่าความชื้นต่ำหรืออุณหภูมิสูงระบบรดน้ำจะทำงานและแสดงผลแบบ real time นอกจากนี้ระบบของเรายังมีระบบพ่นละอองน้ำเพื่อใช้ในการถนอมใบโดยควบคุมจากอุณหภูมิของสภาพอากาศ

## Status Machine
จอ LCD จะแสดงสถานะ คือ ค่าความชื้นของดินและอุณหภูมิ
* สถานะความชื้น แบ่งเป็น 5 ระดับ คือ D(Dry) L(Low) N(Normal) G(Good) และ O(Over)
<br>&nbsp;ระดับความชื้นที่ D L และ N เครื่องรดน้ำจะทำงาน
<br>&nbsp;ระดับความชื้นที่ G และ O เครื่องรดน้ำจะไม่ทำงาน
* ค่าอุณหภูมิจะแสดงโดยวัดจากอุณหภูมิในอากาศ แสดงผลเป็นหน่วยองศาเซลเซียส(°C)
<br>&nbsp;ค่าอุณหภูมิที่ 36°C ขึ้นไประบบจะพ่นละอองน้ำเพื่อช่วยถนอมใบ

## How to use
<br>1.นำเครื่องรดน้ำต้นไม้ไปติดตั้งในบริเวณที่ต้องการ
<br>2.นำ module วัดความชื้นในดินเสียบลงดิน โดยเว้นระยะห่างให้เหมาะสมและนำเครื่องวัดอุณหภูมิไว้ในร่ม กลางแจ้ง (ควรหลีกเลี่ยงไม่ให้เครื่องโดนน้ำ)
<br>3.นำปั๊มน้ำเสียบเข้ากับเต้ารับกับเครื่อง
<br>4.นำ Arduino เสียบเข้ากับไฟบ้านหรือ Powerbank
<br>5.เปิดสวิตซ์และสามารถดูสถานะการทำงานผ่านจอLCD


## Team Members
| รหัสนักศึกษา        | ชื่อ | นามสกุล |
| :-------------: |:----------:|:--------:|
| 60070001      | กชพร | สถาปนเสถียร |
| 60070027      | เดชาพล | เลิศสุรัตน์ |
| 60070032      | ธัญชนก | พัววิริยะกุล |

## Assistant Teacher
* ผศ.ดร. กิติ์สุชาต พสุภา
* ผศ.ดร. ปานวิทย์ ธุวะนุติ
---
Faculty of Information Technology

King Mongkut's Institute of Technology Ladkrabang
