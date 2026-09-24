# Privacy Policy for Alarm Clock: Mission Alarm

**Last Updated:** September 24, 2026  
**Effective Date:** September 24, 2026  

**Alarm Clock: Mission Alarm** ("we", "our", or "us") is committed to protecting your privacy. This Privacy Policy explains how our mobile application (**com.alarmclock.missionalarm**, the "App") handles your information when you use our services.

By installing and using the App, you agree to the collection and use of information in accordance with this policy.

---

## 1. Summary of Core Principles
* **Local-First Processing:** Your alarms, schedules, mission preferences, and settings are stored locally on your device.
* **No Selling of Personal Data:** We do not sell, rent, or trade your personal data to any third parties.
* **On-Device Mission Evaluation:** Photos, QR scans, sensor data (squats, shake), and location checks required for alarm dismissal are processed entirely on your device and are never transmitted to external servers.

---

## 2. Information We Collect and Process

### A. Information Processed Locally on Your Device
To provide interactive wake-up missions and reliable alarm triggering, the App processes certain data locally:
* **Alarm Configuration:** Alarm times, repetition days, custom labels, snooze intervals, and chosen ringtone paths.
* **Camera & Image Data (Optional Missions):**
  * When using the **Photo Mission** or **QR/Barcode Mission**, the camera captures image data solely to compare it with your saved reference image or verify scanned codes.
  * When using the **Squat Mission**, camera frames are analyzed in real time on-device to detect movement and count repetitions.
  * **Images and video streams are processed in temporary memory and are never uploaded, stored on remote servers, or shared.**
* **Motion & Sensor Data (Shake & Squat Missions):**
  * Uses the device accelerometer and motion sensors to detect phone shaking or physical movement.
  * Sensor readings are used only during an active alarm and are discarded immediately after mission completion.
* **Location Data (Location Mission - Optional):**
  * If you choose the **Location Mission**, the App accesses your approximate or precise location (`ACCESS_FINE_LOCATION`) only when the alarm triggers to verify that you have physically reached your designated wake-up location.
  * Location data is never tracked in the background outside of active mission verification and is never sent to any external server.

### B. Automatically Collected Technical Data
When you use the App, we or third-party service providers (such as Google Play Services or Firebase Crashlytics) may collect anonymized technical data:
* Device model, operating system version, and system language.
* Crash reports and diagnostic stack traces to help us fix bugs and improve stability.
* Non-identifiable app performance statistics.

---

## 3. Device Permissions & Prominent Disclosures

The App requests the following permissions strictly to provide alarm clock functionality:

| Permission | Purpose |
| :--- | :--- |
| **`SCHEDULE_EXACT_ALARM` / `USE_EXACT_ALARM`** | Essential to trigger your alarms precisely at the scheduled time, even in deep sleep or Doze mode. |
| **`USE_FULL_SCREEN_INTENT`** | Displays the full-screen alarm ringing and mission dismissal screen over the lock screen. |
| **`FOREGROUND_SERVICE` & `MEDIA_PLAYBACK`** | Ensures uninterrupted alarm sound playback and prevents the operating system from terminating the alarm audio while ringing. |
| **`POST_NOTIFICATIONS`** | Shows upcoming alarm notices, active snooze countdowns, and foreground service status. |
| **`CAMERA`** | Required only for the optional Photo, QR/Barcode, and Squat missions. Operates on-device only. |
| **`ACCESS_FINE_LOCATION`** | Required only for the optional Location mission to verify arrival at your target wake-up spot. |
| **`REQUEST_IGNORE_BATTERY_OPTIMIZATIONS`** | Advises excluding the App from aggressive OS task killers so your alarms never fail to ring. |
| **`VIBRATE` & `WAKE_LOCK`** | Wakes the device screen and provides vibration feedback when alarms trigger. |

### Prominent Disclosure: Accessibility Service API (`PowerOffAccessibilityService`)
* **Purpose:** The App provides an optional "Cheat Prevention / Prevent Power-Off" feature for heavy sleepers. If explicitly enabled by you in Settings and system accessibility, the Accessibility Service detects interaction with the power-off/restart menu while an alarm is actively ringing.
* **Strict Limitations:**
  * The Accessibility Service is used **exclusively** to prevent unauthorized shutdown while the alarm is ringing.
  * We **do not** collect, store, or transmit any personal information, keystrokes, screen contents, or sensitive data via the Accessibility Service.
  * You can enable or disable this feature at any time in system Settings.

---

## 4. Data Storage and Retention
* All user alarms, mission configurations, and app preferences are stored locally in your device's private application storage (`SharedPreferences`).
* Uninstalling the App or clearing app data in Android system settings permanently removes all locally stored data.

---

## 5. Third-Party Services
We may utilize trusted third-party SDKs to assist with app maintenance and crash diagnostics. These third parties may collect pseudonymous identifiers in accordance with their respective privacy policies:
* **Google Play Services:** [https://policies.google.com/privacy](https://policies.google.com/privacy)
* **Firebase Crashlytics & Analytics:** [https://firebase.google.com/support/privacy](https://firebase.google.com/support/privacy)

---

## 6. Children's Privacy
Our App does not knowingly collect personally identifiable information from children under the age of 13. If you believe that your child has provided us with personal information, please contact us so that we can take necessary actions.

---

## 7. Your Rights (GDPR & CCPA / CPRA Compliance)
Depending on your jurisdiction, you have the right to:
* Access or receive a copy of any personal data we hold about you.
* Request deletion of any data collected by clearing your app cache/storage or contacting us.
* Withdraw consent for any optional device permission at any time via Android System Settings (`Settings > Apps > Alarm Clock: Mission Alarm > Permissions`).

---

## 8. Changes to This Privacy Policy
We may update our Privacy Policy periodically. We will notify you of any changes by posting the updated Privacy Policy within the App or on this page with an updated "Last Updated" date.
