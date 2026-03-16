# 🎛️ Costume Mix System

## Overview

Costume Mix System เป็นระบบในเกม **Zone4** ที่ให้ผู้เล่นนำ **Costume Item 2 ชิ้น** มาผสมกันผ่าน \
NPC **Dr.K** โดยใช้ไอเทมพิเศษชื่อ **Costume Cube** เพื่อสร้างไอเทมใหม่แบบสุ่ม (Randomized Result) ระบบนี้ถูกออกแบบเพื่อ

* รีไซเคิล Costume ที่ผู้เล่นไม่ต้องการ
* ให้ผู้เล่นมีโอกาศ ได้รับ ชุด Special Costume ที่อยู่ภายใน

Costume Mix ช่วยให้ผู้เล่นสามารถเปลี่ยนไอเทมแฟชั่นที่มีอยู่ให้ มีโอกาศกลายเป็นไอเทมใหม่โดยไม่ต้องซื้อใหม่จากร้านค้า

{% stepper %}
{% step %}
### Step 1 – Meet Dr.K

<figure><img src="../.gitbook/assets/Dr.K (1).gif" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Step 2 – Open Mixing Interface

แล้วเลือก

<figure><img src="../.gitbook/assets/image (105).png" alt=""><figcaption></figcaption></figure>

```
Costume Mix
```


{% endstep %}

{% step %}
### Step 3 – Insert Items

ผู้เล่นใส่

```
Costume A
Costume B
Costume Cube
```

ลงในช่องผสม


{% endstep %}

{% step %}
### Step 4 – Activate Mix

<figure><img src="../.gitbook/assets/image (106).png" alt=""><figcaption></figcaption></figure>

ผู้เล่นกดปุ่ม

```
Mix
```

ระบบจะเริ่มกระบวนการสุ่ม
{% endstep %}
{% endstepper %}

## Result

เมื่อ Mix สำเร็จ

ระบบจะ

1. ลบ Costume เดิมทั้งสองชิ้น
2. ส่งไอเทมใหม่เข้าสู่ Inventory

## Failure Handling

หากการ Mix ล้มเหลว

<figure><img src="../.gitbook/assets/Costume Mix.gif" alt=""><figcaption></figcaption></figure>

ผลลัพธ์เป็น

* ไม่ได้รับไอเทม
* Sub Item ถูกทำลาย 1 ชิ้น
