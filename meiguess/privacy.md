# 美猜 隐私政策 / Privacy Policy

生效日期 / Effective date: 2026-10-05

---

## 简体中文

**美猜没有自有服务器，没有账号体系，没有广告，没有埋点。你的游戏数据默认只留在这台设备上。**

### 唯一会离开设备的数据

当你**主动**开启 AI 出题 / 智能判定 / 问一问 / 方向引导，并**自行**在设置里填入 API Key 之后，App 才会把你说出的猜测转写为文本，并**直接**发送到你选择的服务商（OpenAI、Anthropic、智谱 GLM、DeepSeek、MiniMax、Kimi，或任何 OpenAI / Anthropic 兼容的自建服务）。

- App **没有中间服务器**，你的 Key 和内容不经过开发者。
- App **不内置任何密钥**，开发者也没有后台。
- 费用由你所选服务商按其自身价格收取，App 不抽成。
- **不填 Key 时这些功能完全离线**：退回内置 120 词词库 + 本地判定算法。
- 购买并使用「本地 AI 推理」扩展时，模型在你的设备上运行，**不发起任何网络请求**。

### 数据存在哪里

- **战绩与历史**：只存在设备本地（`UserDefaults` 与 Application Support 目录），不上传、不同步。模型文件已明确排除 iCloud 备份。可在设置里单独清空历史，卸载 App 即删除全部本地数据。
- **你填的 API Key**：存进系统钥匙串（Keychain），受 iOS 加密保护。
- **标识符（IDFA / 设备 ID）**：不收集。

### 权限用途

- **麦克风**：听你说出的猜测内容。只在开启 AI 功能并自行填写 API Key 时才会离开设备，否则完全本地处理。
- **语音识别**：把你说出的猜测转成文字，以便判断猜得对不对。同样只在你自行开启 AI 功能时才会离开设备。
- 拒绝这些权限不影响使用：可以改用键盘打字猜词。

### 第三方组件

**无。** 零第三方 SDK、零广告 SDK、零分析 SDK。唯一的动态依赖是 **llama.cpp**（Apache-2.0 / MIT 许可），仅用于本地 AI 推理，不含任何网络代码路径。

### 购买

如果购买美猜或「本地 AI 推理」扩展，整个支付流程由 Apple 处理，开发者不会收到你的任何支付或账户信息。交易状态仅用于在设备上判断扩展是否已解锁。

### 儿童隐私

美猜的 App Store 年级分级为 4+，不面向儿童定向设计，也不收集儿童的个人信息。由于不含账号体系与自有服务器，无法建立与任何用户的关联。

如对本政策有疑问，请邮件联系 <tomtrije@163.com>，或通过仓库 Issues：<https://github.com/mei-pub/pages/issues>

---

## English

**MeiGuess has no server of its own, no accounts, no ads, and no analytics. Your game data stays on your device by default.**

### The only data that can leave your device

If — and only if — you **explicitly** enable AI question generation / smart judging / Q&A / hints **and** enter your own API Key in Settings, the app will transcribe what you say and send it **directly** to the provider you chose (OpenAI, Anthropic, Zhipu GLM, DeepSeek, MiniMax, Kimi, or any OpenAI- / Anthropic-compatible self-hosted service).

- The app has **no intermediary server**. Your key and your content never pass through the developer.
- The app **ships no keys**, and the developer has no backend.
- Your provider bills you at their own rates. The app takes no cut.
- **With no key entered, these features are fully offline**, falling back to the built-in 120-word bank and on-device judging.
- With the "Local AI Inference" add-on, the model runs on your device and **makes no network requests**.

### Where your data lives

- **Scores and history**: stored only on your device (`UserDefaults` and the Application Support directory). Never uploaded, never synced. Model files are explicitly excluded from iCloud backup. You can clear history in Settings; uninstalling removes all local data.
- **Your API Key**: stored in the system Keychain, protected by iOS encryption.
- **Identifiers (IDFA / device ID)**: not collected.

### Permissions

- **Microphone**: to hear the guesses you say. Content leaves the device only when you enable an AI feature and enter your own key; otherwise it is processed entirely on device.
- **Speech Recognition**: to turn speech into text so guesses can be judged. Same condition applies.
- Declining these permissions does not limit the app — you can type your guesses instead.

### Third-party components

**None.** No third-party SDKs, no advertising SDKs, no analytics SDKs. The only dynamic dependency is **llama.cpp** (Apache-2.0 / MIT), used solely for local inference, with no network code path.

### Purchases

If you buy MeiGuess or the "Local AI Inference" add-on, the entire payment is processed by Apple. The developer never receives your payment or account information. The transaction state is used only on your device to determine whether the add-on is unlocked.

### Children's privacy

MeiGuess is rated 4+ on the App Store, is not directed at children, and does not collect children's personal information. Because there is no account system and no server of its own, no user association can be made.

Questions about this policy: <tomtrije@163.com> or <https://github.com/mei-pub/pages/issues>
