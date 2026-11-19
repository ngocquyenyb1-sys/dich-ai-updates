# ⌨️ Keyboard AI – Bàn phím dịch AI cho Android

**Chat với khách nước ngoài bằng tiếng Việt, ngay trong Zalo, WeChat, WhatsApp, Messenger, Outlook, Gmail…**
Gõ tiếng Việt → bấm Enter → app dịch rồi gửi. Tin khách gửi đến hiện bản dịch ngay trên màn hình.

> Ứng dụng được tạo và phát triển bởi **Quin**. Miễn phí sử dụng · Mã nguồn không công khai.
> Bản mới nhất: xem `update.json` · Tải APK: file `DichAI-<phiên bản>.apk` trong repo này.

*[English below](#english)*

---

## Vì sao làm app này

Người làm xuất khẩu, bán hàng, tìm nhà cung cấp phải chat cả ngày với khách Mỹ, Trung, Hàn, Nhật… Mỗi tin nhắn lại phải copy sang Google Dịch rồi dán ngược về, vừa chậm vừa dễ sai ý. Keyboard AI đưa việc dịch vào **ngay bàn phím và màn hình chat**, nên không phải chuyển app.

## Tính năng chính

### 🌐 Bảng dịch nổi trong app chat và email
- Mở Zalo, WeChat, WhatsApp, Messenger, Telegram, LINE, Teams, Outlook, Gmail… là **bảng dịch tự hiện**. Tin tiếng nước ngoài được dịch sang tiếng Việt.
- Mỗi tin hiện **👤 tên người nhắn** để biết ai nói gì.
- Kéo lên xem tin cũ thì bản dịch hiện theo. Đoạn đã dịch rồi hiện **tức thì**, không gọi AI lại.
- App không cho đọc chữ (WeChat, thân thư Outlook): AI **đọc ảnh màn hình** để dịch.
- Email dài: dịch toàn bộ thư, chia đoạn dịch song song cho nhanh.
- **💬 Trả lời:** AI gợi ý 3 câu trả lời theo đúng ngôn ngữ của khách, kèm nghĩa tiếng Việt và **🧭 nhận diện tình huống** (đòi giảm giá, khiếu nại, giục hàng…) cùng lời khuyên trước khi trả lời.

### ⌨️ Bàn phím tiếng Việt thông minh
- **Tự dịch:** gõ tiếng Việt, bấm Enter một lần là dịch và gửi. Mỗi app chat nhớ ngôn ngữ riêng, ví dụ WeChat → 中文, WhatsApp → English.
- **Theo tiếng người gửi:** khách nói tiếng gì thì tự trả lời bằng tiếng đó.
- **✏️ Tự sửa chính tả theo ngữ cảnh:** sửa sai chữ, thiếu dấu, gõ nhầm Telex dựa trên đoạn hội thoại. Có lớp kiểm tra chống sửa sai ý: không đổi số, giá, tên; không viết lại câu.
- **✍️ Viết hay:** 3 phiên bản (tự nhiên · chuyên nghiệp, thuyết phục · ngắn gọn, thân thiện).
- **✨ Soạn:** gõ ý ngắn, không dấu cũng được, AI viết thành tin hoàn chỉnh.
- **Telex gõ tự do:** gõ dấu trước hay sau đều ra chữ có nghĩa (`nuarw` → `nửa`).
- **Gợi ý từ tiếp theo**, tự viết hoa tên người và tên nước, **học cách viết của bạn**.
- **🔑 Mã OTP** từ tin nhắn và email hiện ngay trên bàn phím, chạm để điền.
- **Ô mật khẩu:** gõ đúng từng ký tự, tắt Telex và AI.
- Viết dở thoát ra rồi vào lại vẫn **giữ nguyên bản dịch**.

### 🔔 Dịch thông báo
Tin đến hiện thông báo có cả bản dịch và bản gốc, kèm nút **Trả lời (tự dịch)**.

### 📝 Nhắc việc từ tin nhắn
AI nhận ra hẹn giao hàng, gửi báo giá, họp… trong tin nhắn và tạo nhắc việc.

### ⚡ Ổn định và nhanh
- Dùng model AI nhanh cho việc dịch, mở sẵn kết nối, nhớ bản dịch 7 ngày.
- AI chính lỗi liên tục thì tự chuyển sang AI dự phòng.
- Tự cập nhật online, kiểm tra mã sha256 của file tải về. Có báo cáo tốc độ hằng tuần và nút **Tự kiểm tra**.
- Giao diện **Tiếng Việt / English**.

## Chọn AI

Dùng key API của chính bạn: **ChatGPT (OpenAI), Gemini (Google), Claude (Anthropic)** hoặc AI chuẩn OpenAI (DeepSeek, Qwen, Grok, OpenRouter…). Doanh nghiệp có thể dùng **máy chủ riêng**, khi đó key không nằm trên điện thoại nhân viên.

> Key chỉ lưu trên điện thoại của bạn, không nằm trong APK hay repo này. Chi phí AI tính theo lượt dùng của hãng bạn chọn.

## Cài đặt (Android 8 trở lên)

1. Tải file `DichAI-<phiên bản mới nhất>.apk` trong repo này.
2. Máy Samsung: tạm tắt **Auto Blocker** (Cài đặt › Bảo mật và quyền riêng tư). Cho phép cài ứng dụng không rõ nguồn.
3. Cài APK. Play Protect cảnh báo thì chọn **Vẫn cài đặt**.
4. **Android 13 trở lên:** Cài đặt › Ứng dụng › Keyboard AI › ⋮ › **Cho phép cài đặt bị hạn chế**.
5. Mở app, làm theo các bước ①②③: bật bàn phím, truy cập thông báo, Trợ năng và hiển thị trên app khác.
6. Nhập key AI rồi vào mục **Tự kiểm tra**.

Các bản sau tự cập nhật trong app (mục ⑧).

**Lưu ý:** một số app ngân hàng hoặc VNeID yêu cầu tắt Trợ năng. Tắt đi thì bàn phím vẫn dùng được, chỉ bảng dịch tự hiện tạm ngưng. App phát hành trực tiếp bằng APK, không qua Google Play.

## Quyền riêng tư

- App đọc chữ trên màn hình chat (qua Trợ năng) **chỉ để dịch**. Nội dung được gửi thẳng tới AI bạn chọn, không qua máy chủ nào khác (trừ khi bạn tự dựng máy chủ riêng).
- Ô mật khẩu không bao giờ được gửi đi. Mã OTP chỉ xử lý trên máy.
- Không quảng cáo, không thu thập dữ liệu.

---

<a name="english"></a>
# ⌨️ Keyboard AI – AI translation keyboard for Android

**Chat with foreign customers in your own language, right inside Zalo, WeChat, WhatsApp, Messenger, Outlook, Gmail and more.**
Type in Vietnamese, press Enter, and the app translates and sends. Incoming messages are translated on screen as they arrive.

Created and developed by **Quin**.

## Features
- **Floating translation panel** in chat and email apps. It appears automatically, shows the **sender's name** for each message and follows as you scroll. Screens you have already read show their translations instantly.
- **Screenshot reading** for apps that hide their text, such as WeChat and Outlook mail bodies.
- **Smart replies:** 3 suggested replies in the sender's language, plus situation detection (discount request, complaint, delay…) with advice.
- **Translate-and-send keyboard** that remembers the target language per app, or follows the sender's language.
- **Context-aware spell fix** with safeguards so the meaning never changes: numbers, prices and names stay as typed.
- **Rewrite** in 3 styles, and **Compose** a full message from a short note.
- Free-order Vietnamese Telex, next-word prediction, auto-capitalisation of names, learning your writing style.
- **OTP codes** from SMS and email shown on the keyboard. Password fields are typed raw, with AI off.
- Notification translation with reply. Task reminders extracted from chats.
- Fast-model routing, a 7-day translation cache, automatic fallback AI, online updates verified by sha256, and a Vietnamese / English UI.

## AI providers
Bring your own API key: OpenAI, Google Gemini, Anthropic Claude, or any OpenAI-compatible API. Companies can run a private backend so keys never sit on staff phones.

## Install
Download the latest `DichAI-<version>.apk` from this repository. On Android 13 and later, allow "restricted settings" for the app. Then follow steps ①②③ in the app to enable the keyboard, notification access and accessibility. The app updates itself afterwards.

## Privacy
Screen text is read only to translate it, and is sent directly to the AI provider you choose. Password fields are never sent. No ads, no tracking.

---

© 2026 Quin. Bảo lưu mọi quyền · All rights reserved. Free to use; source code is not public.

Dictionary data: FrequencyWords by Hermit Dave (CC BY-SA 4.0).
