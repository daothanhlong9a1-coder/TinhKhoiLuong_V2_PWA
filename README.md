# Tính khối lượng (PWA)

Repo: https://github.com/daothanhlong9a1-coder/TinhKhoiLuong_V2_PWA

## Trạng thái đồng bộ

Đã có trên GitHub:
- `sw.js` (V4.1)
- `manifest.webmanifest`
- `icon.svg`
- `README.md`

Cần upload thêm từ máy local (kéo thả trên GitHub hoặc `git push`):
- `index.html` (bản đầy đủ ~20KB)
- `app.js` (logic app ~27KB)

File đầy đủ nằm trong thư mục dự án `TinhKhoiLuong_V2_PWA/`.

### Upload nhanh trên GitHub

1. Mở repo → **Add file** → **Upload files**
2. Kéo `index.html` + `app.js` từ thư mục local
3. Commit

### Hoặc git

```bash
git clone https://github.com/daothanhlong9a1-coder/TinhKhoiLuong_V2_PWA.git
cd TinhKhoiLuong_V2_PWA
# copy index.html và app.js bản đầy đủ vào đây
git add index.html app.js
git commit -m "V4.1 full app"
git push
```

## Chạy local

```bash
python -m http.server 8080
```

Mở `http://localhost:8080` (không dùng `file://`).

## Phiên bản

V4.1 — auto-update toggle (mặc định tắt), camera, OCR, lọc mã XXXX-YYYY
