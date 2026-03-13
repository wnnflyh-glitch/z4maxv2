# Gang War Matching System

## Overview

ระบบ **Matching** ของ Gang War ใช้รูปแบบ **Single Elimination Tournament**

โดยเลือก **16 Gang ที่มี Club Silver Coin สูงสุด** เข้าร่วมการแข่งขัน และนำมาจัดอันดับ (Seeding) เพื่อจับคู่ต่อสู้ในรอบแรก

รูปแบบการแข่งขันคือ

```
16 Teams → 8 → 4 → 2 → Champion
```

***

## Seeding System (การจัดอันดับ)

หลังจากปิดการลงทะเบียน ระบบจะจัดอันดับ Gang ตามจำนวน

```
Club Silver Coins Registered
```

จากมาก → น้อย

ตัวอย่าง

<table><thead><tr><th width="105">Rank</th><th>Gang</th><th>Coin</th></tr></thead><tbody><tr><td>1</td><td>Gang 1</td><td>1200</td></tr><tr><td>2</td><td>Gang 2</td><td>750</td></tr><tr><td>3</td><td>Gang 3</td><td>500</td></tr><tr><td>4</td><td>Gang 4</td><td>400</td></tr><tr><td>5</td><td>...</td><td>300</td></tr><tr><td>...</td><td>...</td><td>...</td></tr><tr><td>16</td><td>Gang 16</td><td>100</td></tr></tbody></table>

## Bracket Matching Logic

ระบบใช้ **Seed vs Reverse Seed**

```
1 vs 16
2 vs 15
3 vs 14
4 vs 13
5 vs 12
6 vs 11
7 vs 10
8 vs 9
```

## Visual Bracket Model

```
          ┌─1──
      ┌───┤     ┤─── Winner
      │   └─16─
  ┌───┤
  │   │   ┌─8──
  │   └───┤     ┤─── Winner
  │       └─9──
──┤
  │       ┌─4──
  │   ┌───┤     ┤─── Winner
  │   │   └─13─
  └───┤
      │   ┌─5──
      └───┤     ┤─── Winner
          └─12─
          ┌─3──
      ┌───┤     ┤─── Winner
      │   └─14─
  ┌───┤
  │   │   ┌─6──
  │   └───┤     ┤─── Winner
  │       └─11─
──┤
  │       ┌─2──
  │   ┌───┤     ┤─── Winner
  │   │   └─15─
  └───┤
      │   ┌─7──
      └───┤     ┤─── Winner
          └─10─
          
```
