# 🚗 carParkAi - ระบบตรวจจับพื้นที่จอดรถอัจฉริยะ

[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green)](https://opencv.org/)

**carParkAi** เป็นโปรเจกต์ที่ใช้ Image Processing และ Machine Learning ในการตรวจจับว่าพื้นที่จอดรถในลานจอดรถนั้น "ว่าง" หรือ "ไม่ว่าง" แบบ Real-time ผ่านวิดีโอหรือกล้องวงจรปิด เพื่อช่วยอำนวยความสะดวกในการจัดการที่จอดรถ

---

## ✨ ฟีเจอร์หลัก (Features)
- ✅ **Real-time Detection:** ตรวจจับสถานะที่จอดรถได้ทันทีจากไฟล์วิดีโอหรือกล้อง Live Stream
- ✅ **Parking Slot Marking:** สามารถกำหนดขอบเขต (ROI) ของแต่ละช่องจอดได้เอง
- ✅ **Status Counting:** แสดงจำนวนที่ว่างและที่จอดทั้งหมดบนหน้าจอ
- ✅ **Visual Indicators:** แสดงกรอบสีเขียวเมื่อว่าง และสีแดงเมื่อมีรถจอด

---

## 🛠 เทคโนโลยีที่ใช้ (Tech Stack)
- **Language:** Python
- **Libraries:** - `OpenCV` (สำหรับประมวลผลภาพ)
  - `NumPy` (สำหรับการคำนวณ Matrix)
  - `Pickle` (สำหรับบันทึกตำแหน่งช่องจอด)

---

## 🚀 การติดตั้งและใช้งาน

### 1. เตรียมสภาพแวดล้อม
คัดลอกโปรเจกต์และติดตั้ง Library ที่จำเป็น:
```bash
git clone [https://github.com/maethassaeyo/carParkAi.git](https://github.com/maethassaeyo/carParkAi.git)
cd carParkAi
pip install opencv-python numpy flask
