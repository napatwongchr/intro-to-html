# HTML Tags

เราลองมาเริ่มสร้าง Elements บนหน้าเว็บกันดีกว่า

```html
<h1>Welcome to Alcodemist</h1>
```

HTML จะประกอบด้วย Tag เปิด `<h1>` และ Tag ปิด `</h1>` และของที่อยู่ระหว่าง Tag คือ Content ในที่นี้จะเป็น Text "Welcome to Alcodemist"

## Playing With Tags

**heading tag** - เป็น Tag ที่แสดงข้อความที่เป็นหัวข้อใหญ่ ๆ บนหน้าเว็บ

```html
<h1>Alcodemist is fabulous !</h1>
<h2>Alcodemist is fabulous !</h2>
<h3>Alcodemist is fabulous !</h3>
<h4>Alcodemist is fabulous !</h4>
<h5>Alcodemist is fabulous !</h5>
<h6>Alcodemist is fabulous !</h6>
```

**paragraph tag** - เป็น Tag ที่แสดง paragraph บนหน้าเว็บ

```html
<p>
  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed aliquet elit
  dolor, vel consequat arcu convallis vitae. Class aptent taciti sociosqu ad
  litora torquent per conubia nostra, per inceptos himenaeos. Class aptent
  taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos.
  Donec in nisl finibus, eleifend felis a, volutpat lorem. Suspendisse
  ullamcorper nisi vel dui faucibus luctus. Quisque ligula turpis, imperdiet eu
  porta eu, bibendum viverra est. Curabitur posuere lectus at ultricies
  ultrices. Nullam egestas leo sapien, eu bibendum magna viverra a. Curabitur et
  efficitur ex. Proin tempor id mi sit amet commodo. Aliquam erat volutpat.
  Nullam fringilla gravida dui, at bibendum sapien mattis eu. Nullam sit amet
  mauris et ante semper fermentum. Donec bibendum accumsan odio, id viverra
  tortor.
</p>
```

**span tag** - เป็น Tag ที่สร้างกล่องที่อยู่บรรทัดเดียวกันกับ Element ตัวอื่น ๆ

```html
<p>
  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed aliquet elit
  dolor, vel consequat arcu convallis vitae. Class aptent taciti sociosqu ad
  litora torquent per conubia nostra, per inceptos himenaeos.
  <span
    >Class aptent taciti sociosqu ad litora torquent per conubia nostra, per
    inceptos himenaeos.</span
  >
  Donec in nisl finibus, eleifend felis a, volutpat lorem. Suspendisse
  ullamcorper nisi vel dui faucibus luctus. Quisque ligula turpis, imperdiet eu
  porta eu, bibendum viverra est. Curabitur posuere lectus at ultricies
  ultrices. Nullam egestas leo sapien, eu bibendum magna viverra a. Curabitur et
  efficitur ex. Proin tempor id mi sit amet commodo. Aliquam erat volutpat.
  Nullam fringilla gravida dui, at bibendum sapien mattis eu. Nullam sit amet
  mauris et ante semper fermentum. Donec bibendum accumsan odio, id viverra
  tortor.
</p>
```

**a tag** - เป็น Tag ที่สร้าง Link ไปยังหน้าเว็บอื่น ๆ

```html
<a href="https://google.com">Link to GOOGLE</a>
```

**ol/ul และ li Tag** - เป็น Tag ที่สร้าง List ของข้อมูล

**ul** (**U**norder **L**ist) เป็น Tag ที่สร้าง List ของข้อมูลแบบไม่กำหนดลำดับ แต่ละ **li** (**L**ist **I**tem) จะมี Bullet อยู่ข้างหน้า

```html
<ul>
  <li>Home</li>
  <li>Products</li>
  <li>Customer Support</li>
  <li>About US</li>
</ul>
```

**ol** (**O**rder **L**ist) เป็น Tag ที่สร้าง List ของข้อมูลแบบกำหนดลำดับ แต่ละ **li** (**L**ist **I**tem) จะมี 1, 2, 3, 4 อยู่ข้างหน้า

```html
<ol>
  <li>Home</li>
  <li>Products</li>
  <li>Customer Support</li>
  <li>About US</li>
</ol>
```

🌟 **div** เป็น Tag ที่สร้างกล่องเปล่า ๆ ไว้ใช้รวบสิ่งของต่าง ๆ ไว้ข้างในกล่อง

```html
<div>
  <div>Post: Coding is fun 😻</div>
  <div>
    Etiam ut massa a lorem aliquam porttitor non eu erat. Praesent finibus
    laoreet pellentesque. Fusce eu erat odio. Nulla quis ligula ut mauris
    molestie interdum. Suspendisse dolor sem, hendrerit et mi ut, mattis
    placerat tortor.
  </div>
</div>
```

**button** เป็น Tag ที่สร้างปุ่มกด

```html
<button>Submit</button> <button>Login</button>
```

**img** เป็น Tag ที่แสดงรูปภาพ

- attribute href เป็นตัวบอกว่าเราจะเอารูปมาจากไหน สามารใส่ได้ทั้ง file path บนเครื่องเรา หรือ url รูปภาพบน web

- 🌟 alt attribute เป็น attribute ที่บรรยายเวลารูปภาพโหลดไม่ขึ้น และมีผลดีเกี่ยวกับเรื่องของ **Accessibility** เวลา Screen reader มาอ่านรูปมันจะอ่านตามข้อความที่เราใส่ไว้ใน alt attribute เดี๋ยวส่วนนี้เราจะพูดถึงกันอีกต่อ ๆ ไป

```html
<img src="https://placedog.net/640/480?random" alt="cute dog" />
```

**input** เป็น Tag ที่เอาไว้ใช้รับข้อมูล จากผู้ใช้งาน

```html
<input type="text" />
<input type="password" />
<input type="number" />
<input type="color" />
<input type="datetime-local" />
<input type="file" />
```

**form** เป็น Tag ที่เอาไว้ใช้รับข้อมูลจาก Input ต่าง ๆ และสามารถส่งข้อมูลไปยัง Server ได้

```html
<form>
  <input type="text" />
  <button type="submit">Submit</button>
</form>
```

**table** เป็น Tag ที่เอาไว้ใช้สร้างตาราง

```html
<table border="1">
  <tr>
    <td>1</td>
    <td>2</td>
  </tr>
</table>
```

## In Class Exercises

ให้เขียน HTML Elements ให้ได้ตาม User Interface

**Figma:**

**Note**

เขียน Tags ให้ครบ โดยที่ยังไม่ต้องสนในการจัดวาง และหน้าตาของ

[Answer](https://github.com/napatwongchr/intro-to-html/blob/main/exercises/html-exercises-1.md)

## Take Home Exercises

ให้เขียน HTML Elements ให้ได้ตาม User Interface

**Figma:**

**Note**

เขียน Tags ให้ครบ โดยที่ยังไม่ต้องสนในการจัดวาง และหน้าตาของ

[Answer](https://github.com/napatwongchr/intro-to-html/blob/main/exercises/html-exercises-1.md)
