# Bounce Fitness – Massage website (e-commerce style)

Site tĩnh bằng HTML + CSS thuần (không JavaScript, không cần build).

## Cấu trúc

| File | Nội dung |
|---|---|
| `index.html` | Trang chủ: hero, catalog 4 massage, offer $30, benefits, 3 bước đặt lịch, locations, FAQ, CTA |
| `massages.html` | Danh mục tất cả massage |
| `massage-relaxation.html`, `massage-sports.html`, `massage-deep-tissue.html`, `massage-wellness.html` | Trang chi tiết từng dịch vụ (giá $30 / gạch $45) |
| `booking.html`, `booking-<tên>.html` | Trang đặt lịch kiểu checkout (mỗi dịch vụ một bản chọn sẵn đúng massage) |
| `locations.html`, `benefits.html`, `about.html`, `contact.html`, `legal.html` | Các trang còn lại |
| `css/style.css` | Toàn bộ giao diện |
| `images/` | 10 ảnh đã tối ưu (JPG nhẹ) |

## Đưa lên GitHub Pages

1. Tạo repository mới (Public) trên github.com.
2. **Add file → Upload files**, kéo toàn bộ nội dung thư mục này vào (`index.html` phải nằm ngoài cùng) rồi **Commit changes**.
3. **Settings → Pages → Deploy from a branch → main → / (root) → Save**.
4. Sau 1–2 phút web chạy tại `https://tenban.github.io/ten-repo/`.

## Lưu ý

- Form đặt lịch và liên hệ dùng `mailto:` (mở ứng dụng email của khách). Muốn nhận form trực tiếp, đổi `action` sang dịch vụ như Formspree hoặc Getform.
- Trang đặt lịch **chưa thu tiền**. Muốn thanh toán online cần gắn Stripe/PayPal/Square (cần backend hoặc link thanh toán).
- Tóm tắt đơn bên phải trang đặt lịch tự cập nhật bằng CSS `:has()` (trình duyệt hiện đại đều hỗ trợ).
- `legal.html` chỉ là nội dung mẫu, hãy thay bằng nội dung pháp lý chính thức.
