# Chính sách bảo mật — VsScience

Cập nhật: 30/10/2026

VsScience là app máy tính giúp bạn làm việc với tài liệu (PDF, Word, Excel…) cùng Claude. Chính sách này cho biết app xử lý dữ liệu của bạn như thế nào.

## Tóm tắt

- Tài liệu của bạn **nằm trên máy của bạn**. VsScience không có máy chủ riêng và không thu thập dữ liệu của bạn.
- App **không** có quảng cáo, **không** theo dõi hành vi sử dụng, **không** gửi thống kê về cho nhà phát triển.
- Nội dung bạn trao đổi với Claude được gửi tới Anthropic (nhà phát triển Claude) qua tài khoản Claude của chính bạn.

## Dữ liệu được gửi đi đâu

| Khi nào | Gửi tới | Nội dung |
|---|---|---|
| Bạn trò chuyện với Claude | Anthropic | Câu hỏi, hình ảnh bạn đính kèm, và phần nội dung tài liệu Claude đọc để trả lời. Anthropic xử lý theo [chính sách bảo mật của Anthropic](https://www.anthropic.com/legal/privacy). |
| Đăng nhập tài khoản Claude | Anthropic | Đăng nhập do công cụ Claude Code của Anthropic thực hiện. Thông tin đăng nhập lưu trên máy bạn, app không gửi cho ai khác. |
| Kiểm tra bản cập nhật, xem "Có gì mới" | GitHub | Yêu cầu thông tin phiên bản mới nhất. Không kèm dữ liệu cá nhân. |
| Chỉ khi bạn bật đồng bộ OneDrive | Microsoft | Các file trong thư mục bạn chọn đồng bộ, qua tài khoản Microsoft của bạn. |
| Chỉ khi bạn bật "Cho máy khác kết nối" | Máy bạn đã ghép nối | Tài liệu và đoạn chat của thư mục đang mở, truyền trực tiếp giữa các máy của bạn. |
| Chỉ khi bạn kết nối Outlook | Microsoft | Đọc thư, file đính kèm và chuỗi thư bạn hoặc agent cần; tạo thư nháp; gửi thư khi bạn cho phép. |
| Chỉ khi bạn kết nối Google | Google | Đọc, sửa, tạo bảng tính (Sheets), tài liệu (Docs), bài trình chiếu (Slides) bạn hoặc agent cần làm việc. |
| Chỉ khi bạn bật Gmail cho một tài khoản Google | Google | Tìm và đọc thư, chuỗi thư, file đính kèm bạn hoặc agent cần; tạo thư nháp; gửi thư khi bạn cho phép. |

## Tài khoản Outlook và Google bạn kết nối

- Bạn đăng nhập trên trang của Microsoft / Google trong trình duyệt; **mật khẩu không đi qua VsScience**.
- App chỉ lưu mã đăng nhập (refresh token) **trên máy bạn**, được mã hóa bằng kho bảo mật của hệ điều hành khi có. Không gửi về nhà phát triển hay bên thứ ba nào.
- Dữ liệu đọc từ Outlook / Google chỉ được dùng để làm việc bạn yêu cầu trong app. Phần nội dung cần cho việc đó được gửi tới Anthropic qua tài khoản Claude của bạn, như mọi cuộc trò chuyện khác.
- Gửi thư và sửa file có sẵn chỉ diễn ra khi bạn cho phép (hỏi trong chat hoặc theo cài đặt duyệt của agent).
- **Gmail là tùy chọn riêng:** app chỉ xin quyền Gmail khi bạn bấm "Bật Gmail" cho một tài khoản Google. Khi đó app đọc thư bạn hoặc agent cần để làm việc bạn giao (ví dụ tìm thư trả lời của diễn giả, đọc file đính kèm), tạo thư nháp và gửi thư khi bạn cho phép. App không xóa thư, không tự động quét hay lưu trữ toàn bộ hộp thư; thư đọc được không được lưu lại ngoài đoạn chat trên máy bạn và file đính kèm bạn yêu cầu lưu vào thư mục.
- Bạn gỡ kết nối bất cứ lúc nào trong app (Kết nối → nút gỡ tài khoản), và có thể thu hồi quyền tại https://myaccount.google.com/permissions hoặc https://account.live.com/consent/Manage (tài khoản trường / công ty: https://myapps.microsoft.com).

**Google API:** VsScience sử dụng và chuyển giao thông tin nhận được từ Google API tuân theo [Chính sách dữ liệu người dùng của Google API Services](https://developers.google.com/terms/api-services-user-data-policy), bao gồm các yêu cầu Sử dụng giới hạn (Limited Use). Dữ liệu Google không được bán, không dùng cho quảng cáo, không dùng để huấn luyện mô hình AI chung, và không ai đọc trừ khi bạn đồng ý hoặc pháp luật yêu cầu.

## Dữ liệu lưu trên máy bạn

Đoạn chat, bản lưu tài liệu, lưu ý cho Claude và cài đặt được lưu trong thư mục tài liệu của bạn và thư mục dữ liệu của app trên máy. Bạn có thể xóa bất cứ lúc nào bằng cách xóa các thư mục này hoặc gỡ app.

## Trẻ em

App không dành riêng cho trẻ em và không cố ý thu thập dữ liệu của trẻ em.

## Điều khoản sử dụng

Xem https://toniqhz.github.io/vsScience-Release/TERMS.html

## Liên hệ

Câu hỏi về chính sách này: tạo issue tại https://github.com/toniqhz/vsScience-Release/issues.

---

# Privacy Policy — VsScience (English)

VsScience is a desktop app for working with documents together with Claude.

- Your documents stay on your computer. VsScience has no servers of its own and collects no personal data, analytics or telemetry.
- Messages, attached images and document excerpts you discuss with Claude are sent to Anthropic through your own Claude account, under [Anthropic's Privacy Policy](https://www.anthropic.com/legal/privacy).
- Update checks contact GitHub (no personal data). OneDrive sync (Microsoft) and device-to-device connection are used only if you turn them on.
- **Connected Outlook and Google accounts** (only if you connect them): VsScience reads mail and attachments, creates drafts, and sends mail only with your permission (Microsoft Graph); it reads, edits and creates Google Sheets, Docs and Slides you or your agent work with. You sign in on Microsoft's / Google's own page; your password never passes through VsScience. Sign-in tokens are stored only on your computer, encrypted with the operating system's secure storage when available. Data is used only to do what you ask in the app; content needed for that is sent to Anthropic through your Claude account. You can disconnect in the app at any time and revoke access at https://myaccount.google.com/permissions or https://account.live.com/consent/Manage.
- **Gmail (optional, per account):** VsScience requests Gmail access only when you choose "Enable Gmail" for a Google account. It then searches and reads the messages, threads and attachments needed for the task you give, creates drafts, and sends mail only with your permission. It does not delete mail and does not scan or archive your mailbox; messages it reads are kept only in the chat on your computer and in attachments you ask it to save to your folder.
- **Google API:** VsScience's use and transfer of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements. Google user data is not sold, not used for advertising, not used to train general AI models, and not read by humans except with your consent or where required by law.
- Chats, snapshots and settings are stored locally; uninstalling the app or deleting those folders removes them.

Terms of Service: https://toniqhz.github.io/vsScience-Release/TERMS.html

Contact: https://github.com/toniqhz/vsScience-Release/issues
