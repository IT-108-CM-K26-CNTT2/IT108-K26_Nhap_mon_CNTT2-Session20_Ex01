# Bài 1 : Tối ưu từ khóa khi tìm kiếm tài liệu kỹ thuật
## 2. Hiện trường giả

Sinh viên đang dùng từ khóa: **"thầy ơi cho em xin tài liệu học html cơ bản của trang mozilla với ạ".**

## 3. Yêu cầu đầu ra
### Chỉ ra tại sao truy vấn trên là "Bad Query" (gây nhiễu).
-Sinh viên viết câu giao tiếp thay vì từ khóa. Google khớp cả những từ thừa với diễn đàn, trang hỏi đáp (nơi người ta hay viết “cho em xin...”) và bài quảng cáo khóa học. 
### Viết lại truy vấn sử dụng toán tử **site:** để khoanh vùng tên miền uy tín và toán tử **-** để loại bỏ các từ khóa quảng cáo/rác.
**site:developer.mozilla.org "Learn HTML" OR "HTML basics" -"đăng ký" -"giảm giá" -"khuyến mãi"**
### Giải thích ý nghĩa của việc sử dụng các toán tử này trong việc tiết kiệm thời gian lọc tin.
| Toán tử | Công dụng |
|---------|-----------|
| `site` | Lọc trước khi đọc: thu hẹp phạm vi về nguồn uy tín |
| `-`     | Lọc nhiễu trong phạm vi còn lại: loại trang chứa từ khóa quảng cáo/rác |
Kết hợp lại: người dùng không phải lướt qua nhiều trang kết quả, không phải đánh giá độ tin cậy từng nguồn, và tìm đúng tài liệu ngay ở những kết quả đầu tiên.
Minh chứng: nên chụp ảnh kết quả Google của truy vấn gốc và truy vấn mới, đặt cạnh nhau để so sánh. Số liệu thời gian hay số kết quả cần đọc nên lấy từ chính thử nghiệm của bạn, đừng tự đặt.
