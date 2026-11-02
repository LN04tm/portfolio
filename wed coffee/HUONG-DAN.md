# Web menu QR – hướng dẫn dùng lại cho khách

## Đổi sang quán mới (5–10 phút)
Mở `index.html`, chỉ sửa 3 chỗ:
1. `SHOP` – tên quán, số điện thoại, Zalo, địa chỉ, giờ mở/đóng cửa.
2. `MENU` – danh mục và món (`vi`, `en`, `price` tính bằng nghìn đồng, `hot:true` = gắn nhãn "Bán chạy").
3. `:root` trong `<style>` – màu chủ đạo (`--brand`, `--accent`) theo màu logo của quán.

## Đưa lên mạng (miễn phí)
1. Vào https://app.netlify.com/drop
2. Kéo cả thư mục chứa `index.html` vào.
3. Nhận link dạng `ten-quan.netlify.app` (đổi tên trong Site settings).
4. Muốn tên miền riêng (`tenquan.vn`) thì khách mua tên miền, gắn vào Netlify trong Domain settings.

## Tạo mã QR
- Dán link Netlify vào trình tạo QR miễn phí (hoặc Canva → Ứng dụng → QR code).
- In kèm tên quán và chữ "Quét để xem menu & gọi món", dán lên bàn, kích thước tối thiểu 3×3 cm.

## Tính năng có sẵn
- Menu song ngữ Việt / Anh, tìm món không cần gõ dấu.
- Trạng thái "Đang mở / Đã đóng cửa" tự đổi theo giờ.
- Chọn món → giỏ hàng → gửi đơn qua tin nhắn SMS hoặc sao chép gửi Zalo.
- Nút gọi điện, Zalo, chỉ đường Google Maps.
- Tự đổi giao diện tối theo điện thoại.
