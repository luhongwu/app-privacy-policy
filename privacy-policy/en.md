# Privacy Policy

**App Name**: AI Hairstyle

**Developer**: HONGWU LU

**Effective Date**: July 26, 2026

**Last Updated**: July 28, 2026

**Contact Email**: hongwu.lu@outlook.com

---

## 1. Introduction

This Privacy Policy applies to the mobile application "AI Hairstyle" (hereinafter "the App"), developed and published by HONGWU LU (hereinafter "we", "us", or "the Developer"). The App is an AI hairstyle preview tool that allows users to upload local photos, select hairstyles and hair colors, and generate hairstyle preview images via a third-party AI API.

We take your privacy seriously. This policy explains what information is involved when using the App, how it is used and protected, and what rights you have. **The core design principle of this App is: collect as little personal information as possible.**

Please read this policy carefully before using the App. By downloading or using the App, you acknowledge that you have read, understood, and agree to the terms of this policy. If you do not agree with this policy, please stop using and uninstall the App.

---

## 2. Information We Do NOT Collect

The App **does not** collect, store, or transmit the following information to any third party:

- Phone numbers, email addresses, names, or other personally identifiable information (no registration or login required)
- Precise or approximate geolocation data
- Contacts, call logs, or text messages
- Device identifiers (IMEI, Android ID, advertising ID, etc.)
- Payment information (bank card numbers, payment accounts, etc.)
- Behavioral analytics data beyond anonymized Firebase Analytics events (see Section 7)

---

## 3. Photos You Provide and How They Are Used

### 3.1 Photo Sources

To generate hairstyle previews, you may proactively provide photos through:

- Using your device **camera** to take a photo;
- Selecting an existing photo from your device **photo library**.

### 3.2 How Photos Are Used

The photos you select are used solely for the following purposes:

1. Format validation and compression processing locally on your device;
2. Uploaded via **HTTPS encrypted transmission** to a third-party AI image processing service to generate hairstyle preview images;
3. Generated result images, upon your confirmation, may be saved to your device photo library or retained in the App's local history.

### 3.3 What We Do NOT Do

- Your photos are processed only for the duration necessary to generate the hairstyle preview and are not retained by us beyond that;
- Your photos are **not** used for any other purpose (such as advertising, profiling, training data, etc.; refer to the third-party AI service's privacy policy);
- Other than the aforementioned third-party AI processing API, your photos are **not** transmitted to any other party;
- Photos you upload contain facial information, which constitutes sensitive personal data; by uploading, you provide **explicit consent** for their use solely for generating hairstyle previews and for no other purpose.

---

## 4. Locally Stored Data

The following data is stored only on your device and is **never uploaded to any server**:

| Data Type | Storage Method | Purpose |
|-----------|---------------|---------|
| Service usage statistics | Device-encrypted storage | Used to maintain service fairness and normal operation |
| History records (hairstyle ID, color ID, remote URLs and local file paths of generated images, timestamps) | App private directory | Displaying your generation history |
| Theme (dark/light mode, theme color) and language preferences | App private directory | Remembering your interface preferences |
| In-progress generation task information | App private directory (expires after 24 hours) | Recovering unfinished generation tasks after app interruption |

You may delete all of the above local data at any time by uninstalling the App; history records can also be manually deleted within the App.

---

## 5. Device Permissions

The App only requests permissions essential for its core functionality:

| Permission | Purpose |
|------------|---------|
| Network access (INTERNET) | Calling the third-party AI API to generate hairstyles and download result images |
| Camera (CAMERA) | Taking photos for hairstyle generation (only triggered when you tap to take a photo) |
| Read photos/media (READ_MEDIA_IMAGES / READ_EXTERNAL_STORAGE) | Selecting photos from your photo library for hairstyle generation |
| Write storage (WRITE_EXTERNAL_STORAGE) | Saving generated result images to your system photo library when you choose to save |

All permissions are triggered only when you actively use the corresponding feature; the App does not invoke them in the background without your action.

---

## 6. Payment Information

The App is a **free download** with in-app subscription services. The subscription purchase and payment process is handled entirely by the **app store**, subject to the app store's terms of service and privacy policy.

We **do not access, collect, or store** any of your payment information, including but not limited to bank card numbers, billing addresses, Google account payment credentials, etc. Refund requests should be processed through the official app store channels.

---

## 7. Third-Party Services

The App uses the following third-party services, which may process data in accordance with their own privacy policies:

| Third-Party Service | Purpose | Data Involved |
|--------------------|---------|---------------|
| Third-party AI image processing service | Processing photos and generating hairstyle preview images | Photos you upload, selected hairstyle and color parameters |
| Firebase Analytics (Google) | Anonymized app usage statistics | Anonymous events (page views, feature usage counts, etc.), device language/theme preferences, and other anonymous attributes |
| App store | App distribution, subscription purchase | Handled by the app store per its privacy policy |

For the third-party AI image processing service, please refer to its [Privacy Policy](https://www.aihairstyle.cn/privacy-policy). According to its privacy policy, uploaded images are used only for real-time processing and will be **automatically deleted within 24 hours** and not retained long-term.

Firebase Analytics, provided by Google, is used to collect anonymized app usage statistics (such as feature usage frequency, page visits, etc.) to help us improve the product experience. Firebase Analytics **does not collect** your name, email, device identifiers, precise location, uploaded photos, or other personally identifiable information. You may opt out of analytics data collection through the "Limit Ad Tracking" setting on your device. Please refer to the [Firebase Privacy Policy](https://firebase.google.com/support/privacy).

We recommend reviewing the privacy policies of the above third parties to understand their data processing practices. Apart from the above services, the App does not integrate any advertising, social sharing, or other data analytics third-party SDKs, and does not sell, rent, or share your personal information with any third party.

The third-party AI image processing service that the App relies on is deployed within China. Under China's Personal Information Protection Law, your personal information will not be transferred outside of China (no cross-border personal information transfer occurs); if you are located outside China, the relevant transfers will be processed as cross-border transfers under applicable laws of your location (e.g., the EU General Data Protection Regulation, GDPR), and we employ contractual and other reasonable safeguards.

---

## 8. Data Security

We take the following measures to protect your information:

- All network communications with the third-party AI API are transmitted via **HTTPS (TLS) encryption**;
- Service usage statistics are stored using **device-level encrypted storage**;
- Other preference and history data is stored within the App's sandboxed private directory, inaccessible to other applications;
- The App is configured with **system backup disabled** (`allowBackup=false`) to prevent accidental export of local data;
- Release builds are code-obfuscated to reduce the risk of reverse engineering and tampering.

It should be noted that no method of internet transmission or electronic storage is absolutely secure, but we will continue to take reasonable and feasible technical and organizational measures to protect your information.

---

## 9. Data Retention and Deletion

- **Photos**: Photos are only temporarily transmitted to the third-party AI API during the generation process. Per its [Privacy Policy](https://www.aihairstyle.cn/privacy-policy), uploaded images will be automatically deleted within 24 hours.
- **Local Data**: History records, preference settings, service usage statistics, and other data are retained solely on your device until you manually delete history records or uninstall the App. Uninstalling the App will delete all local data stored by the App.
- **Task Recovery Data**: Recovery information for in-progress tasks automatically expires after 24 hours.

---

## 10. Children's Privacy

The App is available to users aged **13 and above**. Minors under 18 should use the App with parental consent and guidance. For children under 14 (classified as children under China's Regulations on the Protection of Children's Personal Information Online), parents or guardians should supervise the child's use of the App and are responsible for the child's actions, including photo uploads. If you are a parent or guardian and discover that a child has used the App without your consent, you may uninstall the App to clear all local data; photos already uploaded to the third-party AI service will be automatically deleted within 24 hours.

---

## 11. Your Rights

You have the following rights regarding the data processed by the App (the App does not operate a user account system; no registration or login is required):

- You may use all features of the App **without** registering or providing any personal information;
- You may delete history records within the App at any time;
- You may revoke granted camera, photo library, and other permissions at any time in system settings (revoking permissions will disable the corresponding features but will not affect other functionality);
- You may permanently delete all of the App's data on your device by uninstalling the App;
- For photos already uploaded to the third-party AI service, the service provider commits to automatic deletion within 24 hours — no additional action is needed on your part;
- You also have the right to file a complaint or report with relevant regulatory authorities in your jurisdiction (such as China's Cyberspace Administration or EU data protection authorities).

---

## 12. Updates to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in App functionality or legal and regulatory requirements. The updated policy will be published on this page, and the "Last Updated" date will be revised. For material changes, we will provide reasonable notice within the App. We recommend reviewing this policy periodically for the latest version. Your continued use of the App after any updates constitutes acceptance of the updated policy.

---

## 13. Contact Us

If you have any questions, comments, or requests regarding this Privacy Policy or the App's data processing practices, please contact us through the following channels:

- **Developer**: HONGWU LU
- **Email**: hongwu.lu@outlook.com

We will respond as promptly as possible after receiving your feedback (typically within 7 business days).
