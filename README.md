# Landing Page - Kẹp Tăng Phồng Chân Tóc Không Dây

Landing page bán hàng COD, chạy quảng cáo Facebook + TikTok, lưu lead về Google Sheet.

## File

- `index.html` — trang landing chính
- `chinh-sach-bao-mat.html` — chính sách bảo mật
- `dieu-khoan-su-dung.html` — điều khoản dịch vụ

## Host bằng GitHub Pages

1. Vào repo trên GitHub → **Settings → Pages**
2. Source: **Deploy from a branch** → Branch: **main** → thư mục **/ (root)** → Save
3. Đợi 1-2 phút, trang chạy tại `https://<tên-github>.github.io/<tên-repo>/`

## Lưu ý bảo mật

File Google Apps Script (`google-apps-script.gs`) chứa khóa bí mật máy chủ, KHÔNG được đưa vào repo công khai. File này đã bị loại qua `.gitignore`.
