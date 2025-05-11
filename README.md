# 📊 Dự án Theo Dõi Thu Chi Cá Nhân 2024 với Looker Studio

Dự án sử dụng Google Looker Studio để trực quan hóa dữ liệu chi tiêu cá nhân trong năm 2024. Dữ liệu được nhập thủ công từ Google Sheets và chia thành nhiều danh mục chi tiêu như: sức khỏe, mua sắm, ăn uống, di chuyển, cho vay...

## 🚀 Mục tiêu

- Hiểu rõ mô hình chi tiêu cá nhân theo thời gian và danh mục
- Quản lý hiệu quả các khoản chi lớn
- Phân tích tỷ lệ chi tiêu theo dạng biểu đồ trực quan
- Theo dõi xu hướng rút tiền, thanh toán

## 🔗 Dashboard

Ảnh minh họa Looker Studio dashboard:

![Dashboard](./dashboard-preview.png)

## 📁 Dữ liệu nguồn

Dữ liệu được lưu trữ trong Google Sheets gồm các cột:

| Cột              | Mô tả |
|------------------|------|
| `Datetime`        | Ngày giờ giao dịch (dùng cho lọc và sắp xếp theo thời gian chính xác) |
| `Mã chi tiêu`     | Mã định danh riêng cho từng giao dịch (có thể dùng để truy xuất nhanh) |
| `Ngày tháng`      | Ngày giao dịch ở định dạng thân thiện để hiển thị (ví dụ: 28/03/2024) |
| `Loại chi tiêu`   | Nhóm chi tiêu như: Sức khỏe, Mua sắm, Ăn uống, Di chuyển... |
| `Số tiền`         | Giá trị giao dịch |
| `Loại tiền`       | Đơn vị tiền tệ (VND, USD...) nếu có hỗ trợ đa tiền tệ |
| `Địa điểm`        | Nơi phát sinh giao dịch (cửa hàng, địa chỉ, khu vực, online...) |
| `Ghi chú`         | Diễn giải chi tiết về giao dịch |
| `Loại thanh toán` | Phương thức thanh toán (tiền mặt, tài khoản, thẻ, ví điện tử...) |
| `Loại ngân hàng`  | Nếu thanh toán qua tài khoản, ghi rõ ngân hàng (VD: MB, TPBank...) |
| `Tiêu chí`        | Dùng để đánh dấu theo chủ đề, mục đích, ưu tiên... (có thể dùng cho lọc nâng cao) |
| `Loại giao dịch`  | Phân biệt thu/chi hoặc nhóm giao dịch như "Rút tiền", "Chuyển khoản", "Chi thường xuyên", v.v. |

## ⚙️ Công cụ sử dụng

- Google Sheets
- Google Looker Studio
- Excel (để xử lý file tạm thời)

## 🧠 Ghi chú

Dự án mang tính cá nhân nhưng có thể mở rộng để áp dụng vào quản lý tài chính gia đình hoặc nhóm nhỏ.
