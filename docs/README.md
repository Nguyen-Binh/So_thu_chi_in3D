# Sổ theo dõi tiền đề tài - GitHub Pages

Thư mục này chứa website tĩnh để đăng trực tiếp lên GitHub Pages.

## Cách xuất bản

1. Tạo một repository mới trên GitHub.
2. Tải toàn bộ nội dung trong thư mục `docs` lên repository.
3. Mở **Settings → Pages**.
4. Tại **Build and deployment**, chọn **Deploy from a branch**.
5. Chọn nhánh `main`, thư mục `/docs`, rồi nhấn **Save**.
6. Chờ GitHub cung cấp địa chỉ dạng `https://ten-tai-khoan.github.io/ten-repository/`.

Website giữ nguyên giao diện và nghiệp vụ hiện tại. Apps Script phiên bản 23 hoạt động như cầu nối dữ liệu ẩn; người dùng không nhìn thấy banner cảnh báo của Apps Script.

## Lưu ý

- Repository có thể để public vì tệp giao diện không chứa mã thành viên.
- Không sửa URL Apps Script trong `index.html` nếu chưa tạo deployment mới.
- Sau khi thay đổi giao diện, tải lại trang bằng Ctrl+F5 hoặc đóng và mở lại tab trên iPhone.
