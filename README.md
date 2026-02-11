# Activity Report Generator
## ระบบสร้างรายงานกิจกรรม — กรุงเทพประกันชีวิต

---

## วิธีใช้งาน

### แบบที่ 1: เปิดไฟล์ HTML โดยตรง (ง่ายที่สุด)
1. ดับเบิลคลิกไฟล์ `index.html`
2. เปิดใน Chrome / Edge
3. กรอกข้อมูล → ดู Preview → กด Export
4. **หมายเหตุ**: ต้องมี Internet สำหรับโหลด Font และ html2canvas

---

### แบบที่ 2: Deploy บน Vercel (แชร์ลิงก์ได้)

#### ขั้นตอน:
1. สร้าง Account ที่ [vercel.com](https://vercel.com) (ฟรี)
2. ติดตั้ง Vercel CLI:
   ```bash
   npm install -g vercel
   ```
3. เปิด Terminal ใน Folder นี้:
   ```bash
   cd vercel-project
   vercel
   ```
4. ตอบคำถาม → ได้ URL ใช้งานเลย เช่น `https://activity-report-xxxxx.vercel.app`

#### หรือ Deploy ผ่าน GitHub:
1. Push โฟลเดอร์นี้ขึ้น GitHub
2. ไปที่ [vercel.com/new](https://vercel.com/new)
3. Import GitHub Repo
4. กด Deploy → เสร็จ!

---

## คุณสมบัติ
- ✅ กรอกข้อมูลกิจกรรม (โซน, สาขา, วันที่, เวลา)
- ✅ อัปโหลดรูปถ่ายได้ 9 รูป
- ✅ Live Preview แบบ Real-time
- ✅ Export เป็น PNG / JPG / PDF
- ✅ Print โดยตรง
- ✅ ใช้งานบน Mobile ได้
- ✅ ไม่มีข้อมูลถูกส่งไป Server (ทำงานฝั่ง Client ทั้งหมด)

---

## เทคโนโลยี
- HTML5 / CSS3 / Vanilla JavaScript
- Google Fonts (Sarabun)
- html2canvas (สำหรับ Export ภาพ)
