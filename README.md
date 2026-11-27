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
- **Android APK (v1.3.0 — Android 10 to Android 15):** [`OFA-Blue-v1.3.0.apk`](OFA-Blue-v1.3.0.apk)

---

## 🆕 الجديد في الإصدار v1.3.0 | What's New in v1.3.0

### 🇪🇬 العربية
- **نقاء صوت استوديو على سماعات البلوتوث (Studio-Grade Bluetooth A2DP):** مسار تشغيل جديد عبر `NormalMixer` مع معالج `Polyphase Sinc Resampler` وتخزين مؤقت آمن ضد النبضات المتقطعة للقضاء تماماً على الشوشرة والطقطقة (Static/Crackling).
- **تصحيح أخطاء الشبكة بدون فقدان (`Systematic K = 4 XOR Parity FEC`):** استعادة حزم الـ Wi-Fi المفقودة بنسبة 100% مطابقة للأصل (`Bit-for-Bit Lossless`) دون أي تقطيع مسموع.
- **معالجة انسيابية للفقدان والتأخير (`Pitch-Matched PLC` + `Raised-Cosine Crossfade`):** دمج صوتي ناعم بمدى `2.5ms` مع مهلة أمان `40ms Time-Slip Underrun Grace` لمنع الطقات والانقطاعات المفاجئة.
- **عزل مسار التقاط الصوت عن الشبكة في الـ Host:** ذاكرة التقاط محمية بسعة `500ms` تمنع الفيضان، مع أولوية شبكة `WMM AC_VI QoS` وإشارات اكتشاف ذكية متكيفة لتقليل التداخل اللاسلكي.
- **💡 ملاحظة هامة:** يُنصح بتحديث كلٍ من موبايل الـ **Host** وموبايلات الاستماع (**Join**) إلى الإصدار `v1.3.0` لتفعيل استعادة الحزم بدون فقدان (`FEC`) بالكامل — ويمكن لمستخدمي `v1.2.0` التحديث مباشرة بضغطة واحدة من داخل التطبيق!

### 🇬🇧 English
- **Studio-Grade Bluetooth A2DP Audio:** Re-engineered playback path routing through Android's `NormalMixer` with a `Polyphase Sinc Resampler` and burst-safe buffering — completely eliminating Bluetooth static and crackling.
- **Lossless Wi-Fi Packet Recovery (`Systematic K = 4 XOR Parity FEC`):** Recovers dropped local Wi-Fi / Hotspot audio packets 100% bit-for-bit losslessly before they ever reach the DAC.
- **Click-Free Continuity (`Pitch-Matched PLC` & `2.5ms` Raised-Cosine Crossfading):** Combined with a `40ms` Time-Slip Underrun Grace window to eliminate harsh clicks, pops, and micro-cutouts under heavy RF congestion.
- **Decoupled Host Capture & Network Pipeline:** Dedicated `500ms` overflow-proof capture buffer, `WMM AC_VI` Wi-Fi QoS prioritization (`DSCP CS5`), and adaptive discovery beacons that back off during active streaming.
- **💡 Upgrade Tip:** Updating **BOTH** Host and Listener phones to `v1.3.0` unlocks full lossless FEC packet recovery (`v1.2.0` users can update directly from inside the app with one tap!).

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
1. ثبّت [`OFA-Blue-v1.3.0.apk`](OFA-Blue-v1.3.0.apk) على الموبايل الرئيسي (**Host**) والموبايلات المستقبلة (**Join**).
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
1. Install [`OFA-Blue-v1.3.0.apk`](OFA-Blue-v1.3.0.apk) on the **Host** phone and all **Listener (Join)** phones.
2. Enable **Hotspot** on the Host phone, connect the other phones to it, and pair each phone with its Bluetooth headphones.
3. On the Host phone: open **Host** mode, tap **Start Broadcast**, grant permissions, and play your downloaded movie/song in your external player.
4. On Listener phones: open **Join** mode and tap the discovered Host.
5. Fine-tune the **Sync Offset** slider if needed to align Bluetooth latency across headsets.

> **Note:** DRM-protected streaming apps (e.g., Netflix, Shahid, Spotify) block Android's `AudioPlaybackCapture` at the OS level and output silence. OFA Blue is built for downloaded local media and non-DRM apps.
