# Báo cáo Thực hành: Quản lý tệp tin bỏ qua (.gitignore) và Sửa lịch sử (Amend)

- **Họ và tên:** Nguyễn Huy Hoàn
- **Đường dẫn bài tập:** `homework/session_04/ex4/`

---

## 1. Bối cảnh & Yêu cầu
Vô tình commit nhầm file chứa thông tin nhạy cảm `credentials.txt` vào Git. Cần gỡ bỏ file này khỏi sự theo dõi (Index/Staging Area) mà không xóa file vật lý trong ổ cứng, cấu hình `.gitignore` để tránh commit lại và sửa lại thông điệp commit gần nhất cho sạch sẽ.

---

## 2. Các bước thực hiện

### Bước 1: Gỡ bỏ file `credentials.txt` khỏi cache theo dõi của Git
Sử dụng cờ `--cached` để loại bỏ tệp tin khỏi Git Index nhưng vẫn giữ nguyên tệp vật lý trong thư mục làm việc cục bộ:

```bash
git rm --cached credentials.txt