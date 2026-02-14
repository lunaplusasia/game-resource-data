<div align="center">

# 📜 Skill Get List — ข้อมูลต้นฉบับ + คำแนะนำ

**รายการสกิลที่ได้รับเมื่อเปลี่ยนอาชีพ + คำแนะนำจากการวิเคราะห์ Balance**

`Skill_Get_List.bin.txt` → **97** อาชีพ · **1771** สกิลรวม

</div>

> **Generated:** 2026-02-14 21:53:57  
> **Skill Analysis Version:** 2.9.0  
> **Source:** `Skill_Get_List.bin.txt` + `skill_rating_report.json`

📊 [Overview](report_overview.md) ｜ 🎯 [Guide](report_class_guide.md) ｜ ⚖️ [Balance](report_balance.md)

---

## 📖 วิธีอ่านตาราง

| สัญลักษณ์ | ความหมาย |
|----------|---------|
| ⚔️ Attack | สกิลโจมตีเป้าเดียว |
| 💥 AoE | สกิลโจมตีวงกว้าง |
| 🔒 CC | สกิลควบคุม (Stun/Slow/KB) |
| ✨ Buff | สกิลบัฟสนับสนุน |
| 🩹 Heal | สกิลรักษา/ฟื้นฟู |
| 💀 Debuff | สกิลลดค่าศัตรู |
| 🟢 Passive | สกิลติดตัวถาวร |
| 🔄 Toggle | สกิลเปิด/ปิด |
| ⚠️ | มีข้อแนะนำให้ปรับ |
| ➕ **เพิ่ม** | แนะนำให้เพิ่มสกิลใหม่ใน Skill_Get_List |
| 🔧 **ปรับ** | แนะนำให้ปรับค่า Multiplier ใน SkillScript/Buff |

---

## 📋 โครงสร้างข้อมูล

### Job Code (4 หลัก: ABCD)
| ตำแหน่ง | ความหมาย | ค่า |
|---------|----------|-----|
| A | สายอาชีพ | 1=Fighter, 2=Rogue, 3=Mage, 4=Devil |
| B | เผ่า | 1=Human, 2=Elf, 3=Devil |
| C | คลาส (Tier) | 1-6 |
| D | สาขา | 1-9 |

---

## 📑 สารบัญ

- **⚔️ [Fighter (นักรบ)](#fighter-นักรบ)** — Avg 84.4 🟡
  - [Human Fighter](#human-fighter)
    - [1111 ไฟท์เตอร์](#1111-fighter) C1
    - [1121 การ์ด](#1121-guard) C2
    - [1122 วอร์ริเออร์](#1122-warrior) C2
    - [1131 อินแฟนทรีแมน](#1131-infantryman) C3
    - [1132 ซอร์ดแมน](#1132-swordman) C3
    - [1133 เมอร์เซนารี](#1133-mercenary) C3
    - [1141 ฟาแลงซ์](#1141-phalanx) C4
    - [1142 ไนท์](#1142-knight) C4
    - [1143 กลาดิเอเตอร์](#1143-gladiator) C4
    - [1144 รูนไนท์](#1144-runic-knight) C4
    - [1151 พาลาดิน](#1151-paladin) **C5** `80` 🟡
    - [1152 แพนเซอร์](#1152-panzer) **C5** `87` 🟡
    - [1153 ครูเสเดอร์](#1153-crusader) **C5** `83` 🟡
    - [1154 เดสทรอยเยอร์](#1154-destroyer) **C5** `92` 🟢
    - [1155 ซอร์ดมาสเตอร์](#1155-sword-master) **C5** `82` 🟡
    - [1156 แม็กเนอร์ส](#1156-magners) **C5**
  - [Elf Fighter](#elf-fighter)
    - [1211 ไฟท์เตอร์](#1211-fighter) C1
    - [1221 การ์ด](#1221-guard) C2
    - [1222 วอร์ริเออร์](#1222-warrior) C2
    - [1231 อินแฟนทรีแมน](#1231-infantryman) C3
    - [1232 ซอร์ดแมน](#1232-swordman) C3
    - [1233 เมอร์เซนารี](#1233-mercenary) C3
    - [1241 ฟาแลงซ์](#1241-phalanx) C4
    - [1242 ไนท์](#1242-knight) C4
    - [1243 กลาดิเอเตอร์](#1243-gladiator) C4
    - [1244 รูนไนท์](#1244-runic-knight) C4
    - [1251 พาลาดิน](#1251-paladin) **C5** `80` 🟡
    - [1252 แพนเซอร์](#1252-panzer) **C5** `87` 🟡
    - [1253 ครูเสเดอร์](#1253-crusader) **C5** `83` 🟡
    - [1254 เดสทรอยเยอร์](#1254-destroyer) **C5** `92` 🟢
    - [1255 ซอร์ดมาสเตอร์](#1255-sword-master) **C5** `82` 🟡
    - [1256 แม็กเนอร์ส](#1256-magners) **C5** `78` 🔴
- **🗡️ [Rogue (โจร/นักธนู)](#rogue-โจร/นักธนู)** — Avg 81.4 🟡
  - [Human Rogue](#human-rogue)
    - [2111 โร้ก](#2111-rogue) C1
    - [2121 วอยเอเจอร์](#2121-voyager) C2
    - [2122 Hunter](#2122-hunter) C2
    - [2131 เทรเชอร์ฮันเตอร์](#2131-treasure-hunter) C3
    - [2132 Assasin](#2132-assasin) C3
    - [2133 เรนเจอร์](#2133-ranger) C3
    - [2141 Rune Walker](#2141-rune-walker) C4
    - [2142 สเคาท์](#2142-scout) C4
    - [2143 Arch Ranger](#2143-arch-ranger) C4
    - [2144 Thief Master](#2144-thief-master) C4
    - [2151 เอ็นแทรปเปอร์](#2151-entrapper) **C5** `88` 🟢
    - [2152 Tempest](#2152-tempest) **C5** `83` 🟡
    - [2153 เบลดเทคเกอร์](#2153-blade-taker) **C5** `77` 🔴
    - [2154 Arch Breezer](#2154-arch-breezer) **C5** `80` 🟡
    - [2155 Magnus](#2155-magnus) **C5** `79` 🔴
  - [Elf Rogue](#elf-rogue)
    - [2211 โร้ก](#2211-rogue) C1
    - [2221 วอยเอเจอร์](#2221-voyager) C2
    - [2222 Hunter](#2222-hunter) C2
    - [2231 เทรเชอร์ฮันเตอร์](#2231-treasure-hunter) C3
    - [2232 Assasin](#2232-assasin) C3
    - [2233 เรนเจอร์](#2233-ranger) C3
    - [2241 Rune Walker](#2241-rune-walker) C4
    - [2242 สเคาท์](#2242-scout) C4
    - [2243 Arch Ranger](#2243-arch-ranger) C4
    - [2244 Thief Master](#2244-thief-master) C4
    - [2251 เอ็นแทรปเปอร์](#2251-entrapper) **C5** `88` 🟢
    - [2252 Tempest](#2252-tempest) **C5** `83` 🟡
    - [2253 เบลดเทคเกอร์](#2253-blade-taker) **C5** `77` 🔴
    - [2254 Arch Breezer](#2254-arch-breezer) **C5** `80` 🟡
    - [2255 Magnus](#2255-magnus) **C5** `79` 🔴
- **🔮 [Mage (จอมเวท)](#mage-จอมเวท)** — Avg 79.8 🔴
  - [Human Mage](#human-mage)
    - [3111 เมจ](#3111-mage) C1
    - [3121 เคลอริค](#3121-cleric) C2
    - [3122 วิซาร์ด](#3122-wizard) C2
    - [3131 พรีสต์](#3131-priest) C3
    - [3132 ซอร์เซอเรอร์](#3132-sorcerer) C3
    - [3133 ม็องค์](#3133-monk) C3
    - [3141 บิชอป](#3141-bishop) C4
    - [3142 วอร์ล็อค](#3142-warlock) C4
    - [3143 อินไควเรอร์](#3143-inquirer) C4
    - [3144 เอเลเมนทัลมาสเตอร์](#3144-elemental-master) C4
    - [3151 คาร์ดินัล](#3151-cardinal) **C5** `83` 🟡
    - [3152 โซลอาร์บิเตอร์](#3152-soul-arbiter) **C5** `91` 🟢
    - [3153 แกรนด์มาสเตอร์](#3153-grand-master) **C5** `80` 🔴
    - [3154 เนโครแมนเซอร์](#3154-necromancer) **C5** `58` 🔴
    - [3155 รูนมาสเตอร์](#3155-runic-master) **C5** `87` 🟡
  - [Elf Mage](#elf-mage)
    - [3211 เมจ](#3211-mage) C1
    - [3221 เคลอริค](#3221-cleric) C2
    - [3222 วิซาร์ด](#3222-wizard) C2
    - [3231 พรีสต์](#3231-priest) C3
    - [3232 ซอร์เซอเรอร์](#3232-sorcerer) C3
    - [3233 ม็องค์](#3233-monk) C3
    - [3241 บิชอป](#3241-bishop) C4
    - [3242 วอร์ล็อค](#3242-warlock) C4
    - [3243 อินไควเรอร์](#3243-inquirer) C4
    - [3244 เอเลเมนทัลมาสเตอร์](#3244-elemental-master) C4
    - [3251 คาร์ดินัล](#3251-cardinal) **C5** `83` 🟡
    - [3252 โซลอาร์บิเตอร์](#3252-soul-arbiter) **C5** `91` 🟢
    - [3253 แกรนด์มาสเตอร์](#3253-grand-master) **C5** `80` 🔴
    - [3254 เนโครแมนเซอร์](#3254-necromancer) **C5** `58` 🔴
    - [3255 รูนมาสเตอร์](#3255-runic-master) **C5** `87` 🟡
- **😈 [Devil (ปีศาจ)](#devil-ปีศาจ)** — Avg 85.3 🟡
  - [Devil Devil](#devil-devil)
    - [4311 แอพเพรนทิส](#4311-apprentice) C1
    - [4321 คอมแบแทนท์](#4321-combatant) C2
    - [4331 เอ็กซ์เพิร์ท](#4331-expert) C3
    - [4341 มาสเตอร์](#4341-master) C4
    - [4351 อะบิสลอร์ด](#4351-abyss-lord) **C5** `85` 🟡

---

## ⚔️ Fighter (นักรบ)

> **Avg Rating:** 84.4/100 · **C5 Jobs:** 11 · เน้นการต่อสู้ระยะประชิดด้วยดาบและโล่ พลังทำลายสูง มี CC และบัฟสนับสนุน
>
> DMG `95` · AoE `82` · CC `82` · Utility `85` · Survivability `75`

### Human Fighter

#### 1111 ไฟท์เตอร์ (C1)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 11001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/4:0:0" width="20" height="20" align="absmiddle" alt="แครชโบลว"> แครชโบลว | 5 | ⚔️ Attack |  |
| 11003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/6:0:0" width="20" height="20" align="absmiddle" alt="วินด์สแลชชิ่ง"> วินด์สแลชชิ่ง | 5 | ⚔️ Attack |  |
| 11004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/7:0:0" width="20" height="20" align="absmiddle" alt="สไตรค์แอทแทค"> สไตรค์แอทแทค | 5 | 💀 Debuff |  |
| 11008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/21:0:0" width="20" height="20" align="absmiddle" alt="อัพเปอร์สวิง"> อัพเปอร์สวิง | 5 | 🔒 CC |  |
| 13001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/10:0:0" width="20" height="20" align="absmiddle" alt="วันแฮนด์เทรนนิ่ง"> วันแฮนด์เทรนนิ่ง | 5 | 🟢 Passive |  |
| 13005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/12:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ HP"> เอนฮานซ์ HP | 5 | 🟢 Passive |  |
| 13009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/26:0:0" width="20" height="20" align="absmiddle" alt="ทูแฮนด์เทรนนิ่ง"> ทูแฮนด์เทรนนิ่ง | 5 | 🟢 Passive |  |
| 15001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/9:0:0" width="20" height="20" align="absmiddle" alt="ไฟเตอร์ฮาร์ท"> ไฟเตอร์ฮาร์ท | 1 | ✨ Buff |  |
| 15022 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/427:0:0" width="20" height="20" align="absmiddle" alt="ดีเปรสชั่นสปิน"> ดีเปรสชั่นสปิน | 15 | 💥 AoE |  |
| 15023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/428:0:0" width="20" height="20" align="absmiddle" alt="อินวิซเอเบิ้ลโรป"> อินวิซเอเบิ้ลโรป | 15 | 💥🔒 AoE+CC |  |
| 15024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/429:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์ซไวทัล"> รีอินฟอร์ซไวทัล | 2 | 💥 AoE |  |
| 15025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/430:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งไฟท์เตอร์"> เบลสซิ่งไฟท์เตอร์ | 2 | 🔄 Toggle |  |
| 15026 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/431:0:0" width="20" height="20" align="absmiddle" alt="ออฟเฟนซิฟโพสิชั่น"> ออฟเฟนซิฟโพสิชั่น | 15 | 🟢 Passive |  |
| 15027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/432:0:0" width="20" height="20" align="absmiddle" alt="ดีเฟนซิฟโพสิชั่น"> ดีเฟนซิฟโพสิชั่น | 15 | 🟢 Passive |  |
| 14001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/138:0:0" width="20" height="20" align="absmiddle" alt="เบิร์นนิ่งเรจ"> เบิร์นนิ่งเรจ | 2 | 🔄 Toggle |  |
| 14002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/1:0:0" width="20" height="20" align="absmiddle" alt="แลช"> แลช | 2 | 🔄 Toggle |  |

---

#### 1121 การ์ด (C2)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 11003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/6:0:0" width="20" height="20" align="absmiddle" alt="วินด์สแลชชิ่ง"> วินด์สแลชชิ่ง | 10 | ⚔️ Attack |  |
| 11004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/7:0:0" width="20" height="20" align="absmiddle" alt="สไตรค์แอทแทค"> สไตรค์แอทแทค | 10 | 💀 Debuff |  |
| 11005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/8:0:0" width="20" height="20" align="absmiddle" alt="แอทแทรค"> แอทแทรค | 5 | 💀 Debuff |  |
| 11007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/17:0:0" width="20" height="20" align="absmiddle" alt="บลันทชิลด์"> บลันทชิลด์ | 5 | 💥🔒 AoE+CC |  |
| 11013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/81:0:0" width="20" height="20" align="absmiddle" alt="บลัดดี้สกาย"> บลัดดี้สกาย | 5 | 💥🔒 AoE+CC |  |
| 13001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/10:0:0" width="20" height="20" align="absmiddle" alt="วันแฮนด์เทรนนิ่ง"> วันแฮนด์เทรนนิ่ง | 10 | 🟢 Passive |  |
| 13003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/19:0:0" width="20" height="20" align="absmiddle" alt="เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์"> เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์ | 5 | 🟢 Passive |  |
| 13005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/12:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ HP"> เอนฮานซ์ HP | 10 | 🟢 Passive |  |
| 15024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/429:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์ซไวทัล"> รีอินฟอร์ซไวทัล | 4 | 💥 AoE |  |
| 15025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/430:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งไฟท์เตอร์"> เบลสซิ่งไฟท์เตอร์ | 4 | 🔄 Toggle |  |

---

#### 1122 วอร์ริเออร์ (C2)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 11001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/4:0:0" width="20" height="20" align="absmiddle" alt="แครชโบลว"> แครชโบลว | 10 | ⚔️ Attack |  |
| 11008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/21:0:0" width="20" height="20" align="absmiddle" alt="อัพเปอร์สวิง"> อัพเปอร์สวิง | 10 | 🔒 CC |  |
| 11010 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/23:0:0" width="20" height="20" align="absmiddle" alt="บอดี้เช็ค"> บอดี้เช็ค | 5 | 🔒 CC |  |
| 11014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/82:0:0" width="20" height="20" align="absmiddle" alt="วีลวินด์"> วีลวินด์ | 5 | 💥 AoE |  |
| 13009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/26:0:0" width="20" height="20" align="absmiddle" alt="ทูแฮนด์เทรนนิ่ง"> ทูแฮนด์เทรนนิ่ง | 10 | 🟢 Passive |  |
| 13015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/232:0:0" width="20" height="20" align="absmiddle" alt="เรจเบอร์สท์"> เรจเบอร์สท์ | 2 | 🟢 Passive |  |
| 15001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/9:0:0" width="20" height="20" align="absmiddle" alt="ไฟเตอร์ฮาร์ท"> ไฟเตอร์ฮาร์ท | 2 | ✨ Buff |  |
| 15024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/429:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์ซไวทัล"> รีอินฟอร์ซไวทัล | 4 | 💥 AoE |  |
| 15025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/430:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งไฟท์เตอร์"> เบลสซิ่งไฟท์เตอร์ | 4 | 🔄 Toggle |  |
| 13003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/19:0:0" width="20" height="20" align="absmiddle" alt="เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์"> เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์ | 3 | 🟢 Passive |  |

---

#### 1131 อินแฟนทรีแมน (C3)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 11003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/6:0:0" width="20" height="20" align="absmiddle" alt="วินด์สแลชชิ่ง"> วินด์สแลชชิ่ง | 15 | ⚔️ Attack |  |
| 11004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/7:0:0" width="20" height="20" align="absmiddle" alt="สไตรค์แอทแทค"> สไตรค์แอทแทค | 15 | 💀 Debuff |  |
| 11005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/8:0:0" width="20" height="20" align="absmiddle" alt="แอทแทรค"> แอทแทรค | 10 | 💀 Debuff |  |
| 11006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/16:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์เอดจ์"> ชิลด์เอดจ์ | 5 | 💥🔒 AoE+CC |  |
| 11007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/17:0:0" width="20" height="20" align="absmiddle" alt="บลันทชิลด์"> บลันทชิลด์ | 10 | 💥🔒 AoE+CC |  |
| 11013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/81:0:0" width="20" height="20" align="absmiddle" alt="บลัดดี้สกาย"> บลัดดี้สกาย | 10 | 💥🔒 AoE+CC |  |
| 11023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/157:0:0" width="20" height="20" align="absmiddle" alt="ทูมบัสต์"> ทูมบัสต์ | 3 | ✨ Buff |  |
| 13001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/10:0:0" width="20" height="20" align="absmiddle" alt="วันแฮนด์เทรนนิ่ง"> วันแฮนด์เทรนนิ่ง | 15 | 🟢 Passive |  |
| 13003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/19:0:0" width="20" height="20" align="absmiddle" alt="เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์"> เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์ | 10 | 🟢 Passive |  |
| 13005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/12:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ HP"> เอนฮานซ์ HP | 15 | 🟢 Passive |  |
| 11015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/96:0:0" width="20" height="20" align="absmiddle" alt="แอทแทรคเซอร์เคิล"> แอทแทรคเซอร์เคิล | 5 | 💥 AoE |  |
| 15024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/429:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์ซไวทัล"> รีอินฟอร์ซไวทัล | 6 | 💥 AoE |  |
| 15025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/430:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งไฟท์เตอร์"> เบลสซิ่งไฟท์เตอร์ | 6 | 🔄 Toggle |  |

---

#### 1132 ซอร์ดแมน (C3)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 11001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/4:0:0" width="20" height="20" align="absmiddle" alt="แครชโบลว"> แครชโบลว | 15 | ⚔️ Attack |  |
| 11014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/82:0:0" width="20" height="20" align="absmiddle" alt="วีลวินด์"> วีลวินด์ | 10 | 💥 AoE |  |
| 11016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/97:0:0" width="20" height="20" align="absmiddle" alt="โซนิคบูม"> โซนิคบูม | 5 | ⚔️ Attack |  |
| 11018 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/230:0:0" width="20" height="20" align="absmiddle" alt="สปิริตเอด"> สปิริตเอด | 5 | ⚔️ Attack |  |
| 11019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/99:0:0" width="20" height="20" align="absmiddle" alt="ซอร์ดสตอร์ม"> ซอร์ดสตอร์ม | 5 | 💥 AoE |  |
| 13001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/10:0:0" width="20" height="20" align="absmiddle" alt="วันแฮนด์เทรนนิ่ง"> วันแฮนด์เทรนนิ่ง | 15 | 🟢 Passive |  |
| 13009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/26:0:0" width="20" height="20" align="absmiddle" alt="ทูแฮนด์เทรนนิ่ง"> ทูแฮนด์เทรนนิ่ง | 15 | 🟢 Passive |  |
| 13010 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/13:0:0" width="20" height="20" align="absmiddle" alt="ซอร์ดเทรนนิ่ง"> ซอร์ดเทรนนิ่ง | 5 | 🟢 Passive |  |
| 13014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/231:0:0" width="20" height="20" align="absmiddle" alt="ซอร์ดแอคคูเรซี่"> ซอร์ดแอคคูเรซี่ | 5 | 🟢 Passive |  |
| 15001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/9:0:0" width="20" height="20" align="absmiddle" alt="ไฟเตอร์ฮาร์ท"> ไฟเตอร์ฮาร์ท | 3 | ✨ Buff |  |
| 15004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/24:0:0" width="20" height="20" align="absmiddle" alt="วอริเออร์ฟอร์ม"> วอริเออร์ฟอร์ม | 2 | ✨ Buff |  |
| 15006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/100:0:0" width="20" height="20" align="absmiddle" alt="มานาสตอร์ม"> มานาสตอร์ม | 5 | ✨ Buff |  |
| 15024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/429:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์ซไวทัล"> รีอินฟอร์ซไวทัล | 6 | 💥 AoE |  |
| 15025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/430:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งไฟท์เตอร์"> เบลสซิ่งไฟท์เตอร์ | 6 | 🔄 Toggle |  |
| 13003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/19:0:0" width="20" height="20" align="absmiddle" alt="เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์"> เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์ | 7 | 🟢 Passive |  |

---

#### 1133 เมอร์เซนารี (C3)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 11001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/4:0:0" width="20" height="20" align="absmiddle" alt="แครชโบลว"> แครชโบลว | 15 | ⚔️ Attack |  |
| 11008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/21:0:0" width="20" height="20" align="absmiddle" alt="อัพเปอร์สวิง"> อัพเปอร์สวิง | 15 | 🔒 CC |  |
| 11010 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/23:0:0" width="20" height="20" align="absmiddle" alt="บอดี้เช็ค"> บอดี้เช็ค | 10 | 🔒 CC |  |
| 11014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/82:0:0" width="20" height="20" align="absmiddle" alt="วีลวินด์"> วีลวินด์ | 10 | 💥 AoE |  |
| 13009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/26:0:0" width="20" height="20" align="absmiddle" alt="ทูแฮนด์เทรนนิ่ง"> ทูแฮนด์เทรนนิ่ง | 15 | 🟢 Passive |  |
| 13010 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/13:0:0" width="20" height="20" align="absmiddle" alt="ซอร์ดเทรนนิ่ง"> ซอร์ดเทรนนิ่ง | 5 | 🟢 Passive |  |
| 13011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/14:0:0" width="20" height="20" align="absmiddle" alt="แอกซ์เทรนนิ่ง"> แอกซ์เทรนนิ่ง | 5 | 🟢 Passive |  |
| 13012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/15:0:0" width="20" height="20" align="absmiddle" alt="เมซเทรนนิ่ง"> เมซเทรนนิ่ง | 5 | 🟢 Passive |  |
| 13015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/232:0:0" width="20" height="20" align="absmiddle" alt="เรจเบอร์สท์"> เรจเบอร์สท์ | 4 | 🟢 Passive |  |
| 15001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/9:0:0" width="20" height="20" align="absmiddle" alt="ไฟเตอร์ฮาร์ท"> ไฟเตอร์ฮาร์ท | 4 | ✨ Buff |  |
| 15024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/429:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์ซไวทัล"> รีอินฟอร์ซไวทัล | 6 | 💥 AoE |  |
| 15025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/430:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งไฟท์เตอร์"> เบลสซิ่งไฟท์เตอร์ | 6 | 🔄 Toggle |  |
| 13003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/19:0:0" width="20" height="20" align="absmiddle" alt="เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์"> เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์ | 7 | 🟢 Passive |  |

---

#### 1141 ฟาแลงซ์ (C4)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 11005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/8:0:0" width="20" height="20" align="absmiddle" alt="แอทแทรค"> แอทแทรค | 15 | 💀 Debuff |  |
| 11006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/16:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์เอดจ์"> ชิลด์เอดจ์ | 10 | 💥🔒 AoE+CC |  |
| 11007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/17:0:0" width="20" height="20" align="absmiddle" alt="บลันทชิลด์"> บลันทชิลด์ | 15 | 💥🔒 AoE+CC |  |
| 11015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/96:0:0" width="20" height="20" align="absmiddle" alt="แอทแทรคเซอร์เคิล"> แอทแทรคเซอร์เคิล | 10 | 💥 AoE |  |
| 11023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/157:0:0" width="20" height="20" align="absmiddle" alt="ทูมบัสต์"> ทูมบัสต์ | 6 | ✨ Buff |  |
| 11028 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/226:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่อาเวนเจอร์"> โฮลี่อาเวนเจอร์ | 10 | 💥🔒 AoE+CC |  |
| 11029 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/5:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่สโตรค"> โฮลี่สโตรค | 10 | 💀 Debuff |  |
| 13003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/19:0:0" width="20" height="20" align="absmiddle" alt="เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์"> เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์ | 15 | 🟢 Passive |  |
| 13005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/12:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ HP"> เอนฮานซ์ HP | 20 | 🟢 Passive |  |
| 13019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/170:0:0" width="20" height="20" align="absmiddle" alt="รีแลกเซชั่น"> รีแลกเซชั่น | 1 | 💥 AoE |  |
| 15005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/94:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์แบริเออร์"> ชิลด์แบริเออร์ | 2 | 🔒 CC |  |
| 15007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/162:0:0" width="20" height="20" align="absmiddle" alt="โซลิดชิลด์"> โซลิดชิลด์ | 1 | ✨ Buff |  |
| 15024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/429:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์ซไวทัล"> รีอินฟอร์ซไวทัล | 8 | 💥 AoE |  |
| 15025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/430:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งไฟท์เตอร์"> เบลสซิ่งไฟท์เตอร์ | 8 | 🔄 Toggle |  |
| 11004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/7:0:0" width="20" height="20" align="absmiddle" alt="สไตรค์แอทแทค"> สไตรค์แอทแทค | 30 | 💀 Debuff |  |
| 15003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/18:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งการ์ด"> เบลสซิ่งการ์ด | 5 | ✨ Buff |  |
| 33007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/78:0:0" width="20" height="20" align="absmiddle" alt="เมจิคแบริเออร์"> เมจิคแบริเออร์ | 10 | 🟢 Passive |  |
| 13012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/15:0:0" width="20" height="20" align="absmiddle" alt="เมซเทรนนิ่ง"> เมซเทรนนิ่ง | 10 | 🟢 Passive |  |
| 13018 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/225:0:0" width="20" height="20" align="absmiddle" alt="เมสโพรเทคชั่น"> เมสโพรเทคชั่น | 10 | 🟢 Passive |  |
| 13004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/20:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์เทรนนิ่ง"> ชิลด์เทรนนิ่ง | 10 | 🟢 Passive |  |
| 15008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/163:0:0" width="20" height="20" align="absmiddle" alt="อินวัลเนอเรเบิล"> อินวัลเนอเรเบิล | 1 | 🔒 CC |  |
| 13013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/229:0:0" width="20" height="20" align="absmiddle" alt="ทรูเปอร์ชิป"> ทรูเปอร์ชิป | 4 | 🟢 Passive |  |
| 11003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/6:0:0" width="20" height="20" align="absmiddle" alt="วินด์สแลชชิ่ง"> วินด์สแลชชิ่ง | 20 | ⚔️ Attack |  |

---

#### 1142 ไนท์ (C4)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 11003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/6:0:0" width="20" height="20" align="absmiddle" alt="วินด์สแลชชิ่ง"> วินด์สแลชชิ่ง | 30 | ⚔️ Attack |  |
| 11004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/7:0:0" width="20" height="20" align="absmiddle" alt="สไตรค์แอทแทค"> สไตรค์แอทแทค | 30 | 💀 Debuff |  |
| 11005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/8:0:0" width="20" height="20" align="absmiddle" alt="แอทแทรค"> แอทแทรค | 10 | 💀 Debuff |  |
| 11006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/16:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์เอดจ์"> ชิลด์เอดจ์ | 10 | 💥🔒 AoE+CC |  |
| 11013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/81:0:0" width="20" height="20" align="absmiddle" alt="บลัดดี้สกาย"> บลัดดี้สกาย | 30 | 💥🔒 AoE+CC |  |
| 11015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/96:0:0" width="20" height="20" align="absmiddle" alt="แอทแทรคเซอร์เคิล"> แอทแทรคเซอร์เคิล | 5 | 💥 AoE |  |
| 11023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/157:0:0" width="20" height="20" align="absmiddle" alt="ทูมบัสต์"> ทูมบัสต์ | 5 | ✨ Buff |  |
| 13001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/10:0:0" width="20" height="20" align="absmiddle" alt="วันแฮนด์เทรนนิ่ง"> วันแฮนด์เทรนนิ่ง | 20 | 🟢 Passive |  |
| 13003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/19:0:0" width="20" height="20" align="absmiddle" alt="เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์"> เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์ | 15 | 🟢 Passive |  |
| 13010 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/13:0:0" width="20" height="20" align="absmiddle" alt="ซอร์ดเทรนนิ่ง"> ซอร์ดเทรนนิ่ง | 10 | 🟢 Passive |  |
| 13011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/14:0:0" width="20" height="20" align="absmiddle" alt="แอกซ์เทรนนิ่ง"> แอกซ์เทรนนิ่ง | 10 | 🟢 Passive |  |
| 13012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/15:0:0" width="20" height="20" align="absmiddle" alt="เมซเทรนนิ่ง"> เมซเทรนนิ่ง | 10 | 🟢 Passive |  |
| 15005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/94:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์แบริเออร์"> ชิลด์แบริเออร์ | 1 | 🔒 CC |  |
| 15009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/164:0:0" width="20" height="20" align="absmiddle" alt="โซลิดวิพพอน"> โซลิดวิพพอน | 2 | ✨ Buff |  |
| 15024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/429:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์ซไวทัล"> รีอินฟอร์ซไวทัล | 8 | 💥 AoE |  |
| 15025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/430:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งไฟท์เตอร์"> เบลสซิ่งไฟท์เตอร์ | 8 | 🔄 Toggle |  |
| 11016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/97:0:0" width="20" height="20" align="absmiddle" alt="โซนิคบูม"> โซนิคบูม | 15 | ⚔️ Attack |  |
| 11019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/99:0:0" width="20" height="20" align="absmiddle" alt="ซอร์ดสตอร์ม"> ซอร์ดสตอร์ม | 15 | 💥 AoE |  |
| 13009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/26:0:0" width="20" height="20" align="absmiddle" alt="ทูแฮนด์เทรนนิ่ง"> ทูแฮนด์เทรนนิ่ง | 20 | 🟢 Passive |  |

---

#### 1143 กลาดิเอเตอร์ (C4)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 11001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/4:0:0" width="20" height="20" align="absmiddle" alt="แครชโบลว"> แครชโบลว | 25 | ⚔️ Attack |  |
| 11008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/21:0:0" width="20" height="20" align="absmiddle" alt="อัพเปอร์สวิง"> อัพเปอร์สวิง | 25 | 🔒 CC |  |
| 11014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/82:0:0" width="20" height="20" align="absmiddle" alt="วีลวินด์"> วีลวินด์ | 15 | 💥 AoE |  |
| 11024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/158:0:0" width="20" height="20" align="absmiddle" alt="เฟลมสแมช"> เฟลมสแมช | 20 | 💀 Debuff |  |
| 11025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/159:0:0" width="20" height="20" align="absmiddle" alt="เอิร์ธเวฟ"> เอิร์ธเวฟ | 20 | 💀 Debuff |  |
| 13009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/26:0:0" width="20" height="20" align="absmiddle" alt="ทูแฮนด์เทรนนิ่ง"> ทูแฮนด์เทรนนิ่ง | 20 | 🟢 Passive |  |
| 13010 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/13:0:0" width="20" height="20" align="absmiddle" alt="ซอร์ดเทรนนิ่ง"> ซอร์ดเทรนนิ่ง | 10 | 🟢 Passive |  |
| 13011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/14:0:0" width="20" height="20" align="absmiddle" alt="แอกซ์เทรนนิ่ง"> แอกซ์เทรนนิ่ง | 10 | 🟢 Passive |  |
| 13012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/15:0:0" width="20" height="20" align="absmiddle" alt="เมซเทรนนิ่ง"> เมซเทรนนิ่ง | 10 | 🟢 Passive |  |
| 13015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/232:0:0" width="20" height="20" align="absmiddle" alt="เรจเบอร์สท์"> เรจเบอร์สท์ | 6 | 🟢 Passive |  |
| 15001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/9:0:0" width="20" height="20" align="absmiddle" alt="ไฟเตอร์ฮาร์ท"> ไฟเตอร์ฮาร์ท | 6 | ✨ Buff |  |
| 15024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/429:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์ซไวทัล"> รีอินฟอร์ซไวทัล | 8 | 💥 AoE |  |
| 15025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/430:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งไฟท์เตอร์"> เบลสซิ่งไฟท์เตอร์ | 8 | 🔄 Toggle |  |
| 13003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/19:0:0" width="20" height="20" align="absmiddle" alt="เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์"> เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์ | 10 | 🟢 Passive |  |
| 15011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/166:0:0" width="20" height="20" align="absmiddle" alt="เบอร์เซอเคอร์"> เบอร์เซอเคอร์ | 1 | 🩹 Heal |  |

---

#### 1144 รูนไนท์ (C4)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 11001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/4:0:0" width="20" height="20" align="absmiddle" alt="แครชโบลว"> แครชโบลว | 15 | ⚔️ Attack |  |
| 11014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/82:0:0" width="20" height="20" align="absmiddle" alt="วีลวินด์"> วีลวินด์ | 15 | 💥 AoE |  |
| 11016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/97:0:0" width="20" height="20" align="absmiddle" alt="โซนิคบูม"> โซนิคบูม | 10 | ⚔️ Attack |  |
| 11018 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/230:0:0" width="20" height="20" align="absmiddle" alt="สปิริตเอด"> สปิริตเอด | 10 | ⚔️ Attack |  |
| 11019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/99:0:0" width="20" height="20" align="absmiddle" alt="ซอร์ดสตอร์ม"> ซอร์ดสตอร์ม | 10 | 💥 AoE |  |
| 11025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/159:0:0" width="20" height="20" align="absmiddle" alt="เอิร์ธเวฟ"> เอิร์ธเวฟ | 10 | 💀 Debuff |  |
| 13009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/26:0:0" width="20" height="20" align="absmiddle" alt="ทูแฮนด์เทรนนิ่ง"> ทูแฮนด์เทรนนิ่ง | 20 | 🟢 Passive |  |
| 15001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/9:0:0" width="20" height="20" align="absmiddle" alt="ไฟเตอร์ฮาร์ท"> ไฟเตอร์ฮาร์ท | 5 | ✨ Buff |  |
| 15004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/24:0:0" width="20" height="20" align="absmiddle" alt="วอริเออร์ฟอร์ม"> วอริเออร์ฟอร์ม | 4 | ✨ Buff |  |
| 15006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/100:0:0" width="20" height="20" align="absmiddle" alt="มานาสตอร์ม"> มานาสตอร์ม | 7 | ✨ Buff |  |
| 15012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/167:0:0" width="20" height="20" align="absmiddle" alt="แอคคูเรซี่ออร่า"> แอคคูเรซี่ออร่า | 2 | 💥 AoE |  |
| 15013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/168:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์ออร่า"> ชิลด์ออร่า | 2 | 💥 AoE |  |
| 15014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/169:0:0" width="20" height="20" align="absmiddle" alt="แรมเพจออร่า"> แรมเพจออร่า | 2 | 🩹 Heal |  |
| 15024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/429:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์ซไวทัล"> รีอินฟอร์ซไวทัล | 8 | 💥 AoE |  |
| 15025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/430:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งไฟท์เตอร์"> เบลสซิ่งไฟท์เตอร์ | 8 | 🔄 Toggle |  |
| 13003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/19:0:0" width="20" height="20" align="absmiddle" alt="เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์"> เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์ | 10 | 🟢 Passive |  |
| 11027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/161:0:0" width="20" height="20" align="absmiddle" alt="รูนอิมแพค"> รูนอิมแพค | 15 | 🔒 CC |  |
| 11017 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/98:0:0" width="20" height="20" align="absmiddle" alt="สปิริตซอร์ด"> สปิริตซอร์ด | 20 | 🔒 CC |  |
| 13001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/10:0:0" width="20" height="20" align="absmiddle" alt="วันแฮนด์เทรนนิ่ง"> วันแฮนด์เทรนนิ่ง | 20 | 🟢 Passive |  |
| 13004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/20:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์เทรนนิ่ง"> ชิลด์เทรนนิ่ง | 10 | 🟢 Passive |  |
| 14004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/3:0:0" width="20" height="20" align="absmiddle" alt="เนเจอร์มายด์"> เนเจอร์มายด์ | 2 | 🔄 Toggle |  |
| 14003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/2:0:0" width="20" height="20" align="absmiddle" alt="เนเจอร์ชิลด์"> เนเจอร์ชิลด์ | 2 | 🔄 Toggle |  |
| 13001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/10:0:0" width="20" height="20" align="absmiddle" alt="วันแฮนด์เทรนนิ่ง"> วันแฮนด์เทรนนิ่ง | 20 | 🟢 Passive |  |
| 15019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/78:0:0" width="20" height="20" align="absmiddle" alt="โพรเทคชั่นออร่า"> โพรเทคชั่นออร่า | 2 | 💥 AoE |  |

---

#### 1151 พาลาดิน (C5)

> 🟡 **Overall: 80.2**/100 · DMG `81` · AoE `95` · CC `100` · Util `75` · Surv `56`

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 11005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/8:0:0" width="20" height="20" align="absmiddle" alt="แอทแทรค"> แอทแทรค | 30 | 💀 Debuff |  |
| 11006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/16:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์เอดจ์"> ชิลด์เอดจ์ | 30 | 💥🔒 AoE+CC |  |
| 11015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/96:0:0" width="20" height="20" align="absmiddle" alt="แอทแทรคเซอร์เคิล"> แอทแทรคเซอร์เคิล | 30 | 💥 AoE |  |
| 11023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/157:0:0" width="20" height="20" align="absmiddle" alt="ทูมบัสต์"> ทูมบัสต์ | 9 | ✨ Buff |  |
| 11032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/230:0:0" width="20" height="20" align="absmiddle" alt="เซ้นต์ฮีล"> เซ้นต์ฮีล | 5 | 💥 AoE |  |
| 13003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/19:0:0" width="20" height="20" align="absmiddle" alt="เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์"> เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์ | 20 | 🟢 Passive |  |
| 13019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/170:0:0" width="20" height="20" align="absmiddle" alt="รีแลกเซชั่น"> รีแลกเซชั่น | 1 | 💥 AoE |  |
| 15005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/94:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์แบริเออร์"> ชิลด์แบริเออร์ | 4 | 🔒 CC |  |
| 15007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/162:0:0" width="20" height="20" align="absmiddle" alt="โซลิดชิลด์"> โซลิดชิลด์ | 5 | ✨ Buff |  |
| 15024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/429:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์ซไวทัล"> รีอินฟอร์ซไวทัล | 10 | 💥 AoE |  |
| 15025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/430:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งไฟท์เตอร์"> เบลสซิ่งไฟท์เตอร์ | 10 | 🔄 Toggle |  |
| 11007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/17:0:0" width="20" height="20" align="absmiddle" alt="บลันทชิลด์"> บลันทชิลด์ | 30 | 💥🔒 AoE+CC |  |
| 13018 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/225:0:0" width="20" height="20" align="absmiddle" alt="เมสโพรเทคชั่น"> เมสโพรเทคชั่น | 20 | 🟢 Passive |  |
| 11022 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/156:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์ชาร์จจิ้ง"> ชิลด์ชาร์จจิ้ง | 30 | 🔒 CC |  |
| 13004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/20:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์เทรนนิ่ง"> ชิลด์เทรนนิ่ง | 20 | 🟢 Passive |  |
| 13012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/15:0:0" width="20" height="20" align="absmiddle" alt="เมซเทรนนิ่ง"> เมซเทรนนิ่ง | 20 | 🟢 Passive |  |
| 15003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/18:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งการ์ด"> เบลสซิ่งการ์ด | 10 | ✨ Buff |  |
| 15015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/162:0:0" width="20" height="20" align="absmiddle" alt="ไอรอนชิลด์"> ไอรอนชิลด์ | 2 | ✨ Buff |  |
| 13001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/10:0:0" width="20" height="20" align="absmiddle" alt="วันแฮนด์เทรนนิ่ง"> วันแฮนด์เทรนนิ่ง | 20 | 🟢 Passive |  |

<details><summary>⚠️ <strong>คำแนะนำการปรับสมดุล (2 รายการ)</strong></summary>

| # | ประเภท | มิติ | รายละเอียด | ไฟล์ที่แก้ | Gap |
|---|--------|------|----------|------------|-----|
| 1 | 🔧 ปรับ | Survivability | 🛡️ ปรับค่า fStatusDataMul สกิลบัฟ/ฮีล (×1.3-1.5) | `Skill_Buff_List.bin.txt` | 9.0 |
| 2 | 🔧 ปรับ | Damage | ⚔️ ปรับค่า fUnitDataValueMul สกิลโจมตี (×1.2-1.5) | `SkillScript.bin.txt` | 14.0 |

</details>

---

#### 1152 แพนเซอร์ (C5)

> 🟡 **Overall: 87.3**/100 · DMG `95` · AoE `65` · CC `84` · Util `99` · Surv `90`

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 11044 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/271:0:0" width="20" height="20" align="absmiddle" alt="สแตนดิ้งไฟร์"> สแตนดิ้งไฟร์ | 20 | 💀 Debuff |  |
| 11045 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/246:0:0" width="20" height="20" align="absmiddle" alt="ไอรอนบอมบ์"> ไอรอนบอมบ์ | 20 | 💥 AoE |  |
| 11046 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/272:0:0" width="20" height="20" align="absmiddle" alt="นิลลิ่งช๊อต"> นิลลิ่งช๊อต | 20 | 🔒 CC |  |
| 11047 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/273:0:0" width="20" height="20" align="absmiddle" alt="มัสเกทพร๊อกซิมิตี้"> มัสเกทพร๊อกซิมิตี้ | 20 | 🔒 CC |  |
| 11048 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/354:0:0" width="20" height="20" align="absmiddle" alt="มัสเกทโบลว"> มัสเกทโบลว | 20 | 💀 Debuff |  |
| 13003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/19:0:0" width="20" height="20" align="absmiddle" alt="เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์"> เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์ | 15 | 🟢 Passive |  |
| 13024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/356:0:0" width="20" height="20" align="absmiddle" alt="มัสเกทแอคคูเรซี่"> มัสเกทแอคคูเรซี่ | 10 | 🟢 Passive |  |
| 13025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/357:0:0" width="20" height="20" align="absmiddle" alt="มัสเกทเทรนนิ่ง"> มัสเกทเทรนนิ่ง | 20 | 🟢 Passive |  |
| 15009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/164:0:0" width="20" height="20" align="absmiddle" alt="โซลิดวิพพอน"> โซลิดวิพพอน | 5 | ✨ Buff |  |
| 15020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/355:0:0" width="20" height="20" align="absmiddle" alt="รีโหลดดิ้ง"> รีโหลดดิ้ง | 5 | 🩹 Heal |  |
| 15024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/429:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์ซไวทัล"> รีอินฟอร์ซไวทัล | 10 | 💥 AoE |  |
| 15025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/430:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งไฟท์เตอร์"> เบลสซิ่งไฟท์เตอร์ | 10 | 🔄 Toggle |  |
| 23013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/358:0:0" width="20" height="20" align="absmiddle" alt="มัสเกทเรนจ์"> มัสเกทเรนจ์ | 5 | 🟢 Passive |  |
| 13015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/232:0:0" width="20" height="20" align="absmiddle" alt="เรจเบอร์สท์"> เรจเบอร์สท์ | 8 | 🟢 Passive |  |
| 15017 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/345:0:0" width="20" height="20" align="absmiddle" alt="เฟทัลฟอร์ซ"> เฟทัลฟอร์ซ | 3 | ✨ Buff |  |
| 13020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/171:0:0" width="20" height="20" align="absmiddle" alt="อาร์มเมอร์ซิงโคร"> อาร์มเมอร์ซิงโคร | 3 | ✨ Buff |  |
| 13021 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/172:0:0" width="20" height="20" align="absmiddle" alt="วิพพอนซิงโคร"> วิพพอนซิงโคร | 3 | 🩹 Heal |  |
| 25014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/276:0:0" width="20" height="20" align="absmiddle" alt="มัสเกทสโคป"> มัสเกทสโคป | 10 | ✨ Buff |  |

<details><summary>⚠️ <strong>คำแนะนำการปรับสมดุล (1 รายการ)</strong></summary>

| # | ประเภท | มิติ | รายละเอียด | ไฟล์ที่แก้ | Gap |
|---|--------|------|----------|------------|-----|
| 1 | ➕ เพิ่ม | AoE | 💥 เพิ่มสกิล AoE อีก 1 ตัว (มี 1, ควรมี 3+) | `Skill_Get_List.bin.txt` | 15.0 |

</details>

---

#### 1153 ครูเสเดอร์ (C5)

> 🟡 **Overall: 83.2**/100 · DMG `100` · AoE `100` · CC `100` · Util `75` · Surv `42`

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 11029 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/5:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่สโตรค"> โฮลี่สโตรค | 30 | 💀 Debuff |  |
| 11030 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/348:0:0" width="20" height="20" align="absmiddle" alt="เรจซอร์ด"> เรจซอร์ด | 20 | 💀 Debuff |  |
| 11031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/8:0:0" width="20" height="20" align="absmiddle" alt="เซ้นต์แช็คเกิ้ล"> เซ้นต์แช็คเกิ้ล | 30 | 💥🔒 AoE+CC |  |
| 11033 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/353:0:0" width="20" height="20" align="absmiddle" alt="ช๊อคเวฟ"> ช๊อคเวฟ | 10 | 💥🔒 AoE+CC |  |
| 11034 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/347:0:0" width="20" height="20" align="absmiddle" alt="ดาร์คอิลูชั่น"> ดาร์คอิลูชั่น | 10 | 🔒 CC |  |
| 11035 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/350:0:0" width="20" height="20" align="absmiddle" alt="ธันเดอร์ออฟเดธ"> ธันเดอร์ออฟเดธ | 20 | 💥🔒 AoE+CC |  |
| 15006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/100:0:0" width="20" height="20" align="absmiddle" alt="มานาสตอร์ม"> มานาสตอร์ม | 10 | ✨ Buff |  |
| 15016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/349:0:0" width="20" height="20" align="absmiddle" alt="เมนทัลเวอร์เทกซ์"> เมนทัลเวอร์เทกซ์ | 10 | ✨ Buff |  |
| 13020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/171:0:0" width="20" height="20" align="absmiddle" alt="อาร์มเมอร์ซิงโคร"> อาร์มเมอร์ซิงโคร | 3 | ✨ Buff |  |
| 35027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/122:0:0" width="20" height="20" align="absmiddle" alt="มานาออร่า"> มานาออร่า | 5 | 🔄 Toggle |  |
| 15024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/429:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์ซไวทัล"> รีอินฟอร์ซไวทัล | 10 | 💥 AoE |  |
| 15025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/430:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งไฟท์เตอร์"> เบลสซิ่งไฟท์เตอร์ | 10 | 🔄 Toggle |  |
| 13003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/19:0:0" width="20" height="20" align="absmiddle" alt="เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์"> เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์ | 15 | 🟢 Passive |  |
| 13012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/15:0:0" width="20" height="20" align="absmiddle" alt="เมซเทรนนิ่ง"> เมซเทรนนิ่ง | 20 | 🟢 Passive |  |
| 33002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/60:0:0" width="20" height="20" align="absmiddle" alt="โร๊บเอ็กซเพอร์ไทซ์"> โร๊บเอ็กซเพอร์ไทซ์ | 20 | 🟢 Passive |  |
| 11028 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/226:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่อาเวนเจอร์"> โฮลี่อาเวนเจอร์ | 20 | 💥🔒 AoE+CC |  |
| 11029 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/5:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่สโตรค"> โฮลี่สโตรค | 15 | 💀 Debuff |  |
| 35023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/234:0:0" width="20" height="20" align="absmiddle" alt="ทวิงเกิ้ลเมจิก"> ทวิงเกิ้ลเมจิก | 8 | ✨ Buff |  |

<details><summary>⚠️ <strong>คำแนะนำการปรับสมดุล (1 รายการ)</strong></summary>

| # | ประเภท | มิติ | รายละเอียด | ไฟล์ที่แก้ | Gap |
|---|--------|------|----------|------------|-----|
| 1 | 🔧 ปรับ | Survivability | 🛡️ ปรับค่า fStatusDataMul สกิลบัฟ/ฮีล (×1.3-1.5) | `Skill_Buff_List.bin.txt` | 23.0 |

</details>

---

#### 1154 เดสทรอยเยอร์ (C5)

> 🟢 **Overall: 92.5**/100 · DMG `100` · AoE `80` · CC `86` · Util `90` · Surv `100`

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 11014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/82:0:0" width="20" height="20" align="absmiddle" alt="วีลวินด์"> วีลวินด์ | 20 | 💥 AoE |  |
| 11024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/158:0:0" width="20" height="20" align="absmiddle" alt="เฟลมสแมช"> เฟลมสแมช | 15 | 💀 Debuff |  |
| 11025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/159:0:0" width="20" height="20" align="absmiddle" alt="เอิร์ธเวฟ"> เอิร์ธเวฟ | 30 | 💀 Debuff |  |
| 11037 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/341:0:0" width="20" height="20" align="absmiddle" alt="ครูเอลซอร์ด"> ครูเอลซอร์ด | 10 | 🔒 CC |  |
| 13009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/26:0:0" width="20" height="20" align="absmiddle" alt="ทูแฮนด์เทรนนิ่ง"> ทูแฮนด์เทรนนิ่ง | 20 | 🟢 Passive |  |
| 13010 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/13:0:0" width="20" height="20" align="absmiddle" alt="ซอร์ดเทรนนิ่ง"> ซอร์ดเทรนนิ่ง | 15 | 🟢 Passive |  |
| 13011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/14:0:0" width="20" height="20" align="absmiddle" alt="แอกซ์เทรนนิ่ง"> แอกซ์เทรนนิ่ง | 15 | 🟢 Passive |  |
| 13012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/15:0:0" width="20" height="20" align="absmiddle" alt="เมซเทรนนิ่ง"> เมซเทรนนิ่ง | 15 | 🟢 Passive |  |
| 13014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/231:0:0" width="20" height="20" align="absmiddle" alt="ซอร์ดแอคคูเรซี่"> ซอร์ดแอคคูเรซี่ | 10 | 🟢 Passive |  |
| 13015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/232:0:0" width="20" height="20" align="absmiddle" alt="เรจเบอร์สท์"> เรจเบอร์สท์ | 8 | 🟢 Passive |  |
| 13017 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/224:0:0" width="20" height="20" align="absmiddle" alt="แอ็กซ์มอทัลลิตี้"> แอ็กซ์มอทัลลิตี้ | 10 | 🟢 Passive |  |
| 13018 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/225:0:0" width="20" height="20" align="absmiddle" alt="เมสโพรเทคชั่น"> เมสโพรเทคชั่น | 10 | 🟢 Passive |  |
| 15001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/9:0:0" width="20" height="20" align="absmiddle" alt="ไฟเตอร์ฮาร์ท"> ไฟเตอร์ฮาร์ท | 8 | ✨ Buff |  |
| 15024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/429:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์ซไวทัล"> รีอินฟอร์ซไวทัล | 10 | 💥 AoE |  |
| 15025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/430:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งไฟท์เตอร์"> เบลสซิ่งไฟท์เตอร์ | 10 | 🔄 Toggle |  |
| 13003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/19:0:0" width="20" height="20" align="absmiddle" alt="เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์"> เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์ | 15 | 🟢 Passive |  |
| 11036 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/351:0:0" width="20" height="20" align="absmiddle" alt="เฟียร์ฟูลโบลว"> เฟียร์ฟูลโบลว | 30 | 💥🔒 AoE+CC |  |
| 15011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/166:0:0" width="20" height="20" align="absmiddle" alt="เบอร์เซอเคอร์"> เบอร์เซอเคอร์ | 3 | 🩹 Heal |  |
| 11001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/4:0:0" width="20" height="20" align="absmiddle" alt="แครชโบลว"> แครชโบลว | 30 | ⚔️ Attack |  |
| 11008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/21:0:0" width="20" height="20" align="absmiddle" alt="อัพเปอร์สวิง"> อัพเปอร์สวิง | 30 | 🔒 CC |  |
| 13020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/171:0:0" width="20" height="20" align="absmiddle" alt="อาร์มเมอร์ซิงโคร"> อาร์มเมอร์ซิงโคร | 3 | ✨ Buff |  |
| 13021 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/172:0:0" width="20" height="20" align="absmiddle" alt="วิพพอนซิงโคร"> วิพพอนซิงโคร | 3 | 🩹 Heal |  |
| 13008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/227:0:0" width="20" height="20" align="absmiddle" alt="ริสกี้เทคเกอร์"> ริสกี้เทคเกอร์ | 8 | 🟢 Passive |  |

> ✅ **สมดุลดี** — ไม่มีข้อแนะนำเพิ่มเติม

---

#### 1155 ซอร์ดมาสเตอร์ (C5)

> 🟡 **Overall: 82.2**/100 · DMG `100` · AoE `80` · CC `54` · Util `84` · Surv `83`

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 11016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/97:0:0" width="20" height="20" align="absmiddle" alt="โซนิคบูม"> โซนิคบูม | 20 | ⚔️ Attack |  |
| 11019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/99:0:0" width="20" height="20" align="absmiddle" alt="ซอร์ดสตอร์ม"> ซอร์ดสตอร์ม | 30 | 💥 AoE |  |
| 11040 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/342:0:0" width="20" height="20" align="absmiddle" alt="ดูอัลโซนิคบูม"> ดูอัลโซนิคบูม | 10 | ⚔️ Attack |  |
| 11041 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/82:0:0" width="20" height="20" align="absmiddle" alt="ซอร์ดสปิน"> ซอร์ดสปิน | 10 | 💥 AoE |  |
| 11042 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/344:0:0" width="20" height="20" align="absmiddle" alt="ดูอัลโบลว"> ดูอัลโบลว | 10 | ⚔️ Attack |  |
| 13010 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/13:0:0" width="20" height="20" align="absmiddle" alt="ซอร์ดเทรนนิ่ง"> ซอร์ดเทรนนิ่ง | 15 | 🟢 Passive |  |
| 13014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/231:0:0" width="20" height="20" align="absmiddle" alt="ซอร์ดแอคคูเรซี่"> ซอร์ดแอคคูเรซี่ | 10 | 🟢 Passive |  |
| 13022 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/267:0:0" width="20" height="20" align="absmiddle" alt="ดูอัลวิปพอนเทรนนิ่ง"> ดูอัลวิปพอนเทรนนิ่ง | 10 | 🟢 Passive |  |
| 13026 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/268:0:0" width="20" height="20" align="absmiddle" alt="ดูอัลวิปพอนมาสเตอรี่"> ดูอัลวิปพอนมาสเตอรี่ | 10 | 🟢 Passive |  |
| 15001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/9:0:0" width="20" height="20" align="absmiddle" alt="ไฟเตอร์ฮาร์ท"> ไฟเตอร์ฮาร์ท | 7 | ✨ Buff |  |
| 15004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/24:0:0" width="20" height="20" align="absmiddle" alt="วอริเออร์ฟอร์ม"> วอริเออร์ฟอร์ม | 8 | ✨ Buff |  |
| 15024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/429:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์ซไวทัล"> รีอินฟอร์ซไวทัล | 10 | 💥 AoE |  |
| 15025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/430:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งไฟท์เตอร์"> เบลสซิ่งไฟท์เตอร์ | 10 | 🔄 Toggle |  |
| 13003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/19:0:0" width="20" height="20" align="absmiddle" alt="เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์"> เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์ | 15 | 🟢 Passive |  |
| 13016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/111:0:0" width="20" height="20" align="absmiddle" alt="ซอร์ดเรพิดิตี้"> ซอร์ดเรพิดิตี้ | 10 | 🟢 Passive |  |
| 15011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/166:0:0" width="20" height="20" align="absmiddle" alt="เบอร์เซอเคอร์"> เบอร์เซอเคอร์ | 3 | 🩹 Heal |  |
| 11001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/4:0:0" width="20" height="20" align="absmiddle" alt="แครชโบลว"> แครชโบลว | 30 | ⚔️ Attack |  |
| 11008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/21:0:0" width="20" height="20" align="absmiddle" alt="อัพเปอร์สวิง"> อัพเปอร์สวิง | 30 | 🔒 CC |  |
| 13023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/15:0:0" width="20" height="20" align="absmiddle" alt="ดูอัลวิปพอร์นแอคคูเรซี่"> ดูอัลวิปพอร์นแอคคูเรซี่ | 10 | 🟢 Passive |  |
| 15017 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/345:0:0" width="20" height="20" align="absmiddle" alt="เฟทัลฟอร์ซ"> เฟทัลฟอร์ซ | 3 | ✨ Buff |  |
| 11002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/5:0:0" width="20" height="20" align="absmiddle" alt="บลัดดิ้งโบลว"> บลัดดิ้งโบลว | 30 | 💀 Debuff |  |
| 11037 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/341:0:0" width="20" height="20" align="absmiddle" alt="ครูเอลซอร์ด"> ครูเอลซอร์ด | 20 | 🔒 CC |  |
| 11039 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/343:0:0" width="20" height="20" align="absmiddle" alt="เฟียร์ฟูลมาซาเคอร์"> เฟียร์ฟูลมาซาเคอร์ | 20 | 💀 Debuff |  |

<details><summary>⚠️ <strong>คำแนะนำการปรับสมดุล (1 รายการ)</strong></summary>

| # | ประเภท | มิติ | รายละเอียด | ไฟล์ที่แก้ | Gap |
|---|--------|------|----------|------------|-----|
| 1 | ➕ เพิ่ม | CC | 🔒 เพิ่มสกิล CC อีก 1 ตัว (มี 2) | `Skill_Get_List / Skill_Buff_List` | 21.0 |

</details>

---

#### 1156 แม็กเนอร์ส (C5)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 11016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/97:0:0" width="20" height="20" align="absmiddle" alt="โซนิคบูม"> โซนิคบูม | 20 | ⚔️ Attack |  |
| 11019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/99:0:0" width="20" height="20" align="absmiddle" alt="ซอร์ดสตอร์ม"> ซอร์ดสตอร์ม | 30 | 💥 AoE |  |
| 11040 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/342:0:0" width="20" height="20" align="absmiddle" alt="ดูอัลโซนิคบูม"> ดูอัลโซนิคบูม | 10 | ⚔️ Attack |  |
| 11042 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/344:0:0" width="20" height="20" align="absmiddle" alt="ดูอัลโบลว"> ดูอัลโบลว | 10 | ⚔️ Attack |  |
| 13022 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/267:0:0" width="20" height="20" align="absmiddle" alt="ดูอัลวิปพอนเทรนนิ่ง"> ดูอัลวิปพอนเทรนนิ่ง | 10 | 🟢 Passive |  |
| 13026 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/268:0:0" width="20" height="20" align="absmiddle" alt="ดูอัลวิปพอนมาสเตอรี่"> ดูอัลวิปพอนมาสเตอรี่ | 10 | 🟢 Passive |  |
| 15006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/100:0:0" width="20" height="20" align="absmiddle" alt="มานาสตอร์ม"> มานาสตอร์ม | 7 | ✨ Buff |  |
| 15012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/167:0:0" width="20" height="20" align="absmiddle" alt="แอคคูเรซี่ออร่า"> แอคคูเรซี่ออร่า | 5 | 💥 AoE |  |
| 15013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/168:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์ออร่า"> ชิลด์ออร่า | 5 | 💥 AoE |  |
| 15014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/169:0:0" width="20" height="20" align="absmiddle" alt="แรมเพจออร่า"> แรมเพจออร่า | 5 | 🩹 Heal |  |
| 15018 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/346:0:0" width="20" height="20" align="absmiddle" alt="มานาแวมไพร์"> มานาแวมไพร์ | 7 | ✨ Buff |  |
| 15019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/78:0:0" width="20" height="20" align="absmiddle" alt="โพรเทคชั่นออร่า"> โพรเทคชั่นออร่า | 3 | 💥 AoE |  |
| 15024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/429:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์ซไวทัล"> รีอินฟอร์ซไวทัล | 10 | 💥 AoE |  |
| 15025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/430:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งไฟท์เตอร์"> เบลสซิ่งไฟท์เตอร์ | 10 | 🔄 Toggle |  |
| 13003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/19:0:0" width="20" height="20" align="absmiddle" alt="เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์"> เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์ | 15 | 🟢 Passive |  |
| 11027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/161:0:0" width="20" height="20" align="absmiddle" alt="รูนอิมแพค"> รูนอิมแพค | 20 | 🔒 CC |  |
| 13011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/14:0:0" width="20" height="20" align="absmiddle" alt="แอกซ์เทรนนิ่ง"> แอกซ์เทรนนิ่ง | 15 | 🟢 Passive |  |
| 13017 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/224:0:0" width="20" height="20" align="absmiddle" alt="แอ็กซ์มอทัลลิตี้"> แอ็กซ์มอทัลลิตี้ | 10 | 🟢 Passive |  |
| 13012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/15:0:0" width="20" height="20" align="absmiddle" alt="เมซเทรนนิ่ง"> เมซเทรนนิ่ง | 20 | 🟢 Passive |  |
| 13018 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/225:0:0" width="20" height="20" align="absmiddle" alt="เมสโพรเทคชั่น"> เมสโพรเทคชั่น | 20 | 🟢 Passive |  |

---

### Elf Fighter

#### 1211 ไฟท์เตอร์ (C1)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 11001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/4:0:0" width="20" height="20" align="absmiddle" alt="แครชโบลว"> แครชโบลว | 5 | ⚔️ Attack |  |
| 11003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/6:0:0" width="20" height="20" align="absmiddle" alt="วินด์สแลชชิ่ง"> วินด์สแลชชิ่ง | 5 | ⚔️ Attack |  |
| 11004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/7:0:0" width="20" height="20" align="absmiddle" alt="สไตรค์แอทแทค"> สไตรค์แอทแทค | 5 | 💀 Debuff |  |
| 11008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/21:0:0" width="20" height="20" align="absmiddle" alt="อัพเปอร์สวิง"> อัพเปอร์สวิง | 5 | 🔒 CC |  |
| 13001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/10:0:0" width="20" height="20" align="absmiddle" alt="วันแฮนด์เทรนนิ่ง"> วันแฮนด์เทรนนิ่ง | 5 | 🟢 Passive |  |
| 13005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/12:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ HP"> เอนฮานซ์ HP | 5 | 🟢 Passive |  |
| 13009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/26:0:0" width="20" height="20" align="absmiddle" alt="ทูแฮนด์เทรนนิ่ง"> ทูแฮนด์เทรนนิ่ง | 5 | 🟢 Passive |  |
| 15001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/9:0:0" width="20" height="20" align="absmiddle" alt="ไฟเตอร์ฮาร์ท"> ไฟเตอร์ฮาร์ท | 1 | ✨ Buff |  |
| 15022 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/427:0:0" width="20" height="20" align="absmiddle" alt="ดีเปรสชั่นสปิน"> ดีเปรสชั่นสปิน | 15 | 💥 AoE |  |
| 15023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/428:0:0" width="20" height="20" align="absmiddle" alt="อินวิซเอเบิ้ลโรป"> อินวิซเอเบิ้ลโรป | 15 | 💥🔒 AoE+CC |  |
| 15024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/429:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์ซไวทัล"> รีอินฟอร์ซไวทัล | 2 | 💥 AoE |  |
| 15025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/430:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งไฟท์เตอร์"> เบลสซิ่งไฟท์เตอร์ | 2 | 🔄 Toggle |  |
| 15026 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/431:0:0" width="20" height="20" align="absmiddle" alt="ออฟเฟนซิฟโพสิชั่น"> ออฟเฟนซิฟโพสิชั่น | 15 | 🟢 Passive |  |
| 15027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/432:0:0" width="20" height="20" align="absmiddle" alt="ดีเฟนซิฟโพสิชั่น"> ดีเฟนซิฟโพสิชั่น | 15 | 🟢 Passive |  |
| 14004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/3:0:0" width="20" height="20" align="absmiddle" alt="เนเจอร์มายด์"> เนเจอร์มายด์ | 2 | 🔄 Toggle |  |
| 14003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/2:0:0" width="20" height="20" align="absmiddle" alt="เนเจอร์ชิลด์"> เนเจอร์ชิลด์ | 2 | 🔄 Toggle |  |

---

#### 1221 การ์ด (C2)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 11003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/6:0:0" width="20" height="20" align="absmiddle" alt="วินด์สแลชชิ่ง"> วินด์สแลชชิ่ง | 10 | ⚔️ Attack |  |
| 11004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/7:0:0" width="20" height="20" align="absmiddle" alt="สไตรค์แอทแทค"> สไตรค์แอทแทค | 10 | 💀 Debuff |  |
| 11005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/8:0:0" width="20" height="20" align="absmiddle" alt="แอทแทรค"> แอทแทรค | 5 | 💀 Debuff |  |
| 11007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/17:0:0" width="20" height="20" align="absmiddle" alt="บลันทชิลด์"> บลันทชิลด์ | 5 | 💥🔒 AoE+CC |  |
| 11013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/81:0:0" width="20" height="20" align="absmiddle" alt="บลัดดี้สกาย"> บลัดดี้สกาย | 5 | 💥🔒 AoE+CC |  |
| 13001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/10:0:0" width="20" height="20" align="absmiddle" alt="วันแฮนด์เทรนนิ่ง"> วันแฮนด์เทรนนิ่ง | 10 | 🟢 Passive |  |
| 13003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/19:0:0" width="20" height="20" align="absmiddle" alt="เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์"> เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์ | 5 | 🟢 Passive |  |
| 13005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/12:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ HP"> เอนฮานซ์ HP | 10 | 🟢 Passive |  |
| 15024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/429:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์ซไวทัล"> รีอินฟอร์ซไวทัล | 4 | 💥 AoE |  |
| 15025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/430:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งไฟท์เตอร์"> เบลสซิ่งไฟท์เตอร์ | 4 | 🔄 Toggle |  |

---

#### 1222 วอร์ริเออร์ (C2)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 11001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/4:0:0" width="20" height="20" align="absmiddle" alt="แครชโบลว"> แครชโบลว | 10 | ⚔️ Attack |  |
| 11008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/21:0:0" width="20" height="20" align="absmiddle" alt="อัพเปอร์สวิง"> อัพเปอร์สวิง | 10 | 🔒 CC |  |
| 11010 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/23:0:0" width="20" height="20" align="absmiddle" alt="บอดี้เช็ค"> บอดี้เช็ค | 5 | 🔒 CC |  |
| 11014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/82:0:0" width="20" height="20" align="absmiddle" alt="วีลวินด์"> วีลวินด์ | 5 | 💥 AoE |  |
| 13009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/26:0:0" width="20" height="20" align="absmiddle" alt="ทูแฮนด์เทรนนิ่ง"> ทูแฮนด์เทรนนิ่ง | 10 | 🟢 Passive |  |
| 13015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/232:0:0" width="20" height="20" align="absmiddle" alt="เรจเบอร์สท์"> เรจเบอร์สท์ | 2 | 🟢 Passive |  |
| 15001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/9:0:0" width="20" height="20" align="absmiddle" alt="ไฟเตอร์ฮาร์ท"> ไฟเตอร์ฮาร์ท | 2 | ✨ Buff |  |
| 15024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/429:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์ซไวทัล"> รีอินฟอร์ซไวทัล | 4 | 💥 AoE |  |
| 15025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/430:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งไฟท์เตอร์"> เบลสซิ่งไฟท์เตอร์ | 4 | 🔄 Toggle |  |
| 13003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/19:0:0" width="20" height="20" align="absmiddle" alt="เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์"> เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์ | 3 | 🟢 Passive |  |

---

#### 1231 อินแฟนทรีแมน (C3)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 11003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/6:0:0" width="20" height="20" align="absmiddle" alt="วินด์สแลชชิ่ง"> วินด์สแลชชิ่ง | 15 | ⚔️ Attack |  |
| 11004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/7:0:0" width="20" height="20" align="absmiddle" alt="สไตรค์แอทแทค"> สไตรค์แอทแทค | 15 | 💀 Debuff |  |
| 11005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/8:0:0" width="20" height="20" align="absmiddle" alt="แอทแทรค"> แอทแทรค | 10 | 💀 Debuff |  |
| 11006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/16:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์เอดจ์"> ชิลด์เอดจ์ | 5 | 💥🔒 AoE+CC |  |
| 11007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/17:0:0" width="20" height="20" align="absmiddle" alt="บลันทชิลด์"> บลันทชิลด์ | 10 | 💥🔒 AoE+CC |  |
| 11013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/81:0:0" width="20" height="20" align="absmiddle" alt="บลัดดี้สกาย"> บลัดดี้สกาย | 10 | 💥🔒 AoE+CC |  |
| 11023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/157:0:0" width="20" height="20" align="absmiddle" alt="ทูมบัสต์"> ทูมบัสต์ | 3 | ✨ Buff |  |
| 13001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/10:0:0" width="20" height="20" align="absmiddle" alt="วันแฮนด์เทรนนิ่ง"> วันแฮนด์เทรนนิ่ง | 15 | 🟢 Passive |  |
| 13003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/19:0:0" width="20" height="20" align="absmiddle" alt="เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์"> เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์ | 10 | 🟢 Passive |  |
| 13005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/12:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ HP"> เอนฮานซ์ HP | 15 | 🟢 Passive |  |
| 11015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/96:0:0" width="20" height="20" align="absmiddle" alt="แอทแทรคเซอร์เคิล"> แอทแทรคเซอร์เคิล | 5 | 💥 AoE |  |
| 15024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/429:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์ซไวทัล"> รีอินฟอร์ซไวทัล | 6 | 💥 AoE |  |
| 15025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/430:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งไฟท์เตอร์"> เบลสซิ่งไฟท์เตอร์ | 6 | 🔄 Toggle |  |

---

#### 1232 ซอร์ดแมน (C3)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 11001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/4:0:0" width="20" height="20" align="absmiddle" alt="แครชโบลว"> แครชโบลว | 15 | ⚔️ Attack |  |
| 11014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/82:0:0" width="20" height="20" align="absmiddle" alt="วีลวินด์"> วีลวินด์ | 10 | 💥 AoE |  |
| 11016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/97:0:0" width="20" height="20" align="absmiddle" alt="โซนิคบูม"> โซนิคบูม | 5 | ⚔️ Attack |  |
| 11018 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/230:0:0" width="20" height="20" align="absmiddle" alt="สปิริตเอด"> สปิริตเอด | 5 | ⚔️ Attack |  |
| 11019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/99:0:0" width="20" height="20" align="absmiddle" alt="ซอร์ดสตอร์ม"> ซอร์ดสตอร์ม | 5 | 💥 AoE |  |
| 13001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/10:0:0" width="20" height="20" align="absmiddle" alt="วันแฮนด์เทรนนิ่ง"> วันแฮนด์เทรนนิ่ง | 15 | 🟢 Passive |  |
| 13009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/26:0:0" width="20" height="20" align="absmiddle" alt="ทูแฮนด์เทรนนิ่ง"> ทูแฮนด์เทรนนิ่ง | 15 | 🟢 Passive |  |
| 13010 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/13:0:0" width="20" height="20" align="absmiddle" alt="ซอร์ดเทรนนิ่ง"> ซอร์ดเทรนนิ่ง | 5 | 🟢 Passive |  |
| 13014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/231:0:0" width="20" height="20" align="absmiddle" alt="ซอร์ดแอคคูเรซี่"> ซอร์ดแอคคูเรซี่ | 5 | 🟢 Passive |  |
| 15001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/9:0:0" width="20" height="20" align="absmiddle" alt="ไฟเตอร์ฮาร์ท"> ไฟเตอร์ฮาร์ท | 3 | ✨ Buff |  |
| 15004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/24:0:0" width="20" height="20" align="absmiddle" alt="วอริเออร์ฟอร์ม"> วอริเออร์ฟอร์ม | 2 | ✨ Buff |  |
| 15006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/100:0:0" width="20" height="20" align="absmiddle" alt="มานาสตอร์ม"> มานาสตอร์ม | 5 | ✨ Buff |  |
| 15024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/429:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์ซไวทัล"> รีอินฟอร์ซไวทัล | 6 | 💥 AoE |  |
| 15025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/430:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งไฟท์เตอร์"> เบลสซิ่งไฟท์เตอร์ | 6 | 🔄 Toggle |  |
| 13003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/19:0:0" width="20" height="20" align="absmiddle" alt="เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์"> เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์ | 7 | 🟢 Passive |  |

---

#### 1233 เมอร์เซนารี (C3)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 11001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/4:0:0" width="20" height="20" align="absmiddle" alt="แครชโบลว"> แครชโบลว | 15 | ⚔️ Attack |  |
| 11008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/21:0:0" width="20" height="20" align="absmiddle" alt="อัพเปอร์สวิง"> อัพเปอร์สวิง | 15 | 🔒 CC |  |
| 11010 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/23:0:0" width="20" height="20" align="absmiddle" alt="บอดี้เช็ค"> บอดี้เช็ค | 10 | 🔒 CC |  |
| 11014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/82:0:0" width="20" height="20" align="absmiddle" alt="วีลวินด์"> วีลวินด์ | 10 | 💥 AoE |  |
| 13009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/26:0:0" width="20" height="20" align="absmiddle" alt="ทูแฮนด์เทรนนิ่ง"> ทูแฮนด์เทรนนิ่ง | 15 | 🟢 Passive |  |
| 13010 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/13:0:0" width="20" height="20" align="absmiddle" alt="ซอร์ดเทรนนิ่ง"> ซอร์ดเทรนนิ่ง | 5 | 🟢 Passive |  |
| 13011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/14:0:0" width="20" height="20" align="absmiddle" alt="แอกซ์เทรนนิ่ง"> แอกซ์เทรนนิ่ง | 5 | 🟢 Passive |  |
| 13012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/15:0:0" width="20" height="20" align="absmiddle" alt="เมซเทรนนิ่ง"> เมซเทรนนิ่ง | 5 | 🟢 Passive |  |
| 13015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/232:0:0" width="20" height="20" align="absmiddle" alt="เรจเบอร์สท์"> เรจเบอร์สท์ | 4 | 🟢 Passive |  |
| 15001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/9:0:0" width="20" height="20" align="absmiddle" alt="ไฟเตอร์ฮาร์ท"> ไฟเตอร์ฮาร์ท | 4 | ✨ Buff |  |
| 15024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/429:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์ซไวทัล"> รีอินฟอร์ซไวทัล | 6 | 💥 AoE |  |
| 15025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/430:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งไฟท์เตอร์"> เบลสซิ่งไฟท์เตอร์ | 6 | 🔄 Toggle |  |
| 13003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/19:0:0" width="20" height="20" align="absmiddle" alt="เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์"> เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์ | 7 | 🟢 Passive |  |

---

#### 1241 ฟาแลงซ์ (C4)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 11005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/8:0:0" width="20" height="20" align="absmiddle" alt="แอทแทรค"> แอทแทรค | 15 | 💀 Debuff |  |
| 11006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/16:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์เอดจ์"> ชิลด์เอดจ์ | 10 | 💥🔒 AoE+CC |  |
| 11007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/17:0:0" width="20" height="20" align="absmiddle" alt="บลันทชิลด์"> บลันทชิลด์ | 15 | 💥🔒 AoE+CC |  |
| 11015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/96:0:0" width="20" height="20" align="absmiddle" alt="แอทแทรคเซอร์เคิล"> แอทแทรคเซอร์เคิล | 10 | 💥 AoE |  |
| 11023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/157:0:0" width="20" height="20" align="absmiddle" alt="ทูมบัสต์"> ทูมบัสต์ | 6 | ✨ Buff |  |
| 11028 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/226:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่อาเวนเจอร์"> โฮลี่อาเวนเจอร์ | 10 | 💥🔒 AoE+CC |  |
| 11029 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/5:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่สโตรค"> โฮลี่สโตรค | 10 | 💀 Debuff |  |
| 13003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/19:0:0" width="20" height="20" align="absmiddle" alt="เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์"> เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์ | 15 | 🟢 Passive |  |
| 13005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/12:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ HP"> เอนฮานซ์ HP | 20 | 🟢 Passive |  |
| 13019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/170:0:0" width="20" height="20" align="absmiddle" alt="รีแลกเซชั่น"> รีแลกเซชั่น | 1 | 💥 AoE |  |
| 15005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/94:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์แบริเออร์"> ชิลด์แบริเออร์ | 2 | 🔒 CC |  |
| 15007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/162:0:0" width="20" height="20" align="absmiddle" alt="โซลิดชิลด์"> โซลิดชิลด์ | 1 | ✨ Buff |  |
| 15024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/429:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์ซไวทัล"> รีอินฟอร์ซไวทัล | 8 | 💥 AoE |  |
| 15025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/430:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งไฟท์เตอร์"> เบลสซิ่งไฟท์เตอร์ | 8 | 🔄 Toggle |  |
| 11004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/7:0:0" width="20" height="20" align="absmiddle" alt="สไตรค์แอทแทค"> สไตรค์แอทแทค | 30 | 💀 Debuff |  |
| 15003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/18:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งการ์ด"> เบลสซิ่งการ์ด | 5 | ✨ Buff |  |
| 33007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/78:0:0" width="20" height="20" align="absmiddle" alt="เมจิคแบริเออร์"> เมจิคแบริเออร์ | 10 | 🟢 Passive |  |
| 13012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/15:0:0" width="20" height="20" align="absmiddle" alt="เมซเทรนนิ่ง"> เมซเทรนนิ่ง | 10 | 🟢 Passive |  |
| 13018 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/225:0:0" width="20" height="20" align="absmiddle" alt="เมสโพรเทคชั่น"> เมสโพรเทคชั่น | 10 | 🟢 Passive |  |
| 13004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/20:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์เทรนนิ่ง"> ชิลด์เทรนนิ่ง | 10 | 🟢 Passive |  |
| 15008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/163:0:0" width="20" height="20" align="absmiddle" alt="อินวัลเนอเรเบิล"> อินวัลเนอเรเบิล | 1 | 🔒 CC |  |
| 13013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/229:0:0" width="20" height="20" align="absmiddle" alt="ทรูเปอร์ชิป"> ทรูเปอร์ชิป | 4 | 🟢 Passive |  |
| 11003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/6:0:0" width="20" height="20" align="absmiddle" alt="วินด์สแลชชิ่ง"> วินด์สแลชชิ่ง | 20 | ⚔️ Attack |  |

---

#### 1242 ไนท์ (C4)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 11003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/6:0:0" width="20" height="20" align="absmiddle" alt="วินด์สแลชชิ่ง"> วินด์สแลชชิ่ง | 30 | ⚔️ Attack |  |
| 11004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/7:0:0" width="20" height="20" align="absmiddle" alt="สไตรค์แอทแทค"> สไตรค์แอทแทค | 30 | 💀 Debuff |  |
| 11005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/8:0:0" width="20" height="20" align="absmiddle" alt="แอทแทรค"> แอทแทรค | 10 | 💀 Debuff |  |
| 11006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/16:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์เอดจ์"> ชิลด์เอดจ์ | 10 | 💥🔒 AoE+CC |  |
| 11013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/81:0:0" width="20" height="20" align="absmiddle" alt="บลัดดี้สกาย"> บลัดดี้สกาย | 30 | 💥🔒 AoE+CC |  |
| 11015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/96:0:0" width="20" height="20" align="absmiddle" alt="แอทแทรคเซอร์เคิล"> แอทแทรคเซอร์เคิล | 5 | 💥 AoE |  |
| 11023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/157:0:0" width="20" height="20" align="absmiddle" alt="ทูมบัสต์"> ทูมบัสต์ | 5 | ✨ Buff |  |
| 13001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/10:0:0" width="20" height="20" align="absmiddle" alt="วันแฮนด์เทรนนิ่ง"> วันแฮนด์เทรนนิ่ง | 20 | 🟢 Passive |  |
| 13003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/19:0:0" width="20" height="20" align="absmiddle" alt="เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์"> เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์ | 15 | 🟢 Passive |  |
| 13010 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/13:0:0" width="20" height="20" align="absmiddle" alt="ซอร์ดเทรนนิ่ง"> ซอร์ดเทรนนิ่ง | 10 | 🟢 Passive |  |
| 13011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/14:0:0" width="20" height="20" align="absmiddle" alt="แอกซ์เทรนนิ่ง"> แอกซ์เทรนนิ่ง | 10 | 🟢 Passive |  |
| 13012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/15:0:0" width="20" height="20" align="absmiddle" alt="เมซเทรนนิ่ง"> เมซเทรนนิ่ง | 10 | 🟢 Passive |  |
| 15005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/94:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์แบริเออร์"> ชิลด์แบริเออร์ | 1 | 🔒 CC |  |
| 15009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/164:0:0" width="20" height="20" align="absmiddle" alt="โซลิดวิพพอน"> โซลิดวิพพอน | 2 | ✨ Buff |  |
| 15024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/429:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์ซไวทัล"> รีอินฟอร์ซไวทัล | 8 | 💥 AoE |  |
| 15025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/430:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งไฟท์เตอร์"> เบลสซิ่งไฟท์เตอร์ | 8 | 🔄 Toggle |  |
| 11016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/97:0:0" width="20" height="20" align="absmiddle" alt="โซนิคบูม"> โซนิคบูม | 15 | ⚔️ Attack |  |
| 11019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/99:0:0" width="20" height="20" align="absmiddle" alt="ซอร์ดสตอร์ม"> ซอร์ดสตอร์ม | 15 | 💥 AoE |  |
| 13009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/26:0:0" width="20" height="20" align="absmiddle" alt="ทูแฮนด์เทรนนิ่ง"> ทูแฮนด์เทรนนิ่ง | 20 | 🟢 Passive |  |

---

#### 1243 กลาดิเอเตอร์ (C4)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 11001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/4:0:0" width="20" height="20" align="absmiddle" alt="แครชโบลว"> แครชโบลว | 25 | ⚔️ Attack |  |
| 11008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/21:0:0" width="20" height="20" align="absmiddle" alt="อัพเปอร์สวิง"> อัพเปอร์สวิง | 25 | 🔒 CC |  |
| 11014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/82:0:0" width="20" height="20" align="absmiddle" alt="วีลวินด์"> วีลวินด์ | 15 | 💥 AoE |  |
| 11024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/158:0:0" width="20" height="20" align="absmiddle" alt="เฟลมสแมช"> เฟลมสแมช | 20 | 💀 Debuff |  |
| 11025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/159:0:0" width="20" height="20" align="absmiddle" alt="เอิร์ธเวฟ"> เอิร์ธเวฟ | 20 | 💀 Debuff |  |
| 13009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/26:0:0" width="20" height="20" align="absmiddle" alt="ทูแฮนด์เทรนนิ่ง"> ทูแฮนด์เทรนนิ่ง | 20 | 🟢 Passive |  |
| 13010 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/13:0:0" width="20" height="20" align="absmiddle" alt="ซอร์ดเทรนนิ่ง"> ซอร์ดเทรนนิ่ง | 10 | 🟢 Passive |  |
| 13011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/14:0:0" width="20" height="20" align="absmiddle" alt="แอกซ์เทรนนิ่ง"> แอกซ์เทรนนิ่ง | 10 | 🟢 Passive |  |
| 13012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/15:0:0" width="20" height="20" align="absmiddle" alt="เมซเทรนนิ่ง"> เมซเทรนนิ่ง | 10 | 🟢 Passive |  |
| 13015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/232:0:0" width="20" height="20" align="absmiddle" alt="เรจเบอร์สท์"> เรจเบอร์สท์ | 6 | 🟢 Passive |  |
| 15001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/9:0:0" width="20" height="20" align="absmiddle" alt="ไฟเตอร์ฮาร์ท"> ไฟเตอร์ฮาร์ท | 6 | ✨ Buff |  |
| 15024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/429:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์ซไวทัล"> รีอินฟอร์ซไวทัล | 8 | 💥 AoE |  |
| 15025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/430:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งไฟท์เตอร์"> เบลสซิ่งไฟท์เตอร์ | 8 | 🔄 Toggle |  |
| 13003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/19:0:0" width="20" height="20" align="absmiddle" alt="เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์"> เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์ | 10 | 🟢 Passive |  |
| 15011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/166:0:0" width="20" height="20" align="absmiddle" alt="เบอร์เซอเคอร์"> เบอร์เซอเคอร์ | 1 | 🩹 Heal |  |

---

#### 1244 รูนไนท์ (C4)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 11001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/4:0:0" width="20" height="20" align="absmiddle" alt="แครชโบลว"> แครชโบลว | 15 | ⚔️ Attack |  |
| 11014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/82:0:0" width="20" height="20" align="absmiddle" alt="วีลวินด์"> วีลวินด์ | 15 | 💥 AoE |  |
| 11016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/97:0:0" width="20" height="20" align="absmiddle" alt="โซนิคบูม"> โซนิคบูม | 10 | ⚔️ Attack |  |
| 11018 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/230:0:0" width="20" height="20" align="absmiddle" alt="สปิริตเอด"> สปิริตเอด | 10 | ⚔️ Attack |  |
| 11019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/99:0:0" width="20" height="20" align="absmiddle" alt="ซอร์ดสตอร์ม"> ซอร์ดสตอร์ม | 10 | 💥 AoE |  |
| 11025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/159:0:0" width="20" height="20" align="absmiddle" alt="เอิร์ธเวฟ"> เอิร์ธเวฟ | 10 | 💀 Debuff |  |
| 13009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/26:0:0" width="20" height="20" align="absmiddle" alt="ทูแฮนด์เทรนนิ่ง"> ทูแฮนด์เทรนนิ่ง | 20 | 🟢 Passive |  |
| 15001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/9:0:0" width="20" height="20" align="absmiddle" alt="ไฟเตอร์ฮาร์ท"> ไฟเตอร์ฮาร์ท | 5 | ✨ Buff |  |
| 15004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/24:0:0" width="20" height="20" align="absmiddle" alt="วอริเออร์ฟอร์ม"> วอริเออร์ฟอร์ม | 4 | ✨ Buff |  |
| 15006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/100:0:0" width="20" height="20" align="absmiddle" alt="มานาสตอร์ม"> มานาสตอร์ม | 7 | ✨ Buff |  |
| 15012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/167:0:0" width="20" height="20" align="absmiddle" alt="แอคคูเรซี่ออร่า"> แอคคูเรซี่ออร่า | 2 | 💥 AoE |  |
| 15013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/168:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์ออร่า"> ชิลด์ออร่า | 2 | 💥 AoE |  |
| 15014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/169:0:0" width="20" height="20" align="absmiddle" alt="แรมเพจออร่า"> แรมเพจออร่า | 2 | 🩹 Heal |  |
| 15024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/429:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์ซไวทัล"> รีอินฟอร์ซไวทัล | 8 | 💥 AoE |  |
| 15025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/430:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งไฟท์เตอร์"> เบลสซิ่งไฟท์เตอร์ | 8 | 🔄 Toggle |  |
| 13003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/19:0:0" width="20" height="20" align="absmiddle" alt="เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์"> เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์ | 10 | 🟢 Passive |  |
| 11027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/161:0:0" width="20" height="20" align="absmiddle" alt="รูนอิมแพค"> รูนอิมแพค | 15 | 🔒 CC |  |
| 11017 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/98:0:0" width="20" height="20" align="absmiddle" alt="สปิริตซอร์ด"> สปิริตซอร์ด | 20 | 🔒 CC |  |
| 13001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/10:0:0" width="20" height="20" align="absmiddle" alt="วันแฮนด์เทรนนิ่ง"> วันแฮนด์เทรนนิ่ง | 20 | 🟢 Passive |  |
| 13004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/20:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์เทรนนิ่ง"> ชิลด์เทรนนิ่ง | 10 | 🟢 Passive |  |
| 14004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/3:0:0" width="20" height="20" align="absmiddle" alt="เนเจอร์มายด์"> เนเจอร์มายด์ | 2 | 🔄 Toggle |  |
| 14003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/2:0:0" width="20" height="20" align="absmiddle" alt="เนเจอร์ชิลด์"> เนเจอร์ชิลด์ | 2 | 🔄 Toggle |  |
| 13001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/10:0:0" width="20" height="20" align="absmiddle" alt="วันแฮนด์เทรนนิ่ง"> วันแฮนด์เทรนนิ่ง | 20 | 🟢 Passive |  |
| 15019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/78:0:0" width="20" height="20" align="absmiddle" alt="โพรเทคชั่นออร่า"> โพรเทคชั่นออร่า | 2 | 💥 AoE |  |

---

#### 1251 พาลาดิน (C5)

> 🟡 **Overall: 80.2**/100 · DMG `81` · AoE `95` · CC `100` · Util `75` · Surv `56`

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 11005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/8:0:0" width="20" height="20" align="absmiddle" alt="แอทแทรค"> แอทแทรค | 30 | 💀 Debuff |  |
| 11006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/16:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์เอดจ์"> ชิลด์เอดจ์ | 30 | 💥🔒 AoE+CC |  |
| 11015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/96:0:0" width="20" height="20" align="absmiddle" alt="แอทแทรคเซอร์เคิล"> แอทแทรคเซอร์เคิล | 30 | 💥 AoE |  |
| 11023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/157:0:0" width="20" height="20" align="absmiddle" alt="ทูมบัสต์"> ทูมบัสต์ | 9 | ✨ Buff |  |
| 11032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/230:0:0" width="20" height="20" align="absmiddle" alt="เซ้นต์ฮีล"> เซ้นต์ฮีล | 5 | 💥 AoE |  |
| 13003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/19:0:0" width="20" height="20" align="absmiddle" alt="เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์"> เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์ | 20 | 🟢 Passive |  |
| 13019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/170:0:0" width="20" height="20" align="absmiddle" alt="รีแลกเซชั่น"> รีแลกเซชั่น | 1 | 💥 AoE |  |
| 15005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/94:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์แบริเออร์"> ชิลด์แบริเออร์ | 4 | 🔒 CC |  |
| 15007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/162:0:0" width="20" height="20" align="absmiddle" alt="โซลิดชิลด์"> โซลิดชิลด์ | 5 | ✨ Buff |  |
| 15024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/429:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์ซไวทัล"> รีอินฟอร์ซไวทัล | 10 | 💥 AoE |  |
| 15025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/430:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งไฟท์เตอร์"> เบลสซิ่งไฟท์เตอร์ | 10 | 🔄 Toggle |  |
| 11007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/17:0:0" width="20" height="20" align="absmiddle" alt="บลันทชิลด์"> บลันทชิลด์ | 30 | 💥🔒 AoE+CC |  |
| 13018 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/225:0:0" width="20" height="20" align="absmiddle" alt="เมสโพรเทคชั่น"> เมสโพรเทคชั่น | 20 | 🟢 Passive |  |
| 11022 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/156:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์ชาร์จจิ้ง"> ชิลด์ชาร์จจิ้ง | 30 | 🔒 CC |  |
| 13004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/20:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์เทรนนิ่ง"> ชิลด์เทรนนิ่ง | 20 | 🟢 Passive |  |
| 13012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/15:0:0" width="20" height="20" align="absmiddle" alt="เมซเทรนนิ่ง"> เมซเทรนนิ่ง | 20 | 🟢 Passive |  |
| 15003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/18:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งการ์ด"> เบลสซิ่งการ์ด | 10 | ✨ Buff |  |
| 15015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/162:0:0" width="20" height="20" align="absmiddle" alt="ไอรอนชิลด์"> ไอรอนชิลด์ | 2 | ✨ Buff |  |
| 13001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/10:0:0" width="20" height="20" align="absmiddle" alt="วันแฮนด์เทรนนิ่ง"> วันแฮนด์เทรนนิ่ง | 20 | 🟢 Passive |  |

<details><summary>⚠️ <strong>คำแนะนำการปรับสมดุล (2 รายการ)</strong></summary>

| # | ประเภท | มิติ | รายละเอียด | ไฟล์ที่แก้ | Gap |
|---|--------|------|----------|------------|-----|
| 1 | 🔧 ปรับ | Survivability | 🛡️ ปรับค่า fStatusDataMul สกิลบัฟ/ฮีล (×1.3-1.5) | `Skill_Buff_List.bin.txt` | 9.0 |
| 2 | 🔧 ปรับ | Damage | ⚔️ ปรับค่า fUnitDataValueMul สกิลโจมตี (×1.2-1.5) | `SkillScript.bin.txt` | 14.0 |

</details>

---

#### 1252 แพนเซอร์ (C5)

> 🟡 **Overall: 87.3**/100 · DMG `95` · AoE `65` · CC `84` · Util `99` · Surv `90`

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 11044 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/271:0:0" width="20" height="20" align="absmiddle" alt="สแตนดิ้งไฟร์"> สแตนดิ้งไฟร์ | 20 | 💀 Debuff |  |
| 11045 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/246:0:0" width="20" height="20" align="absmiddle" alt="ไอรอนบอมบ์"> ไอรอนบอมบ์ | 20 | 💥 AoE |  |
| 11046 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/272:0:0" width="20" height="20" align="absmiddle" alt="นิลลิ่งช๊อต"> นิลลิ่งช๊อต | 20 | 🔒 CC |  |
| 11047 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/273:0:0" width="20" height="20" align="absmiddle" alt="มัสเกทพร๊อกซิมิตี้"> มัสเกทพร๊อกซิมิตี้ | 20 | 🔒 CC |  |
| 11048 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/354:0:0" width="20" height="20" align="absmiddle" alt="มัสเกทโบลว"> มัสเกทโบลว | 20 | 💀 Debuff |  |
| 13003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/19:0:0" width="20" height="20" align="absmiddle" alt="เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์"> เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์ | 15 | 🟢 Passive |  |
| 13024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/356:0:0" width="20" height="20" align="absmiddle" alt="มัสเกทแอคคูเรซี่"> มัสเกทแอคคูเรซี่ | 10 | 🟢 Passive |  |
| 13025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/357:0:0" width="20" height="20" align="absmiddle" alt="มัสเกทเทรนนิ่ง"> มัสเกทเทรนนิ่ง | 20 | 🟢 Passive |  |
| 15009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/164:0:0" width="20" height="20" align="absmiddle" alt="โซลิดวิพพอน"> โซลิดวิพพอน | 5 | ✨ Buff |  |
| 15020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/355:0:0" width="20" height="20" align="absmiddle" alt="รีโหลดดิ้ง"> รีโหลดดิ้ง | 5 | 🩹 Heal |  |
| 15024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/429:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์ซไวทัล"> รีอินฟอร์ซไวทัล | 10 | 💥 AoE |  |
| 15025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/430:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งไฟท์เตอร์"> เบลสซิ่งไฟท์เตอร์ | 10 | 🔄 Toggle |  |
| 23013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/358:0:0" width="20" height="20" align="absmiddle" alt="มัสเกทเรนจ์"> มัสเกทเรนจ์ | 5 | 🟢 Passive |  |
| 13015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/232:0:0" width="20" height="20" align="absmiddle" alt="เรจเบอร์สท์"> เรจเบอร์สท์ | 8 | 🟢 Passive |  |
| 15017 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/345:0:0" width="20" height="20" align="absmiddle" alt="เฟทัลฟอร์ซ"> เฟทัลฟอร์ซ | 3 | ✨ Buff |  |
| 13020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/171:0:0" width="20" height="20" align="absmiddle" alt="อาร์มเมอร์ซิงโคร"> อาร์มเมอร์ซิงโคร | 3 | ✨ Buff |  |
| 13021 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/172:0:0" width="20" height="20" align="absmiddle" alt="วิพพอนซิงโคร"> วิพพอนซิงโคร | 3 | 🩹 Heal |  |
| 25014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/276:0:0" width="20" height="20" align="absmiddle" alt="มัสเกทสโคป"> มัสเกทสโคป | 10 | ✨ Buff |  |

<details><summary>⚠️ <strong>คำแนะนำการปรับสมดุล (1 รายการ)</strong></summary>

| # | ประเภท | มิติ | รายละเอียด | ไฟล์ที่แก้ | Gap |
|---|--------|------|----------|------------|-----|
| 1 | ➕ เพิ่ม | AoE | 💥 เพิ่มสกิล AoE อีก 1 ตัว (มี 1, ควรมี 3+) | `Skill_Get_List.bin.txt` | 15.0 |

</details>

---

#### 1253 ครูเสเดอร์ (C5)

> 🟡 **Overall: 83.2**/100 · DMG `100` · AoE `100` · CC `100` · Util `75` · Surv `42`

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 11029 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/5:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่สโตรค"> โฮลี่สโตรค | 30 | 💀 Debuff |  |
| 11030 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/348:0:0" width="20" height="20" align="absmiddle" alt="เรจซอร์ด"> เรจซอร์ด | 20 | 💀 Debuff |  |
| 11031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/8:0:0" width="20" height="20" align="absmiddle" alt="เซ้นต์แช็คเกิ้ล"> เซ้นต์แช็คเกิ้ล | 30 | 💥🔒 AoE+CC |  |
| 11033 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/353:0:0" width="20" height="20" align="absmiddle" alt="ช๊อคเวฟ"> ช๊อคเวฟ | 10 | 💥🔒 AoE+CC |  |
| 11034 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/347:0:0" width="20" height="20" align="absmiddle" alt="ดาร์คอิลูชั่น"> ดาร์คอิลูชั่น | 10 | 🔒 CC |  |
| 11035 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/350:0:0" width="20" height="20" align="absmiddle" alt="ธันเดอร์ออฟเดธ"> ธันเดอร์ออฟเดธ | 20 | 💥🔒 AoE+CC |  |
| 15006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/100:0:0" width="20" height="20" align="absmiddle" alt="มานาสตอร์ม"> มานาสตอร์ม | 10 | ✨ Buff |  |
| 15016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/349:0:0" width="20" height="20" align="absmiddle" alt="เมนทัลเวอร์เทกซ์"> เมนทัลเวอร์เทกซ์ | 10 | ✨ Buff |  |
| 13020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/171:0:0" width="20" height="20" align="absmiddle" alt="อาร์มเมอร์ซิงโคร"> อาร์มเมอร์ซิงโคร | 3 | ✨ Buff |  |
| 35027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/122:0:0" width="20" height="20" align="absmiddle" alt="มานาออร่า"> มานาออร่า | 5 | 🔄 Toggle |  |
| 15024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/429:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์ซไวทัล"> รีอินฟอร์ซไวทัล | 10 | 💥 AoE |  |
| 15025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/430:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งไฟท์เตอร์"> เบลสซิ่งไฟท์เตอร์ | 10 | 🔄 Toggle |  |
| 13003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/19:0:0" width="20" height="20" align="absmiddle" alt="เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์"> เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์ | 15 | 🟢 Passive |  |
| 13012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/15:0:0" width="20" height="20" align="absmiddle" alt="เมซเทรนนิ่ง"> เมซเทรนนิ่ง | 20 | 🟢 Passive |  |
| 33002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/60:0:0" width="20" height="20" align="absmiddle" alt="โร๊บเอ็กซเพอร์ไทซ์"> โร๊บเอ็กซเพอร์ไทซ์ | 20 | 🟢 Passive |  |
| 11028 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/226:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่อาเวนเจอร์"> โฮลี่อาเวนเจอร์ | 20 | 💥🔒 AoE+CC |  |
| 11029 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/5:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่สโตรค"> โฮลี่สโตรค | 15 | 💀 Debuff |  |
| 35023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/234:0:0" width="20" height="20" align="absmiddle" alt="ทวิงเกิ้ลเมจิก"> ทวิงเกิ้ลเมจิก | 8 | ✨ Buff |  |

<details><summary>⚠️ <strong>คำแนะนำการปรับสมดุล (1 รายการ)</strong></summary>

| # | ประเภท | มิติ | รายละเอียด | ไฟล์ที่แก้ | Gap |
|---|--------|------|----------|------------|-----|
| 1 | 🔧 ปรับ | Survivability | 🛡️ ปรับค่า fStatusDataMul สกิลบัฟ/ฮีล (×1.3-1.5) | `Skill_Buff_List.bin.txt` | 23.0 |

</details>

---

#### 1254 เดสทรอยเยอร์ (C5)

> 🟢 **Overall: 92.5**/100 · DMG `100` · AoE `80` · CC `86` · Util `90` · Surv `100`

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 11014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/82:0:0" width="20" height="20" align="absmiddle" alt="วีลวินด์"> วีลวินด์ | 20 | 💥 AoE |  |
| 11024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/158:0:0" width="20" height="20" align="absmiddle" alt="เฟลมสแมช"> เฟลมสแมช | 15 | 💀 Debuff |  |
| 11025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/159:0:0" width="20" height="20" align="absmiddle" alt="เอิร์ธเวฟ"> เอิร์ธเวฟ | 30 | 💀 Debuff |  |
| 11037 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/341:0:0" width="20" height="20" align="absmiddle" alt="ครูเอลซอร์ด"> ครูเอลซอร์ด | 10 | 🔒 CC |  |
| 13009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/26:0:0" width="20" height="20" align="absmiddle" alt="ทูแฮนด์เทรนนิ่ง"> ทูแฮนด์เทรนนิ่ง | 20 | 🟢 Passive |  |
| 13010 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/13:0:0" width="20" height="20" align="absmiddle" alt="ซอร์ดเทรนนิ่ง"> ซอร์ดเทรนนิ่ง | 15 | 🟢 Passive |  |
| 13011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/14:0:0" width="20" height="20" align="absmiddle" alt="แอกซ์เทรนนิ่ง"> แอกซ์เทรนนิ่ง | 15 | 🟢 Passive |  |
| 13012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/15:0:0" width="20" height="20" align="absmiddle" alt="เมซเทรนนิ่ง"> เมซเทรนนิ่ง | 15 | 🟢 Passive |  |
| 13014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/231:0:0" width="20" height="20" align="absmiddle" alt="ซอร์ดแอคคูเรซี่"> ซอร์ดแอคคูเรซี่ | 10 | 🟢 Passive |  |
| 13015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/232:0:0" width="20" height="20" align="absmiddle" alt="เรจเบอร์สท์"> เรจเบอร์สท์ | 8 | 🟢 Passive |  |
| 13017 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/224:0:0" width="20" height="20" align="absmiddle" alt="แอ็กซ์มอทัลลิตี้"> แอ็กซ์มอทัลลิตี้ | 10 | 🟢 Passive |  |
| 13018 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/225:0:0" width="20" height="20" align="absmiddle" alt="เมสโพรเทคชั่น"> เมสโพรเทคชั่น | 10 | 🟢 Passive |  |
| 15001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/9:0:0" width="20" height="20" align="absmiddle" alt="ไฟเตอร์ฮาร์ท"> ไฟเตอร์ฮาร์ท | 8 | ✨ Buff |  |
| 15024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/429:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์ซไวทัล"> รีอินฟอร์ซไวทัล | 10 | 💥 AoE |  |
| 15025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/430:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งไฟท์เตอร์"> เบลสซิ่งไฟท์เตอร์ | 10 | 🔄 Toggle |  |
| 13003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/19:0:0" width="20" height="20" align="absmiddle" alt="เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์"> เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์ | 15 | 🟢 Passive |  |
| 11036 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/351:0:0" width="20" height="20" align="absmiddle" alt="เฟียร์ฟูลโบลว"> เฟียร์ฟูลโบลว | 30 | 💥🔒 AoE+CC |  |
| 15011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/166:0:0" width="20" height="20" align="absmiddle" alt="เบอร์เซอเคอร์"> เบอร์เซอเคอร์ | 3 | 🩹 Heal |  |
| 11001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/4:0:0" width="20" height="20" align="absmiddle" alt="แครชโบลว"> แครชโบลว | 30 | ⚔️ Attack |  |
| 11008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/21:0:0" width="20" height="20" align="absmiddle" alt="อัพเปอร์สวิง"> อัพเปอร์สวิง | 30 | 🔒 CC |  |
| 13020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/171:0:0" width="20" height="20" align="absmiddle" alt="อาร์มเมอร์ซิงโคร"> อาร์มเมอร์ซิงโคร | 3 | ✨ Buff |  |
| 13021 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/172:0:0" width="20" height="20" align="absmiddle" alt="วิพพอนซิงโคร"> วิพพอนซิงโคร | 3 | 🩹 Heal |  |
| 13008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/227:0:0" width="20" height="20" align="absmiddle" alt="ริสกี้เทคเกอร์"> ริสกี้เทคเกอร์ | 8 | 🟢 Passive |  |

> ✅ **สมดุลดี** — ไม่มีข้อแนะนำเพิ่มเติม

---

#### 1255 ซอร์ดมาสเตอร์ (C5)

> 🟡 **Overall: 82.2**/100 · DMG `100` · AoE `80` · CC `54` · Util `84` · Surv `83`

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 11016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/97:0:0" width="20" height="20" align="absmiddle" alt="โซนิคบูม"> โซนิคบูม | 20 | ⚔️ Attack |  |
| 11019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/99:0:0" width="20" height="20" align="absmiddle" alt="ซอร์ดสตอร์ม"> ซอร์ดสตอร์ม | 30 | 💥 AoE |  |
| 11040 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/342:0:0" width="20" height="20" align="absmiddle" alt="ดูอัลโซนิคบูม"> ดูอัลโซนิคบูม | 10 | ⚔️ Attack |  |
| 11041 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/82:0:0" width="20" height="20" align="absmiddle" alt="ซอร์ดสปิน"> ซอร์ดสปิน | 10 | 💥 AoE |  |
| 11042 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/344:0:0" width="20" height="20" align="absmiddle" alt="ดูอัลโบลว"> ดูอัลโบลว | 10 | ⚔️ Attack |  |
| 13010 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/13:0:0" width="20" height="20" align="absmiddle" alt="ซอร์ดเทรนนิ่ง"> ซอร์ดเทรนนิ่ง | 15 | 🟢 Passive |  |
| 13014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/231:0:0" width="20" height="20" align="absmiddle" alt="ซอร์ดแอคคูเรซี่"> ซอร์ดแอคคูเรซี่ | 10 | 🟢 Passive |  |
| 13022 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/267:0:0" width="20" height="20" align="absmiddle" alt="ดูอัลวิปพอนเทรนนิ่ง"> ดูอัลวิปพอนเทรนนิ่ง | 10 | 🟢 Passive |  |
| 13026 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/268:0:0" width="20" height="20" align="absmiddle" alt="ดูอัลวิปพอนมาสเตอรี่"> ดูอัลวิปพอนมาสเตอรี่ | 10 | 🟢 Passive |  |
| 15001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/9:0:0" width="20" height="20" align="absmiddle" alt="ไฟเตอร์ฮาร์ท"> ไฟเตอร์ฮาร์ท | 7 | ✨ Buff |  |
| 15004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/24:0:0" width="20" height="20" align="absmiddle" alt="วอริเออร์ฟอร์ม"> วอริเออร์ฟอร์ม | 8 | ✨ Buff |  |
| 15024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/429:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์ซไวทัล"> รีอินฟอร์ซไวทัล | 10 | 💥 AoE |  |
| 15025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/430:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งไฟท์เตอร์"> เบลสซิ่งไฟท์เตอร์ | 10 | 🔄 Toggle |  |
| 13003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/19:0:0" width="20" height="20" align="absmiddle" alt="เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์"> เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์ | 15 | 🟢 Passive |  |
| 13016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/111:0:0" width="20" height="20" align="absmiddle" alt="ซอร์ดเรพิดิตี้"> ซอร์ดเรพิดิตี้ | 10 | 🟢 Passive |  |
| 15011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/166:0:0" width="20" height="20" align="absmiddle" alt="เบอร์เซอเคอร์"> เบอร์เซอเคอร์ | 3 | 🩹 Heal |  |
| 11001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/4:0:0" width="20" height="20" align="absmiddle" alt="แครชโบลว"> แครชโบลว | 30 | ⚔️ Attack |  |
| 11008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/21:0:0" width="20" height="20" align="absmiddle" alt="อัพเปอร์สวิง"> อัพเปอร์สวิง | 30 | 🔒 CC |  |
| 13023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/15:0:0" width="20" height="20" align="absmiddle" alt="ดูอัลวิปพอร์นแอคคูเรซี่"> ดูอัลวิปพอร์นแอคคูเรซี่ | 10 | 🟢 Passive |  |
| 15017 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/345:0:0" width="20" height="20" align="absmiddle" alt="เฟทัลฟอร์ซ"> เฟทัลฟอร์ซ | 3 | ✨ Buff |  |
| 11002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/5:0:0" width="20" height="20" align="absmiddle" alt="บลัดดิ้งโบลว"> บลัดดิ้งโบลว | 30 | 💀 Debuff |  |
| 11037 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/341:0:0" width="20" height="20" align="absmiddle" alt="ครูเอลซอร์ด"> ครูเอลซอร์ด | 20 | 🔒 CC |  |
| 11039 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/343:0:0" width="20" height="20" align="absmiddle" alt="เฟียร์ฟูลมาซาเคอร์"> เฟียร์ฟูลมาซาเคอร์ | 20 | 💀 Debuff |  |

<details><summary>⚠️ <strong>คำแนะนำการปรับสมดุล (1 รายการ)</strong></summary>

| # | ประเภท | มิติ | รายละเอียด | ไฟล์ที่แก้ | Gap |
|---|--------|------|----------|------------|-----|
| 1 | ➕ เพิ่ม | CC | 🔒 เพิ่มสกิล CC อีก 1 ตัว (มี 2) | `Skill_Get_List / Skill_Buff_List` | 21.0 |

</details>

---

#### 1256 แม็กเนอร์ส (C5)

> 🔴 **Overall: 77.6**/100 · DMG `95` · AoE `65` · CC `48` · Util `87` · Surv `83`

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 11016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/97:0:0" width="20" height="20" align="absmiddle" alt="โซนิคบูม"> โซนิคบูม | 20 | ⚔️ Attack |  |
| 11019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/99:0:0" width="20" height="20" align="absmiddle" alt="ซอร์ดสตอร์ม"> ซอร์ดสตอร์ม | 30 | 💥 AoE |  |
| 11040 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/342:0:0" width="20" height="20" align="absmiddle" alt="ดูอัลโซนิคบูม"> ดูอัลโซนิคบูม | 10 | ⚔️ Attack |  |
| 11042 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/344:0:0" width="20" height="20" align="absmiddle" alt="ดูอัลโบลว"> ดูอัลโบลว | 10 | ⚔️ Attack |  |
| 13022 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/267:0:0" width="20" height="20" align="absmiddle" alt="ดูอัลวิปพอนเทรนนิ่ง"> ดูอัลวิปพอนเทรนนิ่ง | 10 | 🟢 Passive |  |
| 13026 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/268:0:0" width="20" height="20" align="absmiddle" alt="ดูอัลวิปพอนมาสเตอรี่"> ดูอัลวิปพอนมาสเตอรี่ | 10 | 🟢 Passive |  |
| 15006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/100:0:0" width="20" height="20" align="absmiddle" alt="มานาสตอร์ม"> มานาสตอร์ม | 7 | ✨ Buff |  |
| 15012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/167:0:0" width="20" height="20" align="absmiddle" alt="แอคคูเรซี่ออร่า"> แอคคูเรซี่ออร่า | 5 | 💥 AoE |  |
| 15013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/168:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์ออร่า"> ชิลด์ออร่า | 5 | 💥 AoE |  |
| 15014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/169:0:0" width="20" height="20" align="absmiddle" alt="แรมเพจออร่า"> แรมเพจออร่า | 5 | 🩹 Heal |  |
| 15018 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/346:0:0" width="20" height="20" align="absmiddle" alt="มานาแวมไพร์"> มานาแวมไพร์ | 7 | ✨ Buff |  |
| 15019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/78:0:0" width="20" height="20" align="absmiddle" alt="โพรเทคชั่นออร่า"> โพรเทคชั่นออร่า | 3 | 💥 AoE |  |
| 15024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/429:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์ซไวทัล"> รีอินฟอร์ซไวทัล | 10 | 💥 AoE |  |
| 15025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/430:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งไฟท์เตอร์"> เบลสซิ่งไฟท์เตอร์ | 10 | 🔄 Toggle |  |
| 13003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/19:0:0" width="20" height="20" align="absmiddle" alt="เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์"> เฮฟวี่อาร์เมอร์เอ็กซ์เพอร์ไทซ์ | 15 | 🟢 Passive |  |
| 11027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/161:0:0" width="20" height="20" align="absmiddle" alt="รูนอิมแพค"> รูนอิมแพค | 20 | 🔒 CC |  |
| 13011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/14:0:0" width="20" height="20" align="absmiddle" alt="แอกซ์เทรนนิ่ง"> แอกซ์เทรนนิ่ง | 15 | 🟢 Passive |  |
| 13017 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/224:0:0" width="20" height="20" align="absmiddle" alt="แอ็กซ์มอทัลลิตี้"> แอ็กซ์มอทัลลิตี้ | 10 | 🟢 Passive |  |
| 13012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/15:0:0" width="20" height="20" align="absmiddle" alt="เมซเทรนนิ่ง"> เมซเทรนนิ่ง | 20 | 🟢 Passive |  |
| 13018 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/225:0:0" width="20" height="20" align="absmiddle" alt="เมสโพรเทคชั่น"> เมสโพรเทคชั่น | 20 | 🟢 Passive |  |

<details><summary>⚠️ <strong>คำแนะนำการปรับสมดุล (2 รายการ)</strong></summary>

| # | ประเภท | มิติ | รายละเอียด | ไฟล์ที่แก้ | Gap |
|---|--------|------|----------|------------|-----|
| 1 | ➕ เพิ่ม | AoE | 💥 เพิ่มสกิล AoE อีก 1 ตัว (มี 1, ควรมี 3+) | `Skill_Get_List.bin.txt` | 15.0 |
| 2 | ➕ เพิ่ม | CC | 🔒 เพิ่มสกิล CC อีก 2 ตัว (มี 1) | `Skill_Get_List / Skill_Buff_List` | 27.0 |

</details>

---

## 🗡️ Rogue (โจร/นักธนู)

> **Avg Rating:** 81.4/100 · **C5 Jobs:** 10 · เน้นความเร็วและการโจมตีระยะไกลด้วยธนู หรือระยะประชิดแบบลอบเร้น
>
> DMG `99` · AoE `82` · CC `79` · Utility `75` · Survivability `65`

### Human Rogue

#### 2111 โร้ก (C1)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 21001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/27:0:0" width="20" height="20" align="absmiddle" alt="ดัสก์สแลชชิ่ง"> ดัสก์สแลชชิ่ง | 5 | 💀 Debuff |  |
| 21002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/28:0:0" width="20" height="20" align="absmiddle" alt="ฮาร์ทบลาสท์"> ฮาร์ทบลาสท์ | 5 | ⚔️ Attack |  |
| 21003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/29:0:0" width="20" height="20" align="absmiddle" alt="พาวเวอร์ช๊อต"> พาวเวอร์ช๊อต | 5 | ⚔️ Attack |  |
| 21004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/30:0:0" width="20" height="20" align="absmiddle" alt="นีดเดิ้ลช๊อต"> นีดเดิ้ลช๊อต | 5 | 💀 Debuff |  |
| 23003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/38:0:0" width="20" height="20" align="absmiddle" alt="ไลท์อีเวชั่น"> ไลท์อีเวชั่น | 2 | 🟢 Passive |  |
| 23004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/39:0:0" width="20" height="20" align="absmiddle" alt="ไบลนด์ไซด์"> ไบลนด์ไซด์ | 1 | 🟢 Passive |  |
| 25001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/32:0:0" width="20" height="20" align="absmiddle" alt="เซฟเฟอร์"> เซฟเฟอร์ | 1 | ✨ Buff |  |
| 25004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/47:0:0" width="20" height="20" align="absmiddle" alt="ควิคมูฟ"> ควิคมูฟ | 1 | ✨ Buff |  |
| 25017 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/433:0:0" width="20" height="20" align="absmiddle" alt="ดีโทรปว๊อยส์"> ดีโทรปว๊อยส์ | 15 | 🔒 CC |  |
| 25018 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/434:0:0" width="20" height="20" align="absmiddle" alt="แซนด์สเปรย์"> แซนด์สเปรย์ | 15 | 💥 AoE |  |
| 25019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/435:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สไซต์"> รีอินฟอร์สไซต์ | 2 | 💥 AoE |  |
| 25020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/436:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งโร๊ค"> เบลสซิ่งโร๊ค | 2 | 🔄 Toggle |  |
| 25021 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/437:0:0" width="20" height="20" align="absmiddle" alt="ลัคกี้โพสิชั่น"> ลัคกี้โพสิชั่น | 15 | 🟢 Passive |  |
| 25022 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/438:0:0" width="20" height="20" align="absmiddle" alt="บลัฟโพสิชั่น"> บลัฟโพสิชั่น | 15 | 🟢 Passive |  |
| 14001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/138:0:0" width="20" height="20" align="absmiddle" alt="เบิร์นนิ่งเรจ"> เบิร์นนิ่งเรจ | 2 | 🔄 Toggle |  |
| 14002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/1:0:0" width="20" height="20" align="absmiddle" alt="แลช"> แลช | 2 | 🔄 Toggle |  |

---

#### 2121 วอยเอเจอร์ (C2)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 21003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/29:0:0" width="20" height="20" align="absmiddle" alt="พาวเวอร์ช๊อต"> พาวเวอร์ช๊อต | 10 | ⚔️ Attack |  |
| 21004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/30:0:0" width="20" height="20" align="absmiddle" alt="นีดเดิ้ลช๊อต"> นีดเดิ้ลช๊อต | 10 | 💀 Debuff |  |
| 21007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/44:0:0" width="20" height="20" align="absmiddle" alt="ฮาร์มสตริง"> ฮาร์มสตริง | 5 | 🔒 CC |  |
| 21011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/84:0:0" width="20" height="20" align="absmiddle" alt="เพียร์ซซิ่งช๊อต"> เพียร์ซซิ่งช๊อต | 5 | 💥 AoE |  |
| 23004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/39:0:0" width="20" height="20" align="absmiddle" alt="ไบลนด์ไซด์"> ไบลนด์ไซด์ | 2 | 🟢 Passive |  |
| 25001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/32:0:0" width="20" height="20" align="absmiddle" alt="เซฟเฟอร์"> เซฟเฟอร์ | 2 | ✨ Buff |  |
| 25004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/47:0:0" width="20" height="20" align="absmiddle" alt="ควิคมูฟ"> ควิคมูฟ | 3 | ✨ Buff |  |
| 25019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/435:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สไซต์"> รีอินฟอร์สไซต์ | 4 | 💥 AoE |  |
| 25020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/436:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งโร๊ค"> เบลสซิ่งโร๊ค | 4 | 🔄 Toggle |  |

---

#### 2122 Hunter (C2)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 21001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/27:0:0" width="20" height="20" align="absmiddle" alt="ดัสก์สแลชชิ่ง"> ดัสก์สแลชชิ่ง | 10 | 💀 Debuff |  |
| 21002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/28:0:0" width="20" height="20" align="absmiddle" alt="ฮาร์ทบลาสท์"> ฮาร์ทบลาสท์ | 10 | ⚔️ Attack |  |
| 21009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/46:0:0" width="20" height="20" align="absmiddle" alt="เพอร์โฟเรท"> เพอร์โฟเรท | 5 | ⚔️ Attack |  |
| 21012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/85:0:0" width="20" height="20" align="absmiddle" alt="วินด์เบรคกิ้ง"> วินด์เบรคกิ้ง | 5 | 💥 AoE |  |
| 23003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/38:0:0" width="20" height="20" align="absmiddle" alt="ไลท์อีเวชั่น"> ไลท์อีเวชั่น | 4 | 🟢 Passive |  |
| 23004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/39:0:0" width="20" height="20" align="absmiddle" alt="ไบลนด์ไซด์"> ไบลนด์ไซด์ | 3 | 🟢 Passive |  |
| 25001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/32:0:0" width="20" height="20" align="absmiddle" alt="เซฟเฟอร์"> เซฟเฟอร์ | 3 | ✨ Buff |  |
| 25004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/47:0:0" width="20" height="20" align="absmiddle" alt="ควิคมูฟ"> ควิคมูฟ | 2 | ✨ Buff |  |
| 25019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/435:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สไซต์"> รีอินฟอร์สไซต์ | 4 | 💥 AoE |  |
| 25020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/436:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งโร๊ค"> เบลสซิ่งโร๊ค | 4 | 🔄 Toggle |  |

---

#### 2131 เทรเชอร์ฮันเตอร์ (C3)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 21003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/29:0:0" width="20" height="20" align="absmiddle" alt="พาวเวอร์ช๊อต"> พาวเวอร์ช๊อต | 15 | ⚔️ Attack |  |
| 21004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/30:0:0" width="20" height="20" align="absmiddle" alt="นีดเดิ้ลช๊อต"> นีดเดิ้ลช๊อต | 15 | 💀 Debuff |  |
| 21007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/44:0:0" width="20" height="20" align="absmiddle" alt="ฮาร์มสตริง"> ฮาร์มสตริง | 10 | 🔒 CC |  |
| 21011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/84:0:0" width="20" height="20" align="absmiddle" alt="เพียร์ซซิ่งช๊อต"> เพียร์ซซิ่งช๊อต | 10 | 💥 AoE |  |
| 21014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/106:0:0" width="20" height="20" align="absmiddle" alt="ไอซ์เรนนิ่ง"> ไอซ์เรนนิ่ง | 5 | 💥 AoE |  |
| 23001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/35:0:0" width="20" height="20" align="absmiddle" alt="โบวเทรนนิ่ง"> โบวเทรนนิ่ง | 5 | 🟢 Passive |  |
| 23004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/39:0:0" width="20" height="20" align="absmiddle" alt="ไบลนด์ไซด์"> ไบลนด์ไซด์ | 4 | 🟢 Passive |  |
| 25001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/32:0:0" width="20" height="20" align="absmiddle" alt="เซฟเฟอร์"> เซฟเฟอร์ | 3 | ✨ Buff |  |
| 25004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/47:0:0" width="20" height="20" align="absmiddle" alt="ควิคมูฟ"> ควิคมูฟ | 5 | ✨ Buff |  |
| 25019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/435:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สไซต์"> รีอินฟอร์สไซต์ | 6 | 💥 AoE |  |
| 25020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/436:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งโร๊ค"> เบลสซิ่งโร๊ค | 6 | 🔄 Toggle |  |

---

#### 2132 Assasin (C3)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 21001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/27:0:0" width="20" height="20" align="absmiddle" alt="ดัสก์สแลชชิ่ง"> ดัสก์สแลชชิ่ง | 15 | 💀 Debuff |  |
| 21002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/28:0:0" width="20" height="20" align="absmiddle" alt="ฮาร์ทบลาสท์"> ฮาร์ทบลาสท์ | 15 | ⚔️ Attack |  |
| 21009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/46:0:0" width="20" height="20" align="absmiddle" alt="เพอร์โฟเรท"> เพอร์โฟเรท | 10 | ⚔️ Attack |  |
| 21012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/85:0:0" width="20" height="20" align="absmiddle" alt="วินด์เบรคกิ้ง"> วินด์เบรคกิ้ง | 10 | 💥 AoE |  |
| 21025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/179:0:0" width="20" height="20" align="absmiddle" alt="เดซี่โบลว"> เดซี่โบลว | 5 | 💥 AoE |  |
| 23003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/38:0:0" width="20" height="20" align="absmiddle" alt="ไลท์อีเวชั่น"> ไลท์อีเวชั่น | 6 | 🟢 Passive |  |
| 23004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/39:0:0" width="20" height="20" align="absmiddle" alt="ไบลนด์ไซด์"> ไบลนด์ไซด์ | 5 | 🟢 Passive |  |
| 25001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/32:0:0" width="20" height="20" align="absmiddle" alt="เซฟเฟอร์"> เซฟเฟอร์ | 5 | ✨ Buff |  |
| 25004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/47:0:0" width="20" height="20" align="absmiddle" alt="ควิคมูฟ"> ควิคมูฟ | 3 | ✨ Buff |  |
| 25007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/112:0:0" width="20" height="20" align="absmiddle" alt="สเทลธ์"> สเทลธ์ | 2 | 🔄 Toggle |  |
| 25019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/435:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สไซต์"> รีอินฟอร์สไซต์ | 6 | 💥 AoE |  |
| 25020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/436:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งโร๊ค"> เบลสซิ่งโร๊ค | 6 | 🔄 Toggle |  |

---

#### 2133 เรนเจอร์ (C3)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 21001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/27:0:0" width="20" height="20" align="absmiddle" alt="ดัสก์สแลชชิ่ง"> ดัสก์สแลชชิ่ง | 15 | 💀 Debuff |  |
| 21002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/28:0:0" width="20" height="20" align="absmiddle" alt="ฮาร์ทบลาสท์"> ฮาร์ทบลาสท์ | 15 | ⚔️ Attack |  |
| 21003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/29:0:0" width="20" height="20" align="absmiddle" alt="พาวเวอร์ช๊อต"> พาวเวอร์ช๊อต | 15 | ⚔️ Attack |  |
| 21004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/30:0:0" width="20" height="20" align="absmiddle" alt="นีดเดิ้ลช๊อต"> นีดเดิ้ลช๊อต | 15 | 💀 Debuff |  |
| 21011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/84:0:0" width="20" height="20" align="absmiddle" alt="เพียร์ซซิ่งช๊อต"> เพียร์ซซิ่งช๊อต | 10 | 💥 AoE |  |
| 21012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/85:0:0" width="20" height="20" align="absmiddle" alt="วินด์เบรคกิ้ง"> วินด์เบรคกิ้ง | 10 | 💥 AoE |  |
| 21016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/61:0:0" width="20" height="20" align="absmiddle" alt="เนเจอร์เอด"> เนเจอร์เอด | 5 | ⚔️ Attack |  |
| 21017 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/74:0:0" width="20" height="20" align="absmiddle" alt="พอยซั่นเอด"> พอยซั่นเอด | 1 | ⚔️ Attack |  |
| 25001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/32:0:0" width="20" height="20" align="absmiddle" alt="เซฟเฟอร์"> เซฟเฟอร์ | 5 | ✨ Buff |  |
| 25004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/47:0:0" width="20" height="20" align="absmiddle" alt="ควิคมูฟ"> ควิคมูฟ | 4 | ✨ Buff |  |
| 25005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/116:0:0" width="20" height="20" align="absmiddle" alt="ไซด์สเต็ป"> ไซด์สเต็ป | 3 | ✨ Buff |  |
| 25006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/117:0:0" width="20" height="20" align="absmiddle" alt="วิสเพอริ่งวินด์"> วิสเพอริ่งวินด์ | 3 | 💥 AoE |  |
| 25019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/435:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สไซต์"> รีอินฟอร์สไซต์ | 6 | 💥 AoE |  |
| 25020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/436:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งโร๊ค"> เบลสซิ่งโร๊ค | 6 | 🔄 Toggle |  |

---

#### 2141 Rune Walker (C4)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 21003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/29:0:0" width="20" height="20" align="absmiddle" alt="พาวเวอร์ช๊อต"> พาวเวอร์ช๊อต | 30 | ⚔️ Attack |  |
| 21004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/30:0:0" width="20" height="20" align="absmiddle" alt="นีดเดิ้ลช๊อต"> นีดเดิ้ลช๊อต | 30 | 💀 Debuff |  |
| 21007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/44:0:0" width="20" height="20" align="absmiddle" alt="ฮาร์มสตริง"> ฮาร์มสตริง | 15 | 🔒 CC |  |
| 21011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/84:0:0" width="20" height="20" align="absmiddle" alt="เพียร์ซซิ่งช๊อต"> เพียร์ซซิ่งช๊อต | 15 | 💥 AoE |  |
| 21014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/106:0:0" width="20" height="20" align="absmiddle" alt="ไอซ์เรนนิ่ง"> ไอซ์เรนนิ่ง | 10 | 💥 AoE |  |
| 21020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/174:0:0" width="20" height="20" align="absmiddle" alt="แรพพิดแอโรว์"> แรพพิดแอโรว์ | 5 | 🔒 CC |  |
| 23001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/35:0:0" width="20" height="20" align="absmiddle" alt="โบวเทรนนิ่ง"> โบวเทรนนิ่ง | 10 | 🟢 Passive |  |
| 23004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/39:0:0" width="20" height="20" align="absmiddle" alt="ไบลนด์ไซด์"> ไบลนด์ไซด์ | 6 | 🟢 Passive |  |
| 23006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/41:0:0" width="20" height="20" align="absmiddle" alt="ลองช๊อต"> ลองช๊อต | 3 | 🟢 Passive |  |
| 25001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/32:0:0" width="20" height="20" align="absmiddle" alt="เซฟเฟอร์"> เซฟเฟอร์ | 4 | ✨ Buff |  |
| 25003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/34:0:0" width="20" height="20" align="absmiddle" alt="เฟทอลทัช"> เฟทอลทัช | 3 | ✨ Buff |  |
| 25004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/47:0:0" width="20" height="20" align="absmiddle" alt="ควิคมูฟ"> ควิคมูฟ | 7 | ✨ Buff |  |
| 25019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/435:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สไซต์"> รีอินฟอร์สไซต์ | 8 | 💥 AoE |  |
| 25020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/436:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งโร๊ค"> เบลสซิ่งโร๊ค | 8 | 🔄 Toggle |  |

---

#### 2142 สเคาท์ (C4)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 13002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/11:0:0" width="20" height="20" align="absmiddle" alt="ไลท์อาร์เมอร์เอ็กเพอร์ไทซ์"> ไลท์อาร์เมอร์เอ็กเพอร์ไทซ์ | 15 | 🟢 Passive |  |
| 21002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/28:0:0" width="20" height="20" align="absmiddle" alt="ฮาร์ทบลาสท์"> ฮาร์ทบลาสท์ | 25 | ⚔️ Attack |  |
| 21022 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/176:0:0" width="20" height="20" align="absmiddle" alt="ฮันเตอร์พัม"> ฮันเตอร์พัม | 20 | 💥 AoE |  |
| 21023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/177:0:0" width="20" height="20" align="absmiddle" alt="ฮันเตอร์สโมค"> ฮันเตอร์สโมค | 10 | 💥 AoE |  |
| 21024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/178:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์บูมเมอแรง"> ชิลด์บูมเมอแรง | 10 | 🔒 CC |  |
| 23002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/36:0:0" width="20" height="20" align="absmiddle" alt="แด๊กเกอร์เทรนนิ่ง"> แด๊กเกอร์เทรนนิ่ง | 15 | 🟢 Passive |  |
| 25001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/32:0:0" width="20" height="20" align="absmiddle" alt="เซฟเฟอร์"> เซฟเฟอร์ | 6 | ✨ Buff |  |
| 25004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/47:0:0" width="20" height="20" align="absmiddle" alt="ควิคมูฟ"> ควิคมูฟ | 4 | ✨ Buff |  |
| 25019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/435:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สไซต์"> รีอินฟอร์สไซต์ | 8 | 💥 AoE |  |
| 25020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/436:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งโร๊ค"> เบลสซิ่งโร๊ค | 8 | 🔄 Toggle |  |
| 23004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/39:0:0" width="20" height="20" align="absmiddle" alt="ไบลนด์ไซด์"> ไบลนด์ไซด์ | 9 | 🟢 Passive |  |
| 21021 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/175:0:0" width="20" height="20" align="absmiddle" alt="เทคเกอร์โบลว"> เทคเกอร์โบลว | 15 | ⚔️ Attack |  |
| 13004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/20:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์เทรนนิ่ง"> ชิลด์เทรนนิ่ง | 10 | 🟢 Passive |  |

---

#### 2143 Arch Ranger (C4)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 21001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/27:0:0" width="20" height="20" align="absmiddle" alt="ดัสก์สแลชชิ่ง"> ดัสก์สแลชชิ่ง | 25 | 💀 Debuff |  |
| 21002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/28:0:0" width="20" height="20" align="absmiddle" alt="ฮาร์ทบลาสท์"> ฮาร์ทบลาสท์ | 25 | ⚔️ Attack |  |
| 21009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/46:0:0" width="20" height="20" align="absmiddle" alt="เพอร์โฟเรท"> เพอร์โฟเรท | 20 | ⚔️ Attack |  |
| 21012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/85:0:0" width="20" height="20" align="absmiddle" alt="วินด์เบรคกิ้ง"> วินด์เบรคกิ้ง | 15 | 💥 AoE |  |
| 21015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/115:0:0" width="20" height="20" align="absmiddle" alt="ซัดเดินเรด"> ซัดเดินเรด | 15 | 🔒 CC |  |
| 21025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/179:0:0" width="20" height="20" align="absmiddle" alt="เดซี่โบลว"> เดซี่โบลว | 20 | 💥 AoE |  |
| 21027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/181:0:0" width="20" height="20" align="absmiddle" alt="ไฟนอลโบลว"> ไฟนอลโบลว | 10 | ⚔️ Attack |  |
| 23002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/36:0:0" width="20" height="20" align="absmiddle" alt="แด๊กเกอร์เทรนนิ่ง"> แด๊กเกอร์เทรนนิ่ง | 10 | 🟢 Passive |  |
| 23003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/38:0:0" width="20" height="20" align="absmiddle" alt="ไลท์อีเวชั่น"> ไลท์อีเวชั่น | 8 | 🟢 Passive |  |
| 23004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/39:0:0" width="20" height="20" align="absmiddle" alt="ไบลนด์ไซด์"> ไบลนด์ไซด์ | 8 | 🟢 Passive |  |
| 25001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/32:0:0" width="20" height="20" align="absmiddle" alt="เซฟเฟอร์"> เซฟเฟอร์ | 7 | ✨ Buff |  |
| 25004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/47:0:0" width="20" height="20" align="absmiddle" alt="ควิคมูฟ"> ควิคมูฟ | 4 | ✨ Buff |  |
| 25007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/112:0:0" width="20" height="20" align="absmiddle" alt="สเทลธ์"> สเทลธ์ | 4 | 🔄 Toggle |  |
| 25011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/187:0:0" width="20" height="20" align="absmiddle" alt="พรีเดเตอร์"> พรีเดเตอร์ | 2 | ✨ Buff |  |
| 25019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/435:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สไซต์"> รีอินฟอร์สไซต์ | 8 | 💥 AoE |  |
| 25020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/436:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งโร๊ค"> เบลสซิ่งโร๊ค | 8 | 🔄 Toggle |  |

---

#### 2144 Thief Master (C4)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 21001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/27:0:0" width="20" height="20" align="absmiddle" alt="ดัสก์สแลชชิ่ง"> ดัสก์สแลชชิ่ง | 25 | 💀 Debuff |  |
| 21002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/28:0:0" width="20" height="20" align="absmiddle" alt="ฮาร์ทบลาสท์"> ฮาร์ทบลาสท์ | 25 | ⚔️ Attack |  |
| 21003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/29:0:0" width="20" height="20" align="absmiddle" alt="พาวเวอร์ช๊อต"> พาวเวอร์ช๊อต | 30 | ⚔️ Attack |  |
| 21004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/30:0:0" width="20" height="20" align="absmiddle" alt="นีดเดิ้ลช๊อต"> นีดเดิ้ลช๊อต | 30 | 💀 Debuff |  |
| 21011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/84:0:0" width="20" height="20" align="absmiddle" alt="เพียร์ซซิ่งช๊อต"> เพียร์ซซิ่งช๊อต | 15 | 💥 AoE |  |
| 21012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/85:0:0" width="20" height="20" align="absmiddle" alt="วินด์เบรคกิ้ง"> วินด์เบรคกิ้ง | 15 | 💥 AoE |  |
| 21016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/61:0:0" width="20" height="20" align="absmiddle" alt="เนเจอร์เอด"> เนเจอร์เอด | 10 | ⚔️ Attack |  |
| 21017 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/74:0:0" width="20" height="20" align="absmiddle" alt="พอยซั่นเอด"> พอยซั่นเอด | 2 | ⚔️ Attack |  |
| 21028 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/182:0:0" width="20" height="20" align="absmiddle" alt="แคสติ้งฟอยล์"> แคสติ้งฟอยล์ | 2 | 🔒 CC |  |
| 21029 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/183:0:0" width="20" height="20" align="absmiddle" alt="สแลค"> สแลค | 2 | 💀 Debuff |  |
| 25001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/32:0:0" width="20" height="20" align="absmiddle" alt="เซฟเฟอร์"> เซฟเฟอร์ | 6 | ✨ Buff |  |
| 25004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/47:0:0" width="20" height="20" align="absmiddle" alt="ควิคมูฟ"> ควิคมูฟ | 6 | ✨ Buff |  |
| 25005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/116:0:0" width="20" height="20" align="absmiddle" alt="ไซด์สเต็ป"> ไซด์สเต็ป | 6 | ✨ Buff |  |
| 25006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/117:0:0" width="20" height="20" align="absmiddle" alt="วิสเพอริ่งวินด์"> วิสเพอริ่งวินด์ | 6 | 💥 AoE |  |
| 25019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/435:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สไซต์"> รีอินฟอร์สไซต์ | 8 | 💥 AoE |  |
| 25020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/436:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งโร๊ค"> เบลสซิ่งโร๊ค | 8 | 🔄 Toggle |  |
| 23011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/191:0:0" width="20" height="20" align="absmiddle" alt="แรพพิดมูฟเมนท์"> แรพพิดมูฟเมนท์ | 2 | 🟢 Passive |  |
| 23010 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/190:0:0" width="20" height="20" align="absmiddle" alt="แรพพิดแอทแทค"> แรพพิดแอทแทค | 2 | 🟢 Passive |  |

---

#### 2151 เอ็นแทรปเปอร์ (C5)

> 🟢 **Overall: 88.2**/100 · DMG `95` · AoE `80` · CC `74` · Util `99` · Surv `90`

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 13025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/357:0:0" width="20" height="20" align="absmiddle" alt="มัสเกทเทรนนิ่ง"> มัสเกทเทรนนิ่ง | 20 | 🟢 Passive |  |
| 21033 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/271:0:0" width="20" height="20" align="absmiddle" alt="สแตนดิ้งช๊อต"> สแตนดิ้งช๊อต | 20 | ⚔️ Attack |  |
| 21034 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/359:0:0" width="20" height="20" align="absmiddle" alt="ไวลด์ช๊อต"> ไวลด์ช๊อต | 20 | 💥 AoE |  |
| 21035 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/272:0:0" width="20" height="20" align="absmiddle" alt="นีลลิ่งไฟร์"> นีลลิ่งไฟร์ | 30 | 💥 AoE |  |
| 21036 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/273:0:0" width="20" height="20" align="absmiddle" alt="พรอกซิมิตี้ไฟร์"> พรอกซิมิตี้ไฟร์ | 30 | 🔒 CC |  |
| 21037 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/274:0:0" width="20" height="20" align="absmiddle" alt="แฟลชไฟร์"> แฟลชไฟร์ | 30 | 🔒 CC |  |
| 23004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/39:0:0" width="20" height="20" align="absmiddle" alt="ไบลนด์ไซด์"> ไบลนด์ไซด์ | 8 | 🟢 Passive |  |
| 23013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/358:0:0" width="20" height="20" align="absmiddle" alt="มัสเกทเรนจ์"> มัสเกทเรนจ์ | 5 | 🟢 Passive |  |
| 25001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/32:0:0" width="20" height="20" align="absmiddle" alt="เซฟเฟอร์"> เซฟเฟอร์ | 5 | ✨ Buff |  |
| 25003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/34:0:0" width="20" height="20" align="absmiddle" alt="เฟทอลทัช"> เฟทอลทัช | 6 | ✨ Buff |  |
| 25004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/47:0:0" width="20" height="20" align="absmiddle" alt="ควิคมูฟ"> ควิคมูฟ | 9 | ✨ Buff |  |
| 25019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/435:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สไซต์"> รีอินฟอร์สไซต์ | 10 | 💥 AoE |  |
| 25020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/436:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งโร๊ค"> เบลสซิ่งโร๊ค | 10 | 🔄 Toggle |  |
| 25014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/276:0:0" width="20" height="20" align="absmiddle" alt="มัสเกทสโคป"> มัสเกทสโคป | 10 | ✨ Buff |  |
| 15020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/355:0:0" width="20" height="20" align="absmiddle" alt="รีโหลดดิ้ง"> รีโหลดดิ้ง | 5 | 🩹 Heal |  |
| 23007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/42:0:0" width="20" height="20" align="absmiddle" alt="อีเกิ้ลอาย"> อีเกิ้ลอาย | 10 | 🟢 Passive |  |
| 23005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/40:0:0" width="20" height="20" align="absmiddle" alt="เดธซายน์"> เดธซายน์ | 8 | 🟢 Passive |  |
| 25009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/185:0:0" width="20" height="20" align="absmiddle" alt="ฟาสต์รีโหลด"> ฟาสต์รีโหลด | 4 | 🩹 Heal |  |

<details><summary>⚠️ <strong>คำแนะนำการปรับสมดุล (1 รายการ)</strong></summary>

| # | ประเภท | มิติ | รายละเอียด | ไฟล์ที่แก้ | Gap |
|---|--------|------|----------|------------|-----|
| 1 | ➕ เพิ่ม | CC | 🔒 เพิ่มสกิล CC อีก 1 ตัว (มี 2) | `Skill_Get_List / Skill_Buff_List` | 1.0 |

</details>

---

#### 2152 Tempest (C5)

> 🟡 **Overall: 83.1**/100 · DMG `100` · AoE `78` · CC `96` · Util `72` · Surv `64`

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 13002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/11:0:0" width="20" height="20" align="absmiddle" alt="ไลท์อาร์เมอร์เอ็กเพอร์ไทซ์"> ไลท์อาร์เมอร์เอ็กเพอร์ไทซ์ | 25 | 🟢 Passive |  |
| 21022 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/176:0:0" width="20" height="20" align="absmiddle" alt="ฮันเตอร์พัม"> ฮันเตอร์พัม | 30 | 💥 AoE |  |
| 21023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/177:0:0" width="20" height="20" align="absmiddle" alt="ฮันเตอร์สโมค"> ฮันเตอร์สโมค | 10 | 💥 AoE |  |
| 21024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/178:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์บูมเมอแรง"> ชิลด์บูมเมอแรง | 30 | 🔒 CC |  |
| 21031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/263:0:0" width="20" height="20" align="absmiddle" alt="ไฟร์แทรป"> ไฟร์แทรป | 5 | ⚔️ Attack | ⚠️ DPS ต่ำ (30) |
| 21032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/263:0:0" width="20" height="20" align="absmiddle" alt="ไอซ์แทรป"> ไอซ์แทรป | 5 | ⚔️ Attack | ⚠️ DPS ต่ำ (31) |
| 25001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/32:0:0" width="20" height="20" align="absmiddle" alt="เซฟเฟอร์"> เซฟเฟอร์ | 9 | ✨ Buff |  |
| 25004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/47:0:0" width="20" height="20" align="absmiddle" alt="ควิคมูฟ"> ควิคมูฟ | 5 | ✨ Buff |  |
| 25019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/435:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สไซต์"> รีอินฟอร์สไซต์ | 10 | 💥 AoE |  |
| 25020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/436:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งโร๊ค"> เบลสซิ่งโร๊ค | 10 | 🔄 Toggle |  |
| 23002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/36:0:0" width="20" height="20" align="absmiddle" alt="แด๊กเกอร์เทรนนิ่ง"> แด๊กเกอร์เทรนนิ่ง | 20 | 🟢 Passive |  |
| 23003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/38:0:0" width="20" height="20" align="absmiddle" alt="ไลท์อีเวชั่น"> ไลท์อีเวชั่น | 10 | 🟢 Passive |  |
| 25011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/187:0:0" width="20" height="20" align="absmiddle" alt="พรีเดเตอร์"> พรีเดเตอร์ | 4 | ✨ Buff |  |
| 21021 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/175:0:0" width="20" height="20" align="absmiddle" alt="เทคเกอร์โบลว"> เทคเกอร์โบลว | 30 | ⚔️ Attack |  |
| 21012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/85:0:0" width="20" height="20" align="absmiddle" alt="วินด์เบรคกิ้ง"> วินด์เบรคกิ้ง | 30 | 💥 AoE |  |
| 21041 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/108:0:0" width="20" height="20" align="absmiddle" alt="แคชพาวน์ดิ้ง"> แคชพาวน์ดิ้ง | 20 | 🔒 CC |  |
| 21009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/46:0:0" width="20" height="20" align="absmiddle" alt="เพอร์โฟเรท"> เพอร์โฟเรท | 30 | ⚔️ Attack |  |
| 21008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/45:0:0" width="20" height="20" align="absmiddle" alt="เรจสเต็ป"> เรจสเต็ป | 30 | 🔒 CC |  |
| 25002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/33:0:0" width="20" height="20" align="absmiddle" alt="ดีเทคโฮล"> ดีเทคโฮล | 8 | ✨ Buff |  |
| 23009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/137:0:0" width="20" height="20" align="absmiddle" alt="ไดอาบอลิคอินสติงท์"> ไดอาบอลิคอินสติงท์ | 7 | 🟢 Passive |  |
| 23004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/39:0:0" width="20" height="20" align="absmiddle" alt="ไบลนด์ไซด์"> ไบลนด์ไซด์ | 9 | 🟢 Passive |  |
| 13004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/20:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์เทรนนิ่ง"> ชิลด์เทรนนิ่ง | 20 | 🟢 Passive |  |

<details><summary>⚠️ <strong>คำแนะนำการปรับสมดุล (3 รายการ)</strong></summary>

| # | ประเภท | มิติ | รายละเอียด | ไฟล์ที่แก้ | Gap |
|---|--------|------|----------|------------|-----|
| 1 | 🔧 ปรับ | AoE | ⚔️ ปรับค่า fUnitDataValueMul สกิล AoE ที่มี (×1.3-1.5) | `SkillScript.bin.txt` | 2.4 |
| 2 | 🔧 ปรับ | Survivability | 🛡️ ปรับค่า fStatusDataMul สกิลบัฟ/ฮีล (×1.3-1.5) | `Skill_Buff_List.bin.txt` | 1.0 |
| 3 | 🔧 ปรับ | Utility | ✨ ปรับค่า fStatusDataMul สกิลบัฟ (×1.3-1.5) | `Skill_Buff_List.bin.txt` | 3.0 |

</details>

---

#### 2153 เบลดเทคเกอร์ (C5)

> 🔴 **Overall: 76.7**/100 · DMG `100` · AoE `80` · CC `62` · Util `66` · Surv `64`

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 13022 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/267:0:0" width="20" height="20" align="absmiddle" alt="ดูอัลวิปพอนเทรนนิ่ง"> ดูอัลวิปพอนเทรนนิ่ง | 10 | 🟢 Passive |  |
| 13026 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/268:0:0" width="20" height="20" align="absmiddle" alt="ดูอัลวิปพอนมาสเตอรี่"> ดูอัลวิปพอนมาสเตอรี่ | 10 | 🟢 Passive |  |
| 21009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/46:0:0" width="20" height="20" align="absmiddle" alt="เพอร์โฟเรท"> เพอร์โฟเรท | 30 | ⚔️ Attack |  |
| 21012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/85:0:0" width="20" height="20" align="absmiddle" alt="วินด์เบรคกิ้ง"> วินด์เบรคกิ้ง | 30 | 💥 AoE |  |
| 21015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/115:0:0" width="20" height="20" align="absmiddle" alt="ซัดเดินเรด"> ซัดเดินเรด | 30 | 🔒 CC |  |
| 21025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/179:0:0" width="20" height="20" align="absmiddle" alt="เดซี่โบลว"> เดซี่โบลว | 30 | 💥 AoE |  |
| 21027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/181:0:0" width="20" height="20" align="absmiddle" alt="ไฟนอลโบลว"> ไฟนอลโบลว | 15 | ⚔️ Attack |  |
| 21042 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/264:0:0" width="20" height="20" align="absmiddle" alt="เดดลี่สไตรค์"> เดดลี่สไตรค์ | 10 | ⚔️ Attack |  |
| 23002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/36:0:0" width="20" height="20" align="absmiddle" alt="แด๊กเกอร์เทรนนิ่ง"> แด๊กเกอร์เทรนนิ่ง | 20 | 🟢 Passive |  |
| 23003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/38:0:0" width="20" height="20" align="absmiddle" alt="ไลท์อีเวชั่น"> ไลท์อีเวชั่น | 10 | 🟢 Passive |  |
| 23004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/39:0:0" width="20" height="20" align="absmiddle" alt="ไบลนด์ไซด์"> ไบลนด์ไซด์ | 10 | 🟢 Passive |  |
| 25001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/32:0:0" width="20" height="20" align="absmiddle" alt="เซฟเฟอร์"> เซฟเฟอร์ | 9 | ✨ Buff |  |
| 25004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/47:0:0" width="20" height="20" align="absmiddle" alt="ควิคมูฟ"> ควิคมูฟ | 5 | ✨ Buff |  |
| 25007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/112:0:0" width="20" height="20" align="absmiddle" alt="สเทลธ์"> สเทลธ์ | 6 | 🔄 Toggle |  |
| 25011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/187:0:0" width="20" height="20" align="absmiddle" alt="พรีเดเตอร์"> พรีเดเตอร์ | 4 | ✨ Buff |  |
| 25019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/435:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สไซต์"> รีอินฟอร์สไซต์ | 10 | 💥 AoE |  |
| 25020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/436:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งโร๊ค"> เบลสซิ่งโร๊ค | 10 | 🔄 Toggle |  |
| 13002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/11:0:0" width="20" height="20" align="absmiddle" alt="ไลท์อาร์เมอร์เอ็กเพอร์ไทซ์"> ไลท์อาร์เมอร์เอ็กเพอร์ไทซ์ | 8 | 🟢 Passive |  |
| 21021 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/175:0:0" width="20" height="20" align="absmiddle" alt="เทคเกอร์โบลว"> เทคเกอร์โบลว | 20 | ⚔️ Attack |  |
| 21030 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/184:0:0" width="20" height="20" align="absmiddle" alt="อิลลูชั่นแอทแทค"> อิลลูชั่นแอทแทค | 30 | 🔒 CC |  |

<details><summary>⚠️ <strong>คำแนะนำการปรับสมดุล (3 รายการ)</strong></summary>

| # | ประเภท | มิติ | รายละเอียด | ไฟล์ที่แก้ | Gap |
|---|--------|------|----------|------------|-----|
| 1 | ➕ เพิ่ม | CC | 🔒 เพิ่มสกิล CC อีก 1 ตัว (มี 2) | `Skill_Get_List / Skill_Buff_List` | 13.0 |
| 2 | 🔧 ปรับ | Survivability | 🛡️ ปรับค่า fStatusDataMul สกิลบัฟ/ฮีล (×1.3-1.5) | `Skill_Buff_List.bin.txt` | 1.0 |
| 3 | 🔧 ปรับ | Utility | ✨ ปรับค่า fStatusDataMul สกิลบัฟ (×1.3-1.5) | `Skill_Buff_List.bin.txt` | 9.0 |

</details>

---

#### 2154 Arch Breezer (C5)

> 🟡 **Overall: 80.4**/100 · DMG `100` · AoE `79` · CC `69` · Util `75` · Surv `70`

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 21011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/84:0:0" width="20" height="20" align="absmiddle" alt="เพียร์ซซิ่งช๊อต"> เพียร์ซซิ่งช๊อต | 20 | 💥 AoE |  |
| 21012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/85:0:0" width="20" height="20" align="absmiddle" alt="วินด์เบรคกิ้ง"> วินด์เบรคกิ้ง | 30 | 💥 AoE |  |
| 21016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/61:0:0" width="20" height="20" align="absmiddle" alt="เนเจอร์เอด"> เนเจอร์เอด | 15 | ⚔️ Attack | ⚠️ DPS ต่ำ (39) |
| 21017 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/74:0:0" width="20" height="20" align="absmiddle" alt="พอยซั่นเอด"> พอยซั่นเอด | 3 | ⚔️ Attack | ⚠️ DPS ต่ำ (15) |
| 21028 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/182:0:0" width="20" height="20" align="absmiddle" alt="แคสติ้งฟอยล์"> แคสติ้งฟอยล์ | 5 | 🔒 CC |  |
| 21029 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/183:0:0" width="20" height="20" align="absmiddle" alt="สแลค"> สแลค | 5 | 💀 Debuff |  |
| 21038 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/84:0:0" width="20" height="20" align="absmiddle" alt="เมจิคแอโรว์"> เมจิคแอโรว์ | 10 | ⚔️ Attack |  |
| 21042 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/264:0:0" width="20" height="20" align="absmiddle" alt="เดดลี่สไตรค์"> เดดลี่สไตรค์ | 10 | ⚔️ Attack |  |
| 21047 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/111:0:0" width="20" height="20" align="absmiddle" alt="เดดลี่โซล"> เดดลี่โซล | 10 | 💥 AoE |  |
| 25001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/32:0:0" width="20" height="20" align="absmiddle" alt="เซฟเฟอร์"> เซฟเฟอร์ | 8 | ✨ Buff |  |
| 25004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/47:0:0" width="20" height="20" align="absmiddle" alt="ควิคมูฟ"> ควิคมูฟ | 8 | ✨ Buff |  |
| 25005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/116:0:0" width="20" height="20" align="absmiddle" alt="ไซด์สเต็ป"> ไซด์สเต็ป | 9 | ✨ Buff |  |
| 25006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/117:0:0" width="20" height="20" align="absmiddle" alt="วิสเพอริ่งวินด์"> วิสเพอริ่งวินด์ | 9 | 💥 AoE |  |
| 25019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/435:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สไซต์"> รีอินฟอร์สไซต์ | 10 | 💥 AoE |  |
| 25020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/436:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งโร๊ค"> เบลสซิ่งโร๊ค | 10 | 🔄 Toggle |  |
| 23003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/38:0:0" width="20" height="20" align="absmiddle" alt="ไลท์อีเวชั่น"> ไลท์อีเวชั่น | 10 | 🟢 Passive |  |
| 13002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/11:0:0" width="20" height="20" align="absmiddle" alt="ไลท์อาร์เมอร์เอ็กเพอร์ไทซ์"> ไลท์อาร์เมอร์เอ็กเพอร์ไทซ์ | 25 | 🟢 Passive |  |
| 23008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/136:0:0" width="20" height="20" align="absmiddle" alt="ชาโดว์อินสติงท์"> ชาโดว์อินสติงท์ | 8 | 🟢 Passive |  |
| 23002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/36:0:0" width="20" height="20" align="absmiddle" alt="แด๊กเกอร์เทรนนิ่ง"> แด๊กเกอร์เทรนนิ่ง | 20 | 🟢 Passive |  |
| 13022 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/267:0:0" width="20" height="20" align="absmiddle" alt="ดูอัลวิปพอนเทรนนิ่ง"> ดูอัลวิปพอนเทรนนิ่ง | 10 | 🟢 Passive |  |
| 13026 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/268:0:0" width="20" height="20" align="absmiddle" alt="ดูอัลวิปพอนมาสเตอรี่"> ดูอัลวิปพอนมาสเตอรี่ | 10 | 🟢 Passive |  |
| 21002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/28:0:0" width="20" height="20" align="absmiddle" alt="ฮาร์ทบลาสท์"> ฮาร์ทบลาสท์ | 30 | ⚔️ Attack |  |
| 21001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/27:0:0" width="20" height="20" align="absmiddle" alt="ดัสก์สแลชชิ่ง"> ดัสก์สแลชชิ่ง | 30 | 💀 Debuff |  |
| 23001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/35:0:0" width="20" height="20" align="absmiddle" alt="โบวเทรนนิ่ง"> โบวเทรนนิ่ง | 20 | 🟢 Passive |  |
| 21003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/29:0:0" width="20" height="20" align="absmiddle" alt="พาวเวอร์ช๊อต"> พาวเวอร์ช๊อต | 30 | ⚔️ Attack |  |
| 21004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/30:0:0" width="20" height="20" align="absmiddle" alt="นีดเดิ้ลช๊อต"> นีดเดิ้ลช๊อต | 30 | 💀 Debuff |  |
| 21013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/108:0:0" width="20" height="20" align="absmiddle" alt="ฟาวน์ดิ้งช๊อต"> ฟาวน์ดิ้งช๊อต | 30 | 🔒 CC |  |
| 23011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/191:0:0" width="20" height="20" align="absmiddle" alt="แรพพิดมูฟเมนท์"> แรพพิดมูฟเมนท์ | 4 | 🟢 Passive |  |
| 23010 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/190:0:0" width="20" height="20" align="absmiddle" alt="แรพพิดแอทแทค"> แรพพิดแอทแทค | 4 | 🟢 Passive |  |
| 25013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/189:0:0" width="20" height="20" align="absmiddle" alt="วิสเปอริ่งสตรีม"> วิสเปอริ่งสตรีม | 4 | 💥 AoE |  |
| 25016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/270:0:0" width="20" height="20" align="absmiddle" alt="วิสเปอริ่งอิเวชั่น"> วิสเปอริ่งอิเวชั่น | 5 | 💥 AoE |  |
| 25012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/188:0:0" width="20" height="20" align="absmiddle" alt="วิสเปอริ่งไฟเออร์"> วิสเปอริ่งไฟเออร์ | 8 | 💥 AoE |  |

<details><summary>⚠️ <strong>คำแนะนำการปรับสมดุล (2 รายการ)</strong></summary>

| # | ประเภท | มิติ | รายละเอียด | ไฟล์ที่แก้ | Gap |
|---|--------|------|----------|------------|-----|
| 1 | 🔧 ปรับ | AoE | ⚔️ ปรับค่า fUnitDataValueMul สกิล AoE ที่มี (×1.3-1.5) | `SkillScript.bin.txt` | 1.0 |
| 2 | ➕ เพิ่ม | CC | 🔒 เพิ่มสกิล CC อีก 1 ตัว (มี 2) | `Skill_Get_List / Skill_Buff_List` | 6.2 |

</details>

---

#### 2155 Magnus (C5)

> 🔴 **Overall: 78.7**/100 · DMG `100` · AoE `95` · CC `96` · Util `64` · Surv `36`

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 21007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/44:0:0" width="20" height="20" align="absmiddle" alt="ฮาร์มสตริง"> ฮาร์มสตริง | 20 | 🔒 CC |  |
| 21011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/84:0:0" width="20" height="20" align="absmiddle" alt="เพียร์ซซิ่งช๊อต"> เพียร์ซซิ่งช๊อต | 20 | 💥 AoE |  |
| 21014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/106:0:0" width="20" height="20" align="absmiddle" alt="ไอซ์เรนนิ่ง"> ไอซ์เรนนิ่ง | 30 | 💥 AoE |  |
| 21019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/173:0:0" width="20" height="20" align="absmiddle" alt="ไฟเออร์แอโรว์"> ไฟเออร์แอโรว์ | 30 | 💥 AoE |  |
| 21020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/174:0:0" width="20" height="20" align="absmiddle" alt="แรพพิดแอโรว์"> แรพพิดแอโรว์ | 15 | 🔒 CC |  |
| 21038 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/84:0:0" width="20" height="20" align="absmiddle" alt="เมจิคแอโรว์"> เมจิคแอโรว์ | 10 | ⚔️ Attack |  |
| 23001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/35:0:0" width="20" height="20" align="absmiddle" alt="โบวเทรนนิ่ง"> โบวเทรนนิ่ง | 20 | 🟢 Passive |  |
| 23004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/39:0:0" width="20" height="20" align="absmiddle" alt="ไบลนด์ไซด์"> ไบลนด์ไซด์ | 8 | 🟢 Passive |  |
| 23006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/41:0:0" width="20" height="20" align="absmiddle" alt="ลองช๊อต"> ลองช๊อต | 6 | 🟢 Passive |  |
| 25001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/32:0:0" width="20" height="20" align="absmiddle" alt="เซฟเฟอร์"> เซฟเฟอร์ | 5 | ✨ Buff |  |
| 25003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/34:0:0" width="20" height="20" align="absmiddle" alt="เฟทอลทัช"> เฟทอลทัช | 6 | ✨ Buff |  |
| 25004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/47:0:0" width="20" height="20" align="absmiddle" alt="ควิคมูฟ"> ควิคมูฟ | 8 | ✨ Buff |  |
| 25019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/435:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สไซต์"> รีอินฟอร์สไซต์ | 10 | 💥 AoE |  |
| 25020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/436:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งโร๊ค"> เบลสซิ่งโร๊ค | 10 | 🔄 Toggle |  |
| 21004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/30:0:0" width="20" height="20" align="absmiddle" alt="นีดเดิ้ลช๊อต"> นีดเดิ้ลช๊อต | 30 | 💀 Debuff |  |
| 21013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/108:0:0" width="20" height="20" align="absmiddle" alt="ฟาวน์ดิ้งช๊อต"> ฟาวน์ดิ้งช๊อต | 30 | 🔒 CC |  |

<details><summary>⚠️ <strong>คำแนะนำการปรับสมดุล (2 รายการ)</strong></summary>

| # | ประเภท | มิติ | รายละเอียด | ไฟล์ที่แก้ | Gap |
|---|--------|------|----------|------------|-----|
| 1 | 🔧 ปรับ | Survivability | 🛡️ ปรับค่า fStatusDataMul สกิลบัฟ/ฮีล (×1.3-1.5) | `Skill_Buff_List.bin.txt` | 29.0 |
| 2 | 🔧 ปรับ | Utility | ✨ ปรับค่า fStatusDataMul สกิลบัฟ (×1.3-1.5) | `Skill_Buff_List.bin.txt` | 11.0 |

</details>

---

### Elf Rogue

#### 2211 โร้ก (C1)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 21001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/27:0:0" width="20" height="20" align="absmiddle" alt="ดัสก์สแลชชิ่ง"> ดัสก์สแลชชิ่ง | 5 | 💀 Debuff |  |
| 21002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/28:0:0" width="20" height="20" align="absmiddle" alt="ฮาร์ทบลาสท์"> ฮาร์ทบลาสท์ | 5 | ⚔️ Attack |  |
| 21003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/29:0:0" width="20" height="20" align="absmiddle" alt="พาวเวอร์ช๊อต"> พาวเวอร์ช๊อต | 5 | ⚔️ Attack |  |
| 21004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/30:0:0" width="20" height="20" align="absmiddle" alt="นีดเดิ้ลช๊อต"> นีดเดิ้ลช๊อต | 5 | 💀 Debuff |  |
| 23003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/38:0:0" width="20" height="20" align="absmiddle" alt="ไลท์อีเวชั่น"> ไลท์อีเวชั่น | 2 | 🟢 Passive |  |
| 23004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/39:0:0" width="20" height="20" align="absmiddle" alt="ไบลนด์ไซด์"> ไบลนด์ไซด์ | 1 | 🟢 Passive |  |
| 25001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/32:0:0" width="20" height="20" align="absmiddle" alt="เซฟเฟอร์"> เซฟเฟอร์ | 1 | ✨ Buff |  |
| 25004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/47:0:0" width="20" height="20" align="absmiddle" alt="ควิคมูฟ"> ควิคมูฟ | 1 | ✨ Buff |  |
| 25017 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/433:0:0" width="20" height="20" align="absmiddle" alt="ดีโทรปว๊อยส์"> ดีโทรปว๊อยส์ | 15 | 🔒 CC |  |
| 25018 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/434:0:0" width="20" height="20" align="absmiddle" alt="แซนด์สเปรย์"> แซนด์สเปรย์ | 15 | 💥 AoE |  |
| 25019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/435:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สไซต์"> รีอินฟอร์สไซต์ | 2 | 💥 AoE |  |
| 25020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/436:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งโร๊ค"> เบลสซิ่งโร๊ค | 2 | 🔄 Toggle |  |
| 25021 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/437:0:0" width="20" height="20" align="absmiddle" alt="ลัคกี้โพสิชั่น"> ลัคกี้โพสิชั่น | 15 | 🟢 Passive |  |
| 25022 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/438:0:0" width="20" height="20" align="absmiddle" alt="บลัฟโพสิชั่น"> บลัฟโพสิชั่น | 15 | 🟢 Passive |  |
| 14003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/2:0:0" width="20" height="20" align="absmiddle" alt="เนเจอร์ชิลด์"> เนเจอร์ชิลด์ | 2 | 🔄 Toggle |  |
| 14004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/3:0:0" width="20" height="20" align="absmiddle" alt="เนเจอร์มายด์"> เนเจอร์มายด์ | 2 | 🔄 Toggle |  |

---

#### 2221 วอยเอเจอร์ (C2)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 21003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/29:0:0" width="20" height="20" align="absmiddle" alt="พาวเวอร์ช๊อต"> พาวเวอร์ช๊อต | 10 | ⚔️ Attack |  |
| 21004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/30:0:0" width="20" height="20" align="absmiddle" alt="นีดเดิ้ลช๊อต"> นีดเดิ้ลช๊อต | 10 | 💀 Debuff |  |
| 21007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/44:0:0" width="20" height="20" align="absmiddle" alt="ฮาร์มสตริง"> ฮาร์มสตริง | 5 | 🔒 CC |  |
| 21011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/84:0:0" width="20" height="20" align="absmiddle" alt="เพียร์ซซิ่งช๊อต"> เพียร์ซซิ่งช๊อต | 5 | 💥 AoE |  |
| 23004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/39:0:0" width="20" height="20" align="absmiddle" alt="ไบลนด์ไซด์"> ไบลนด์ไซด์ | 2 | 🟢 Passive |  |
| 25001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/32:0:0" width="20" height="20" align="absmiddle" alt="เซฟเฟอร์"> เซฟเฟอร์ | 2 | ✨ Buff |  |
| 25004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/47:0:0" width="20" height="20" align="absmiddle" alt="ควิคมูฟ"> ควิคมูฟ | 3 | ✨ Buff |  |
| 25019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/435:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สไซต์"> รีอินฟอร์สไซต์ | 4 | 💥 AoE |  |
| 25020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/436:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งโร๊ค"> เบลสซิ่งโร๊ค | 4 | 🔄 Toggle |  |

---

#### 2222 Hunter (C2)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 21001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/27:0:0" width="20" height="20" align="absmiddle" alt="ดัสก์สแลชชิ่ง"> ดัสก์สแลชชิ่ง | 10 | 💀 Debuff |  |
| 21002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/28:0:0" width="20" height="20" align="absmiddle" alt="ฮาร์ทบลาสท์"> ฮาร์ทบลาสท์ | 10 | ⚔️ Attack |  |
| 21009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/46:0:0" width="20" height="20" align="absmiddle" alt="เพอร์โฟเรท"> เพอร์โฟเรท | 5 | ⚔️ Attack |  |
| 21012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/85:0:0" width="20" height="20" align="absmiddle" alt="วินด์เบรคกิ้ง"> วินด์เบรคกิ้ง | 5 | 💥 AoE |  |
| 23003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/38:0:0" width="20" height="20" align="absmiddle" alt="ไลท์อีเวชั่น"> ไลท์อีเวชั่น | 4 | 🟢 Passive |  |
| 23004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/39:0:0" width="20" height="20" align="absmiddle" alt="ไบลนด์ไซด์"> ไบลนด์ไซด์ | 3 | 🟢 Passive |  |
| 25001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/32:0:0" width="20" height="20" align="absmiddle" alt="เซฟเฟอร์"> เซฟเฟอร์ | 3 | ✨ Buff |  |
| 25004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/47:0:0" width="20" height="20" align="absmiddle" alt="ควิคมูฟ"> ควิคมูฟ | 2 | ✨ Buff |  |
| 25019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/435:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สไซต์"> รีอินฟอร์สไซต์ | 4 | 💥 AoE |  |
| 25020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/436:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งโร๊ค"> เบลสซิ่งโร๊ค | 4 | 🔄 Toggle |  |

---

#### 2231 เทรเชอร์ฮันเตอร์ (C3)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 21003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/29:0:0" width="20" height="20" align="absmiddle" alt="พาวเวอร์ช๊อต"> พาวเวอร์ช๊อต | 15 | ⚔️ Attack |  |
| 21004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/30:0:0" width="20" height="20" align="absmiddle" alt="นีดเดิ้ลช๊อต"> นีดเดิ้ลช๊อต | 15 | 💀 Debuff |  |
| 21007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/44:0:0" width="20" height="20" align="absmiddle" alt="ฮาร์มสตริง"> ฮาร์มสตริง | 10 | 🔒 CC |  |
| 21011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/84:0:0" width="20" height="20" align="absmiddle" alt="เพียร์ซซิ่งช๊อต"> เพียร์ซซิ่งช๊อต | 10 | 💥 AoE |  |
| 21014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/106:0:0" width="20" height="20" align="absmiddle" alt="ไอซ์เรนนิ่ง"> ไอซ์เรนนิ่ง | 5 | 💥 AoE |  |
| 23001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/35:0:0" width="20" height="20" align="absmiddle" alt="โบวเทรนนิ่ง"> โบวเทรนนิ่ง | 5 | 🟢 Passive |  |
| 23004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/39:0:0" width="20" height="20" align="absmiddle" alt="ไบลนด์ไซด์"> ไบลนด์ไซด์ | 4 | 🟢 Passive |  |
| 25001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/32:0:0" width="20" height="20" align="absmiddle" alt="เซฟเฟอร์"> เซฟเฟอร์ | 3 | ✨ Buff |  |
| 25004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/47:0:0" width="20" height="20" align="absmiddle" alt="ควิคมูฟ"> ควิคมูฟ | 5 | ✨ Buff |  |
| 25019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/435:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สไซต์"> รีอินฟอร์สไซต์ | 6 | 💥 AoE |  |
| 25020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/436:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งโร๊ค"> เบลสซิ่งโร๊ค | 6 | 🔄 Toggle |  |

---

#### 2232 Assasin (C3)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 21001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/27:0:0" width="20" height="20" align="absmiddle" alt="ดัสก์สแลชชิ่ง"> ดัสก์สแลชชิ่ง | 15 | 💀 Debuff |  |
| 21002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/28:0:0" width="20" height="20" align="absmiddle" alt="ฮาร์ทบลาสท์"> ฮาร์ทบลาสท์ | 15 | ⚔️ Attack |  |
| 21009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/46:0:0" width="20" height="20" align="absmiddle" alt="เพอร์โฟเรท"> เพอร์โฟเรท | 10 | ⚔️ Attack |  |
| 21012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/85:0:0" width="20" height="20" align="absmiddle" alt="วินด์เบรคกิ้ง"> วินด์เบรคกิ้ง | 10 | 💥 AoE |  |
| 21025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/179:0:0" width="20" height="20" align="absmiddle" alt="เดซี่โบลว"> เดซี่โบลว | 5 | 💥 AoE |  |
| 23003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/38:0:0" width="20" height="20" align="absmiddle" alt="ไลท์อีเวชั่น"> ไลท์อีเวชั่น | 6 | 🟢 Passive |  |
| 23004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/39:0:0" width="20" height="20" align="absmiddle" alt="ไบลนด์ไซด์"> ไบลนด์ไซด์ | 5 | 🟢 Passive |  |
| 25001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/32:0:0" width="20" height="20" align="absmiddle" alt="เซฟเฟอร์"> เซฟเฟอร์ | 5 | ✨ Buff |  |
| 25004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/47:0:0" width="20" height="20" align="absmiddle" alt="ควิคมูฟ"> ควิคมูฟ | 3 | ✨ Buff |  |
| 25007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/112:0:0" width="20" height="20" align="absmiddle" alt="สเทลธ์"> สเทลธ์ | 2 | 🔄 Toggle |  |
| 25019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/435:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สไซต์"> รีอินฟอร์สไซต์ | 6 | 💥 AoE |  |
| 25020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/436:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งโร๊ค"> เบลสซิ่งโร๊ค | 6 | 🔄 Toggle |  |

---

#### 2233 เรนเจอร์ (C3)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 21001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/27:0:0" width="20" height="20" align="absmiddle" alt="ดัสก์สแลชชิ่ง"> ดัสก์สแลชชิ่ง | 15 | 💀 Debuff |  |
| 21002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/28:0:0" width="20" height="20" align="absmiddle" alt="ฮาร์ทบลาสท์"> ฮาร์ทบลาสท์ | 15 | ⚔️ Attack |  |
| 21003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/29:0:0" width="20" height="20" align="absmiddle" alt="พาวเวอร์ช๊อต"> พาวเวอร์ช๊อต | 15 | ⚔️ Attack |  |
| 21004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/30:0:0" width="20" height="20" align="absmiddle" alt="นีดเดิ้ลช๊อต"> นีดเดิ้ลช๊อต | 15 | 💀 Debuff |  |
| 21011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/84:0:0" width="20" height="20" align="absmiddle" alt="เพียร์ซซิ่งช๊อต"> เพียร์ซซิ่งช๊อต | 10 | 💥 AoE |  |
| 21012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/85:0:0" width="20" height="20" align="absmiddle" alt="วินด์เบรคกิ้ง"> วินด์เบรคกิ้ง | 10 | 💥 AoE |  |
| 21016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/61:0:0" width="20" height="20" align="absmiddle" alt="เนเจอร์เอด"> เนเจอร์เอด | 5 | ⚔️ Attack |  |
| 21017 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/74:0:0" width="20" height="20" align="absmiddle" alt="พอยซั่นเอด"> พอยซั่นเอด | 1 | ⚔️ Attack |  |
| 25001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/32:0:0" width="20" height="20" align="absmiddle" alt="เซฟเฟอร์"> เซฟเฟอร์ | 5 | ✨ Buff |  |
| 25004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/47:0:0" width="20" height="20" align="absmiddle" alt="ควิคมูฟ"> ควิคมูฟ | 4 | ✨ Buff |  |
| 25005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/116:0:0" width="20" height="20" align="absmiddle" alt="ไซด์สเต็ป"> ไซด์สเต็ป | 3 | ✨ Buff |  |
| 25006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/117:0:0" width="20" height="20" align="absmiddle" alt="วิสเพอริ่งวินด์"> วิสเพอริ่งวินด์ | 3 | 💥 AoE |  |
| 25019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/435:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สไซต์"> รีอินฟอร์สไซต์ | 6 | 💥 AoE |  |
| 25020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/436:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งโร๊ค"> เบลสซิ่งโร๊ค | 6 | 🔄 Toggle |  |

---

#### 2241 Rune Walker (C4)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 21003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/29:0:0" width="20" height="20" align="absmiddle" alt="พาวเวอร์ช๊อต"> พาวเวอร์ช๊อต | 30 | ⚔️ Attack |  |
| 21004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/30:0:0" width="20" height="20" align="absmiddle" alt="นีดเดิ้ลช๊อต"> นีดเดิ้ลช๊อต | 30 | 💀 Debuff |  |
| 21007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/44:0:0" width="20" height="20" align="absmiddle" alt="ฮาร์มสตริง"> ฮาร์มสตริง | 15 | 🔒 CC |  |
| 21011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/84:0:0" width="20" height="20" align="absmiddle" alt="เพียร์ซซิ่งช๊อต"> เพียร์ซซิ่งช๊อต | 15 | 💥 AoE |  |
| 21014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/106:0:0" width="20" height="20" align="absmiddle" alt="ไอซ์เรนนิ่ง"> ไอซ์เรนนิ่ง | 10 | 💥 AoE |  |
| 21020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/174:0:0" width="20" height="20" align="absmiddle" alt="แรพพิดแอโรว์"> แรพพิดแอโรว์ | 5 | 🔒 CC |  |
| 23001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/35:0:0" width="20" height="20" align="absmiddle" alt="โบวเทรนนิ่ง"> โบวเทรนนิ่ง | 10 | 🟢 Passive |  |
| 23004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/39:0:0" width="20" height="20" align="absmiddle" alt="ไบลนด์ไซด์"> ไบลนด์ไซด์ | 6 | 🟢 Passive |  |
| 23006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/41:0:0" width="20" height="20" align="absmiddle" alt="ลองช๊อต"> ลองช๊อต | 3 | 🟢 Passive |  |
| 25001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/32:0:0" width="20" height="20" align="absmiddle" alt="เซฟเฟอร์"> เซฟเฟอร์ | 4 | ✨ Buff |  |
| 25003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/34:0:0" width="20" height="20" align="absmiddle" alt="เฟทอลทัช"> เฟทอลทัช | 3 | ✨ Buff |  |
| 25004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/47:0:0" width="20" height="20" align="absmiddle" alt="ควิคมูฟ"> ควิคมูฟ | 7 | ✨ Buff |  |
| 25019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/435:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สไซต์"> รีอินฟอร์สไซต์ | 8 | 💥 AoE |  |
| 25020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/436:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งโร๊ค"> เบลสซิ่งโร๊ค | 8 | 🔄 Toggle |  |

---

#### 2242 สเคาท์ (C4)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 13002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/11:0:0" width="20" height="20" align="absmiddle" alt="ไลท์อาร์เมอร์เอ็กเพอร์ไทซ์"> ไลท์อาร์เมอร์เอ็กเพอร์ไทซ์ | 15 | 🟢 Passive |  |
| 21002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/28:0:0" width="20" height="20" align="absmiddle" alt="ฮาร์ทบลาสท์"> ฮาร์ทบลาสท์ | 25 | ⚔️ Attack |  |
| 21022 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/176:0:0" width="20" height="20" align="absmiddle" alt="ฮันเตอร์พัม"> ฮันเตอร์พัม | 30 | 💥 AoE |  |
| 21023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/177:0:0" width="20" height="20" align="absmiddle" alt="ฮันเตอร์สโมค"> ฮันเตอร์สโมค | 10 | 💥 AoE |  |
| 21024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/178:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์บูมเมอแรง"> ชิลด์บูมเมอแรง | 10 | 🔒 CC |  |
| 23002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/36:0:0" width="20" height="20" align="absmiddle" alt="แด๊กเกอร์เทรนนิ่ง"> แด๊กเกอร์เทรนนิ่ง | 15 | 🟢 Passive |  |
| 25001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/32:0:0" width="20" height="20" align="absmiddle" alt="เซฟเฟอร์"> เซฟเฟอร์ | 6 | ✨ Buff |  |
| 25004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/47:0:0" width="20" height="20" align="absmiddle" alt="ควิคมูฟ"> ควิคมูฟ | 4 | ✨ Buff |  |
| 25019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/435:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สไซต์"> รีอินฟอร์สไซต์ | 8 | 💥 AoE |  |
| 25020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/436:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งโร๊ค"> เบลสซิ่งโร๊ค | 8 | 🔄 Toggle |  |
| 23004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/39:0:0" width="20" height="20" align="absmiddle" alt="ไบลนด์ไซด์"> ไบลนด์ไซด์ | 9 | 🟢 Passive |  |
| 21021 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/175:0:0" width="20" height="20" align="absmiddle" alt="เทคเกอร์โบลว"> เทคเกอร์โบลว | 15 | ⚔️ Attack |  |
| 13004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/20:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์เทรนนิ่ง"> ชิลด์เทรนนิ่ง | 10 | 🟢 Passive |  |

---

#### 2243 Arch Ranger (C4)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 21001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/27:0:0" width="20" height="20" align="absmiddle" alt="ดัสก์สแลชชิ่ง"> ดัสก์สแลชชิ่ง | 25 | 💀 Debuff |  |
| 21002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/28:0:0" width="20" height="20" align="absmiddle" alt="ฮาร์ทบลาสท์"> ฮาร์ทบลาสท์ | 25 | ⚔️ Attack |  |
| 21009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/46:0:0" width="20" height="20" align="absmiddle" alt="เพอร์โฟเรท"> เพอร์โฟเรท | 20 | ⚔️ Attack |  |
| 21012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/85:0:0" width="20" height="20" align="absmiddle" alt="วินด์เบรคกิ้ง"> วินด์เบรคกิ้ง | 15 | 💥 AoE |  |
| 21015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/115:0:0" width="20" height="20" align="absmiddle" alt="ซัดเดินเรด"> ซัดเดินเรด | 15 | 🔒 CC |  |
| 21025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/179:0:0" width="20" height="20" align="absmiddle" alt="เดซี่โบลว"> เดซี่โบลว | 20 | 💥 AoE |  |
| 21027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/181:0:0" width="20" height="20" align="absmiddle" alt="ไฟนอลโบลว"> ไฟนอลโบลว | 10 | ⚔️ Attack |  |
| 23002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/36:0:0" width="20" height="20" align="absmiddle" alt="แด๊กเกอร์เทรนนิ่ง"> แด๊กเกอร์เทรนนิ่ง | 10 | 🟢 Passive |  |
| 23003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/38:0:0" width="20" height="20" align="absmiddle" alt="ไลท์อีเวชั่น"> ไลท์อีเวชั่น | 8 | 🟢 Passive |  |
| 23004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/39:0:0" width="20" height="20" align="absmiddle" alt="ไบลนด์ไซด์"> ไบลนด์ไซด์ | 8 | 🟢 Passive |  |
| 25001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/32:0:0" width="20" height="20" align="absmiddle" alt="เซฟเฟอร์"> เซฟเฟอร์ | 7 | ✨ Buff |  |
| 25004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/47:0:0" width="20" height="20" align="absmiddle" alt="ควิคมูฟ"> ควิคมูฟ | 4 | ✨ Buff |  |
| 25007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/112:0:0" width="20" height="20" align="absmiddle" alt="สเทลธ์"> สเทลธ์ | 4 | 🔄 Toggle |  |
| 25011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/187:0:0" width="20" height="20" align="absmiddle" alt="พรีเดเตอร์"> พรีเดเตอร์ | 2 | ✨ Buff |  |
| 25019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/435:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สไซต์"> รีอินฟอร์สไซต์ | 8 | 💥 AoE |  |
| 25020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/436:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งโร๊ค"> เบลสซิ่งโร๊ค | 8 | 🔄 Toggle |  |

---

#### 2244 Thief Master (C4)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 21001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/27:0:0" width="20" height="20" align="absmiddle" alt="ดัสก์สแลชชิ่ง"> ดัสก์สแลชชิ่ง | 25 | 💀 Debuff |  |
| 21002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/28:0:0" width="20" height="20" align="absmiddle" alt="ฮาร์ทบลาสท์"> ฮาร์ทบลาสท์ | 25 | ⚔️ Attack |  |
| 21003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/29:0:0" width="20" height="20" align="absmiddle" alt="พาวเวอร์ช๊อต"> พาวเวอร์ช๊อต | 30 | ⚔️ Attack |  |
| 21004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/30:0:0" width="20" height="20" align="absmiddle" alt="นีดเดิ้ลช๊อต"> นีดเดิ้ลช๊อต | 30 | 💀 Debuff |  |
| 21011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/84:0:0" width="20" height="20" align="absmiddle" alt="เพียร์ซซิ่งช๊อต"> เพียร์ซซิ่งช๊อต | 15 | 💥 AoE |  |
| 21012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/85:0:0" width="20" height="20" align="absmiddle" alt="วินด์เบรคกิ้ง"> วินด์เบรคกิ้ง | 15 | 💥 AoE |  |
| 21016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/61:0:0" width="20" height="20" align="absmiddle" alt="เนเจอร์เอด"> เนเจอร์เอด | 10 | ⚔️ Attack |  |
| 21017 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/74:0:0" width="20" height="20" align="absmiddle" alt="พอยซั่นเอด"> พอยซั่นเอด | 2 | ⚔️ Attack |  |
| 21028 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/182:0:0" width="20" height="20" align="absmiddle" alt="แคสติ้งฟอยล์"> แคสติ้งฟอยล์ | 2 | 🔒 CC |  |
| 21029 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/183:0:0" width="20" height="20" align="absmiddle" alt="สแลค"> สแลค | 2 | 💀 Debuff |  |
| 25001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/32:0:0" width="20" height="20" align="absmiddle" alt="เซฟเฟอร์"> เซฟเฟอร์ | 6 | ✨ Buff |  |
| 25004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/47:0:0" width="20" height="20" align="absmiddle" alt="ควิคมูฟ"> ควิคมูฟ | 6 | ✨ Buff |  |
| 25005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/116:0:0" width="20" height="20" align="absmiddle" alt="ไซด์สเต็ป"> ไซด์สเต็ป | 6 | ✨ Buff |  |
| 25006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/117:0:0" width="20" height="20" align="absmiddle" alt="วิสเพอริ่งวินด์"> วิสเพอริ่งวินด์ | 6 | 💥 AoE |  |
| 25019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/435:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สไซต์"> รีอินฟอร์สไซต์ | 8 | 💥 AoE |  |
| 25020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/436:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งโร๊ค"> เบลสซิ่งโร๊ค | 8 | 🔄 Toggle |  |
| 23011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/191:0:0" width="20" height="20" align="absmiddle" alt="แรพพิดมูฟเมนท์"> แรพพิดมูฟเมนท์ | 2 | 🟢 Passive |  |
| 23010 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/190:0:0" width="20" height="20" align="absmiddle" alt="แรพพิดแอทแทค"> แรพพิดแอทแทค | 2 | 🟢 Passive |  |

---

#### 2251 เอ็นแทรปเปอร์ (C5)

> 🟢 **Overall: 88.2**/100 · DMG `95` · AoE `80` · CC `74` · Util `99` · Surv `90`

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 13025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/357:0:0" width="20" height="20" align="absmiddle" alt="มัสเกทเทรนนิ่ง"> มัสเกทเทรนนิ่ง | 20 | 🟢 Passive |  |
| 21033 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/271:0:0" width="20" height="20" align="absmiddle" alt="สแตนดิ้งช๊อต"> สแตนดิ้งช๊อต | 20 | ⚔️ Attack |  |
| 21034 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/359:0:0" width="20" height="20" align="absmiddle" alt="ไวลด์ช๊อต"> ไวลด์ช๊อต | 20 | 💥 AoE |  |
| 21035 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/272:0:0" width="20" height="20" align="absmiddle" alt="นีลลิ่งไฟร์"> นีลลิ่งไฟร์ | 30 | 💥 AoE |  |
| 21036 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/273:0:0" width="20" height="20" align="absmiddle" alt="พรอกซิมิตี้ไฟร์"> พรอกซิมิตี้ไฟร์ | 30 | 🔒 CC |  |
| 21037 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/274:0:0" width="20" height="20" align="absmiddle" alt="แฟลชไฟร์"> แฟลชไฟร์ | 30 | 🔒 CC |  |
| 23004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/39:0:0" width="20" height="20" align="absmiddle" alt="ไบลนด์ไซด์"> ไบลนด์ไซด์ | 8 | 🟢 Passive |  |
| 23013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/358:0:0" width="20" height="20" align="absmiddle" alt="มัสเกทเรนจ์"> มัสเกทเรนจ์ | 5 | 🟢 Passive |  |
| 25001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/32:0:0" width="20" height="20" align="absmiddle" alt="เซฟเฟอร์"> เซฟเฟอร์ | 5 | ✨ Buff |  |
| 25003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/34:0:0" width="20" height="20" align="absmiddle" alt="เฟทอลทัช"> เฟทอลทัช | 6 | ✨ Buff |  |
| 25004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/47:0:0" width="20" height="20" align="absmiddle" alt="ควิคมูฟ"> ควิคมูฟ | 9 | ✨ Buff |  |
| 25019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/435:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สไซต์"> รีอินฟอร์สไซต์ | 10 | 💥 AoE |  |
| 25020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/436:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งโร๊ค"> เบลสซิ่งโร๊ค | 10 | 🔄 Toggle |  |
| 25014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/276:0:0" width="20" height="20" align="absmiddle" alt="มัสเกทสโคป"> มัสเกทสโคป | 10 | ✨ Buff |  |
| 15020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/355:0:0" width="20" height="20" align="absmiddle" alt="รีโหลดดิ้ง"> รีโหลดดิ้ง | 5 | 🩹 Heal |  |
| 23007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/42:0:0" width="20" height="20" align="absmiddle" alt="อีเกิ้ลอาย"> อีเกิ้ลอาย | 10 | 🟢 Passive |  |
| 23005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/40:0:0" width="20" height="20" align="absmiddle" alt="เดธซายน์"> เดธซายน์ | 8 | 🟢 Passive |  |
| 25009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/185:0:0" width="20" height="20" align="absmiddle" alt="ฟาสต์รีโหลด"> ฟาสต์รีโหลด | 4 | 🩹 Heal |  |

<details><summary>⚠️ <strong>คำแนะนำการปรับสมดุล (1 รายการ)</strong></summary>

| # | ประเภท | มิติ | รายละเอียด | ไฟล์ที่แก้ | Gap |
|---|--------|------|----------|------------|-----|
| 1 | ➕ เพิ่ม | CC | 🔒 เพิ่มสกิล CC อีก 1 ตัว (มี 2) | `Skill_Get_List / Skill_Buff_List` | 1.0 |

</details>

---

#### 2252 Tempest (C5)

> 🟡 **Overall: 83.1**/100 · DMG `100` · AoE `78` · CC `96` · Util `72` · Surv `64`

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 13002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/11:0:0" width="20" height="20" align="absmiddle" alt="ไลท์อาร์เมอร์เอ็กเพอร์ไทซ์"> ไลท์อาร์เมอร์เอ็กเพอร์ไทซ์ | 25 | 🟢 Passive |  |
| 21022 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/176:0:0" width="20" height="20" align="absmiddle" alt="ฮันเตอร์พัม"> ฮันเตอร์พัม | 30 | 💥 AoE |  |
| 21023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/177:0:0" width="20" height="20" align="absmiddle" alt="ฮันเตอร์สโมค"> ฮันเตอร์สโมค | 10 | 💥 AoE |  |
| 21024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/178:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์บูมเมอแรง"> ชิลด์บูมเมอแรง | 30 | 🔒 CC |  |
| 21031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/263:0:0" width="20" height="20" align="absmiddle" alt="ไฟร์แทรป"> ไฟร์แทรป | 5 | ⚔️ Attack | ⚠️ DPS ต่ำ (30) |
| 21032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/263:0:0" width="20" height="20" align="absmiddle" alt="ไอซ์แทรป"> ไอซ์แทรป | 5 | ⚔️ Attack | ⚠️ DPS ต่ำ (31) |
| 25001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/32:0:0" width="20" height="20" align="absmiddle" alt="เซฟเฟอร์"> เซฟเฟอร์ | 9 | ✨ Buff |  |
| 25004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/47:0:0" width="20" height="20" align="absmiddle" alt="ควิคมูฟ"> ควิคมูฟ | 5 | ✨ Buff |  |
| 25019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/435:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สไซต์"> รีอินฟอร์สไซต์ | 10 | 💥 AoE |  |
| 25020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/436:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งโร๊ค"> เบลสซิ่งโร๊ค | 10 | 🔄 Toggle |  |
| 23002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/36:0:0" width="20" height="20" align="absmiddle" alt="แด๊กเกอร์เทรนนิ่ง"> แด๊กเกอร์เทรนนิ่ง | 20 | 🟢 Passive |  |
| 23003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/38:0:0" width="20" height="20" align="absmiddle" alt="ไลท์อีเวชั่น"> ไลท์อีเวชั่น | 10 | 🟢 Passive |  |
| 25011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/187:0:0" width="20" height="20" align="absmiddle" alt="พรีเดเตอร์"> พรีเดเตอร์ | 4 | ✨ Buff |  |
| 21021 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/175:0:0" width="20" height="20" align="absmiddle" alt="เทคเกอร์โบลว"> เทคเกอร์โบลว | 30 | ⚔️ Attack |  |
| 21012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/85:0:0" width="20" height="20" align="absmiddle" alt="วินด์เบรคกิ้ง"> วินด์เบรคกิ้ง | 30 | 💥 AoE |  |
| 21041 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/108:0:0" width="20" height="20" align="absmiddle" alt="แคชพาวน์ดิ้ง"> แคชพาวน์ดิ้ง | 20 | 🔒 CC |  |
| 21009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/46:0:0" width="20" height="20" align="absmiddle" alt="เพอร์โฟเรท"> เพอร์โฟเรท | 30 | ⚔️ Attack |  |
| 21008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/45:0:0" width="20" height="20" align="absmiddle" alt="เรจสเต็ป"> เรจสเต็ป | 30 | 🔒 CC |  |
| 25002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/33:0:0" width="20" height="20" align="absmiddle" alt="ดีเทคโฮล"> ดีเทคโฮล | 8 | ✨ Buff |  |
| 23009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/137:0:0" width="20" height="20" align="absmiddle" alt="ไดอาบอลิคอินสติงท์"> ไดอาบอลิคอินสติงท์ | 7 | 🟢 Passive |  |
| 23004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/39:0:0" width="20" height="20" align="absmiddle" alt="ไบลนด์ไซด์"> ไบลนด์ไซด์ | 9 | 🟢 Passive |  |
| 13004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/20:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์เทรนนิ่ง"> ชิลด์เทรนนิ่ง | 20 | 🟢 Passive |  |

<details><summary>⚠️ <strong>คำแนะนำการปรับสมดุล (3 รายการ)</strong></summary>

| # | ประเภท | มิติ | รายละเอียด | ไฟล์ที่แก้ | Gap |
|---|--------|------|----------|------------|-----|
| 1 | 🔧 ปรับ | AoE | ⚔️ ปรับค่า fUnitDataValueMul สกิล AoE ที่มี (×1.3-1.5) | `SkillScript.bin.txt` | 2.4 |
| 2 | 🔧 ปรับ | Survivability | 🛡️ ปรับค่า fStatusDataMul สกิลบัฟ/ฮีล (×1.3-1.5) | `Skill_Buff_List.bin.txt` | 1.0 |
| 3 | 🔧 ปรับ | Utility | ✨ ปรับค่า fStatusDataMul สกิลบัฟ (×1.3-1.5) | `Skill_Buff_List.bin.txt` | 3.0 |

</details>

---

#### 2253 เบลดเทคเกอร์ (C5)

> 🔴 **Overall: 76.7**/100 · DMG `100` · AoE `80` · CC `62` · Util `66` · Surv `64`

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 13022 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/267:0:0" width="20" height="20" align="absmiddle" alt="ดูอัลวิปพอนเทรนนิ่ง"> ดูอัลวิปพอนเทรนนิ่ง | 10 | 🟢 Passive |  |
| 13026 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/268:0:0" width="20" height="20" align="absmiddle" alt="ดูอัลวิปพอนมาสเตอรี่"> ดูอัลวิปพอนมาสเตอรี่ | 10 | 🟢 Passive |  |
| 21009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/46:0:0" width="20" height="20" align="absmiddle" alt="เพอร์โฟเรท"> เพอร์โฟเรท | 30 | ⚔️ Attack |  |
| 21012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/85:0:0" width="20" height="20" align="absmiddle" alt="วินด์เบรคกิ้ง"> วินด์เบรคกิ้ง | 30 | 💥 AoE |  |
| 21015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/115:0:0" width="20" height="20" align="absmiddle" alt="ซัดเดินเรด"> ซัดเดินเรด | 30 | 🔒 CC |  |
| 21025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/179:0:0" width="20" height="20" align="absmiddle" alt="เดซี่โบลว"> เดซี่โบลว | 30 | 💥 AoE |  |
| 21027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/181:0:0" width="20" height="20" align="absmiddle" alt="ไฟนอลโบลว"> ไฟนอลโบลว | 15 | ⚔️ Attack |  |
| 21042 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/264:0:0" width="20" height="20" align="absmiddle" alt="เดดลี่สไตรค์"> เดดลี่สไตรค์ | 10 | ⚔️ Attack |  |
| 23002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/36:0:0" width="20" height="20" align="absmiddle" alt="แด๊กเกอร์เทรนนิ่ง"> แด๊กเกอร์เทรนนิ่ง | 20 | 🟢 Passive |  |
| 23003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/38:0:0" width="20" height="20" align="absmiddle" alt="ไลท์อีเวชั่น"> ไลท์อีเวชั่น | 10 | 🟢 Passive |  |
| 23004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/39:0:0" width="20" height="20" align="absmiddle" alt="ไบลนด์ไซด์"> ไบลนด์ไซด์ | 10 | 🟢 Passive |  |
| 25001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/32:0:0" width="20" height="20" align="absmiddle" alt="เซฟเฟอร์"> เซฟเฟอร์ | 9 | ✨ Buff |  |
| 25004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/47:0:0" width="20" height="20" align="absmiddle" alt="ควิคมูฟ"> ควิคมูฟ | 5 | ✨ Buff |  |
| 25007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/112:0:0" width="20" height="20" align="absmiddle" alt="สเทลธ์"> สเทลธ์ | 6 | 🔄 Toggle |  |
| 25011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/187:0:0" width="20" height="20" align="absmiddle" alt="พรีเดเตอร์"> พรีเดเตอร์ | 4 | ✨ Buff |  |
| 25019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/435:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สไซต์"> รีอินฟอร์สไซต์ | 10 | 💥 AoE |  |
| 25020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/436:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งโร๊ค"> เบลสซิ่งโร๊ค | 10 | 🔄 Toggle |  |
| 13002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/11:0:0" width="20" height="20" align="absmiddle" alt="ไลท์อาร์เมอร์เอ็กเพอร์ไทซ์"> ไลท์อาร์เมอร์เอ็กเพอร์ไทซ์ | 8 | 🟢 Passive |  |
| 21021 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/175:0:0" width="20" height="20" align="absmiddle" alt="เทคเกอร์โบลว"> เทคเกอร์โบลว | 20 | ⚔️ Attack |  |
| 21030 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/184:0:0" width="20" height="20" align="absmiddle" alt="อิลลูชั่นแอทแทค"> อิลลูชั่นแอทแทค | 30 | 🔒 CC |  |

<details><summary>⚠️ <strong>คำแนะนำการปรับสมดุล (3 รายการ)</strong></summary>

| # | ประเภท | มิติ | รายละเอียด | ไฟล์ที่แก้ | Gap |
|---|--------|------|----------|------------|-----|
| 1 | ➕ เพิ่ม | CC | 🔒 เพิ่มสกิล CC อีก 1 ตัว (มี 2) | `Skill_Get_List / Skill_Buff_List` | 13.0 |
| 2 | 🔧 ปรับ | Survivability | 🛡️ ปรับค่า fStatusDataMul สกิลบัฟ/ฮีล (×1.3-1.5) | `Skill_Buff_List.bin.txt` | 1.0 |
| 3 | 🔧 ปรับ | Utility | ✨ ปรับค่า fStatusDataMul สกิลบัฟ (×1.3-1.5) | `Skill_Buff_List.bin.txt` | 9.0 |

</details>

---

#### 2254 Arch Breezer (C5)

> 🟡 **Overall: 80.4**/100 · DMG `100` · AoE `79` · CC `69` · Util `75` · Surv `70`

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 21011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/84:0:0" width="20" height="20" align="absmiddle" alt="เพียร์ซซิ่งช๊อต"> เพียร์ซซิ่งช๊อต | 20 | 💥 AoE |  |
| 21012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/85:0:0" width="20" height="20" align="absmiddle" alt="วินด์เบรคกิ้ง"> วินด์เบรคกิ้ง | 30 | 💥 AoE |  |
| 21016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/61:0:0" width="20" height="20" align="absmiddle" alt="เนเจอร์เอด"> เนเจอร์เอด | 15 | ⚔️ Attack | ⚠️ DPS ต่ำ (39) |
| 21017 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/74:0:0" width="20" height="20" align="absmiddle" alt="พอยซั่นเอด"> พอยซั่นเอด | 3 | ⚔️ Attack | ⚠️ DPS ต่ำ (15) |
| 21028 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/182:0:0" width="20" height="20" align="absmiddle" alt="แคสติ้งฟอยล์"> แคสติ้งฟอยล์ | 5 | 🔒 CC |  |
| 21029 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/183:0:0" width="20" height="20" align="absmiddle" alt="สแลค"> สแลค | 5 | 💀 Debuff |  |
| 21038 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/84:0:0" width="20" height="20" align="absmiddle" alt="เมจิคแอโรว์"> เมจิคแอโรว์ | 10 | ⚔️ Attack |  |
| 21042 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/264:0:0" width="20" height="20" align="absmiddle" alt="เดดลี่สไตรค์"> เดดลี่สไตรค์ | 10 | ⚔️ Attack |  |
| 21047 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/111:0:0" width="20" height="20" align="absmiddle" alt="เดดลี่โซล"> เดดลี่โซล | 10 | 💥 AoE |  |
| 25001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/32:0:0" width="20" height="20" align="absmiddle" alt="เซฟเฟอร์"> เซฟเฟอร์ | 8 | ✨ Buff |  |
| 25004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/47:0:0" width="20" height="20" align="absmiddle" alt="ควิคมูฟ"> ควิคมูฟ | 8 | ✨ Buff |  |
| 25005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/116:0:0" width="20" height="20" align="absmiddle" alt="ไซด์สเต็ป"> ไซด์สเต็ป | 9 | ✨ Buff |  |
| 25006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/117:0:0" width="20" height="20" align="absmiddle" alt="วิสเพอริ่งวินด์"> วิสเพอริ่งวินด์ | 9 | 💥 AoE |  |
| 25019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/435:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สไซต์"> รีอินฟอร์สไซต์ | 10 | 💥 AoE |  |
| 25020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/436:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งโร๊ค"> เบลสซิ่งโร๊ค | 10 | 🔄 Toggle |  |
| 23003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/38:0:0" width="20" height="20" align="absmiddle" alt="ไลท์อีเวชั่น"> ไลท์อีเวชั่น | 10 | 🟢 Passive |  |
| 13002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/11:0:0" width="20" height="20" align="absmiddle" alt="ไลท์อาร์เมอร์เอ็กเพอร์ไทซ์"> ไลท์อาร์เมอร์เอ็กเพอร์ไทซ์ | 25 | 🟢 Passive |  |
| 23008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/136:0:0" width="20" height="20" align="absmiddle" alt="ชาโดว์อินสติงท์"> ชาโดว์อินสติงท์ | 8 | 🟢 Passive |  |
| 23002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/36:0:0" width="20" height="20" align="absmiddle" alt="แด๊กเกอร์เทรนนิ่ง"> แด๊กเกอร์เทรนนิ่ง | 20 | 🟢 Passive |  |
| 13022 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/267:0:0" width="20" height="20" align="absmiddle" alt="ดูอัลวิปพอนเทรนนิ่ง"> ดูอัลวิปพอนเทรนนิ่ง | 10 | 🟢 Passive |  |
| 13026 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/268:0:0" width="20" height="20" align="absmiddle" alt="ดูอัลวิปพอนมาสเตอรี่"> ดูอัลวิปพอนมาสเตอรี่ | 10 | 🟢 Passive |  |
| 21002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/28:0:0" width="20" height="20" align="absmiddle" alt="ฮาร์ทบลาสท์"> ฮาร์ทบลาสท์ | 30 | ⚔️ Attack |  |
| 21001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/27:0:0" width="20" height="20" align="absmiddle" alt="ดัสก์สแลชชิ่ง"> ดัสก์สแลชชิ่ง | 30 | 💀 Debuff |  |
| 23001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/35:0:0" width="20" height="20" align="absmiddle" alt="โบวเทรนนิ่ง"> โบวเทรนนิ่ง | 20 | 🟢 Passive |  |
| 21003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/29:0:0" width="20" height="20" align="absmiddle" alt="พาวเวอร์ช๊อต"> พาวเวอร์ช๊อต | 30 | ⚔️ Attack |  |
| 21004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/30:0:0" width="20" height="20" align="absmiddle" alt="นีดเดิ้ลช๊อต"> นีดเดิ้ลช๊อต | 30 | 💀 Debuff |  |
| 21013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/108:0:0" width="20" height="20" align="absmiddle" alt="ฟาวน์ดิ้งช๊อต"> ฟาวน์ดิ้งช๊อต | 30 | 🔒 CC |  |
| 23011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/191:0:0" width="20" height="20" align="absmiddle" alt="แรพพิดมูฟเมนท์"> แรพพิดมูฟเมนท์ | 4 | 🟢 Passive |  |
| 23010 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/190:0:0" width="20" height="20" align="absmiddle" alt="แรพพิดแอทแทค"> แรพพิดแอทแทค | 4 | 🟢 Passive |  |
| 25013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/189:0:0" width="20" height="20" align="absmiddle" alt="วิสเปอริ่งสตรีม"> วิสเปอริ่งสตรีม | 4 | 💥 AoE |  |
| 25016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/270:0:0" width="20" height="20" align="absmiddle" alt="วิสเปอริ่งอิเวชั่น"> วิสเปอริ่งอิเวชั่น | 5 | 💥 AoE |  |
| 25012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/188:0:0" width="20" height="20" align="absmiddle" alt="วิสเปอริ่งไฟเออร์"> วิสเปอริ่งไฟเออร์ | 8 | 💥 AoE |  |

<details><summary>⚠️ <strong>คำแนะนำการปรับสมดุล (2 รายการ)</strong></summary>

| # | ประเภท | มิติ | รายละเอียด | ไฟล์ที่แก้ | Gap |
|---|--------|------|----------|------------|-----|
| 1 | 🔧 ปรับ | AoE | ⚔️ ปรับค่า fUnitDataValueMul สกิล AoE ที่มี (×1.3-1.5) | `SkillScript.bin.txt` | 1.0 |
| 2 | ➕ เพิ่ม | CC | 🔒 เพิ่มสกิล CC อีก 1 ตัว (มี 2) | `Skill_Get_List / Skill_Buff_List` | 6.2 |

</details>

---

#### 2255 Magnus (C5)

> 🔴 **Overall: 78.7**/100 · DMG `100` · AoE `95` · CC `96` · Util `64` · Surv `36`

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 21007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/44:0:0" width="20" height="20" align="absmiddle" alt="ฮาร์มสตริง"> ฮาร์มสตริง | 20 | 🔒 CC |  |
| 21011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/84:0:0" width="20" height="20" align="absmiddle" alt="เพียร์ซซิ่งช๊อต"> เพียร์ซซิ่งช๊อต | 20 | 💥 AoE |  |
| 21014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/106:0:0" width="20" height="20" align="absmiddle" alt="ไอซ์เรนนิ่ง"> ไอซ์เรนนิ่ง | 30 | 💥 AoE |  |
| 21019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/173:0:0" width="20" height="20" align="absmiddle" alt="ไฟเออร์แอโรว์"> ไฟเออร์แอโรว์ | 30 | 💥 AoE |  |
| 21020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/174:0:0" width="20" height="20" align="absmiddle" alt="แรพพิดแอโรว์"> แรพพิดแอโรว์ | 15 | 🔒 CC |  |
| 21038 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/84:0:0" width="20" height="20" align="absmiddle" alt="เมจิคแอโรว์"> เมจิคแอโรว์ | 10 | ⚔️ Attack |  |
| 23001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/35:0:0" width="20" height="20" align="absmiddle" alt="โบวเทรนนิ่ง"> โบวเทรนนิ่ง | 20 | 🟢 Passive |  |
| 23004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/39:0:0" width="20" height="20" align="absmiddle" alt="ไบลนด์ไซด์"> ไบลนด์ไซด์ | 8 | 🟢 Passive |  |
| 23006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/41:0:0" width="20" height="20" align="absmiddle" alt="ลองช๊อต"> ลองช๊อต | 6 | 🟢 Passive |  |
| 25001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/32:0:0" width="20" height="20" align="absmiddle" alt="เซฟเฟอร์"> เซฟเฟอร์ | 5 | ✨ Buff |  |
| 25003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/34:0:0" width="20" height="20" align="absmiddle" alt="เฟทอลทัช"> เฟทอลทัช | 6 | ✨ Buff |  |
| 25004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/47:0:0" width="20" height="20" align="absmiddle" alt="ควิคมูฟ"> ควิคมูฟ | 8 | ✨ Buff |  |
| 25019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/435:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สไซต์"> รีอินฟอร์สไซต์ | 10 | 💥 AoE |  |
| 25020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/436:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งโร๊ค"> เบลสซิ่งโร๊ค | 10 | 🔄 Toggle |  |
| 21004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/30:0:0" width="20" height="20" align="absmiddle" alt="นีดเดิ้ลช๊อต"> นีดเดิ้ลช๊อต | 30 | 💀 Debuff |  |
| 21013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/108:0:0" width="20" height="20" align="absmiddle" alt="ฟาวน์ดิ้งช๊อต"> ฟาวน์ดิ้งช๊อต | 30 | 🔒 CC |  |

<details><summary>⚠️ <strong>คำแนะนำการปรับสมดุล (2 รายการ)</strong></summary>

| # | ประเภท | มิติ | รายละเอียด | ไฟล์ที่แก้ | Gap |
|---|--------|------|----------|------------|-----|
| 1 | 🔧 ปรับ | Survivability | 🛡️ ปรับค่า fStatusDataMul สกิลบัฟ/ฮีล (×1.3-1.5) | `Skill_Buff_List.bin.txt` | 29.0 |
| 2 | 🔧 ปรับ | Utility | ✨ ปรับค่า fStatusDataMul สกิลบัฟ (×1.3-1.5) | `Skill_Buff_List.bin.txt` | 11.0 |

</details>

---

## 🔮 Mage (จอมเวท)

> **Avg Rating:** 79.8/100 · **C5 Jobs:** 10 · เน้นเวทมนตร์โจมตี ฮีล บัฟ และ CC ระยะไกล มีทั้งสายโจมตีและสายซัพพอร์ต
>
> DMG `96` · AoE `94` · CC `76` · Utility `77` · Survivability `52`

### Human Mage

#### 3111 เมจ (C1)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 32001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/48:0:0" width="20" height="20" align="absmiddle" alt="วินด์สไตรค์"> วินด์สไตรค์ | 5 | 🔒 CC |  |
| 32003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/50:0:0" width="20" height="20" align="absmiddle" alt="ไฟร์บอล"> ไฟร์บอล | 5 | ⚔️ Attack |  |
| 32013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/72:0:0" width="20" height="20" align="absmiddle" alt="ไอซ์แอโรว์"> ไอซ์แอโรว์ | 5 | 💀 Debuff |  |
| 32004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/51:0:0" width="20" height="20" align="absmiddle" alt="ฮีล"> ฮีล | 5 | ⚔️ Attack |  |
| 33005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/63:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ MP"> เอนฮานซ์ MP | 1 | 🟢 Passive |  |
| 35003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/57:0:0" width="20" height="20" align="absmiddle" alt="เบลสฮาร์ท"> เบลสฮาร์ท | 1 | ✨ Buff |  |
| 35029 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/439:0:0" width="20" height="20" align="absmiddle" alt="เบอร์ซิอุส"> เบอร์ซิอุส | 10 | 🔒 CC |  |
| 35030 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/440:0:0" width="20" height="20" align="absmiddle" alt="สคิปริสกี้"> สคิปริสกี้ | 15 | 🔒 CC |  |
| 35031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/441:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สวิสดอม"> รีอินฟอร์สวิสดอม | 2 | 💥 AoE |  |
| 35032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/442:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งเมจิก"> เบลสซิ่งเมจิก | 2 | 🔄 Toggle |  |
| 35033 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/443:0:0" width="20" height="20" align="absmiddle" alt="อินเทลิเจ้นท์โพสิชั่น"> อินเทลิเจ้นท์โพสิชั่น | 15 | 🟢 Passive |  |
| 35034 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/444:0:0" width="20" height="20" align="absmiddle" alt="เมนทัลโพสิชั่น"> เมนทัลโพสิชั่น | 15 | 🟢 Passive |  |
| 14001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/138:0:0" width="20" height="20" align="absmiddle" alt="เบิร์นนิ่งเรจ"> เบิร์นนิ่งเรจ | 2 | 🔄 Toggle |  |
| 14002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/1:0:0" width="20" height="20" align="absmiddle" alt="แลช"> แลช | 2 | 🔄 Toggle |  |

---

#### 3121 เคลอริค (C2)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 32007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/54:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่สไตรค์"> โฮลี่สไตรค์ | 5 | ⚔️ Attack |  |
| 32008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/64:0:0" width="20" height="20" align="absmiddle" alt="ฟาสท์ฮีล"> ฟาสท์ฮีล | 5 | ⚔️ Attack |  |
| 32009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/66:0:0" width="20" height="20" align="absmiddle" alt="ดีไวน์จัดจ์เมนท์"> ดีไวน์จัดจ์เมนท์ | 5 | 💀 Debuff |  |
| 32004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/51:0:0" width="20" height="20" align="absmiddle" alt="ฮีล"> ฮีล | 10 | ⚔️ Attack |  |
| 33005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/63:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ MP"> เอนฮานซ์ MP | 3 | 🟢 Passive |  |
| 35002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/56:0:0" width="20" height="20" align="absmiddle" alt="วิสดอม"> วิสดอม | 1 | ✨ Buff |  |
| 35003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/57:0:0" width="20" height="20" align="absmiddle" alt="เบลสฮาร์ท"> เบลสฮาร์ท | 3 | ✨ Buff |  |
| 35027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/122:0:0" width="20" height="20" align="absmiddle" alt="มานาออร่า"> มานาออร่า | 1 | 🔄 Toggle |  |
| 32006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/53:0:0" width="20" height="20" align="absmiddle" alt="เคียวร์พ้อยซั่น"> เคียวร์พ้อยซั่น | 1 | ⚔️ Attack |  |
| 35031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/441:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สวิสดอม"> รีอินฟอร์สวิสดอม | 4 | 💥 AoE |  |
| 35032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/442:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งเมจิก"> เบลสซิ่งเมจิก | 4 | 🔄 Toggle |  |

---

#### 3122 วิซาร์ด (C2)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 32001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/48:0:0" width="20" height="20" align="absmiddle" alt="วินด์สไตรค์"> วินด์สไตรค์ | 10 | 🔒 CC |  |
| 32003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/50:0:0" width="20" height="20" align="absmiddle" alt="ไฟร์บอล"> ไฟร์บอล | 10 | ⚔️ Attack |  |
| 32011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/70:0:0" width="20" height="20" align="absmiddle" alt="เบิร์นนิ่งไฟร์"> เบิร์นนิ่งไฟร์ | 5 | 💀 Debuff |  |
| 32012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/71:0:0" width="20" height="20" align="absmiddle" alt="ชิลบรีซ"> ชิลบรีซ | 5 | 🔒 CC |  |
| 32013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/72:0:0" width="20" height="20" align="absmiddle" alt="ไอซ์แอโรว์"> ไอซ์แอโรว์ | 10 | 💀 Debuff |  |
| 32015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/74:0:0" width="20" height="20" align="absmiddle" alt="อีเวนนอม"> อีเวนนอม | 5 | 💀 Debuff |  |
| 32016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/75:0:0" width="20" height="20" align="absmiddle" alt="บลัดสตีม"> บลัดสตีม | 1 | ⚔️ Attack |  |
| 32018 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/88:0:0" width="20" height="20" align="absmiddle" alt="วินด์สไปค์"> วินด์สไปค์ | 5 | 💥 AoE |  |
| 35001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/55:0:0" width="20" height="20" align="absmiddle" alt="อินเทลิเจนท์"> อินเทลิเจนท์ | 1 | ✨ Buff |  |
| 35027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/122:0:0" width="20" height="20" align="absmiddle" alt="มานาออร่า"> มานาออร่า | 1 | 🔄 Toggle |  |
| 35031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/441:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สวิสดอม"> รีอินฟอร์สวิสดอม | 4 | 💥 AoE |  |
| 35032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/442:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งเมจิก"> เบลสซิ่งเมจิก | 4 | 🔄 Toggle |  |

---

#### 3131 พรีสต์ (C3)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 32007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/54:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่สไตรค์"> โฮลี่สไตรค์ | 10 | ⚔️ Attack |  |
| 32008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/64:0:0" width="20" height="20" align="absmiddle" alt="ฟาสท์ฮีล"> ฟาสท์ฮีล | 10 | ⚔️ Attack |  |
| 32009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/66:0:0" width="20" height="20" align="absmiddle" alt="ดีไวน์จัดจ์เมนท์"> ดีไวน์จัดจ์เมนท์ | 10 | 💀 Debuff |  |
| 32019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/87:0:0" width="20" height="20" align="absmiddle" alt="รีเวิร์ส"> รีเวิร์ส | 1 | ⚔️ Attack |  |
| 32020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/118:0:0" width="20" height="20" align="absmiddle" alt="กรุ๊ปฮีล"> กรุ๊ปฮีล | 5 | 💥 AoE |  |
| 32004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/51:0:0" width="20" height="20" align="absmiddle" alt="ฮีล"> ฮีล | 15 | ⚔️ Attack |  |
| 33005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/63:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ MP"> เอนฮานซ์ MP | 5 | 🟢 Passive |  |
| 35002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/56:0:0" width="20" height="20" align="absmiddle" alt="วิสดอม"> วิสดอม | 3 | ✨ Buff |  |
| 35003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/57:0:0" width="20" height="20" align="absmiddle" alt="เบลสฮาร์ท"> เบลสฮาร์ท | 5 | ✨ Buff |  |
| 35006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/68:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่แบริเออร์"> โฮลี่แบริเออร์ | 1 | utility |  |
| 35007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/76:0:0" width="20" height="20" align="absmiddle" alt="วิสาร์ดลี่"> วิสาร์ดลี่ | 1 | ✨ Buff |  |
| 35010 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/121:0:0" width="20" height="20" align="absmiddle" alt="ไมท์"> ไมท์ | 1 | ✨ Buff |  |
| 35011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/122:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์"> ชิลด์ | 1 | ✨ Buff |  |
| 35013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/25:0:0" width="20" height="20" align="absmiddle" alt="บีโฮลเดอร์"> บีโฮลเดอร์ | 2 | 💥 AoE |  |
| 35014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/205:0:0" width="20" height="20" align="absmiddle" alt="ชรูดสเพ็ล"> ชรูดสเพ็ล | 1 | ✨ Buff |  |
| 35027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/122:0:0" width="20" height="20" align="absmiddle" alt="มานาออร่า"> มานาออร่า | 3 | 🔄 Toggle |  |
| 32006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/53:0:0" width="20" height="20" align="absmiddle" alt="เคียวร์พ้อยซั่น"> เคียวร์พ้อยซั่น | 3 | ⚔️ Attack |  |
| 35031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/441:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สวิสดอม"> รีอินฟอร์สวิสดอม | 6 | 💥 AoE |  |
| 35032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/442:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งเมจิก"> เบลสซิ่งเมจิก | 6 | 🔄 Toggle |  |
| 32032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/193:0:0" width="20" height="20" align="absmiddle" alt="เทิร์นอันเด๊ด"> เทิร์นอันเด๊ด | 5 | 💥 AoE |  |

---

#### 3132 ซอร์เซอเรอร์ (C3)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 32001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/48:0:0" width="20" height="20" align="absmiddle" alt="วินด์สไตรค์"> วินด์สไตรค์ | 20 | 🔒 CC |  |
| 32003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/50:0:0" width="20" height="20" align="absmiddle" alt="ไฟร์บอล"> ไฟร์บอล | 20 | ⚔️ Attack |  |
| 32011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/70:0:0" width="20" height="20" align="absmiddle" alt="เบิร์นนิ่งไฟร์"> เบิร์นนิ่งไฟร์ | 10 | 💀 Debuff |  |
| 32012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/71:0:0" width="20" height="20" align="absmiddle" alt="ชิลบรีซ"> ชิลบรีซ | 10 | 🔒 CC |  |
| 32013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/72:0:0" width="20" height="20" align="absmiddle" alt="ไอซ์แอโรว์"> ไอซ์แอโรว์ | 20 | 💀 Debuff |  |
| 32015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/74:0:0" width="20" height="20" align="absmiddle" alt="อีเวนนอม"> อีเวนนอม | 10 | 💀 Debuff |  |
| 32016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/75:0:0" width="20" height="20" align="absmiddle" alt="บลัดสตีม"> บลัดสตีม | 3 | ⚔️ Attack |  |
| 32018 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/88:0:0" width="20" height="20" align="absmiddle" alt="วินด์สไปค์"> วินด์สไปค์ | 10 | 💥 AoE |  |
| 32022 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/103:0:0" width="20" height="20" align="absmiddle" alt="ไฟเออร์บลาสท์"> ไฟเออร์บลาสท์ | 5 | 💥 AoE |  |
| 32023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/123:0:0" width="20" height="20" align="absmiddle" alt="บลิสซาร์ด"> บลิสซาร์ด | 5 | 💥🔒 AoE+CC |  |
| 32024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/107:0:0" width="20" height="20" align="absmiddle" alt="ไลท์นิ่งสโตน"> ไลท์นิ่งสโตน | 5 | 🔒 CC |  |
| 35001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/55:0:0" width="20" height="20" align="absmiddle" alt="อินเทลิเจนท์"> อินเทลิเจนท์ | 3 | ✨ Buff |  |
| 35027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/122:0:0" width="20" height="20" align="absmiddle" alt="มานาออร่า"> มานาออร่า | 2 | 🔄 Toggle |  |
| 35031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/441:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สวิสดอม"> รีอินฟอร์สวิสดอม | 6 | 💥 AoE |  |
| 35032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/442:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งเมจิก"> เบลสซิ่งเมจิก | 6 | 🔄 Toggle |  |

---

#### 3133 ม็องค์ (C3)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 32027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/128:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่สวิง"> โฮลี่สวิง | 5 | 🔒 CC |  |
| 32028 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/129:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่สไปค์"> โฮลี่สไปค์ | 5 | 🩹 Heal |  |
| 32029 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/130:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่อัพเปอร์"> โฮลี่อัพเปอร์ | 5 | 🔒 CC |  |
| 32040 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/201:0:0" width="20" height="20" align="absmiddle" alt="คริปเปิ้ล"> คริปเปิ้ล | 2 | 💥🔒 AoE+CC |  |
| 33002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/60:0:0" width="20" height="20" align="absmiddle" alt="โร๊บเอ็กซเพอร์ไทซ์"> โร๊บเอ็กซเพอร์ไทซ์ | 5 | 🟢 Passive |  |
| 35001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/55:0:0" width="20" height="20" align="absmiddle" alt="อินเทลิเจนท์"> อินเทลิเจนท์ | 2 | ✨ Buff |  |
| 35002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/56:0:0" width="20" height="20" align="absmiddle" alt="วิสดอม"> วิสดอม | 2 | ✨ Buff |  |
| 35008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/133:0:0" width="20" height="20" align="absmiddle" alt="เบลสเฟทอล"> เบลสเฟทอล | 2 | 🩹 Heal |  |
| 35023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/234:0:0" width="20" height="20" align="absmiddle" alt="ทวิงเกิ้ลเมจิก"> ทวิงเกิ้ลเมจิก | 2 | ✨ Buff |  |
| 32006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/53:0:0" width="20" height="20" align="absmiddle" alt="เคียวร์พ้อยซั่น"> เคียวร์พ้อยซั่น | 2 | ⚔️ Attack |  |
| 35031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/441:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สวิสดอม"> รีอินฟอร์สวิสดอม | 6 | 💥 AoE |  |
| 35032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/442:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งเมจิก"> เบลสซิ่งเมจิก | 6 | 🔄 Toggle |  |

---

#### 3141 บิชอป (C4)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 32007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/54:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่สไตรค์"> โฮลี่สไตรค์ | 20 | ⚔️ Attack |  |
| 32008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/64:0:0" width="20" height="20" align="absmiddle" alt="ฟาสท์ฮีล"> ฟาสท์ฮีล | 15 | ⚔️ Attack |  |
| 32009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/66:0:0" width="20" height="20" align="absmiddle" alt="ดีไวน์จัดจ์เมนท์"> ดีไวน์จัดจ์เมนท์ | 30 | 💀 Debuff |  |
| 32019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/87:0:0" width="20" height="20" align="absmiddle" alt="รีเวิร์ส"> รีเวิร์ส | 2 | ⚔️ Attack |  |
| 32020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/118:0:0" width="20" height="20" align="absmiddle" alt="กรุ๊ปฮีล"> กรุ๊ปฮีล | 15 | 💥 AoE |  |
| 32004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/51:0:0" width="20" height="20" align="absmiddle" alt="ฮีล"> ฮีล | 20 | ⚔️ Attack |  |
| 32033 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/194:0:0" width="20" height="20" align="absmiddle" alt="แซคริไฟซ์"> แซคริไฟซ์ | 1 | 💥 AoE |  |
| 32044 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/234:0:0" width="20" height="20" align="absmiddle" alt="ทรานสเฟอร์มานา"> ทรานสเฟอร์มานา | 5 | ⚔️ Attack |  |
| 33005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/63:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ MP"> เอนฮานซ์ MP | 7 | 🟢 Passive |  |
| 35002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/56:0:0" width="20" height="20" align="absmiddle" alt="วิสดอม"> วิสดอม | 5 | ✨ Buff |  |
| 35003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/57:0:0" width="20" height="20" align="absmiddle" alt="เบลสฮาร์ท"> เบลสฮาร์ท | 7 | ✨ Buff |  |
| 35006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/68:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่แบริเออร์"> โฮลี่แบริเออร์ | 3 | utility |  |
| 35007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/76:0:0" width="20" height="20" align="absmiddle" alt="วิสาร์ดลี่"> วิสาร์ดลี่ | 3 | ✨ Buff |  |
| 35010 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/121:0:0" width="20" height="20" align="absmiddle" alt="ไมท์"> ไมท์ | 3 | ✨ Buff |  |
| 35011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/122:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์"> ชิลด์ | 3 | ✨ Buff |  |
| 35013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/25:0:0" width="20" height="20" align="absmiddle" alt="บีโฮลเดอร์"> บีโฮลเดอร์ | 4 | 💥 AoE |  |
| 35014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/205:0:0" width="20" height="20" align="absmiddle" alt="ชรูดสเพ็ล"> ชรูดสเพ็ล | 3 | ✨ Buff |  |
| 35027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/122:0:0" width="20" height="20" align="absmiddle" alt="มานาออร่า"> มานาออร่า | 5 | 🔄 Toggle |  |
| 32006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/53:0:0" width="20" height="20" align="absmiddle" alt="เคียวร์พ้อยซั่น"> เคียวร์พ้อยซั่น | 4 | ⚔️ Attack |  |
| 35031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/441:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สวิสดอม"> รีอินฟอร์สวิสดอม | 8 | 💥 AoE |  |
| 35032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/442:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งเมจิก"> เบลสซิ่งเมจิก | 8 | 🔄 Toggle |  |
| 32032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/193:0:0" width="20" height="20" align="absmiddle" alt="เทิร์นอันเด๊ด"> เทิร์นอันเด๊ด | 10 | 💥 AoE |  |

---

#### 3142 วอร์ล็อค (C4)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 32011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/70:0:0" width="20" height="20" align="absmiddle" alt="เบิร์นนิ่งไฟร์"> เบิร์นนิ่งไฟร์ | 20 | 💀 Debuff |  |
| 32012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/71:0:0" width="20" height="20" align="absmiddle" alt="ชิลบรีซ"> ชิลบรีซ | 20 | 🔒 CC |  |
| 32015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/74:0:0" width="20" height="20" align="absmiddle" alt="อีเวนนอม"> อีเวนนอม | 20 | 💀 Debuff |  |
| 32016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/75:0:0" width="20" height="20" align="absmiddle" alt="บลัดสตีม"> บลัดสตีม | 5 | ⚔️ Attack |  |
| 32018 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/88:0:0" width="20" height="20" align="absmiddle" alt="วินด์สไปค์"> วินด์สไปค์ | 20 | 💥 AoE |  |
| 32022 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/103:0:0" width="20" height="20" align="absmiddle" alt="ไฟเออร์บลาสท์"> ไฟเออร์บลาสท์ | 20 | 💥 AoE |  |
| 32023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/123:0:0" width="20" height="20" align="absmiddle" alt="บลิสซาร์ด"> บลิสซาร์ด | 20 | 💥🔒 AoE+CC |  |
| 32024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/107:0:0" width="20" height="20" align="absmiddle" alt="ไลท์นิ่งสโตน"> ไลท์นิ่งสโตน | 20 | 🔒 CC |  |
| 32034 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/195:0:0" width="20" height="20" align="absmiddle" alt="ไฟเออร์เบิร์สติ้ง"> ไฟเออร์เบิร์สติ้ง | 10 | 🔒 CC |  |
| 32035 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/196:0:0" width="20" height="20" align="absmiddle" alt="มิทิเออร์"> มิทิเออร์ | 10 | 💥 AoE |  |
| 32036 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/197:0:0" width="20" height="20" align="absmiddle" alt="ธันเดอร์เบรค"> ธันเดอร์เบรค | 10 | 💥🔒 AoE+CC |  |
| 32037 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/198:0:0" width="20" height="20" align="absmiddle" alt="วีนอมคลาวด์"> วีนอมคลาวด์ | 20 | 🩹 Heal |  |
| 33006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/77:0:0" width="20" height="20" align="absmiddle" alt="สเพ็ลคราฟท์"> สเพ็ลคราฟท์ | 5 | 🟢 Passive |  |
| 35001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/55:0:0" width="20" height="20" align="absmiddle" alt="อินเทลิเจนท์"> อินเทลิเจนท์ | 5 | ✨ Buff |  |
| 35027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/122:0:0" width="20" height="20" align="absmiddle" alt="มานาออร่า"> มานาออร่า | 3 | 🔄 Toggle |  |
| 35031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/441:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สวิสดอม"> รีอินฟอร์สวิสดอม | 8 | 💥 AoE |  |
| 35032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/442:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งเมจิก"> เบลสซิ่งเมจิก | 8 | 🔄 Toggle |  |
| 32036 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/197:0:0" width="20" height="20" align="absmiddle" alt="ธันเดอร์เบรค"> ธันเดอร์เบรค | 20 | 💥🔒 AoE+CC |  |
| 32034 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/195:0:0" width="20" height="20" align="absmiddle" alt="ไฟเออร์เบิร์สติ้ง"> ไฟเออร์เบิร์สติ้ง | 20 | 🔒 CC |  |
| 32017 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/86:0:0" width="20" height="20" align="absmiddle" alt="ดีไวน์โฮลด์"> ดีไวน์โฮลด์ | 15 | 💥🔒 AoE+CC |  |

---

#### 3143 อินไควเรอร์ (C4)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 32027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/128:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่สวิง"> โฮลี่สวิง | 10 | 🔒 CC |  |
| 32028 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/129:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่สไปค์"> โฮลี่สไปค์ | 10 | 🩹 Heal |  |
| 32029 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/130:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่อัพเปอร์"> โฮลี่อัพเปอร์ | 10 | 🔒 CC |  |
| 32038 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/199:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่จัสติส"> โฮลี่จัสติส | 10 | 💥 AoE |  |
| 32039 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/200:0:0" width="20" height="20" align="absmiddle" alt="ทรานควิลลิตี้"> ทรานควิลลิตี้ | 2 | 💥🔒 AoE+CC |  |
| 32040 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/201:0:0" width="20" height="20" align="absmiddle" alt="คริปเปิ้ล"> คริปเปิ้ล | 4 | 💥🔒 AoE+CC |  |
| 33002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/60:0:0" width="20" height="20" align="absmiddle" alt="โร๊บเอ็กซเพอร์ไทซ์"> โร๊บเอ็กซเพอร์ไทซ์ | 10 | 🟢 Passive |  |
| 35001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/55:0:0" width="20" height="20" align="absmiddle" alt="อินเทลิเจนท์"> อินเทลิเจนท์ | 3 | ✨ Buff |  |
| 35002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/56:0:0" width="20" height="20" align="absmiddle" alt="วิสดอม"> วิสดอม | 3 | ✨ Buff |  |
| 35008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/133:0:0" width="20" height="20" align="absmiddle" alt="เบลสเฟทอล"> เบลสเฟทอล | 4 | 🩹 Heal |  |
| 35016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/207:0:0" width="20" height="20" align="absmiddle" alt="คอนเซ็นเทรชั่น"> คอนเซ็นเทรชั่น | 2 | ✨ Buff |  |
| 35023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/234:0:0" width="20" height="20" align="absmiddle" alt="ทวิงเกิ้ลเมจิก"> ทวิงเกิ้ลเมจิก | 5 | ✨ Buff |  |
| 32006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/53:0:0" width="20" height="20" align="absmiddle" alt="เคียวร์พ้อยซั่น"> เคียวร์พ้อยซั่น | 3 | ⚔️ Attack |  |
| 35031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/441:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สวิสดอม"> รีอินฟอร์สวิสดอม | 8 | 💥 AoE |  |
| 35032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/442:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งเมจิก"> เบลสซิ่งเมจิก | 8 | 🔄 Toggle |  |
| 35017 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/208:0:0" width="20" height="20" align="absmiddle" alt="ฟอร์จูนเนทเมจิค"> ฟอร์จูนเนทเมจิค | 5 | ✨ Buff |  |
| 13005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/12:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ HP"> เอนฮานซ์ HP | 10 | 🟢 Passive |  |
| 13012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/15:0:0" width="20" height="20" align="absmiddle" alt="เมซเทรนนิ่ง"> เมซเทรนนิ่ง | 10 | 🟢 Passive |  |
| 13018 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/225:0:0" width="20" height="20" align="absmiddle" alt="เมสโพรเทคชั่น"> เมสโพรเทคชั่น | 10 | 🟢 Passive |  |

---

#### 3144 เอเลเมนทัลมาสเตอร์ (C4)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 32007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/54:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่สไตรค์"> โฮลี่สไตรค์ | 20 | ⚔️ Attack |  |
| 32009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/66:0:0" width="20" height="20" align="absmiddle" alt="ดีไวน์จัดจ์เมนท์"> ดีไวน์จัดจ์เมนท์ | 30 | 💀 Debuff |  |
| 32019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/87:0:0" width="20" height="20" align="absmiddle" alt="รีเวิร์ส"> รีเวิร์ส | 1 | ⚔️ Attack |  |
| 32020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/118:0:0" width="20" height="20" align="absmiddle" alt="กรุ๊ปฮีล"> กรุ๊ปฮีล | 10 | 💥 AoE |  |
| 33005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/63:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ MP"> เอนฮานซ์ MP | 10 | 🟢 Passive |  |
| 35002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/56:0:0" width="20" height="20" align="absmiddle" alt="วิสดอม"> วิสดอม | 3 | ✨ Buff |  |
| 35003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/57:0:0" width="20" height="20" align="absmiddle" alt="เบลสฮาร์ท"> เบลสฮาร์ท | 5 | ✨ Buff |  |
| 35010 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/121:0:0" width="20" height="20" align="absmiddle" alt="ไมท์"> ไมท์ | 5 | ✨ Buff |  |
| 35011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/122:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์"> ชิลด์ | 5 | ✨ Buff |  |
| 35019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/210:0:0" width="20" height="20" align="absmiddle" alt="พินพอยท์"> พินพอยท์ | 3 | 💥 AoE |  |
| 35020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/211:0:0" width="20" height="20" align="absmiddle" alt="คิสออฟเดธ"> คิสออฟเดธ | 3 | 💥 AoE |  |
| 35021 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/212:0:0" width="20" height="20" align="absmiddle" alt="เคล้าท์"> เคล้าท์ | 3 | 💥 AoE |  |
| 35027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/122:0:0" width="20" height="20" align="absmiddle" alt="มานาออร่า"> มานาออร่า | 4 | 🔄 Toggle |  |
| 32006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/53:0:0" width="20" height="20" align="absmiddle" alt="เคียวร์พ้อยซั่น"> เคียวร์พ้อยซั่น | 3 | ⚔️ Attack |  |
| 35031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/441:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สวิสดอม"> รีอินฟอร์สวิสดอม | 8 | 💥 AoE |  |
| 35032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/442:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งเมจิก"> เบลสซิ่งเมจิก | 8 | 🔄 Toggle |  |
| 32032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/193:0:0" width="20" height="20" align="absmiddle" alt="เทิร์นอันเด๊ด"> เทิร์นอันเด๊ด | 10 | 💥 AoE |  |
| 33002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/60:0:0" width="20" height="20" align="absmiddle" alt="โร๊บเอ็กซเพอร์ไทซ์"> โร๊บเอ็กซเพอร์ไทซ์ | 10 | 🟢 Passive |  |
| 32014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/73:0:0" width="20" height="20" align="absmiddle" alt="เคิร์ซวีคเนส"> เคิร์ซวีคเนส | 10 | 💀 Debuff |  |
| 32025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/126:0:0" width="20" height="20" align="absmiddle" alt="สลีปปิ้งสโตน"> สลีปปิ้งสโตน | 20 | 🔒 CC |  |
| 32026 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/127:0:0" width="20" height="20" align="absmiddle" alt="ไบน์ดิ้งโซล"> ไบน์ดิ้งโซล | 20 | 🔒 CC |  |
| 35006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/68:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่แบริเออร์"> โฮลี่แบริเออร์ | 4 | utility |  |

---

#### 3151 คาร์ดินัล (C5)

> 🟡 **Overall: 83.0**/100 · DMG `100` · AoE `100` · CC `86` · Util `75` · Surv `52`

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 32008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/64:0:0" width="20" height="20" align="absmiddle" alt="ฟาสท์ฮีล"> ฟาสท์ฮีล | 20 | ⚔️ Attack |  |
| 32019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/87:0:0" width="20" height="20" align="absmiddle" alt="รีเวิร์ส"> รีเวิร์ส | 3 | ⚔️ Attack | ⚠️ DPS ต่ำ (1) / 💧 Mana สิ้นเปลือง |
| 32020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/118:0:0" width="20" height="20" align="absmiddle" alt="กรุ๊ปฮีล"> กรุ๊ปฮีล | 20 | 💥 AoE | ⚠️ DPS ต่ำ (25) |
| 32004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/51:0:0" width="20" height="20" align="absmiddle" alt="ฮีล"> ฮีล | 20 | ⚔️ Attack |  |
| 32033 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/194:0:0" width="20" height="20" align="absmiddle" alt="แซคริไฟซ์"> แซคริไฟซ์ | 3 | 💥 AoE | ⚠️ DPS ต่ำ (9) |
| 32044 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/234:0:0" width="20" height="20" align="absmiddle" alt="ทรานสเฟอร์มานา"> ทรานสเฟอร์มานา | 10 | ⚔️ Attack | ⚠️ DPS ต่ำ (25) / 💧 Mana สิ้นเปลือง |
| 32046 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/22:0:0" width="20" height="20" align="absmiddle" alt="เดมอนสไปค์"> เดมอนสไปค์ | 10 | 💥🔒 AoE+CC |  |
| 32047 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/206:0:0" width="20" height="20" align="absmiddle" alt="อันเดดเทคเกอร์"> อันเดดเทคเกอร์ | 10 | 💥 AoE |  |
| 33005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/63:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ MP"> เอนฮานซ์ MP | 20 | 🟢 Passive |  |
| 35002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/56:0:0" width="20" height="20" align="absmiddle" alt="วิสดอม"> วิสดอม | 7 | ✨ Buff |  |
| 35003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/57:0:0" width="20" height="20" align="absmiddle" alt="เบลสฮาร์ท"> เบลสฮาร์ท | 9 | ✨ Buff |  |
| 35006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/68:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่แบริเออร์"> โฮลี่แบริเออร์ | 5 | utility |  |
| 35007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/76:0:0" width="20" height="20" align="absmiddle" alt="วิสาร์ดลี่"> วิสาร์ดลี่ | 5 | ✨ Buff |  |
| 35013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/25:0:0" width="20" height="20" align="absmiddle" alt="บีโฮลเดอร์"> บีโฮลเดอร์ | 6 | 💥 AoE |  |
| 35014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/205:0:0" width="20" height="20" align="absmiddle" alt="ชรูดสเพ็ล"> ชรูดสเพ็ล | 5 | ✨ Buff |  |
| 35022 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/230:0:0" width="20" height="20" align="absmiddle" alt="อินเทนสิฝมานา"> อินเทนสิฝมานา | 3 | 💥 AoE |  |
| 35026 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/55:0:0" width="20" height="20" align="absmiddle" alt="จุดเยือกแข็งแห่งโอลฟีอุส"> จุดเยือกแข็งแห่งโอลฟีอุส | 6 | 💥 AoE |  |
| 35027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/122:0:0" width="20" height="20" align="absmiddle" alt="มานาออร่า"> มานาออร่า | 9 | 🔄 Toggle |  |
| 32006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/53:0:0" width="20" height="20" align="absmiddle" alt="เคียวร์พ้อยซั่น"> เคียวร์พ้อยซั่น | 5 | ⚔️ Attack | ⚠️ DPS ต่ำ (13) / 💧 Mana สิ้นเปลือง |
| 35031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/441:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สวิสดอม"> รีอินฟอร์สวิสดอม | 10 | 💥 AoE |  |
| 35032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/442:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งเมจิก"> เบลสซิ่งเมจิก | 10 | 🔄 Toggle |  |
| 32032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/193:0:0" width="20" height="20" align="absmiddle" alt="เทิร์นอันเด๊ด"> เทิร์นอันเด๊ด | 15 | 💥 AoE |  |
| 33007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/78:0:0" width="20" height="20" align="absmiddle" alt="เมจิคแบริเออร์"> เมจิคแบริเออร์ | 20 | 🟢 Passive |  |
| 32007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/54:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่สไตรค์"> โฮลี่สไตรค์ | 30 | ⚔️ Attack |  |
| 13005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/12:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ HP"> เอนฮานซ์ HP | 20 | 🟢 Passive |  |
| 33002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/60:0:0" width="20" height="20" align="absmiddle" alt="โร๊บเอ็กซเพอร์ไทซ์"> โร๊บเอ็กซเพอร์ไทซ์ | 20 | 🟢 Passive |  |
| 35004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/58:0:0" width="20" height="20" align="absmiddle" alt="มายนด์แบริเออร์"> มายนด์แบริเออร์ | 8 | ✨ Buff |  |
| 35009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/120:0:0" width="20" height="20" align="absmiddle" alt="เบลสวินด์"> เบลสวินด์ | 7 | ✨ Buff |  |
| 35005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/67:0:0" width="20" height="20" align="absmiddle" alt="เบลสมายนด์"> เบลสมายนด์ | 7 | ✨ Buff |  |
| 33010 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/70085:0:0" width="20" height="20" align="absmiddle" alt="เคียวร์เบลสเพอร์เฟคชั่น"> เคียวร์เบลสเพอร์เฟคชั่น | 10 | ⚔️ Attack | ⚠️ DPS ต่ำ (12) / 💧 Mana สิ้นเปลือง |
| 33011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/70086:0:0" width="20" height="20" align="absmiddle" alt="เคียวร์เคิร์ซเอ็กซ์เครชั่น"> เคียวร์เคิร์ซเอ็กซ์เครชั่น | 10 | ⚔️ Attack | ⚠️ DPS ต่ำ (12) / 💧 Mana สิ้นเปลือง |
| 32024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/107:0:0" width="20" height="20" align="absmiddle" alt="ไลท์นิ่งสโตน"> ไลท์นิ่งสโตน | 30 | 🔒 CC |  |
| 32036 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/197:0:0" width="20" height="20" align="absmiddle" alt="ธันเดอร์เบรค"> ธันเดอร์เบรค | 30 | 💥🔒 AoE+CC |  |

<details><summary>⚠️ <strong>คำแนะนำการปรับสมดุล (1 รายการ)</strong></summary>

| # | ประเภท | มิติ | รายละเอียด | ไฟล์ที่แก้ | Gap |
|---|--------|------|----------|------------|-----|
| 1 | 🔧 ปรับ | Survivability | 🛡️ ปรับค่า fStatusDataMul สกิลบัฟ/ฮีล (×1.3-1.5) | `Skill_Buff_List.bin.txt` | 13.0 |

</details>

---

#### 3152 โซลอาร์บิเตอร์ (C5)

> 🟢 **Overall: 91.2**/100 · DMG `100` · AoE `80` · CC `100` · Util `87` · Surv `85`

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 32027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/128:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่สวิง"> โฮลี่สวิง | 20 | 🔒 CC |  |
| 32028 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/129:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่สไปค์"> โฮลี่สไปค์ | 20 | 🩹 Heal |  |
| 32029 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/130:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่อัพเปอร์"> โฮลี่อัพเปอร์ | 20 | 🔒 CC |  |
| 32038 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/199:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่จัสติส"> โฮลี่จัสติส | 20 | 💥 AoE |  |
| 32039 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/200:0:0" width="20" height="20" align="absmiddle" alt="ทรานควิลลิตี้"> ทรานควิลลิตี้ | 4 | 💥🔒 AoE+CC |  |
| 32040 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/201:0:0" width="20" height="20" align="absmiddle" alt="คริปเปิ้ล"> คริปเปิ้ล | 6 | 💥🔒 AoE+CC |  |
| 32049 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/101:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่เอิร์ธเควค"> โฮลี่เอิร์ธเควค | 10 | 💥🔒 AoE+CC |  |
| 32050 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/195:0:0" width="20" height="20" align="absmiddle" alt="มานาเบิร์น"> มานาเบิร์น | 5 | 💀 Debuff |  |
| 33002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/60:0:0" width="20" height="20" align="absmiddle" alt="โร๊บเอ็กซเพอร์ไทซ์"> โร๊บเอ็กซเพอร์ไทซ์ | 20 | 🟢 Passive |  |
| 35001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/55:0:0" width="20" height="20" align="absmiddle" alt="อินเทลิเจนท์"> อินเทลิเจนท์ | 4 | ✨ Buff |  |
| 35002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/56:0:0" width="20" height="20" align="absmiddle" alt="วิสดอม"> วิสดอม | 4 | ✨ Buff |  |
| 35004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/58:0:0" width="20" height="20" align="absmiddle" alt="มายนด์แบริเออร์"> มายนด์แบริเออร์ | 5 | ✨ Buff |  |
| 35008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/133:0:0" width="20" height="20" align="absmiddle" alt="เบลสเฟทอล"> เบลสเฟทอล | 6 | 🩹 Heal |  |
| 35016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/207:0:0" width="20" height="20" align="absmiddle" alt="คอนเซ็นเทรชั่น"> คอนเซ็นเทรชั่น | 4 | ✨ Buff |  |
| 35023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/234:0:0" width="20" height="20" align="absmiddle" alt="ทวิงเกิ้ลเมจิก"> ทวิงเกิ้ลเมจิก | 8 | ✨ Buff |  |
| 35031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/441:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สวิสดอม"> รีอินฟอร์สวิสดอม | 10 | 💥 AoE |  |
| 35032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/442:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งเมจิก"> เบลสซิ่งเมจิก | 10 | 🔄 Toggle |  |
| 35017 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/208:0:0" width="20" height="20" align="absmiddle" alt="ฟอร์จูนเนทเมจิค"> ฟอร์จูนเนทเมจิค | 5 | ✨ Buff |  |
| 33007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/78:0:0" width="20" height="20" align="absmiddle" alt="เมจิคแบริเออร์"> เมจิคแบริเออร์ | 20 | 🟢 Passive |  |
| 13005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/12:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ HP"> เอนฮานซ์ HP | 20 | 🟢 Passive |  |
| 33005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/63:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ MP"> เอนฮานซ์ MP | 20 | 🟢 Passive |  |
| 33006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/77:0:0" width="20" height="20" align="absmiddle" alt="สเพ็ลคราฟท์"> สเพ็ลคราฟท์ | 20 | 🟢 Passive |  |
| 13012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/15:0:0" width="20" height="20" align="absmiddle" alt="เมซเทรนนิ่ง"> เมซเทรนนิ่ง | 20 | 🟢 Passive |  |
| 13018 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/225:0:0" width="20" height="20" align="absmiddle" alt="เมสโพรเทคชั่น"> เมสโพรเทคชั่น | 20 | 🟢 Passive |  |
| 13004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/20:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์เทรนนิ่ง"> ชิลด์เทรนนิ่ง | 20 | 🟢 Passive |  |
| 32051 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/129:0:0" width="20" height="20" align="absmiddle" alt="โซลสเปียร์"> โซลสเปียร์ | 10 | 💀 Debuff |  |
| 35012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/132:0:0" width="20" height="20" align="absmiddle" alt="อาร์เมอร์ลิงค์"> อาร์เมอร์ลิงค์ | 8 | ✨ Buff |  |

> ✅ **สมดุลดี** — ไม่มีข้อแนะนำเพิ่มเติม

---

#### 3153 แกรนด์มาสเตอร์ (C5)

> 🔴 **Overall: 79.8**/100 · DMG `95` · AoE `100` · CC `96` · Util `66` · Surv `42`

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 32016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/75:0:0" width="20" height="20" align="absmiddle" alt="บลัดสตีม"> บลัดสตีม | 7 | ⚔️ Attack | ⚠️ DPS ต่ำ (18) |
| 32030 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/59:0:0" width="20" height="20" align="absmiddle" alt="บูสท์สเพ็ล"> บูสท์สเพ็ล | 3 | ✨ Buff |  |
| 32035 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/196:0:0" width="20" height="20" align="absmiddle" alt="มิทิเออร์"> มิทิเออร์ | 20 | 💥 AoE |  |
| 32052 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/100:0:0" width="20" height="20" align="absmiddle" alt="ทอร์นาโดอัปเปอร์"> ทอร์นาโดอัปเปอร์ | 10 | 💥🔒 AoE+CC |  |
| 32054 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/71:0:0" width="20" height="20" align="absmiddle" alt="เดธชิลลี่เนส"> เดธชิลลี่เนส | 20 | 💥🔒 AoE+CC |  |
| 32055 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/197:0:0" width="20" height="20" align="absmiddle" alt="เกรทธันเดอร์"> เกรทธันเดอร์ | 10 | 💥🔒 AoE+CC |  |
| 33006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/77:0:0" width="20" height="20" align="absmiddle" alt="สเพ็ลคราฟท์"> สเพ็ลคราฟท์ | 20 | 🟢 Passive |  |
| 35001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/55:0:0" width="20" height="20" align="absmiddle" alt="อินเทลิเจนท์"> อินเทลิเจนท์ | 7 | ✨ Buff |  |
| 35027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/122:0:0" width="20" height="20" align="absmiddle" alt="มานาออร่า"> มานาออร่า | 5 | 🔄 Toggle |  |
| 35031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/441:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สวิสดอม"> รีอินฟอร์สวิสดอม | 10 | 💥 AoE |  |
| 35032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/442:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งเมจิก"> เบลสซิ่งเมจิก | 10 | 🔄 Toggle |  |
| 33009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/213:0:0" width="20" height="20" align="absmiddle" alt="วิทช์คราฟท์"> วิทช์คราฟท์ | 6 | 🟢 Passive |  |
| 33005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/63:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ MP"> เอนฮานซ์ MP | 20 | 🟢 Passive |  |
| 35005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/67:0:0" width="20" height="20" align="absmiddle" alt="เบลสมายนด์"> เบลสมายนด์ | 3 | ✨ Buff |  |

<details><summary>⚠️ <strong>คำแนะนำการปรับสมดุล (2 รายการ)</strong></summary>

| # | ประเภท | มิติ | รายละเอียด | ไฟล์ที่แก้ | Gap |
|---|--------|------|----------|------------|-----|
| 1 | 🔧 ปรับ | Survivability | 🛡️ ปรับค่า fStatusDataMul สกิลบัฟ/ฮีล (×1.3-1.5) | `Skill_Buff_List.bin.txt` | 23.0 |
| 2 | 🔧 ปรับ | Utility | ✨ ปรับค่า fStatusDataMul สกิลบัฟ (×1.3-1.5) | `Skill_Buff_List.bin.txt` | 9.0 |

</details>

---

#### 3154 เนโครแมนเซอร์ (C5)

> 🔴 **Overall: 57.6**/100 · DMG `100` · AoE `95` · CC `0` · Util `72` · Surv `12`

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 32010 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/65:0:0" width="20" height="20" align="absmiddle" alt="แองเจลิคทัช"> แองเจลิคทัช | 30 | 💀 Debuff |  |
| 32014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/73:0:0" width="20" height="20" align="absmiddle" alt="เคิร์ซวีคเนส"> เคิร์ซวีคเนส | 20 | 💀 Debuff |  |
| 32015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/74:0:0" width="20" height="20" align="absmiddle" alt="อีเวนนอม"> อีเวนนอม | 20 | 💀 Debuff |  |
| 32016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/75:0:0" width="20" height="20" align="absmiddle" alt="บลัดสตีม"> บลัดสตีม | 6 | ⚔️ Attack | ⚠️ DPS ต่ำ (18) |
| 32022 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/103:0:0" width="20" height="20" align="absmiddle" alt="ไฟเออร์บลาสท์"> ไฟเออร์บลาสท์ | 30 | 💥 AoE |  |
| 32035 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/196:0:0" width="20" height="20" align="absmiddle" alt="มิทิเออร์"> มิทิเออร์ | 20 | 💥 AoE |  |
| 32037 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/198:0:0" width="20" height="20" align="absmiddle" alt="วีนอมคลาวด์"> วีนอมคลาวด์ | 30 | 🩹 Heal |  |
| 32060 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/226:0:0" width="20" height="20" align="absmiddle" alt="ไวทัลเอ็กซ์โพลชั่น"> ไวทัลเอ็กซ์โพลชั่น | 10 | 💥 AoE |  |
| 32063 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/8:0:0" width="20" height="20" align="absmiddle" alt="คอร์ปซ์เทค"> คอร์ปซ์เทค | 5 | 💥 AoE |  |
| 35001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/55:0:0" width="20" height="20" align="absmiddle" alt="อินเทลิเจนท์"> อินเทลิเจนท์ | 6 | ✨ Buff |  |
| 35024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/22:0:0" width="20" height="20" align="absmiddle" alt="เดฟวิลอาร์มเมอร์"> เดฟวิลอาร์มเมอร์ | 10 | ✨ Buff |  |
| 35031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/441:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สวิสดอม"> รีอินฟอร์สวิสดอม | 10 | 💥 AoE |  |
| 35032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/442:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งเมจิก"> เบลสซิ่งเมจิก | 10 | 🔄 Toggle |  |
| 35007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/76:0:0" width="20" height="20" align="absmiddle" alt="วิสาร์ดลี่"> วิสาร์ดลี่ | 5 | ✨ Buff |  |
| 35027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/122:0:0" width="20" height="20" align="absmiddle" alt="มานาออร่า"> มานาออร่า | 9 | 🔄 Toggle |  |
| 32007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/54:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่สไตรค์"> โฮลี่สไตรค์ | 30 | ⚔️ Attack |  |
| 32059 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/113:0:0" width="20" height="20" align="absmiddle" alt="โบนสเปียร์"> โบนสเปียร์ | 10 | 💀 Debuff |  |
| 32058 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/98:0:0" width="20" height="20" align="absmiddle" alt="โซลสควิซ"> โซลสควิซ | 10 | ✨ Buff |  |

<details><summary>⚠️ <strong>คำแนะนำการปรับสมดุล (3 รายการ)</strong></summary>

| # | ประเภท | มิติ | รายละเอียด | ไฟล์ที่แก้ | Gap |
|---|--------|------|----------|------------|-----|
| 1 | ➕ เพิ่ม | CC | 🔒 เพิ่มสกิล CC (Stun/Slow) อย่างน้อย 2-3 ตัว หรือเพิ่ม CC Buff ในสกิลโจมตี | `Skill_Get_List / Skill_Buff_List` | 75.0 |
| 2 | 🔧 ปรับ | Survivability | 🛡️ ปรับค่า fStatusDataMul สกิลบัฟ/ฮีล (×1.3-1.5) | `Skill_Buff_List.bin.txt` | 53.0 |
| 3 | 🔧 ปรับ | Utility | ✨ ปรับค่า fStatusDataMul สกิลบัฟ (×1.3-1.5) | `Skill_Buff_List.bin.txt` | 3.0 |

</details>

---

#### 3155 รูนมาสเตอร์ (C5)

> 🟡 **Overall: 87.2**/100 · DMG `87` · AoE `95` · CC `100` · Util `87` · Surv `71`

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 32019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/87:0:0" width="20" height="20" align="absmiddle" alt="รีเวิร์ส"> รีเวิร์ส | 1 | ⚔️ Attack | ⚠️ DPS ต่ำ (1) / 💧 Mana สิ้นเปลือง |
| 32020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/118:0:0" width="20" height="20" align="absmiddle" alt="กรุ๊ปฮีล"> กรุ๊ปฮีล | 15 | 💥 AoE | ⚠️ DPS ต่ำ (25) |
| 32061 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/98:0:0" width="20" height="20" align="absmiddle" alt="รูนไซเลนซ์"> รูนไซเลนซ์ | 5 | 🔒 CC |  |
| 33005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/63:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ MP"> เอนฮานซ์ MP | 20 | 🟢 Passive |  |
| 35002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/56:0:0" width="20" height="20" align="absmiddle" alt="วิสดอม"> วิสดอม | 6 | ✨ Buff |  |
| 35003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/57:0:0" width="20" height="20" align="absmiddle" alt="เบลสฮาร์ท"> เบลสฮาร์ท | 7 | ✨ Buff |  |
| 35010 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/121:0:0" width="20" height="20" align="absmiddle" alt="ไมท์"> ไมท์ | 7 | ✨ Buff |  |
| 35011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/122:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์"> ชิลด์ | 7 | ✨ Buff |  |
| 35019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/210:0:0" width="20" height="20" align="absmiddle" alt="พินพอยท์"> พินพอยท์ | 5 | 💥 AoE |  |
| 35020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/211:0:0" width="20" height="20" align="absmiddle" alt="คิสออฟเดธ"> คิสออฟเดธ | 5 | 💥 AoE |  |
| 35021 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/212:0:0" width="20" height="20" align="absmiddle" alt="เคล้าท์"> เคล้าท์ | 5 | 💥 AoE |  |
| 35028 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/98:0:0" width="20" height="20" align="absmiddle" alt="ฮาร์ทเบรค"> ฮาร์ทเบรค | 5 | 💥 AoE |  |
| 35027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/122:0:0" width="20" height="20" align="absmiddle" alt="มานาออร่า"> มานาออร่า | 7 | 🔄 Toggle |  |
| 35031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/441:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สวิสดอม"> รีอินฟอร์สวิสดอม | 10 | 💥 AoE |  |
| 35032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/442:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งเมจิก"> เบลสซิ่งเมจิก | 10 | 🔄 Toggle |  |
| 13005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/12:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ HP"> เอนฮานซ์ HP | 20 | 🟢 Passive |  |
| 33007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/78:0:0" width="20" height="20" align="absmiddle" alt="เมจิคแบริเออร์"> เมจิคแบริเออร์ | 20 | 🟢 Passive |  |
| 35018 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/209:0:0" width="20" height="20" align="absmiddle" alt="แอทคิวท์เนส"> แอทคิวท์เนส | 4 | 🩹 Heal |  |
| 33002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/60:0:0" width="20" height="20" align="absmiddle" alt="โร๊บเอ็กซเพอร์ไทซ์"> โร๊บเอ็กซเพอร์ไทซ์ | 20 | 🟢 Passive |  |
| 32017 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/86:0:0" width="20" height="20" align="absmiddle" alt="ดีไวน์โฮลด์"> ดีไวน์โฮลด์ | 20 | 💥🔒 AoE+CC |  |
| 32066 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/70087:0:0" width="20" height="20" align="absmiddle" alt="รูนสโตนเคิร์ส"> รูนสโตนเคิร์ส | 5 | 🔒 CC |  |
| 32067 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/70088:0:0" width="20" height="20" align="absmiddle" alt="รูนไควท์เท็น"> รูนไควท์เท็น | 5 | 🔒 CC |  |
| 32012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/71:0:0" width="20" height="20" align="absmiddle" alt="ชิลบรีซ"> ชิลบรีซ | 30 | 🔒 CC |  |
| 32018 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/88:0:0" width="20" height="20" align="absmiddle" alt="วินด์สไปค์"> วินด์สไปค์ | 30 | 💥 AoE |  |
| 32023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/123:0:0" width="20" height="20" align="absmiddle" alt="บลิสซาร์ด"> บลิสซาร์ด | 30 | 💥🔒 AoE+CC |  |

<details><summary>⚠️ <strong>คำแนะนำการปรับสมดุล (1 รายการ)</strong></summary>

| # | ประเภท | มิติ | รายละเอียด | ไฟล์ที่แก้ | Gap |
|---|--------|------|----------|------------|-----|
| 1 | 🔧 ปรับ | Damage | ⚔️ ปรับค่า fUnitDataValueMul สกิลโจมตี (×1.2-1.5) | `SkillScript.bin.txt` | 7.6 |

</details>

---

### Elf Mage

#### 3211 เมจ (C1)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 32001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/48:0:0" width="20" height="20" align="absmiddle" alt="วินด์สไตรค์"> วินด์สไตรค์ | 5 | 🔒 CC |  |
| 32003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/50:0:0" width="20" height="20" align="absmiddle" alt="ไฟร์บอล"> ไฟร์บอล | 5 | ⚔️ Attack |  |
| 32013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/72:0:0" width="20" height="20" align="absmiddle" alt="ไอซ์แอโรว์"> ไอซ์แอโรว์ | 5 | 💀 Debuff |  |
| 32004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/51:0:0" width="20" height="20" align="absmiddle" alt="ฮีล"> ฮีล | 5 | ⚔️ Attack |  |
| 33005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/63:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ MP"> เอนฮานซ์ MP | 1 | 🟢 Passive |  |
| 35003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/57:0:0" width="20" height="20" align="absmiddle" alt="เบลสฮาร์ท"> เบลสฮาร์ท | 1 | ✨ Buff |  |
| 35029 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/439:0:0" width="20" height="20" align="absmiddle" alt="เบอร์ซิอุส"> เบอร์ซิอุส | 10 | 🔒 CC |  |
| 35030 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/440:0:0" width="20" height="20" align="absmiddle" alt="สคิปริสกี้"> สคิปริสกี้ | 15 | 🔒 CC |  |
| 35031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/441:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สวิสดอม"> รีอินฟอร์สวิสดอม | 2 | 💥 AoE |  |
| 35032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/442:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งเมจิก"> เบลสซิ่งเมจิก | 2 | 🔄 Toggle |  |
| 35033 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/443:0:0" width="20" height="20" align="absmiddle" alt="อินเทลิเจ้นท์โพสิชั่น"> อินเทลิเจ้นท์โพสิชั่น | 15 | 🟢 Passive |  |
| 35034 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/444:0:0" width="20" height="20" align="absmiddle" alt="เมนทัลโพสิชั่น"> เมนทัลโพสิชั่น | 15 | 🟢 Passive |  |
| 14003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/2:0:0" width="20" height="20" align="absmiddle" alt="เนเจอร์ชิลด์"> เนเจอร์ชิลด์ | 2 | 🔄 Toggle |  |
| 14004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/3:0:0" width="20" height="20" align="absmiddle" alt="เนเจอร์มายด์"> เนเจอร์มายด์ | 2 | 🔄 Toggle |  |

---

#### 3221 เคลอริค (C2)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 32007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/54:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่สไตรค์"> โฮลี่สไตรค์ | 5 | ⚔️ Attack |  |
| 32008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/64:0:0" width="20" height="20" align="absmiddle" alt="ฟาสท์ฮีล"> ฟาสท์ฮีล | 5 | ⚔️ Attack |  |
| 32009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/66:0:0" width="20" height="20" align="absmiddle" alt="ดีไวน์จัดจ์เมนท์"> ดีไวน์จัดจ์เมนท์ | 5 | 💀 Debuff |  |
| 32004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/51:0:0" width="20" height="20" align="absmiddle" alt="ฮีล"> ฮีล | 10 | ⚔️ Attack |  |
| 33005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/63:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ MP"> เอนฮานซ์ MP | 3 | 🟢 Passive |  |
| 35002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/56:0:0" width="20" height="20" align="absmiddle" alt="วิสดอม"> วิสดอม | 1 | ✨ Buff |  |
| 35003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/57:0:0" width="20" height="20" align="absmiddle" alt="เบลสฮาร์ท"> เบลสฮาร์ท | 3 | ✨ Buff |  |
| 35027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/122:0:0" width="20" height="20" align="absmiddle" alt="มานาออร่า"> มานาออร่า | 1 | 🔄 Toggle |  |
| 32006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/53:0:0" width="20" height="20" align="absmiddle" alt="เคียวร์พ้อยซั่น"> เคียวร์พ้อยซั่น | 1 | ⚔️ Attack |  |
| 35031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/441:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สวิสดอม"> รีอินฟอร์สวิสดอม | 4 | 💥 AoE |  |
| 35032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/442:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งเมจิก"> เบลสซิ่งเมจิก | 4 | 🔄 Toggle |  |

---

#### 3222 วิซาร์ด (C2)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 32001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/48:0:0" width="20" height="20" align="absmiddle" alt="วินด์สไตรค์"> วินด์สไตรค์ | 10 | 🔒 CC |  |
| 32003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/50:0:0" width="20" height="20" align="absmiddle" alt="ไฟร์บอล"> ไฟร์บอล | 10 | ⚔️ Attack |  |
| 32011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/70:0:0" width="20" height="20" align="absmiddle" alt="เบิร์นนิ่งไฟร์"> เบิร์นนิ่งไฟร์ | 5 | 💀 Debuff |  |
| 32012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/71:0:0" width="20" height="20" align="absmiddle" alt="ชิลบรีซ"> ชิลบรีซ | 5 | 🔒 CC |  |
| 32013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/72:0:0" width="20" height="20" align="absmiddle" alt="ไอซ์แอโรว์"> ไอซ์แอโรว์ | 10 | 💀 Debuff |  |
| 32015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/74:0:0" width="20" height="20" align="absmiddle" alt="อีเวนนอม"> อีเวนนอม | 5 | 💀 Debuff |  |
| 32016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/75:0:0" width="20" height="20" align="absmiddle" alt="บลัดสตีม"> บลัดสตีม | 1 | ⚔️ Attack |  |
| 32018 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/88:0:0" width="20" height="20" align="absmiddle" alt="วินด์สไปค์"> วินด์สไปค์ | 5 | 💥 AoE |  |
| 35001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/55:0:0" width="20" height="20" align="absmiddle" alt="อินเทลิเจนท์"> อินเทลิเจนท์ | 1 | ✨ Buff |  |
| 35027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/122:0:0" width="20" height="20" align="absmiddle" alt="มานาออร่า"> มานาออร่า | 1 | 🔄 Toggle |  |
| 35031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/441:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สวิสดอม"> รีอินฟอร์สวิสดอม | 4 | 💥 AoE |  |
| 35032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/442:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งเมจิก"> เบลสซิ่งเมจิก | 4 | 🔄 Toggle |  |

---

#### 3231 พรีสต์ (C3)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 32007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/54:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่สไตรค์"> โฮลี่สไตรค์ | 10 | ⚔️ Attack |  |
| 32008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/64:0:0" width="20" height="20" align="absmiddle" alt="ฟาสท์ฮีล"> ฟาสท์ฮีล | 10 | ⚔️ Attack |  |
| 32009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/66:0:0" width="20" height="20" align="absmiddle" alt="ดีไวน์จัดจ์เมนท์"> ดีไวน์จัดจ์เมนท์ | 10 | 💀 Debuff |  |
| 32019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/87:0:0" width="20" height="20" align="absmiddle" alt="รีเวิร์ส"> รีเวิร์ส | 1 | ⚔️ Attack |  |
| 32020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/118:0:0" width="20" height="20" align="absmiddle" alt="กรุ๊ปฮีล"> กรุ๊ปฮีล | 5 | 💥 AoE |  |
| 32004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/51:0:0" width="20" height="20" align="absmiddle" alt="ฮีล"> ฮีล | 15 | ⚔️ Attack |  |
| 33005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/63:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ MP"> เอนฮานซ์ MP | 5 | 🟢 Passive |  |
| 35002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/56:0:0" width="20" height="20" align="absmiddle" alt="วิสดอม"> วิสดอม | 3 | ✨ Buff |  |
| 35003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/57:0:0" width="20" height="20" align="absmiddle" alt="เบลสฮาร์ท"> เบลสฮาร์ท | 5 | ✨ Buff |  |
| 35006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/68:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่แบริเออร์"> โฮลี่แบริเออร์ | 1 | utility |  |
| 35007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/76:0:0" width="20" height="20" align="absmiddle" alt="วิสาร์ดลี่"> วิสาร์ดลี่ | 1 | ✨ Buff |  |
| 35010 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/121:0:0" width="20" height="20" align="absmiddle" alt="ไมท์"> ไมท์ | 1 | ✨ Buff |  |
| 35011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/122:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์"> ชิลด์ | 1 | ✨ Buff |  |
| 35013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/25:0:0" width="20" height="20" align="absmiddle" alt="บีโฮลเดอร์"> บีโฮลเดอร์ | 2 | 💥 AoE |  |
| 35014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/205:0:0" width="20" height="20" align="absmiddle" alt="ชรูดสเพ็ล"> ชรูดสเพ็ล | 1 | ✨ Buff |  |
| 35027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/122:0:0" width="20" height="20" align="absmiddle" alt="มานาออร่า"> มานาออร่า | 3 | 🔄 Toggle |  |
| 32006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/53:0:0" width="20" height="20" align="absmiddle" alt="เคียวร์พ้อยซั่น"> เคียวร์พ้อยซั่น | 3 | ⚔️ Attack |  |
| 35031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/441:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สวิสดอม"> รีอินฟอร์สวิสดอม | 6 | 💥 AoE |  |
| 35032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/442:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งเมจิก"> เบลสซิ่งเมจิก | 6 | 🔄 Toggle |  |
| 32032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/193:0:0" width="20" height="20" align="absmiddle" alt="เทิร์นอันเด๊ด"> เทิร์นอันเด๊ด | 5 | 💥 AoE |  |

---

#### 3232 ซอร์เซอเรอร์ (C3)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 32001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/48:0:0" width="20" height="20" align="absmiddle" alt="วินด์สไตรค์"> วินด์สไตรค์ | 20 | 🔒 CC |  |
| 32003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/50:0:0" width="20" height="20" align="absmiddle" alt="ไฟร์บอล"> ไฟร์บอล | 20 | ⚔️ Attack |  |
| 32011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/70:0:0" width="20" height="20" align="absmiddle" alt="เบิร์นนิ่งไฟร์"> เบิร์นนิ่งไฟร์ | 10 | 💀 Debuff |  |
| 32012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/71:0:0" width="20" height="20" align="absmiddle" alt="ชิลบรีซ"> ชิลบรีซ | 10 | 🔒 CC |  |
| 32013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/72:0:0" width="20" height="20" align="absmiddle" alt="ไอซ์แอโรว์"> ไอซ์แอโรว์ | 20 | 💀 Debuff |  |
| 32015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/74:0:0" width="20" height="20" align="absmiddle" alt="อีเวนนอม"> อีเวนนอม | 10 | 💀 Debuff |  |
| 32016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/75:0:0" width="20" height="20" align="absmiddle" alt="บลัดสตีม"> บลัดสตีม | 3 | ⚔️ Attack |  |
| 32018 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/88:0:0" width="20" height="20" align="absmiddle" alt="วินด์สไปค์"> วินด์สไปค์ | 10 | 💥 AoE |  |
| 32022 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/103:0:0" width="20" height="20" align="absmiddle" alt="ไฟเออร์บลาสท์"> ไฟเออร์บลาสท์ | 5 | 💥 AoE |  |
| 32023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/123:0:0" width="20" height="20" align="absmiddle" alt="บลิสซาร์ด"> บลิสซาร์ด | 5 | 💥🔒 AoE+CC |  |
| 32024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/107:0:0" width="20" height="20" align="absmiddle" alt="ไลท์นิ่งสโตน"> ไลท์นิ่งสโตน | 5 | 🔒 CC |  |
| 35001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/55:0:0" width="20" height="20" align="absmiddle" alt="อินเทลิเจนท์"> อินเทลิเจนท์ | 3 | ✨ Buff |  |
| 35027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/122:0:0" width="20" height="20" align="absmiddle" alt="มานาออร่า"> มานาออร่า | 2 | 🔄 Toggle |  |
| 35031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/441:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สวิสดอม"> รีอินฟอร์สวิสดอม | 6 | 💥 AoE |  |
| 35032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/442:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งเมจิก"> เบลสซิ่งเมจิก | 6 | 🔄 Toggle |  |

---

#### 3233 ม็องค์ (C3)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 32027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/128:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่สวิง"> โฮลี่สวิง | 5 | 🔒 CC |  |
| 32028 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/129:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่สไปค์"> โฮลี่สไปค์ | 5 | 🩹 Heal |  |
| 32029 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/130:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่อัพเปอร์"> โฮลี่อัพเปอร์ | 5 | 🔒 CC |  |
| 32040 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/201:0:0" width="20" height="20" align="absmiddle" alt="คริปเปิ้ล"> คริปเปิ้ล | 2 | 💥🔒 AoE+CC |  |
| 33002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/60:0:0" width="20" height="20" align="absmiddle" alt="โร๊บเอ็กซเพอร์ไทซ์"> โร๊บเอ็กซเพอร์ไทซ์ | 5 | 🟢 Passive |  |
| 35001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/55:0:0" width="20" height="20" align="absmiddle" alt="อินเทลิเจนท์"> อินเทลิเจนท์ | 2 | ✨ Buff |  |
| 35002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/56:0:0" width="20" height="20" align="absmiddle" alt="วิสดอม"> วิสดอม | 2 | ✨ Buff |  |
| 35008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/133:0:0" width="20" height="20" align="absmiddle" alt="เบลสเฟทอล"> เบลสเฟทอล | 2 | 🩹 Heal |  |
| 35023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/234:0:0" width="20" height="20" align="absmiddle" alt="ทวิงเกิ้ลเมจิก"> ทวิงเกิ้ลเมจิก | 2 | ✨ Buff |  |
| 32006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/53:0:0" width="20" height="20" align="absmiddle" alt="เคียวร์พ้อยซั่น"> เคียวร์พ้อยซั่น | 2 | ⚔️ Attack |  |
| 35031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/441:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สวิสดอม"> รีอินฟอร์สวิสดอม | 6 | 💥 AoE |  |
| 35032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/442:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งเมจิก"> เบลสซิ่งเมจิก | 6 | 🔄 Toggle |  |

---

#### 3241 บิชอป (C4)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 32007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/54:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่สไตรค์"> โฮลี่สไตรค์ | 20 | ⚔️ Attack |  |
| 32008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/64:0:0" width="20" height="20" align="absmiddle" alt="ฟาสท์ฮีล"> ฟาสท์ฮีล | 15 | ⚔️ Attack |  |
| 32009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/66:0:0" width="20" height="20" align="absmiddle" alt="ดีไวน์จัดจ์เมนท์"> ดีไวน์จัดจ์เมนท์ | 30 | 💀 Debuff |  |
| 32019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/87:0:0" width="20" height="20" align="absmiddle" alt="รีเวิร์ส"> รีเวิร์ส | 2 | ⚔️ Attack |  |
| 32020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/118:0:0" width="20" height="20" align="absmiddle" alt="กรุ๊ปฮีล"> กรุ๊ปฮีล | 15 | 💥 AoE |  |
| 32004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/51:0:0" width="20" height="20" align="absmiddle" alt="ฮีล"> ฮีล | 20 | ⚔️ Attack |  |
| 32033 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/194:0:0" width="20" height="20" align="absmiddle" alt="แซคริไฟซ์"> แซคริไฟซ์ | 1 | 💥 AoE |  |
| 32044 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/234:0:0" width="20" height="20" align="absmiddle" alt="ทรานสเฟอร์มานา"> ทรานสเฟอร์มานา | 5 | ⚔️ Attack |  |
| 33005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/63:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ MP"> เอนฮานซ์ MP | 7 | 🟢 Passive |  |
| 35002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/56:0:0" width="20" height="20" align="absmiddle" alt="วิสดอม"> วิสดอม | 5 | ✨ Buff |  |
| 35003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/57:0:0" width="20" height="20" align="absmiddle" alt="เบลสฮาร์ท"> เบลสฮาร์ท | 7 | ✨ Buff |  |
| 35006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/68:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่แบริเออร์"> โฮลี่แบริเออร์ | 3 | utility |  |
| 35007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/76:0:0" width="20" height="20" align="absmiddle" alt="วิสาร์ดลี่"> วิสาร์ดลี่ | 3 | ✨ Buff |  |
| 35010 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/121:0:0" width="20" height="20" align="absmiddle" alt="ไมท์"> ไมท์ | 3 | ✨ Buff |  |
| 35011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/122:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์"> ชิลด์ | 3 | ✨ Buff |  |
| 35013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/25:0:0" width="20" height="20" align="absmiddle" alt="บีโฮลเดอร์"> บีโฮลเดอร์ | 4 | 💥 AoE |  |
| 35014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/205:0:0" width="20" height="20" align="absmiddle" alt="ชรูดสเพ็ล"> ชรูดสเพ็ล | 3 | ✨ Buff |  |
| 35027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/122:0:0" width="20" height="20" align="absmiddle" alt="มานาออร่า"> มานาออร่า | 5 | 🔄 Toggle |  |
| 32006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/53:0:0" width="20" height="20" align="absmiddle" alt="เคียวร์พ้อยซั่น"> เคียวร์พ้อยซั่น | 4 | ⚔️ Attack |  |
| 35031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/441:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สวิสดอม"> รีอินฟอร์สวิสดอม | 8 | 💥 AoE |  |
| 35032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/442:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งเมจิก"> เบลสซิ่งเมจิก | 8 | 🔄 Toggle |  |
| 32032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/193:0:0" width="20" height="20" align="absmiddle" alt="เทิร์นอันเด๊ด"> เทิร์นอันเด๊ด | 10 | 💥 AoE |  |

---

#### 3242 วอร์ล็อค (C4)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 32011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/70:0:0" width="20" height="20" align="absmiddle" alt="เบิร์นนิ่งไฟร์"> เบิร์นนิ่งไฟร์ | 20 | 💀 Debuff |  |
| 32012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/71:0:0" width="20" height="20" align="absmiddle" alt="ชิลบรีซ"> ชิลบรีซ | 20 | 🔒 CC |  |
| 32015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/74:0:0" width="20" height="20" align="absmiddle" alt="อีเวนนอม"> อีเวนนอม | 20 | 💀 Debuff |  |
| 32016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/75:0:0" width="20" height="20" align="absmiddle" alt="บลัดสตีม"> บลัดสตีม | 5 | ⚔️ Attack |  |
| 32018 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/88:0:0" width="20" height="20" align="absmiddle" alt="วินด์สไปค์"> วินด์สไปค์ | 20 | 💥 AoE |  |
| 32022 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/103:0:0" width="20" height="20" align="absmiddle" alt="ไฟเออร์บลาสท์"> ไฟเออร์บลาสท์ | 20 | 💥 AoE |  |
| 32023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/123:0:0" width="20" height="20" align="absmiddle" alt="บลิสซาร์ด"> บลิสซาร์ด | 20 | 💥🔒 AoE+CC |  |
| 32024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/107:0:0" width="20" height="20" align="absmiddle" alt="ไลท์นิ่งสโตน"> ไลท์นิ่งสโตน | 20 | 🔒 CC |  |
| 32034 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/195:0:0" width="20" height="20" align="absmiddle" alt="ไฟเออร์เบิร์สติ้ง"> ไฟเออร์เบิร์สติ้ง | 10 | 🔒 CC |  |
| 32035 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/196:0:0" width="20" height="20" align="absmiddle" alt="มิทิเออร์"> มิทิเออร์ | 10 | 💥 AoE |  |
| 32036 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/197:0:0" width="20" height="20" align="absmiddle" alt="ธันเดอร์เบรค"> ธันเดอร์เบรค | 10 | 💥🔒 AoE+CC |  |
| 32037 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/198:0:0" width="20" height="20" align="absmiddle" alt="วีนอมคลาวด์"> วีนอมคลาวด์ | 20 | 🩹 Heal |  |
| 33006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/77:0:0" width="20" height="20" align="absmiddle" alt="สเพ็ลคราฟท์"> สเพ็ลคราฟท์ | 5 | 🟢 Passive |  |
| 35001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/55:0:0" width="20" height="20" align="absmiddle" alt="อินเทลิเจนท์"> อินเทลิเจนท์ | 5 | ✨ Buff |  |
| 35027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/122:0:0" width="20" height="20" align="absmiddle" alt="มานาออร่า"> มานาออร่า | 3 | 🔄 Toggle |  |
| 35031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/441:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สวิสดอม"> รีอินฟอร์สวิสดอม | 8 | 💥 AoE |  |
| 35032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/442:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งเมจิก"> เบลสซิ่งเมจิก | 8 | 🔄 Toggle |  |
| 32036 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/197:0:0" width="20" height="20" align="absmiddle" alt="ธันเดอร์เบรค"> ธันเดอร์เบรค | 20 | 💥🔒 AoE+CC |  |
| 32034 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/195:0:0" width="20" height="20" align="absmiddle" alt="ไฟเออร์เบิร์สติ้ง"> ไฟเออร์เบิร์สติ้ง | 20 | 🔒 CC |  |
| 32017 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/86:0:0" width="20" height="20" align="absmiddle" alt="ดีไวน์โฮลด์"> ดีไวน์โฮลด์ | 15 | 💥🔒 AoE+CC |  |

---

#### 3243 อินไควเรอร์ (C4)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 32027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/128:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่สวิง"> โฮลี่สวิง | 10 | 🔒 CC |  |
| 32028 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/129:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่สไปค์"> โฮลี่สไปค์ | 10 | 🩹 Heal |  |
| 32029 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/130:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่อัพเปอร์"> โฮลี่อัพเปอร์ | 10 | 🔒 CC |  |
| 32038 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/199:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่จัสติส"> โฮลี่จัสติส | 10 | 💥 AoE |  |
| 32039 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/200:0:0" width="20" height="20" align="absmiddle" alt="ทรานควิลลิตี้"> ทรานควิลลิตี้ | 2 | 💥🔒 AoE+CC |  |
| 32040 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/201:0:0" width="20" height="20" align="absmiddle" alt="คริปเปิ้ล"> คริปเปิ้ล | 4 | 💥🔒 AoE+CC |  |
| 33002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/60:0:0" width="20" height="20" align="absmiddle" alt="โร๊บเอ็กซเพอร์ไทซ์"> โร๊บเอ็กซเพอร์ไทซ์ | 10 | 🟢 Passive |  |
| 35001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/55:0:0" width="20" height="20" align="absmiddle" alt="อินเทลิเจนท์"> อินเทลิเจนท์ | 3 | ✨ Buff |  |
| 35002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/56:0:0" width="20" height="20" align="absmiddle" alt="วิสดอม"> วิสดอม | 3 | ✨ Buff |  |
| 35008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/133:0:0" width="20" height="20" align="absmiddle" alt="เบลสเฟทอล"> เบลสเฟทอล | 4 | 🩹 Heal |  |
| 35016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/207:0:0" width="20" height="20" align="absmiddle" alt="คอนเซ็นเทรชั่น"> คอนเซ็นเทรชั่น | 2 | ✨ Buff |  |
| 35023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/234:0:0" width="20" height="20" align="absmiddle" alt="ทวิงเกิ้ลเมจิก"> ทวิงเกิ้ลเมจิก | 5 | ✨ Buff |  |
| 32006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/53:0:0" width="20" height="20" align="absmiddle" alt="เคียวร์พ้อยซั่น"> เคียวร์พ้อยซั่น | 3 | ⚔️ Attack |  |
| 35031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/441:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สวิสดอม"> รีอินฟอร์สวิสดอม | 8 | 💥 AoE |  |
| 35032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/442:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งเมจิก"> เบลสซิ่งเมจิก | 8 | 🔄 Toggle |  |
| 35017 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/208:0:0" width="20" height="20" align="absmiddle" alt="ฟอร์จูนเนทเมจิค"> ฟอร์จูนเนทเมจิค | 5 | ✨ Buff |  |
| 13005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/12:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ HP"> เอนฮานซ์ HP | 10 | 🟢 Passive |  |
| 13012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/15:0:0" width="20" height="20" align="absmiddle" alt="เมซเทรนนิ่ง"> เมซเทรนนิ่ง | 10 | 🟢 Passive |  |
| 13018 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/225:0:0" width="20" height="20" align="absmiddle" alt="เมสโพรเทคชั่น"> เมสโพรเทคชั่น | 10 | 🟢 Passive |  |

---

#### 3244 เอเลเมนทัลมาสเตอร์ (C4)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 32007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/54:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่สไตรค์"> โฮลี่สไตรค์ | 20 | ⚔️ Attack |  |
| 32009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/66:0:0" width="20" height="20" align="absmiddle" alt="ดีไวน์จัดจ์เมนท์"> ดีไวน์จัดจ์เมนท์ | 30 | 💀 Debuff |  |
| 32019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/87:0:0" width="20" height="20" align="absmiddle" alt="รีเวิร์ส"> รีเวิร์ส | 1 | ⚔️ Attack |  |
| 32020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/118:0:0" width="20" height="20" align="absmiddle" alt="กรุ๊ปฮีล"> กรุ๊ปฮีล | 10 | 💥 AoE |  |
| 33005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/63:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ MP"> เอนฮานซ์ MP | 10 | 🟢 Passive |  |
| 35002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/56:0:0" width="20" height="20" align="absmiddle" alt="วิสดอม"> วิสดอม | 3 | ✨ Buff |  |
| 35003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/57:0:0" width="20" height="20" align="absmiddle" alt="เบลสฮาร์ท"> เบลสฮาร์ท | 5 | ✨ Buff |  |
| 35010 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/121:0:0" width="20" height="20" align="absmiddle" alt="ไมท์"> ไมท์ | 5 | ✨ Buff |  |
| 35011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/122:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์"> ชิลด์ | 5 | ✨ Buff |  |
| 35019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/210:0:0" width="20" height="20" align="absmiddle" alt="พินพอยท์"> พินพอยท์ | 3 | 💥 AoE |  |
| 35020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/211:0:0" width="20" height="20" align="absmiddle" alt="คิสออฟเดธ"> คิสออฟเดธ | 3 | 💥 AoE |  |
| 35021 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/212:0:0" width="20" height="20" align="absmiddle" alt="เคล้าท์"> เคล้าท์ | 3 | 💥 AoE |  |
| 35027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/122:0:0" width="20" height="20" align="absmiddle" alt="มานาออร่า"> มานาออร่า | 4 | 🔄 Toggle |  |
| 32006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/53:0:0" width="20" height="20" align="absmiddle" alt="เคียวร์พ้อยซั่น"> เคียวร์พ้อยซั่น | 3 | ⚔️ Attack |  |
| 35031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/441:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สวิสดอม"> รีอินฟอร์สวิสดอม | 8 | 💥 AoE |  |
| 35032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/442:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งเมจิก"> เบลสซิ่งเมจิก | 8 | 🔄 Toggle |  |
| 32032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/193:0:0" width="20" height="20" align="absmiddle" alt="เทิร์นอันเด๊ด"> เทิร์นอันเด๊ด | 10 | 💥 AoE |  |
| 33002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/60:0:0" width="20" height="20" align="absmiddle" alt="โร๊บเอ็กซเพอร์ไทซ์"> โร๊บเอ็กซเพอร์ไทซ์ | 10 | 🟢 Passive |  |
| 32014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/73:0:0" width="20" height="20" align="absmiddle" alt="เคิร์ซวีคเนส"> เคิร์ซวีคเนส | 10 | 💀 Debuff |  |
| 32025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/126:0:0" width="20" height="20" align="absmiddle" alt="สลีปปิ้งสโตน"> สลีปปิ้งสโตน | 20 | 🔒 CC |  |
| 32026 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/127:0:0" width="20" height="20" align="absmiddle" alt="ไบน์ดิ้งโซล"> ไบน์ดิ้งโซล | 20 | 🔒 CC |  |
| 35006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/68:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่แบริเออร์"> โฮลี่แบริเออร์ | 4 | utility |  |

---

#### 3251 คาร์ดินัล (C5)

> 🟡 **Overall: 83.0**/100 · DMG `100` · AoE `100` · CC `86` · Util `75` · Surv `52`

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 32008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/64:0:0" width="20" height="20" align="absmiddle" alt="ฟาสท์ฮีล"> ฟาสท์ฮีล | 20 | ⚔️ Attack |  |
| 32019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/87:0:0" width="20" height="20" align="absmiddle" alt="รีเวิร์ส"> รีเวิร์ส | 3 | ⚔️ Attack | ⚠️ DPS ต่ำ (1) / 💧 Mana สิ้นเปลือง |
| 32020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/118:0:0" width="20" height="20" align="absmiddle" alt="กรุ๊ปฮีล"> กรุ๊ปฮีล | 20 | 💥 AoE | ⚠️ DPS ต่ำ (25) |
| 32004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/51:0:0" width="20" height="20" align="absmiddle" alt="ฮีล"> ฮีล | 20 | ⚔️ Attack |  |
| 32033 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/194:0:0" width="20" height="20" align="absmiddle" alt="แซคริไฟซ์"> แซคริไฟซ์ | 3 | 💥 AoE | ⚠️ DPS ต่ำ (9) |
| 32044 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/234:0:0" width="20" height="20" align="absmiddle" alt="ทรานสเฟอร์มานา"> ทรานสเฟอร์มานา | 10 | ⚔️ Attack | ⚠️ DPS ต่ำ (25) / 💧 Mana สิ้นเปลือง |
| 32046 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/22:0:0" width="20" height="20" align="absmiddle" alt="เดมอนสไปค์"> เดมอนสไปค์ | 10 | 💥🔒 AoE+CC |  |
| 32047 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/206:0:0" width="20" height="20" align="absmiddle" alt="อันเดดเทคเกอร์"> อันเดดเทคเกอร์ | 10 | 💥 AoE |  |
| 33005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/63:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ MP"> เอนฮานซ์ MP | 20 | 🟢 Passive |  |
| 35002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/56:0:0" width="20" height="20" align="absmiddle" alt="วิสดอม"> วิสดอม | 7 | ✨ Buff |  |
| 35003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/57:0:0" width="20" height="20" align="absmiddle" alt="เบลสฮาร์ท"> เบลสฮาร์ท | 9 | ✨ Buff |  |
| 35006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/68:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่แบริเออร์"> โฮลี่แบริเออร์ | 5 | utility |  |
| 35007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/76:0:0" width="20" height="20" align="absmiddle" alt="วิสาร์ดลี่"> วิสาร์ดลี่ | 5 | ✨ Buff |  |
| 35013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/25:0:0" width="20" height="20" align="absmiddle" alt="บีโฮลเดอร์"> บีโฮลเดอร์ | 6 | 💥 AoE |  |
| 35014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/205:0:0" width="20" height="20" align="absmiddle" alt="ชรูดสเพ็ล"> ชรูดสเพ็ล | 5 | ✨ Buff |  |
| 35022 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/230:0:0" width="20" height="20" align="absmiddle" alt="อินเทนสิฝมานา"> อินเทนสิฝมานา | 3 | 💥 AoE |  |
| 35026 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/55:0:0" width="20" height="20" align="absmiddle" alt="จุดเยือกแข็งแห่งโอลฟีอุส"> จุดเยือกแข็งแห่งโอลฟีอุส | 6 | 💥 AoE |  |
| 35027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/122:0:0" width="20" height="20" align="absmiddle" alt="มานาออร่า"> มานาออร่า | 9 | 🔄 Toggle |  |
| 32006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/53:0:0" width="20" height="20" align="absmiddle" alt="เคียวร์พ้อยซั่น"> เคียวร์พ้อยซั่น | 5 | ⚔️ Attack | ⚠️ DPS ต่ำ (13) / 💧 Mana สิ้นเปลือง |
| 35031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/441:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สวิสดอม"> รีอินฟอร์สวิสดอม | 10 | 💥 AoE |  |
| 35032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/442:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งเมจิก"> เบลสซิ่งเมจิก | 10 | 🔄 Toggle |  |
| 32032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/193:0:0" width="20" height="20" align="absmiddle" alt="เทิร์นอันเด๊ด"> เทิร์นอันเด๊ด | 15 | 💥 AoE |  |
| 33007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/78:0:0" width="20" height="20" align="absmiddle" alt="เมจิคแบริเออร์"> เมจิคแบริเออร์ | 20 | 🟢 Passive |  |
| 32007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/54:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่สไตรค์"> โฮลี่สไตรค์ | 30 | ⚔️ Attack |  |
| 13005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/12:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ HP"> เอนฮานซ์ HP | 20 | 🟢 Passive |  |
| 33002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/60:0:0" width="20" height="20" align="absmiddle" alt="โร๊บเอ็กซเพอร์ไทซ์"> โร๊บเอ็กซเพอร์ไทซ์ | 20 | 🟢 Passive |  |
| 35004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/58:0:0" width="20" height="20" align="absmiddle" alt="มายนด์แบริเออร์"> มายนด์แบริเออร์ | 8 | ✨ Buff |  |
| 35009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/120:0:0" width="20" height="20" align="absmiddle" alt="เบลสวินด์"> เบลสวินด์ | 7 | ✨ Buff |  |
| 35005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/67:0:0" width="20" height="20" align="absmiddle" alt="เบลสมายนด์"> เบลสมายนด์ | 7 | ✨ Buff |  |
| 33010 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/70085:0:0" width="20" height="20" align="absmiddle" alt="เคียวร์เบลสเพอร์เฟคชั่น"> เคียวร์เบลสเพอร์เฟคชั่น | 10 | ⚔️ Attack | ⚠️ DPS ต่ำ (12) / 💧 Mana สิ้นเปลือง |
| 33011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/70086:0:0" width="20" height="20" align="absmiddle" alt="เคียวร์เคิร์ซเอ็กซ์เครชั่น"> เคียวร์เคิร์ซเอ็กซ์เครชั่น | 10 | ⚔️ Attack | ⚠️ DPS ต่ำ (12) / 💧 Mana สิ้นเปลือง |
| 32024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/107:0:0" width="20" height="20" align="absmiddle" alt="ไลท์นิ่งสโตน"> ไลท์นิ่งสโตน | 30 | 🔒 CC |  |
| 32036 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/197:0:0" width="20" height="20" align="absmiddle" alt="ธันเดอร์เบรค"> ธันเดอร์เบรค | 30 | 💥🔒 AoE+CC |  |

<details><summary>⚠️ <strong>คำแนะนำการปรับสมดุล (1 รายการ)</strong></summary>

| # | ประเภท | มิติ | รายละเอียด | ไฟล์ที่แก้ | Gap |
|---|--------|------|----------|------------|-----|
| 1 | 🔧 ปรับ | Survivability | 🛡️ ปรับค่า fStatusDataMul สกิลบัฟ/ฮีล (×1.3-1.5) | `Skill_Buff_List.bin.txt` | 13.0 |

</details>

---

#### 3252 โซลอาร์บิเตอร์ (C5)

> 🟢 **Overall: 91.2**/100 · DMG `100` · AoE `80` · CC `100` · Util `87` · Surv `85`

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 32027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/128:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่สวิง"> โฮลี่สวิง | 20 | 🔒 CC |  |
| 32028 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/129:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่สไปค์"> โฮลี่สไปค์ | 20 | 🩹 Heal |  |
| 32029 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/130:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่อัพเปอร์"> โฮลี่อัพเปอร์ | 20 | 🔒 CC |  |
| 32038 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/199:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่จัสติส"> โฮลี่จัสติส | 20 | 💥 AoE |  |
| 32039 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/200:0:0" width="20" height="20" align="absmiddle" alt="ทรานควิลลิตี้"> ทรานควิลลิตี้ | 4 | 💥🔒 AoE+CC |  |
| 32040 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/201:0:0" width="20" height="20" align="absmiddle" alt="คริปเปิ้ล"> คริปเปิ้ล | 6 | 💥🔒 AoE+CC |  |
| 32049 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/101:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่เอิร์ธเควค"> โฮลี่เอิร์ธเควค | 10 | 💥🔒 AoE+CC |  |
| 32050 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/195:0:0" width="20" height="20" align="absmiddle" alt="มานาเบิร์น"> มานาเบิร์น | 5 | 💀 Debuff |  |
| 33002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/60:0:0" width="20" height="20" align="absmiddle" alt="โร๊บเอ็กซเพอร์ไทซ์"> โร๊บเอ็กซเพอร์ไทซ์ | 20 | 🟢 Passive |  |
| 35001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/55:0:0" width="20" height="20" align="absmiddle" alt="อินเทลิเจนท์"> อินเทลิเจนท์ | 4 | ✨ Buff |  |
| 35002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/56:0:0" width="20" height="20" align="absmiddle" alt="วิสดอม"> วิสดอม | 4 | ✨ Buff |  |
| 35004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/58:0:0" width="20" height="20" align="absmiddle" alt="มายนด์แบริเออร์"> มายนด์แบริเออร์ | 5 | ✨ Buff |  |
| 35008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/133:0:0" width="20" height="20" align="absmiddle" alt="เบลสเฟทอล"> เบลสเฟทอล | 6 | 🩹 Heal |  |
| 35016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/207:0:0" width="20" height="20" align="absmiddle" alt="คอนเซ็นเทรชั่น"> คอนเซ็นเทรชั่น | 4 | ✨ Buff |  |
| 35023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/234:0:0" width="20" height="20" align="absmiddle" alt="ทวิงเกิ้ลเมจิก"> ทวิงเกิ้ลเมจิก | 8 | ✨ Buff |  |
| 35031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/441:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สวิสดอม"> รีอินฟอร์สวิสดอม | 10 | 💥 AoE |  |
| 35032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/442:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งเมจิก"> เบลสซิ่งเมจิก | 10 | 🔄 Toggle |  |
| 35017 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/208:0:0" width="20" height="20" align="absmiddle" alt="ฟอร์จูนเนทเมจิค"> ฟอร์จูนเนทเมจิค | 5 | ✨ Buff |  |
| 33007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/78:0:0" width="20" height="20" align="absmiddle" alt="เมจิคแบริเออร์"> เมจิคแบริเออร์ | 20 | 🟢 Passive |  |
| 13005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/12:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ HP"> เอนฮานซ์ HP | 20 | 🟢 Passive |  |
| 33005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/63:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ MP"> เอนฮานซ์ MP | 20 | 🟢 Passive |  |
| 33006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/77:0:0" width="20" height="20" align="absmiddle" alt="สเพ็ลคราฟท์"> สเพ็ลคราฟท์ | 20 | 🟢 Passive |  |
| 13012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/15:0:0" width="20" height="20" align="absmiddle" alt="เมซเทรนนิ่ง"> เมซเทรนนิ่ง | 20 | 🟢 Passive |  |
| 13018 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/225:0:0" width="20" height="20" align="absmiddle" alt="เมสโพรเทคชั่น"> เมสโพรเทคชั่น | 20 | 🟢 Passive |  |
| 13004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/20:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์เทรนนิ่ง"> ชิลด์เทรนนิ่ง | 20 | 🟢 Passive |  |
| 32051 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/129:0:0" width="20" height="20" align="absmiddle" alt="โซลสเปียร์"> โซลสเปียร์ | 10 | 💀 Debuff |  |
| 35012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/132:0:0" width="20" height="20" align="absmiddle" alt="อาร์เมอร์ลิงค์"> อาร์เมอร์ลิงค์ | 8 | ✨ Buff |  |

> ✅ **สมดุลดี** — ไม่มีข้อแนะนำเพิ่มเติม

---

#### 3253 แกรนด์มาสเตอร์ (C5)

> 🔴 **Overall: 79.8**/100 · DMG `95` · AoE `100` · CC `96` · Util `66` · Surv `42`

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 32016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/75:0:0" width="20" height="20" align="absmiddle" alt="บลัดสตีม"> บลัดสตีม | 7 | ⚔️ Attack | ⚠️ DPS ต่ำ (18) |
| 32030 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/59:0:0" width="20" height="20" align="absmiddle" alt="บูสท์สเพ็ล"> บูสท์สเพ็ล | 3 | ✨ Buff |  |
| 32035 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/196:0:0" width="20" height="20" align="absmiddle" alt="มิทิเออร์"> มิทิเออร์ | 20 | 💥 AoE |  |
| 32052 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/100:0:0" width="20" height="20" align="absmiddle" alt="ทอร์นาโดอัปเปอร์"> ทอร์นาโดอัปเปอร์ | 10 | 💥🔒 AoE+CC |  |
| 32054 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/71:0:0" width="20" height="20" align="absmiddle" alt="เดธชิลลี่เนส"> เดธชิลลี่เนส | 20 | 💥🔒 AoE+CC |  |
| 32055 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/197:0:0" width="20" height="20" align="absmiddle" alt="เกรทธันเดอร์"> เกรทธันเดอร์ | 10 | 💥🔒 AoE+CC |  |
| 33006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/77:0:0" width="20" height="20" align="absmiddle" alt="สเพ็ลคราฟท์"> สเพ็ลคราฟท์ | 20 | 🟢 Passive |  |
| 35001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/55:0:0" width="20" height="20" align="absmiddle" alt="อินเทลิเจนท์"> อินเทลิเจนท์ | 7 | ✨ Buff |  |
| 35027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/122:0:0" width="20" height="20" align="absmiddle" alt="มานาออร่า"> มานาออร่า | 5 | 🔄 Toggle |  |
| 35031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/441:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สวิสดอม"> รีอินฟอร์สวิสดอม | 10 | 💥 AoE |  |
| 35032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/442:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งเมจิก"> เบลสซิ่งเมจิก | 10 | 🔄 Toggle |  |
| 33009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/213:0:0" width="20" height="20" align="absmiddle" alt="วิทช์คราฟท์"> วิทช์คราฟท์ | 6 | 🟢 Passive |  |
| 33005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/63:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ MP"> เอนฮานซ์ MP | 20 | 🟢 Passive |  |
| 35005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/67:0:0" width="20" height="20" align="absmiddle" alt="เบลสมายนด์"> เบลสมายนด์ | 3 | ✨ Buff |  |

<details><summary>⚠️ <strong>คำแนะนำการปรับสมดุล (2 รายการ)</strong></summary>

| # | ประเภท | มิติ | รายละเอียด | ไฟล์ที่แก้ | Gap |
|---|--------|------|----------|------------|-----|
| 1 | 🔧 ปรับ | Survivability | 🛡️ ปรับค่า fStatusDataMul สกิลบัฟ/ฮีล (×1.3-1.5) | `Skill_Buff_List.bin.txt` | 23.0 |
| 2 | 🔧 ปรับ | Utility | ✨ ปรับค่า fStatusDataMul สกิลบัฟ (×1.3-1.5) | `Skill_Buff_List.bin.txt` | 9.0 |

</details>

---

#### 3254 เนโครแมนเซอร์ (C5)

> 🔴 **Overall: 57.6**/100 · DMG `100` · AoE `95` · CC `0` · Util `72` · Surv `12`

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 32010 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/65:0:0" width="20" height="20" align="absmiddle" alt="แองเจลิคทัช"> แองเจลิคทัช | 30 | 💀 Debuff |  |
| 32014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/73:0:0" width="20" height="20" align="absmiddle" alt="เคิร์ซวีคเนส"> เคิร์ซวีคเนส | 20 | 💀 Debuff |  |
| 32015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/74:0:0" width="20" height="20" align="absmiddle" alt="อีเวนนอม"> อีเวนนอม | 20 | 💀 Debuff |  |
| 32016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/75:0:0" width="20" height="20" align="absmiddle" alt="บลัดสตีม"> บลัดสตีม | 6 | ⚔️ Attack | ⚠️ DPS ต่ำ (18) |
| 32022 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/103:0:0" width="20" height="20" align="absmiddle" alt="ไฟเออร์บลาสท์"> ไฟเออร์บลาสท์ | 30 | 💥 AoE |  |
| 32035 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/196:0:0" width="20" height="20" align="absmiddle" alt="มิทิเออร์"> มิทิเออร์ | 20 | 💥 AoE |  |
| 32037 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/198:0:0" width="20" height="20" align="absmiddle" alt="วีนอมคลาวด์"> วีนอมคลาวด์ | 30 | 🩹 Heal |  |
| 32060 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/226:0:0" width="20" height="20" align="absmiddle" alt="ไวทัลเอ็กซ์โพลชั่น"> ไวทัลเอ็กซ์โพลชั่น | 10 | 💥 AoE |  |
| 32063 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/8:0:0" width="20" height="20" align="absmiddle" alt="คอร์ปซ์เทค"> คอร์ปซ์เทค | 5 | 💥 AoE |  |
| 35001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/55:0:0" width="20" height="20" align="absmiddle" alt="อินเทลิเจนท์"> อินเทลิเจนท์ | 6 | ✨ Buff |  |
| 35024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/22:0:0" width="20" height="20" align="absmiddle" alt="เดฟวิลอาร์มเมอร์"> เดฟวิลอาร์มเมอร์ | 10 | ✨ Buff |  |
| 35031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/441:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สวิสดอม"> รีอินฟอร์สวิสดอม | 10 | 💥 AoE |  |
| 35032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/442:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งเมจิก"> เบลสซิ่งเมจิก | 10 | 🔄 Toggle |  |
| 35007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/76:0:0" width="20" height="20" align="absmiddle" alt="วิสาร์ดลี่"> วิสาร์ดลี่ | 5 | ✨ Buff |  |
| 35027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/122:0:0" width="20" height="20" align="absmiddle" alt="มานาออร่า"> มานาออร่า | 9 | 🔄 Toggle |  |
| 32007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/54:0:0" width="20" height="20" align="absmiddle" alt="โฮลี่สไตรค์"> โฮลี่สไตรค์ | 30 | ⚔️ Attack |  |
| 32059 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/113:0:0" width="20" height="20" align="absmiddle" alt="โบนสเปียร์"> โบนสเปียร์ | 10 | 💀 Debuff |  |
| 32058 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/98:0:0" width="20" height="20" align="absmiddle" alt="โซลสควิซ"> โซลสควิซ | 10 | ✨ Buff |  |

<details><summary>⚠️ <strong>คำแนะนำการปรับสมดุล (3 รายการ)</strong></summary>

| # | ประเภท | มิติ | รายละเอียด | ไฟล์ที่แก้ | Gap |
|---|--------|------|----------|------------|-----|
| 1 | ➕ เพิ่ม | CC | 🔒 เพิ่มสกิล CC (Stun/Slow) อย่างน้อย 2-3 ตัว หรือเพิ่ม CC Buff ในสกิลโจมตี | `Skill_Get_List / Skill_Buff_List` | 75.0 |
| 2 | 🔧 ปรับ | Survivability | 🛡️ ปรับค่า fStatusDataMul สกิลบัฟ/ฮีล (×1.3-1.5) | `Skill_Buff_List.bin.txt` | 53.0 |
| 3 | 🔧 ปรับ | Utility | ✨ ปรับค่า fStatusDataMul สกิลบัฟ (×1.3-1.5) | `Skill_Buff_List.bin.txt` | 3.0 |

</details>

---

#### 3255 รูนมาสเตอร์ (C5)

> 🟡 **Overall: 87.2**/100 · DMG `87` · AoE `95` · CC `100` · Util `87` · Surv `71`

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 32019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/87:0:0" width="20" height="20" align="absmiddle" alt="รีเวิร์ส"> รีเวิร์ส | 1 | ⚔️ Attack | ⚠️ DPS ต่ำ (1) / 💧 Mana สิ้นเปลือง |
| 32020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/118:0:0" width="20" height="20" align="absmiddle" alt="กรุ๊ปฮีล"> กรุ๊ปฮีล | 15 | 💥 AoE | ⚠️ DPS ต่ำ (25) |
| 32061 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/98:0:0" width="20" height="20" align="absmiddle" alt="รูนไซเลนซ์"> รูนไซเลนซ์ | 5 | 🔒 CC |  |
| 33005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/63:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ MP"> เอนฮานซ์ MP | 20 | 🟢 Passive |  |
| 35002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/56:0:0" width="20" height="20" align="absmiddle" alt="วิสดอม"> วิสดอม | 6 | ✨ Buff |  |
| 35003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/57:0:0" width="20" height="20" align="absmiddle" alt="เบลสฮาร์ท"> เบลสฮาร์ท | 7 | ✨ Buff |  |
| 35010 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/121:0:0" width="20" height="20" align="absmiddle" alt="ไมท์"> ไมท์ | 7 | ✨ Buff |  |
| 35011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/122:0:0" width="20" height="20" align="absmiddle" alt="ชิลด์"> ชิลด์ | 7 | ✨ Buff |  |
| 35019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/210:0:0" width="20" height="20" align="absmiddle" alt="พินพอยท์"> พินพอยท์ | 5 | 💥 AoE |  |
| 35020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/211:0:0" width="20" height="20" align="absmiddle" alt="คิสออฟเดธ"> คิสออฟเดธ | 5 | 💥 AoE |  |
| 35021 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/212:0:0" width="20" height="20" align="absmiddle" alt="เคล้าท์"> เคล้าท์ | 5 | 💥 AoE |  |
| 35028 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/98:0:0" width="20" height="20" align="absmiddle" alt="ฮาร์ทเบรค"> ฮาร์ทเบรค | 5 | 💥 AoE |  |
| 35027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/122:0:0" width="20" height="20" align="absmiddle" alt="มานาออร่า"> มานาออร่า | 7 | 🔄 Toggle |  |
| 35031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/441:0:0" width="20" height="20" align="absmiddle" alt="รีอินฟอร์สวิสดอม"> รีอินฟอร์สวิสดอม | 10 | 💥 AoE |  |
| 35032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/442:0:0" width="20" height="20" align="absmiddle" alt="เบลสซิ่งเมจิก"> เบลสซิ่งเมจิก | 10 | 🔄 Toggle |  |
| 13005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/12:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ HP"> เอนฮานซ์ HP | 20 | 🟢 Passive |  |
| 33007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/78:0:0" width="20" height="20" align="absmiddle" alt="เมจิคแบริเออร์"> เมจิคแบริเออร์ | 20 | 🟢 Passive |  |
| 35018 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/209:0:0" width="20" height="20" align="absmiddle" alt="แอทคิวท์เนส"> แอทคิวท์เนส | 4 | 🩹 Heal |  |
| 33002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/60:0:0" width="20" height="20" align="absmiddle" alt="โร๊บเอ็กซเพอร์ไทซ์"> โร๊บเอ็กซเพอร์ไทซ์ | 20 | 🟢 Passive |  |
| 32017 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/86:0:0" width="20" height="20" align="absmiddle" alt="ดีไวน์โฮลด์"> ดีไวน์โฮลด์ | 20 | 💥🔒 AoE+CC |  |
| 32066 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/70087:0:0" width="20" height="20" align="absmiddle" alt="รูนสโตนเคิร์ส"> รูนสโตนเคิร์ส | 5 | 🔒 CC |  |
| 32067 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/70088:0:0" width="20" height="20" align="absmiddle" alt="รูนไควท์เท็น"> รูนไควท์เท็น | 5 | 🔒 CC |  |
| 32012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/71:0:0" width="20" height="20" align="absmiddle" alt="ชิลบรีซ"> ชิลบรีซ | 30 | 🔒 CC |  |
| 32018 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/88:0:0" width="20" height="20" align="absmiddle" alt="วินด์สไปค์"> วินด์สไปค์ | 30 | 💥 AoE |  |
| 32023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/123:0:0" width="20" height="20" align="absmiddle" alt="บลิสซาร์ด"> บลิสซาร์ด | 30 | 💥🔒 AoE+CC |  |

<details><summary>⚠️ <strong>คำแนะนำการปรับสมดุล (1 รายการ)</strong></summary>

| # | ประเภท | มิติ | รายละเอียด | ไฟล์ที่แก้ | Gap |
|---|--------|------|----------|------------|-----|
| 1 | 🔧 ปรับ | Damage | ⚔️ ปรับค่า fUnitDataValueMul สกิลโจมตี (×1.2-1.5) | `SkillScript.bin.txt` | 7.6 |

</details>

---

## 😈 Devil (ปีศาจ)

> **Avg Rating:** 85.3/100 · **C5 Jobs:** 1 · เผ่าพิเศษ พลังทำลายล้างสูงสุด มี AoE และ CC จำนวนมาก
>
> DMG `100` · AoE `100` · CC `100` · Utility `68` · Survivability `56`

### Devil Devil

#### 4311 แอพเพรนทิส (C1)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 61001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/363:0:0" width="20" height="20" align="absmiddle" alt="อินเกจ"> อินเกจ | 5 | ⚔️ Attack |  |
| 61002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/28:0:0" width="20" height="20" align="absmiddle" alt="ดับเบิ้ลอิมแพค"> ดับเบิ้ลอิมแพค | 5 | 💀 Debuff |  |
| 61003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/105:0:0" width="20" height="20" align="absmiddle" alt="โซลดิไวเดอร์"> โซลดิไวเดอร์ | 5 | 💀 Debuff |  |
| 61012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/369:0:0" width="20" height="20" align="absmiddle" alt="ดาร์กไลท์นิ่ง"> ดาร์กไลท์นิ่ง | 5 | 🔒 CC |  |
| 61022 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/377:0:0" width="20" height="20" align="absmiddle" alt="เว็ปพอนเบรค"> เว็ปพอนเบรค | 5 | 💀 Debuff |  |
| 61023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/378:0:0" width="20" height="20" align="absmiddle" alt="อาร์เมอร์เบรค"> อาร์เมอร์เบรค | 5 | 💀 Debuff |  |
| 61024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/379:0:0" width="20" height="20" align="absmiddle" alt="มายด์เบรค"> มายด์เบรค | 5 | 💀 Debuff |  |
| 61025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/380:0:0" width="20" height="20" align="absmiddle" alt="ไนท์แมร์"> ไนท์แมร์ | 5 | 💥🔒 AoE+CC |  |
| 61029 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/384:0:0" width="20" height="20" align="absmiddle" alt="แบทเทิลฮิล"> แบทเทิลฮิล | 5 | 💀 Debuff |  |
| 60001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/267:0:0" width="20" height="20" align="absmiddle" alt="ดูอัลอันเดอร์"> ดูอัลอันเดอร์ | 5 | 🟢 Passive |  |
| 60003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/63:0:0" width="20" height="20" align="absmiddle" alt="เอวิลสปิริทชวล"> เอวิลสปิริทชวล | 5 | 🟢 Passive |  |
| 60004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/11:0:0" width="20" height="20" align="absmiddle" alt="อาเมอร์บาวู๊ด"> อาเมอร์บาวู๊ด | 5 | 🟢 Passive |  |
| 60005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/60:0:0" width="20" height="20" align="absmiddle" alt="เดโมนิกกิฟท์"> เดโมนิกกิฟท์ | 5 | 🟢 Passive |  |
| 61032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/360:0:0" width="20" height="20" align="absmiddle" alt="พรแห่งเบอร์เซ่"> พรแห่งเบอร์เซ่ | 1 | 🔄 Toggle |  |
| 61033 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/361:0:0" width="20" height="20" align="absmiddle" alt="พรแห่งรูเปีย"> พรแห่งรูเปีย | 1 | 🔄 Toggle |  |
| 61034 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/362:0:0" width="20" height="20" align="absmiddle" alt="พรแห่งฟาร์เซก้า"> พรแห่งฟาร์เซก้า | 1 | 🔄 Toggle |  |
| 33001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/59:0:0" width="20" height="20" align="absmiddle" alt="สต๊าฟเทรนนิ่ง"> สต๊าฟเทรนนิ่ง | 20 | 🟢 Passive |  |
| 13015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/232:0:0" width="20" height="20" align="absmiddle" alt="เรจเบอร์สท์"> เรจเบอร์สท์ | 8 | 🟢 Passive |  |
| 13005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/12:0:0" width="20" height="20" align="absmiddle" alt="เอนฮานซ์ HP"> เอนฮานซ์ HP | 20 | 🟢 Passive |  |
| 61040 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/68:0:0" width="20" height="20" align="absmiddle" alt="รูเปียแบริเออร์"> รูเปียแบริเออร์ | 4 | utility |  |
| 61041 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/112:0:0" width="20" height="20" align="absmiddle" alt="เบอร์เซ่สเทลธ์"> เบอร์เซ่สเทลธ์ | 4 | 🔄 Toggle |  |
| 61042 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/110043:0:0" width="20" height="20" align="absmiddle" alt="ฟาร์เซก้าชิลด์"> ฟาร์เซก้าชิลด์ | 4 | 💥 AoE |  |

---

#### 4321 คอมแบแทนท์ (C2)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 61001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/363:0:0" width="20" height="20" align="absmiddle" alt="อินเกจ"> อินเกจ | 10 | ⚔️ Attack |  |
| 61002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/28:0:0" width="20" height="20" align="absmiddle" alt="ดับเบิ้ลอิมแพค"> ดับเบิ้ลอิมแพค | 10 | 💀 Debuff |  |
| 61003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/105:0:0" width="20" height="20" align="absmiddle" alt="โซลดิไวเดอร์"> โซลดิไวเดอร์ | 10 | 💀 Debuff |  |
| 61004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/82:0:0" width="20" height="20" align="absmiddle" alt="อิโวนี่แดนซ์เซอร์"> อิโวนี่แดนซ์เซอร์ | 10 | 💥 AoE |  |
| 61005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/365:0:0" width="20" height="20" align="absmiddle" alt="เพนเนเทรท"> เพนเนเทรท | 10 | 💥 AoE |  |
| 61006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/364:0:0" width="20" height="20" align="absmiddle" alt="ไลท์นิ่งเพน"> ไลท์นิ่งเพน | 10 | 🔒 CC |  |
| 61012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/369:0:0" width="20" height="20" align="absmiddle" alt="ดาร์กไลท์นิ่ง"> ดาร์กไลท์นิ่ง | 10 | 🔒 CC |  |
| 61013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/370:0:0" width="20" height="20" align="absmiddle" alt="ทูสออฟทูนดร้า"> ทูสออฟทูนดร้า | 5 | 🔒 CC |  |
| 61014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/371:0:0" width="20" height="20" align="absmiddle" alt="แฮนด์เพลค"> แฮนด์เพลค | 5 | 💥🔒 AoE+CC |  |
| 61015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/373:0:0" width="20" height="20" align="absmiddle" alt="บลาสท์ฮิล"> บลาสท์ฮิล | 5 | ⚔️ Attack |  |
| 61017 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/103:0:0" width="20" height="20" align="absmiddle" alt="อิโมเลชั่น"> อิโมเลชั่น | 5 | 💥 AoE |  |
| 61022 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/377:0:0" width="20" height="20" align="absmiddle" alt="เว็ปพอนเบรค"> เว็ปพอนเบรค | 10 | 💀 Debuff |  |
| 61023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/378:0:0" width="20" height="20" align="absmiddle" alt="อาร์เมอร์เบรค"> อาร์เมอร์เบรค | 10 | 💀 Debuff |  |
| 61024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/379:0:0" width="20" height="20" align="absmiddle" alt="มายด์เบรค"> มายด์เบรค | 10 | 💀 Debuff |  |
| 61025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/380:0:0" width="20" height="20" align="absmiddle" alt="ไนท์แมร์"> ไนท์แมร์ | 10 | 💥🔒 AoE+CC |  |
| 61029 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/384:0:0" width="20" height="20" align="absmiddle" alt="แบทเทิลฮิล"> แบทเทิลฮิล | 10 | 💀 Debuff |  |
| 60001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/267:0:0" width="20" height="20" align="absmiddle" alt="ดูอัลอันเดอร์"> ดูอัลอันเดอร์ | 10 | 🟢 Passive |  |
| 60003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/63:0:0" width="20" height="20" align="absmiddle" alt="เอวิลสปิริทชวล"> เอวิลสปิริทชวล | 10 | 🟢 Passive |  |
| 60004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/11:0:0" width="20" height="20" align="absmiddle" alt="อาเมอร์บาวู๊ด"> อาเมอร์บาวู๊ด | 10 | 🟢 Passive |  |
| 60005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/60:0:0" width="20" height="20" align="absmiddle" alt="เดโมนิกกิฟท์"> เดโมนิกกิฟท์ | 10 | 🟢 Passive |  |
| 61032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/360:0:0" width="20" height="20" align="absmiddle" alt="พรแห่งเบอร์เซ่"> พรแห่งเบอร์เซ่ | 3 | 🔄 Toggle |  |
| 61033 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/361:0:0" width="20" height="20" align="absmiddle" alt="พรแห่งรูเปีย"> พรแห่งรูเปีย | 3 | 🔄 Toggle |  |
| 61034 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/362:0:0" width="20" height="20" align="absmiddle" alt="พรแห่งฟาร์เซก้า"> พรแห่งฟาร์เซก้า | 3 | 🔄 Toggle |  |
| 61031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/386:0:0" width="20" height="20" align="absmiddle" alt="โซลชาร์จ"> โซลชาร์จ | 5 | 💥 AoE |  |
| 61030 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/385:0:0" width="20" height="20" align="absmiddle" alt="ฮีลลิ่งเซอร์เคิล"> ฮีลลิ่งเซอร์เคิล | 3 | 💥🔒 AoE+CC |  |
| 61028 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/383:0:0" width="20" height="20" align="absmiddle" alt="เอวิลแอดไวเซอร์"> เอวิลแอดไวเซอร์ | 3 | 💥 AoE |  |
| 61027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/382:0:0" width="20" height="20" align="absmiddle" alt="คาโอติกอาร์มี่"> คาโอติกอาร์มี่ | 3 | 💥 AoE |  |
| 61026 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/381:0:0" width="20" height="20" align="absmiddle" alt="บลัดรัสท์"> บลัดรัสท์ | 3 | 💥 AoE |  |
| 60006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/40:0:0" width="20" height="20" align="absmiddle" alt="พินพอยท์"> พินพอยท์ | 5 | 🟢 Passive |  |

---

#### 4331 เอ็กซ์เพิร์ท (C3)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 61001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/363:0:0" width="20" height="20" align="absmiddle" alt="อินเกจ"> อินเกจ | 15 | ⚔️ Attack |  |
| 61002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/28:0:0" width="20" height="20" align="absmiddle" alt="ดับเบิ้ลอิมแพค"> ดับเบิ้ลอิมแพค | 15 | 💀 Debuff |  |
| 61003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/105:0:0" width="20" height="20" align="absmiddle" alt="โซลดิไวเดอร์"> โซลดิไวเดอร์ | 15 | 💀 Debuff |  |
| 61004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/82:0:0" width="20" height="20" align="absmiddle" alt="อิโวนี่แดนซ์เซอร์"> อิโวนี่แดนซ์เซอร์ | 15 | 💥 AoE |  |
| 61005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/365:0:0" width="20" height="20" align="absmiddle" alt="เพนเนเทรท"> เพนเนเทรท | 15 | 💥 AoE |  |
| 61006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/364:0:0" width="20" height="20" align="absmiddle" alt="ไลท์นิ่งเพน"> ไลท์นิ่งเพน | 15 | 🔒 CC |  |
| 61012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/369:0:0" width="20" height="20" align="absmiddle" alt="ดาร์กไลท์นิ่ง"> ดาร์กไลท์นิ่ง | 20 | 🔒 CC |  |
| 61013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/370:0:0" width="20" height="20" align="absmiddle" alt="ทูสออฟทูนดร้า"> ทูสออฟทูนดร้า | 10 | 🔒 CC |  |
| 61014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/371:0:0" width="20" height="20" align="absmiddle" alt="แฮนด์เพลค"> แฮนด์เพลค | 10 | 💥🔒 AoE+CC |  |
| 61015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/373:0:0" width="20" height="20" align="absmiddle" alt="บลาสท์ฮิล"> บลาสท์ฮิล | 10 | ⚔️ Attack |  |
| 61017 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/103:0:0" width="20" height="20" align="absmiddle" alt="อิโมเลชั่น"> อิโมเลชั่น | 10 | 💥 AoE |  |
| 61022 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/377:0:0" width="20" height="20" align="absmiddle" alt="เว็ปพอนเบรค"> เว็ปพอนเบรค | 15 | 💀 Debuff |  |
| 61023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/378:0:0" width="20" height="20" align="absmiddle" alt="อาร์เมอร์เบรค"> อาร์เมอร์เบรค | 15 | 💀 Debuff |  |
| 61024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/379:0:0" width="20" height="20" align="absmiddle" alt="มายด์เบรค"> มายด์เบรค | 15 | 💀 Debuff |  |
| 61025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/380:0:0" width="20" height="20" align="absmiddle" alt="ไนท์แมร์"> ไนท์แมร์ | 15 | 💥🔒 AoE+CC |  |
| 61029 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/384:0:0" width="20" height="20" align="absmiddle" alt="แบทเทิลฮิล"> แบทเทิลฮิล | 15 | 💀 Debuff |  |
| 60001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/267:0:0" width="20" height="20" align="absmiddle" alt="ดูอัลอันเดอร์"> ดูอัลอันเดอร์ | 15 | 🟢 Passive |  |
| 60003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/63:0:0" width="20" height="20" align="absmiddle" alt="เอวิลสปิริทชวล"> เอวิลสปิริทชวล | 15 | 🟢 Passive |  |
| 60004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/11:0:0" width="20" height="20" align="absmiddle" alt="อาเมอร์บาวู๊ด"> อาเมอร์บาวู๊ด | 15 | 🟢 Passive |  |
| 60005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/60:0:0" width="20" height="20" align="absmiddle" alt="เดโมนิกกิฟท์"> เดโมนิกกิฟท์ | 15 | 🟢 Passive |  |
| 61032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/360:0:0" width="20" height="20" align="absmiddle" alt="พรแห่งเบอร์เซ่"> พรแห่งเบอร์เซ่ | 5 | 🔄 Toggle |  |
| 61033 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/361:0:0" width="20" height="20" align="absmiddle" alt="พรแห่งรูเปีย"> พรแห่งรูเปีย | 5 | 🔄 Toggle |  |
| 61034 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/362:0:0" width="20" height="20" align="absmiddle" alt="พรแห่งฟาร์เซก้า"> พรแห่งฟาร์เซก้า | 5 | 🔄 Toggle |  |
| 61031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/386:0:0" width="20" height="20" align="absmiddle" alt="โซลชาร์จ"> โซลชาร์จ | 10 | 💥 AoE |  |
| 61030 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/385:0:0" width="20" height="20" align="absmiddle" alt="ฮีลลิ่งเซอร์เคิล"> ฮีลลิ่งเซอร์เคิล | 5 | 💥🔒 AoE+CC |  |
| 61028 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/383:0:0" width="20" height="20" align="absmiddle" alt="เอวิลแอดไวเซอร์"> เอวิลแอดไวเซอร์ | 5 | 💥 AoE |  |
| 61027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/382:0:0" width="20" height="20" align="absmiddle" alt="คาโอติกอาร์มี่"> คาโอติกอาร์มี่ | 5 | 💥 AoE |  |
| 61026 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/381:0:0" width="20" height="20" align="absmiddle" alt="บลัดรัสท์"> บลัดรัสท์ | 5 | 💥 AoE |  |
| 60006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/40:0:0" width="20" height="20" align="absmiddle" alt="พินพอยท์"> พินพอยท์ | 10 | 🟢 Passive |  |
| 61018 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/376:0:0" width="20" height="20" align="absmiddle" alt="ดิสอินทิเกรท"> ดิสอินทิเกรท | 10 | 🔒 CC |  |
| 61016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/372:0:0" width="20" height="20" align="absmiddle" alt="เด๊ทอาย"> เด๊ทอาย | 5 | ⚔️ Attack |  |
| 61009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/366:0:0" width="20" height="20" align="absmiddle" alt="เคอร์สเนล"> เคอร์สเนล | 5 | 🔒 CC |  |
| 61008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/97:0:0" width="20" height="20" align="absmiddle" alt="เจโนไซด์"> เจโนไซด์ | 5 | ⚔️ Attack |  |
| 61007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/367:0:0" width="20" height="20" align="absmiddle" alt="เบลดสตอร์ม"> เบลดสตอร์ม | 5 | ⚔️ Attack |  |
| 61020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/88:0:0" width="20" height="20" align="absmiddle" alt="เอวิลเทมเพสท์"> เอวิลเทมเพสท์ | 10 | 💀 Debuff |  |
| 61021 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/374:0:0" width="20" height="20" align="absmiddle" alt="เอนเนอร์จี้บลาสท์"> เอนเนอร์จี้บลาสท์ | 10 | ⚔️ Attack |  |

---

#### 4341 มาสเตอร์ (C4)

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 61001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/363:0:0" width="20" height="20" align="absmiddle" alt="อินเกจ"> อินเกจ | 20 | ⚔️ Attack |  |
| 61002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/28:0:0" width="20" height="20" align="absmiddle" alt="ดับเบิ้ลอิมแพค"> ดับเบิ้ลอิมแพค | 20 | 💀 Debuff |  |
| 61003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/105:0:0" width="20" height="20" align="absmiddle" alt="โซลดิไวเดอร์"> โซลดิไวเดอร์ | 20 | 💀 Debuff |  |
| 61004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/82:0:0" width="20" height="20" align="absmiddle" alt="อิโวนี่แดนซ์เซอร์"> อิโวนี่แดนซ์เซอร์ | 20 | 💥 AoE |  |
| 61005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/365:0:0" width="20" height="20" align="absmiddle" alt="เพนเนเทรท"> เพนเนเทรท | 20 | 💥 AoE |  |
| 61006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/364:0:0" width="20" height="20" align="absmiddle" alt="ไลท์นิ่งเพน"> ไลท์นิ่งเพน | 20 | 🔒 CC |  |
| 61012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/369:0:0" width="20" height="20" align="absmiddle" alt="ดาร์กไลท์นิ่ง"> ดาร์กไลท์นิ่ง | 20 | 🔒 CC |  |
| 61013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/370:0:0" width="20" height="20" align="absmiddle" alt="ทูสออฟทูนดร้า"> ทูสออฟทูนดร้า | 20 | 🔒 CC |  |
| 61014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/371:0:0" width="20" height="20" align="absmiddle" alt="แฮนด์เพลค"> แฮนด์เพลค | 20 | 💥🔒 AoE+CC |  |
| 61015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/373:0:0" width="20" height="20" align="absmiddle" alt="บลาสท์ฮิล"> บลาสท์ฮิล | 15 | ⚔️ Attack |  |
| 61017 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/103:0:0" width="20" height="20" align="absmiddle" alt="อิโมเลชั่น"> อิโมเลชั่น | 20 | 💥 AoE |  |
| 61022 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/377:0:0" width="20" height="20" align="absmiddle" alt="เว็ปพอนเบรค"> เว็ปพอนเบรค | 20 | 💀 Debuff |  |
| 61023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/378:0:0" width="20" height="20" align="absmiddle" alt="อาร์เมอร์เบรค"> อาร์เมอร์เบรค | 20 | 💀 Debuff |  |
| 61024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/379:0:0" width="20" height="20" align="absmiddle" alt="มายด์เบรค"> มายด์เบรค | 20 | 💀 Debuff |  |
| 61025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/380:0:0" width="20" height="20" align="absmiddle" alt="ไนท์แมร์"> ไนท์แมร์ | 20 | 💥🔒 AoE+CC |  |
| 61029 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/384:0:0" width="20" height="20" align="absmiddle" alt="แบทเทิลฮิล"> แบทเทิลฮิล | 20 | 💀 Debuff |  |
| 60001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/267:0:0" width="20" height="20" align="absmiddle" alt="ดูอัลอันเดอร์"> ดูอัลอันเดอร์ | 20 | 🟢 Passive |  |
| 60003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/63:0:0" width="20" height="20" align="absmiddle" alt="เอวิลสปิริทชวล"> เอวิลสปิริทชวล | 20 | 🟢 Passive |  |
| 60004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/11:0:0" width="20" height="20" align="absmiddle" alt="อาเมอร์บาวู๊ด"> อาเมอร์บาวู๊ด | 20 | 🟢 Passive |  |
| 60005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/60:0:0" width="20" height="20" align="absmiddle" alt="เดโมนิกกิฟท์"> เดโมนิกกิฟท์ | 20 | 🟢 Passive |  |
| 61032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/360:0:0" width="20" height="20" align="absmiddle" alt="พรแห่งเบอร์เซ่"> พรแห่งเบอร์เซ่ | 7 | 🔄 Toggle |  |
| 61033 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/361:0:0" width="20" height="20" align="absmiddle" alt="พรแห่งรูเปีย"> พรแห่งรูเปีย | 7 | 🔄 Toggle |  |
| 61034 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/362:0:0" width="20" height="20" align="absmiddle" alt="พรแห่งฟาร์เซก้า"> พรแห่งฟาร์เซก้า | 7 | 🔄 Toggle |  |
| 61031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/386:0:0" width="20" height="20" align="absmiddle" alt="โซลชาร์จ"> โซลชาร์จ | 15 | 💥 AoE |  |
| 61030 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/385:0:0" width="20" height="20" align="absmiddle" alt="ฮีลลิ่งเซอร์เคิล"> ฮีลลิ่งเซอร์เคิล | 7 | 💥🔒 AoE+CC |  |
| 61028 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/383:0:0" width="20" height="20" align="absmiddle" alt="เอวิลแอดไวเซอร์"> เอวิลแอดไวเซอร์ | 7 | 💥 AoE |  |
| 61027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/382:0:0" width="20" height="20" align="absmiddle" alt="คาโอติกอาร์มี่"> คาโอติกอาร์มี่ | 7 | 💥 AoE |  |
| 61026 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/381:0:0" width="20" height="20" align="absmiddle" alt="บลัดรัสท์"> บลัดรัสท์ | 7 | 💥 AoE |  |
| 61018 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/376:0:0" width="20" height="20" align="absmiddle" alt="ดิสอินทิเกรท"> ดิสอินทิเกรท | 20 | 🔒 CC |  |
| 61016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/372:0:0" width="20" height="20" align="absmiddle" alt="เด๊ทอาย"> เด๊ทอาย | 15 | ⚔️ Attack |  |
| 61009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/366:0:0" width="20" height="20" align="absmiddle" alt="เคอร์สเนล"> เคอร์สเนล | 15 | 🔒 CC |  |
| 61008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/97:0:0" width="20" height="20" align="absmiddle" alt="เจโนไซด์"> เจโนไซด์ | 15 | ⚔️ Attack |  |
| 61007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/367:0:0" width="20" height="20" align="absmiddle" alt="เบลดสตอร์ม"> เบลดสตอร์ม | 15 | ⚔️ Attack |  |
| 61020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/88:0:0" width="20" height="20" align="absmiddle" alt="เอวิลเทมเพสท์"> เอวิลเทมเพสท์ | 15 | 💀 Debuff |  |
| 61021 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/374:0:0" width="20" height="20" align="absmiddle" alt="เอนเนอร์จี้บลาสท์"> เอนเนอร์จี้บลาสท์ | 20 | ⚔️ Attack |  |
| 61011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/368:0:0" width="20" height="20" align="absmiddle" alt="เทอร์มิเนชั่น"> เทอร์มิเนชั่น | 10 | 💥 AoE |  |
| 61010 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/387:0:0" width="20" height="20" align="absmiddle" alt="มูนแสลชเชอร์"> มูนแสลชเชอร์ | 10 | ⚔️ Attack |  |
| 61019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/375:0:0" width="20" height="20" align="absmiddle" alt="ดิสแทรคชั่น"> ดิสแทรคชั่น | 10 | 💥 AoE |  |

---

#### 4351 อะบิสลอร์ด (C5)

> 🟡 **Overall: 85.3**/100 · DMG `100` · AoE `100` · CC `100` · Util `68` · Surv `56`

| Skill ID | ชื่อสกิล | Max Lv | ประเภท | คำแนะนำ |
|----------|---------|--------|--------|----------|
| 61001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/363:0:0" width="20" height="20" align="absmiddle" alt="อินเกจ"> อินเกจ | 25 | ⚔️ Attack |  |
| 61002 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/28:0:0" width="20" height="20" align="absmiddle" alt="ดับเบิ้ลอิมแพค"> ดับเบิ้ลอิมแพค | 25 | 💀 Debuff |  |
| 61003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/105:0:0" width="20" height="20" align="absmiddle" alt="โซลดิไวเดอร์"> โซลดิไวเดอร์ | 25 | 💀 Debuff |  |
| 61004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/82:0:0" width="20" height="20" align="absmiddle" alt="อิโวนี่แดนซ์เซอร์"> อิโวนี่แดนซ์เซอร์ | 25 | 💥 AoE |  |
| 61005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/365:0:0" width="20" height="20" align="absmiddle" alt="เพนเนเทรท"> เพนเนเทรท | 25 | 💥 AoE |  |
| 61006 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/364:0:0" width="20" height="20" align="absmiddle" alt="ไลท์นิ่งเพน"> ไลท์นิ่งเพน | 25 | 🔒 CC |  |
| 61012 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/369:0:0" width="20" height="20" align="absmiddle" alt="ดาร์กไลท์นิ่ง"> ดาร์กไลท์นิ่ง | 25 | 🔒 CC |  |
| 61013 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/370:0:0" width="20" height="20" align="absmiddle" alt="ทูสออฟทูนดร้า"> ทูสออฟทูนดร้า | 20 | 🔒 CC |  |
| 61014 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/371:0:0" width="20" height="20" align="absmiddle" alt="แฮนด์เพลค"> แฮนด์เพลค | 25 | 💥🔒 AoE+CC |  |
| 61015 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/373:0:0" width="20" height="20" align="absmiddle" alt="บลาสท์ฮิล"> บลาสท์ฮิล | 20 | ⚔️ Attack |  |
| 61017 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/103:0:0" width="20" height="20" align="absmiddle" alt="อิโมเลชั่น"> อิโมเลชั่น | 25 | 💥 AoE |  |
| 61022 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/377:0:0" width="20" height="20" align="absmiddle" alt="เว็ปพอนเบรค"> เว็ปพอนเบรค | 20 | 💀 Debuff |  |
| 61023 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/378:0:0" width="20" height="20" align="absmiddle" alt="อาร์เมอร์เบรค"> อาร์เมอร์เบรค | 20 | 💀 Debuff |  |
| 61024 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/379:0:0" width="20" height="20" align="absmiddle" alt="มายด์เบรค"> มายด์เบรค | 20 | 💀 Debuff |  |
| 61025 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/380:0:0" width="20" height="20" align="absmiddle" alt="ไนท์แมร์"> ไนท์แมร์ | 20 | 💥🔒 AoE+CC |  |
| 61029 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/384:0:0" width="20" height="20" align="absmiddle" alt="แบทเทิลฮิล"> แบทเทิลฮิล | 20 | 💀 Debuff |  |
| 60001 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/267:0:0" width="20" height="20" align="absmiddle" alt="ดูอัลอันเดอร์"> ดูอัลอันเดอร์ | 20 | 🟢 Passive |  |
| 60003 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/63:0:0" width="20" height="20" align="absmiddle" alt="เอวิลสปิริทชวล"> เอวิลสปิริทชวล | 20 | 🟢 Passive |  |
| 60004 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/11:0:0" width="20" height="20" align="absmiddle" alt="อาเมอร์บาวู๊ด"> อาเมอร์บาวู๊ด | 20 | 🟢 Passive |  |
| 60005 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/60:0:0" width="20" height="20" align="absmiddle" alt="เดโมนิกกิฟท์"> เดโมนิกกิฟท์ | 20 | 🟢 Passive |  |
| 61032 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/360:0:0" width="20" height="20" align="absmiddle" alt="พรแห่งเบอร์เซ่"> พรแห่งเบอร์เซ่ | 10 | 🔄 Toggle |  |
| 61033 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/361:0:0" width="20" height="20" align="absmiddle" alt="พรแห่งรูเปีย"> พรแห่งรูเปีย | 10 | 🔄 Toggle |  |
| 61034 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/362:0:0" width="20" height="20" align="absmiddle" alt="พรแห่งฟาร์เซก้า"> พรแห่งฟาร์เซก้า | 10 | 🔄 Toggle |  |
| 61031 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/386:0:0" width="20" height="20" align="absmiddle" alt="โซลชาร์จ"> โซลชาร์จ | 20 | 💥 AoE | ⚠️ DPS ต่ำ (17) |
| 61030 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/385:0:0" width="20" height="20" align="absmiddle" alt="ฮีลลิ่งเซอร์เคิล"> ฮีลลิ่งเซอร์เคิล | 10 | 💥🔒 AoE+CC |  |
| 61028 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/383:0:0" width="20" height="20" align="absmiddle" alt="เอวิลแอดไวเซอร์"> เอวิลแอดไวเซอร์ | 10 | 💥 AoE |  |
| 61027 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/382:0:0" width="20" height="20" align="absmiddle" alt="คาโอติกอาร์มี่"> คาโอติกอาร์มี่ | 10 | 💥 AoE |  |
| 61026 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/381:0:0" width="20" height="20" align="absmiddle" alt="บลัดรัสท์"> บลัดรัสท์ | 10 | 💥 AoE |  |
| 61018 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/376:0:0" width="20" height="20" align="absmiddle" alt="ดิสอินทิเกรท"> ดิสอินทิเกรท | 20 | 🔒 CC |  |
| 61016 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/372:0:0" width="20" height="20" align="absmiddle" alt="เด๊ทอาย"> เด๊ทอาย | 20 | ⚔️ Attack |  |
| 61009 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/366:0:0" width="20" height="20" align="absmiddle" alt="เคอร์สเนล"> เคอร์สเนล | 20 | 🔒 CC |  |
| 61008 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/97:0:0" width="20" height="20" align="absmiddle" alt="เจโนไซด์"> เจโนไซด์ | 20 | ⚔️ Attack |  |
| 61007 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/367:0:0" width="20" height="20" align="absmiddle" alt="เบลดสตอร์ม"> เบลดสตอร์ม | 20 | ⚔️ Attack |  |
| 61020 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/88:0:0" width="20" height="20" align="absmiddle" alt="เอวิลเทมเพสท์"> เอวิลเทมเพสท์ | 25 | 💀 Debuff |  |
| 61021 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/374:0:0" width="20" height="20" align="absmiddle" alt="เอนเนอร์จี้บลาสท์"> เอนเนอร์จี้บลาสท์ | 20 | ⚔️ Attack |  |
| 61011 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/368:0:0" width="20" height="20" align="absmiddle" alt="เทอร์มิเนชั่น"> เทอร์มิเนชั่น | 15 | 💥 AoE |  |
| 61010 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/387:0:0" width="20" height="20" align="absmiddle" alt="มูนแสลชเชอร์"> มูนแสลชเชอร์ | 15 | ⚔️ Attack |  |
| 61019 | <img src="https://cdn.lunaonline.asia/img/2d/skill/imageidx/375:0:0" width="20" height="20" align="absmiddle" alt="ดิสแทรคชั่น"> ดิสแทรคชั่น | 15 | 💥 AoE |  |

<details><summary>⚠️ <strong>คำแนะนำการปรับสมดุล (2 รายการ)</strong></summary>

| # | ประเภท | มิติ | รายละเอียด | ไฟล์ที่แก้ | Gap |
|---|--------|------|----------|------------|-----|
| 1 | 🔧 ปรับ | Survivability | 🛡️ ปรับค่า fStatusDataMul สกิลบัฟ/ฮีล (×1.3-1.5) | `Skill_Buff_List.bin.txt` | 9.0 |
| 2 | 🔧 ปรับ | Utility | ✨ ปรับค่า fStatusDataMul สกิลบัฟ (×1.3-1.5) | `Skill_Buff_List.bin.txt` | 7.0 |

</details>

---

## 📊 สรุปภาพรวม

| รายการ | ค่า |
|---------|-----|
| อาชีพทั้งหมด | 97 |
| สกิลรวม (Skill_Get_List) | 1771 |
| C5 Jobs ที่วิเคราะห์แล้ว | 32 |
| ข้อแนะนำทั้งหมด | 50 |
| ไฟล์ต้นฉบับ | `Skill_Get_List.bin.txt` |

---

📌 **Luna Plus ASIA** | Patch v2.0.0 ― Skill Analysis v2.9.0 | Generated: 2026-02-14 21:53:57
