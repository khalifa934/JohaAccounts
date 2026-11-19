# حسابات جحا - مشروع Android

هذا مشروع Android Studio يحوّل ملف HTML الأصلي إلى تطبيق Android يعمل داخل WebView.

## إنشاء APK
1. ثبّت Android Studio على الكمبيوتر.
2. فك ضغط ملف `JohaAccountsAndroid.zip`.
3. من Android Studio اختر **Open** ثم اختر مجلد `JohaAccountsAndroid`.
4. انتظر انتهاء Gradle Sync وثبّت Android SDK Platform 35 إذا طلبه البرنامج.
5. من القائمة اختر **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
6. بعد نجاح البناء اضغط **locate** للوصول إلى ملف APK.

## ملاحظات مهمة
- التطبيق يعمل دون اتصال بالإنترنت.
- البيانات محفوظة محليًا داخل مساحة التطبيق باستخدام localStorage في WebView.
- حذف التطبيق أو مسح بياناته قد يؤدي إلى فقد البيانات؛ استخدم صفحة النسخ الاحتياطي بانتظام.
- هذا مجلد مشروع جاهز للبناء، وليس ملف APK مبنيًا بالفعل.
