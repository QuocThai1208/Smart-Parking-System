🅿️ Smart Parking System v2
Hệ thống quản lý đỗ xe thông minh tự động hóa việc nhận diện biển số, khuôn mặt và thông báo thời gian thực. Hệ thống sử dụng Pipeline AI để xử lý hình ảnh và tích hợp thông báo qua WebSocket/Notifee.

🚀 Tính năng cốt lõi
•	AI Camera Integration: Tự động nhận diện loại xe, hãng xe, màu sắc và biển số từ ảnh chụp đầu xe.
•	Facial Verification: Nhận diện khuôn mặt chủ xe để xác thực ra/vào hầm.
•	Real-time Notifications: Thông báo trạng thái đỗ xe, cảnh báo quá giờ qua WebSocket và Notifee (Expo Go).
•	Automated Fee Calculation: Tự động tính toán phí gửi xe dựa trên loại phương tiện và thời gian gửi.
•	Cross-platform App: Ứng dụng di động phát triển bằng React Native (Expo).
🛠 Tech Stack
•	Backend: Django, Django Rest Framework, Django Channels (WebSocket).
•	Database: PostgreSQL, Redis (Message Broker cho Celery).
•	Task Queue: Celery & Celery Beat (Xử lý tác vụ AI nặng và lịch trình).
•	AI Services: FastAPI, DeepFace/InsightFace (Nhận diện khuôn mặt), OCR (Nhận diện biển số).
•	Mobile App: React Native, Expo, Notifee/Expo-Notifications.
•	DevOps: Docker & Docker Compose, Nginx, Ngrok (Tunneling).

🌐 Đường dẫn hệ thống
•	Trang quản lý: http://160.191.50.68:3000/
•	Trang admin: http://160.191.50.68:8000/admin/
•	Tài liệu api: http://160.191.50.68:8000/swagger/


🔑 Tài khoản trải nghiệm (Demo)
•	Trang quản lý: Tài khoản: thai, mật khẩu: thai1234
•	Trang admin: Tài khoản: admin, mật khẩu: admin


