# Sổ Tay Kỹ Năng An Toàn Thông Tin Toàn Diện

Đây là danh sách kiểm tra (checklist) sinh tử đối với mọi nhân sự TechNova. Vui lòng tick (x) vào các ô sau khi bạn đã hoàn thành.

## A. Quản lý Tài khoản & Mật khẩu
- [ ] Tôi đã cài đặt **Bitwarden** (hoặc 1Password, LastPass) và KHÔNG lưu mật khẩu trên trình duyệt.
- [ ] Tôi sử dụng nguyên tắc "1 Tài khoản - 1 Mật khẩu riêng biệt".
- [ ] Mật khẩu Master của tôi dài từ 16-32 ký tự, bao gồm chữ hoa, chữ thường, số và ký tự đặc biệt.
- [ ] Tôi đã bật **Xác thực 2 yếu tố (2FA / TOTP)** bằng ứng dụng (Google Authenticator, Authy, Microsoft Authenticator) cho Email, GitHub và Jira.
- [ ] Tôi đã in hoặc lưu trữ an toàn các mã Backup Codes của 2FA.

## B. Thiết bị & Không gian mạng
- [ ] Laptop làm việc luôn được khóa màn hình (`Windows + L` hoặc `Ctrl + Cmd + Q`) mỗi khi tôi rời khỏi bàn.
- [ ] Tôi không sử dụng Wifi công cộng (quán cafe, sân bay) để truy cập hệ thống công ty mà không bật VPN.
- [ ] Máy tính tôi đã bật Firewall và Windows Defender (hoặc phần mềm Anti-virus tương đương).
- [ ] Tôi tuyệt đối không tải, cài đặt phần mềm crack/lậu trên máy tính làm việc.

## C. Quản lý Mã Nguồn (Dành cho Dev)
- [ ] Tôi KHÔNG BAO GIỜ hard-code (viết cứng) mật khẩu, chuỗi kết nối Database, API Key vào thẳng mã nguồn.
- [ ] Tôi sử dụng file `.env` để lưu trữ biến môi trường cục bộ.
- [ ] Tôi luôn kiểm tra chắc chắn file `.env` đã được liệt kê trong `.gitignore` trước khi gõ lệnh `git commit`.

## D. Nhận diện Lừa đảo (Phishing)
- [ ] Tôi luôn kiểm tra kỹ đường link URL trước khi nhập mật khẩu (Đề phòng Typosquatting: `g00gle.com` thay vì `google.com`).
- [ ] Tôi cảnh giác với các email giả danh sếp, HR yêu cầu chuyển tiền hoặc tải file đính kèm lạ (.exe, .zip, .scr).
