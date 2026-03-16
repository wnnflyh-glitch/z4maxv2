# ⚖️ Tax System

### Overview

ระบบ **Tax System** ในเกม Zone4 เป็นระบบที่ใช้เรียกเก็บค่าธรรมเนียมจากการซื้อขายไอเทมระหว่างผู้เล่น (Player-to-Player Trading) ภายในพื้นที่ **Square / Marketplace**

เมื่อผู้เล่นทำการตั้งร้านขายไอเทมหรือซื้อขายสินค้า ระบบจะหักภาษีตามเปอร์เซ็นต์ที่กำหนดก่อนที่เงินจะถูกส่งไปยังผู้ขาย

วัตถุประสงค์ของระบบภาษีคือ

* ควบคุมปริมาณเงินในระบบเกม
* สร้างความสมดุลของเศรษฐกิจในเกม

## Tax Structure

ใน Zone4 การซื้อขายไอเทมสามารถทำผ่าน **Player Shop** หรือ **Square Market** ซึ่งแต่ละประเภทของร้านค้าจะมีอัตราภาษีที่แตกต่างกัน

ตัวอย่างอัตราภาษีที่ใช้ในระบบ (ขึ้นอยู่กับประเภท Shop)

<table data-view="cards"><thead><tr><th></th><th data-hidden data-card-cover data-type="image">Cover image</th></tr></thead><tbody><tr><td></td><td data-object-fit="contain"><a href="../.gitbook/assets/image (70).png">image (70).png</a></td></tr><tr><td></td><td data-object-fit="contain"><a href="../.gitbook/assets/image (71).png">image (71).png</a></td></tr><tr><td></td><td data-object-fit="contain"><a href="../.gitbook/assets/image (72).png">image (72).png</a></td></tr></tbody></table>

| Shop Type    | Tax Rate |
| ------------ | -------- |
| My Shop      | 10%      |
| Special Shop | 7%       |
| Premium Shop | 5%       |
| Mega Shop    | 3%       |
| ZM Shop      | 1%       |
| No VAT       | 0%       |

## P2P Trading (Player-to-Player)

### Definition![](<../.gitbook/assets/image (72).png>)

<figure><img src="../.gitbook/assets/image (71).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (70).png" alt=""><figcaption></figcaption></figure>

**P2P Trading** คือการซื้อขายไอเทมระหว่างผู้เล่นโดยตรงภายในเกม โดยทั่วไปจะเกิดขึ้นผ่าน

* Player Trade

ผู้เล่นสามารถแลกเปลี่ยนสินค้าบางประเภท หรือ ZEN กับผู้เล่นคนอื่นได้

### P2P Tax System

ในการซื้อขายแบบ P2P ระบบจะหักภาษีจากราคาขายก่อนที่เงินจะถูกส่งไปยังผู้ขาย

#### Tax Calculation

#### Example

ราคาขายไอเทม

100,000 Gold

อัตราภาษี

10%

การคำนวณ

Tax = 100,000 × 10%\
Tax = 10,000

เงินที่ผู้ขายได้รับ

90,000 Gold
