# Hệ thống khảo sát (HeThongKhaoSat)

- `index.html`: trang khảo sát công khai (danh sách khảo sát, `?s=<slug>` để mở một khảo sát).
- `quan-tri.html`: trang quản trị (đăng nhập bằng tài khoản Supabase được cấp quyền).

Backend: Supabase (Postgres, Auth, Storage). Cấu hình `SB` và `KEY` (khóa publishable) ở đầu phần script mỗi file.
Chạy thử trên máy: `npx serve site` rồi mở `http://localhost:3000/quan-tri.html`.
