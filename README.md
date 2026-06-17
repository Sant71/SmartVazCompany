<p align="center">
  <img src="assets/cover.png" alt="SmartVaz Irrigation System Banner" width="100%">
</p>

<h1 align="center">🌱 SmartVaz Irrigation System</h1>
<p align="center">
  <em>نظام ري ذكي يعتمد على إنترنت الأشياء (IoT) لترشيد استهلاك المياه وتعزيز الاستدامة البيئية</em>
</p>

<p align="center">
  <!-- شارات الحالة الاحترافية -->
  <img src="https://img.shields.io/badge/version-1.0.0-2ecc71?style=for-the-badge&logo=git" alt="الإصدار">
  <img src="https://img.shields.io/badge/IoT-Enabled-3498db?style=for-the-badge&logo=arduino" alt="IoT">
  <img src="https://img.shields.io/badge/JavaScript-ES6+-f1c40f?style=for-the-badge&logo=javascript" alt="JavaScript">
  <img src="https://img.shields.io/badge/License-MIT-orange?style=for-the-badge" alt="الرخصة">
  <img src="https://img.shields.io/badge/Status-Operational-27ae60?style=for-the-badge" alt="الحالة">
  <img src="https://img.shields.io/badge/Contributions-Welcome-brightgreen?style=for-the-badge" alt="المساهمات">
</p>

---

## 📖 نبذة عن المشروع

يُعد **SmartVaz** نظاماً زراعياً ذكياً يهدف إلى **حل مشكلة هدر المياه** في القطاع الزراعي، حيث يعمل على:

- قياس **رطوبة التربة** و**درجة الحرارة** و**مستوى الماء** لحظياً.
- اتخاذ قرارات الري **تلقائياً** بناءً على خوارزميات ذكية.
- توفير **واجهة تحكم عن بُعد** عبر الويب للمزارعين.
- تقديم **تقارير تحليلية** تساعد في تحسين الإنتاجية.

> 💡 *"زراعة أكثر إنتاجية... بمياه أقل."*

---

## ✨ المميزات الرئيسية

| الميزة | الوصف |
|--------|-------|
| ⏱️ **ري تلقائي** | يعتمد على قراءات المستشعرات لتشغيل المضخة فقط عند الحاجة |
| 📊 **تحليل فوري** | رسوم بيانية تفاعلية تعرض حالة التربة على مدار اليوم |
| 🌐 **تحكم عن بُعد** | لوحة تحكم ويب تعمل على الهواتف والحواسيب |
| 🔔 **تنبيهات ذكية** | إشعارات عند انخفاض الرطوبة أو ارتفاع الحرارة |
| 📈 **توفير المياه** | يقلل الاستهلاك بنسبة تصل إلى **40%** مقارنة بالري التقليدي |
| 🛠️ **وضع يدوي/تلقائي** | مرونة كاملة للمزارع للتدخل اليدوي عند الحاجة |

---

## 🧠 البنية التقنية (Tech Stack)

<div align="center">
  
| الطبقة | التقنيات المستخدمة |
|--------|----------------------|
| **الأجهزة (Hardware)** | Arduino UNO / ESP8266, مستشعر رطوبة (YL-69), مستشعر حرارة (LM35), مضخة مياه, شاشة LCD |
| **البرمجيات (Backend)** | Node.js (محاكاة) أو Firebase (قاعدة البيانات) |
| **الواجهة (Frontend)** | HTML5, CSS3 (Flexbox/Grid), JavaScript (ES6+) |
| **المكتبات** | Chart.js (للرسوم البيانية), Font Awesome (الأيقونات) |
| **بروتوكول الاتصال** | MQTT / Serial Communication (محاكاة) |

</div>

---

## 🖥️ واجهة المستخدم (UI Preview)

<p align="center">
  <img src="assets/ui_dashboard.png" alt="لوحة التحكم" width="45%">
  &nbsp;&nbsp;&nbsp;
  <img src="assets/mobile_view.png" alt="واجهة الجوال" width="25%">
</p>

> *الصور أعلاه توضيحية، يُرجى استبدالها بلقطات شاشة من مشروعك الفعلي.*

---

## 📂 هيكل المشروع (Folder Structure)

```bash
SmartVaz_Irrigation_Sys/
├── 📁 assets/                 # الصور والملفات الثابتة
│   ├── cover.png
│   ├── ui_dashboard.png
│   └── logo.svg
├── 📁 src/                    # الكود المصدري
│   ├── index.html            # صفحة لوحة التحكم
│   ├── style.css             # التنسيقات الاحترافية
│   └── script.js             # منطق العمل والرسوم البيانية
├── 📁 hardware/               # كود الأردوينو (اختياري)
│   └── irrigation.ino
├── 📄 README.md               # هذا الملف
└── 📄 LICENSE                 # ملف الترخيص
