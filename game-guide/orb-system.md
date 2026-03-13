# ORB System

<figure><img src="../.gitbook/assets/image.png" alt="" width="563"><figcaption></figcaption></figure>

### Overview

**ORB System** เป็นระบบ **Enhancement / Socket System** ของเกม Zone4 ที่อนุญาตให้ผู้เล่นใส่ **ลูกแก้ว (ORB)** ลงในอุปกรณ์ของตัวละครเพื่อเพิ่ม **Stat Bonus**

คุณสมบัติหลักของระบบ

* ใส่ ORB ลงใน Costume
* มีระดับ ORB ตั้งแต่ **+1 ถึง +20**
* ORB สามารถ **Upgrade**
* เพิ่ม Stat ให้ตัวละคร

ระบบนี้เป็น **Core Progression System** ของเกม

## 2. Equipment Slot Structure

ชุดตัวละครสามารถติด ORB ได้ทั้งหมด

```
9 Slots
```

ตัวอย่าง Slot

| Slot   | Description |
| ------ | ----------- |
| Hair   | ทรงผม       |
| Face   | หน้า        |
| Top    | เสื้อ       |
| Bottom | กางเกง      |
| Shoes  | รองเท้า     |
| Gloves | ถุงมือ      |
| Back   | หลัง        |
| Hat    | หมวก        |
| Ring   | แหวน        |

## 3. ORB Levels

ORB มีระดับ

```
+1 → +20
```

ระดับยิ่งสูง

* Stat เพิ่มขึ้น
* ความหายากเพิ่มขึ้น
* มูลค่าเพิ่มขึ้น

***

## 4. ORB Types

ORB อาจมีหลายประเภท เช่น

| ORB Type    | Stat Effect     |
| ----------- | --------------- |
| Orange ORB  | Hit Attack      |
| Skyblue ORB | Grip Attack     |
| Green ORB   | Hit Defense     |
| Purple ORB  | Grip Defense    |
| Yellow ORB  | Critical        |
| Red ORB     | HP              |
| Blue ORB    | SP              |
| White ORB   | Critical Damage |
| Violet ORB  | Team Attack     |

ตัวอย่าง

<figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

```
Yellow Orb +10
```

***

## 5. ORB Upgrade System

<figure><img src="../.gitbook/assets/image (3).png" alt="" width="563"><figcaption></figcaption></figure>

จากภาพ

ระบบ Upgrade ใช้

```
5 ORBs
```

เพื่อสร้าง ORB ที่สูงขึ้น

### Upgrade Rule

สูตร

```
5 ORB → 1 ORB (+1 Level)
```

ผลลัพธ์

<figure><img src="../.gitbook/assets/Success.gif" alt="" width="563"><figcaption></figcaption></figure>

| Result  | Description |
| ------- | ----------- |
| Success | ORB Level+1 |

<figure><img src="../.gitbook/assets/Fail.gif" alt="" width="563"><figcaption></figcaption></figure>

ผลลัพธ์

| Result | Description                              |
| ------ | ---------------------------------------- |
| Fail   | ORB Level เท่าเดิม (เสียทรัพยากร 4 ชิ้น) |

***

### 6. ORB Socket System

ผู้เล่นสามารถใส่ ORB ลงใน Costume

<figure><img src="../.gitbook/assets/Step 1.gif" alt="" width="563"><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/Step 2.gif" alt="" width="563"><figcaption></figcaption></figure>

#### Socket Process

1. เปิด Costume UI
2. เลือก Slot
3. ใส่ ORB
