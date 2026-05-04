# Supermarket Inventory Management System
โปรเจกต์นี้เป็นระบบจัดการข้อมูลสินค้าในซูเปอร์มาร์เก็ต พัฒนาโดยใช้ Node.js ร่วมกับ Express และเชื่อมต่อฐานข้อมูล MySQL โดยใช้รูปแบบโครงสร้างแบบ MVC เพื่อให้โค้ดเป็นระเบียบและแยกหน้าที่ชัดเจน

## functionระบบ
- แสดงรายการสินค้า
- เพิ่มสินค้าใหม่
- แก้ไขข้อมูลสินค้า
- ลบสินค้า
- อัปโหลดรูปภาพสินค้า
- แสดงสถานะสินค้าเมื่อของหมด

## เครื่องมือที่ใช้
- Node.js
- Express.js
- MySQL (ใช้ผ่าน MAMP)
- EJS
- Bootstrap 5

## วิธีติดตั้งและใช้งาน
1. ดาวน์โหลดโปรเจกต์นี้มาไว้ในเครื่อง
2. เปิดโปรเจกต์ด้วย VS Code แล้วติดตั้ง dependencies โดยใช้คำสั่ง npm install
3. เปิดโปรแกรม MAMP และกด Start Servers
4. เข้า phpMyAdmin แล้ว import ไฟล์
supermarket_db.sql
5. ตรวจสอบการตั้งค่า database ในไฟล์ app.js ให้ตรงกับเครื่องที่ใช้ เช่น
host: '127.0.0.1'
user: 'root'
password: 'root'
port: 3306
database: 'supermarket_db'
6. รันโปรเจกต์ด้วยคำสั่ง node app.js
7. เปิดเว็บเบราว์เซอร์แล้วเข้า http://localhost:3000

## หมายเหตุ
- ต้องเปิด MAMP ก่อนใช้งานทุกครั้ง
- ต้องมีไฟล์ no-image.png อยู่ในโฟลเดอร์ public/assets/img/
- ไม่ต้องอัปโหลดโฟลเดอร์ node_modules ขึ้น GitHub
