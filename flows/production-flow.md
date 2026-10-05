# Production Flow

Quy trình sản xuất in ấn.

## Mục tiêu

Biến file đã duyệt và lệnh sản xuất thành thành phẩm sẵn sàng giao.

## Các bước

1. **Nhận lệnh** — Kiểm tra file, vật liệu, số lượng, deadline.
2. **Chuẩn bị** — Chọn máy, vật liệu, gia công.
3. **In thử / duyệt** — Nếu khách yêu cầu mẫu.
4. **In chính** — Sản xuất theo thông số.
5. **Gia công** — Cắt, cán, bế, may, khoen, lắp ráp.
6. **Kiểm tra** — Đối chiếu màu, kích thước, số lượng.
7. **Bàn giao** — Đóng gói, sẵn sàng giao; cập nhật kế toán.

## Agent tham gia

- Production Agent (chủ trì)
- Design Agent (sửa file nếu lỗi kỹ thuật)
- Sales Agent (liên hệ khách khi đổi deadline / mẫu)
- Accounting Agent (chi phí phát sinh)
- CEO Agent (nút thắt tiến độ)

## Kết quả

Lệnh có trạng thái: `queued` → `printing` → `finishing` → `ready` → `delivered`.

## Phiên bản

v0.1
