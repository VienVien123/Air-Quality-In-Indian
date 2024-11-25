# Mô Hình Vector AutoRegression (VAR) 

## Mục Lục
1. [Vector AutoRegression là gì?](#vector-autoregression-là-gì)
2. [Ứng Dụng của Mô Hình VAR](#ứng-dụng-của-mô-hình-var)
3. [Ưu Điểm](#ưu-điểm)
4. [Hạn Chế](#hạn-chế)
5. [Tham Khảo](#tham-khảo)
6. [Analyst AQI - INDIA](#analyst-aqi---india)

---

## Vector AutoRegression là gì?
Mô hình **Vector AutoRegression (VAR)** là một công cụ thống kê được sử dụng để dự báo sự thay đổi của các chuỗi thời gian có sự liên kết với nhau. Mô hình VAR phù hợp để nghiên cứu các mối quan hệ động giữa nhiều biến bằng cách sử dụng các giá trị quá khứ của chúng.

VAR được ứng dụng rộng rãi trong các lĩnh vực như kinh tế, tài chính, và khoa học môi trường. Một ví dụ là dự đoán mức độ ô nhiễm không khí dựa trên dữ liệu lịch sử của các yếu tố như PM2.5, CO, và NO2.

---

## Ứng Dụng của Mô Hình VAR
- **Kinh Tế và Tài Chính**: Dự báo lãi suất, tỷ giá, và các chỉ số kinh tế như GDP, lạm phát, và tỷ lệ thất nghiệp.
- **Khoa Học Môi Trường**: Dự báo mức độ ô nhiễm bằng cách phân tích đồng thời nhiều chất ô nhiễm.
- **Khoa Học Xã Hội**: Nghiên cứu mối quan hệ giữa các yếu tố như giáo dục, thu nhập, và tỷ lệ tội phạm theo thời gian.

---

## Ưu Điểm
- **Phân Tích Đa Biến**: VAR có khả năng phân tích mối quan hệ giữa nhiều biến, không giống các mô hình chuỗi thời gian đơn biến.
- **Dự Báo Tự Động**: Khi đã thiết lập, mô hình có thể tự động tạo dự báo mà không cần phải hiểu rõ chi tiết về các mối quan hệ giữa các biến.
- **Không Yêu Cầu Xác Định Quan Hệ Nhân Quả**: VAR tự động học các mối quan hệ giữa các biến mà không cần xác định trước các mối quan hệ nhân quả.

---

## Hạn Chế
- **Phức Tạp Khi Có Nhiều Biến**: Khi có nhiều biến, mô hình trở nên phức tạp và dễ dẫn đến tình trạng quá khớp.
- **Yêu Cầu Tính Dừng**: Dữ liệu cần có tính dừng, yêu cầu quá trình tiền xử lý như lấy sai phân.
- **Dự Báo Ngắn Hạn**: VAR phù hợp cho dự báo ngắn hạn, nhưng có thể gặp khó khăn khi dự báo dài hạn với các xu hướng hoặc chu kỳ phức tạp.

---

## Tham Khảo
- [Tài liệu Statsmodels](https://www.statsmodels.org/stable/vector_ar.html)
- [Wikipedia - Vector Autoregression](https://en.wikipedia.org/wiki/Vector_autoregression)
- [GeeksforGeeks - Vector Autoregression (VAR)](https://www.geeksforgeeks.org/vector-autoregression-var-for-multivariate-time-series/) 
---

## Analyst AQI - INDIA
Dưới đây là thông tin tóm tắt về dữ liệu và các phân tích chỉ số ô nhiễm ở Ấn Độ:

- **Nguồn Dữ Liệu**: Toàn bộ dữ liệu được lấy từ "India Air Quality Data" của Shruti Bhargava.
- **Mục Đích**: Dữ liệu này phân tích và chia sẻ chủ yếu về tình trạng ô nhiễm tại các tiểu bang của Ấn Độ trong nhiều năm.
- **Nội Dung Phân Tích**: Tại đây, dữ liệu được xử lý, các chỉ số ô nhiễm của các cột như SO2, NO2, SPM, RSPM được tính toán và sử dụng để đánh giá mức độ ô nhiễm dựa trên công thức tính chỉ số AQI và phân chia mức độ ô nhiễm.

---

