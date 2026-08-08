# Privacy Policy

**App Name**: AI Hairstyle

**Developer**: BoboBru

**Effective Date**: July 26, 2026

**Last Updated**: August 8, 2026

---

## 1. Introduction

This Privacy Policy applies to the mobile application "AI Hairstyle" (hereinafter "the App"), developed and published by BoboBru (hereinafter "we", "us", or "the Developer"). The App is an AI hairstyle preview tool that allows users to upload local photos, select hairstyles and hair colors, and generate hairstyle preview images via a third-party AI API.

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

**The App does not sell, nor share with any third party, your personal information** (including sensitive personal information such as facial information contained in photos you upload). If you are a California resident, you have the right under the CCPA/CPRA to direct us not to sell or share your personal information — the App already satisfies this requirement by default, and no further action is required on your part.

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
| History records (hairstyle ID, color ID, remote URLs and local file paths of generated images, timestamps) | App private directory | Displaying your generation history |
| Theme (dark/light mode, theme color) and language preferences | App private directory | Remembering your interface preferences |
| In-progress generation task information | App private directory (expires after 24 hours) | Recovering unfinished generation tasks after app interruption |

**About "service usage statistics"**: the App does **not maintain a separate local "usage statistics" database**. The anonymous events collected by Firebase Analytics described in Section 7 are the sole application-layer usage-statistics source. Locally, the App only retains a "last-generation timestamp" for task recovery (see the "In-progress generation task information" row above) and does not separately store any other statistical fields, so as to avoid ambiguity with the Firebase Analytics collection scope.

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
| App store (Apple App Store / Google Play) | App distribution, subscription purchase and billing | Subscription-related information you provide (such as purchase receipts, subscription identifiers, and order numbers); the App does not receive sensitive data such as payment card numbers, billing addresses, or payment credentials |

For the third-party AI image processing service, please refer to its [Privacy Policy](https://www.aihairstyle.cn/privacy-policy). According to its privacy policy, uploaded images are used only for real-time processing and will be **automatically deleted within 24 hours** and not retained long-term.

Firebase Analytics, provided by Google, is used to collect anonymized app usage statistics (such as feature usage frequency and page visits) to help us improve the product experience. Firebase Analytics **does not collect** your name, email, device identifiers, precise location, uploaded photos, or other personally identifiable information. You may opt out of analytics data collection through the "Limit Ad Tracking" setting on your device. Please refer to the [Firebase Privacy Policy](https://firebase.google.com/support/privacy).

We recommend reviewing the privacy policies of the above third parties to understand their data processing practices. Apart from the above services, the App does not integrate any advertising, social sharing, or other data analytics third-party SDKs, and does not sell, rent, or share your personal information with any third party.

**Cross-border Transfers and Overseas Recipient Safeguards**: the third-party services integrated by the App may be deployed in different jurisdictions. We describe them **separately** based on actual deployment, to avoid one-size-fits-all misstatements.

- **Third-party AI image processing service**: the App relies on this service to perform image generation. Depending on your location and where the service is actually deployed, the relevant data transfer **may** constitute a cross-border transfer:
  - If you are located in China and the service is deployed overseas: outbound transfer of your personal information will be handled under China's Personal Information Protection Law, including but not limited to executing the **standard contract under the Measures for the Standard Contract for Personal Information Outbound Transfers (2023)**, filing with the local CAC where required, and conducting a **Personal Information Protection Impact Assessment (PIPIA)**;
  - If you are located outside China and the service is deployed in China: the transfer will be processed as a cross-border transfer under the laws of your location (e.g., the EU GDPR, the UK GDPR, the Swiss FADP, the California CCPA/CPRA, etc.). We implement safeguards including the **EU Standard Contractual Clauses (SCCs, modules under Commission Implementing Decision 2021/914)** and a **Transfer Impact Assessment (TIA)**;
  - If the service is actually deployed in the same jurisdiction as you: no cross-border transfer occurs, and data is processed under the service's own privacy policy.

- **Firebase Analytics (Google, deployed in the United States and the European Union among others)**: as a typical overseas SDK, it constitutes outbound transfer of personal information when used from within China. We have completed the compliance bridge via **SCCs (2021/914)** provided by Google, and apply minimum-exposure settings in the Firebase console (anonymized events, IP-address limitation, advertising-personalization disabled, etc.).

- **Other third-party SDKs that may be (or may in the future be) integrated**: if such an SDK is deployed **domestically** (e.g., a China-based BaaS, statistics, or push service), no cross-border transfer occurs and data is processed under that SDK's own privacy policy; if deployed **overseas**, we will apply the same safeguards as for any other overseas SDK — SCCs / Chinese standard contract / PIPIA / encrypted transmission and data minimization.

Regardless of the above, we adopt the following **common safeguards**: (1) only the **minimum data necessary** to provide the corresponding feature is transferred; (2) all cross-border links use **HTTPS / TLS encryption**; (3) we **periodically review** third-party SDK privacy policies, compliance status, and the latest regulatory developments; (4) where required by the laws of your jurisdiction, we provide you with channels to access, correct, delete, and withdraw consent.

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
- **Task Recovery Data**: Recovery information for in-progress tasks automatically expires after 24 hours; expired data is deleted from local storage by **secure overwrite** so that it cannot be recovered.

---

## 10. Children's Privacy

The App is available to users as follows:
- **aged 16 and above** for users located in the European Union, the United Kingdom, Switzerland, and other jurisdictions where the GDPR applies;
- **aged 13 and above** for users located in the United States, Canada, and other jurisdictions.

Minors under 18 should use the App with parental or guardian consent and guidance. For children below the applicable age threshold (which varies by jurisdiction), parents or guardians should supervise the child's use of the App and are responsible for the child's actions, including photo uploads. If you are a parent or guardian and discover that a child has used the App without your consent, you may uninstall the App to clear all local data; photos already uploaded to the third-party AI service will be automatically deleted within 24 hours.

---

## 11. Your Rights

You have the following rights regarding the data processed by the App (the App does not operate a user account system; no registration or login is required):

- You may use all features of the App **without** registering or providing any personal information;
- You may delete history records within the App at any time;
- You may revoke granted camera, photo library, and other permissions at any time in system settings (revoking permissions will disable the corresponding features but will not affect other functionality);
- You may permanently delete all of the App's data on your device by uninstalling the App;
- For photos already uploaded to the third-party AI service, the service provider commits to automatic deletion within 24 hours — no additional action is needed on your part;
- You also have the right to file a complaint or report with relevant regulatory authorities in your jurisdiction (such as China's Cyberspace Administration or EU data protection authorities).
- Where required by applicable law (e.g., Article 20 of the EU GDPR), you have the right to obtain a copy of your local data (such as history records and preference settings) in a **structured, commonly used, and machine-readable format**.

---

## 12. Updates to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in App functionality or legal and regulatory requirements. The updated policy will be published on this page, and the "Last Updated" date will be revised. For material changes, we will provide reasonable notice within the App. **"Material changes" include but are not limited to**: adding new data-collection items or fields; changing third-party services or third-party SDKs; adjusting cross-border transfer mechanisms; changing your rights or how you may exercise them; modifying data retention periods. We recommend reviewing this policy periodically for the latest version. Your continued use of the App after any updates constitutes acceptance of the updated policy.

---

## 13. Contact Us

If you have any questions, comments, or requests regarding this Privacy Policy or the App's data processing practices, please contact us through the following channels:

- **Developer**: BoboBru
- **Email**: hongwu.lu@outlook.com

We will respond as promptly as possible after receiving your feedback (typically within 7 business days; for personal-data-related requests — such as access, correction, deletion, or withdrawal of consent — we will respond within **30 calendar days**, which may be extended by up to a further 60 days for complex cases, with notice of the reason for the extension).
