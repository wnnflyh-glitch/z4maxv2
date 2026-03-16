# 🤸‍♂️ Skill System

## Overview

ระบบ Skill ของ Zone4 เป็นระบบ **Martial Art Skill Equipment System**\
ที่ให้ผู้เล่นสะสมสกิลและเลือก **ติดตั้งสกิลใน Slot ต่าง ๆ**

Skill จะถูกแบ่งตาม **ประเภทของท่าการโจมตี** เช่น

* Crush
* Hold
* Special
* Team Double
* Misc

ผู้เล่นสามารถ

* สะสม Skill
* Equip Skill
* Upgrade Skill

โดย Skill สามารถอัปเกรดได้ **0 → 10 Level**

***

## Skill Inventory System

จากภาพ UI

<figure><img src="../../.gitbook/assets/image (108).png" alt="" width="380"><figcaption></figcaption></figure>

ผู้เล่นมี **Skill Inventory**

```
Skill Quantity : 29
Enhanced Power : 0
```

#### Skill Quantity

จำนวนสกิลที่ผู้เล่นครอบครอง

#### Enhanced Power

ค่าพลังรวมจาก Skill Upgrade

***

## Skill Category System

ใน Zone4 Skill ถูกแบ่งตาม **ประเภทท่า**

| Category    | Description  |
| ----------- | ------------ |
| CRUSH       | ท่าโจมตีหลัก |
| HOLD        | ท่าจับ       |
| SPECIAL     | ท่าพิเศษ     |
| TEAM DOUBLE | ท่าร่วมทีม   |
| MISC        | ท่าพิเศษอื่น |

## Crush Skill System

CRUSH คือ

> ท่าโจมตีหลักของ Combo

<figure><img src="../../.gitbook/assets/image (110).png" alt=""><figcaption></figcaption></figure>

ตัวอย่างจากภาพ

* Strom Combo
* Whiplash Kick
* Double Spin Kick
* Swallow Mallet Elbow

***

#### CRUSH Mechanics

CRUSH skill ใช้สำหรับ

* Combo opener
* Combo chain
* Burst damage

***

## Hold Skill System

HOLD คือ

> ท่าจับ (Grab)

<figure><img src="../../.gitbook/assets/image (111).png" alt=""><figcaption></figcaption></figure>

ใช้เพื่อ

* Break defense
* Crowd control

***

#### Hold Mechanics

เมื่อ Hold สำเร็จ

ผู้เล่นสามารถ

* Throw
* Slam
* Follow up attack

***

## Special Skill System

SPECIAL คือ

> Ultimate move

<figure><img src="../../.gitbook/assets/image (112).png" alt=""><figcaption></figcaption></figure>

มีลักษณะ

| Attribute                         |
| --------------------------------- |
| Damage สูง                        |
| จำเป็นต้องใช้ Special Points (SP) |

***

## Team Double Skill

TEAM DOUBLE คือ

> Cooperative Skill

<figure><img src="../../.gitbook/assets/image (113).png" alt=""><figcaption></figcaption></figure>

ต้องใช้

* ผู้เล่น 2 คน
* ระยะใกล้

##

***

## Skill Equip System

ในหน้าขวาของ UI

```
Skills in Possession
```

<figure><img src="../../.gitbook/assets/image (114).png" alt=""><figcaption></figcaption></figure>

ผู้เล่นสามารถ

* Equip
* Unequip

Skill ได้

***

## Skill Upgrade System

ผู้เล่นสามารถ upgrade skill เพื่อเพิ่ม

* Damage

## Skill Damage Scaling

การ upgrade skill จะเพิ่ม

> **ประมาณ 4–5% ต่อระดับ**

***

### Skill Scaling Table

| Level | \[PvP Mode] | \[PvE Mode] |
| ----- | ----------- | ----------- |
| 0     | 0%          | 0%          |
| 1     | 1%          | 10%         |
| 2     | 2%          | 20%         |
| 3     | 3%          | 30%         |
| 4     | 5%          | 50%         |
| 5     | 7%          | 70%         |
| 6     | 9%          | 90%         |
| 7     | 14%         | 140%        |
| 8     | 20%         | 200%        |
| 9     | 27%         | 270%        |
| 10    | 35%         | 350%        |
