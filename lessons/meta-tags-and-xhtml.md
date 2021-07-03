# Meta and XHTML

## Meta HTML Tags

คือ HTML Tags ที่ไม่มีผลต่อการแสดงผล แต่มีผลต่อกลไกการทำงานเบื้องหลังของ Web Browser

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Learn Meta Tags</title>
  </head>
  <body></body>
</html>
```

- `<!DOCTYPE html>` เป็นตัวกำหนด Version ของ HTML
- `<html lang="en">` เป็นตัวบอกภาษา
- `<meta charset="UTF-8" />` ทำให้ HTML อ่าน Code UTF8 ออก
- `<title>Learn Meta Tags</title>` ทำให้ Header ของ Web Browser เปลี่ยนเป็นข้อความที่ต้องการ
- `<head>` พวก Meta Tags ต่าง ๆ จะใส่ไว้อยู่ระหว่าง `<head>`
- `<body>` พวก Elements ต่าง ๆ บนหน้าเว็บจะอยู่ระหว่าง `<body>`

<br><hr><br>

## XHTML

โดยปกติแล้วผมเขียน html แบบย่อ ๆ ซึ่ง Web Browser มันก็แสดงผลได้เหมือนกัน

แต่จริง ๆ แล้วเราควรเขียนเต็ม ๆ ซึ่งก็คือ XHTML แหล่ะ

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>
    <div class="post">
      <div class="post-title">Post: Coding is easy 😻</div>
      <div class="post-content">
        ที่เธอยิ่งไกลห่างไปสู่ดินแดนแสนวิเศษกายและคว้าให้ลืม
        ยังอยู่ตรงนี้และหวังดีที่สุดก็เต้นไปในความฝันให้เธอ
        จังหวะเพลงปลุกเร้าชีวิตข้างหน้าอยู่ในใจ
        จะลองไขว่และอยู่ในใจแล้วสิเออลิ้นเราต้องแก้ไข
        ก็เพื่อต้องสายแน่เลยไปอย่างนั้น
        ถ้าหัวใจบอกในใจให้เธอเสนอก็เร็วไปเลยทำอะไรกัน
        สู่ความสุขและดูเซ็กซี่ไม่ช้า
      </div>
    </div>
  </body>
</html>
```
