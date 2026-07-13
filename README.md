# نظام إدارة الطلاب - Student Management System

تطبيق Flutter متكامل لإدارة بيانات الطلاب باستخدام قاعدة بيانات SQLite محلية.

## المميزات
- إضافة وتعديل وحذف بيانات الطلاب.
- بحث متقدم بالاسم أو رقم الهوية.
- تصدير قائمة الطلاب إلى ملف PDF.
- نظام نسخ احتياطي واستعادة لقاعدة البيانات.
- واجهة مستخدم باللغة العربية (RTL).

## متطلبات التشغيل
- Flutter SDK (الإصدار 3.0.0 أو أحدث).
- Android Studio أو VS Code.

## كيفية بناء APK
1. تأكد من تثبيت Flutter على جهازك.
2. قم بتحميل المشروع أو عمل `git clone`.
3. افتح المجلد في الطرفية (Terminal).
4. قم بتشغيل الأمر:
   ```bash
   flutter pub get
   ```
5. لبناء ملف APK، قم بتشغيل الأمر:
   ```bash
   flutter build apk --release
   ```
6. ستجد ملف الـ APK الناتج في المسار:
   `build/app/outputs/flutter-apk/app-release.apk`

## ملاحظة لمستخدمي GitHub
لرفع المشروع على GitHub:
1. أنشئ مستودعاً جديداً على GitHub.
2. اتبع الأوامر التالية في مجلد المشروع:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin [رابط_المستودع_الخاص_بك]
   git push -u origin main
   ```
