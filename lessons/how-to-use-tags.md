# How To Use Tags

การเลือกใช้ Tag ควรคำนึงถึง ความหมาย และหน้าที่ของ Tag นั้นๆ จริงๆ

🌟 **ยกตัวอย่าง h1 กับ span ต่างกันยังไง ?** เลือกใช้ตัวไหนดี ? หรือว่าใช้แทนกันได้เลย

- h1 คือ Tag ที่เป็นหัวข้อใหญ่ ๆ บนหน้าเว็บ
- span คือ Tag ที่เป็นกล่องข้อความเล็ก ๆ บนหน้าเว็บ

เราไม่ควรใช้กลับกันอย่างยิ่ง มันจะมีผลชัดเจนมาก ๆ ในเรื่องของ **Accessibility** คนที่ใช้ Screen reader จะไม่สามารถแยกข้อความได้ออกว่า เป็นข้อความที่เป็นหัวข้อใหญ่ หรือเป็นแค่ข้อความธรรมดา

เคสนี้เราสามารถลองเล่นผ่าน Google Chome Extension ที่ชื่อว่า [Screen Reader](https://chrome.google.com/webstore/detail/screen-reader/kgejglhpjiefppelpmljglcjbhoiplfn?hl=en)

## Accessibility 📖

🌟 **Accessibility** การที่เราทำ Web Application โดยคำนึงถึงกลุ่มคนที่มีความพิการในด้านต่าง ๆ

ยกตัวอย่างเกี่ยวกับ กลุ่มคนที่เป็น [Dyslexia](https://youtu.be/PTqhgjxRkFU?t=47)

> Dyslexia คือความบกพร่องในการอ่านและการเขียน จัดเป็นความผิดปกติด้านการเรียนรู้ (Learning Disorder) ประเภทหนึ่ง ซึ่งมีสาเหตุจากความผิดปกติของสมองส่วนที่เกี่ยวข้องกับกระบวนการเรียนรู้ ทำให้ผู้ที่เป็น มีปัญหาในการอ่าน การเขียน แม้แต่การแปลภาษาหรือสัญลักษณ์ง่ายๆ ไม่สามารถเรียนรู้สิ่งต่างๆ ได้เหมือนคนทั่วไป

[Reference](https://www.brainandlifecenter.com/braintraining-improve-dyslexia#:~:text=Dyslexia%20%E0%B8%84%E0%B8%B7%E0%B8%AD%E0%B8%84%E0%B8%A7%E0%B8%B2%E0%B8%A1%E0%B8%9A%E0%B8%81%E0%B8%9E%E0%B8%A3%E0%B9%88%E0%B8%AD%E0%B8%87%E0%B9%83%E0%B8%99,%E0%B8%97%E0%B8%B1%E0%B9%88%E0%B8%A7%E0%B9%84%E0%B8%9B%20%E0%B8%8B%E0%B8%B6%E0%B9%88%E0%B8%87%E0%B9%82%E0%B8%A3%E0%B8%84%E0%B8%99%E0%B8%B5%E0%B9%89%E0%B8%AA%E0%B8%B2%E0%B8%A1%E0%B8%B2%E0%B8%A3%E0%B8%96)

การที่เราจะทำให้ Content บนหน้าเว็บเรานั้น Accessible สำหรับกลุ่มคนที่เป็น Dyslexia

- **Fonts**

  - sans serif จัดว่าเป็น Best practice เป็น Font ที่กลุ่มคนประเภทนี้สามารถที่จะอ่าน ทำความเข้าใจได้ง่ายที่สุด
  - ขนาดของ Font ต้องขนาด 12 or 14 pt

- **Content Design**

  - บรรทัดแต่ละบรรทัดต้องสูงห่างกัน 1.5
  - Paragraph ไม่ควรยาวเกินไป ให้พยายาม Break ลงมาเป็นบรรทัดใหม่ ให้อ่านได้ง่ายมากขึ้น
  - ลดการใช้ <u>Underline</u> **Bold** หรือ _Italic_

- **Layout and Graphics**
  - พยายามใช้ Images, Diagrams, Icons ประกอบข้อความต่าง ๆ
  - ทำให้ Web Application เราสามารถปรับ ขนาด, สี, font ได้
  - ควรทำให้ Text ชิดซ้ายอย่างเท่ากันสม่ำเสมอ

[Reference](https://www.boia.org/blog/how-to-create-accessible-content-and-designs-for-people-with-dyslexia)

## In Class Exercises - 05 🏅

ให้ Refactor Code HTML ออกมาโดยใช้ Tags ได้อย่างเหมาะสม

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>ABC Company</title>
  </head>
  <body>
    <div class="header-section">
      <div class="logo">
        <img src="https://via.placeholder.com/150" />
        <div>ABC Company</div>
      </div>
      <div class="navigation-bar">
        <ul class="menu">
          <li class="menu-item">Home</li>
          <li class="menu-item">About Us</li>
          <li class="menu-item">SignUp</li>
          <li class="menu-item">SignIn</li>
        </ul>
      </div>
    </div>
    <div class="promotion-section">
      <div class="promotion-item">
        <span class="promotion-title">Buy 2 Get 3 Free !!</span>
        <div class="promotion-content">
          Etiam ut massa a lorem aliquam porttitor non eu erat. Praesent finibus
          laoreet pellentesque. Fusce eu erat odio. Nulla quis ligula ut mauris
          molestie interdum. Suspendisse dolor sem, hendrerit et mi ut, mattis
          placerat tortor.
        </div>
        <span class="promotion-time">08:00:00</span
        ><span class="promotion-time-unit">Hours Left !</span>
      </div>
    </div>
    <div class="footer-section">© 2021 ABC</div>
  </body>
</html>
```

**Note**

- ทำให้ Code มีความ Semantics ให้มากขึ้นกว่าเดิม

[Answer](https://github.com/napatwongchr/intro-to-html/blob/main/exercises/ex05-inclass-answer.html)

## Take Home Exercises - 05 🏅

ให้ Refactor Code HTML ออกมาโดยใช้ Tags ได้อย่างเหมาะสม

```html
<div class="article">
  <span class="article-title">Some article title</span>
  <div class="article-content">
    Etiam ut massa a lorem aliquam porttitor non eu erat. Praesent finibus
    laoreet pellentesque. Fusce eu erat odio. Nulla quis ligula ut mauris
    molestie interdum. Suspendisse dolor sem, hendrerit et mi ut, mattis
    placerat tortor. In pulvinar sollicitudin justo consequat rhoncus. Aliquam
    sit amet mauris turpis. Etiam ornare neque metus, sed mattis lectus maximus
    sed. Ut vehicula metus nec nunc rhoncus, eget volutpat erat aliquet. Sed eu
    sapien nec magna auctor pellentesque interdum a augue. Aenean arcu justo,
    ullamcorper in quam sollicitudin, sagittis feugiat metus. Quisque quis
    ultrices tortor, eget dignissim ipsum.
  </div>
  <span class="article-author">Author: John</span>
  <span class="article-published-time"
    >Published At:
    <span class="article-published-time-text"
      >Tuesday, 31 October 2020</span
    ></span
  >
  <time datetime="2020-10-31T11:21:00+00:00">Tuesday, 31 October 2020</time>
</div>
```

**Note**

- ทำให้ Code มีความ Semantics ให้มากขึ้นกว่าเดิม

[Answer](https://github.com/napatwongchr/intro-to-html/blob/main/exercises/ex05-takehome-answer.html)
