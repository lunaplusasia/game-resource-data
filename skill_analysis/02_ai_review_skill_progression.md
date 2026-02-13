# 🤖 AI Analysis: Progression System

> 📊 วิเคราะห์จาก: progression_compact.txt | 27 C5 Jobs | Generated: 2026-02-14
> 🤖 Reviewed by: GitHub Copilot (Claude Opus 4.6)

---

## 1. 🌳 Progression Path Mapping

### ภาพรวมโครงสร้างสายอาชีพทั้งหมด

ระบบอาชีพของ LUNA2 แบ่งออกเป็น **4 สายหลัก** (Class Path) โดยแต่ละสายมีจุดแยกสาขา (Branch Point) ที่ **C2** ซึ่งกำหนดทิศทางการเติบโตไปจนถึง C5

### 🔴 Fighter Path (10 C5 Jobs)

```
                                    ┌─ Paladin (19) ─────── Tank/Support
                        ┌─ Phalanx ─┤
                        │   (23)    ├─ Panzer (18) ──────── Heavy Tank
                        │           └─ Crusader (18) ────── Holy DPS
            ┌─ InfantryMan ─┘
            │     (13)
  ┌─ Guard ─┤                       ┌─ Sword Master (23) ── H: Melee DPS
  │   (10)  └─ SwordMan ── Knight ──┤
  │              (15)       (19)    └─ Magners (23) ──────── E: Magic Knight
  │
Fighter (16)
  │
  │                                  ┌─ Destroyer (23) ───── H: Berserker
  └─ Warrior ── Mercenary ─┬─ Gladiator ─┘
      (10)       (13)      │   (15)
                           │
                           └─ Runic Knight ── Magners (20) ── E: Runic DPS
                                 (24)
```

**จุดแยกสำคัญที่ C2:**
- **Guard** → สาย Tank/Knight (6 อาชีพปลายทาง) — สกิลสะสมมากกว่า
- **Warrior** → สาย DPS/Berserker (2 อาชีพปลายทาง) — สกิลสะสมน้อยกว่า

### 🟢 Rogue Path (8 C5 Jobs)

```
                                     ┌─ Sniper (18) ──────── Ranged DPS
                         ┌─ Ranger ──┤
                         │   (14)    ├─ Entrapper (22) ───── Trap/CC
            ┌─ Archer ───┤           └─ Arc Ranger (16) ──── Hybrid
            │   (11)     │
  ┌─ Voyager ─┤          │
  │    (9)    └─ Scout ── Runic Worker ── Temper Master (32) ── E: Crafter
  │              (14)       (18)
  │
Rogue (16)
  │
  └─ Ruffian ── Chief ── Assassin ── Blade Taker (20) ── H: Assassin
      (10)       (12)      (16)
```

**จุดแยกสำคัญที่ C2:**
- **Voyager** → สายธนูและสนับสนุน (6 อาชีพปลายทาง) — หลากหลายมากที่สุด
- **Ruffian** → สายมีดสั้น/ลอบเร้น (1 อาชีพปลายทาง) — เฉพาะ Human เท่านั้น

### 🔵 Mage Path (8 C5 Jobs)

```
                                      ┌─ Cardinal (33) ────── Healer
                          ┌─ Bishop ──┤
                          │   (22)    └─ Soul Arbiter (27) ── Dark Mage
             ┌─ Priest ───┤
             │   (20)     └─ Elemental Master ── Runic Master (25) ── E: Elemental
  ┌─ Cleric ─┤                   (22)
  │   (11)   │
  │          └─ Monk ── Inquirer ── Necromancer (18) ── H: Summoner
  │              (12)     (19)
  │
Mage (14)
  │
  └─ Wizard ── Sorcerer ── Warlock ── Grand Master (14) ── Pure DPS
      (12)       (15)       (20)
```

**จุดแยกสำคัญที่ C2:**
- **Cleric** → สาย Heal/Support/Dark (7 อาชีพปลายทาง) — ครอบคลุมบทบาทมากที่สุด
- **Wizard** → สาย DPS ล้วน (1 อาชีพปลายทาง) — เส้นทางเดียว

### 👿 Devil Path (1 C5 Job)

```
Apprentice (36) ── Combatant (0) ── Expert (0) ── Master (0) ── Abyss Lord (0)
    ▲
    │
    └── สกิลทั้งหมด 36 ตัวได้ที่ C1 ไม่มีสกิลเพิ่มเมื่อเลื่อนอาชีพ!
```

**ลักษณะพิเศษ:** Devil ได้สกิลทุกตัวตั้งแต่ C1 — การเลื่อนอาชีพเป็นเพียงพิธีการ (Ceremonial Advancement)

---

## 2. 📊 Skill Accumulation Analysis

### ตารางสรุปสกิลสะสมรวมทุกอาชีพ C5

| อันดับ | อาชีพ C5 | สายหลัก | สกิลสะสมรวม | สกิล C5 | เส้นทาง |
|:------:|----------|---------|:-----------:|:-------:|---------|
| 🥇 1 | Soul Arbiter | Mage | **54** | 27 | Cleric→Priest→Bishop |
| 2 | Panzer | Fighter | **50** | 18 | Guard→InfantryMan→Phalanx |
| 3 | Necromancer | Mage | **48** | 18 | Cleric→Monk→Inquirer |
| 4 | Sword Master | Fighter | **47** | 23 | Guard→SwordMan→Knight |
| 5 | Runic Master | Mage | **47** | 25 | Cleric→Priest→Elemental Master |
| 6 | Crusader | Fighter | **46** | 18 | Guard→InfantryMan→Phalanx |
| 7 | Cardinal | Mage | **45** | 33 | Cleric→Priest→Bishop |
| 8 | Magners (Knight) | Fighter | **43** | 20 | Warrior→Mercenary→Runic Knight |
| 9 | Temper Master | Rogue | **40** | 32 | Voyager→Scout→Runic Worker |
| 10 | Entrapper | Rogue | **39** | 22 | Voyager→Archer→Ranger |
| 11 | Paladin | Fighter | **38** | 19 | Guard→InfantryMan→Phalanx |
| 12 | Grand Master | Mage | **36** | 14 | Wizard→Sorcerer→Warlock |
| 13 | Abyss Lord | Devil | **36** | 0 | ไม่มี (ได้ทั้งหมดที่ C1) |
| 14 | Sniper | Rogue | **35** | 18 | Voyager→Archer→Ranger |
| 15 | Destroyer | Fighter | **34** | 23 | Warrior→Mercenary→Gladiator |
| 16 | Blade Taker | Rogue | **30** | 20 | Ruffian→Chief→Assassin |
| 17 | Arc Ranger | Rogue | **26** | 16 | Voyager→Archer→Ranger |

### สรุปภาพรวมรายสายอาชีพ

| สายอาชีพ | จำนวน C5 | สกิลสะสมเฉลี่ย | ต่ำสุด | สูงสุด | ช่วงกว้าง |
|----------|:--------:|:--------------:|:------:|:------:|:---------:|
| ⚔️ Fighter | 10 | 43.9 | 34 (Destroyer) | 50 (Panzer) | 16 |
| 🏹 Rogue | 8 | 33.75 | 26 (Arc Ranger) | 40 (Temper Master) | 14 |
| 🔮 Mage | 8 | 45.625 | 36 (Grand Master) | 54 (Soul Arbiter) | 18 |
| 👿 Devil | 1 | 36.0 | 36 | 36 | 0 |

### 📌 ข้อสังเกตสำคัญ

- **Mage มีค่าเฉลี่ยสกิลสะสมสูงสุด** (45.6) — มากกว่า Fighter ถึง 1.7 สกิลโดยเฉลี่ย
- **Rogue มีค่าเฉลี่ยต่ำสุด** (33.75) — น้อยกว่า Mage ถึง ~12 สกิล
- **ช่วงกว้าง (Range) ของ Mage สูงสุด** = 18 — แสดงว่าสายนี้มีความหลากหลายในจำนวนสกิลมากที่สุด
- **Devil ไม่มีช่วงกว้าง** เพราะมีเพียง 1 อาชีพปลายทาง

---

## 3. ⚡ Power Spike Analysis

### รูปแบบการเพิ่มพลัง (Growth Pattern) แต่ละ Tier

การวิเคราะห์ว่าสกิลใหม่เพิ่มขึ้นมากที่สุดใน Tier ไหน:

| รูปแบบ | คำอธิบาย | อาชีพตัวอย่าง |
|--------|----------|--------------|
| 🔥 **Late Peak (C5)** | พลังสูงสุดที่ C5 | Destroyer(23), Cardinal(33), Temper Master(32) |
| ⚡ **Late Peak (C4)** | พลังสูงสุดที่ C4 แล้วลดลง | Grand Master, Phalanx-branch(23 ที่ C4) |
| 🌱 **Early Peak (C1)** | เริ่มแรงแล้วค่อยๆ เพิ่ม | Arc Ranger, Devil (Abyss Lord) |
| 📈 **Steady Growth** | เพิ่มสม่ำเสมอตลอด | Sniper, Blade Taker |

### กราฟการเติบโตของสกิล (C1→C5) — เปรียบเทียบแต่ละสาย

```
สกิลใหม่ต่อ Tier
35 ┤
   │                                              ██ Temper Master C5 (32)
30 ┤                              ██ Cardinal C5 (33)
   │
25 ┤              ██ Soul Arbiter C5 (27)
   │   ██ Runic Knight C4 (24)   ██ Runic Master C5 (25)
   │   ██ Phalanx C4 (23)        ██ Destroyer C5 (23)  ██ SM C5 (23)
20 ┤   ██ Priest C3 (20)         ██ Warlock C4 (20)    ██ Entrapper C5 (22)
   │   ██ Bishop C4 (22)         ██ Blade Taker C5 (20)
   │   ██ Knight C4 (19)         ██ Paladin C5 (19)    ██ Inquirer C4 (19)
   │   ██ Panzer/Crusader C5 (18)██ Necromancer C5 (18)██ Sniper C5 (18)
15 ┤   ██ SwordMan C3 (15)       ██ Gladiator C4 (15)  ██ Sorcerer C3 (15)
   │   ██ Fighter C1 (16)        ██ Rogue C1 (16)      ██ Arc Ranger C5 (16)
   │   ██ Mage C1 (14)           ██ Grand Master C5 (14)██ Scout C3 (14)
   │   ██ InfantryMan C3 (13)    ██ Mercenary C3 (13)
10 ┤   ██ Guard/Warrior C2 (10)  ██ Ruffian C2 (10)
   │   ██ Voyager C2 (9)         ██ Cleric C2 (11)     ██ Archer C3 (11)
   │
 0 ┤   ██ Combatant/Expert/Master/AbyssLord C2-C5 (0) ← Devil ไม่มีสกิลเพิ่ม!
   └─────────────────────────────────────────────────────────────────────
        C1          C2          C3          C4          C5
```

### 🏆 Top 5 Power Spike ที่ใหญ่ที่สุด (สกิลใหม่ต่อ Tier)

| อันดับ | อาชีพ | Tier | สกิลใหม่ | หมายเหตุ |
|:------:|--------|:----:|:--------:|----------|
| 🥇 | Apprentice (Devil) | C1 | **36** | สกิลทั้งหมดในทีเดียว |
| 🥈 | Cardinal | C5 | **33** | Healer สุดยอด — สกิลใหม่มากที่สุดใน C5 |
| 🥉 | Temper Master | C5 | **32** | Crafter ได้สกิลระเบิดที่ C5 |
| 4 | Soul Arbiter | C5 | **27** | Dark Mage ที่มีสกิลสะสมมากที่สุดในเกม |
| 5 | Runic Master | C5 | **25** | Elemental สาย Elf ที่ทรงพลัง |

### ⚠️ Power Spike ที่น่ากังวล

| ปัญหา | อาชีพ | รายละเอียด |
|--------|--------|-----------|
| **C5 อ่อนกว่า C4** | Grand Master | C4 Warlock ได้ 20 สกิล แต่ C5 Grand Master ได้แค่ **14** สกิล — ลดลง 30%! |
| **สกิลสะสมน้อยมาก** | Arc Ranger | รวมทุก Tier ได้แค่ **26** สกิล — น้อยที่สุดในทุกสาย |
| **ไม่มีการเติบโต** | Abyss Lord | สกิล 0 ตัวตั้งแต่ C2-C5 — ไม่มีความรู้สึกก้าวหน้า |

---

## 4. 🔗 Parent Job Influence

### การวิเคราะห์อิทธิพลของอาชีพแม่ต่ออาชีพลูก

**แนวคิด**: อาชีพที่ C2-C4 กำหนดว่าตัวละครจะมี "ฐานสกิล" แบบไหน — อาชีพแม่ที่ให้สกิลมากจะทำให้อาชีพลูกมีความหลากหลายในการเล่นสูงกว่า

### Fighter Branch Analysis

| อาชีพแม่ (C2) | สกิลที่ให้ | อาชีพลูก C5 | สกิลสะสมเฉลี่ย C5 |
|---------------|:----------:|-------------|:------------------:|
| **Guard** | 10 | Paladin, Panzer, Crusader, Sword Master, Magners(E) | **44.8** |
| **Warrior** | 10 | Destroyer, Magners(E via Runic Knight) | **38.5** |

> 📌 **สรุป**: สาย Guard ให้สกิลสะสมเฉลี่ยมากกว่า Warrior ถึง **6.3 สกิล** — เหตุผลหลักคือ InfantryMan→Phalanx ที่ C3-C4 ให้สกิลมากถึง 13+23 = 36 สกิล

### Rogue Branch Analysis

| อาชีพแม่ (C2) | สกิลที่ให้ | อาชีพลูก C5 | สกิลสะสมเฉลี่ย C5 |
|---------------|:----------:|-------------|:------------------:|
| **Voyager** | 9 | Sniper, Entrapper, Arc Ranger, Temper Master | **35.0** |
| **Ruffian** | 10 | Blade Taker | **30.0** |

> 📌 **สรุป**: แม้ Ruffian จะให้สกิลมากกว่า Voyager ที่ C2 (10 vs 9) แต่สาย Voyager มีสกิลสะสมเฉลี่ยสูงกว่า เพราะ C3-C5 ของ Voyager ให้สกิลรวมมากกว่าอย่างชัดเจน

### Mage Branch Analysis

| อาชีพแม่ (C2) | สกิลที่ให้ | อาชีพลูก C5 | สกิลสะสมเฉลี่ย C5 |
|---------------|:----------:|-------------|:------------------:|
| **Cleric** | 11 | Cardinal, Soul Arbiter, Necromancer, Runic Master | **48.5** |
| **Wizard** | 12 | Grand Master | **36.0** |

> 📌 **สรุป**: Cleric เป็น C2 ที่มีอิทธิพลสูงสุดในเกม — อาชีพลูกทุกตัวมีสกิลสะสมสูงกว่า 45 (ยกเว้น Necro ที่ 48) ขณะที่ Wizard ถึงแม้ให้สกิลเริ่มต้นมากกว่า (12 vs 11) แต่สาย Grand Master จบด้วยสกิลน้อยกว่ามาก

### 🏆 อาชีพแม่ (Parent Job) ที่ทรงอิทธิพลมากที่สุด

| อันดับ | อาชีพแม่ | Tier | สกิลสะสมเฉลี่ย C5 ของลูก | อาชีพลูก C5 |
|:------:|----------|:----:|:------------------------:|:-----------:|
| 🥇 | Cleric | C2 | **48.5** | 4 อาชีพ |
| 🥈 | Guard | C2 | **44.8** | 5 อาชีพ |
| 🥉 | Bishop | C4 | **49.5** | 2 อาชีพ (Cardinal, Soul Arbiter) |
| 4 | Phalanx | C4 | **44.7** | 3 อาชีพ (Paladin, Panzer, Crusader) |
| 5 | Voyager | C2 | **35.0** | 4 อาชีพ |

---

## 5. 📈 Tier Distribution Analysis

### จำนวนสกิลใหม่เฉลี่ยแยกตาม Tier

| Tier | Fighter | Rogue | Mage | Devil | ค่าเฉลี่ยรวม |
|:----:|:-------:|:-----:|:----:|:-----:|:------------:|
| C1 | 16.0 | 16.0 | 14.0 | 36.0 | **20.5** |
| C2 | 10.0 | 9.5 | 11.5 | 0.0 | **7.75** |
| C3 | 13.5 | 12.0 | 16.2 | 0.0 | **10.4** |
| C4 | 20.8 | 15.5 | 21.0 | 0.0 | **14.3** |
| C5 | 20.3 | 21.3 | 23.4 | 0.0 | **16.3** |

### กราฟแนวโน้ม: สกิลใหม่ต่อ Tier (เฉลี่ยรายสาย)

```
สกิลใหม่
36 ┤ ★ Devil C1 (36)
   │
24 ┤                                           ●─── Mage (23.4)
   │                                     ●────○ Fighter (20.3)
20 ┤                               ●────○     ○ Rogue (21.3)
   │                         ○────●
16 ┤ ●───────────────○       ○
   │ ○               ●────●
14 ┤ ●
   │
10 ┤       ●
   │       ○
 8 ┤
   │
 0 ┤ - - - - - ★ - - - ★ - - - ★ - - - ★ Devil (0 ตั้งแต่ C2)
   └──────┬──────┬──────┬──────┬──────┬──
         C1     C2     C3     C4     C5

● Fighter  ○ Rogue  ● Mage  ★ Devil
```

### สัดส่วนสกิลแบ่งตาม Tier (C1–C5)

**Fighter (ค่าเฉลี่ย 43.9 สกิลสะสม):**
```
C1 ████████████████░░░░░░░░░░░░░░░░░░░░░░░░░░ 36.4%
C2 ██████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ 22.8%
C3 █████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ 30.7%
C4 ████████████████████░░░░░░░░░░░░░░░░░░░░░░ 47.4%
C5 ████████████████████░░░░░░░░░░░░░░░░░░░░░░ 46.2%
```

**Rogue (ค่าเฉลี่ย 33.75 สกิลสะสม):**
```
C1 ████████████████░░░░░░░░░░░░░░░░░░░░░░░░░░ 47.4%
C2 █████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ 28.1%
C3 ████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ 35.6%
C4 ███████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░ 45.9%
C5 █████████████████████░░░░░░░░░░░░░░░░░░░░░ 63.1%
```

**Mage (ค่าเฉลี่ย 45.625 สกิลสะสม):**
```
C1 ██████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░ 30.7%
C2 ███████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ 25.2%
C3 ████████████████░░░░░░░░░░░░░░░░░░░░░░░░░░ 35.5%
C4 █████████████████████░░░░░░░░░░░░░░░░░░░░░ 46.0%
C5 ███████████████████████░░░░░░░░░░░░░░░░░░░ 51.3%
```

### 📌 ข้อสังเกตจาก Tier Distribution

1. **C2 เป็น Tier ที่ได้สกิลน้อยที่สุด** ทุกสาย (7-12 สกิล) — ช่วงเปลี่ยนผ่านที่ "แห้งแล้ง" ที่สุด
2. **C4-C5 เป็น Power Tier** — สกิลใหม่เฉลี่ย 14-23 ตัว คิดเป็น ~50% ของสกิลทั้งหมด
3. **Rogue มีสัดส่วน C5 สูงสุด** (63.1%) — หมายความว่า Rogue ต้อง "ทนเล่น" จนถึง C5 ถึงจะรู้สึกถึงพลัง
4. **Devil หักล้างทุกกฎ** — ได้ 100% ที่ C1 และ 0% หลังจากนั้น

---

## 6. 🎮 Leveling Recommendation

### คำแนะนำสำหรับผู้เล่นแต่ละสาย

### ⚔️ Fighter — คำแนะนำตามเป้าหมาย

| เป้าหมาย | อาชีพแนะนำ | เหตุผล |
|----------|-----------|--------|
| 🛡️ Tank สมบูรณ์แบบ | **Panzer** (50 สกิล) | สกิลสะสมมากที่สุดในสาย Fighter ผ่าน Phalanx ที่แข็งแกร่ง |
| ⚔️ DPS สูงสุด | **Sword Master** (47 สกิล) | สาย Knight ให้สกิลบุกมาก + C5 ได้ 23 สกิลใหม่ |
| 🔥 Burst DPS | **Destroyer** (34 สกิล) | แม้สกิลน้อยแต่ทรงพลัง — C5 ได้ 23 สกิลใหม่ทีเดียว |
| 🏰 Holy Knight | **Crusader** (46 สกิล) | สกิลมากพอสมควร ผสม Tank + Holy DPS |
| 🔮 Magic Knight | **Magners** (43-47 สกิล) | เฉพาะ Elf — สกิลผสมระหว่าง Physical/Magical |

**เส้นทางที่แนะนำ (Fighter):**
```
ผู้เล่นใหม่ ──→ Guard ──→ InfantryMan ──→ Phalanx ──→ Panzer/Crusader
                                                         (ปลอดภัย/สกิลเยอะ)

ผู้เล่นชำนาญ ──→ Guard ──→ SwordMan ──→ Knight ──→ Sword Master
                                                     (DPS สูง/ท้าทาย)

ผู้เล่นฮาร์ดคอร์ ──→ Warrior ──→ Mercenary ──→ Gladiator ──→ Destroyer
                                                               (สกิลน้อยแต่ดุ)
```

### 🏹 Rogue — คำแนะนำตามเป้าหมาย

| เป้าหมาย | อาชีพแนะนำ | เหตุผล |
|----------|-----------|--------|
| 🎯 Ranged DPS | **Sniper** (35 สกิล) | สกิลสมดุลดี เน้นยิงระยะไกล |
| 🪤 CC/Trap | **Entrapper** (39 สกิล) | สกิลมาก สร้างกับดักควบคุมศัตรู |
| 🔧 Crafter/Support | **Temper Master** (40 สกิล) | สกิลมากที่สุดในสาย Rogue แต่เฉพาะ Elf |
| 🗡️ Assassin | **Blade Taker** (30 สกิล) | สาย Ruffian เฉพาะ Human — สกิลน้อยแต่ร้ายกาจ |

> ⚠️ **คำเตือน**: หลีกเลี่ยง **Arc Ranger** หากต้องการสกิลหลากหลาย (มีแค่ 26 สกิล — น้อยที่สุดในทุกสาย!)

### 🔮 Mage — คำแนะนำตามเป้าหมาย

| เป้าหมาย | อาชีพแนะนำ | เหตุผล |
|----------|-----------|--------|
| 💚 Healer หลัก | **Cardinal** (45 สกิล) | C5 ได้ 33 สกิลใหม่ — มากที่สุดเป็นอันดับ 2 ในเกม |
| 💀 Dark Mage | **Soul Arbiter** (54 สกิล) | **สกิลสะสมมากที่สุดในเกมทั้งหมด!** |
| 💥 Pure DPS | **Grand Master** (36 สกิล) | สกิลน้อยแต่เน้น DPS ล้วน — แต่ระวัง C5 อ่อนกว่า C4! |
| ☠️ Summoner | **Necromancer** (48 สกิล) | สาย Monk เฉพาะ Human — สกิลเยอะ เรียก Undead |
| 🌊 Elemental | **Runic Master** (47 สกิล) | เฉพาะ Elf — สกิลธาตุหลากหลาย |

**เส้นทางที่แนะนำ (Mage):**
```
ผู้เล่นใหม่ ──→ Cleric ──→ Priest ──→ Bishop ──→ Cardinal
                                                   (Healer ที่ทุกปาร์ตี้ต้องการ!)

ผู้เล่น Endgame ──→ Cleric ──→ Priest ──→ Bishop ──→ Soul Arbiter
                                                       (สกิลมากที่สุดในเกม!)

ผู้เล่น Solo ──→ Wizard ──→ Sorcerer ──→ Warlock ──→ Grand Master
                                                       (DPS สูงแต่สกิลจำกัด)
```

### 👿 Devil — คำแนะนำ

| เป้าหมาย | อาชีพแนะนำ | เหตุผล |
|----------|-----------|--------|
| 🔥 ทุกอย่าง | **Abyss Lord** (36 สกิล) | มีทางเลือกเดียว — แต่ได้สกิลทั้งหมดตั้งแต่ต้น! |

> 💡 **จุดเด่นของ Devil**: ไม่ต้องรอ Power Spike — เล่นได้เต็มพลังตั้งแต่ C1 เหมาะสำหรับผู้เล่นที่ต้องการ "พร้อมรบ" ทันที

---

## 7. 🏅 Summary + Best Paths

### สรุปผลวิเคราะห์ระบบ Progression ทั้งหมด

#### 🔑 Key Findings

1. **ความไม่สมดุลระหว่างสาย**: Mage มีค่าเฉลี่ยสกิลสะสมสูงกว่า Rogue ถึง **~12 สกิล** (45.6 vs 33.75) — ความแตกต่างนี้อาจส่งผลต่อ balance ของเกม
2. **C2 เป็นจุดวิกฤต**: การเลือก C2 ผิดอาจทำให้เสียสกิลสะสมไปถึง **12-18 สกิล** เมื่อเทียบกับเส้นทางที่ดีที่สุด
3. **C5 ไม่ได้ดีเสมอไป**: Grand Master (C5) ได้สกิลน้อยกว่า Warlock (C4) — แสดงว่าบางอาชีพ C5 อาจไม่คุ้มค่าจากมุมมองสกิลใหม่
4. **Devil เป็นข้อยกเว้นทุกกฎ**: ไม่มีการเติบโตของสกิลเลยหลัง C1 — ออกแบบเป็น "Complete from Start"

#### 🏆 Best Paths — อาชีพ C5 ที่แนะนำที่สุดแยกตามเกณฑ์

| เกณฑ์ | อาชีพ | ค่า | หมายเหตุ |
|-------|--------|:---:|----------|
| 📊 สกิลสะสมมากที่สุด | **Soul Arbiter** | 54 | Mage → Cleric → Priest → Bishop → Soul Arbiter |
| 🚀 Power Spike สูงสุดที่ C5 | **Cardinal** | 33 | ระเบิดสกิลที่ C5 มากที่สุดใน 3 สายหลัก |
| ⚡ พร้อมรบเร็วที่สุด | **Abyss Lord** | 36 | ได้สกิลทั้งหมดที่ C1 ไม่ต้องรอ |
| ⚔️ Fighter ที่ดีที่สุด | **Panzer** | 50 | สกิลสะสมสูงสุดในสาย + Tank ที่แข็งแกร่ง |
| 🏹 Rogue ที่ดีที่สุด | **Temper Master** | 40 | สกิลมากที่สุดในสาย Rogue (เฉพาะ Elf) |
| 📈 เติบโตสม่ำเสมอที่สุด | **Sniper** | 35 | สกิลเพิ่มขึ้นอย่างสม่ำเสมอทุก Tier |

#### ⚠️ อาชีพที่ควรระวัง

| อาชีพ | ปัญหา | สกิลสะสม |
|--------|--------|:--------:|
| **Arc Ranger** | สกิลน้อยที่สุดในเกม (26) — C5 ได้แค่ 16 สกิลใหม่ | 26 |
| **Grand Master** | C5 ได้สกิลน้อยกว่า C4 (14 vs 20) — รู้สึก "ถดถอย" | 36 |
| **Destroyer** | สกิลสะสมน้อยที่สุดในสาย Fighter (34) — ต้องพึ่ง burst damage | 34 |

#### 📋 ตารางเปรียบเทียบ Branch ทั้งหมด

```
                    สกิลสะสมเฉลี่ย C5
                    ←── น้อย ─────────── มาก ──→
                    25   30   35   40   45   50   55
                    │    │    │    │    │    │    │
Guard Branch        │    │    │    │    ████████████│  44.8
Warrior Branch      │    │    │    █████│    │    │  38.5
Voyager Branch      │    │    ██████████│    │    │  35.0
Ruffian Branch      │    ████│    │    │    │    │  30.0
Cleric Branch       │    │    │    │    │    █████████  48.5
Wizard Branch       │    │    │████│    │    │    │  36.0
Devil (ไม่มี branch)│    │    │████│    │    │    │  36.0
```

### 🎯 คำแนะนำสุดท้าย

> **สำหรับผู้เล่นใหม่**: เลือกสาย **Cleric** (Mage) หรือ **Guard** (Fighter) — ทั้งสองสายให้สกิลสะสมมากและมีอาชีพปลายทางหลากหลาย
>
> **สำหรับผู้เล่นชำนาญ**: ลอง **Destroyer** หรือ **Blade Taker** — สกิลน้อยแต่ทรงพลังเมื่อใช้ให้เป็น
>
> **สำหรับผู้เล่นที่รีบ**: เลือก **Devil (Abyss Lord)** — พร้อมรบทันทีตั้งแต่ C1 ไม่ต้องรอ Power Spike

---

📌 Luna Plus ASIA | LUNA2 Skill Analysis v2.8.0
