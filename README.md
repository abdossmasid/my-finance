# مالي — لوحة التحكم المالي

تطبيق PWA لتتبع الدخل والمصاريف، يعمل offline ويمكن تثبيته على الشاشة الرئيسية.

---

## 🚀 رفع المشروع على GitHub + نشره

### الخطوة 1 — إنشاء Repository

1. اذهب إلى [github.com/new](https://github.com/new)
2. اختر اسماً مثل `mali-finance`
3. اتركه **Public**
4. لا تضف README (المشروع عنده ملف)
5. اضغط **Create repository**

---

### الخطوة 2 — رفع الملفات

افتح Terminal/Command Prompt داخل مجلد المشروع:

```bash
git init
git add .
git commit -m "initial: mali finance PWA"
git branch -M main
git remote add origin https://github.com/USERNAME/mali-finance.git
git push -u origin main
```

> استبدل `USERNAME` باسم حسابك على GitHub

---

### الخطوة 3 — تفعيل GitHub Pages

1. افتح الـ Repository على GitHub
2. اذهب إلى **Settings → Pages**
3. تحت **Source** اختر: **GitHub Actions**
4. احفظ

GitHub Actions سينشر التطبيق تلقائياً عند كل `push` على main.

رابط التطبيق سيكون:
```
https://USERNAME.github.io/mali-finance/
```

---

### الخطوة 4 — إضافة أيقونة التطبيق

ضع ملفين داخل مجلد `public/`:
- `icon-192.png` (192×192 px)
- `icon-512.png` (512×512 px)

يمكن إنشاؤها مجاناً على [favicon.io](https://favicon.io) أو [realfavicongenerator.net](https://realfavicongenerator.net)

---

## 📲 تثبيت كـ PWA

### على Android (Chrome):
- افتح الرابط في Chrome
- ستظهر نافذة "إضافة إلى الشاشة الرئيسية"
- أو: القائمة (⋮) → **تثبيت التطبيق**

### على iPhone (Safari):
- افتح الرابط في Safari
- اضغط زر **المشاركة** (⬆)
- اختر **إضافة إلى الشاشة الرئيسية**

---

## ✨ الميزات

- ✅ تسجيل الدخل والمصاريف مع تاريخ تلقائي
- ✅ التنقل بين الأيام (الرجوع لأمس وما قبله)
- ✅ ملخص شهري تلقائي (KPIs)
- ✅ سجل كامل مع تجميع حسب التاريخ
- ✅ خطة توزيع الدخل الشهري
- ✅ يعمل بدون إنترنت (Offline)
- ✅ قابل للتثبيت كتطبيق PWA
- ✅ واجهة عربية كاملة

---

## 🛠 تحديث المشروع

```bash
git add .
git commit -m "update: وصف التعديل"
git push
```
GitHub Pages يتحدث تلقائياً خلال دقيقة.
