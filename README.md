# ▶ PlayFlow

> منصة ترفيهية تفاعلية مثل تيك توك — ولكن بالألعاب المصغرة بدلاً من الفيديو

![PlayFlow Banner](https://img.shields.io/badge/PlayFlow-v1.0%20Beta-00f5d4?style=for-the-badge&logo=gamepad&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-Canvas-f72585?style=flat-square)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-ffd166?style=flat-square)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-Ready-4361ee?style=flat-square)

---

## 🎮 ما هو PlayFlow؟

**PlayFlow** منصة تصفح لا نهائي (Endless Scroll) تعرض ألعاباً مصغرة HTML5 قابلة للعب فوراً، مع محرر كود مدمج لإنشاء ألعابك الخاصة ونشرها.

---

## 📁 هيكل الملفات

```
playflow/
├── index.html       ← شاشة البداية (Splash Screen) + Google Sign-in
├── feed.html        ← الفيد الرئيسي (5 ألعاب قابلة للعب)
├── create.html      ← محرر الكود + Drag & Drop Builder + القوالب
├── profile.html     ← الملف الشخصي + الإنجازات + الأرقام القياسية
├── style.css        ← الستايل المشترك لجميع الصفحات
└── README.md        ← هذا الملف
```

---

## 🕹️ الألعاب المضمنة

| اللعبة | النوع | التحكم |
|--------|-------|--------|
| 🐍 Neon Snake | كلاسيك | ↑↓←→ / WASD / سحب بالأصبع |
| 🧱 Cyber Breakout | أركيد | فأرة / لمس يمين يسار |
| 🔮 Flappy Orb | ردود أفعال | لمس / SPACE |
| 🤖 Pixel Dash | لا نهائي | لمس / SPACE (قفز مزدوج) |
| 🧠 Memory Matrix | ذاكرة | لمس البطاقات |

---

## 🚀 رفع على GitHub Pages — خطوة بخطوة

### الطريقة الأولى: عبر واجهة GitHub

1. افتح [github.com](https://github.com) وسجّل دخولك
2. اضغط **New Repository** (مستودع جديد)
3. اسم المستودع: `playflow` (أو أي اسم تريده)
4. اختر **Public** ✅
5. اضغط **Create repository**
6. اضغط **uploading an existing file**
7. اسحب جميع الملفات الخمسة (`index.html`, `feed.html`, `create.html`, `profile.html`, `style.css`)
8. اكتب في خانة commit: `Initial PlayFlow release 🚀`
9. اضغط **Commit changes**

#### تفعيل GitHub Pages:
1. اذهب إلى **Settings** في المستودع
2. من القائمة الجانبية اختر **Pages**
3. تحت **Source** اختر **Deploy from a branch**
4. Branch: `main` — Folder: `/ (root)`
5. اضغط **Save**
6. انتظر دقيقة ثم ستحصل على رابط مثل:
   ```
   https://yourusername.github.io/playflow/
   ```

---

### الطريقة الثانية: عبر Git CLI

```bash
# 1. أنشئ مجلداً وضع فيه الملفات
mkdir playflow && cd playflow

# 2. ابدأ git
git init
git add .
git commit -m "🚀 Initial PlayFlow release"

# 3. اربط بالمستودع على GitHub
git remote add origin https://github.com/YOUR_USERNAME/playflow.git

# 4. ارفع
git branch -M main
git push -u origin main
```

ثم فعّل GitHub Pages من Settings كما في الطريقة الأولى.

---

## ✨ المزايا

- 🎮 **5 ألعاب قابلة للعب** مباشرة في المتصفح بدون تحميل
- 📱 **تصفح عمودي** بسحب للأعلى/الأسفل مثل TikTok
- 💻 **محرر كود مدمج** يدعم JavaScript مع معاينة حية
- 🎨 **Drag & Drop Builder** لبناء الألعاب بدون كتابة كود
- 📋 **6 قوالب جاهزة** للبدء السريع
- 👤 **صفحة ملف شخصي** مع إنجازات وأرقام قياسية
- ❤️ نظام إعجاب وحفظ ومشاركة
- 🌙 تصميم Dark Mode نيون احترافي
- 📱 متجاوب 100% مع الجوال

---

## 🛠️ التقنيات المستخدمة

- **HTML5 Canvas** — لرسم الألعاب
- **Vanilla JavaScript** — بدون أي مكتبة خارجية
- **CSS3** — متحركات، Glassmorphism، Neon Effects
- **Google Fonts** — Orbitron + Rajdhani
- **Intersection Observer API** — لتشغيل الألعاب عند الظهور
- **localStorage** — لحفظ بيانات المستخدم

---

## 📝 ملاحظات

- الرابط الافتراضي عند فتح الموقع هو `index.html` (شاشة البداية)
- تسجيل الدخول عبر Google هو محاكاة فقط (Demo) — لتفعيله حقيقياً تحتاج Google OAuth Client ID
- بيانات المستخدم تُحفظ في `localStorage` المتصفح فقط

---

## 📄 الرخصة

MIT License — يمكنك استخدامه وتعديله بحرية 🎉

---

<div align="center">
  صُنع بـ ❤️ + ☕ باستخدام HTML5 Canvas & Vanilla JavaScript
  <br>
  <strong>PlayFlow v1.0 Beta</strong>
</div>
