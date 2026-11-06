BOMBAY GUJARAT ROADLINES — Android Studio Project

Yeh APK nahi hai. Yeh Android app ka source project hai jise Android Studio mein build karke APK banayi ja sakti hai.

Build karne ke liye:
1. Computer par Android Studio install karein.
2. Is ZIP ko extract karein.
3. Android Studio > Open > extracted BGR-Android-Project folder select karein.
4. Gradle sync complete hone dein. Android SDK Platform 35 install karna pad sakta hai.
5. Build > Build Bundle(s) / APK(s) > Build APK(s).
6. APK app/build/outputs/apk/debug/app-debug.apk par milegi.

Features in current app: booking entry, customer/truck-owner records, booking-wise payment ledger, partial payments, commission calculation, expenses, reports, CSV export, JSON backup/restore, Hindi/English interface, local offline storage.

Important:
- Is environment mein Android SDK/Gradle installed nahi hai, isliye yahan APK compile ya device-test nahi ki gayi.
- Records isi phone/app ke local storage mein rehte hain. App data clear karne se records delete ho sakte hain. Regular backup rakhein.
- GST fields record-keeping ke liye hain; app GST returns file nahi karti. Tax invoice issue karne se pehle accountant se verify karein.
- Production use se pehle app ko real business data ke saath test karein.
