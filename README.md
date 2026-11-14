# lap-trinh-nhung-esp32
He thong canh bao khi gas va nhiet do su dung ESP32 FreeRTOS MQTT
# BÀI TẬP LẬP TRÌNH NHÚNG

## Đề tài
Xây dựng hệ thống cảnh báo khí gas và nhiệt độ sử dụng ESP32, FreeRTOS và MQTT.

## 1. Phần cứng
- ESP32
- Cảm biến MQ2
- Cảm biến DHT22
- LED xanh
- LED đỏ

## 2. Công nghệ sử dụng
- Arduino IDE
- Wokwi Simulator
- FreeRTOS
- MQTT
- HTML, CSS, JavaScript

## 3. Chức năng
- Đọc dữ liệu khí gas từ MQ2.
- Đọc nhiệt độ từ DHT22.
- Sử dụng FreeRTOS để quản lý các Task.
- Sử dụng Queue để truyền dữ liệu giữa các Task.
- Gửi dữ liệu lên MQTT Broker.
- Hiển thị dữ liệu và điều khiển thiết bị qua Website.

## 4. Cấu trúc thư mục
- main.ino: Chương trình ESP32.
- index.html: Giao diện Website.
- libraries.txt: Danh sách thư viện.
- Bao_cao.pdf: Báo cáo thực hành.
- images/: Hình ảnh kết quả mô phỏng.

## 5. Mô phỏng
Link Wokwi: https://wokwi.com/projects/480668353592368129
