# murim

ฐานข้อมูลและต้นฉบับนิยายกำลังภายใน

## เริ่มต้นอ่าน
1. [00-CANON.md](./00-CANON.md) — กฎ Canon และข้อกำหนดที่ห้ามเปลี่ยนโดยพลการ
2. [01-WRITING-GUIDE.md](./01-WRITING-GUIDE.md) — หลักการเขียนและการรักษาความต่อเนื่อง
3. [world/overview.md](./world/overview.md) — ภาพรวมโลก
4. [power-system/principles.md](./power-system/principles.md) — หลักวรยุทธ์และลมปราณ
5. [power-system/reputation-model.md](./power-system/reputation-model.md) — วิธีประเมินยอดฝีมือผ่านชื่อเสียง ตำแหน่ง และข่าววงใน
6. [plot/main-plot.md](./plot/main-plot.md) — โครงเรื่องหลัก
7. [timeline/master-timeline.md](./timeline/master-timeline.md) — Timeline กลางของเรื่อง

## World Modules
- `world/overview.md` — ภาพรวมโลก
- `world/regions.md` — เขตอารยธรรม เขตชายขอบ เขตนอก และกฎออกแบบภูมิภาค
- `world/dangerous-zones.md` — หลักการสร้างเขตอันตราย
- `world/power-balance.md` — สมดุลอำนาจและเหตุผลที่ฝ่ายใหญ่ไม่สามารถใช้กำลังตามใจ
- `world/information-network.md` — ข่าวสาร ชื่อเสียง ข่าววงใน และการประเมินยอดฝีมือ
- `world/mysteries.md` — ปริศนาของโลกที่ยังไม่ควรเฉลย

## Martial Arts
- `power-system/principles.md` — หลักลมปราณ วิชา การแพ้ทาง และบุคคลระดับตำนาน
- `power-system/reputation-model.md` — วิธีที่คนในโลกประเมินฝีมือโดยไม่มีระดับพลังตายตัว

## Factions
- `factions/README.md` — ภาพรวมสำนัก ตระกูล และองค์กร
- `factions/design-guide.md` — กฎสร้างฝ่ายให้มีทั้งกำลัง เงิน ข่าวสาร และผลประโยชน์

## Characters
- `characters/character-template.md` — แม่แบบตัวละคร รวมบุคลิก รูปแบบการพูด วิชา ความสัมพันธ์ และสถานะล่าสุด

## Events
- `events/major-events.md` — บันทึกเหตุการณ์สำคัญ
- `events/event-template.md` — แม่แบบสำหรับเหตุการณ์ใหม่ รวมข่าวสาธารณะ ข่าววงใน และผลทางการเมือง

## การเขียนแต่ละภาค
แต่ละภาคอยู่ใน `arcs/`

ก่อนเขียนภาคใด:
1. เปิด `arcs/<arc>/context.md`
2. อ่าน Canon และ World Modules ที่ไฟล์นั้นระบุ
3. อ่านเฉพาะตัวละคร ฝ่าย สถานที่ และเหตุการณ์ที่เกี่ยวข้อง
4. ตรวจ Master Timeline
5. เขียนบท
6. หลังเขียนให้อัปเดต timeline, สถานะตัวละคร, ความสัมพันธ์, ข่าวสาร และเหตุการณ์สำคัญที่เปลี่ยนไป

ใช้ `arcs/arc-context-template.md` เป็นแม่แบบเมื่อสร้างภาคใหม่

## ต้นฉบับ
ต้นฉบับจริงเก็บใน `chapters/`

## กฎสำคัญ
โลกนี้ไม่มี “ระดับพลัง” แบบขั้นหนึ่ง ขั้นสอง หรือเลเวล

เวลาบันทึกความแข็งแกร่ง ให้ใช้:
- ผลงาน
- ตำแหน่ง
- ชื่อเสียง
- คู่ต่อสู้ที่เคยรับมือ
- รายงานข่าวกรอง
- ข่าววงใน
- วิชาและข้อจำกัด

แทนการกำหนดตัวเลขหรือขั้นพลัง


## Cross-chat workflow
เพื่อให้ทุกแชทใช้ข้อมูลตรงกัน ให้เริ่มจาก:
- `PROJECT-GUIDE.md` — กฎการใช้ Git เป็น Source of Truth
- `CONTEXT-MAP.md` — งานแต่ละประเภทต้องอ่านไฟล์ใด
- `SYNC-CHECKLIST.md` — เช็กก่อนจบงานว่าได้อัปเดต Canon/Timeline/Character/Faction ครบหรือยัง
- `arcs/WORKFLOW.md` — ขั้นตอนทำงานระดับภาค
- `chapters/WORKFLOW.md` — ขั้นตอนทำงานระดับบท
- `characters/STRUCTURE.md` — โครงไฟล์ของตัวละครสำคัญ
