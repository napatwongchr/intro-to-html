# Meta HTML Tags

คือ HTML Tags ที่ไม่มีผลต่อการแสดงผล แต่**มีผลต่อกลไกการทำงานเบื้องหลังของ Web Browser**

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
- `<meta name="viewport" content="width=device-width, initial-scale=1.0" />` ทำให้ Web App แสดงผลบน Device อื่นๆด้วย Scale ที่เหมาะสม ดู[ตัวอย่างได้ที่นี่](https://www.w3schools.com/css/css_rwd_viewport.asp) 🌟
- `<title>Learn Meta Tags</title>` ทำให้ Header ของ Web Browser เปลี่ยนเป็นข้อความที่ต้องการ
- `<head>` พวก Meta Tags ต่าง ๆ จะใส่ไว้อยู่ระหว่าง `<head>`
- `<body>` พวก Elements ต่าง ๆ บนหน้าเว็บจะอยู่ระหว่าง `<body>`
