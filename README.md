# 🛡️ AKM Liquid Labs — Privacy Policies Portal
### البوابة المركزية لسياسات الخصوصية لتطبيقات أندرويد

مستودع رسمي مخصص لاستضافة سياسات الخصوصية لجميع تطبيقات نظام أندرويد المطورة بواسطة **AKM Liquid Labs** (Developer: `ayman3340`).
تم إعداد هذا المستودع ليكون متوافقاً 100% مع شروط وسياسات متجر **Google Play Console** ولوائح **GDPR** و **COPPA**.

---

## 🌐 الروابط الحية المباشرة (Live URLs for Google Play Console)

عند إدخال رابط سياسة الخصوصية في **Google Play Console**، استخدم الروابط التالية:

| التطبيق (Application) | معرف الحزمة (Package ID) | الرابط المباشر لـ Google Play | الحالة |
| :--- | :--- | :--- | :--- |
| **I'm up! (أنا مستيقظ)** | `com.akmliquidlabs.imup` | `https://ayman3340.github.io/privacy-policies/im-up.html` | ✅ معتمد ونشط |
| **رابط احتياطي لـ I'm up** | `com.akmliquidlabs.imup` | `https://ayman3340.github.io/privacy-policies/privacy_policy.html` | ✅ متوفر |
| **البوابة الرئيسية لجميع التطبيقات** | كل التطبيقات | `https://ayman3340.github.io/privacy-policies/` | 🏛️ Hub |

---

## 📁 هيكلية المستودع (Repository Structure)

```text
privacy-policies/
├── index.html            # البوابة الرئيسية لسياسات الخصوصية لكافة التطبيقات
├── im-up.html            # سياسة الخصوصية التفصيلية لتطبيق I'm up! (ثنائية اللغة عربي/إنجليزي)
├── privacy_policy.html   # نسخة متطابقة لضمان عمل أي رابط مباشر قديم
├── template.html         # قالب جاهز لإنشاء سياسة خصوصية لأي تطبيق أندرويد جديد مستقبلاً
├── .nojekyll             # لتعطيل معالجة Jekyll وضمان تقديم ملفات HTML النقية
└── README.md             # الدليل التوثيقي وروابط Google Play Console
```

---

## ✨ مزايا السياسات المتضمنة (Policy Highlights)

- 🔒 **Zero-Cloud Architecture:** توثيق كامل لعدم إرسال أو تخزين أي بيانات في أي خوادم خارجية.
- ⚡ **Exact Alarm Compliance:** تبرير تقني رسمي ومباشر لأذونات `SCHEDULE_EXACT_ALARM` و `USE_EXACT_ALARM` وفق متطلبات أندرويد 14 و 15.
- 📱 **Full-Screen Intent:** تبرير إذن `USE_FULL_SCREEN_INTENT` لعرض المنبه فوق شاشة القفل.
- 🚫 **No Ads & No Tracking:** خلو التطبيق من أي حزم تتبع خارجية (No AdMob, No Facebook SDK, No Firebase Analytics).
- 👶 **COPPA & GDPR-K:** تأكيد الامتثال الكامل لسياسات حماية الأطفال والقصّر لعدم جمع أي معلومات شخصية.
- 🌐 **Bilingual (عربي / English):** زر تبديل فوري بين العربية والإنجليزية وخيار طباعة كملف PDF.

---

## 🚀 كيفية إضافة سياسة خصوصية لتطبيق جديد (Adding a New App)

1. انسخ ملف `template.html` وأعد تسميته باسم تطبيقك الجديد (مثال: `my-new-app.html`).
2. افتح الملف وقم بتعديل اسم التطبيق، معرف الحزمة (`Package ID`)، وأي أذونات خاصة به.
3. أضف بطاقة للتطبيق الجديد في ملف `index.html`.
4. ارفع التغييرات:
   ```bash
   git add .
   git commit -m "feat: add privacy policy for My New App"
   git push
   ```
5. سيصبح الرابط الفوري لتطبيقك متاحاً على:
   `https://ayman3340.github.io/privacy-policies/my-new-app.html`

---

## 👨‍💻 المطور وبيانات الاتصال

- **المطور:** AKM Liquid Labs
- **حساب GitHub:** [@ayman3340](https://github.com/ayman3340)
- **مستودع كود تطبيق I'm up!:** [ayman3340/Alarm](https://github.com/ayman3340/Alarm)
- **الاستفسارات القانونية والتقنية:** [فتح Issue على المستودع](https://github.com/ayman3340/privacy-policies/issues)
