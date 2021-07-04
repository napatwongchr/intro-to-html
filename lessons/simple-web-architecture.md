# How Web Works ?

เราลองมาดูการทำงานของ Web กันสักหน่อยก่อนที่จะไปกันต่อ

![Basic web architecture](./images/web-basic-architect-client-server.png)

จากภาพด้านบน เราเปิดเว็บผ่าน Browser (ในที่นี้คือ Google Chrome) มาสัก 1 เว็บ

สมมุติว่าเป็นเว็บ Shopee สิ่งที่เราเห็นก็คือ เราจะเห็น รายการสินค้าที่เอามาจัด Flash Sale, สิ้นค้าติดอันดับ และเวลาเรากดเข้าไปตามหมวดหมู่เราก็จะเห็นสินค้าตามหมวดหมู่นั้น ๆ

สิ่งที่เราเห็นจะเป็นส่วนที่เรียกว่า Frontend ซึ่ง Frontend ก็คือส่วนแสดงผลของเว็บ จะมีข้อมูลต่าง ๆ ที่เรามองเห็น ข้อมูลพวกนี้จะถูกเก็บอยู่ที่ Database

การที่จะเอาข้อมูลมาแสดงที่ Frontend Frontend จะต้องทำการ Request ไปที่ Server

Request ตือ การติดต่อ Server เพื่อที่จะขอทำอะไรสักอย่าง

Server จะดึงข้อมูลที่อยู่ใน Database แล้วส่งกลับไปเป็น Response ให้ Frontend นำไปแสดงผล

เช่น ขอรายการสินค้า Flash Sale ตัว Server จะมีช่องทางการติดต่อกับ Frontend ช่องทางนี้แหล่ะ เราเรียกว่า API

<br><br>

<div style="display: flex; justify-content: space-between;">
  <a href="https://github.com/napatwongchr/intro-to-html/blob/main/lessons/2-simple-web-architecture.md"><< ไปก่อนหน้า</a>
  <a href="https://github.com/napatwongchr/intro-to-html/blob/main/lessons/3-getting-into-html.md">หน้าต่อไป >></a>
</div>
