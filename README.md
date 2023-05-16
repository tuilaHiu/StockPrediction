# StockPrediction
ỨNG DỤNG MÔ HÌNH LSTM ĐỂ DỰ ĐOÁN GIÁ CỔ PHIẾU FPT

Lý thuyết về mô hình LSTM có thể tham khảo tại: https://nttuan8.com/bai-14-long-short-term-memory-lstm/

File FPT.csv bao gồm các ngày giờ, các chỉ số cơ bản và khối lượng giao dịch của cổ phiếu FPT từ ngày 25/12/2018 đến ngày 22/12/2020, thời gian giao dịch từ 9h15 đến 14h46
Data không đầy đủ về thời gian nên cần xử lý bằng cách chèn thêm dữ liệu bị thiếu, số liệu các cột sẽ được copy lại từ hàng gần nhất

Ta sẽ sử dụng dữ liệu có 7 ngày để dự đoán cho 1 ngày kế tiếp
Sau khi train, giá trị dự đoán thể hiện bằng hình sau: 
![FPTPrediction](https://github.com/tuilaHiu/StockPrediction/assets/129571170/b422c161-e6f9-45c6-ba98-c477c33e1826)

Đồ thị thể hiện độ biến động (giá trị thực - giá trị dự đoán) lúc 14h46
![Stock_price_volatility_closes_at_14h46](https://github.com/tuilaHiu/StockPrediction/assets/129571170/51e9d045-e08e-407f-b514-38ecebfd4664)

