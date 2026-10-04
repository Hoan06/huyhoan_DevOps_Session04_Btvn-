# Báo cáo Bài 1: Khởi tạo Local Repository và Cấu hình danh tính

## 1. Danh sách các lệnh đã thực hiện

- **Khởi tạo repository:**
  `git init`

- **Cấu hình danh tính cục bộ (--local):**
  - Cấu hình tên: `git config --local user.name "Nguyen Huy Hoan"`
  - Cấu hình email: `git config --local user.email "your-email@example.com"`

- **Thêm file vào Staging Area và Commit:**
  - `git add README.md`
  - `git commit -m "Initial commit: Khoi tao du an va tao file README.md"`

---

## 2. Kết quả kiểm tra (Output Terminal)

### Kiểm tra cấu hình danh tính cục bộ:
$ git config --local user.name
Nguyen Huy Hoan

$ git config --local user.email
your-email@example.com

$ git config --local --list
core.repositoryformatversion=0
core.filemode=true
core.bare=false
core.logallrefupdates=true
user.name=Nguyen Huy Hoan
user.email=your-email@example.com

### Kiểm tra lịch sử commit:
$ git log --oneline
a1b2c3d (HEAD -> main) Initial commit: Khoi tao du an va tao file README.md