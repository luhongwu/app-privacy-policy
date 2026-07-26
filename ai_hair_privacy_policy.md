# 隐私政策（Privacy Policy）

**应用名称**：AI 发型（HairStyleApp）
**开发者**：HONGWU LU（个人开发者）
**生效日期**：2026 年 7 月 26 日
**最后更新**：2026 年 7 月 26 日
**联系邮箱**：hongwu.lu@outlook.com

---

## 1. 引言

本隐私政策适用于由个人开发者 HONGWU LU（以下简称"我们"或"开发者"）开发并发布的移动应用「AI 发型（HairStyleApp）」（以下简称"本应用"）。本应用是一款 AI 发型预览工具，用户上传本地照片、选择发型与发色后，通过第三方 AI 接口生成换发型预览效果图。

我们高度重视您的隐私。本政策旨在说明本应用在使用过程中涉及哪些信息、这些信息如何被使用与保护，以及您享有的权利。**本应用的核心设计原则是：尽可能不收集任何个人信息。**

请您在使用本应用前仔细阅读本政策。您下载或使用本应用，即表示您已阅读、理解并同意本政策的内容。如果您不同意本政策，请停止使用并卸载本应用。

---

## 2. 我们不收集的信息

本应用**不会**收集、存储或向任何第三方传输以下信息：

- 手机号码、邮箱地址、姓名等身份识别信息（无需注册、无需登录）
- 精确或粗略的地理位置信息
- 通讯录、通话记录、短信
- 设备标识符（IMEI、Android ID、广告 ID 等）的收集与上报
- 支付信息（银行卡号、支付账户等）
- 使用行为分析数据（本应用未集成任何统计分析或广告 SDK）

---

## 3. 您主动提供的照片及其使用

### 3.1 照片的来源

为生成发型预览效果，您可以通过以下方式主动提供照片：

- 调用设备**相机**拍摄照片；
- 从设备**相册**中选择已有照片。

### 3.2 照片的用途

您选择的照片仅用于以下目的：

1. 在您的设备本地进行格式校验与压缩处理；
2. 通过 **HTTPS 加密传输**上传至第三方 AI 图像处理服务接口（`api.aihairstyle.cn`），用于生成换发型效果图；
3. 生成结果图片在您确认后由您主动保存至设备相册或保留在应用本地历史记录中。

### 3.3 我们不做的事

- 我们**不运营自己的服务器**，不会在开发者的任何服务器上存储您的照片；
- 您的照片**不会**被用于任何其他目的（如广告、画像、训练数据等，以第三方 AI 服务的隐私政策为准）；
- 除上述第三方 AI 处理接口外，您的照片**不会**被传输给任何其他方。

---

## 4. 本地存储的数据

以下数据仅保存在您的设备本地，**不会上传至任何服务器**：

| 数据类型 | 存储方式 | 用途 |
|----------|----------|------|
| 生成调用次数及周期重置时间 | 设备加密存储（Encrypted Storage） | 应用内每周调用次数限制（防滥用） |
| 历史记录（发型 ID、发色 ID、生成结果图片的远程链接与本地文件路径、时间戳） | 应用私有目录（AsyncStorage） | 向您展示历史生成记录 |
| 主题（深色/浅色、主题色）与语言偏好 | 应用私有目录（AsyncStorage） | 记住您的界面偏好设置 |
| 进行中的生成任务信息 | 应用私有目录（AsyncStorage，24 小时过期） | 应用中断后恢复未完成的生成任务 |

您可以随时通过卸载本应用删除以上全部本地数据；历史记录也可以在本应用内手动删除。

---

## 5. 设备权限说明

本应用仅申请实现核心功能所必需的权限：

| 权限 | 用途 |
|------|------|
| 网络访问（INTERNET） | 调用第三方 AI 接口生成发型、下载生成结果图片 |
| 相机（CAMERA） | 拍摄照片用于发型生成（仅在您主动点击拍照时调用） |
| 读取相册/媒体图片（READ_MEDIA_IMAGES / READ_EXTERNAL_STORAGE） | 从相册选择照片用于发型生成 |
| 写入存储（WRITE_EXTERNAL_STORAGE） | 将您主动保存的生成结果图片写入系统相册 |
| Google Play 许可校验（CHECK_LICENSE） | 校验应用为 Google Play 正版付费下载，保护开发者与您的权益 |

所有权限仅在您主动使用对应功能时触发，本应用不会在后台擅自调用。

---

## 6. 支付信息

本应用为 **Google Play 付费下载**应用。购买及支付流程完全由 **Google Play 商店**处理，适用《Google Play 服务条款》与 Google 的隐私政策。

我们**不会接触、收集或存储**您的任何支付信息，包括但不限于银行卡号、账单地址、Google 账户支付资料等。退款事宜请通过 Google Play 官方渠道办理。

---

## 7. 第三方服务

本应用使用以下第三方服务，这些服务可能依据其自身的隐私政策处理数据：

| 第三方服务 | 用途 | 涉及数据 |
|------------|------|----------|
| AI Hairstyle 图像处理接口（`api.aihairstyle.cn`） | 处理照片并生成换发型效果图 | 您主动上传的照片、所选发型与发色参数 |
| Google Play 商店 / Google Play 许可服务 | 应用分发、付费购买、正版许可校验 | 由 Google 按其隐私政策处理 |

其中，AI Hairstyle 图像处理服务的隐私政策请见：<https://www.aihairstyle.cn/privacy-policy>。据其隐私政策，您上传的图片仅用于实时生成处理，并将在 **24 小时内自动删除**，不会被长期留存。

我们建议您查阅上述第三方的隐私政策，以了解其数据处理实践。除上述服务外，本应用不集成任何广告、统计、社交分享或数据分析类第三方 SDK，不会向任何第三方出售、出租或共享您的个人信息。

---

## 8. 数据安全

我们采取以下措施保护您的信息安全：

- 与第三方 AI 接口之间的所有网络通信均通过 **HTTPS（TLS）加密传输**；
- 调用次数数据使用**设备级加密存储**（基于 Android Keystore 系统）；
- 其他偏好与历史数据保存在应用沙盒私有目录内，其他应用无法访问；
- 应用设置为**不允许系统备份**（`allowBackup=false`），防止本地数据被意外导出；
- 发布版本对代码进行混淆加固，降低被逆向篡改的风险。

需要说明的是，互联网传输与电子设备存储无法保证绝对安全，但我们会持续采取合理可行的技术与组织措施保护您的信息。

---

## 9. 数据保留与删除

- **照片**：本应用不在任何自有服务器留存您的照片；照片仅在生成流程中临时传输至第三方 AI 接口，据其隐私政策（<https://www.aihairstyle.cn/privacy-policy>），上传的图片将在 24 小时内自动删除。
- **本地数据**：历史记录、偏好设置、调用次数等数据仅保留在您的设备上，直至您手动删除历史记录或卸载本应用。卸载本应用将删除应用存储的全部本地数据。
- **任务恢复数据**：进行中任务的恢复信息在 24 小时后自动过期失效。

---

## 10. 儿童隐私

本应用不面向 13 周岁以下的儿童，我们也不会故意收集儿童的任何个人信息。如果您是儿童的监护人，并发现儿童在未经同意的情况下使用了本应用，请通过本政策末尾的联系方式与我们取得联系。

---

## 11. 您的权利

由于本应用不收集您的个人身份信息，也不运营用户账户体系：

- 您**无需**注册或提供任何个人信息即可使用本应用的全部功能；
- 您可以随时在应用内删除历史记录；
- 您可以随时在系统设置中撤销已授予的相机、相册等权限（撤销后对应功能将无法使用，但不影响其他功能）；
- 您可以通过卸载本应用彻底删除本应用在您设备上的全部数据。

---

## 12. 隐私政策的更新

我们可能不定期更新本隐私政策，以反映应用功能变化或法律法规要求。更新后的政策将通过本页面发布，并更新"最后更新"日期。重大变更时，我们会在应用内以合理方式提示。建议您定期查阅本政策以了解最新版本。您在政策更新后继续使用本应用，即视为接受更新后的政策。

---

## 13. 联系我们

如果您对本隐私政策或本应用的数据处理实践有任何疑问、意见或请求，欢迎通过以下方式联系我们：

- **开发者**：HONGWU LU
- **电子邮箱**：hongwu.lu@outlook.com

我们将在收到您的反馈后尽快回复（通常在 7 个工作日内）。

---

# Privacy Policy (English Summary)

**App**: AI Hairstyle (HairStyleApp) — **Developer**: HONGWU LU (Individual) — **Effective Date**: July 26, 2026 — **Contact**: hongwu.lu@outlook.com

- **No personal data collected**: no registration, no phone numbers, no location, no contacts, no device identifiers, no analytics or advertising SDKs.
- **Your photos**: photos you take or pick are compressed locally and uploaded over HTTPS **only** to the third-party AI image API (`api.aihairstyle.cn`) to generate hairstyle previews. We operate no servers of our own and never store your photos. Per the third party's privacy policy (<https://www.aihairstyle.cn/privacy-policy>), uploaded images are used only for real-time processing and are **automatically deleted within 24 hours**.
- **Local-only storage**: weekly call-count data (encrypted on-device via Android Keystore-backed Encrypted Storage), generation history, and theme/language preferences are stored only on your device and are removed when you uninstall the app.
- **Payments**: the app is a paid download on Google Play; all payment processing is handled entirely by Google Play. We never see or store your payment information.
- **Permissions**: Camera, Photos/Media, Storage, and Network are used solely for the core features described above; `CHECK_LICENSE` is used for Google Play license verification.
- **Children**: the app is not directed to children under 13, and we do not knowingly collect data from children.
- **Changes & contact**: any updates to this policy will be posted at this URL. Questions: **hongwu.lu@outlook.com**.
