# 🚀 Competency 2026: Interactive Learning & Exam Simulator

เว็บแอปพลิเคชันสำหรับการเรียนรู้ ติวเข้ม และจำลองการทดสอบ **Competency ประจำปี 2026** (ครอบคลุมทั้ง 15 ทักษะตามมาตรฐาน CoE)

---

## 🌟 ฟีเจอร์หลัก (Key Features)

1. **📚 Study Notes & Fullscreen Study Reader (หนังสือติวเข้มเสมือนจริง)**
   * รวบรวมสรุป 15 ทักษะใน 6 หมวดหมู่ (Architecture, Engineering, DevOps/Cloud, Security, Problem Solving, AI Prompt)
   * หน้าต่างอ่านหนังสือติวเข้มแบบ Fullscreen Reader พร้อมสารบัญ (TOC), Reading Progress Bar, และ Checkpoint Mini-Quiz
   * บทเรียนติวเข้ม **Microservices Architecture ฉบับสมบูรณ์ 6 บทเรียน** อิงมาตรฐานสากล (HackerRank, System Design Interview)

2. **📝 Multiple Choice Exam (ระบบจำลองสอบ 20 ข้อ)**
   * ข้อสอบวัดระดับตามสถานการณ์งานจริง (ทั้งแบบ Single-select และ Multi-select)
   * 2 โหมดการใช้งาน: *ซ้อมทำทีละข้อ (ดูเฉลยทันที)* และ *จำลองสอบจริง (จับเวลา 45 นาที)*

3. **💻 In-Browser Coding Lab (ห้องสอบเขียนโค้ด)**
   * โครงสร้างโจทย์ Function Skeleton สไตล์ HackerRank
   * รัน Unit Tests แบบเรียลไทม์ในเบราว์เซอร์ พร้อมวัด Execution Time
   * ปุ่ม `💡 ดูเฉลย (Solution)` พร้อมคำอธิบาย Clean Code & Algorithm Complexity

4. **🤖 AI & Prompt Context Optimization Simulator**
   * จำลอง Incident Ticket จริงบน Production 4 สถานการณ์
   * ระบบให้คะแนนอัตโนมัติตาม Rubric 100 คะแนน (Context, Noise Reduction, Guardrails, Output Format)

5. **📊 Real-Time Dashboard**
   * ติดตามคะแนนแยกตาม 6 หมวด Competency
   * บันทึกสถานะอัตโนมัติลงใน `LocalStorage`

---

## 🚀 วิธีการใช้งาน (Getting Started)

เนื่องจากเว็บนี้พัฒนาด้วยสถาปัตยกรรม **Standalone Single-File Web App (HTML5 + Tailwind CSS + Vanilla JS)**:
* **ไม่ต้องติดตั้ง Dependencies หรือรัน Server**
* ดับเบิ้ลคลิกเปิดไฟล์ `index.html` ด้วย Web Browser ใดๆ (Chrome, Safari, Edge, Firefox) ก็สามารถใช้งานได้ทันที!

---

## 🌐 ใช้งานผ่าน GitHub Pages
สามารถนำขึ้น GitHub แล้วเปิด **Settings > Pages > Deploy from a branch (main / root)** เพื่อให้คนอื่นเข้าใช้งานผ่านลิงก์เว็บออนไลน์ได้ทันที
