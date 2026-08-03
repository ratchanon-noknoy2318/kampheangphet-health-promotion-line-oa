# LINE OA ANC Integration

ระบบเชื่อมต่อ LINE Official Account (OA) สำหรับการฝากครรภ์ (ANC)  
รองรับการแจ้งเตือนนัดหมาย, การบันทึกข้อมูล, และการส่ง Flex Message ให้ผู้ใช้

## Features
- แจ้งเตือนนัด ANC ผ่าน LINE OA
- ส่ง Flex Message (เช่น ตารางนัด, คำแนะนำสุขภาพแม่และเด็ก)
- บันทึกข้อมูลลง Google Sheets หรือ HIS/HOSxP
- รองรับ push และ reply message

## Requirements
- Node.js (latest)
- LINE Messaging API key
- Google Sheets API key
- Hosting: Vercel, Netlify หรือ server โรงพยาบาล

## How to Use
1. Clone repo  
   ```bash
   git clone https://github.com/ratchanon-noknoy2318/line_oa_anc.git
   npm install
   npm run dev
   
2. สร้างไฟล์ .env
 ```bash
LINE_CHANNEL_ACCESS_TOKEN=your_line_channel_access_token
LINE_CHANNEL_SECRET=your_line_channel_secret
GOOGLE_SHEETS_API_KEY=your_google_sheets_api_key
PORT=3000
 ```

---

## ผู้พัฒนา (Author)

**ชื่อ:** นายรัชชานนท์ นกน้อย  
**ตำแหน่ง:** นักวิชาการคอมพิวเตอร์  
**GitHub:** [ratchanon-noknoy2318](https://github.com/ratchanon-noknoy2318)  
**LinkedIn:** [linkedin.com/in/ratchanon-noknoy](https://linkedin.com/in/ratchanon-noknoy)


