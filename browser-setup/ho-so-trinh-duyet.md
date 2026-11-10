# Hướng dẫn Thiết Lập Trình Duyệt Chuyên Nghiệp

Để đảm bảo năng suất và bảo mật, TechNova yêu cầu nhân viên tuân thủ các chuẩn mực thiết lập trình duyệt sau (Khuyến nghị dùng Google Chrome hoặc Microsoft Edge).

## 1. Phân tách Profile Trình Duyệt
Tuyệt đối không dùng chung một cửa sổ cho việc công ty và việc nhà.
-  **Profile Work (TechNova):** Đăng nhập bằng email công ty. Đồng bộ Bookmark, History công việc. Cài đặt các extension phục vụ Dev/Design.
-  **Profile Personal:** Đăng nhập bằng email cá nhân. Dùng để xem YouTube, mạng xã hội, tài chính cá nhân.

## 2. Tổ chức Bookmark (Dấu trang) siêu tốc
Hiển thị thanh Bookmark (Ctrl + Shift + B) và chia thành 4 thư mục:
1.  `01_Daily`: Email, Lịch, Lark/Slack web.
2.  `02_Projects`: Jira, Trello, Figma, GitHub repo hiện tại.
3.  `03_Docs`: Sổ tay công ty, API Documentation, StackOverflow.
4.  `04_Tools`: Các công cụ chuyển đổi JSON, Base64, Regex testing.

## 3. Extension (Tiện ích mở rộng) Bắt buộc
Để chống mã độc và tăng hiệu suất, yêu cầu cài đặt và giới hạn quyền các tiện ích sau:
-  **Bảo mật:** Bitwarden (Quản lý mật khẩu), uBlock Origin (Chặn quảng cáo/mã độc).
-  **Dev (Cho team IT):** React Developer Tools, JSON Formatter, Wappalyzer.
-  **Productivity:** Grammarly (Hỗ trợ viết tiếng Anh), Notion Web Clipper.
*Lưu ý bảo mật: Vào `Manage Extensions`, chọn `Site access` -> Đổi từ `On all sites` sang `On click` để tránh bị extension đọc lén dữ liệu trên mọi trang web.*

## 4. Bỏ túi kỹ năng Developer Tools (F12)
Là nhân viên công nghệ, bạn cần biết các thao tác cơ bản:
- **Xóa Cache mạnh (Hard Reload):** Bấm `Ctrl + Shift + R` (hoặc mở F12, chuột phải vào nút Refresh -> Empty Cache and Hard Reload).
- **Kiểm tra Network:** Mở tab `Network`, lọc theo `Fetch/XHR` để xem các API gọi đi có bị lỗi 404, 500 hay không.
- **Xóa Cookie rác:** Mở tab `Application` -> `Cookies` -> Xóa các cookie hỏng gây lỗi đăng nhập.
