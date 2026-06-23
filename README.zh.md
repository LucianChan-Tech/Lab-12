# Lab 12 Final Project

> **其他语言版本：** [🇬🇧 English](README.md) | [🇹🇭 ภาษาไทย](README.th.md)

---

## 个人信息

| 项目 | 内容 |
|------|------|
| **姓名** | 陈炆熠 (Lucian Chen) |
| **学号** | 20242178 |
| **班级** | 241班（国际交流班） |
| **专业** | 软件工程 |
| **学校** | 北方民族大学 & 清迈大学 |

## 照片

![本人照片](website/Myself.jpg)

## 应用地址

| 应用 | 链接 |
|------|------|
| 个人网站 | http://98.89.48.43:8080 |
| Todo 应用 | http://98.89.48.43:8081 |

## 项目结构

```
.
├── .github/workflows/
│   └── deploy.yml          # GitHub Actions 自动部署
├── website/                 # 个人网站
│   ├── Dockerfile
│   ├── index.html
│   ├── profile.html
│   ├── CAMTinfo.html
│   ├── Myself.jpg
│   ├── CAMT.jpeg
│   └── NMU.png
├── todo-app/                # Vanilla JS Todo 应用
│   ├── Dockerfile
│   └── index.html
├── docker-compose.yml       # 多容器编排
├── README.md                # English
├── README.zh.md             # 中文
└── README.th.md             # ภาษาไทย
```

## 部署说明

本项目部署在 **AWS EC2** 上，使用 Docker Compose 编排。
两个应用通过 GitHub Actions CI/CD 自动构建并部署在同一台服务器上。

---

_最后验证：2026年6月23日_
