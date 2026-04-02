# ⌨️ Code Exporter — محوّل الأكواد

> Convert code to downloadable files with GitHub support, offline PWA, and bilingual UI (Arabic / English).
> أداة ويب لتحويل الأكواد البرمجية إلى ملفات قابلة للتنزيل، مع دعم PWA للعمل بدون إنترنت وواجهة ثنائية اللغة.

[![PWA](https://img.shields.io/badge/PWA-Ready-d4570a?style=flat-square)](https://web.dev/pwa)
[![Offline](https://img.shields.io/badge/Offline-Supported-2e7d32?style=flat-square)](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps)
[![Bilingual](https://img.shields.io/badge/UI-AR%20%2F%20EN-1a5fb4?style=flat-square)](#)
[![License](https://img.shields.io/badge/License-MIT-555?style=flat-square)](LICENSE)

---

## 🌐 Live Demo

**[yoor77.github.io/Codex](https://yoor77.github.io/Codex/)**

---

## ✨ Features — المميزات

| Feature | الميزة |
|---------|--------|
| Code editor with line numbers | محرر كود مع ترقيم الأسطر |
| 15 programming languages | 15 لغة برمجية |
| Download files instantly | تحميل الملفات فوراً |
| Copy code with one tap | نسخ الكود بنقرة واحدة |
| Push to GitHub guide | دليل الرفع على GitHub |
| Import & extract code from files | استيراد واستخراج الكود من الملفات |
| Syntax highlighting | تمييز الصيغة بالألوان |
| Search in code | البحث في الكود |
| Auto-save up to 50 files | حفظ تلقائي لـ 50 ملف |
| **Bilingual UI (AR / EN)** | **واجهة ثنائية اللغة** |
| **Full PWA — works offline** | **PWA كامل — يعمل بدون إنترنت** |

---

## 🚀 Getting Started — البدء

### Open directly — فتح مباشر
```
Open index.html in any modern browser
افتح index.html في أي متصفح حديث
```

### Local server (required for PWA) — خادم محلي
```bash
# Python
python3 -m http.server 8000

# Node.js
npx serve .
```
Then open: `http://localhost:8000`

### Install as PWA — التثبيت كتطبيق
After opening the site, tap **"Install"** / **"تثبيت"** in the header or browser prompt.

---

## 📁 File Structure — هيكل الملفات

```
code-exporter/
├── index.html       # Full app (HTML + CSS + JS + i18n)
├── manifest.json    # PWA config
├── sw.js            # Service Worker (offline support)
├── icon-72.png
├── icon-96.png
├── icon-128.png
├── icon-144.png
├── icon-152.png
├── icon-192.png
├── icon-384.png
├── icon-512.png
└── README.md
```

---

## 🌐 Deploy to GitHub Pages

1. Upload all files to a GitHub repository
2. Go to **Settings → Pages → Branch: main → / (root) → Save**
3. Wait 1-2 minutes, then visit your site at:
   `https://USERNAME.github.io/REPO/`

---

## 🛠️ Tech Stack

| Tech | Usage |
|------|-------|
| HTML5 / CSS3 / Vanilla JS | Full app, no frameworks |
| Service Worker API | Offline caching |
| Web App Manifest | PWA installation |
| localStorage | Save files locally |
| Blob / FileReader API | Download & import files |
| Cairo + IBM Plex Mono | Fonts |

---

## 📄 License

MIT — Use, modify, and distribute freely.
