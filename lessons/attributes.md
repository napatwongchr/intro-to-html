# Attributes

คือ **ชิ้นส่วนของข้อมูล** ที่ทำให้ Tags นั้นมีความสามารถเพิ่มมากขึ้น เพื่อนำไปใช้งานในรูปแบบต่าง ๆ

**ตัวอย่าง**

Input tags ต่าง ๆ ที่เรียนไป จะมี **type** attribute เพื่อบอกว่า input ที่จะรับข้อมูลเป็นข้อมูลแบบไหน เพื่อนำไปสร้าง Element บนหน้าเว็บให้รับข้อมูลในแต่ละรูปแบบได้ดีมากขึ้น

```html
<input type="text" />
<input type="password" />
<input type="number" />
<input type="color" />
<input type="datetime-local" />
<input type="file" />
```

<hr>

## Special Attributes 🌟

- **class** เป็น attribute ที่ใช้ในการแยกความแตกต่างระหว่าง Tag ที่เหมือนกัน

```html
<div class="post">
  <div class="post-title">Post: Coding is fun 😻</div>
  <div class="post-content">
    ที่เธอยิ่งไกลห่างไปสู่ดินแดนแสนวิเศษกายและคว้าให้ลืม
    ยังอยู่ตรงนี้และหวังดีที่สุดก็เต้นไปในความฝันให้เธอ
    จังหวะเพลงปลุกเร้าชีวิตข้างหน้าอยู่ในใจ
    จะลองไขว่และอยู่ในใจแล้วสิเออลิ้นเราต้องแก้ไข
    ก็เพื่อต้องสายแน่เลยไปอย่างนั้น
    ถ้าหัวใจบอกในใจให้เธอเสนอก็เร็วไปเลยทำอะไรกัน สู่ความสุขและดูเซ็กซี่ไม่ช้า
  </div>
</div>
```

- **id** เป็น attribute ที่ใช้มีจุดประสงค์เดียวกับกับ class attribute

```html
<div id="promotion-section">
  <h1>ส่วนของ Promotion บนหน้าเว็บ</h1>
</div>
```

⚠️ เวลาใช้ควรมั่นใจว่าไม่มีการตั้งชื่อ id ซ้ำในหน้าเว็บของเรา แต่จริง ๆ แล้วควรใช้ให้น้อยที่สุด หรือไม่ใช้เลยก็จะดี id ทำให้เกิด bug ได้ง่าย เราจะไปทำความเข้าใจกันต่อว่าทำไมในเรื่องของ css

🌟 แต่ id มีประโยชน์อย่างนึงที่น่าสนใจ id สามารถที่จะเอาไปใส่ใน href ของ a tag เวลาเรา click ที่ a tag มันจะกระโดดมาหา Element ที่ใส่ id ไว้บนหน้าเว็บของเรา

```html
<a href="#promotion-section"> Click to scroll to promotion section </a>

<!-- Other sections or elements make page very tall -->

<div id="promotion-section">
  <h1>ส่วนของ Promotion บนหน้าเว็บ</h1>
</div>
```

<hr>

## In Class Exercises

ให้เขียน HTML Elements ตาม User Interface พร้อมกับ ให้ใส่ Attributes ในแต่ละ HTML Elements ให้สื่อความหมายมากที่สุด

**Figma:** 

**Note** 

เขียน Tags ให้ครบ โดยที่ยังไม่ต้องสนในการจัดวาง และหน้าตาของ

[Answer](https://github.com/napatwongchr/intro-to-html/blob/main/exercises/html-exercises-1.md)

<hr>

## Take Home Exercises

ให้ทำตาม Requirements

**Requirements**

โรงเรียนแห่งหนึ่ง อยากเก็บข้อมูลของนักเรียนผ่านระบบของโรงเรียนด้วยหน้าเว็บที่มีอยู่ ดังนี้
ชื่อ, นามสกุล, อายุ, วัน เดือน ปีเกิด, สีที่ชอบ, เพศ, รูปประจำตัว, คติประจำใจ ลูกค้าอยากได้หน้าเว็บ ที่ีสามารถรับข้อมูลจากผู้ใช้งาน ผ่านหน้าเว็บ ได้ครบถ้วน

**Note** 

เขียน Tags ให้ครบ โดยที่ยังไม่ต้องสนในการจัดวาง และหน้าตาของ

[Answer](https://github.com/napatwongchr/intro-to-html/blob/main/exercises/html-exercises-1.md)
