# Privacy Policy for Blood Pressure Tracker

**Last updated:** August 24, 2026

**Blood Pressure Tracker** ("we", "our", or "the App"), developed by **Pro Apps**, is committed to protecting your privacy and personal health data. This Privacy Policy explains how our mobile application handles user information, health data, device permissions, and security.

Please read this Privacy Policy carefully. By downloading, installing, or using Blood Pressure Tracker, you agree to the practices described in this policy.

---

## 1. Summary of Core Privacy Principles

* 🔒 **100% Local Storage:** All blood pressure records, pulse logs, notes, and personal settings are stored solely on your device's local database.
* 🚫 **No Account Required:** You do not need to register, create an account, or log in with an email or social media profile to use the App.
* 🛡️ **No Cloud Harvesting:** We do not operate remote servers that collect, store, or sell your health metrics.
* 📤 **User-Controlled Export:** You have full control over exporting and sharing your data via CSV or text summary with your healthcare provider.

---

## 2. Information We Handle

### A. Health & Personal Vitals (Stored Locally Only)
When you log readings within the App, the following information is recorded directly into your device's secure internal database (Room SQLite):
* **Blood Pressure Measurements:** Systolic and Diastolic values (mmHg).
* **Heart Rate:** Pulse rate (BPM).
* **Measurement Context:** Measurement arm (Left/Right), posture (Sitting, Lying, Standing), date/time stamps.
* **Custom Tags & Notes:** Optional tags (e.g., Morning, Evening, After Meds, Post-Workout, Stress) and personal notes.
* **Calculated Metrics:** Mean Arterial Pressure (MAP) and Pulse Pressure.

> **Note:** This health data is never transmitted to our servers or any third parties without your explicit action.

### B. App Preferences (Stored Locally Only)
* Measurement reminder time (hour and minute).
* Reminder enabled/disabled status.
* User display name (used solely for formatting doctor report exports).

### C. Automatically Collected Technical Data
The App does not collect personally identifiable analytics or device identifiers. Standard system crash logs may be processed anonymously by Google Play Services in accordance with [Google's Privacy Policy](https://policies.google.com/privacy) to ensure application stability.

---

## 3. Device Permissions & Why We Need Them

To provide core functionality, the App may request the following permissions:

| Permission | Technical Name | Purpose |
| :--- | :--- | :--- |
| **Notifications** | `android.permission.POST_NOTIFICATIONS` | Used exclusively to deliver daily measurement reminder alerts that you schedule. |
| **Exact Alarms** | `android.permission.SCHEDULE_EXACT_ALARM` | Allows the App to trigger daily measurement reminders at your exact chosen time. |

*You can grant or revoke these permissions at any time via your device's Android System Settings.*

---

## 4. How Your Data Is Used

We use the information stored on your device exclusively to:
1. Display your historical readings, trends, and statistics within the App interface.
2. Classify readings against the American Heart Association (AHA) blood pressure categories.
3. Generate formatted summaries and CSV files when you explicitly choose to export or share them.
4. Trigger scheduled reminder notifications on your device.

We **do not** use your data for marketing, advertising profiling, or sale to data brokers.

---

## 5. Data Sharing & Third-Party Disclosure

We **do not sell, trade, rent, or transfer** your health or personal data to outside parties.

### User-Initiated Sharing
If you use the "Export & Share Report" feature:
* The App generates a standard CSV file or text summary saved temporarily in the App's secure cache directory.
* The App utilizes the standard Android Share Sheet (`Intent.ACTION_SEND` via `FileProvider`) to transfer the file only to the application you explicitly select (such as your Email client, Google Drive, or messaging app).
* You maintain total discretion over who receives this data (e.g., your physician or cardiologist).

---

## 6. Data Retention, Backup & Deletion

* **Data Retention:** Your data remains stored on your device for as long as you keep the App installed.
* **Data Deletion:** You can delete individual readings at any time within the History screen, or permanently erase all logged data using the **"Clear All Data"** option in the Guide/Settings screen.
* **App Uninstallation:** Uninstalling the App permanently removes all locally stored data from your device unless you have enabled Android System Backups.

---

## 7. Security of Your Health Information

Because your health information never leaves your device:
* Your data is protected by the built-in sandboxing and file-level encryption mechanisms of the Android operating system.
* We recommend securing your device with a PIN, pattern, password, or biometric lock (fingerprint/face recognition) to prevent unauthorized local access.

---

## 8. Children’s Privacy

Our App is not directed to children under the age of 13 (or under 16 in certain jurisdictions). We do not knowingly collect or solicit personal information from children. If you believe a child has provided health data, the data can be erased immediately by clearing data in the App or uninstalling it.

---

## 9. Compliance with Regulations

### GDPR (General Data Protection Regulation - EU/EEA)
Under the GDPR, you have the right to access, rectify, port, and erase your personal data. Because the App operates 100% offline with local storage, you can exercise these rights directly within the App by viewing, editing, exporting, or clearing your records at any time.

### CCPA / CPRA (California Consumer Privacy Act)
We do not collect personal information for commercial sale or sharing with third-party advertisers. California residents have full control over their local data through the App interface.

### Google Play Health Apps Policy
Blood Pressure Tracker complies fully with Google Play Developer Policies regarding Health Apps and User Data. We do not transmit sensitive health data to unauthorized third parties or use health data for advertising.

---

## 10. Medical Disclaimer

> **IMPORTANT MEDICAL NOTICE:**
> Blood Pressure Tracker is an informational tool designed for logging, tracking, and analyzing blood pressure and heart rate measurements. **This App DOES NOT measure blood pressure independently**; a physical, medically validated blood pressure monitor or cuff is required to take measurements.
> 
> The information provided by the App is for personal tracking and educational purposes only and is not a substitute for professional medical advice, clinical diagnosis, or medical treatment. Always seek the advice of your physician, cardiologist, or other qualified healthcare provider regarding any cardiovascular health concerns or changes to your medication regimen.

---

## 11. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect improvements in the App or legal requirements. Any updates will be posted on this page with an updated "Last updated" date. We encourage you to review this policy periodically.
