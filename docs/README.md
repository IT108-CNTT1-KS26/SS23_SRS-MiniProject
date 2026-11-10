# Hệ thống Không gian số TechNova (TechNova Onboarding Kit)

Chào mừng bạn đến với TechNova! Dự án này cung cấp toàn bộ hướng dẫn, biểu mẫu và quy trình chuẩn để giúp nhân viên mới (Onboardees) thiết lập không gian làm việc số an toàn, bảo mật và hiệu quả nhất.

##  Hướng dẫn sử dụng & Cài đặt
```bash
# 1. Clone repository về máy tính cá nhân/công ty
git clone https://github.com/your-username/IT108-K26_NhapMonCNTT_MiniProject_TechNova.git

# 2. Di chuyển vào thư mục dự án
cd IT108-K26_NhapMonCNTT_MiniProject_TechNova

# 3. Khởi tạo môi trường bảo mật (Mô phỏng)
cp security/.env.example .env
```

##  Checklist Onboarding Nâng Cao
- [ ] **Bước 1:** Hoàn tất thiết lập thư mục Cloud Workspace bằng Google Drive for Desktop (Đồng bộ `docs`, `cloud-workspace`,...).
- [ ] **Bước 2:** Phân tách không gian mạng bằng cách tạo 2 Browser Profile riêng biệt: `Personal` và `TechNova_Work`.
- [ ] **Bước 3:** Cài đặt các Extension bắt buộc (Bitwarden, uBlock Origin) và cấu hình Bookmark dự án.
- [ ] **Bước 4:** Bật Xác thực 2 yếu tố (2FA) qua Authenticator App cho GitHub, Google Workspace, và các hệ thống nội bộ.
- [ ] **Bước 5:** Đọc tài liệu `mau-bao-cao-loi.md` để nắm vững quy trình tạo Bug Report và giao tiếp với đội ngũ IT/Dev.

## Bảng Trang Thiết Bị & Tài Khoản Cấp Phát
| Hạng mục | Nền tảng / Công cụ | Quyền hạn / Trạng thái | Ghi chú quan trọng |
|---|---|---|---|
| **Email Công ty** | Google Workspace | User / Đã cấp | Chỉ dùng giao dịch công việc, không đăng ký dịch vụ cá nhân. |
| **Lưu trữ Cloud** | Google Drive | Editor (Share Drive) | Tuân thủ nghiêm ngặt bảng phân quyền. |
| **Mã nguồn** | GitHub Enterprise | Developer / Tự tạo | Bắt buộc bật 2FA, không commit mã bí mật (credentials). |
| **Bảo mật Pass** | Bitwarden | Premium / Tự cài | Master Password phải >16 ký tự. |
| **Giao tiếp** | Slack / Lark | Member / Đã cấp | Tham gia kênh #onboarding, #general, #it-support. |

##  Hỗ Trợ Kỹ Thuật (IT Helpdesk)
- Nếu gặp lỗi trong quá trình cài đặt, vui lòng tạo ticket hoặc gửi tin nhắn vào kênh Slack **#it-support** theo mẫu trong thư mục `troubleshooting/`.
- Email liên hệ khẩn cấp: it-support@technova.example.com
