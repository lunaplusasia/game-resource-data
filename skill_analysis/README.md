# 📊 LUNA Skill Analysis

> **ระบบวิเคราะห์สกิลและความสมดุลอาชีพ — LUNA Plus ASIA**  
> Version 2.9.0 | Game Patch 2.0.0

---

## 🎯 ภาพรวม

ระบบนี้รวบรวมและวิเคราะห์ข้อมูลสกิลทุกอาชีพใน LUNA Online อย่างละเอียด
เพื่อให้ผู้เล่นเข้าใจระบบเกมและวางแผนตัวละครได้ดียิ่งขึ้น

### ครอบคลุมอะไรบ้าง?

| หมวด | เนื้อหา | จำนวน |
|------|---------|------:|
| ⚔️ **สกิลทุกอาชีพ** | ข้อมูลสกิลทุก Level — Power, Mana, Cooldown, AoE, Buff/Debuff | 95 หน้า |
| 🗡️ **Combat Analysis** | DPS Rotation, CC Chain, Matchup 1v1, Role Classification | 33 หน้า |
| 📈 **Simulation** | จำลอง DPS/HPS ด้วยสูตรจากเกมจริง — 3 ระดับเลเวล (75/105/150) | 31 หน้า |
| 🌳 **Progression** | เส้นทางพัฒนาสกิล C1→C5 — power spike ที่แต่ละ tier | 4 หน้า |
| 🤖 **AI Review** | วิเคราะห์เชิงลึกโดย AI — balance, combat, recommendations | 18 ไฟล์ |

---

## 📋 Consolidated Reports

รายงานสรุปภาพรวมทั้งระบบ:

| รายงาน | คำอธิบาย |
|--------|----------|
| [📊 สรุปรวม (Overview)](reports/report_overview.md) | ภาพรวมทุกสายอาชีพ + จุดเด่น/จุดด้อย |
| [🎯 คู่มือสายอาชีพ (Class Guide)](reports/report_class_guide.md) | แนะนำการจัดสเตตัส + สไตล์การเล่น |
| [⚖️ วิเคราะห์ Balance](reports/report_balance.md) | ความสมดุลระหว่าง 4 สาย + ข้อเสนอแนะ |
| [📜 Skill Get List](reports/report_skill_get_list.md) | สกิลที่ได้รับเมื่อเปลี่ยนอาชีพ |
| [⚔️ Combat Summary](reports/report_combat.md) | สรุป DPS/CC/Matchup ranking |

---

## 🤖 AI Reviews

วิเคราะห์เชิงลึกโดย AI — อ่านตามลำดับ 01→06 เพื่อความเข้าใจที่ดีที่สุด:

| # | หัวข้อ | เนื้อหาหลัก |
|---|--------|-------------|
| 01 | [claude](reviews/claude/01_ai_review_skill_inventory.md) / [gemini](reviews/gemini/01_ai_review_skill_inventory.md) / [gpt](reviews/gpt/01_ai_review_skill_inventory.md) | toolkit แต่ละอาชีพ, power, CD, CC |
| 02 | [claude](reviews/claude/02_ai_review_skill_progression.md) / [gemini](reviews/gemini/02_ai_review_skill_progression.md) / [gpt](reviews/gpt/02_ai_review_skill_progression.md) | เส้นทางพัฒนา, power spike, สกิลใหม่ |
| 03 | [claude](reviews/claude/03_ai_review_skill_combat.md) / [gemini](reviews/gemini/03_ai_review_skill_combat.md) / [gpt](reviews/gpt/03_ai_review_skill_combat.md) | DPS tier, burst damage, CC chain, matchup |
| 04 | [claude](reviews/claude/04_ai_review_skill_simulation.md) / [gemini](reviews/gemini/04_ai_review_skill_simulation.md) / [gpt](reviews/gpt/04_ai_review_skill_simulation.md) | DPS ranking จากสูตรจริง, burst, heal, mana |
| 05 | [claude](reviews/claude/05_ai_review_skill_balance.md) / [gemini](reviews/gemini/05_ai_review_skill_balance.md) / [gpt](reviews/gpt/05_ai_review_skill_balance.md) | ความสมดุล 7 มิติ, cross-path comparison |
| 06 | [claude](reviews/claude/06_ai_review_skill_overview.md) / [gemini](reviews/gemini/06_ai_review_skill_overview.md) / [gpt](reviews/gpt/06_ai_review_skill_overview.md) | ภาพรวม + คำแนะนำสำหรับผู้เล่น |

---

## ⚔️ สกิลแยกตามสาย

### ⚔️ Fighter (30 อาชีพ, 11 C5)

### 🗡️ Rogue (30 อาชีพ, 10 C5)

### 🔮 Mage (30 อาชีพ, 10 C5)

### 😈 Devil (5 อาชีพ, 1 C5)

---

## 📈 Simulation Highlights

จำลองด้วยสูตรจากซอร์สโค้ดจริง — 3 ระดับ gear:

| ระดับ | Level | สำหรับ |
|-------|------:|--------|
| 🟡 Mid-game | 75 | ผู้เล่นระดับกลาง |
| 🟠 End-game | 105 | ผู้เล่นระดับสูง |
| 🔴 Max-game | 150 | ผู้เล่น end-content |

ข้อมูล simulation ประกอบด้วย:
- **DPS** (Damage Per Second) — sustained damage
- **Burst** — damage สูงสุดใน 3 วินาที
- **HPS** (Heal Per Second) — สำหรับสาย healer
- **Mana Efficiency** — ประสิทธิภาพการใช้ mana

---

## 🗺️ Navigation

- [📊 ภาพรวมระบบ](overview.md)
- [⚖️ วิเคราะห์ Balance](balance.md)
- [📋 SUMMARY (สารบัญ)](SUMMARY.md)

---

> 📌 **Luna Plus ASIA** | Patch v2.0.0 ― Skill Analysis v2.9.0
