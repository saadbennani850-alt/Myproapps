Privacy Policy for Satellite Finder: Dish Pointer

**Last updated:** September 29, 2026

This Privacy Policy explains how **Satellite Finder: Dish Pointer** ("the App", "we", "us", or "our", package name: `com.satellitefinder.dishpointer`) handles your information when you use our mobile application on Android devices.

We are committed to protecting your privacy. **Satellite Finder: Dish Pointer** is built with privacy-by-design principles: the app operates primarily offline, performs calculations locally on your device, and **does not sell, rent, or transmit your personal or location data to external servers**.

---

## 1. Information We Access and Collect

### A. Location Data (`ACCESS_FINE_LOCATION` and `ACCESS_COARSE_LOCATION`)
* **What We Access:** Precise (GPS) and approximate (network-based) geographic coordinates (latitude, longitude, and altitude).
* **Why We Need It:**
  * **Topocentric Astronomical Calculations:** Geostationary satellite alignment requires the exact geographic coordinates of the observer. The app uses these coordinates to calculate the target satellite's **True Azimuth**, **Elevation angle**, **LNB Polarization (Skew Angle)**, and **Line-of-Sight distance** using 3D vector geodesy.
  * **Magnetic Declination Compensation:** Your coordinates are used with the standard World Magnetic Model (`GeomagneticField`) to calculate local magnetic declination, enabling accurate switching between True North and Magnetic North.
* **Storage and Retention:** Your last known coordinates are stored **locally on your device** in private application storage (`SharedPreferences`) so that astronomical calculations remain available across app restarts without delay.
* **Sharing:** **We do not transmit your location to any remote server or third party.** All coordinate processing and trigonometric calculations occur strictly in-memory on your device.

### B. Device Sensors (Hardware Features)
* **What We Access:**
  * **Magnetometer (Compass):** Detects Earth's geomagnetic field to determine device orientation and azimuth heading.
  * **Accelerometer & Gyroscope (Rotation Vector):** Fuses motion and gravity vectors to calculate pitch, roll, bubble level alignment, and dish clinometer inclination.
* **How It Is Used:** Sensor data is processed dynamically in real-time to render the live compass dial and clinometer display.
* **Storage and Retention:** Sensor readings are processed in volatile memory only and are **never logged, permanently recorded, or transmitted**.

### C. Device Vibration (`VIBRATE`)
* **What We Access:** Device vibration motor.
* **Why We Need It:** To provide optional haptic radar feedback pulses when the device approaches or locks within range of the selected satellite target. No personal data is involved.

### D. Network State and Internet Access (`INTERNET`, `ACCESS_NETWORK_STATE`)
* **Usage:** Declared for standard platform compatibility. The core application functions fully offline without requiring an account, sign-in, or active internet connection. We do not maintain user tracking databases or remote user telemetry profiles.

### E. App Preferences and Local Settings
* **What Is Stored:** Your selected satellite, interface theme preference (Dark/Light mode), and local UI states.
* **Storage:** Saved strictly on the local device via standard Android application sandboxing.

---

## 2. Third-Party Services and Analytics

* **No Third-Party Tracking / Advertising SDKs:** The application does not integrate third-party ad networks, telemetry trackers, or profiling SDKs.
* **Google Play Services:** If you download the App via the Google Play Store, standard platform services provided by Google LLC (such as app updates and crash reporting via Android OS) may operate in accordance with [Google's Privacy Policy](https://policies.google.com/privacy).

---

## 3. Data Sharing and Disclosure

We **do not** sell, trade, rent, or disclose your location or personal information to third parties. We do not transfer your data to external servers because the app does not operate a backend database for user tracking.

Data may only be disclosed if required by law or valid legal process, or to protect the safety and integrity of the app and its users in compliance with applicable laws.

---

## 4. Data Storage, Security, and Retention

* **On-Device Storage:** All configuration settings and cached coordinates are stored inside the secure Android application sandbox (`/data/data/com.satellitefinder.dishpointer/`). Other applications cannot access this private sandbox on standard Android devices.
* **Data Deletion:** You can delete all locally stored data at any time by:
  1. Opening your device **Settings** > **Apps** > **Satellite Finder: Dish Pointer**.
  2. Selecting **Storage & cache** > **Clear storage** (or **Clear data**).
  3. Uninstalling the application will permanently remove all locally cached preferences and coordinates from your device.

---

## 5. Permissions and User Control

You have full control over the permissions granted to the App:
* **Location Permission:** You can grant, deny, or revoke location permissions at any time via Android system settings (**Settings** > **Apps** > **Satellite Finder: Dish Pointer** > **Permissions** > **Location**).
* If location permission is denied, you may still use manual coordinate input (if available) or general app features, though dynamic real-time satellite pointing calculations require geographic coordinates.

---

## 6. Children's Privacy (COPPA & GDPR-K Compliance)

Our application does not address anyone under the age of 13 (or under 16 in the EEA). We do not knowingly collect personally identifiable information from children. If you are a parent or guardian and believe that your child has provided us with personal information, please contact us so that we can take necessary actions.

---

## 7. International Data Protection Rights (GDPR & CCPA/CPRA)

Depending on your jurisdiction, you may have specific privacy rights:
* **GDPR (European Economic Area / UK):** You have the right to access, rectify, or erase your data, and the right to object to or restrict processing. Because we do not transmit or store personal data on remote servers, your data is entirely controlled by you on your local device.
* **CCPA / CPRA (California Residents):** We do not sell or share personal information (including geolocation) with third parties for commercial consideration.

---

## 8. Changes to This Privacy Policy

We may update our Privacy Policy from time to time. We will notify you of any changes by updating the "Last updated" date at the top of this document and publishing the revised version in the app repository or hosting URL. You are advised to review this page periodically for any changes.
