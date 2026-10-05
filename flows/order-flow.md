# Order Flow

Quy trình nhận và xử lý đơn hàng.

## Mục tiêu

Đưa yêu cầu khách hàng từ tiếp nhận đến đơn đã chốt, sẵn sàng thiết kế / sản xuất.

## Các bước

1. **Tiếp nhận** — Sales thu thập nhu cầu, kích thước, số lượng, deadline.
2. **Tư vấn** — Đối chiếu `printing-materials.md` và khả năng sản xuất.
3. **Báo giá** — Tính theo `pricing.md`, gửi khách.
4. **Chốt đơn** — Xác nhận nội dung, giá, thời gian giao.
5. **Brief thiết kế** — Chuyển Design nếu cần làm / duyệt file.
6. **Lệnh sản xuất** — Production nhận thông số và file đã duyệt.
7. **Kế toán** — Ghi nhận tạm ứng / công nợ.

## Agent tham gia

- Sales Agent (chủ trì)
- Design Agent
- Production Agent
- Accounting Agent
- CEO Agent (đơn lớn / rủi ro / ưu tiên)

## Kết quả

Đơn có trạng thái: `draft` → `quoted` → `confirmed` → `in_production`.

## Phiên bản

v0.1
