# CapYaDoo System - Data Flow Diagrams

ระบบ CapYaDoo สำหรับการจัดการยาและการแจ้งเตือน

## DFD Levels

### Level 1 - Main Processes
- การจัดการข้อมูลผู้ใช้
- ระบบ OCR/Barcode และ Text-to-Speech  
- การจัดการยา
- การจัดการแจ้งเตือน
- บันทึกประวัติ

### Level 2 - Detailed Processes
แยกรายละเอียดของแต่ละกระบวนการหลัก

## การใช้งาน

1. ไฟล์ `.puml` จะถูกแปลงเป็น PNG อัตโนมัติผ่าน GitHub Actions
2. รูปภาพจะถูกสร้างและ commit กลับเข้า repository
3. ดูรูปภาพได้ที่ไฟล์ PNG ที่ถูกสร้างขึ้น

## ไฟล์ PlantUML

- `dfd-level1-capyadoo.puml` - DFD Level 1
- `dfd-level2-1-user-management.puml` - การจัดการผู้ใช้
- `dfd-level2-2-ocr-system.puml` - ระบบ OCR/Barcode
- `dfd-level2-3-medication.puml` - การจัดการยา
- `dfd-level2-4-notification.puml` - การจัดการแจ้งเตือน
- `dfd-level2-5-history.puml` - บันทึกประวัติ
