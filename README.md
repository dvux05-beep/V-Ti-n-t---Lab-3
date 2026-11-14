# ESP32 FIRE ALARM SYSTEM USING FREERTOS AND MQTT

## 1. Giới thiệu
Đề tài xây dựng hệ thống cảnh báo cháy sử dụng ESP32, FreeRTOS và MQTT.

Hệ thống sử dụng cảm biến MQ2 để phát hiện khí gas/khói và DS18B20 để đo nhiệt độ. Dữ liệu được truyền lên MQTT Broker và hiển thị trên Website.

## 2. Chức năng
- Đọc dữ liệu cảm biến MQ2 và DS18B20.
- Sử dụng FreeRTOS với 3 Task.
- Sử dụng Queue để trao đổi dữ liệu giữa các Task.
- Truyền dữ liệu thông qua MQTT.
- Hiển thị dữ liệu trên Website.
- Điều khiển quạt và máy bơm bằng chế độ AUTO/MANUAL.

## 3. Công nghệ sử dụng
- ESP32 DevKit V1
- FreeRTOS
- MQTT – HiveMQ Broker
- HTML, CSS, JavaScript
- MQTT.js
- Wokwi Simulator

## 4. Cấu trúc dự án
- Report/: Báo cáo thực hành.
- Wokwi/: Code ESP32 và sơ đồ mạch mô phỏng.
- Web/: Mã nguồn giao diện Website.

## 5. Link mô phỏng Wokwi
https://wokwi.com/projects/480639306343471105

## 6. Hướng dẫn chạy
1. Truy cập đường dẫn Wokwi ở trên.
2. Chạy mô phỏng ESP32.
3. Mở thư mục Web và chạy index.html bằng Live Server.
4. Kiểm tra dữ liệu cảm biến trên Website.
5. Chuyển sang MANUAL để thử điều khiển quạt và máy bơm.

## 7. Ngưỡng điều khiển
- Khí gas MQ2: 1800 ADC.
- Nhiệt độ DS18B20: 50°C.

## 8. Tác giả
Sinh viên: Vũ Tiến Đạt
