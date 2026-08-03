# Notion Widgets

Bộ widget cá nhân để nhúng vào Notion, giao diện tối giản trắng–đen.

## Widget hiện có

- `/weather/` — thời tiết hiện tại và dự báo 5 ngày, hiển thị °C.
- `/pomodoro/` — Pomodoro 25/5/15 phút, có tạm dừng, đặt lại, đếm phiên và âm báo.

## Sử dụng trong Notion

Sau khi deploy lên Vercel, dùng các URL:

```text
https://TEN-DU-AN.vercel.app/weather/
https://TEN-DU-AN.vercel.app/pomodoro/
```

Trong Notion, gõ `/embed`, dán URL của widget rồi chọn **Embed link**.

## Thêm widget mới

Tạo một thư mục mới ở thư mục gốc, ví dụ:

```text
clock/index.html
```

Sau khi push lên nhánh `main`, Vercel sẽ deploy lại dự án. Các URL cũ không thay đổi.
