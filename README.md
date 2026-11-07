# Tính khối lượng (PWA)

Ứng dụng Progressive Web App tính khối lượng theo công thức:

`Dài × Rộng × Cao ÷ mức chia`

## Tính năng

- Cài đặt: mức chia, đơn vị, ngưỡng làm tròn, OCR API key, tự động cập nhật (mặc định tắt)
- Camera / album, flash, overlay kết quả lên ảnh
- OCR (cloud OCR.space khi có key + online; fallback Tesseract)
- Lọc mã dạng `XXXX-YYYY`
- Lịch sử 50 phép tính, chia sẻ Zalo
- PWA offline (cache cơ bản)

## Chạy local

```bash
cd TinhKhoiLuong_V2_PWA
python -m http.server 8080
```

Mở `http://localhost:8080` (không mở bằng `file://`).

## Phiên bản

V4.0
