# 🌸 MOMDAYS — ของขวัญวันแม่แห่งชาติ 💐

เว็บบอร์ด / เว็บแอปโต้ตอบฉลองวันแม่แห่งชาติ (Mother's Day Gift Web App) ที่ออกแบบในลักษณะ **Decoy Interactive Surprise** (พรีวิวลิงก์แนบเนียน พร้อมเซอร์ไพรส์โต้ตอบสุดอบอุ่นใจ)

---

## 🎨 เวอร์ชันที่พร้อมใช้งาน (Available Versions)

1. **[`index.html`](file:///root/ai-workspace/momdays/index.html)** — **Dark/Warm Evening Theme (อบอุ่น โรแมนติก เป็นกันเอง)**:
   - ธีมสีโรสโกลด์ นุ่มนวล แสงโคมไฟหัวเตียงอบอุ่น
   - เหมาะสำหรับส่งตรงให้คุณแม่ในบรรยากาศผ่อนคลายและประทับใจ
2. **[`reserved.html`](file:///root/ai-workspace/momdays/reserved.html)** — **Light/Semi-Formal Honorary Theme (สว่าง ทรงเกียรติ กึ่งทางการ)**:
   - ธีมสีครีมสว่าง ทองอร่าม ละอองมะลิสีขาวบริสุทธิ์
   - สารวันแม่แห่งชาติ กลอนวันแม่ และการนอบน้อมมอบพวงมาลัยดอกมะลิกิตติมศักดิ์

---

## 🌟 ฟีเจอร์หลัก (Features)

- **Decoy Social Link Preview (การพรีวิวลิงก์เนียนตา)**:
  - ตั้งค่า Open Graph metadata (LINE, Facebook, Messenger, Telegram) ให้เหมือนกับลิงก์บทความแนะนำของขวัญ/ความหมายวันแม่ เพื่อเนียนตาเวลาแชร์ลิงก์ให้คุณแม่หรือในไลน์กลุ่ม
- **Ambient Lighting & Floating Petals**:
  - เอฟเฟกต์ละอองเกสรดอกมะลิและกลีบดอกไม้ลอยล่อง (Floating Jasmine Petals)
- **Interactive Scroll & Candle/Emblem Reveal**:
  - แสดงผลและเปิดการ์ดความทรงจำตามจังหวะการเลื่อนสกอร์ (Scroll-driven reveal)
- **Interactive Garland & Love Offering (ปุ่มกราบมอบพวงมาลัย/บอกรักคุณแม่)**:
  - ปุ่มกดส่งหัวใจและดอกมะลิกระจายเต็มหน้าจอ พร้อมตัวนับจำนวน
- **Background Music Player**:
  - เครื่องเล่นเพลงบรรเลงผ่อนคลาย เปิด/ปิดได้ตลอดเวลา

---

## 🚀 วิธีการเปิดใช้งาน (How to Run)

สามารถเปิดไฟล์ `index.html` หรือ `reserved.html` ผ่านเว็บเบราว์เซอร์ได้ทันที หรือรันผ่าน Local Server:

```bash
cd /root/ai-workspace/momdays
python3 -m http.server 8090
```

- **หน้าหลัก (Dark/Warm Theme):** `http://localhost:8090/`
- **หน้าทางการ (Light/Formal Theme):** `http://localhost:8090/reserved.html`
