<p align="center">
  <img src="assets/ofa_blue_icon.svg" width="128" height="128" alt="OFA Blue Icon" />
</p>

<h1 align="center">OFA Blue</h1>

<p align="center">
  <strong>بث صوت الأفلام والأغاني لعدة سماعات بلوتوث معاً عبر الـ Hotspot بدون إنترنت</strong><br/>
  <strong>Stream local movies & music to multiple Bluetooth headphones over local Wi-Fi / Hotspot — no internet required.</strong>
</p>

---

## 📥 التحميل | Download
- **Android APK (v1.2.0 — Android 10 to Android 15):** [`OFA-Blue-v1.2.0.apk`](OFA-Blue-v1.2.0.apk)

---

## 🆕 الجديد في الإصدار v1.2.0 | What's New in v1.2.0

### 🇪🇬 العربية
- **تحديث تلقائي من داخل التطبيق بضغطة واحدة (In-App Auto-Updates):** يفحص التطبيق التحديثات الجديدة تلقائياً من GitHub Releases، ويعرض بانر التحديث مع شريط تقدم التنزيل المباشر وزر تثبيت فوري بدون إعادة تحميل يدوي.
- **حفظ مؤقت ذكي للـ APK (Single-Download Cache):** عند طلب إذن التثبيت من مصادر غير معروفة، يُستأنف التثبيت تلقائياً من النسخة المحمّلة دون إعادة تنزيل الملف مرة أخرى.
- **حماية وتحقق أمني كامل:** تحقق من رابط GitHub الرسمي، حجم الملف، سلامة الحزمة (`packageName` و `versionCode`)، وتنظيف تلقائي لملفات التحديث القديمة بعد التثبيت.

### 🇬🇧 English
- **One-Tap In-App Auto-Updates:** Automatically checks GitHub Releases on startup (silently offline-safe on Hotspot) and displays a bilingual update banner with live download progress and one-tap install.
- **Single-Download APK Cache & Auto-Resume:** Caches verified APKs in private app cache so granting "Install unknown apps" automatically resumes installation without ever re-downloading.
- **Hardened Update Security:** Strict HTTPS & GitHub CDN redirect allowlist, bounded download size verification, package/version integrity checks, and automatic post-install cache cleanup.

---

## 🇪🇬 ما هو تطبيق OFA Blue؟ (العربية)

**One For ALl Blue - OFA Blue** هو تطبيق أندرويد يتيح لك تشغيل فيلم أو أغنية من أي مشغّل خارجي (مثل **VLC** أو **MX Player** أو مشغل الأغاني) وبث الصوت لايف إلى أكثر من موبايل متصلين على نفس الـ **Hotspot** أو الـ **Wi-Fi**، ليسمع كل شخص عبر سماعته البلوتوث (مثل سماعات **Oraimo** وغيرها) في نفس الوقت **بدون استهلاك إنترنت**.

### ✨ المميزات
- **يعمل بدون إنترنت:** يعتمد على شبكة الـ Hotspot أو الـ Wi-Fi المحلية فقط.
- **متوافق مع التطبيقات الخارجية:** شغّل ملفاتك المحمّلة من VLC أو MX Player أو أي مشغّل موسيقى محلي.
- **اكتشاف تلقائي للأجهزة:** يتعرف على الموبايل الباث تلقائياً (`NSD + UDP Broadcast`) مع إمكانية إدخال الـ IP يدوياً كخيار احتياطي.
- **معايرة تزامن فورية (Live Sync Offset Slider):** شريط تحكم دقيق من `-50ms` إلى `+400ms` بخطوات `5ms` لموازنة فرق التأخير بين سماعات البلوتوث المختلفة.
- **تحديثات تلقائية داخل التطبيق:** تنزيل وتثبيت الإصدارات الجديدة مباشرة من التطبيق بضغطة واحدة.
- **متوافق مع Android 14 و Android 15:** يدعم خدمات الخلفية (`MediaProjection` / `MediaPlayback`) وأيقونة Adaptive + Themed Icon.

### 📱 طريقة الاستخدام
1. ثبّت [`OFA-Blue-v1.2.0.apk`](OFA-Blue-v1.2.0.apk) على الموبايل الرئيسي (**Host**) والموبايلات المستقبلة (**Join**).
2. افتح **Hotspot** من الموبايل الرئيسي ووصّل باقي الموبايلات عليه، ووصّل كل موبايل بسماعته البلوتوث.
3. على الموبايل الرئيسي: اختر **Host • بث الصوت**، اضغط بدء البث، ووافق على صلاحية التقاط الصوت، ثم افتح الفيديو أو الأغنية في مشغّلك المفضل.
4. على الموبايلات التانية: اختر **Join • استقبال الصوت** واضغط على اسم الموبايل الرئيسي.
5. عدّل شريط **Sync Offset** إذا احتجت لضبط التزامن بين السماعات.

> **ملاحظة:** تطبيقات البث المحمية بـ DRM (مثل Netflix و Shahid و Spotify) تمنع التقاط الصوت على مستوى نظام أندرويد، لذا صُمم التطبيق خصيصاً للميديا المحمّلة ومشغلات الفيديو والموسيقى المحلية.

---

## 🇬🇧 What is OFA Blue? (English)

**One For ALl Blue - OFA Blue** is an Android application that captures audio from your favorite external local media player (**VLC**, **MX Player**, local music players) and broadcasts it live over a local **Wi-Fi / Hotspot** network to multiple Android devices — letting everyone listen simultaneously through their own Bluetooth earbuds (such as **Oraimo** TWS) with **zero internet usage**.

### ✨ Features
- **100% Offline Local Streaming:** Works over Android Hotspot or local Wi-Fi with zero data consumption.
- **External Media Player Friendly:** Play downloaded movies or songs in VLC, MX Player, or any local music app while OFA Blue streams in the background.
- **Auto-Discovery + Manual IP Fallback:** Finds the Host automatically via `NsdManager` + UDP Broadcast, with a manual IP option for strict hotspot setups.
- **Live Sync Offset Calibration:** Real-time `-50ms` to `+400ms` slider (in `5ms` steps) with live buffer telemetry and automatic drift regulation to match different Bluetooth earbud latencies.
- **In-App Auto-Updates:** One-tap update check, verified download, and automatic install directly from GitHub Releases.
- **Android 14 & 15 Ready:** Fully compliant with `FOREGROUND_SERVICE_MEDIA_PROJECTION` and `FOREGROUND_SERVICE_MEDIA_PLAYBACK`.

### 📱 How to Use
1. Install [`OFA-Blue-v1.2.0.apk`](OFA-Blue-v1.2.0.apk) on the **Host** phone and all **Listener (Join)** phones.
2. Enable **Hotspot** on the Host phone, connect the other phones to it, and pair each phone with its Bluetooth headphones.
3. On the Host phone: open **Host** mode, tap **Start Broadcast**, grant permissions, and play your downloaded movie/song in your external player.
4. On Listener phones: open **Join** mode and tap the discovered Host.
5. Fine-tune the **Sync Offset** slider if needed to align Bluetooth latency across headsets.

> **Note:** DRM-protected streaming apps (e.g., Netflix, Shahid, Spotify) block Android's `AudioPlaybackCapture` at the OS level and output silence. OFA Blue is built for downloaded local media and non-DRM apps.
