# Quy Trình Báo Lỗi & Xử Lý Sự Cố (Bug Reporting)

Văn hóa của TechNova là: Giải quyết vấn đề nhanh chóng bằng cách cung cấp thông tin rõ ràng. Càng cung cấp đủ bối cảnh, đồng đội càng dễ giúp bạn.

## 1. Kỹ năng Tra cứu tự chủ (Level 1 Support)
Trước khi hỏi người khác, hãy thử:
- **Google Dorking:** Sử dụng cú pháp `site:stackoverflow.com "Nguyên văn dòng lỗi"`.
- **Hỏi AI (ChatGPT/Claude):** Sử dụng cấu trúc Prompt 3 phần:
  1. *Ngữ cảnh:* Ngôn ngữ, framework đang dùng (VD: React 18, NodeJS 20).
  2. *Mã lỗi:* Copy paste chính xác toàn bộ log lỗi báo đỏ.
  3. *Mục tiêu:* Bạn đang muốn đoạn code này làm gì.

## 2. Template Báo Lỗi Chuẩn (Dùng cho Jira / Trello / Slack)
Khi cầu cứu IT, Mentor hoặc Leader, **tuyệt đối không nhắn** *"Anh ơi code em bị lỗi"* hay *"Hệ thống hỏng rồi"*. Hãy copy mẫu sau:

**Tiêu đề:** [Phân hệ/Tính năng] - Tóm tắt ngắn gọn lỗi (VD: [Login] - Không thể đăng nhập bằng Google trên Chrome)

**1. Context (Bối cảnh xảy ra lỗi):**
- Môi trường: Production (Thực tế) hay Local (Máy cá nhân)?
- Trình duyệt/Hệ điều hành: Chrome 120, Windows 11.
- URL màn hình lỗi: `https://app.technova...`

**2. Steps to Reproduce (Các bước tái hiện lỗi):**
- Bước 1: Mở trang đăng nhập.
- Bước 2: Nhập email `abc@technova...`
- Bước 3: Bấm nút "Đăng nhập".

**3. Expected Behavior (Kết quả mong muốn):**
- Nút đăng nhập loading, chuyển hướng vào Dashboard thành công.

**4. Actual Behavior (Kết quả thực tế):**
- Nút bấm không phản hồi, hiện thông báo nhỏ "Network Error 500" ở góc phải.
