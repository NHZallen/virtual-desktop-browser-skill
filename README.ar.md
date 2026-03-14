# Virtual Desktop Browser (العربية)

مهارة لـ OpenClaw/الوكلاء لتشغيل **Chromium بوضع غير headless** على **شاشة Xvfb افتراضية (ثابتة 1200x720x24)** مع أتمتة تشبه سلوك الإنسان باستخدام PyAutoGUI.

## الميزات
- تشغيل/إيقاف Xvfb + Chromium
- نقر الفأرة، الكتابة، اختصارات لوحة المفاتيح
- التمرير، لقطة شاشة، قراءة لون البكسل
- مطابقة الصور (OpenCV)
- تفعيل النافذة

## متطلبات النظام
```bash
sudo apt-get update
sudo apt-get install -y xvfb chromium-browser \
  libnss3 libgconf-2-4 libxss1 libasound2 \
  libatk1.0-0 libatk-bridge2.0-0 libcups2 \
  libdrm2 libgbm1 libgtk-3-0 libxshmfence1 x11-utils
```

## متطلبات بايثون
```bash
pip install -r requirements.txt
```

## المؤلف
المنشئ: **Allen Niu**
