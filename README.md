# 🌸 MOMDAYS — ของขวัญวันแม่แห่งชาติ 💐

เว็บบอร์ด / เว็บแอปโต้ตอบฉลองวันแม่แห่งชาติ (Mother's Day Gift Web App) ที่ออกแบบในลักษณะ **Decoy Interactive Surprise** (พรีวิวลิงก์แนบเนียน พร้อมเซอร์ไพรส์โต้ตอบสุดอบอุ่นใจ)

---

## 🌟 ฟีเจอร์หลัก (Features)

1. **Decoy Social Link Preview (การพรีวิวลิงก์เนียนตา)**:
   - ตั้งค่า Open Graph metadata (LINE, Facebook, Messenger, Telegram) ให้เหมือนกับลิงก์บทความแนะนำของขวัญ/สูตรอาหาร เพื่อเซอร์ไพรส์ผู้รับเมื่อกดเปิด
2. **Warm Ambient Aesthetics**:
   - ธีมสีอบอุ่น ละมุนตา (Rose Gold, Pearl Cream, Warm Amber, Soft Jasmine White)
   - แสงโคมไฟหัวเตียงสว่างนุ่มนวล พร้อมละอองเกสรดอกมะลิและกลีบดอกไม้ลอยล่อง (Floating Jasmine Petals)
3. **Interactive Candle Light Ignition**:
   - แสดงผลแบบจุดไฟแห่งความรัก และเปิดการ์ดความทรงจำตามจังหวะการเลื่อนสกอร์ (Scroll-driven reveal)
4. **Interactive Love Burst Button (ปุ่มกดบอกรักแม่)**:
   - ปุ่มกดส่งหัวใจและดอกไม้กระจายเต็มหน้าจอ พร้อมตัวนับจำนวนดวงใจ
5. **Background Music Player**:
   - เครื่องเล่นเพลงบรรเลงอะคูสติกผ่อนคลาย เปิด/ปิดได้ตลอดเวลา

---

## 📂 โครงสร้างโปรเจกต์ (Project Structure)

```text
momdays/
├── index.html        # เว็บแอปเดี่ยว (Single-file HTML5/CSS3/JavaScript)
└── README.md         # เอกสารแนะนำโครงการ
```

---

## 🚀 วิธีการเปิดใช้งาน (How to Run)

สามารถเปิดไฟล์ `index.html` ผ่านเว็บเบราว์เซอร์ได้ทันที หรือรันผ่าน Local Server:

```bash
cd /root/ai-workspace/momdays
python3 -m http.server 8090
```

แล้วเปิดเบราว์เซอร์ไปที่ `http://localhost:8090`
