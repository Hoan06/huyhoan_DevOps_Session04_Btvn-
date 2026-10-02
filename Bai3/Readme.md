# Báo cáo Thực hành: Cấu hình xác thực SSH và Đẩy dự án lên GitHub

- **Họ và tên:** Nguyễn Huy Hoàn
- **Đường dẫn bài tập:** `homework/session_04/ex3/`
- **Địa chỉ Repository:** `git@github.com:<your-username>/<your-repo-name>.git`

---

## 1. Các bước thực hiện

### Bước 1: Tạo cặp khóa SSH với thuật toán Ed25519
Mở Git Bash hoặc Terminal và chạy lệnh sau để khởi tạo cặp khóa SSH mới:

```bash
ssh-keygen -t ed25519 -C "your_email@example.com"