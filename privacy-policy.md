# Privacy Policy – LAST HOOK: 30 ROOFTOPS

**Effective date:** 12 November 2026 (applies to app version 1.1.0)
**App:** LAST HOOK: 30 ROOFTOPS (Android), package `[APPLICATION ID]` (currently `sk.lasthook.rooftops`)
**Developer (data controller):** [MENO VÝVOJÁRA], [ADRESA VÝVOJÁRA]
**Contact:** [TVOJ EMAIL]

This policy explains what data the LAST HOOK: 30 ROOFTOPS game ("the App") handles, why, and what
choices you have. It is based on what the App's code actually does.

## 1. Summary
* The App has **no user accounts, no registration, no in-app purchases, no analytics and no crash
  reporting**. The developer runs **no server** and does not receive your personal data.
* **An internet connection is required:** the App does not start without a working (validated)
  internet connection, because the game is funded by ads that must be loaded online.
* Your game progress and settings are stored **only on your device**.
* The App shows **ads from Google AdMob**. The Google Mobile Ads SDK collects certain data
  (e.g. IP address, advertising ID, device information), as described in section 4.
* In the EEA, the UK and Switzerland, a consent message from Google's User Messaging Platform (UMP)
  is shown where required, and you can change your choice later in the App.

## 2. Permissions the App uses
| Permission | Why |
|---|---|
| `INTERNET` | The App cannot be started or played without an internet connection, because it is required to load and show ads (and the consent message). The App itself does not send your data to any developer server. |
| `ACCESS_NETWORK_STATE` | To check on the device whether a working (validated) internet connection is available – without it the App shows a "connection required" screen instead of the game – and to pause the game safely if the connection is lost. Nothing about your network is sent anywhere by the App itself. |
| `VIBRATE` | Haptic feedback during play (can be turned off in Settings). |
| `WRITE_EXTERNAL_STORAGE` (Android 8–9 only) | Only when you tap "Save video", to save the clip to the gallery. Not requested on Android 10+. |
| `com.google.android.gms.permission.AD_ID`, `ACCESS_ADSERVICES_AD_ID`, `ACCESS_ADSERVICES_ATTRIBUTION`, `ACCESS_ADSERVICES_TOPICS`, `WAKE_LOCK`, `FOREGROUND_SERVICE` | Added automatically by the Google Mobile Ads SDK for ad delivery, measurement and Android Privacy Sandbox APIs. |

The App does **not** request location, camera, microphone, contacts, phone, or access to your photos/files.

## 3. Data stored on your device only
The App stores the following in its private app storage (Android SharedPreferences):
* game progress: best section and percentage, number of attempts, whether you finished the route,
  whether the tutorial was completed, unlocked and selected robot looks;
* a counter used for ad pacing (number of deaths since the last ad opportunity);
* settings: music, sound effects, vibration, reduced effects, chosen language.

This data never leaves your device through the App. If Android Backup is enabled on your device,
Android may include this app data in your device backup (Google's Auto Backup), which is governed by
your Google account settings. The Google UMP SDK also stores your consent choice on the device.

## 4. Advertising – Google AdMob and Google UMP
The App uses the **Google Mobile Ads SDK** (version 25.5.0) to show full-screen (interstitial) ads at
certain moments after a game over, and the **Google User Messaging Platform SDK** (version 4.0.0) to
obtain consent where required.

According to Google's official disclosure, the Google Mobile Ads SDK **automatically collects and
shares** the following for advertising, analytics and fraud-prevention purposes:
* **IP address** – which may be used to estimate the general location of the device;
* **User product interactions** – e.g. app launches, taps, video views;
* **Diagnostic information** – e.g. app launch time, hang rate, energy usage;
* **Device and account identifiers** – the Android advertising ID, app set ID and, if applicable,
  other identifiers related to signed-in accounts on the device.

Google states that this data is encrypted in transit (TLS). This data is collected and processed by
**Google**, not by the developer. Depending on your consent and settings, ads may be personalised or
non-personalised.

Official sources:
* Google Mobile Ads SDK – Google Play data disclosure: https://developers.google.com/admob/android/privacy/play-data-disclosure
* How Google uses information from sites or apps that use its services: https://policies.google.com/technologies/partner-sites
* Google Privacy Policy: https://policies.google.com/privacy
* Google User Messaging Platform: https://developers.google.com/admob/android/privacy
* Google ad settings / My Ad Center: https://myadcenter.google.com/

**Your choices**
* **Consent (EEA/UK/Switzerland):** where required, a Google consent message is shown at launch.
  When required, a **"Privacy options"** button appears in the App's Settings so you can change or
  withdraw your choice at any time.
* **Advertising ID:** you can reset or delete it in Android settings
  (Settings → Privacy → Ads, or Settings → Google → Ads, depending on the device).
* **Ad personalisation:** you can control it at https://myadcenter.google.com/.

**Legal basis (GDPR):** where the consent message requires it, ads-related processing for storing or
accessing information on your device and for personalised ads is based on your **consent**
(Art. 6(1)(a) GDPR); you can withdraw it at any time via "Privacy options". Other processing
described in Google's message (e.g. non-personalised ads, fraud prevention, measurement) may rely on
**legitimate interests** (Art. 6(1)(f) GDPR) as stated in that message.

## 5. Gameplay videos, saving and sharing
* When you tap **"Share run"** or **"Save video"**, the App creates a short MP4 video (or, if video
  encoding is unavailable, a PNG image) **on your device** from the game state of your last attempt.
  It contains only game graphics and game sound – no camera, microphone or screen recording.
* The file is first written to the App's private cache (`exports/`); it is replaced at the next
  export and removed when the app's cache is cleared or the App is uninstalled.
* **Save video** copies the file to your gallery folder **Movies/LastHook**. It stays there until you
  delete it (also after uninstalling the App).
* **Share on TikTok** (only when you tap it) passes the file directly to the TikTok app installed on
  your device, with a temporary read permission; TikTok then opens its own editor and **you decide
  whether to post**. The App contains **no TikTok SDK**, uses no TikTok account or key and sends
  nothing to TikTok by itself. To offer this button, the App checks locally whether a TikTok app
  is installed; this check is not transmitted anywhere. If TikTok is not installed, you can pick
  another app or open TikTok's Google Play page. Once shared, TikTok's privacy policy applies:
  https://www.tiktok.com/legal/page/eea/privacy-policy/en
* **Share run** opens the Android share sheet. The file is passed only to the app you choose,
  with a temporary read permission. What that app does with it is governed by its own privacy policy.

## 6. Analytics and crash reporting
The App contains **no analytics and no crash-reporting SDK** of its own (no Firebase, no Crashlytics).
Note that the Google Mobile Ads SDK collects diagnostic information as described in section 4.

## 7. Children
The App is **not directed at children under 13** [UPRAV PODĽA CIEĽOVEJ SKUPINY V PLAY CONSOLE] and
the developer does not knowingly collect personal data from children. The App does not ask for age
and does not configure child-directed ad treatment. Google Play's Families Policy requires apps
targeting children to use only Families self-certified ad SDKs and to not serve personalised ads to
children (https://support.google.com/googleplay/android-developer/answer/9893335). If you believe a
child has provided personal data, contact us at [TVOJ EMAIL].

## 8. Data retention and deletion
* **On your device:** progress and settings remain until you uninstall the App or clear its data
  (Android Settings → Apps → LAST HOOK → Storage → Clear storage). This deletes everything the App
  stored, including the consent choice.
* **Saved videos** in Movies/LastHook: delete them in your gallery or file manager.
* **Data collected by Google:** retained according to Google's policies; you can manage it via
  https://myadcenter.google.com/ and https://policies.google.com/privacy, and reset your advertising ID.
* The developer holds no personal data about you on any server, so there is nothing to delete on the
  developer's side; you may still contact us with any request.

## 9. Your rights (GDPR)
If you are in the EU/EEA, you have the right to access, rectification, erasure, restriction of
processing, data portability, objection, and to withdraw consent at any time (without affecting
processing before withdrawal). To exercise them, contact [TVOJ EMAIL]. For data processed by Google,
you can also use Google's tools linked above.
You have the right to lodge a complaint with a supervisory authority – in Slovakia: **Úrad na ochranu
osobných údajov Slovenskej republiky**, https://dataprotection.gov.sk/ – or the authority in your
country of residence.

## 10. International transfers
Google may process data outside the EU/EEA. Google describes its safeguards (e.g. EU Standard
Contractual Clauses, EU–US Data Privacy Framework) in its Privacy Policy: https://policies.google.com/privacy.

## 11. Security
The App sends no data to any developer server. Communication of the Google SDKs is encrypted (TLS)
according to Google. Data stored by the App is kept in Android's private app storage.

## 12. Changes to this policy
We may update this policy when the App changes. The current version is always published at
[URL TEJTO STRÁNKY], with the effective date at the top.

## 13. Contact
[MENO VÝVOJÁRA]
[ADRESA VÝVOJÁRA]
E-mail: [TVOJ EMAIL]
