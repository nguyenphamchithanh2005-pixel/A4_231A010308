Nội dung thực hiện Yêu cầu Nâng cao
1. Nâng cao 1 (NC1): Bổ sung tính năng Tính Phần trăm (%) và Đổi dấu (±)
   Tính năng Phần trăm (%) Mô tả: Cho phép người dùng tính nhanh giá trị phần trăm của số nhập vào (chia cho 100).
   Cách thực hiện trong code (MainActivity.java):Gán sự kiện OnClickListener cho nút btnPhanTram.
   Lấy giá trị từ ô nhập liệu edtSoA (hoặc edtSoB).
   Cập nhật kết quả hiển thị lên tvKetQua và tự động cập nhật lại vào ô nhập liệu.

   Tính năng Đổi dấu (±)Mô tả: Đổi nhanh giá trị số từ dương sang âm hoặc ngược lại.
   Cách thực hiện trong code (MainActivity.java):Gán sự kiện OnClickListener cho nút btnDoiDau.
   Lấy giá trị hiện tại và đảo dấu bằng cách nhân với -1 ($A_{mới} = A \times -1$).
   Cập nhật lại kết quả lên giao diện.

   2. Nâng cao 3 (NC3): Đổi màu sắc hiển thị phân loại kết quả BMI
      Mô tả tính năng: Thêm phản hồi trực quan sinh động cho người dùng bằng cách thay đổi màu sắc chữ (textColor) của dòng phân loại kết quả BMI tương ứng với từng mức độ sức khỏe.
      Quy tắc tô màu theo trạng thái BMI:
      Bình thường: Hiển thị màu Xanh lá (Green) 🟢 — Chỉ số lý tưởng.
      Thiếu cân: Hiển thị màu Cam (Orange) 🟠 — Cảnh báo nguy cơ thừa cân.
      Béo phì: Hiển thị màu Đỏ (Red) 🔴 — Cảnh báo nguy cơ béo phì.
