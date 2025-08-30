# Tai-va-chien
Xe Robot điều khiển sử dụng FreeRTOS
GVHD: Lê Duy Hùng

SVTH: Huỳnh Minh Chiến, Trần Văn Tài

#Giới thiệu 
Dự án này hiện thực một xe robot 4 bánh điều khiển từ xa sử dụng vi điều khiển ESP32 và hệ điều hành thời gian thực FreeRTOS. Xe được trang bị kết nối Bluetooth/WiFi để nhận lệnh từ ứng dụng điện thoại thông minh, đồng thời điều khiển 4 động cơ thông qua mạch cầu H (L298N). Hệ thống áp dụng lập trình đa luồng giúp quản lý đồng thời nhiều tác vụ như nhận lệnh, xử lý tín hiệu và điều khiển chuyển động một cách ổn định và hiệu quả.

#phần cứng sử dụng 
ESP32 DevKit V1: Bộ xử lý trung tâm.
HC-05 Bluetooth Module: Kết nối với điện thoại trong phạm vi ngắn.
L298N Motor Driver: Điều khiển 4 động cơ DC.
Động cơ DC 6V + bánh xe: 4 bánh với cấu hình differential drive.
Pin Li-ion 18650 + mạch bảo vệ: Nguồn cho robot.
Khung robot 4 bánh (chassis): Hỗ trợ lắp ráp.

#Phần mềm và công nghệ
Ngôn ngữ: C/C++
IDE: Arduino IDE 
Hệ điều hành thời gian thực: FreeRTOS
Thư viện cần thiết:DabbleESP32,.ESP32 Board Package
Ứng dụng di động cần thiết:Dabble 


#Cách chạy dự án
Cài đặt Arduino IDE
Cài thư viện cần thiết 
Kết nối ESP32 với máy tính qua cổng USB.
Cấp nguồn cho robot và đặt trên mặt phẳng.
Kết nối  bluetooth qua app đabble 

