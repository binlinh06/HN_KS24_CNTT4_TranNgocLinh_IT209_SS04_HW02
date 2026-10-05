# Bài 2: Quản lý nhánh và giải quyết xung đột

## Các bước thực hiện haaaaaa

## Các bước thực hiện nhe

1. Tạo nhánh `feature-update` từ `main`.
2. Chỉnh sửa file `README.md` trên nhánh `feature-update`.
3. Commit thay đổi trên nhánh `feature-update`.
4. Chuyển về nhánh `main`.
5. Chỉnh sửa cùng dòng trong `README.md` trên nhánh `main`.
6. Commit thay đổi trên `main`.
7. Thực hiện `git merge feature-update` để tạo Merge Conflict.
8. Mở `README.md` và xử lý thủ công các ký hiệu:
   - `<<<<<<<`
   - `=======`
   - `>>>>>>>`
9. Xóa các ký hiệu conflict và giữ lại nội dung mong muốn.
10. Chạy `git add README.md`.
11. Tạo merge commit bằng `git commit`.
12. Kiểm tra lịch sử bằng `git log --graph --oneline`.

## Kết quả

Merge Conflict đã được giải quyết thủ công thành công.

Lịch sử commit hiển thị nhánh `feature-update` tách từ `main`
và sau đó được gộp trở lại bằng một merge commit.