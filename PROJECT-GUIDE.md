# MURIM PROJECT GUIDE

ไฟล์นี้กำหนดวิธีทำงานร่วมกันของทุกแชทใน Project

## Source of Truth
ให้ถือ GitHub repository `sakon9654/murim` เป็นแหล่งข้อมูลหลักของนิยาย

เมื่อข้อมูลขัดกัน ให้ยึดตามลำดับ:
1. `00-CANON.md`
2. `timeline/master-timeline.md`
3. `plot/main-plot.md`
4. `characters/`, `world/`, `factions/`, `power-system/`
5. `arcs/`
6. `chapters/`
7. ข้อมูลจากบทสนทนา หากยังไม่ได้บันทึกลง Git

ห้ามใช้ความจำจากบทสนทนาแทนข้อมูลใน Git หากตรวจสอบ Git ได้

## ก่อนวางโครงเรื่องหรือเขียนบท
ต้องอ่านอย่างน้อย:
- `00-CANON.md`
- `01-WRITING-GUIDE.md`
- `world/overview.md`
- `world/power-balance.md`
- `world/information-network.md`
- `power-system/principles.md`
- `power-system/reputation-model.md`
- `timeline/master-timeline.md`
- `plot/main-plot.md`

จากนั้นอ่าน `arcs/<arc>/context.md`

## ก่อนเขียนตัวละคร
ต้องอ่าน:
- character profile ของตัวละคร
- combat/reputation/knowledge ถ้ามี
- ตัวละครที่เกี่ยวข้องโดยตรง
- Arc context
- Timeline ล่าสุด

ต้องรักษา:
- บุคลิก
- รูปแบบการพูด
- สิ่งที่ตัวละครรู้
- สิ่งที่ตัวละครไม่รู้
- ความสัมพันธ์
- เป้าหมาย
- ความลับ
- สภาพร่างกาย
- ชื่อเสียงในแต่ละวงการ

## ก่อนเขียนฉากต่อสู้
ตรวจ:
1. วิชาของแต่ละฝ่าย
2. ข้อมูลที่แต่ละฝ่ายมี
3. การแพ้ทาง
4. พื้นที่
5. สภาพร่างกาย
6. เป้าหมายของการต่อสู้
7. ไพ่ลับที่สมเหตุผล
8. ผลตามมาหลังการต่อสู้

ห้ามใช้ระบบ Level หรือขั้นพลัง

## หลังเขียนเหตุการณ์สำคัญ
ตรวจว่าต้องอัปเดตหรือไม่:
- Master Timeline
- Arc Timeline
- Character status
- Relationships
- Reputation
- Knowledge
- Injuries
- Techniques
- Political consequences
- Major events

## กฎสำคัญ
ถ้ามีการเปลี่ยน Canon ต้องแก้ `00-CANON.md` โดยตรง
ห้ามปล่อยให้ข้อมูล Canon อยู่เฉพาะในบทสนทนา
