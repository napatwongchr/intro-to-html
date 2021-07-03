# Form

รูปแบบการเขียน Form ทั่วไปบนหน้าเว็บ จะมีสิ่งที่เราต้องรู้เพิ่มเติมก็คือ **Label Tag**

<hr>

## Label Tag

Label Tag เป็นการปรับปรุงตัว Form ให้ใช้งานง่ายมากยิ่งขึ้น

ตัวอย่างคือ เวลา user click ไปที่ text หรือตัว label เนี่ย มันจะทำการ focus ไปที่ตัว input field ให้เราเลย

ลองมาดู Code กัน

```html
<form>
  <label for="username">Username</label>
  <input id="username" type="text" />

  <label for="password">Password</label>
  <input id="password" type="password" />

  <label for="number">Number</label>
  <input id="number" type="number" />

  <input type="color" />
  <input type="datetime-local" />
  <input type="file" />

  <div>
    <span>Radio</span>
    <input id="option1" type="radio" name="options" />
    <label for="option1">Option 1</label>

    <input id="option2" type="radio" name="options" />
    <label for="option2">Option 2</label>

    <input id="option3" type="radio" name="options" />
    <label for="option3">Option 3</label>
  </div>

  <div>
    <span>Checkbox</span>
    <label for="checkbox">Checkbox 1</label>
    <input id="checkbox" type="checkbox" />

    <label for="checkbox2">Checkbox 2</label>
    <input id="checkbox2" type="checkbox" />
  </div>

  <label for="textarea">Checkbox 1</label>
  <textarea id="textarea"></textarea>
</form>
```

⚠️ ชื่อข้างใน Attribute for กับ id ของ input element นั้นต้องตรงกันนะ ไม่งั้นเราจะไม่สามารถ click ที่ label ได้

<hr>

## In Class Exercises

ให้สร้าง Login Form ตาม User Interface ให้สมบูรณ์

**Figma:** 

**Note** 

- เขียน Tags ให้ครบ โดยที่ยังไม่ต้องสนในการจัดวาง และหน้าตาของ
- อย่าลืม Label Tags !

[Answer](https://github.com/napatwongchr/intro-to-html/blob/main/exercises/html-exercises-1.md)

<hr>

## Take Home Exercises

ให้สร้าง Payment Form ตาม User Interface ให้สมบูรณ์

**Figma:** 

**Note** 

- เขียน Tags ให้ครบ โดยที่ยังไม่ต้องสนในการจัดวาง และหน้าตาของ
- อย่าลืม Label Tags !

[Answer](https://github.com/napatwongchr/intro-to-html/blob/main/exercises/html-exercises-1.md)