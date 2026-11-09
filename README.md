# Thailand Stay (HTML/CSS/JavaScript)

เว็บไซต์ตัวอย่างจองที่พัก 2 หน้า ใช้ HTML, CSS และ Vanilla JavaScript เท่านั้น ไม่มี Backend และไม่มีฐานข้อมูล

## เปิดใช้งานในเครื่อง
1. แตกไฟล์ ZIP
2. เปิดโฟลเดอร์ด้วย VS Code
3. เปิด `index.html` ในเบราว์เซอร์ หรือใช้ส่วนขยาย Live Server

## Deploy บน Vercel
1. สร้าง GitHub repository และอัปโหลดไฟล์ทั้งหมดในโฟลเดอร์นี้ไว้ที่ root ของ repository
2. เข้า https://vercel.com และ Sign up / Log in ด้วย GitHub
3. เลือก Add New → Project → Import Git Repository
4. เลือก repository ที่อัปโหลดไว้
5. ตั้งค่า Framework Preset เป็น Other (หรือปล่อยให้ตรวจจับเป็น Other), Root Directory เป็น `./`
6. ไม่ต้องกำหนด Build Command และ Output Directory; เว็บไซต์เป็น static files
7. กด Deploy แล้วเปิด URL ที่ Vercel แสดง

## ข้อจำกัดสำคัญ
- การจองเป็น Demo เท่านั้น ข้อมูลเก็บใน LocalStorage ของ Browser เครื่องนั้น
- ไม่มีระบบบัญชีผู้ใช้, ระบบห้องว่างแบบเรียลไทม์, การชำระเงินจริง หรือการซิงก์ข้อมูลข้ามอุปกรณ์
- รูปภาพและ Google Fonts โหลดจากอินเทอร์เน็ต
- ก่อนใช้เชิงธุรกิจจริง ต้องมี Backend/ฐานข้อมูลและระบบชำระเงินที่ปลอดภัย
