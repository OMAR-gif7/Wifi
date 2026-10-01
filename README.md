# WiFi Usage Tester (Phase 1)

نسخة اختبار للتأكد أن `NetworkStatsManager` يعمل على Android 15 / Realme Note 50.

## الوظائف
- فحص صلاحية Usage Access + زر لفتح إعداداتها
- قراءة استهلاك Wi-Fi للجهاز عبر `querySummaryForDevice(NETWORK_TYPE_WIFI)`
- عرض Download / Upload / Total
- تحديد فترة زمنية (تاريخ بداية / نهاية)
- عرض الأخطاء بوضوح
- عرض معلومات الجهاز (لتشخيص Realme UI)

## البناء
يُبنى تلقائيًا عبر GitHub Actions (`.github/workflows/build.yml`) ويُرفع الـ APK كـ Artifact.
لا حاجة لـ Android Studio أو Gradle Wrapper محليًا.
