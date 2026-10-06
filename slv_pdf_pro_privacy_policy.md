# Privacy Policy for SLV PDF Pro

**Last Updated: October 6, 2026**

**SLV PDF Pro** ("we," "our," or "us"), package name **`com.slv.pdfpro`**, provides a comprehensive, professional document intelligence and PDF utility application for Android. We are deeply committed to user privacy, data security, and full transparency.

This Privacy Policy explains how information is handled when you use the **SLV PDF Pro** mobile application (the "App").

---

### 1. 100% Offline-First Architecture & Absolute Document Privacy

Your documents are private, sensitive, and belong exclusively to you.

* **Zero Cloud Document Processing:** All document operations—including PDF reading, authoring, editing, splitting, merging, rotating, compressing, digital signing, watermarking, redaction, and local encryption—occur 100% locally on your device.
* **On-Device OCR & Scanner:** Optical Character Recognition (OCR), document edge detection, and perspective transformations are executed completely on-device using local machine learning models (Google ML Kit on-device text recognition). Your scanned images, camera captures, and extracted text never leave your device.
* **No Mandatory Account or Login:** You are never required to register an account, sign in with an email address, or link a social profile to use the App.
* **Zero Telemetry on Document Content:** Document names, contents, text streams, photos, signatures, and passwords are never transmitted to any analytics, monetization, or remote server.

---

### 2. Device Permissions & Purpose of Access

The App requests only the permissions necessary to provide its core local functionality:

* **Camera (`android.permission.CAMERA`):**
  Required strictly to allow you to photograph documents within the Document Scanner module. All image enhancement, edge detection, perspective correction, and scanning occur locally on your device. Camera streams and captured images are never shared.
* **Storage & Photos / Media (`READ_EXTERNAL_STORAGE`, `WRITE_EXTERNAL_STORAGE`, `READ_MEDIA_IMAGES`):**
  Required to browse, open, view, edit, convert, and save PDF files and images from your local device storage.
* **Internet & Network Access (`INTERNET`, `ACCESS_NETWORK_STATE`):**
  Used exclusively for Google Play Billing subscription entitlement checks and loading standard non-intrusive advertisements from Google AdMob.

---

### 3. Monetization, Subscriptions & Third-Party Services

To provide flexible access, the App utilizes official Google services:

#### A. Google Play Billing
* When purchasing a subscription (Plus, Pro, Business), all payment transactions, credit card handling, recurring billing, and cancellations are managed directly and securely by Google Play.
* **We do not collect, process, or store credit card numbers, bank details, UPI information, or payment credentials.**
* The App merely receives an entitlement token from Google Play confirming whether an active subscription tier exists.

#### B. Google AdMob (Advertisements)
* For free-tier users and during testing periods, the App may display advertisements via Google AdMob to support ongoing development.
* AdMob may collect pseudonymous device information, including Google Advertising ID (GAID), IP address, and general diagnostic/interaction metrics.
* **Ad Policy Guarantee:** Advertisements are strictly suppressed during sensitive document workflows, including active camera capture, document editing, password entry, signature placement, native printing, and recovery. Users on ad-free paid plans receive zero advertisements.
* You can manage or opt out of personalized advertising at any time in your Android device settings (**Settings > Google > Ads**).

For more details on Google's privacy practices:
* [Google Privacy Policy](https://policies.google.com/privacy)
* [How Google uses information from sites or apps that use our services](https://policies.google.com/technologies/partner-sites)

---

### 4. Data Retention & User Control

* **Local Storage Control:** All created documents, scans, drafts, signatures, and app preferences reside strictly in your local device storage (and private app sandbox via Hive).
* **Instant Deletion:** You can delete any document, scan, or draft directly within the App. If you clear the App's data via Android Settings (**Settings > Apps > SLV PDF Pro > Storage > Clear Data**) or uninstall the App, all locally cached files and application settings are permanently deleted.
* **Subscription Expiration Safety:** If a paid subscription expires or is cancelled, user documents are **never** deleted or locked. All created files remain fully readable and accessible on your device.

---

### 5. Children's Privacy (COPPA & GDPR Compliance)

The App does not knowingly collect or solicit personal information from children under the age of 13 (or the applicable age of digital consent). The App is designed as a productivity tool for students, professionals, and general users.

---

### 6. Security Safeguards

The App incorporates local cryptographic protection mechanisms:
* Standard AES encryption for password-protected PDF files.
* Permanent, destructive text purging for the Redaction tool (ensuring redacted content cannot be retrieved or inspected in the PDF stream).

---

### 7. Changes to This Privacy Policy

We may periodically update this Privacy Policy to reflect app enhancements or legal requirements. Updated policies will be posted directly to this repository with an updated "Last Updated" date.

---

### 8. Contact Us

If you have any questions, feedback, or privacy concerns regarding **SLV PDF Pro**, please contact us via our developer GitHub profile:
* **Developer:** Lokanath / SLV
* **GitHub Repository:** [https://github.com/Lokanath862001/SLV-PDF-Pro](https://github.com/Lokanath862001/SLV-PDF-Pro)
