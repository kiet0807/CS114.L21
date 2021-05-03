# CS114.L21 - ML

## BÀI TẬP QUÁ TRÌNH

- Mỗi nhóm tìm dăm ba ví dụ về bài toán regression TRONG THỰC TẾ
- Ghi rõ input, output và cách thu thập + xử lý data, commit vào github repository và dẫn link lên Google Classroom.

## NHÓM THỰC HIỆN

- 15520404 - Nguyễn Văn Kiệt
- 19522444 - Phan Lê Xuân Trường
- 19521533 - Lê Duy Hoàng

## BÀI TOÁN

### Ví dụ 1:

- Input: Tuổi của nhân viên.
- Output: Tiền lương của nhân viên.
- Thu thập data: Data là dữ liệu số, bao gồm x là số tuổi của nhân viên, là tiền lương của họ.
- Xử lý data: Giả thuyết đưa ra y = a + bx, tìm 2 hệ số a,b bằng Gradient Descent

### Ví dụ 2:

- Input: tổng trọng lượng tính bằng kg.
  - Lượng calories tiêu thụ mỗi ngày.
  - Lượng calories thải ra nhờ các bài tập: đi bộ, chạy.
- Thu thập data: cân nặng và lượng calo tiêu thụ trên bản thân được lưu lại mỗi ngày.
- Xử lý data:
  - Lượng calories được chuyển về cùng đơn vị cân nặng, và từ đó quy đổi calo thành số lượng cân nặng thay đổi ước tính.
  - Data được số hóa và chuyển thành dạng file csv.

### Ví dụ 3:

- Input:
  - Diện tích
  - Số phòng, tuổi căn nhà, số bếp lửa.
- Thu thập data: Thông số cùng giá của 20 căn nhà.
- Xử lý data:
  - Dựa vào các dữ kiện trên để tìm ra mối liên hệ tuyến tính giữa giá nhà với các thông số của căn nhà. Từ đó ta có thể dự đoán giá của căn nhà bất kỳ
  - yˆ= w0 + w1*x1 + w2*x2 + w3*x3 + w4*x4
    với yˆ là giá dự đoán của căn nhà diện tích x1, có x2 phòng, đã xây dựng được x3 năm và có x4 bếp lửa.
