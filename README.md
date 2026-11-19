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

### 😀 Bảng tiện ích (phím 😀 cạnh ?123)
- **Emoji** theo nhóm + emoji vừa dùng; **🖼 Emoji của tôi** tạo từ ảnh (logo, sản phẩm…) – chạm là gửi.
- **📋 Bộ nhớ tạm** 20 mục gần nhất (ghim được; không lưu mật khẩu, OTP, số thẻ).
- **📌 Mẫu câu gõ tắt**: gõ `/stk`, `/cty`, `/cam` + cách → ra số tài khoản, thông tin công ty, câu cảm ơn…
- **✉️ Mẫu tin theo tình huống**: báo giá, xác nhận PO, báo trễ hàng, nhắc cọc, gửi bản vẽ… – AI viết theo ý chính và cuộc chat, không bịa giá/ngày.
- **📷 Chụp/chọn ảnh để dịch** bản vẽ, spec, báo giá (hoặc Chia sẻ ảnh → Keyboard AI) · **🔊 Đọc to** · **🎤 Nói để viết**.
- Chỉnh **độ cao phím**, **chia đôi bàn phím khi mở màn gập (Galaxy Fold)**, giao diện **sáng/tối**.

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

## Cài đặt (Android 8 trở lên) – làm theo thứ tự, bấm link trên điện thoại

**Bước 1 – Tải app:** 👉 [**Bấm vào đây để tải Keyboard AI (APK)**](https://github.com/ngocquyenyb1-sys/dich-ai-updates/raw/main/DichAI-0.9.19.apk)
- Link dự phòng (nếu link trên chậm): [tải qua jsDelivr](https://cdn.jsdelivr.net/gh/ngocquyenyb1-sys/dich-ai-updates@main/DichAI-0.9.19.apk)

**Bước 2 – Tắt chặn cài đặt (quan trọng, làm TRƯỚC khi mở file APK)**

Điện thoại có 2 lớp chặn app cài ngoài CH Play. Keyboard AI cần quyền Trợ năng + đọc thông báo để dịch trong khung chat nên sẽ bị chặn nếu không tắt tạm:

| | Lớp chặn | Cách tắt |
|---|---|---|
| 1 | **Auto Blocker** (chỉ máy Samsung: S25, S24, Z Fold/Flip…) | **Cài đặt** › **Bảo mật và quyền riêng tư** › **Auto Blocker** › **Tắt**. Nếu có mục **"Hạn chế tối đa"** cũng tắt. Không thấy thì gõ "Auto Blocker" vào ô tìm kiếm của Cài đặt. |
| 2 | **Google Play Protect** (mọi máy Android) | Mở **CH Play** › bấm **ảnh đại diện** (góc phải trên) › **Play Protect** › **⚙️** (góc phải trên) › tắt **cả 2**: "Quét ứng dụng bằng Play Protect" và "Cải thiện việc phát hiện ứng dụng có hại". |

Sau đó:
- Nếu trước đó đã bị chặn: **xoá file APK cũ** trong Tệp đã tải xuống rồi **tải lại** bằng link ở Bước 1.
- Mở file bằng app **Tệp của bạn (My Files)** › bấm file › **Cài đặt**. Máy hỏi "cho phép cài từ nguồn này" → bật **Cho phép**.

**Dấu hiệu bị chặn:**
- *"Đã chặn ứng dụng để bảo vệ thiết bị của bạn"* (chỉ có nút "Tôi hiểu") → chưa tắt Play Protect (lớp 2).
- Thông báo có chữ *Auto Blocker* / *"Chặn cài ứng dụng từ nguồn không xác định"* → chưa tắt Auto Blocker (lớp 1).

✅ **Cài xong nhớ BẬT LẠI cả 2** để máy vẫn được bảo vệ – app đã cài vẫn chạy bình thường.
🔄 **Khi app báo có bản mới:** nếu bấm cập nhật mà không cài được, tắt tạm Auto Blocker (trong app có nút mở nhanh), cập nhật xong bật lại.

**Bước 3 – Mở app Keyboard AI và bấm nút 👉 "Làm bước tiếp theo"** – app tự mở đúng màn hình cài đặt cho từng bước còn thiếu, có dòng "Còn N bước" để biết còn bao nhiêu:
1. Bật bàn phím → 2. Chọn bàn phím → 3. Trợ năng (dịch trong khung chat) → 4. Đọc thông báo → 5. Hiện thông báo → 6. Cho chạy nền.
- ⚠️ **Android 13 trở lên**, nếu bật Trợ năng mà hiện **"Ứng dụng đã bị từ chối cấp quyền"** (nút Đóng), hoặc Trợ năng bị mờ / báo "Cài đặt bị hạn chế": bấm nút **"Mở Thông tin ứng dụng"** trong app › ⋮ (góc phải trên) › **Cho phép cài đặt bị hạn chế**, rồi bấm lại 👉.

**Bước 4 – Lấy key AI** (chọn 1, trong app có nút 🔗 mở thẳng trang này):
- ChatGPT: [platform.openai.com/api-keys](https://platform.openai.com/api-keys)
- Gemini (có gói miễn phí): [aistudio.google.com/apikey](https://aistudio.google.com/apikey)
- Claude: [platform.claude.com/settings/keys](https://platform.claude.com/settings/keys)

Tạo key → sao chép → dán vào mục **2. Nhà cung cấp AI** trong app → **Lưu** → mục **Tự kiểm tra** để thử.

**Xong!** Mở Zalo / WeChat / WhatsApp / Outlook để dùng. Các bản sau app tự cập nhật (mục ⑧).

**Lưu ý:** một số app ngân hàng / VNeID yêu cầu tắt Trợ năng – tắt đi bàn phím vẫn dùng được, chỉ bảng dịch tự hiện tạm ngưng. App phát hành trực tiếp bằng APK, không qua Google Play. Gặp lỗi: trong app bấm **🐞 Gửi lỗi** (mục Tự kiểm tra).

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
- **Extras panel**: emoji, custom emoji from your photos, clipboard history, text shortcuts (/stk…), situation-based message templates, photo translation, read-aloud, voice typing, adjustable key height, split layout on foldables, light/dark theme.
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
Download the latest APK: [Keyboard AI APK](https://github.com/ngocquyenyb1-sys/dich-ai-updates/raw/main/DichAI-0.9.19.apk). On Android 13 and later, allow "restricted settings" for the app. Then tap 👉 "Next step" in the app – it opens each required settings screen in turn to enable the keyboard, notification access and accessibility. The app updates itself afterwards.

## Privacy
Screen text is read only to translate it, and is sent directly to the AI provider you choose. Password fields are never sent. No ads, no tracking.

---

© 2026 Quin. Bảo lưu mọi quyền · All rights reserved. Free to use; source code is not public.

Dictionary data: FrequencyWords by Hermit Dave (CC BY-SA 4.0).
