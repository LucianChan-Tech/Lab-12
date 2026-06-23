# Lab 12 Final Project

> **ภาษาอื่น ๆ：** [🇬🇧 English](README.md) | [🇨🇳 中文](README.zh.md)

---

## ข้อมูลส่วนตัว

| รายการ | รายละเอียด |
|--------|------------|
| **ชื่อ** | เฉิน เหวินอี้ (Lucian Chen) |
| **รหัสนักศึกษา** | 20242178 |
| **ชั้นเรียน** | 241 (ชั้นเรียนแลกเปลี่ยนนานาชาติ) |
| **สาขาวิชา** | วิศวกรรมซอฟต์แวร์ |
| **มหาวิทยาลัย** | North Minzu University & Chiang Mai University |

## รูปถ่าย

![รูปของฉัน](website/Myself.jpg)

## ที่อยู่ของแอปพลิเคชัน

| แอปพลิเคชัน | URL |
|-------------|-----|
| เว็บไซต์ส่วนตัว | http://98.89.48.43:8080 |
| แอปพลิเคชัน Todo | http://98.89.48.43:8081 |

## โครงสร้างโปรเจค

```
.
├── .github/workflows/
│   └── deploy.yml          # GitHub Actions CI/CD
├── website/                 # เว็บไซต์ส่วนตัว
│   ├── Dockerfile
│   ├── index.html
│   ├── profile.html
│   ├── CAMTinfo.html
│   ├── Myself.jpg
│   ├── CAMT.jpeg
│   └── NMU.png
├── todo-app/                # แอปพลิเคชัน Todo Vanilla JS
│   ├── Dockerfile
│   └── index.html
├── docker-compose.yml       # การจัดการหลายคอนเทนเนอร์
├── README.md                # English
├── README.zh.md             # 中文
└── README.th.md             # ภาษาไทย
```

## การติดตั้ง

โปรเจคนี้ถูกติดตั้งบน **AWS EC2** โดยใช้ Docker Compose
แอปพลิเคชันทั้งสองถูกสร้างและติดตั้งบนเซิร์ฟเวอร์เดียวกันผ่าน GitHub Actions CI/CD

---

_อัปเดตล่าสุด: 23 มิถุนายน 2026_
