# Form Practice

รูปแบบการเขียน Form ทั่วไปบนหน้าเว็บ จะมีสิ่งที่เราต้องรู้เพิ่มเติมก็คือ Tags label

## Tag Label

Tag Label เป็นการปรับปรุงตัว Form ให้ใช้งานง่ายมากยิ่งขึ้น ตัวอย่างคือ เวลา Users click ไปที่ Text หรือตัว Label เนี่ย มันจะทำการ Focus ไปที่ตัว Input Field ให้เราเลย

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

⚠️ ชื่อข้างใน Attribute for กับ id ของ Input Element นั้นต้องตรงกันนะ ไม่งั้นเราจะไม่สามารถ click ที่ label ได้

<br><hr><br>

<div style="display: flex; justify-content: space-between;">
  <a href="https://github.com/napatwongchr/intro-to-html/blob/main/lessons/9-chrome-dev-tools.md"><< ไปก่อนหน้า</a>
  <a href="#">หน้าต่อไป >></a>
</div>
