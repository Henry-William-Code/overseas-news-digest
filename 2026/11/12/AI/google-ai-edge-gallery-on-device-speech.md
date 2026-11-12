# Google AI Edge Gallery 上线端侧语音识别和语音合成，可完全离线使用

[当日日报](../日报.md#google-ai-edge-gallery-on-device-speech) · [首页](../../../../README.md#google-ai-edge-gallery-on-device-speech)

- **版块**: AI
- **来源**: Google Developers Blog
- **来源标题**: On-Device Speech Recognition and Text-to-Speech in Google AI Edge Gallery
- **来源链接**: https://developers.googleblog.com/en/on-device-speech-recognition-and-text-to-speech-in-google-ai-edge-gallery/
- **原始发布时间**: 可见日期 NOV. 10, 2026；JSON-LD datePublished="2026-11-10"（仅日期，无时刻）。Google Developers Blog 正文日期行与 JSON-LD datePublished 均只到日，未给出时区或钟点。本条按 48 小时窗口收入，并标明仅有日期。
- **上海时间**: 2026-11-10（官方仅标注日期，未给出具体时刻）
- **窗口**: 48小时内（官方仅标注日期）

## 摘要

Google 宣布在 AI Edge Gallery 中加入可完全在设备上运行的自动语音识别（ASR）和文本转语音（TTS）。官方的设想是：把这些轻量语音模型与 Gemini Nano、Gemma 4 等端侧小语言模型搭配，让应用在没有网络时也能一边实时转写用户说话，一边在本地合成口语回复。

在 Android 上，开发者可通过 ML Kit 使用系统内的语音模型，官方称这样不会增加应用安装包体积。跨平台应用则可通过 MediaPipe Tasks 和 LiteRT 使用开放权重模型包，文中举例包括 Parakeet-TDT 0.6B、PocketTTS、Kokoro 和 Phonon。Gallery 还加入了「XR Language Teacher」示范：把手机摄像头对准菜单或路牌并开口提问，即可在本地听到解释和外语发音；主聊天界面也增加了语音输入和朗读。

文中给出的性能数字，例如 ML Kit 语音识别可覆盖 100 多种语言、以约 10 倍实时速度转写，以及 TTS 约 100 毫秒起声、最高约 50 倍实时合成，均来自 Google 自己的说明，需要视为公司评测陈述。相关应用、示例代码和文档已在稿件中提供下载和链接。

为何关注：在地铁里或出国时信号不好，如果转写和朗读都能在手机上离线完成，语音助手就不只依赖云端。
